# AWS EC2 Auto Scaling Lab Project

This project contains evidence and documentation of an AWS hands-on lab focused on setting up and testing EC2 Auto Scaling using launch templates, load balancers, CloudWatch alarms, and web servers.

## 📌 Objectives

- Create an Amazon Machine Image (AMI) from a configured EC2 instance.
- Build and use a Launch Template.
- Configure Application Load Balancer (ALB).
- Create Target Groups and register EC2 instances.
- Define CloudWatch alarms to trigger scaling policies.
- Test Auto Scaling by simulating CPU stress.
- Terminate an instance and observe self-healing behavior.

## 📷 Key Screenshots

1. **Launch Template Created** – Template for new EC2 instances.
2. **Load Balancer (ALB) Setup** – With routing to multiple AZs.
3. **Target Groups** – Created and registered to monitor EC2 health.
4. **CloudWatch Alarms** – Triggering scale-up/down actions.
5. **Two Lab Instances Running** – After autoscaling based on alarm.
6. **Web Server Test Pages** – Accessed using public IPs.
7. **Termination Event** – Shows self-healing instance behavior.

## 🛠️ Technologies Used

- **Amazon EC2**
- **Launch Templates**
- **Elastic Load Balancing (ALB)**
- **Target Groups**
- **CloudWatch Alarms**
- **Auto Scaling Groups**
- **Amazon Linux 2**
- **User Data Script**

## 💡 What I Learned

- How to automate EC2 instance creation using Launch Templates.
- How to configure scalable infrastructure with high availability.
- How CloudWatch integrates with Auto Scaling for dynamic load handling.
- How to test web server deployment and monitor instance behavior.

---

> Created and executed as part of AWS Cloud Engineer training.  
> **Author:** [Ime Ben](https://github.com/ime-cloud-sec-analyst)
