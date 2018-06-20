---
swagger: "2.0"
x-collection-name: Azure Virtual Network
x-complete: 1
info:
  title: NetworkManagementClient
  description: the-microsoft-azure-network-management-api-provides-a-restful-set-of-web-services-that-interact-with-microsoft-azure-networks-service-to-manage-your-network-resources--the-api-has-entities-that-capture-the-relationship-between-an-end-user-and-the-microsoft-azure-networks-service-
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
  /subscriptions/{subscriptionId}/providers/Microsoft.Network/loadBalancers:
    get:
      summary: Load Balancers List All
      description: Gets all the load balancers in a subscription.
      operationId: LoadBalancers_ListAll
      x-api-path-slug: subscriptionssubscriptionidprovidersmicrosoft-networkloadbalancers-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Load Balancers All
  /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/loadBalancers:
    get:
      summary: Load Balancers List
      description: Gets all the load balancers in a resource group.
      operationId: LoadBalancers_List
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networkloadbalancers-get
      parameters:
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
---