# AWS-VPC-Creation
A Virtual Private Cloud (VPC) in AWS is a segmented portion of the cloud infrastructure that enables the deployment of various AWS resources, such as EC2 instances and RDS databases. This isolation allows users to define their own network configuration, encompassing IP address ranges, subnets, route tables, and security configurations.

Within a created VPC, users have granular control over the network environment, with the option to establish connections to on-premises data centers or link multiple VPCs. A standard setup involves the creation of two subnets within the VPC: one designated as public and the other as private.

To facilitate network routing, two route tables are established, each associated with a respective subnet. Additionally, two instances, each deployed in one of the subnets, are provisioned. To enhance security, two security groups and two Network Access Control Lists (NACL) are configured to govern the traffic flow within the VPC.

For internet connectivity in the public subnet, an Internet Gateway is implemented, while a Network Address Translation (NAT) Gateway is employed to allow private subnet instances to access the internet while maintaining a secure environment. This comprehensive setup enables users to tailor their AWS VPC to specific requirements, optimizing both network performance and security.

VPC Components
1.Create VPC
2.Create subnet (Public,Private)
3.Create gateway(Internet gateway , NAT gateway)
4.Create route tables
5.Attach gateways to subnet via route table
6.Create Security group
7.Create NACL
9.Associate NACL to Subnet
10.Create instance (Public,Private)
11.Associate Security group to instances
