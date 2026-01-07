# DesignMyFragrance 

A custom perfume e-commerce website built using WordPress and deployed on AWS.  
This repository documents the cloud architecture, deployment workflow and security considerations of the project.

## Project Overview
. Built a perfume e-commerce website using WordPress
. Deployed and hosted on AWS EC2
. Configured domain, DNS and HTTPS
. Applied basic security hardening and access controls
. Documented architecture and deployment steps

## Architecture Overview
Users → DNS → EC2 (Web Server + WordPress) → Database

📄 See `docs/architecture.md`

## Tech Stack
. WordPress
. AWS EC2
. Web Server: Apache 
. Database: MySQL 
. HTTPS: Let’s Encrypt 

## Deployment Summary
. EC2 provisioning and security group configuration
. Web server, PHP, and database setup
. WordPress installation and configuration
. Domain mapping and HTTPS enablement
. Production-level security hardening

## Security Considerations
. SSH key-based access
. Restricted network exposure
. Minimal plugins and regular updates
. HTTPS enabled for data protection

## Screenshots
📁 Located in `docs/screenshots/`

## Future Enhancements
. Migrate database to AWS RDS
. Store media assets in Amazon S3
. Add WAF and rate-limiting
. Enable monitoring and alerts (CloudWatch)

## License
MIT
