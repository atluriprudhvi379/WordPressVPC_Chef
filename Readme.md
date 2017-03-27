This cloud formation template creates and automates installing wordpress website using CM tool chef.

Objectives:
1.Create VPC.
2.Create Subnet.
3.Created Subnet and attached it to the IGW with Route table setup.
4.Created webserver security group and added Inbound and Outbound rules for EC2 Instance.
5.Created User data scripts, to allow EC2 instance to automatically download or clone required packages or cooks books to automate installation of wordpress website using Chef.
6.Output the Public IP to access word press website.


Due to the limitations with account, i was not able to implement ELB ,ASG and separate RDS instance. In addition to that, I Configured and installed wordpress using chef by leveraging the community cook books available online (https://github.com/brint/wordpress-cookbook.git ), Since current version of cook book does not have wider OS support, and due to the fact it is best compatible with Ubuntu 14.04 as per cook book description, I limited the template to launch EC2 instance with Ubuntu 14.04 version.
