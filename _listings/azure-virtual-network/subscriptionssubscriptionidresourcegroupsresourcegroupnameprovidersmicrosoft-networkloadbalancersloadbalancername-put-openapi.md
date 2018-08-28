---
swagger: "2.0"
x-collection-name: Azure Virtual Network
x-complete: 0
info:
  title: Azure Virtual Network API Load Balancers Create Or Update
  description: Creates or updates a load balancer.
  version: 1.0.0
host: management.azure.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/loadBalancers/{loadBalancerName}:
    delete:
      summary: Load Balancers Delete
      description: Deletes the specified load balancer.
      operationId: LoadBalancers_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networkloadbalancersloadbalancername-delete
      parameters:
      - in: path
        name: loadBalancerName
        description: The name of the load balancer
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      responses:
        200:
          description: OK
      tags:
      - Load Balancers
    get:
      summary: Load Balancers Get
      description: Gets the specified load balancer.
      operationId: LoadBalancers_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networkloadbalancersloadbalancername-get
      parameters:
      - in: query
        name: $expand
        description: Expands referenced resources
      - in: path
        name: loadBalancerName
        description: The name of the load balancer
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      responses:
        200:
          description: OK
      tags:
      - Load Balancers
    put:
      summary: Load Balancers Create Or Update
      description: Creates or updates a load balancer.
      operationId: LoadBalancers_CreateOrUpdate
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networkloadbalancersloadbalancername-put
      parameters:
      - in: path
        name: loadBalancerName
        description: The name of the load balancer
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: Parameters supplied to the create or update load balancer operation
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      responses:
        200:
          description: OK
      tags:
      - Load Balancers
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---