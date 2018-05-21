---
swagger: "2.0"
x-collection-name: AWS Snowball
x-complete: 0
info:
  title: AWS Snowball API List Cluster Jobs
  version: 1.0.0
  description: Returns an array of JobListEntry objects of the specified length.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=CancelCluster:
    get:
      summary: Cancel Cluster
      description: Cancels a cluster job.
      operationId: cancelCluster
      x-api-path-slug: actioncancelcluster-get
      parameters:
      - in: query
        name: ClusterId
        description: The 39-character ID for the cluster that you want to cancel,
          for example        CID123e4567-e89b-12d3-a456-426655440000
        type: string
      responses:
        200:
          description: OK
      tags:
      - Clusters
  /?Action=CancelJob:
    get:
      summary: Cancel Job
      description: Cancels the specified job.
      operationId: cancelJob
      x-api-path-slug: actioncanceljob-get
      parameters:
      - in: query
        name: JobId
        description: The 39-character job ID for the job that you want to cancel,
          for example        JID123e4567-e89b-12d3-a456-426655440000
        type: string
      responses:
        200:
          description: OK
      tags:
      - Jobs
  /?Action=CreateAddress:
    get:
      summary: Create Address
      description: Creates an address for a Snowball to be shipped to.
      operationId: createAddress
      x-api-path-slug: actioncreateaddress-get
      parameters:
      - in: query
        name: Address
        description: The address that you want the Snowball shipped to
        type: string
      responses:
        200:
          description: OK
      tags:
      - Addresses
  /?Action=CreateCluster:
    get:
      summary: Create Cluster
      description: Creates an empty cluster.
      operationId: createCluster
      x-api-path-slug: actioncreatecluster-get
      parameters:
      - in: query
        name: AddressId
        description: The ID for the address that you want the cluster shipped to
        type: string
      - in: query
        name: Description
        description: An optional description of this specific cluster, for example
          Environmental Data        Cluster-01
        type: string
      - in: query
        name: JobType
        description: The type of job for this cluster
        type: string
      - in: query
        name: KmsKeyARN
        description: The KmsKeyARN value that you want to associate with this cluster
        type: string
      - in: query
        name: Notification
        description: The Amazon Simple Notification Service (Amazon SNS) notification
          settings for this      cluster
        type: string
      - in: query
        name: Resources
        description: The resources associated with the cluster job
        type: string
      - in: query
        name: RoleARN
        description: The RoleARN that you want to associate with this cluster
        type: string
      - in: query
        name: ShippingOption
        description: The shipping speed for each node in this cluster
        type: string
      - in: query
        name: SnowballType
        description: The type of AWS Snowball appliance to use for this cluster
        type: string
      responses:
        200:
          description: OK
      tags:
      - Clusters
  /?Action=CreateJob:
    get:
      summary: Create Job
      description: |-
        Creates a job to import or export data between Amazon S3 and your on-premises data
              center.
      operationId: createJob
      x-api-path-slug: actioncreatejob-get
      parameters:
      - in: query
        name: AddressId
        description: The ID for the address that you want the Snowball shipped to
        type: string
      - in: query
        name: ClusterId
        description: The ID of a cluster
        type: string
      - in: query
        name: Description
        description: Defines an optional description of this specific job, for example
          Important        Photos 2016-08-11
        type: string
      - in: query
        name: JobType
        description: Defines the type of job that youre creating
        type: string
      - in: query
        name: KmsKeyARN
        description: The KmsKeyARN that you want to associate with this job
        type: string
      - in: query
        name: Notification
        description: Defines the Amazon Simple Notification Service (Amazon SNS) notification
          settings for      this job
        type: string
      - in: query
        name: Resources
        description: Defines the Amazon S3 buckets associated with this job
        type: string
      - in: query
        name: RoleARN
        description: The RoleARN that you want to associate with this job
        type: string
      - in: query
        name: ShippingOption
        description: The shipping speed for this job
        type: string
      - in: query
        name: SnowballCapacityPreference
        description: If your job is being created in one of the US regions, you have
          the option of      specifying what size Snowball youd like for this job
        type: string
      - in: query
        name: SnowballType
        description: The type of AWS Snowball appliance to use for this job
        type: string
      responses:
        200:
          description: OK
      tags:
      - Jobs
  /?Action=DescribeAddress:
    get:
      summary: Describe Address
      description: |-
        Takes an AddressId and returns specific details about that address in the
              form of an Address object.
      operationId: describeAddress
      x-api-path-slug: actiondescribeaddress-get
      parameters:
      - in: query
        name: AddressId
        description: The automatically generated ID for a specific address
        type: string
      responses:
        200:
          description: OK
      tags:
      - Addresses
  /?Action=DescribeAddresses:
    get:
      summary: Describe Addresses
      description: Returns a specified number of ADDRESS objects.
      operationId: describeAddresses
      x-api-path-slug: actiondescribeaddresses-get
      parameters:
      - in: query
        name: MaxResults
        description: The number of ADDRESS objects to return
        type: string
      - in: query
        name: NextToken
        description: HTTP requests are stateless
        type: string
      responses:
        200:
          description: OK
      tags:
      - Addresses
  /?Action=DescribeCluster:
    get:
      summary: Describe Cluster
      description: |-
        Returns information about a specific cluster including shipping information, cluster
              status, and other important metadata.
      operationId: describeCluster
      x-api-path-slug: actiondescribecluster-get
      parameters:
      - in: query
        name: ClusterId
        description: The automatically generated ID for a cluster
        type: string
      responses:
        200:
          description: OK
      tags:
      - Clusters
  /?Action=DescribeJob:
    get:
      summary: Describe Job
      description: |-
        Returns information about a specific job including shipping information, job status,
              and other important metadata.
      operationId: describeJob
      x-api-path-slug: actiondescribejob-get
      parameters:
      - in: query
        name: JobId
        description: The automatically generated ID for a job, for example        JID123e4567-e89b-12d3-a456-426655440000
        type: string
      responses:
        200:
          description: OK
      tags:
      - Jobs
  /?Action=GetJobManifest:
    get:
      summary: Get Job Manifest
      description: |-
        Returns a link to an Amazon S3 presigned URL for the manifest file associated with the
              specified JobId value.
      operationId: getJobManifest
      x-api-path-slug: actiongetjobmanifest-get
      parameters:
      - in: query
        name: JobId
        description: The ID for a job that you want to get the manifest file for,
          for example        JID123e4567-e89b-12d3-a456-426655440000
        type: string
      responses:
        200:
          description: OK
      tags:
      - Job Manifest
  /?Action=GetJobUnlockCode:
    get:
      summary: Get Job Unlock Code
      description: Returns the UnlockCode code value for the specified job.
      operationId: getJobUnlockCode
      x-api-path-slug: actiongetjobunlockcode-get
      parameters:
      - in: query
        name: JobId
        description: The ID for the job that you want to get the UnlockCode value
          for, for      example JID123e4567-e89b-12d3-a456-426655440000
        type: string
      responses:
        200:
          description: OK
      tags:
      - Jobs
  /?Action=GetSnowballUsage:
    get:
      summary: Get Snowball Usage
      description: |-
        Returns information about the Snowball service limit for your account, and also the
              number of Snowballs your account has in use.
      operationId: getSnowballUsage
      x-api-path-slug: actiongetsnowballusage-get
      parameters:
      - in: query
        name: SnowballLimit
        description: The service limit for number of Snowballs this account can have
          at once
        type: string
      - in: query
        name: SnowballsInUse
        description: The number of Snowballs that this account is currently using
        type: string
      responses:
        200:
          description: OK
      tags:
      - Usage
  /?Action=ListClusterJobs:
    get:
      summary: List Cluster Jobs
      description: Returns an array of JobListEntry objects of the specified length.
      operationId: listClusterJobs
      x-api-path-slug: actionlistclusterjobs-get
      parameters:
      - in: query
        name: ClusterId
        description: The 39-character ID for the cluster that you want to list, for
          example        CID123e4567-e89b-12d3-a456-426655440000
        type: string
      - in: query
        name: MaxResults
        description: The number of JobListEntry objects to return
        type: string
      - in: query
        name: NextToken
        description: HTTP requests are stateless
        type: string
      responses:
        200:
          description: OK
      tags:
      - Cluster Jobs
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