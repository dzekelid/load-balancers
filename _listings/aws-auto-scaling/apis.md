---
name: AWS Auto Scaling
x-slug: aws-auto-scaling
description: Auto Scaling helps you maintain application availability and allows you
  to scale yourAmazon EC2capacity up or down automatically according to conditions
  you define. You can use Auto Scaling to help ensure that you are running your desired
  number of Amazon EC2 instances. Auto Scaling can also automatically increase the
  number of Amazon EC2 instances during demand spikes to maintain performance and
  decrease capacity during lulls to reduce costs. Auto Scaling is well suited both
  to applications that have stable demand patterns or that experience hourly, daily,
  or weekly variability in usage.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2_AutoScaling.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Load Balancers
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/load-balancers/master/_listings/aws-auto-scaling/apis.md
specificationVersion: "0.14"
apis:
- name: AWS Auto Scaling API Attach Load Balancers
  x-api-slug: aws-auto-scaling-api
  description: Attaches one or more Classic load balancers to the specified Auto Scaling
    group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2_AutoScaling.png
  humanURL: https://aws.amazon.com/autoscaling/
  baseURL: ://///?Action=AttachLoadBalancers
  tags: Load Balancers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/load-balancers/master/_listings/aws-auto-scaling/actionattachloadbalancers-get-openapi.md
- name: AWS Auto Scaling API Attach Load Balancer Target Groups
  x-api-slug: aws-auto-scaling-api
  description: Attaches one or more target groups to the specified Auto Scaling group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2_AutoScaling.png
  humanURL: https://aws.amazon.com/autoscaling/
  baseURL: ://///?Action=AttachLoadBalancerTargetGroups
  tags: Load Balancers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/load-balancers/master/_listings/aws-auto-scaling/actionattachloadbalancertargetgroups-get-openapi.md
- name: AWS Auto Scaling API Describe Load Balancers
  x-api-slug: aws-auto-scaling-api
  description: Describes the load balancers for the specified Auto Scaling group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2_AutoScaling.png
  humanURL: https://aws.amazon.com/autoscaling/
  baseURL: ://///?Action=DescribeLoadBalancers
  tags: Load Balancers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/load-balancers/master/_listings/aws-auto-scaling/actiondescribeloadbalancers-get-openapi.md
- name: AWS Auto Scaling API Describe Load Balancer Target Groups
  x-api-slug: aws-auto-scaling-api
  description: Describes the target groups for the specified Auto Scaling group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2_AutoScaling.png
  humanURL: https://aws.amazon.com/autoscaling/
  baseURL: ://///?Action=DescribeLoadBalancerTargetGroups
  tags: Load Balancers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/load-balancers/master/_listings/aws-auto-scaling/actiondescribeloadbalancertargetgroups-get-openapi.md
- name: AWS Auto Scaling API Detach Load Balancers
  x-api-slug: aws-auto-scaling-api
  description: Detaches one or more Classic load balancers from the specified Auto
    Scaling group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2_AutoScaling.png
  humanURL: https://aws.amazon.com/autoscaling/
  baseURL: ://///?Action=DetachLoadBalancers
  tags: Load Balancers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/load-balancers/master/_listings/aws-auto-scaling/actiondetachloadbalancers-get-openapi.md
- name: AWS Auto Scaling API Detach Load Balancer Target Groups
  x-api-slug: aws-auto-scaling-api
  description: Detaches one or more target groups from the specified Auto Scaling
    group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2_AutoScaling.png
  humanURL: https://aws.amazon.com/autoscaling/
  baseURL: ://///?Action=DetachLoadBalancerTargetGroups
  tags: Load Balancers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/load-balancers/master/_listings/aws-auto-scaling/actiondetachloadbalancertargetgroups-get-openapi.md
- name: AWS Auto Scaling API
  x-api-slug: aws-auto-scaling-api
  description: Auto Scaling helps you maintain application availability and allows
    you to scale yourAmazon EC2capacity up or down automatically according to conditions
    you define. You can use Auto Scaling to help ensure that you are running your
    desired number of Amazon EC2 instances. Auto Scaling can also automatically increase
    the number of Amazon EC2 instances during demand spikes to maintain performance
    and decrease capacity during lulls to reduce costs. Auto Scaling is well suited
    both to applications that have stable demand patterns or that experience hourly,
    daily, or weekly variability in usage.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2_AutoScaling.png
  humanURL: https://aws.amazon.com/autoscaling/
  baseURL: :///
  tags: Load Balancers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/load-balancers/master/_listings/aws-auto-scaling/openapi.md
x-common:
- type: x-articles
  url: http://developer.amazonwebservices.com/connect/kbcategory.jspa?categoryID=100
- type: x-change-log
  url: http://developer.amazonwebservices.com/connect/kbcategory.jspa?categoryID=86
- type: x-code
  url: http://developer.amazonwebservices.com/connect/kbcategory.jspa?categoryID=85
- type: x-command-line-interface
  url: http://docs.aws.amazon.com/cli/latest/reference/autoscaling/index.html
- type: x-documentation
  url: http://docs.aws.amazon.com/AutoScaling/latest/APIReference/
- type: x-forum
  url: http://developer.amazonwebservices.com/connect/forum.jspa?forumID=30
- type: x-getting-started
  url: https://aws.amazon.com/autoscaling/getting-started/
- type: x-pricing
  url: https://aws.amazon.com/autoscaling/pricing/
- type: x-service-health
  url: http://status.aws.amazon.com/
- type: x-website
  url: https://aws.amazon.com/autoscaling/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---