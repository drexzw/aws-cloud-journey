# Secure Multi-Tier Network on AWS

## Project Overview

This project demonstrates how to build a secure multi-tier network architecture on AWS.

The environment separates public-facing resources from private resources using Amazon VPC, subnets, route tables, and security groups.

---

## Objectives

- Build a custom Amazon VPC
- Create public and private subnets
- Configure an Internet Gateway
- Configure route tables
- Launch EC2 instances
- Configure Security Groups
- Test secure communication between tiers

---

## AWS Services Used

- Amazon VPC
- EC2
- Security Groups
- Route Tables
- Internet Gateway
- Elastic IP (if used)

---

## Architecture

<img width="591" height="528" alt="image" src="https://github.com/user-attachments/assets/b2148952-ebf1-4881-9f62-6e59f107159c" />


---

## Implementation Steps

### Step 1
Create the VPC<img width="1331" height="541" alt="image" src="https://github.com/user-attachments/assets/b8e7c794-2aa1-46e2-a036-39f92613c3c5" />



### Step 2
Create public subnets 
Public Subnet 1<img width="991" height="541" alt="image" src="https://github.com/user-attachments/assets/46a2ff4a-b734-41f0-8406-0a39a5a4f90b" />
Public Subnet 2<img width="1175" height="537" alt="image" src="https://github.com/user-attachments/assets/8257a6f4-8fc6-4d30-a8ea-aae1261f88e3" />



### Step 3
Create private subnets
Private Subnet 1<img width="1175" height="545" alt="image" src="https://github.com/user-attachments/assets/3c4a88bf-661b-4a25-9169-e5a6e24bf3ba" />
Private Subnet 2 <img width="1117" height="591" alt="image" src="https://github.com/user-attachments/assets/ca90dced-3f2e-47b0-8357-013d71005c0d" />

###Step 4
Create Internet Gateway<img width="1356" height="538" alt="Screenshot 2026-07-06 215752" src="https://github.com/user-attachments/assets/3e4987c9-61f2-4d78-913a-c738fbafa4a1" />



### Step 5
Attach Internet Gateway<img width="1357" height="504" alt="image" src="https://github.com/user-attachments/assets/1ad52716-01f7-4962-b836-e93c3a33510e" />

###Step 6
Create Route Table<img width="1339" height="541" alt="image" src="https://github.com/user-attachments/assets/dec636ee-389b-4d1d-ae27-322ff9f18d84" />


### Step 7
Configure Route Tables<img width="1349" height="453" alt="image" src="https://github.com/user-attachments/assets/58823ccc-7d31-44f2-9f1f-5302749f46cb" />

Edit Route Destination <img width="1349" height="453" alt="Screenshot 2026-07-06 220532" src="https://github.com/user-attachments/assets/5609d0f5-1a68-466e-a005-d7772ec575a4" />


Edit Subnet Associations<img width="1359" height="536" alt="Screenshot 2026-07-06 221755" src="https://github.com/user-attachments/assets/7cb1f721-6dc2-40c3-8b31-d280b7f99bee" />

###Step 8 
Create Private Route Table<img width="1348" height="536" alt="image" src="https://github.com/user-attachments/assets/0c06af3d-593c-4e24-a94a-15f3d03828df" />

Edit subnet Associations <img width="1346" height="532" alt="image" src="https://github.com/user-attachments/assets/dcc2fcba-7f3a-4bc7-afea-7b8a2b4c18b8" />


### Step 7
Launch EC2 instances
Public EC2
Configuring Security Groups <img width="1314" height="497" alt="image" src="https://github.com/user-attachments/assets/dc538d46-68b4-4d35-9fe5-f0ae66fdbfbc" />
Configuring Security Groups<img width="1311" height="488" alt="image" src="https://github.com/user-attachments/assets/2cd2572d-b85d-4a6e-abe5-76624436cf5a" />
<img width="1302" height="453" alt="image" src="https://github.com/user-attachments/assets/af004644-417b-4101-834c-c3e36e442bb2" />


### Step 8
Launching Private EC2t<img width="1327" height="499" alt="image" src="https://github.com/user-attachments/assets/61d5fafc-7781-4b36-9a86-a72f0e807660" />
Network Settings<img width="1329" height="547" alt="image" src="https://github.com/user-attachments/assets/c0df9614-8fa6-46f1-8804-2752b4561ca0" />
Security Groups <img width="1304" height="490" alt="image" src="https://github.com/user-attachments/assets/a8653c6a-46a7-4dcf-b29b-afc2be581783" />


### Step 9
Test connectivity <img width="1346" height="421" alt="image" src="https://github.com/user-attachments/assets/8d07ef4e-4758-49dc-9d44-8a8c5774f7c6" />


Skills and Concepts Practiced
Created and configured a custom AWS VPC
Designed a multi-tier network architecture using public and private subnets
Applied CIDR addressing and subnet planning
Configured route tables for controlled network traffic flow
Connected public resources through an Internet Gateway
Deployed EC2 instances into different network tiers
Configured Security Groups as virtual firewalls
Tested SSH connectivity between instances
Practiced cloud security principles including network isolation and least-privilege access

This project provided hands-on experience with the core networking concepts required for building secure and scalable cloud environments.




