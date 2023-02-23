## Introduction

## Cloud research
### Amazon S3 – Replication (CRR & SRR)
• Must enable Versioning in source and destination buckets

• Cross-Region Replication (CRR)

• Same-Region Replication (SRR)

• Buckets can be in different AWS accounts

• Copying is asynchronous

• Must give proper IAM permissions to S3

• Use cases:

  • CRR – compliance, lower latency access, replication across accounts
  
  • SRR – log aggregation, live replication between production and test
    accounts
    
### S3 Storage Classes

• Amazon S3 Standard - General Purpose

• Amazon S3 Standard-Infrequent Access (IA)

• Amazon S3 One Zone-Infrequent Access

• Amazon S3 Glacier Instant Retrieval

• Amazon S3 Glacier Flexible Retrieval

• Amazon S3 Glacier Deep Archive

• Amazon S3 Intelligent Tiering

• Can move between classes manually or using S3 Lifecycle configurations


### S3 Durability and Availability

• Durability:

  • High durability (99.999999999%, 11 9’s) of objects across multiple AZ
  
  • If you store 10,000,000 objects with Amazon S3, you can on average expect to
    incur a loss of a single object once every 10,000 years
    
  • Same for all storage classes
  
• Availability:

  • Measures how readily available a service is
  
  • Varies depending on storage class
  
  • Example: S3 standard has 99.99% availability = not available 53 minutes a year
  
  
### S3 Standard – General Purpose

• 99.99% Availability

• Used for frequently accessed data

• Low latency and high throughput

• Sustain 2 concurrent facility failures

• Use Cases: Big Data analytics, mobile & gaming applications, content
distribution…

### S3 Storage Classes – Infrequent Access

• For data that is less frequently accessed, but requires rapid access when needed

• Lower cost than S3 Standard

• Amazon S3 Standard-Infrequent Access (S3 Standard-IA)

  • 99.9% Availability
  
  • Use cases: Disaster Recovery, backups

• Amazon S3 One Zone-Infrequent Access (S3 One Zone-IA)

  • High durability (99.999999999%) in a single AZ; data lost when AZ is destroyed
  
  • 99.5% Availability
  
  • Use Cases: Storing secondary backup copies of on-premise data, or data you can recreate    
    
### Amazon S3 Glacier Storage Classes
• Low-cost object storage meant for archiving / backup

• Pricing: price for storage + object retrieval cost

• Amazon S3 Glacier Instant Retrieval

  • Millisecond retrieval, great for data accessed once a quarter
  
  • Minimum storage duration of 90 days

• Amazon S3 Glacier Flexible Retrieval (formerly Amazon S3 Glacier): 

  • Expedited (1 to 5 minutes), Standard (3 to 5 hours), Bulk (5 to 12 hours) – free
  
  • Minimum storage duration of 90 days

• Amazon S3 Glacier Deep Archive – for long term storage:

  • Standard (12 hours), Bulk (48 hours)
  
  • Minimum storage duration of 180 days


  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  




