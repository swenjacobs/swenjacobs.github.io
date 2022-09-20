---
permalink: /research/
title: "Research"
defaults:
  # _pages
  - scope:
      path: ""
      type: pages
    values:
      layout: single
      author_profile: true
---

My research mission is to make it easier to obtain systems with reliable correctness guarantees.

To this end, I am developing methods and tools for the rigorous analysis and design of software and hardware, based on formal verification and automatic synthesis.
Application domains include concurrent and distributed systems, security-critical software and hardware, and any kind of system that is expected to scale with the number of users or participants. 

# Projects

### Global Synchronization Protocols and Proving their Correctness (GSP&Co, [DFG research grant](https://gepris.dfg.de/gepris/projekt/497132954), 2022-)
This project aims at the further development of Global Synchronization Protocols (GPSs), an expressive computational model for distributed systems, and formal methods that can ensure their correctness. To this end, we study extensions of the basic model and develop verification approaches based on the framework of well-structured transition systems and on the cutoff technique, as well as methods for automatic repair and synthesis of GSPs.


### Automatic Synthesis of Distributed and Parameterized Systems (ASDPS, [DFG research grant](https://gepris.dfg.de/gepris/projekt/266796805), 2015-2019)
This project aimed at developing new methods and tools for the verification and synthesis of distributed and parameterized systems, such as communication protocols with a given or even a parametric number of components. To this end, we studied approaches for the verification of distributed and parameterized systems and generalized the underlying ideas to develop novel methods for the more difficult task of automatic synthesis. This included the development of efficient methods for the distributed synthesis problem with finite-state components, reductions from parameterized to distributed verification and synthesis, and methods for the synthesis of distributed infinite-state systems.
