# Cloudera Data Platform (CDP) - Public Cloud - Self On-Boarding in AWS

This is a series of steps to set up Clouder Data Platform (CDP) - Public Cloud 
in AWS. 

Steps are:
1. Prep your AWS account 
2. Set up an Environment and Datalake
2. Set up a Datahub cluster - TBD
3. Set up Cloudera Data Warehouse (CDP) - TBD

# Assumptions
The following assumptions are being made, which have been validated as "good 
enough" over the course of several on-boardings:
* All EC2 instances will use Private IPs (this requires the CCM feature of CDP)
* All S3 buckets will be deployed with Default AWS Encryption (AKA AES-256)
