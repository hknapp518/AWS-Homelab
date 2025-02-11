
# AWS Cybersecurity Lab Built with Terraform
 

## Objective

The objective of this project is to use Terraform to automate the deployment of a secure, isolated virtualized environment in AWS, consisting of three virtual machines (VMs). These VMs are configured to simulate real-world Red Team (offensive security) and Blue Team (defensive security) activities. The goal is to create a fully functional cybersecurity lab to practice penetration testing, exploitation, and network defense.

Key objectives include:

Deploying Three VMs: Set up Kali Linux (Red Team), Windows 10 (Workstation for Blue Team), and Ubuntu (Target for exploitation) as EC2 instances in AWS.
Creating a Secure AWS VPC: All VMs are deployed within a Virtual Private Cloud (VPC) to ensure network isolation and security between the machines.
Automating Deployment with Terraform: Utilize Terraform to automate the infrastructure creation process, including security groups, EC2 instances, and VPN setup.
Simulating Real-World Cybersecurity Scenarios: Red Team members will simulate cyberattacks, while Blue Team members will defend the network, using the lab to hone both offensive and defensive security skills.


## Steps

Create an AWS topology outlining the cloud, the VPC which holds all of our VMs, and the public subnet where all of the machines will connect to the internet. The internet gateway is attached to the VPC and enables communication between the public subnet and the internet.
![AWS cyber topology](https://github.com/user-attachments/assets/f4bd6cdd-ba8e-4daa-a0a3-9a11166b53e1)
