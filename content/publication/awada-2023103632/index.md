---
title: 'EdgeDrones: Co-scheduling of drones for multi-location aerial computing missions'
authors:
- Uchechukwu Awada
- Jiankang Zhang
- Sheng Chen
- Shuangzhi Li
- Shouyi Yang
date: '2023-01-01'
publishDate: '2024-12-12T13:07:33.640571Z'
publication_types:
- article-journal
publication: '*Journal of Network and Computer Applications*'
doi: https://doi.org/10.1016/j.jnca.2023.103632
abstract: Low altitude platform (LAP) unmanned aerial vehicles (UAVs), also called
  drones, are currently being exploited by Edge computing (EC) systems to execute
  complex resource-hungry use cases, such as virtual reality, smart cities, autonomous
  vehicles, etc., by attaching portable edge devices on them. However, a typical drone
  has limited flight time, coupled with the resource-constrained attached edge device,
  which can jeopardize aerial computing missions if they are not holistically taking
  into consideration. Moreover, the fundamental challenge is how to co-schedule multi-drone
  among multi-location where EC services are needed, such that drones are scheduled
  to maximize the utility from the activities while meeting computing resource and
  flight time constraints. Therefore, for a given fleet of drones and tasks across
  disjointed target locations in a city, we derive a machine learning (ML) linear
  regression model that estimates these tasks resource requirement and execution time.
  Leveraging this estimation values, we jointly consider each drone’s flight time
  availability and its attached edge device resource capacity, and formulate a novel
  Multi-Location Capacitated Mission Scheduling Problem (MLCMSP) that selects suitable
  drones and co-schedules their flight routes with the least total distance to visit
  and execute tasks at the target locations. Then, we show that faster scheduling
  and execution of complex tasks at each location, while considering the inter-task
  dependencies is important to achieve effective solution for our MLCMSP. Hence, we
  further propose EdgeDrones, a variant bin-packing optimization approach through
  gang-scheduling of inter-dependent tasks that co-schedules and co-locates tasks
  tightly so as to achieve faster execution time, as well as to fully utilize available
  resources. Extensive experiments on Alibaba cluster trace with information on task
  dependencies (about 12,207,703 dependencies) show that EdgeDrones achieves up to
  73% higher resource utilization, up to 17.6 times faster executions, and up to 2.87
  times faster flight travel time compared to the baseline approaches.
tags:
- Edge computing
- Aerial computing
- Vehicle routing
- Linear regression
- Execution time
- Resource efficiency
- Co-location
links:
- name: URL
  url: https://www.sciencedirect.com/science/article/pii/S1084804523000516
---
