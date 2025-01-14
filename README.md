# Oracle RAC Setup

This repository contains detailed instructions, scripts, and resources for setting up Oracle Real Application Clusters (RAC).  

## Table of Contents
- [Introduction](#introduction)
- [Prerequisites](#prerequisites)
- [Setup Steps](#setup-steps)
- [Common Issues and Solutions](#common-issues-and-solutions)
- [Virtual Machines](#virtual-machines)

## Introduction
Oracle RAC is a high-availability and scalability solution for Oracle databases. This project demonstrates the installation and configuration of RAC on VirtualBox with Oracle Linux.  

## Prerequisites
- VirtualBox 7.1+
- Oracle Linux 7.7 ISO
- Minimum of 8 GB RAM per node

## Setup Steps
1. [Download and Install VirtualBox](https://www.virtualbox.org/).
2. Set up two virtual machines with shared storage and configure RAC.
3. Follow the detailed steps in the [Oracle RAC Setup Guide](docs/Oracle_RAC_Setup_Guide.pdf).

## Common Issues and Solutions
Refer to the [guide](docs/Oracle_RAC_Setup_Guide.pdf) for solutions to common issues encountered during setup.

## Virtual Machines
Configured virtual machine templates for RAC setup:
- [RAC Node 1](VMs/RAC_Node1.ova)
- [RAC Node 2](VMs/RAC_Node2.ova)


