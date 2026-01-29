# Static Website Hosting on AWS using S3, CloudFront & GitHub Actions

## 📌 Project Overview
This project demonstrates how to host a static website on AWS using **Amazon S3** and **CloudFront CDN**, with an automated **CI/CD pipeline using GitHub Actions**.  
The setup ensures fast global delivery, secure access, and automated deployment on every code update.

---

## Architecture
User → CloudFront (CDN) → S3 Bucket (Static Website)

---

## 🛠️ Technologies Used
- AWS S3 (Static Website Hosting)
- AWS CloudFront (CDN)
- AWS IAM (Access Management)
- GitHub
- GitHub Actions (CI/CD)
- HTML, CSS, JavaScript

---

## 🚀 Features
- Static website hosting using S3
- Global content delivery using CloudFront
- Automated deployment using GitHub Actions
- CloudFront cache invalidation to reflect latest changes
- Secure access using IAM policies
- Cost-optimized architecture (Free Tier friendly)

---

## 🔄 CI/CD Workflow
1. Developer pushes code to GitHub repository  
2. GitHub Actions workflow is triggered  
3. Files are automatically uploaded to S3  
4. CloudFront cache is invalidated  
5. Latest website changes are reflected globally  

---
