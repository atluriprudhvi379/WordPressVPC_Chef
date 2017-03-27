This cloud formation template creates and automates installing wordpress website using CM tool chef.

Objectives:
1.Create VPC.
2.Create Subnet.
3.Created Subnet and attached it to the IGW with Route table setup.
4.Created webserver security group and added Inbound and Outbound rules for EC2 Instance.
5.Created User data scripts, to allow EC2 instance to automatically download or clone required packages or cooks books to automate installation of wordpress website using Chef.
6.Output the Public IP to access word press website.
