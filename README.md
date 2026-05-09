# aws-ec2-minecraft-server
Self-hosted Minecraft server deployed on AWS EC2 (Ubuntu), configured manually via SSH using PaperMC and Java. Demonstrates hands-on experience with cloud infrastructure, Linux system administration, networking (security groups), and debugging in a real AWS environment.

# Cloud Game Server (AWS EC2 + PaperMC)

## Overview
Self-hosted Minecraft server deployed on AWS EC2 using Ubuntu and PaperMC. The project demonstrates cloud infrastructure setup, Linux administration, and server troubleshooting.

## Architecture
![AWS Architecture](/docs/architecture.png)

## Tech Stack
- AWS EC2
- Ubuntu Server
- Java (OpenJDK)
- PaperMC Minecraft Server
- SSH / CLI administration

## Setup Process
- Provisioned EC2 instance on AWS
- Configured security groups for SSH and Minecraft traffic
- Installed and configured Java runtime
- Deployed PaperMC server manually via SSH
- Configured server settings and EULA
- Debugged Java compatibility issues and runtime errors

## Challenges Solved
- Java version mismatch between OpenJDK releases
- Server startup failures due to incompatible runtime
- AWS networking configuration for public access
- Debugging server logs via Linux CLI

## Key Learnings
- AWS EC2 provisioning and networking basics
- Linux server administration
- Java runtime management
- Debugging production-like server environments
