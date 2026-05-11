AWS Secure Static Website Hosting (S3 + CloudFront)

Author: Yousuf Ali Shaik | AWS Cloud Support Engineer

Overview

This project demonstrates foundational AWS Cloud storage, networking, and security concepts. I have architected and deployed a highly available, secure static website to host my digital resume.

Architecture & Technologies Used

Amazon S3: Configured an S3 bucket for static website hosting, utilizing strict Bucket Policies and Object Ownership rules to block public access at the bucket level.

Amazon CloudFront: Deployed a Content Delivery Network (CDN) distribution to cache the website globally, reducing latency.

Origin Access Control (OAC): Secured the S3 bucket so that it can only be accessed via the CloudFront distribution, preventing direct, unencrypted access to the S3 URLs.

AWS Certificate Manager (ACM): Provisioned an SSL/TLS certificate to ensure all traffic is encrypted via HTTPS.

Skills Demonstrated: S3 Bucket Policies, CloudFront Distribution Configuration, CDN Caching, SSL/TLS Encryption, Origin Access Control.
