+++
title = "When VerticalPodAutoscaler Goes Rogue: How an Autoscaler Took Down Our Cluster"
date = 2025-03-11
draft = false
tags = ["Kubernetes", "Autoscaling", "Incident Response", "DevOps"]
categories = ["Technical"]
[params]
  original_url = "https://medium.com/learnings-from-the-paas/when-verticalpodautoscaler-goes-rogue-how-an-autoscaler-took-down-our-cluster-8c7479d5be3c"
+++

What happens when a Kubernetes autoscaler misconfiguration spirals out of control?
In this post, together with my colleagues [Fabian Selles](https://www.linkedin.com/in/fabi%C3%A1n-sell%C3%A9s-rosa-37108b27/) and [Tanat Lokejaroenlarb](https://www.linkedin.com/in/tanatloke/), we share our experience with a real-world incident story: a minor alert led to a cluster-wide crisis, relentless pod evictions, and a deep debugging journey.
Learn how we traced the root cause to a hidden rate limit, the lessons we learned about VPA internals, and how open-source code access saved the day.

If you're fascinated by incident response, Kubernetes reliability, or want to avoid similar pitfalls, this summary will give you a taste of the drama and the technical takeaways.
