**Add a cover photo like:**
![placeholder image](https://via.placeholder.com/1200x600)

# CCP Course udemy

## Introduction
As an AWS learning Starter, I will start with the IAM CCP Course by stephane mareek
- IAM Users & Groups
- IAM Policies
- IAM MFA

## CLoud Research
- IAM User & Group
As I know, a user is someone who joins a group, for example, user A joins the admin group, user B joins the developer group, and the group is like grouping a user.So users and groups are given JSON Documents which means policies, IAM policies as below for example

{
"Version": "2012-10-17",
"Statement": [
{
"Effect": "Allow",
"Action": "ec2:Describe*",
"Resource": "*"
},
{
"Effect": "Allow",
"Action": "elasticloadbalancing:Describe*"
,
"Resource": "*"
},
{
"Effect": "Allow",
"Action": [
"cloudwatch:ListMetrics",
"cloudwatch:GetMetricStatistics",
"cloudwatch:Describe*"
],
"Resource": "*"
}
]
}
- IAM Policies

 For example, I'm in the developer group and I get access, like editing, I see like that and that's giving group permissions and even in other groups like that. For example, the admin group is allowed access, all access is allowed to access AWS and others. Yes, that's enough, my understanding of IAM Policies. IAM Policies structure
 Consists of • Version: policy language version, always include “2012
-10
-
17”
• Id: an identifier for the policy (optional) • Statement: one or more individual statements (required)
• Statements consists of • Sid: an identifier for the statement (optional) • Effect: whether the statement allows or denies access
(Allow, Deny)
• Principal: account/user/role to which this policy applied to • Action: list of actions this policy allows or denies • Resource: list of resources to which the actions applied to • Condition: conditions for when this policy is in effect
(optional)

IAM – Password Policy
• Strong passwords = higher security for your account
• In AWS, you can setup a password policy:
• Set a minimum password length
• Require specific character types:
• including uppercase letters
• lowercase letters
• numbers
• non-alphanumeric characters
• Allow all IAM users to change their own passwords
• Require users to change their password after some time (password expiration)
• Prevent password re-use

- IAM MFA

MFA : Multi Factor authentication


## Cloud Research

- AWS Cli


## Try yourself

✍️ Add a mini tutorial to encourage the reader to get started learning something new about the cloud.

### Step 1 — Summary of Step

![Screenshot](https://via.placeholder.com/500x300)

### Step 1 — Summary of Step

![Screenshot](https://via.placeholder.com/500x300)

### Step 3 — Summary of Step

![Screenshot](https://via.placeholder.com/500x300)

## ☁️ Cloud Outcome

✍️ (Result) Describe your personal outcome, and lessons learned.

## Next Steps

✍️ Describe what you think you think you want to do next.

## Social Proof

✍️ Show that you shared your process on Twitter or LinkedIn

[link](link)
