---
title: "How Netflix Simplified Batch Compute with Kueue"
url: "https://netflixtechblog.com/how-netflix-simplified-batch-compute-with-kueue-87860682629c?source=rss----2615bd06b42e---4"
date: "2026-06-22"
author: "Netflix Technology Blog"
feed_url: "https://medium.com/feed/netflix-techblog"
---
By Alvin Bao , Alex Petrov , Jennifer Lai , Aidan Sherr , and Samartha Chandrashekar As a part of the journey to transition Netflix’s compute infrastructure to be more Kubernetes-native, we have leaned into incorporating components from the Kubernetes ecosystem into our container platform Titus . One example of this is our use of Kueue , a cloud-native job queueing system for batch workloads, which has largely replaced the custom queuing and scheduling logic in our homegrown managed batch solution Compute Managed Batch (CMB). In this post, we’ll give an overview of what motivated the migration
