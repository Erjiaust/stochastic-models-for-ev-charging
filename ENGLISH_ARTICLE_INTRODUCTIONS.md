# English Introductions to the Articles in This Repository

## Overview

The papers in this repository explore how to make electric-vehicle (EV) charging and battery services more scalable, efficient, and economically viable. Together, they cover complementary perspectives: stochastic and fluid queueing theory, large-scale optimization, pricing and mechanism design, and infrastructure planning. Across different problem settings, the shared objective is to improve service quality for EV users while reducing operational costs and pressure on the power grid.

## 1) *A Fluid Model of an Electric Vehicle Charging Network*  
**Angelos Aveklouris, Maria Vlasiou, Bert Zwart**

This paper develops a rigorous measure-valued fluid model for EV charging networks with realistic operational constraints, including limited parking spaces, heterogeneous vehicles, and power-flow restrictions in distribution grids. The authors bridge stochastic network dynamics and deterministic fluid approximations, showing how large-scale system behavior can be captured through tractable limits. A key contribution is integrating electricity-network physics (including AC and linearized Distflow models) into the charging-allocation framework and establishing continuity properties for power allocation. The work offers a mathematically grounded foundation for studying congestion, stability, and control in urban EV charging systems.

## 2) *An Exponential Cone Programming Approach for Managing Electric Vehicle Charging*  
**Li Chen, Long He, Yangfang (Helen) Zhou**

This study addresses the operational challenge of scheduling EV charging under uncertain arrivals and demand charges, which can dominate electricity bills for charging providers. The authors formulate the problem as a large-scale stochastic program and propose exponential cone programming (ECP) approximations that remain computationally tractable at industrial scale. They develop methods for both uncapacitated and capacitated charging settings, provide theoretical performance guarantees, and benchmark against sample average approximation and semidefinite DRO approaches. Using data-calibrated experiments, the paper shows that ECP can deliver faster computation and strong cost performance, making it a practical method for real-world charging operations and tariff-aware planning.

## 3) *Bounds and Limit Theorems for a Layered Queueing Model in Electric Vehicle Charging*  
**Angelos Aveklouris, Maria Vlasiou, Bert Zwart**

This paper models EV charging as a layered queueing system in which parking spots and the electricity grid jointly constrain service. EVs have random parking and charging times, and customers may leave before being fully charged. The authors focus on service effectiveness, especially the fraction of vehicles that depart fully charged, and derive explicit bounds for key operating regimes. They further develop fluid and diffusion approximations (including Halfin-Whitt-type limits), enabling deeper performance analysis beyond exact Markovian solutions. The paper is valuable for understanding how congestion emerges from both physical capacity and stochastic demand, and how asymptotic methods can guide planning decisions.

## 4) *Scaling Up Electric-Vehicle Battery Swapping Services in Cities: A Joint Location and Repairable-Inventory Model*  
**Wei Qi, Yuli Zhang, Ningwei Zhang**

This article studies how to design city-scale battery-swapping infrastructure when swapping is decentralized but charging can be centralized. The authors capture the coupled dynamics of swapping demand, battery inventory, charging, and transportation through analytical extensions of repairable-inventory theory, then embed these insights in a joint location-inventory optimization model. Because the resulting objective is nonconvex and nonconcave, they propose an exact algorithmic framework combining constraint generation and parameter search, achieving major computational gains. The managerial insight is nuanced: pooling alone is often insufficient, but access to faster centralized charging can substantially reduce total battery stock and improve system economics.

## 5) *Smart Charging of Electric Vehicles: An Innovative Business Model for Utility Firms*  
**Owen Q. Wu, Safak Yucel, Yangfang (Helen) Zhou**

This paper presents smart charging as a mechanism-design problem for utility firms that own or operate charging stations. Instead of charging vehicles immediately after plug-in, the utility offers customers a menu of price-completion-time pairs and then schedules charging to exploit time-varying electricity procurement costs. The authors characterize implementable optimal policies and analyze both public and private utility objectives. Empirical calibration with U.S. electricity market data shows meaningful potential gains in cost and emissions reductions from delay-aware charging and differentiated pricing. The study offers an actionable business model for aligning customer flexibility with grid and sustainability benefits.

## 6) *Wait Time Based Pricing for Queues with Customer-Chosen Service Times*  
**Chen-An Lin, Kevin Shang, Peng Sun**

This paper examines dynamic pricing in a queue where customers observe wait time and choose both whether to join and how long to receive service. Motivated in part by EV fast-charging stations, the model is formulated as a continuous-time control problem with delay differential equations. The authors identify an optimal wait-time-dependent pricing structure with a non-monotonic pattern, including both congestion and compensation effects, and provide a constructive method for obtaining the policy. Compared with flat pricing, the dynamic policy improves revenue and can also improve social welfare in many scenarios. The framework is broadly relevant to service systems where waiting and service duration are jointly behavior-driven.
