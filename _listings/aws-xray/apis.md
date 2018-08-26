---
name: AWS X-Ray
x-slug: aws-xray
description: AWS X-Ray helps developers analyze and debug production, distributed
  applications, such as those built using a microservices architecture. With X-Ray,
  you can understand how your application and its underlying services are performing
  to identify and troubleshoot the root cause of performance issues and errors. X-Ray
  provides an end-to-end view of requests as they travel through your application,
  and shows a map of your applications underlying components. You can use X-Ray to
  analyze both applications in development and in production, from simple three-tier
  applications to complex microservices applications consisting of thousands of services.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-xray.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Summary
created: "2018-08-26"
modified: "2018-08-26"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/summary/master/_listings/aws-xray/apis.md
specificationVersion: "0.14"
apis:
- name: AWS X-Ray API - Get Trace Summaries
  x-api-slug: actiongettracesummaries-get
  description: |-
    Retrieves IDs and metadata for traces available for a specified time frame using an
          optional filter.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-xray.png
  humanURL: https://aws.amazon.com/xray/
  baseURL: :///
  tags: Amazon Web Services, Monitoring, Testing, Orchestration, Stack Network, API
    Service Provider, API Service Provider, API Provider, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/summary/master/_listings/aws-xray/actiongettracesummaries-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/summary/master/_listings/aws-xray/actiongettracesummaries-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://aws.workspaces.api.gallery.streamdata.io
- type: x-api-stack
  url: http://aws.xray.stack.network
- type: x-documentation
  url: http://docs.aws.amazon.com/xray/latest/api/Welcome.html
- type: x-faq
  url: https://aws.amazon.com/xray/faqs/
- type: x-getting-started
  url: https://aws.amazon.com/xray/getting-started/
- type: x-pricing
  url: https://aws.amazon.com/xray/pricing/
- type: x-website
  url: https://aws.amazon.com/xray/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---