---
name: AWS Snowball
x-slug: aws-snowball
description: Snowball is a petabyte-scale data transport solution that uses secure
  appliances totransfer large amounts of datainto and out of theAWS cloud. Using Snowball
  addresses common challenges with large-scale data transfers including high network
  costs, long transfer times, and security concerns. Transferring data with Snowball
  is simple, fast, secure, and can be as little as one-fifth the cost of high-speed
  Internet.With Snowball, you don&rsquo;t need to write any code or purchase any hardware
  to transfer your data. Simply create a job in the AWS Management Console and a Snowball
  appliance will be automatically shipped to you*. Once it arrives, attach the appliance
  to your local network, download and run the Snowball client to establish a connection,
  and then use the client to select the file directories that you want to transfer
  to the appliance. The client will then encrypt and transfer the files to the appliance
  at high speed. Once the transfer is complete and the appliance is ready to be returned,
  the E Ink shipping label will automatically update and you can track the job status
  viaAmazon Simple Notification Service (SNS), text messages, or directly in the Console.Snowball
  uses multiple layers of security designed to protect your data including tamper-resistant
  enclosures, 256-bit encryption, and an industry-standard Trusted Platform Module
  (TPM) designed to ensure both security and full chain-of-custody of your data. Once
  the data transfer job has been processed and verified, AWS performs a software erasure
  of the Snowball appliance.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSImportExportSnowball.png
x-kinRank: "10"
x-alexaRank: "0"
tags: AWS Snowball
created: "2018-08-29"
modified: "2018-08-29"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-snowball/master/_listings/aws-snowball/apis.md
specificationVersion: "0.14"
apis:
- name: AWS Snowball API - Cancel Cluster
  x-api-slug: actioncancelcluster-get
  description: Cancels a cluster job.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSImportExportSnowball.png
  humanURL: https://aws.amazon.com/snowball/
  baseURL: :///
  tags: Amazon Web Services, Data, Security, Stack Network, API Service Provider,
    API Service Provider, API Provider, Databases, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-snowball/master/_listings/aws-snowball/actioncancelcluster-get-openapi.md
- name: AWS Snowball API - Cancel Job
  x-api-slug: actioncanceljob-get
  description: Cancels the specified job.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSImportExportSnowball.png
  humanURL: https://aws.amazon.com/snowball/
  baseURL: :///
  tags: Amazon Web Services, Data, Security, Stack Network, API Service Provider,
    API Service Provider, API Provider, Databases, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-snowball/master/_listings/aws-snowball/actioncanceljob-get-openapi.md
- name: AWS Snowball API - Create Address
  x-api-slug: actioncreateaddress-get
  description: Creates an address for a Snowball to be shipped to.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSImportExportSnowball.png
  humanURL: https://aws.amazon.com/snowball/
  baseURL: :///
  tags: Amazon Web Services, Data, Security, Stack Network, API Service Provider,
    API Service Provider, API Provider, Databases, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-snowball/master/_listings/aws-snowball/actioncreateaddress-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-snowball/master/_listings/aws-snowball/actioncreateaddress-get-openapi.md
- name: AWS Snowball API - Create Cluster
  x-api-slug: actioncreatecluster-get
  description: Creates an empty cluster.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSImportExportSnowball.png
  humanURL: https://aws.amazon.com/snowball/
  baseURL: :///
  tags: Amazon Web Services, Data, Security, Stack Network, API Service Provider,
    API Service Provider, API Provider, Databases, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-snowball/master/_listings/aws-snowball/actioncreatecluster-get-openapi.md
- name: AWS Snowball API - Create Job
  x-api-slug: actioncreatejob-get
  description: |-
    Creates a job to import or export data between Amazon S3 and your on-premises data
          center.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSImportExportSnowball.png
  humanURL: https://aws.amazon.com/snowball/
  baseURL: :///
  tags: Amazon Web Services, Data, Security, Stack Network, API Service Provider,
    API Service Provider, API Provider, Databases, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-snowball/master/_listings/aws-snowball/actioncreatejob-get-openapi.md
- name: AWS Snowball API - Describe Address
  x-api-slug: actiondescribeaddress-get
  description: |-
    Takes an AddressId and returns specific details about that address in the
          form of an Address object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSImportExportSnowball.png
  humanURL: https://aws.amazon.com/snowball/
  baseURL: :///
  tags: Amazon Web Services, Data, Security, Stack Network, API Service Provider,
    API Service Provider, API Provider, Databases, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-snowball/master/_listings/aws-snowball/actiondescribeaddress-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-snowball/master/_listings/aws-snowball/actiondescribeaddress-get-openapi.md
- name: AWS Snowball API - Describe Addresses
  x-api-slug: actiondescribeaddresses-get
  description: Returns a specified number of ADDRESS objects.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSImportExportSnowball.png
  humanURL: https://aws.amazon.com/snowball/
  baseURL: :///
  tags: Amazon Web Services, Data, Security, Stack Network, API Service Provider,
    API Service Provider, API Provider, Databases, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-snowball/master/_listings/aws-snowball/actiondescribeaddresses-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-snowball/master/_listings/aws-snowball/actiondescribeaddresses-get-openapi.md
- name: AWS Snowball API - Describe Cluster
  x-api-slug: actiondescribecluster-get
  description: |-
    Returns information about a specific cluster including shipping information, cluster
          status, and other important metadata.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSImportExportSnowball.png
  humanURL: https://aws.amazon.com/snowball/
  baseURL: :///
  tags: Amazon Web Services, Data, Security, Stack Network, API Service Provider,
    API Service Provider, API Provider, Databases, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-snowball/master/_listings/aws-snowball/actiondescribecluster-get-openapi.md
- name: AWS Snowball API - Describe Job
  x-api-slug: actiondescribejob-get
  description: |-
    Returns information about a specific job including shipping information, job status,
          and other important metadata.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSImportExportSnowball.png
  humanURL: https://aws.amazon.com/snowball/
  baseURL: :///
  tags: Amazon Web Services, Data, Security, Stack Network, API Service Provider,
    API Service Provider, API Provider, Databases, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-snowball/master/_listings/aws-snowball/actiondescribejob-get-openapi.md
- name: AWS Snowball API - Get Job Manifest
  x-api-slug: actiongetjobmanifest-get
  description: |-
    Returns a link to an Amazon S3 presigned URL for the manifest file associated with the
          specified JobId value.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSImportExportSnowball.png
  humanURL: https://aws.amazon.com/snowball/
  baseURL: :///
  tags: Amazon Web Services, Data, Security, Stack Network, API Service Provider,
    API Service Provider, API Provider, Databases, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-snowball/master/_listings/aws-snowball/actiongetjobmanifest-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-snowball/master/_listings/aws-snowball/actiongetjobmanifest-get-openapi.md
- name: AWS Snowball API - Get Job Unlock Code
  x-api-slug: actiongetjobunlockcode-get
  description: Returns the UnlockCode code value for the specified job.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSImportExportSnowball.png
  humanURL: https://aws.amazon.com/snowball/
  baseURL: :///
  tags: Amazon Web Services, Data, Security, Stack Network, API Service Provider,
    API Service Provider, API Provider, Databases, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-snowball/master/_listings/aws-snowball/actiongetjobunlockcode-get-openapi.md
- name: AWS Snowball API - Get Snowball Usage
  x-api-slug: actiongetsnowballusage-get
  description: |-
    Returns information about the Snowball service limit for your account, and also the
          number of Snowballs your account has in use.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSImportExportSnowball.png
  humanURL: https://aws.amazon.com/snowball/
  baseURL: :///
  tags: Amazon Web Services, Data, Security, Stack Network, API Service Provider,
    API Service Provider, API Provider, Databases, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-snowball/master/_listings/aws-snowball/actiongetsnowballusage-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-snowball/master/_listings/aws-snowball/actiongetsnowballusage-get-openapi.md
- name: AWS Snowball API - List Cluster Jobs
  x-api-slug: actionlistclusterjobs-get
  description: Returns an array of JobListEntry objects of the specified length.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSImportExportSnowball.png
  humanURL: https://aws.amazon.com/snowball/
  baseURL: :///
  tags: Amazon Web Services, Data, Security, Stack Network, API Service Provider,
    API Service Provider, API Provider, Databases, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-snowball/master/_listings/aws-snowball/actionlistclusterjobs-get-openapi.md
- name: AWS Snowball API - List Clusters
  x-api-slug: actionlistclusters-get
  description: Returns an array of ClusterListEntry objects of the specified length.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSImportExportSnowball.png
  humanURL: https://aws.amazon.com/snowball/
  baseURL: :///
  tags: Amazon Web Services, Data, Security, Stack Network, API Service Provider,
    API Service Provider, API Provider, Databases, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-snowball/master/_listings/aws-snowball/actionlistclusters-get-openapi.md
- name: AWS Snowball API - List Jobs
  x-api-slug: actionlistjobs-get
  description: Returns an array of JobListEntry objects of the specified length.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSImportExportSnowball.png
  humanURL: https://aws.amazon.com/snowball/
  baseURL: :///
  tags: Amazon Web Services, Data, Security, Stack Network, API Service Provider,
    API Service Provider, API Provider, Databases, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-snowball/master/_listings/aws-snowball/actionlistjobs-get-openapi.md
- name: AWS Snowball API - Update Cluster
  x-api-slug: actionupdatecluster-get
  description: |-
    While a cluster's ClusterState value is in the AwaitingQuorum
          state, you can update some of the information associated with a cluster.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSImportExportSnowball.png
  humanURL: https://aws.amazon.com/snowball/
  baseURL: :///
  tags: Amazon Web Services, Data, Security, Stack Network, API Service Provider,
    API Service Provider, API Provider, Databases, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-snowball/master/_listings/aws-snowball/actionupdatecluster-get-openapi.md
- name: AWS Snowball API - Update Job
  x-api-slug: actionupdatejob-get
  description: |-
    While a job's JobState value is New, you can update some of
          the information associated with a job.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSImportExportSnowball.png
  humanURL: https://aws.amazon.com/snowball/
  baseURL: :///
  tags: Amazon Web Services, Data, Security, Stack Network, API Service Provider,
    API Service Provider, API Provider, Databases, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-snowball/master/_listings/aws-snowball/actionupdatejob-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://aws.simple.queue.service.api.gallery.streamdata.io
- type: x-api-stack
  url: http://aws.snowball.stack.network
- type: x-documentation
  url: http://docs.aws.amazon.com/snowball/latest/api-reference/api-reference.html
- type: x-faq
  url: https://aws.amazon.com/snowball/faqs/
- type: x-getting-started
  url: https://aws.amazon.com/snowball/getting-started/
- type: x-tools
  url: https://aws.amazon.com/snowball/tools/
- type: x-website
  url: https://aws.amazon.com/snowball/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---