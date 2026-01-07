# Architecture

## Components
- Client: Browser
- DNS: Domain routing for designmyfragrance.com
- Compute: AWS EC2 instance
- Web Server: Apache 
- Application: WordPress
- Database: MySQL 
- HTTPS: Let’s Encrypt 

## Request Flow
1. User accesses the domain.
2. DNS routes traffic to EC2 instance.
3. HTTPS terminates at the server.
4. WordPress processes the request.
5. Data is retrieved/stored in the database.
