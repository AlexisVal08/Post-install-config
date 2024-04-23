<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>


# osTicket - Post-Installation Configuration Objectives

This tutorial outlines post install configuration of the open-source help desk ticketing system osTicket.

## Environments and Technologies Used

- **Microsoft Azure (Virtual Machines/Compute)**
- **Remote Desktop**
- **Internet Information Services (IIS)**
- **Operating System:** Windows 10 (21H2)

## List of Prerequisites

- Azure Virtual Machine
- Internet Information Services (IIS)
- PHP Manager
- Rewrite Module
- VC Redist
- MySQL
- Heidi SQL
- osTicket v1.15.8



## 1. **Configure Roles:**
    - Admin Panel -> Agents -> Roles
    - Supreme Admin
<img width="428" alt="Step 1A" src="">
<img width="428" alt="Step 1B" src="">
<img width="428" alt="Step 1C" src="">
<img width="428" alt="Step 1D" src="">
<img width="428" alt="Step 1E" src="">


## 2. **Configure Departments:**
   - Admin Panel -> Agents -> Departments
   - System Administrators
<img width="428" alt="Step 2A" src="">
<img width="428" alt="Step 2B" src="">
<img width="428" alt="Step 2C" src="">
<img width="428" alt="Step 2D" src="">
<img width="428" alt="Step 2E" src="">


## 3. **Configure Teams:**
   - Admin Panel -> Agents -> Teams
   - Level I Support
   - Level II Support
   - 
<img width="428" alt="Step 3A" src="">
<img width="428" alt="Step 3B" src="">
<img width="428" alt="Step 3C" src="">
<img width="428" alt="Step 3D" src="">
<img width="428" alt="Step 3E" src="">

## 4. *Allow anyone to create tickets:**
   - Admin Panel -> Settings -> User Settings
   - Registration Required: Require registration and login to create tickets 
<img width="428" alt="Step 4A" src="">
<img width="428" alt="Step 4B" src="">
<img width="428" alt="Step 4C" src="">
<img width="428" alt="Step 4D" src="">
<img width="428" alt="Step 4E" src="">

## 5. **Configure Agents (workers):**
   - Admin Panel -> Agents -> Add New
   - Jane
   - John
<img width="428" alt="Step 5A" src="">
<img width="428" alt="Step 5B" src="">
<img width="428" alt="Step 5C" src="">
<img width="428" alt="Step 5D" src="">
<img width="428" alt="Step 5E" src="">

## 6. **Configure Users (customers):**
   - Agent Panel -> Users -> Add New
   - Karen
   - Ken
<img width="428" alt="Step 6A" src="">
<img width="428" alt="Step 6B" src="">
<img width="428" alt="Step 6C" src="">
<img width="428" alt="Step 6D" src="">
<img width="428" alt="Step 6E" src=""> 

## 7. **Configure SLA:**
   - Admin Panel -> Manage -> SLA
   - Sev-A (1 hour, 24/7)
   - Sev-B (4 hours, 24/7)
   - Sev-C (8 hours, business hours)
<img width="428" alt="Step 7A" src="">
<img width="428" alt="Step 7B" src="">
<img width="428" alt="Step 7C" src="">
<img width="428" alt="Step 7D" src="">
<img width="428" alt="Step 7E" src="">

## 8. **Configure Help Topics:**
   - Admin Panel -> Manage -> Help Topics
   - Business Critical Outage
   - Personal Computer Issues
   - Equipment Request
   - Password Reset
<img width="428" alt="Step 8A" src="">
<img width="428" alt="Step 8B" src="">
<img width="428" alt="Step 8C" src="">
<img width="428" alt="Step 8D" src="">
<img width="428" alt="Step 8E" src="">
