# AWS S3 Static Website with CloudFront 🚀

##  Overview
This project demonstrates how to host a static website on AWS S3 and deliver it globally using CloudFront.

##  Architecture
- Amazon S3 (static website hosting)
- AWS CloudFront (CDN)
- GitHub Actions (CI/CD pipeline)

##  What it does
- Hosts a static HTML website on S3
- Uses CloudFront to improve performance and security
- Automatically deploys updates using GitHub Actions

##  Security
- S3 bucket is not publicly exposed
- CloudFront is used as the entry point
- Access is controlled via IAM user and access keys

##  CI/CD Pipeline
When I push code to GitHub:
1. GitHub Actions is triggered
2. AWS credentials are used securely (Secrets)
3. Files are uploaded to S3
4. Website is updated automatically

##  Technologies
- AWS S3
- AWS CloudFront
- GitHub Actions
- IAM

##  Demo
(Add your website link here)

##  What I learned
- How to design a secure static website architecture
- How to use CloudFront for low latency and security
- How to automate deployments with CI/