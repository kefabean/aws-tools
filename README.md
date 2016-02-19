# aws-tools
Repo for AWS tools generally created in python

mfa - uses limited access credentials stored cli/boto profile to generate temporary admin credentials for cli/boto using MFA
pricing - downloads EC2 and RDS pricing information in CSV format for easy import in to Microsoft Excel
stack - provides simple stack create and update with validation and automated tracking of stack update progress
failover - stack to provide automated failover of a static instance and associated data on EBS volume from one AZ to another
