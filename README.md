# product-case-studies
Product design case study to improve visibility, auditability, and risk detection of cloud IAM permissions through user-centric workflows and clear permission mapping.
IAM Permissions Explorer – Product Design Assignment
Overview
IAM Permissions Explorer is a security-focused product design that helps cloud security engineers identify, analyze, and safely remediate excessive or unused IAM permissions across cloud accounts.
The solution prioritizes clarity, confidence, and least-privilege enforcement while minimizing the risk of breaking production systems.
Problem Statement
Cloud IAM policies often become overly permissive over time due to role reuse, manual changes, and lack of visibility into real permission usage.
Security engineers struggle to:
Identify unused or risky permissions
Understand the impact of removing permissions
Enforce least privilege without disrupting services
This leads to increased security risk and audit failures.
User Persona
Primary User: Cloud Security Engineer / Security Analyst
Responsibilities
Managing IAM permissions across AWS / GCP / Azure
Ensuring least privilege and compliance (SOC2, ISO, CIS)
Reducing security risk without service downtime
Pain Points
Large, unreadable IAM policies
No clear visibility into permission usage
Fear of breaking production while removing access
Solution Summary
IAM Permissions Explorer provides:
A clear dashboard highlighting risky IAM roles
Used vs unused permission visibility
Risk scoring to prioritize action
A simulation view to preview the impact of permission removal
Key Features
IAM role risk overview across cloud accounts
Permission usage tracking (last 30–90 days)
Highlighting high-risk permissions (*, admin access)
Safe-to-remove recommendations
change impact simulation before applying updates
Exportable reports for audits and reviews
