swagger: "2.0"
x-collection-name: AWS OpsWorks
x-complete: 1
info:
  title: AWS OpsWorks API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DescribeElasticLoadBalancers:
    get:
      summary: Describe Elastic Load Balancers
      description: Describes a stack's Elastic Load Balancing instances.
      operationId: describeElasticLoadBalancers
      x-api-path-slug: actiondescribeelasticloadbalancers-get
      parameters:
      - in: query
        name: LayerIds
        description: A list of layer IDs
        type: string
      - in: query
        name: StackId
        description: A stack ID
        type: string
      responses:
        200:
          description: OK
      tags:
      - Describe
      - Elastic
      - Load
      - Balancers