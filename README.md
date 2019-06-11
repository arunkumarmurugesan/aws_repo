# aws_repo

Introduction:
This document is a short description of AWS security CIS benchmark and compliance fix in Production Account and How to remediate the AWS security gaps. 

The cloudformation template is creates following Cloudtrail Metric and Alarm in the AWS account:

CloudTrailIAMPolicyChanges
CloudTrailVpcChanges
CloudTrailEC2LargeInstanceChanges
CloudTrailSecurityGroupChanges
CloudTrailGatewayChanges
CloudTrailConsoleSignInFailures
DisabledOrDeletedCmks
NoMfaConsoleLogins
AwsConfigChangesAlarm
CloudTrailEC2InstanceChanges
RootAccountLogins
CloudTrailNetworkAclChanges
S3BucketPolicyChanges
CloudTrailChanges


Execute the CloudFormation template: 
In order to monitor the security and compliance events, run the cloudformation template to configure it. 

Go to cloudformation console
Choose the create task
Upload the CF template and click the "Next"
Enter the CF Name and Email address


CloudTrailIAMPolicyChanges	
IAMPolicyEventCount >= 1 for 1 datapoints within 5 minutes

CloudTrailVpcChanges	
VpcEventCount >= 1 for 1 datapoints within 5 minutes

CloudTrailEC2LargeInstanceChanges	
EC2LargeInstanceEventCount >= 1 for 1 datapoints within 5 minutes

CloudTrailSecurityGroupChanges	
SecurityGroupEventCount >= 1 for 1 datapoints within 5 minutes

CloudTrailGatewayChanges	
GatewayEventCount >= 1 for 1 datapoints within 5 minutes

CloudTrailConsoleSignInFailures	
ConsoleSignInFailureCount >= 3 for 1 datapoints within 5 minutes

DisabledOrDeletedCmks	
DisabledOrDeletedCmks >= 1 for 1 datapoints within 5 minutes

NoMfaConsoleLogins	
NoMfaConsoleLogins >= 1 for 1 datapoints within 5 minutes

AwsConfigChangesAlarm	
AwsConfigChanges >= 1 for 1 datapoints within 5 minutes

CloudTrailEC2InstanceChanges	
EC2InstanceEventCount >= 1 for 1 datapoints within 5 minutes

RootAccountLogins	
RootAccountLogins >= 1 for 1 datapoints within 5 minutes

CloudTrailNetworkAclChanges	
NetworkAclEventCount >= 1 for 1 datapoints within 5 minutes

S3BucketPolicyChanges	
S3BucketPolicyChanges >= 1 for 1 datapoints within 5 minutes

CloudTrailChanges	
CloudTrailEventCount >= 1 for 1 datapoints within 5 minutes

