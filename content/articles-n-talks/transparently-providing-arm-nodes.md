+++
title = "Transparently providing ARM nodes to 4,000 engineers"
date = 2025-03-13
draft = false
tags = ["Kubernetes", "ARM", "Cloud Platform", "DevOps"]
categories = ["Technical"]
[params]
  original_url = "https://medium.com/learnings-from-the-paas/transparently-providing-arm-nodes-to-4-000-engineers-3264ba6738d2"
+++

How do you enable thousands of engineers to seamlessly use ARM nodes in Kubernetes without manual intervention? In this article, together with my colleague [Miguel Bernabeu](https://www.linkedin.com/in/miguelbernadi/),
we detail the technical and organizational challenges of introducing ARM architecture into a large-scale, multi-tenant platform. Discover how we leveraged mutating webhooks,
optimized multi-arch builds, and open-sourced our solution to make ARM adoption transparent and efficient for over 4,000 developers.

If you're interested in platform engineering, Kubernetes internals, or cost optimization at scale, this summary will guide you to the full technical journey and open-source release.
