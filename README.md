\# AWS Static Website Hosting

## Project Overview

This project demonstrates how to host a secure and highly available static website using Amazon Web Services (AWS).

The solution leverages:

* Amazon S3
* Amazon CloudFront
* Amazon Route53
* AWS IAM

The website content is stored in Amazon S3 and delivered globally through CloudFront CDN for improved performance and security.

---

## Architecture

User → Route53 → CloudFront → Amazon S3

---

## AWS Services Used

### Amazon S3

* Static website hosting
* Object storage
* Versioned content storage

### CloudFront

* Global Content Delivery Network (CDN)
* HTTPS delivery
* Improved performance

### Route53

* DNS management
* Domain routing

### IAM

* Least privilege access
* Security best practices

---

## Deployment Steps

1. Create S3 bucket.
2. Upload website files.
3. Enable static website hosting.
4. Create CloudFront distribution.
5. Configure Route53 DNS records.
6. Validate website accessibility.
7. Secure permissions using IAM.

---

## Skills Demonstrated

* AWS Cloud Architecture
* Static Website Hosting
* Content Delivery Networks
* DNS Configuration
* Cloud Security
* IAM Best Practices
* AWS Networking

---

## Author

Musaab Mohamedani

AWS Certified Solutions Architect – Associate (SAA-C03)

GitHub: https://github.com/Mus7ab
