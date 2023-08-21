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

## Projects

### Advancing Formal Methods to Support the Creation of Novel, Homogeneous and Hybrid Resilient Distributed Systems and Technologies
#### (FM-CReST, [joint DFG/FNR Luxembourg grant](https://gepris.dfg.de/gepris/projekt/513487900), 2023-)
Computer systems in critical infrastucture or autonomous vehicles remain worthwhile targets for cyberattacks and must be protected to withstand, tolerate and safely operate through such attacks. Due to the growing complexity of systems, adversaries have gained an advantage, which requires us to anticipate that some attacks might be successful. Resilience techniques allow systems to continue to work correctly, even if cyberattacks have been partially successful. But for these techniques to be applicable, they have to match the system's structure, in particular how the individual components of such a system interact. Existing resilience techniques are limited in these interaction patterns and developing new techniques for more elaborate patterns remains a difficult and error prone task. In the FM-CReST project, researchers from CISPA, Germany, and from the SnT of University of Luxembourg have joined forces to research a new class of highly automated, easy-to-use tools to assist developers in constructing provably correct resilience protocols. We do so by co-designing protocols for systems with complicated interaction patterns, while observing this protocol construction and developing the tools needed to simplify such developments in the future.

### Global Synchronization Protocols and Proving their Correctness 
#### (GSP&Co, [DFG research grant](https://gepris.dfg.de/gepris/projekt/497132954), 2023-)
This project aims at the further development of Global Synchronization Protocols (GPSs), an expressive computational model for distributed systems, and formal methods that can ensure their correctness. To this end, we study extensions of the basic model and develop verification approaches based on the framework of well-structured transition systems and on the cutoff technique, as well as methods for automatic repair and synthesis of GSPs.

### Global Synchronization Protocols and Proving their Correctness 
#### (GSP&Co, [DFG research grant](https://gepris.dfg.de/gepris/projekt/497132954), 2023-)
This project aims at the further development of Global Synchronization Protocols (GPSs), an expressive computational model for distributed systems, and formal methods that can ensure their correctness. To this end, we study extensions of the basic model and develop verification approaches based on the framework of well-structured transition systems and on the cutoff technique, as well as methods for automatic repair and synthesis of GSPs.


### Automatic Synthesis of Distributed and Parameterized Systems
#### (ASDPS, [DFG research grant](https://gepris.dfg.de/gepris/projekt/266796805), 2015-2019)
This project aimed at developing new methods and tools for the verification and synthesis of distributed and parameterized systems, such as communication protocols with a given or even a parametric number of components. To this end, we studied approaches for the verification of distributed and parameterized systems and generalized the underlying ideas to develop novel methods for the more difficult task of automatic synthesis. This included the development of efficient methods for the distributed synthesis problem with finite-state components, reductions from parameterized to distributed verification and synthesis, and methods for the synthesis of distributed infinite-state systems.
