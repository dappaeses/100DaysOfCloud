#introduction
- aws snow course udemy
## cloud research
### AWS Snow Family
• Highly-secure, portable devices to collect and process data at the edge,
  and migrate data into and out of AWS
  
• Data migration: Snowcone,Snowball Edge,Snowmobile
• Edge computing: Snowcone,Snowball Edge

### Snowball Edge (for data transfers)
• Physical data transport solution: move TBs or PBs of data in or out of AWS

• Alternative to moving data over the network (and paying network fees)

• Pay per data transfer job • Provide block storage and Amazon S3-compatible object storage

• Snowball Edge Storage Optimized 

  • 80 TB of HDD capacity for block volume and S3 compatible object
    storage

• Snowball Edge Compute Optimized 
  • 42 TB of HDD capacity for block volume and S3 compatible object
    storage

• Use cases: large data cloud migrations, DC decommission, disaster
recovery

### AWS Snowcone
• Small, portable computing, anywhere, rugged & secure, withstands harsh environments

• Light (4.5 pounds, 2.1 kg) 

• Device used for edge computing, storage, and data transfer

• 8 TBs of usable storage

• Use Snowcone where Snowball does not fit (space-constrained environment)

• Must provide your own battery / cables 

• Can be sent back to AWS offline, or connect it to internet and use AWS DataSync to send data

### AWS Snowmobile
• Transfer exabytes of data (1 EB = 1,000 PB = 1,000,000 TBs)

• Each Snowmobile has 100 PB of capacity (use multiple in parallel)

• High security: temperature controlled, GPS, 24/7 video surveillance

• Better than Snowball if you transfer more than 10 PB

### Snow Family – Usage Process
1. Request Snowball devices from the AWS console for delivery
2. Install the snowball client / AWS OpsHub on your servers
3. Connect the snowball to your servers and copy files using the client
4. Ship back the device when you’re done (goes to the right AWS facility)
5. Data will be loaded into an S3 bucket
6. Snowball is completely wiped


















