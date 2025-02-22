---
title: Ligase
display_order: 15
categories:
  - server
thumbnail: /docs/projects/images/ligase.png
description: Ligase is a Cloud-native Matrix home server written in Golang.
author: Finogeeks team
maturity: Late Beta
language: Go
license: AGPLv3
repo: https://github.com/finogeeks/Ligase
screenshot: /docs/projects/images/ligase_complete.png
---

Ligase is a Golang-based implementation of Matrix home server. It has been used in production by an array of financial institutions in various scenarios, including but not limited to OTC-style trading (i.e in the bond trading market), collaborative workspace, stock brokerage, retail banking and more.

While sticking to the Matrix spec as much as it could be, this implementation has adopted the following approaches:
* a Fan-in/Fan-out topology
* a CQRS (Command and Query Responsibility Segregation) pattern
* leveraging Kafka for event sourcing and stream message storage
* micro-service based with full leverage to containers (i.e. Docker) and container choreography platforms (i.e. Kubernetes/Rancher)

[For setup instructions, check the repo](https://github.com/finogeeks/Ligase).
