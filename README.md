# Self-Hosted Infrastructure Project

This project demonstrates a Linux-based self-hosted infrastructure built on Ubuntu Server.

## Overview
- Nginx configured as a reverse proxy  
- Python backend service  
- UFW firewall for access control  
- Fail2Ban for SSH protection  

## Functionality
- Nginx serves static content and routes requests to the backend  
- Backend is not directly exposed  
- Only ports 22 (SSH) and 80 (HTTP) are allowed  
- Fail2Ban protects against brute-force attacks  

## Documentation
Detailed documentation is available in the repository.
