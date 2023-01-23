
# New post title here

## Introduction

EC2 Part 3


## Cloud Research

##EC2 Image Builder

• Used to automate the creation of Virtual Machines or container images

 • => Automate the creation, maintain, validate and test EC2 AMIs 
 
• Can be run on a schedule (weekly, whenever packages are updated, etc…) 

• Free service (only pay for the underlying resources)


## EC2 Instance Store
• EBS volumes are network drives with good but “limited” performance

• If you need a high-performance hardware disk, use EC2 Instance Store

• Better I/O performance

• EC2 Instance Store lose their storage if they’re stopped (ephemeral)

• Good for buffer / cache / scratch data / temporary content

• Risk of data loss if hardware fails

• Backups and Replication are your responsibility
