---
title: "Distributed and Local Scheduling Algorithms for mmWave Integrated Access and Backhaul"
collection: publications
permalink: /publication/2022-TNet-IAB-Scheduling
excerpt: 'We consider the stability region of a mmWave integrated access and backhaul (IAB) network with stochastic arrivals and time-varying link rates. In the scheduling of links, we consider a limit on the number of RF chains, and the half-duplex constraint which occurs due to the wireless backhaul links. We characterize the stability region, and propose a back-pressure policy for the IAB network under the RF chains and half-duplex constraints.'
date: 2022-03-17
venue: ' IEEE/ACM Transactions on Networking'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/9737293'
citation: 'S. Gopalam, S. V. Hanly and P. Whiting,  &quot;Distributed and Local Scheduling Algorithms for mmWave Integrated Access and Backhaul,&quot; in <i>IEEE/ACM Transactions on Networking</i>, vol. 30, no. 4, pp. 1749-1764, Aug. 2022.'
---
**Abstract:** We consider the stability region of a mmWave integrated access and backhaul (IAB) network with stochastic arrivals and time-varying link rates. In the scheduling of links, we consider a limit on the number of RF chains, and the half-duplex constraint which occurs due to the wireless backhaul links. We characterize the stability region, and propose a back-pressure policy for the IAB network under the RF chains and half-duplex constraints. To implement the back-pressure policy, it is required to compute the maximum weighted schedule, which is a complex problem in general. For the IAB network, we present a distributed message passing scheme to compute the maximum weighted schedule, with almost linear complexity. We also investigate a class of local scheduling policies for the IAB network, which have a smaller stability region in general, but require no message passing. We characterize the stability region for the local class, and show that it is same as the global stability region, if the link rates are un-varying. We provide a bound on the gap between local and global regions when the links are time varying. We propose a local max-weight algorithm which achieves the stability region for the local class, and we present numerical results.

<!-- [Download paper here](https://ieeexplore.ieee.org/abstract/document/10137766) -->

<!-- Recommended citation: 'S. Gopalam, S. V. Hanly and P. Whiting,  &quot;Distributed Resource Allocation and Flow Control Algorithms for mmWave IAB Networks,&quot; in <i>IEEE/ACM Transactions on Networking</i>, vol. 31, no. 6, pp. 3175-3190, Dec. 2023.' -->