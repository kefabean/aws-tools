# aws-tools

Useful AWS-related command line tools written in python:

- **mfa** - uses restricted access credentials stored cli/boto profile to generate temporary admin credentials for cli/boto using MFA
- **pricing** - downloads EC2 and RDS pricing information from AWS pricing API in CSV format for easy import in to Microsoft Excel
- **stack** - provides simple stack create/update with parameter validation and automated tracking of stack update progress
- **failover** - stack to provide automated failover of a static instance and associated data on EBS volume from one AZ to another
