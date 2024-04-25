##Introduction

This document is designed to showcase the technical implementation of the various services to effectively migrate on-prem environment to Amazon Web Services(AWS) to improve its security posture. The documents put emphasizes several and how they can be mitigated using various AWS services. Once the application migrates to the AWS cloud, it will be highly secure, scalable, resilient, and compliant.

Major problems in the existing application -

Improper Account Authorization
Highly vulnerable to DDoS attacks
No Patching Strategy
Slow Streaming, Downloads and Order Processing
No Backup Strategy
Improper data protection
Non-Compliant application
Insecure coding practices
Various tools and services leveraged to improve the security posture -

For Account Authorization, we will recommend AWS Identity and Access Management.
For DDoS attacks prevention, we will recommend Amazon Shield Advanced, Route 53, AWS WAF.
For Patch Management, we will recommend AWS Patch Manager.
For Fast Streaming, Downloads and Order Processing, we will recommend AWS CloudFront and S3 bucket.
For Backup, we will recommend AWS Backup Service and AWS S3 Glacier.
For Data protection, we will recommend Amazon Macie.
For Compliant, we will recommend PCI and PII Compliant.
For Secure coding practices, we will recommend AWS CodeGuru.
