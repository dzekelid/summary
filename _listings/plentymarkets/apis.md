---
name: Plentymarkets
x-slug: plentymarkets
description: plentymarkets is an all-in-one e-commerce ERP solution, which combines
  a comprehensive stock management system with a versatile shop system and effortless
  multichannel sales. Thanks to comprehensive functions and interfaces that include
  all steps of the e-commerce value chain, you can use the cloud based software to
  completely automate all of your e-business processes as well as your companys own
  individual processes.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
x-kinRank: "7"
x-alexaRank: ""
tags: Summary
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/summary/master/_listings/plentymarkets/apis.md
specificationVersion: "0.14"
apis:
- name: plentymarkets REST-API - Create an order summary
  x-api-slug: restaccountsorder-summaries-post
  description: Create an order summary.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/summary/master/_listings/plentymarkets/restaccountsorder-summaries-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/summary/master/_listings/plentymarkets/restaccountsorder-summaries-post-openapi.md
- name: plentymarkets REST-API - Get an order summary by the contact ID
  x-api-slug: restaccountsorder-summariescontactscontactid-get
  description: Gets an order summary. The ID of the contact must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/summary/master/_listings/plentymarkets/restaccountsorder-summariescontactscontactid-get-openapi.md
- name: plentymarkets REST-API - Get an order summary by the address ID
  x-api-slug: restaccountsorder-summariesordersaddressid-get
  description: Gets an order summary. The ID of the address must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/summary/master/_listings/plentymarkets/restaccountsorder-summariesordersaddressid-get-openapi.md
- name: plentymarkets REST-API - Delete an order summary
  x-api-slug: restaccountsorder-summariesordersummaryid-delete
  description: Deletes an order summary. The ID of the order summary must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/summary/master/_listings/plentymarkets/restaccountsorder-summariesordersummaryid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/summary/master/_listings/plentymarkets/restaccountsorder-summariesordersummaryid-delete-openapi.md
- name: plentymarkets REST-API - Get an order summary by the order summary ID
  x-api-slug: restaccountsorder-summariesordersummaryid-get
  description: Gets an order summary. The ID of the order summary must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/summary/master/_listings/plentymarkets/restaccountsorder-summariesordersummaryid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/summary/master/_listings/plentymarkets/restaccountsorder-summariesordersummaryid-get-openapi.md
- name: plentymarkets REST-API - Update an order summary
  x-api-slug: restaccountsorder-summariesordersummaryid-put
  description: Updates an order summary. The ID of the order summary must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/summary/master/_listings/plentymarkets/restaccountsorder-summariesordersummaryid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/summary/master/_listings/plentymarkets/restaccountsorder-summariesordersummaryid-put-openapi.md
- name: plentymarkets REST-API - List order summaries
  x-api-slug: restaccountsorder-summaries-get
  description: List order summaries.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/summary/master/_listings/plentymarkets/restaccountsorder-summaries-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/summary/master/_listings/plentymarkets/restaccountsorder-summaries-get-openapi.md
- name: plentymarkets REST-API - List document accounting summaries
  x-api-slug: restordersdocumentsaccounting-summary-get
  description: Lists document accounting summaries. A document accounting summary
    is saved along with each reversal document (for invoice and credit note). It contains
    accounting information about the order for this point in time. The summary is
    saved because an order can be updated after a reversal_document is generated.
    The information about the order before the update is needed for accounting.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/summary/master/_listings/plentymarkets/restordersdocumentsaccounting-summary-get-openapi.md
- name: plentymarkets REST-API - List order summaries
  x-api-slug: restaccountsorder-summaries-get
  description: List order summaries.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/summary/master/_listings/plentymarkets/restaccountsorder-summaries-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/summary/master/_listings/plentymarkets/restaccountsorder-summaries-get-openapi.md
- name: plentymarkets REST-API - List document accounting summaries
  x-api-slug: restordersdocumentsaccounting-summary-get
  description: Lists document accounting summaries. A document accounting summary
    is saved along with each reversal document (for invoice and credit note). It contains
    accounting information about the order for this point in time. The summary is
    saved because an order can be updated after a reversal_document is generated.
    The information about the order before the update is needed for accounting.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/summary/master/_listings/plentymarkets/restordersdocumentsaccounting-summary-get-openapi.md
- name: plentymarkets REST-API - List document accounting summaries
  x-api-slug: restordersdocumentsaccounting-summary-get
  description: Lists document accounting summaries. A document accounting summary
    is saved along with each reversal document (for invoice and credit note). It contains
    accounting information about the order for this point in time. The summary is
    saved because an order can be updated after a reversal_document is generated.
    The information about the order before the update is needed for accounting.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/summary/master/_listings/plentymarkets/restordersdocumentsaccounting-summary-get-openapi.md
- name: plentymarkets REST-API - List order summaries
  x-api-slug: restaccountsorder-summaries-get
  description: List order summaries.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/summary/master/_listings/plentymarkets/restaccountsorder-summaries-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/summary/master/_listings/plentymarkets/restaccountsorder-summaries-get-openapi.md
x-common:
- type: x-blog-rss
  url: https://www.plentymarkets.co.uk/?ActionCall=WebActionRSS&rrss_id=1
- type: x-github
  url: https://github.com/plentymarkets
- type: x-twitter
  url: https://twitter.com/plentymarketsuk
- type: x-website
  url: http://www.plentymarkets.co.uk
- type: x-api-gallery
  url: http://pivotal.tracker.api.gallery.streamdata.io
- type: x-api-stack
  url: http://plentymarkets.stack.network
- type: x-blog
  url: https://www.plentymarkets.co.uk/blog/
- type: x-pricing
  url: https://www.plentymarkets.co.uk/prices/
- type: x-website
  url: https://www.plentymarkets.co.uk
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---