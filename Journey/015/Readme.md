
# New post title here

## Introduction


## Cloud Research
• Launch 3rd party high-performance file systems on AWS

• Fully managed service

![image](https://user-images.githubusercontent.com/121011336/214195891-a5f71179-cd72-4c93-a1c7-a38378a94f51.png)

### Amazon FSx for Windows File Server
• A fully managed, highly reliable, and scalable Windows native shared file system

• Built on Windows File Server 

• Supports SMB protocol & Windows NTFS

• Integrated with Microsoft Active Directory

• Can be accessed from AWS or your on-premise infrastructure

![image](https://user-images.githubusercontent.com/121011336/214196064-d4be1c23-6a2c-44f7-bddc-f0baac429510.png)

### Amazon FSx for Lustre

• A fully managed, high-performance, scalable file storage for High Performance Computing (HPC)

• The name Lustre is derived from “Linux” and “cluster”

• Machine Learning, Analytics, Video Processing, Financial Modeling, …

• Scales up to 100s GB/s, millions of IOPS, sub-ms latencies

### EC2 Instance Storage Summary
• EBS volumes: 
  • network drives attached to one EC2 instance at a time 
  
  • Mapped to an Availability Zones
  
  • Can use EBS Snapshots for backups / transferring EBS volumes across AZ
  
• AMI: create ready-to-use EC2 instances with our customizations 

• EC2 Image Builder: automatically build, test and distribute AMIs

• EC2 Instance Store:
  • High performance hardware disk attached to our EC2 instance
  
  • Lost if our instance is stopped / terminated

• EFS: network file system, can be attached to 100s of instances in a region 

• EFS-IA: cost-optimized storage class for infrequent accessed files

• FSx for Windows: Network File System for Windows servers 

• FSx for Lustre: High Performance Computing Linux file system




