+++
title = "How We Migrated 30+ Kubernetes Clusters to Terraform"
date = 2025-06-02
draft = false
tags = ["Terraform", "Kubernetes", "Infrastructure", "DevOps", "Migration", "Automation"]
categories = ["Technical"]
[params]
  original_url = "https://medium.com/learnings-from-the-paas/how-we-migrated-30-kubernetes-clusters-to-terraform-cd2b1cef8b84"
+++

What does it take to migrate the deployment of 30+ Kubernetes clusters from a patchwork of CDK and Sceptre to Terraform without breaking production?
In this comprehensive post, I share our team's journey at Adevinta, covering the automated migration strategies, custom tooling decisions, and hard-learned lessons about rollbacks and local development workflows.

From simple Go-based import automation to sophisticated CI pipelines that prevented state conflicts, we built confidence through iterative waves—starting with low-risk IAM roles and progressing to critical VPCs and network routes. The post reveals why custom tooling sometimes beats off-the-shelf solutions and how hands-on learning scaled better than documentation for complex technical migrations.

If you're planning a similar infrastructure transformation or want to understand proven automation strategies for large-scale Terraform migrations, this detailed experience report offers both technical nuts-and-bolts and organizational insights. 