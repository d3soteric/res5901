# RES5901
Repo for work related to my second research paper for the SANS Technical Institute MSISE program

the res_infra.json template is a skeleton to get you started with replicating the simulation environment. It includes the VPC, IGW, routetable, route, subnets, security groups and EC2 instances.  

RDS, ES, S3 flow logs and the vulnerable test server running on Ubuntu are not included but using the skeleton provided can be built as needed and if desired.

Depending on the tests desired to run, additional security group modifications may be required or desired.

The res_storage.json template is not needed unless you want to mess with setting flow logs to go to s3 buckets created in other accounts (abandoned by me because CloudWatch was simpler for my testing)
