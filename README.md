# AWS EC2 Automation using Lambda and Boto3

## Objective
Automate starting and stopping EC2 instances using AWS Lambda based on tags.

## Services Used
- AWS EC2
- AWS Lambda
- AWS IAM
- Python Boto3

## Steps Performed

1. Created two EC2 instances
2. Added tags:
   - Action = Auto-Stop
   - Action = Auto-Start
3. Created IAM role with EC2 permissions
4. Created Lambda function using Python
5. Implemented Boto3 script to start/stop instances
6. Tested Lambda execution

## Result
- Instance with tag **Auto-Stop → Stopped**
- Instance with tag **Auto-Start → Running**

## Author
Prashant Kumar
