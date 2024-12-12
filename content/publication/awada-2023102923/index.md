---
title: Resource-aware multi-task offloading and dependency-aware scheduling for integrated
  edge-enabled IoV
authors:
- Uchechukwu Awada
- Jiankang Zhang
- Sheng Chen
- Shuangzhi Li
- Shouyi Yang
date: '2023-01-01'
publishDate: '2024-12-12T13:07:33.632390Z'
publication_types:
- article-journal
publication: '*Journal of Systems Architecture*'
doi: https://doi.org/10.1016/j.sysarc.2023.102923
abstract: Internet of Vehicles (IoV) enables a wealth of modern vehicular applications,
  such as pedestrian detection, real-time video analytics, etc., that can help to
  improve traffic efficiency and driving safety. However, these applications impose
  significant resource demands on the in-vehicle resource-constrained Edge Computing
  (EC) device installation. In this article, we study the problem of resource-aware
  offloading of these computation-intensive applications to the Closest roadside units
  (RSUs) or telecommunication base stations (BSs), where on-site EC devices with larger
  resource capacities are deployed, and mobility of vehicles are considered at the
  same time. Specifically, we propose an Integrated EC framework, which can keep edge
  resources running across various in-vehicles, RSUs and BSs in a single pool, such
  that these resources can be holistically monitored from a single control plane (CP).
  Through the CP, individual in-vehicle, RSU or BS edge resource availability can
  be obtained, hence applications can be offloaded concerning their resource demands.
  This approach can avoid execution delays due to resource unavailability or insufficient
  resource availability at any EC deployment. This research further extends the state-of-the-art
  by providing intelligent multi-task scheduling, by considering both task dependencies
  and heterogeneous resource demands at the same time. To achieve this, we propose
  FedEdge, a variant Bin-Packing optimization approach through Gang-Scheduling of
  multi-dependent tasks that co-schedules and co-locates multi-task tightly on nodes
  to fully utilize available resources. Extensive experiments on real-world data trace
  from the recent Alibaba cluster trace, with information on task dependencies and
  resource demands, show the effectiveness, faster executions, and resource efficiency
  of our approach compared to the existing approaches.
tags:
- Edge computing
- IoV
- Dependency-aware
- Execution time
- Resource efficiency
- Co-location
links:
- name: URL
  url: https://www.sciencedirect.com/science/article/pii/S1383762123001029
---
