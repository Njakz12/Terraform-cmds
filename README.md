## Terraform Project

![image](https://github.com/user-attachments/assets/e6ede2a7-f49b-456b-ab35-8f7ad403a051)

Using a remote-exec provisioner, we would assume there is a development team working on an app. They want us to make sure anytime changes are made to the app file should be tested so we need to create the following:

- VPC

- Public subnet with a route table and an IGW assigned to the public subnet.

-  EC2 instance and deploy the app on this instance using its public IP address and configure its security group.
