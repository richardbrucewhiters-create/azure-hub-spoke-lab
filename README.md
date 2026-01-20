# Azure Hub-and-Spoke Architecture Lab

## Overview
This project demonstrates a production-style Azure hub-and-spoke architecture
implemented using free-tier resources for hands-on learning.

## Architecture
- Hub VNet for shared services
- Spoke VNet for application workloads
- VNet peering between hub and spoke
- Centralized logging with Log Analytics
- Secure access using Azure RBAC and policies

## Phases
- Phase 1: Networking (VNets, subnets, peering)
- Phase 2: Core services (Storage, Key Vault, logging)
- Phase 3: Identity and governance (RBAC, Policy, Locks)
- Phase 4: Documentation and validation

## Cost Control
All resources were deployed using Azure free-tier or non-billable services.
No virtual machines or premium services were used.
