# DesignMyFragrance — WordPress E-commerce on AWS

A custom perfume e-commerce website built using WordPress and deployed on AWS.  
This repository documents the cloud architecture, deployment workflow, and security considerations of the project.

## Project Overview
• Built a perfume e-commerce website using WordPress  
• Deployed and hosted on AWS EC2  
• Configured custom domain and DNS routing  
• Enabled HTTPS for secure communication  
• Applied basic security hardening and access controls  
• Documented architecture, deployment steps, and security practices  

## Architecture Overview
• Users → DNS → EC2 (Web Server + WordPress) → Database  
• Architecture details documented in `docs/architecture.md`

## Tech Stack
• WordPress  
• AWS EC2  
• Web Server: Apache   
• Database: MySQL 
• HTTPS: Let’s Encrypt   

## Deployment Summary
• Provisioned EC2 instance and configured security groups  
• Installed and configured web server, PHP, and database  
• Installed and customized WordPress  
• Connected domain via DNS records  
• Enabled HTTPS and verified secure access  
• Applied production-level security hardening  

## Security Considerations
• SSH key-based authentication  
• Restricted network exposure (HTTP/HTTPS only)  
• Minimal plugins and regular updates  
• HTTPS enabled for data protection  
• Backup and recovery considerations documented  

## Screenshots
• Screenshots of the website UI are available in `docs/screenshots/`

## Future Enhancements
• Migrate database to AWS RDS  
• Store media assets in Amazon S3  
• Add WAF and rate limiting  
• Enable monitoring and alerts using CloudWatch  

