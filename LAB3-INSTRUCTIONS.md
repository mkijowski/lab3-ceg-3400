## Lab 3 : CEG 3400

### The Terminalator

Table of contents:
* [Background](LAB3-INSTRUCTIONS.md#background)
* [Objectives](LAB3-INSTRUCTIONS.md#objectives)
* [Preparation](LAB3-INSTRUCTIONS.md#preparation)
* [Task 1: Crafting Packets](LAB3-INSTRUCTIONS.md#task-1-crafting-packets)
* [Task 2: Iptables](LAB3-INSTRUCTIONS.md#task-2-iptables)
* [Task 3: Overslept](LAB3-INSTRUCTIONS.md#task-3-overslept)

---

#### Background

Learn about some basic (and more advanced) network manipulation tools.

The year is 2021, as the world nears the end of a pandemic, we gather around one of 
our last bastions of scientific reason and level-headed discourse, Facebook.

Little did we know, in the year 2031, the robot uprising has nearly wiped out humanity.  
And it all started with Steve Stevenson.  Two weeks from today Steve has an interview at 
Facebook, he will ace the interview and be assigned to Facebook's dark web AI: FaceNet.

The rest, as they say, is the future.  Knowing this you are tasked with making sure Steve
does NOT make it to his interview.  Future folk have provided you with an IP and SSH key
for Steve's home network (you will be creating this in AWS).  Your goal is to practice 
crafting and sending packets using scapy, and creating iptables firewall rules to prevent
Steve accessing Facebook.com, and finally you will redirect the network time protocol (NTP)
request from his alarm clock to a dummy server that will respond with the wrong time.

---

#### Objectives

Students should become familiar with the following:

* creating packets with Scapy
* sending and capturing packets with Scapy
* configuring iptables (firewalls)

---

#### Preparation

This lab will require all work be done in AWS.  Please deploy the below instance and work inside the lab.

* Click [this cloudformation link](https://console.aws.amazon.com/cloudformation/home?region=us-east-1#/stacks/new?stackName=ceg3400Lab1&templateURL=https:%2F%2Fwsu-cecs-cf-templates.s3.us-east-2.amazonaws.com%2Fcourse-templates%2Fceg3400-mek.yml)
  to deploy your stack
* Identify the IP address of the running EC2 instance created [in the EC2
  page](https://console.aws.amazon.com/ec2/v2/home?region=us-east-1)
* Connect with the following string: `ssh -i /path/to/keyfile ubuntu@<IP
  ADDRESS>` 

---

### Task 1: Crafting Packets

Famliarize yourself with scapy (covered in class) by creating an NTP request and sending it to 204.2.134.163.  
Capture the response.

Answer all questions in `README.md`


---

### Task 2: Iptables




---

### Task 3: Overslept




