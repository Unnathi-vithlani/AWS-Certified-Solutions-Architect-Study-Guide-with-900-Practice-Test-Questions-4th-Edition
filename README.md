# AWS Certified Solutions Architect Study Guide with 900 Practice Test Questions, 4th Edition
## Study Kit README

> **Book Reference:** *AWS Certified Solutions Architect Study Guide with 900 Practice Test Questions, 4th Edition* (O'Reilly)

---

## 📁 Kit Structure

```
AWS Certified Solutions Architect Study Guide .../
├── All Exercise Assignment/     ← Hands-on lab PDFs (Labs 1–8)
├── Aws in detail/               ← Deep-dive topic PDFs & reference docs
└── kata/                        ← Project exercise ("Where's Fluffy")
```

---

## 🧪 All Exercise Assignment — Labs 1–8

These are hands-on lab assignments aligned to the SAA-C03 exam domains. Complete them in order.

| Lab | Topic | File |
|-----|-------|------|
| Lab 1 | Identity and Access Management (IAM) | `AWS LAB 1-Identity and Access Management.pdf` |
| Lab 2 | EC2 – Elastic Compute Cloud | `AWS Lab 2- EC2 Lab.pdf` |
| Lab 3 | Storage and Database Services | `AWS Lab 3- Storage and Database Services Lab.pdf` |
| Lab 4 | VPC, Route 53, and CloudFront | `AWS Lab 4 - AWS VPC, Route53, and CloudFront Lab.pdf` |
| Lab 5 | Auto Scaling | `AWS Lab 5- Auto-scaling Lab.pdf` |
| Lab 6 | CloudWatch, CloudTrail, SNS, SQS | `AWS Lab 6 - CloudWatch, CloudTrail, SNS, SQS.pdf` |
| Lab 7 | Secure Architectures | `AWS Lab 7 - Secure Architectures.pdf` |
| Lab 8 | High-Performing Architectures | `AWS Lab 8 - High-Performing Architectures.pdf` |

---

## 📚 AWS In Detail — Reference PDFs

Deep-dive study materials covering every major SAA-C03 topic area.

### Core Compute & Networking
- `EC2.pdf` — Instance types, pricing, AMIs, placement groups
- `VPC.pdf` — Subnets, routing, NACLs, Security Groups, peering
- `AWSELB.pdf` — Elastic Load Balancing (ALB, NLB, CLB)
- `AWSAutoScaling.pdf` — Launch templates, scaling policies
- `CloudFront.pdf` — CDN, edge locations, distributions
- `Route53.pdf` — DNS, routing policies, health checks

### Storage
- `S3.pdf` — Buckets, versioning, lifecycle, storage classes
- `EBS_EFS.pdf` — Block and file storage, snapshots
- `CloudStorage.pdf` — Comprehensive cloud storage overview

### Databases
- `Databases.pdf` — RDS, Aurora, DynamoDB, ElastiCache

### Security & Identity
- `AWS_IAM.pdf` — Roles, policies, users, MFA
- `AWSSecurity.pdf` — KMS, Shield, WAF, GuardDuty
- `CloudSecurity.pdf` — Cloud security architecture
- `Security Guidance v5 20240708.pdf` — Up-to-date security best practices (2024)

### Serverless & Application Services
- `AWSServerless.pdf` — Lambda, API Gateway, Step Functions
- `CloudApps.pdf` — Application services overview
- `DecouplingWorkFlows.pdf` — SQS, SNS, EventBridge

### Monitoring & Management
- `AWSCloudWatch.pdf` — Metrics, alarms, logs, dashboards
- `AWSAutomation.pdf` — CloudFormation, Systems Manager
- `CloudResourceManagement.pdf` — Resource tagging, Config, Organizations

### Big Data & Analytics
- `AWSBigData.pdf` — Kinesis, EMR, Redshift, Athena

### Broader Cloud Context
- `AWSOverview.pdf` — AWS global infrastructure, shared responsibility
- `Virtualization.pdf` — Hypervisors, containers, VM fundamentals
- `TopThreatstoCloudComputing202420240805.pdf` — CSA top threats (2024 edition)

### Bonus: AZ-500 Practice Questions (Azure)
- `AZ-500_Full_520_Questions.docx` — 520 Azure Security Engineer practice questions
- `AZ-500_Mock_Papers_2_Sets.docx` — Two full mock exams

---

## 🐾 kata/ — Project Exercise: "Where's Fluffy"

A capstone-style kata project for practicing AWS architecture design.

| File | Description |
|------|-------------|
| `Where's Fluffy.docx` | Project requirements and write-up |
| `Where's Fluffy Presentation.pptx` | Architecture presentation deck |
| `Where's Fluffy Presentation.pdf` | PDF export of the presentation |
| `Where's Fluffy.pdf` | PDF export of the project doc |
| `aws_cost_formulas_html.html` | AWS cost calculation reference formulas |

---

## 🗺️ Recommended Study Path

### Phase 1 — Foundations (Week 1–2)
1. Read `AWSOverview.pdf` for the big picture
2. Complete **Lab 1** (IAM) — everything else depends on it
3. Study `AWS_IAM.pdf` in depth

### Phase 2 — Core Services (Week 2–4)
4. EC2: `EC2.pdf` → **Lab 2**
5. Storage: `S3.pdf`, `EBS_EFS.pdf` → **Lab 3**
6. Networking: `VPC.pdf`, `CloudFront.pdf`, `Route53.pdf` → **Lab 4**

### Phase 3 — Advanced Topics (Week 4–6)
7. Auto Scaling: `AWSAutoScaling.pdf`, `AWSELB.pdf` → **Lab 5**
8. Monitoring: `AWSCloudWatch.pdf` → **Lab 6**
9. Security: `AWSSecurity.pdf`, `CloudSecurity.pdf` → **Lab 7**
10. High Availability: `DecouplingWorkFlows.pdf`, `AWSServerless.pdf` → **Lab 8**

### Phase 4 — Exam Prep (Final Week)
11. Review `Security Guidance v5 20240708.pdf` and `TopThreatstoCloudComputing202420240805.pdf`
12. Work through the O'Reilly book's 900 practice questions
13. Complete the **"Where's Fluffy"** kata as an architecture design exercise

---

## 🎯 SAA-C03 Exam Domain Mapping

| Exam Domain | Weight | Key Files in This Kit |
|-------------|--------|-----------------------|
| Design Secure Architectures | 30% | IAM, AWSSecurity, CloudSecurity, Lab 1, Lab 7 |
| Design Resilient Architectures | 26% | ELB, AutoScaling, VPC, Lab 4, Lab 5, Lab 8 |
| Design High-Performing Architectures | 24% | EC2, S3, Databases, CloudFront, Lab 2, Lab 3 |
| Design Cost-Optimized Architectures | 20% | AWSOverview, aws_cost_formulas_html, Lab 3 |

---

## 📝 Notes

- All labs are PDF walkthroughs — you'll need an AWS account (free tier works for most labs)
- The book referenced on O'Reilly covers all 900 practice questions; labs here are the hands-on companion exercises
- The AZ-500 materials are a bonus — useful if you plan to pursue Azure certs after AWS
- Use the `aws_cost_formulas_html.html` file locally in a browser for quick cost estimation reference

---

*Good luck! 🚀*
