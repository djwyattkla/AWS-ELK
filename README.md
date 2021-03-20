# AWS-ELK
This project began inside Amazon's AWS console.
I created a VPC and named it VPC1
I created Subnets and named them Private1 and Private2, Public1 and Public2
Actually, this was all then simplified with a CloudFormation stack that set everything up.
I then went and edited the public subnets to auto assign IP.
Route Tables were created and associated.
A Linux2 instance, Windows Server (to monitor Kibana), A DVWA Ubuntu Server (X2) and an Elk Stack Ubuntu (with 4G storage) was created.
Much work was done from the GitBash command line to install Docker, Ansible, SSH into various machines to do updates and upgrades and transfer of files (included in this repo).
Working in progress.. more to follow.

