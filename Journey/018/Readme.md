# Amazon S3 

##introduction
- course udemy

## Cloud Research

### Amazon S3 – Security

• User-Based

  • IAM Policies – which API calls should be allowed for a specific user from IAM
  
• Resource-Based
  • Bucket Policies – bucket wide rules from the S3 console - allows cross account
  • Object Access Control List (ACL) – finer grain (can be disabled)
  • Bucket Access Control List (ACL) – less common (can be disabled)

### S3 Bucket Policies 
• JSON based policies
  • Resources: buckets and objects
  
  • Effect: Allow / Deny
  
  • Actions: Set of API to Allow or Deny
  
  • Principal: The account or user to apply the
    policy to
 
• Use S3 bucket for policy to:
  • Grant public access to the bucket
  
  • Force objects to be encrypted at upload
  
  • Grant access to another account (Cross
    Account)
   
   
   
   
   
   
