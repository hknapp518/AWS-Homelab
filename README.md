
# Red Team / Blue Team AWS Homelab
Deploying 3 machines in AWS to practice my defending and attacking on VMs. 

## Objective
This project sets up a virtualized environment in AWS with three machines for practicing Red Team (offensive security) and Blue Team (defensive security) activities. The environment consists of:

Kali Linux (Attacker): A penetration testing machine used for offensive security exercises.
Windows 10 (Workstation): A common endpoint that the Blue Team needs to defend against potential attacks.
Ubuntu (Target): A vulnerable server used for Red Team to exploit and Blue Team to secure.
The goal of this environment is to practice penetration testing, network defense, and improve security skills by simulating a real-world attack and defense scenario.

Project Overview
Red Team (Offensive Security): The Red Team simulates cyberattacks to test vulnerabilities, conduct penetration tests, and exploit weaknesses in the network and systems.

Blue Team (Defensive Security): The Blue Team defends against the attacks launched by the Red Team, identifying threats, mitigating them, and securing the system.

Each machine is deployed as an EC2 instance in AWS, creating a fully isolated environment to simulate real-world cybersecurity scenarios.

### Skills Learned

Penetration Testing Techniques:
Understanding how to conduct penetration tests using tools like Metasploit, Nmap, Hydra, and Burp Suite.

Incident Detection & Response:
Using Sysmon, Wireshark, Splunk, and other logging tools to monitor network traffic and detect suspicious activities.

## Steps

Create an AWS topology outlining the cloud, the VPC which holds all of our VMs, and the public subnet where all of the machines will connect to the internet. The internet gateway is attached to the VPC and enables communication between the public subnet and the internet.
![AWS cyber topology](https://github.com/user-attachments/assets/f4bd6cdd-ba8e-4daa-a0a3-9a11166b53e1)
