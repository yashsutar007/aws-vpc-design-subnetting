# aws-vpc-design-subnetting

## Overview
This project demonstrates AWS VPC design and subnetting by creating a custom Virtual Private Cloud with public and private subnets across multiple Availability Zones.

The project simulates real-world cloud networking architecture used in production environments for secure and scalable infrastructure deployment.

---

## Features

- Custom VPC creation
- Public and private subnet configuration
- Multi-AZ subnet architecture
- Internet Gateway attachment
- Route table configuration
- Subnet association management
- AWS networking architecture design

---

## Technologies Used

- AWS VPC
- AWS Subnets
- Internet Gateway
- Route Tables
- AWS Networking
- Ubuntu EC2

---

## Architecture Design

- VPC CIDR: `10.0.0.0/16`

### Public Subnets
- Public Subnet AZ-1: `10.0.1.0/24`
- Public Subnet AZ-2: `10.0.2.0/24`

### Private Subnets
- Private Subnet AZ-1: `10.0.11.0/24`
- Private Subnet AZ-2: `10.0.12.0/24`

---

## Project Structure

```text
aws-vpc-design-subnetting/
│
├── README.md
│
├── report/
│   └── assignment-3-report.pdf
│
├── screenshots/
│   ├── 01-vpc-created.png
│   ├── 02-public-subnet-az1.png
│   ├── 03-public-subnet-az2.png
│   ├── 04-private-subnet-az1.png
│   ├── 05-private-subnet-az2.png
│   ├── 06-internet-gateway.png
│   ├── 07-route-table-public.png
│   ├── 08-route-table-private.png
│   ├── 09-subnet-associations.png
│   ├── 10-vpc-resource-map.png
│   └── 11-architecture-diagram.png
│
└── architecture/
    └── architecture-diagram.png
