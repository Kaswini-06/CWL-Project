# CWL-Project
# DevOps Internship Assignment 🚀

 Project Overview
This project demonstrates core DevOps skills including:
- Secure server access using SSH
- Docker-based application deployment
- Container monitoring
- User access control and permissions
- Firewall configuration for security

Project Structure

Task 1: SSH Configuration
- Configured SSH access to server
- Implemented passwordless login using SSH keys

Task 2: Docker Deployment
- Installed Docker
- Created Dockerfile and index.html
- Built Docker image
- Ran container on port 8000


 Task 3: Container Monitoring
- Created monitoring script using `docker stats`
- Logged CPU and memory usage
- Added timestamps for each entry
- Automated logging using cron job (every minut

Task 4: User & Permissions
- Created dedicated user: `monitoruser`
- Assigned ownership of monitoring directory
- Restricted access using permissions (`700`)
- Verified access control

 Task 5: Firewall Configuration
- Installed and configured UFW firewall
- Allowed:
  - SSH (port 22) from specific IP
  - HTTP (port 80)
  - Application port (8000)
- Enabled firewall and verified rules


##  Conclusion
This project successfully demonstrates end-to-end DevOps workflow:
- Secure access
- Application deployment
- Monitoring automation
- Access control
- Network security

---

