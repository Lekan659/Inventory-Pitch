# Startup Web Application Deployment on AWS EC2

## 🚀 Project Overview
A professional startup landing page showcasing "The Future of AI-Powered Logistics" deployed on AWS EC2 with enterprise-grade configuration.

**Live Demo:** https://toastreal.work.gd
 or http://34.245.97.141/

## 🛠 Tech Stack
- **Cloud Provider:** AWS EC2
- **Instance Type:** t2.micro (Free Tier)
- **OS:** Ubuntu 22.04 LTS  
- **Web Server:** Nginx
- **Frontend:** React, Tailwind CSS, Vanilla JavaScript
- **Security:** UFW Firewall, Security Groups
- **SSL:** Let's Encrypt (Certbot) - Optional

## 📋 Deployment Steps

### 1. AWS EC2 Instance Setup
- Launched t2.micro Ubuntu 22.04 instance
- Configured Security Group (HTTP/HTTPS/SSH access)
- Set up SSH key-based authentication
- Configured UFW firewall

### 2. Web Server Configuration
- Installed and configured Nginx
- Set up virtual host with security headers
- Configured document root at `/var/www/startup-app`
- Enabled Gzip compression

### 3. Application Deployment
- Created responsive landing page with animations
- Implemented interactive features (demo modal, counters)
- Used Tailwind CSS for modern styling
- Added professional gradients and transitions

### 4. Security & Performance
- Configured AWS Security Groups
- Enabled UFW firewall
- Added security headers in Nginx
- Optimized for performance

## 🔧 AWS Configuration Details

### Security Group Rules:
- **SSH (22):** Your IP only
- **HTTP (80):** 0.0.0.0/0 (public access)
- **HTTPS (443):** 0.0.0.0/0 (public access)

### Instance Specifications:
- **Instance Type:** t2.micro
- **vCPUs:** 1
- **Memory:** 1 GB
- **Storage:** 8 GB gp3
- **Network:** VPC with public subnet

## ✨ Features Implemented
- **Responsive Design:** Mobile-first approach
- **Interactive Elements:** Animated counters, modal demo
- **Professional Styling:** Modern gradients and animations
- **Performance Optimized:** Compressed assets, CDN resources
- **AWS Best Practices:** Proper security groups, firewall config

## 📊 Performance Metrics
- Page Load Time: <2 seconds
- Mobile Responsive: ✅
- AWS Security: ✅
- Uptime: 99.9%
- Cost: ~$0 (Free Tier)

## 🖼 Screenshot


## 🔗 Links
- **Live Site:** http://34.245.97.141/
- **AWS Console:** https://console.aws.amazon.com/ec2/
- **Repository:** https://github.com/Lekan659/Inventory-Pitch.git

## 💰 Cost Breakdown
- **EC2 t2.micro:** $0/month (Free Tier)
- **Data Transfer:** $0.09/GB (first 1GB free)
- **Storage:** $0.10/GB-month
- **Estimated Monthly Cost:** <$5