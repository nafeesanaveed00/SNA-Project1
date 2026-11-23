# SNA-Project1
# Project: Multi-Site Highly Available Web Hosting Platform

Act as an expert System Administrator, Network Engineer, DevOps Engineer, and Kubernetes instructor.

I am a student working on a System and Network Administration project. I have selected the following project:

**Multi-Site Highly Available Web Hosting Platform**

## 1. Project Objective

Build a fully automated, highly available web hosting infrastructure across two simulated data centers (Site A and Site B).

The main objective is to create a resilient multi-site network and Kubernetes-based platform that can continue serving users even if one entire site goes down.

If Site A fails, users should automatically be redirected to Site B, where the same web application should remain accessible.

The infrastructure should be deployable and rebuildable entirely through code.

## 2. Required Technologies

Use the following technologies where appropriate:

- Ubuntu Linux – Operating system
- VMware Workstation – Virtual machine environment
- Docker – Containerization
- Kubernetes (preferably K3s for a manageable student lab) – Container orchestration
- Terraform – Infrastructure provisioning
- Ansible – Configuration management and automation
- HAProxy – Load balancing and traffic distribution
- Keepalived – Virtual IP and high availability, if suitable
- Prometheus – System monitoring
- Grafana – Monitoring dashboards
- Git and GitHub – Version control and project code

Suggest alternatives only when technically necessary, and explain why.

## 3. Required Project Features

Implement the following features:

1. Two simulated data centers: Site A and Site B.
2. Network connectivity between both sites.
3. Ubuntu virtual machines configured as servers.
4. Automated server configuration using Ansible.
5. Kubernetes cluster deployment.
6. Containerized web application deployed on both sites.
7. Load balancing and traffic distribution.
8. Health checks to identify server and application failures.
9. Automatic failover from Site A to Site B.
10. Database backup and replication or another appropriate data synchronization method.
11. Monitoring using Prometheus and Grafana.
12. Infrastructure deployment and rebuilding through automation scripts.
13. Failure simulation and recovery testing.

## 4. Important Architecture Requirements

Design a clear network architecture containing:

- Site A (Primary Data Center)
- Site B (Secondary Data Center)
- Kubernetes infrastructure
- Web application servers
- Database layer
- Load balancer
- Monitoring server
- Network connections between sites
- User access point

Explain the role of every component.

Clearly distinguish application failover, load-balancer failover, and database recovery. Do not assume that deploying the same application on two sites automatically provides database consistency.

## 5. How I Want You to Teach Me

I am a student, so guide me from the beginning.

Follow these rules:

**Step 1: Project Planning**
- Explain the complete project in simple language.
- Show the architecture diagram.
- Explain how the system will work.
- List hardware and software requirements.
- Estimate the number of virtual machines and their resources.
- Make sure the project is realistic for a student.

**Step 2: Environment Setup**
- Guide me through VMware installation and configuration if required.
- Guide me through creating virtual machines.
- Explain Ubuntu installation and network configuration.
- Provide exact commands.

**Step 3: Network Configuration**
- Configure IP addresses, subnets, gateways, DNS, and communication between sites.
- Explain every network configuration.
- Test connectivity using ping and other networking commands.

**Step 4: Infrastructure Automation**
- Configure Terraform and Ansible.
- Create the necessary configuration files.
- Explain where each file should be saved.
- Provide complete code, not incomplete examples.

**Step 5: Kubernetes Deployment**
- Install and configure Kubernetes/K3s.
- Deploy the web application.
- Configure networking and services.
- Explain how to verify that everything is working.

**Step 6: High Availability**
- Configure load balancing and health checks.
- Implement automatic failover between Site A and Site B.
- Configure appropriate database backup and recovery.
- Demonstrate what happens when Site A becomes unavailable.

**Step 7: Monitoring**
- Install Prometheus and Grafana.
- Configure dashboards.
- Monitor CPU, RAM, network traffic, server health, and application availability.

**Step 8: Testing**
- Test normal application access.
- Shut down Site A and verify that Site B continues serving users.
- Test recovery when Site A comes back online.
- Test automation by rebuilding the infrastructure from code.
- Document all results.

**Step 9: Final Documentation**
Prepare:
- Project introduction
- Problem statement
- Objectives
- Scope
- Architecture diagram
- Network topology
- Software and hardware requirements
- Implementation steps
- Configuration files and commands
- Testing and results
- Screenshots checklist
- Challenges and solutions
- Conclusion
- Future improvements

## 6. Very Important Instructions

- Explain everything in beginner-friendly language.
- Give commands one step at a time.
- Explain what each command does before asking me to execute it.
- Tell me exactly which terminal to use (Windows CMD, PowerShell, or Ubuntu terminal).
- Provide the complete configuration files and their directory locations.
- Never skip steps.
- Do not assume that a command worked; ask me to share its output and verify it.
- If an error occurs, troubleshoot it before moving forward.
- Do not move to the next stage until the current stage is working.
- Prefer free and open-source technologies.
- Avoid unnecessary complexity and expensive cloud services.
- Make the architecture realistic and demonstrate actual high availability rather than just describing it.
- Clearly explain any limitations caused by running both simulated sites on one physical computer.

## 7. Final Expected Outcome

At the end of this project, I should have:

1. Two functioning simulated data centers.
2. A working multi-site network.
3. A Kubernetes-based web hosting platform.
4. Automated infrastructure deployment.
5. A working web application.
6. Load balancing and automatic failover.
7. Monitoring dashboards.
8. Backup and recovery mechanisms.
9. A complete GitHub repository containing the project code.
10. A successful final demonstration showing that the application remains accessible when one site fails.

**Start by explaining the complete project architecture, required resources, and the proposed virtual machine layout. Then ask me about my computer's specifications and available resources before selecting the final architecture. Do not start installing anything until the plan is finalized.**

Remember: I want to BUILD this project practically, not just write a theoretical report. Guide me until the complete project is implemented and tested.
