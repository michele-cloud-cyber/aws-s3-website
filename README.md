# # AWS S3 Static Website with CloudFront

## Overview
This project demonstrates how to host a static website on Amazon S3 and deliver it globally using AWS CloudFront.

## Architecture
- Amazon S3 for static website hosting  
- AWS CloudFront as CDN  
- GitHub Actions for CI/CD  

This project is deployed globally using AWS CloudFront CDN.

## What it does
- Hosts a static HTML website on S3  
- Uses CloudFront to improve performance and reduce latency  
- Automates deployment using GitHub Actions  

## Security
- The S3 bucket is not publicly exposed  
- CloudFront acts as the entry point  
- Access is managed using IAM credentials  

## CI/CD Pipeline
When code is pushed to the repository:
1. GitHub Actions is triggered  
2. AWS credentials are retrieved securely from GitHub Secrets  
3. Files are uploaded to S3  
4. The website is updated automatically  

## Technologies
- AWS S3  
- AWS CloudFront  
- GitHub Actions  
- IAM  

## Live Demo
The website is available at:  
https://d2esnkd0m5scu4.cloudfront.net

## What I learned
- How to design a secure static website architecture  
- How to use CloudFront for performance and security  
- How to automate deployments with CI/CD