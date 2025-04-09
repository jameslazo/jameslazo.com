---
title: "Containerized CMS Deployment"
link: "https://medium.com/@james.lazo/containerized-cms-deployment-e735da873307"
image: "/img/cms.png"
description: "Deployed WordPress in a Multi-AZ load-balanced configuration, decoupling the data and application layers"
tags: ["DevOps","IaC","Terraform","Docker","containers","SQL","RDS","high availability","DNS","web development"]
fact: "a"
featured: true
---

- Designed a scalable, fault-tolerant WordPress deployment leveraging AWS services (EC2, ELB, RDS, EBS, S3, ECR, CloudFront, ACM) and Docker containers
- Decoupled data plane with AWS RDS, designing correct network topology for multi-AZ failover
- Developed extensive user data scripts in Bash to automate container deployment and external S3 and EFS volumes for shared persistent storage across instances

