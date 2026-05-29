# Jenkins Remoting Project

## Overview
This project demonstrates how to set up and configure Jenkins Remoting using remote Jenkins agents (nodes) to distribute build workloads securely across multiple machines.

The setup includes:
- A Jenkins Controller (Master)
- A Remote Jenkins Agent
- Docker-based agent deployment
- Jenkins inbound agent communication using WebSocket
- Secure remote execution and node isolation

This project was completed as part of a DevOps learning task focused on Jenkins distributed builds and remote execution.

---

# Objectives

- Set up Jenkins Remoting to connect remote Jenkins nodes
- Distribute build workloads across different machines securely
- Run jobs remotely on different architectures
- Improve security using node isolation
- Gain hands-on experience with Jenkins remote execution capabilities

---

# Technologies Used

- Jenkins
- Docker
- PowerShell
- Jenkins Inbound Agent
- WebSocket Communication
- Ubuntu/Linux Containers

---

# Project Architecture

```text
                   Jenkins Controller
                           |
                    Jenkins Remoting
                           |
                -----------------------
                |                     |
         Remote Agent Node      Future Nodes
