# Basic Employee Onboarding (AD)(RBAC)

## Problem Statement
* Northstar Medical Group is a fictional healthcare company with 200+ employees whose Active Directory was left disorganized by its previous MSP. Users were added manually with no structure, permissions were inconsistent, onboarding took days, and nothing was documented, so nobody could say who had access to what. As a healthcare organization, this put Northstar at risk of HIPAA fines and failed audits.

## Solution Overview
* I built a new Active Directory domain, NMG.com, on a Windows Server domain controller in VirtualBox. I created four department OUs (Finance, HR, IT, Operations), each with a matching security group, to implement a flat RBAC model where access comes from group membership instead of individual users. I then provisioned 15 users with standardized usernames, UPNs, job titles, and departments, giving each only the access their role needs, which created a documented, repeatable onboarding process.

## Video Walkthrough
Video coming soon!

## Tools Used
* Windows Server
* Active Directory Domain Services
* VirtualBox
* RBAC
* GitHub

## Project Timeline
* Day 1: Domain creation and domain controller promotion
* Day 2: Organizational unit and security group design
* Day 3: User provisioning and RBAC implementation
* Day 4: Incident response and resolution (NMG-0047)
* Day 5: Documentation and case study packaging

## Key Accomplishments
* Built NMG.com domain from scratch
* Solved a mock ticket where a user was given incorrect access
* Fully documented my steps from beginning to end
