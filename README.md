<div align="center">

# Karim Rabie Eladl
**AWS Cloud & Infrastructure | Terraform | GitHub Actions CI/CD**

[LinkedIn](https://www.linkedin.com/in/karim-rabiee) · [GitHub](https://github.com/karimrabiee)

</div>

## About

I build and document AWS infrastructure projects with an emphasis on secure networking, infrastructure as code, and deployment automation.

My hands-on portfolio includes a Terraform-based, two-Availability-Zone web application and a serverless image-processing pipeline. I focus on clear architecture, scoped IAM permissions, repeatable deployment steps, validation evidence, and honest documentation of limitations.

I'm interested in AWS Cloud Engineer, Cloud Support, Cloud Operations, and Junior DevOps opportunities.

## Core Technologies

- **AWS:** VPC, EC2, ALB, Auto Scaling, RDS, S3, Lambda, API Gateway, SQS, DynamoDB, CloudFront, WAF, IAM, KMS, CloudWatch, CloudTrail, Systems Manager
- **Infrastructure as Code:** Terraform
- **CI/CD:** GitHub Actions, AWS IAM OIDC
- **Operating Systems & Scripting:** Linux, Bash, Python
- **Networking:** TCP/IP, VLANs, OSPF, ACLs, NAT
- **Tools:** Git, Wireshark, Cisco Packet Tracer

## Selected Projects

### [AWS Secure & Highly Available 3-Tier Web Application](https://github.com/karimrabiee/AWS-Secure-Scalable-Web-Application-Architecture)

A two-AZ AWS web application with a public Application Load Balancer, private EC2 Auto Scaling instances, private RDS MySQL, AWS WAF, Secrets Manager, and Systems Manager access. Infrastructure is organized into Terraform modules and deployed through a guarded GitHub Actions workflow using AWS IAM OIDC.

**Documented validation:** two healthy ALB targets across Availability Zones, private instances and database, IMDSv2 enforcement, no inbound SSH rule, selected WAF test requests returning 403, and a least-privilege access check.

The repository distinguishes current Terraform `dev` evidence from historical manual-build tests and unverified production-like scenarios.

### [Global Secure Image Processing Pipeline](https://github.com/karimrabiee/global-secure-image-processing-pipeline)

An event-driven AWS image-processing project using presigned S3 uploads, Lambda, SQS with a dead-letter queue, DynamoDB metadata, and CloudFront Origin Access Control. Security components include IAM policies, KMS, WAF, CloudTrail, GuardDuty, and Security Hub.

The repository documents owner-run validation for upload, processing, metadata, private delivery, selected WAF tests, DLQ behavior, and optional data-plane replication. Multi-region ingestion recovery remains manual; this is not presented as automatic full-stack failover.

### [Secure Enterprise Network — CCNA Lab](https://github.com/karimrabiee/Secure-Enterprise-Network-CCNA)

A Packet Tracer network lab covering VLAN segmentation, routing, ACLs, NAT, and secure device management, with configuration evidence and verification notes.

## Certifications

- **AWS Certified Solutions Architect – Associate (SAA-C03)**
- **HashiCorp Certified: Terraform Associate (004)**

## Additional Training

- Kubernetes for Absolute Beginners — KodeKloud
- GitHub Actions — KodeKloud
- Docker for Absolute Beginners — KodeKloud
- Linux CLI Basics — Cybrary
- Cybersecurity for Beginners — MaharaTech

## Contact

- **LinkedIn:** https://www.linkedin.com/in/karim-rabiee
- **GitHub:** https://github.com/karimrabiee

