---
layout: default
title: "ACM SIGCOMM 2019 Workshop on Network Meets AI & ML (NetAI 2019)"
group: Workshops

dates:
    - info: Paper submission deadline
      date: <mark>April 12, 2019 11:59 PST</mark>
    - info: Paper acceptance notification
      date: May 17, 2019 11:59 PST
    - info: Camera-ready deadline
      date: June 20, 2019 11:59 PST

committees:
    - role: General Chairs
      people:
       - name:        Marco Canini
         affiliation: KAUST
       - name:        Jon Crowcroft 
         affiliation: University of Cambridge
       - name:        Nick Feamster
         affiliation: Princeton University
       - name:        Jennifer Rexford
         affiliation: Princeton University
       - name:        Walter Willinger
         affiliation: NIKSUN Inc.
       - name:        Nicholas Zhang
         affiliation: Huawei

    
    - role: Program Committee Chairs
      people:
       - name:        Theophilus Benson 
         affiliation: Brown University
       - name:        Arpit Gupta
         affiliation: UC Santa Barbara
       - name:        Junchen Jiang
         affiliation: University of Chicago
         
    - role: Program Committee Members
      people:
       - name:        Mohammad Alizadeh 
         affiliation: MIT, USA
       - name:        Behnaz Arzani 
         affiliation: Microsoft Research, USA
       - name:        Sujata Banerjee 
         affiliation: VMWare, USA
       - name:        Marco Canini 
         affiliation: KAUST, Saudi Arabia
       - name:        Aakanksha Chowdhery 
         affiliation: Google Brain, USA
       - name:        Jon Crowcroft 
         affiliation: University of Cambridge, UK
       - name:        Nick Feamster 
         affiliation: Princeton, USA
       - name:        Chuanxiong Guo 
         affiliation: Bytedance, USA
       - name:        Xin Jin 
         affiliation: John Hopkins Univ, USA
       - name:        Srikanth Kandula 
         affiliation: Microsoft Research, USA
       - name:        Changhoon Kim 
         affiliation: Barefoot, USA
       - name:        Bryan Larish 
         affiliation: Verizon, USA
       - name:        Dan Li 
         affiliation: Tsinghua Univ, China
       - name:        Ihsan Ayyub Qazi 
         affiliation: LUMS, Pakistan
       - name:        Matthew Roughan 
         affiliation: University of Adelaide, Australia
       - name:        Rijurekha Sen 
         affiliation: IIT Delhi, India
       - name:        Michael Schapira 
         affiliation: Hebrew University of Jerusalem, Israel
       - name:        Chen Tian 
         affiliation: Nanjing University, China
       - name:        Shobha Venkataraman 
         affiliation: AT&T, USA
       - name:        Walter Willinger 
         affiliation: NIKSUN Inc., USA
       - name:        Ying Zhang 
         affiliation: Facebook, USA
       - name:        Ben Zhao 
         affiliation: University of Chicago, USA
---

# {{ page.title }}

### Call for Papers
In recent years, we have witnessed: (1) development of fully programmable, protocol-independent data planes and languages for programming them; and (2) the emergence of new platforms, tools, and algorithms for Artificial Intelligence (AI) and Machine Learning (ML).  These technological advancements and scientific innovations create exciting new opportunities. On the one hand, the scientific innovations in the area of AI/ML have the potential to simplify network management (monitoring as well as control). On the other hand, recent advancements in the area of networking technology have the potential to improve the performance of AI and ML systems.  

**AI/ML for Networking.** AI & ML have been successfully applied to various perceptual domains, including computer vision, natural language processing, and voice recognition. In addition, ML techniques are showing impressive results in new domains such as medicine, finance, and astronomy, to name a few. This success in non-perceptual domains suggests that ML techniques could be successfully applied to simplify network management. For at least a decade, networking researchers, equipment vendors, and Internet service providers alike have argued for “autonomous” or “self-driving” networks, where network management and control decisions are made in real time and in an automated fashion. Yet, building such “self-driving” networks that are practically deployable has largely remained unrealized.  The coupling of the programmable control of software-defined networking (SDN) with scientific innovations in AI and ML promises unprecedented opportunities for querying high-volume and high-velocity, distributed streaming data at scale; this new technical capability can provide the necessary information to the many different network monitoring and control tasks that self-driving networks should perform automatically and autonomously. Building a self-driving network is one of the “grand challenges” of networking research today. Realizing this vision will require incorporating the collective expertise and input from the networking research community.

**Networking for AI/ML.** Distributed processing systems for Artificial Intelligence (AI) and Machine Learning (ML), such as Hadoop, Spark, Storm, GraphLab, TensorFlow etc., are widely used by industry. Networking is a well-known bottleneck for AI & ML systems. Though the recent technological advances, such as reconfigurable switches, programmable NICs, RDMA- over-converged Ethernet (RoCE) and GPU direct, etc., provide exciting opportunities to improve the performance of AI and ML solutions, but the ever-increasing complexity of networks composed of a heterogeneous set of targets makes effective monitoring, modeling, auditing, and overall control of network traffic difficult if not impossible. Hence there is a need for more powerful methods to solve the challenges faced in the design, deployment, and management of networks for distributed processing systems for AI and ML. 

This workshop will provide a forum for networking researchers to present and share their latest research on building self-driving networks and coupling the technological advances in networking with scientific innovations in AI and ML. This workshop seeks contributions from experts in areas such as network programming, formal methods, control theory, distributed systems, machine learning, data science, data structures and algorithms, and optimization who share in the excitement of realizing the vision of self-driving networks as well as improving the performance of AI and ML solutions. 
 
### Topics of Interest

- Design and implementation of systems for flexible and scalable network monitoring
- Design and implementation of closed-loop systems (modular) that use monitoring to drive network control (e.g., congestion control, TE, QoE, QoS, etc.) with minimal human intervention
- Unified programming languages/abstractions for expressing both network monitoring (streaming as well as offline) and control tasks
- Algorithms to train learning models for inferring network attacks, device/service fingerprinting, congestion, failures, QoE metrics, etc. in (real time) at scale
- New data structures, algorithms, network protocols, and switch architectures for storing and/or processing network monitoring data (single-site and/or distributed settings)
- Query-planning algorithms to scale the execution of network-monitoring queries
- Techniques to collect and analyze network data in a privacy-preserving manner
- Learning models to capture the relationship between network events and control actions
- Design data structures and algorithms for consistently and correctly updating the distributed states (e.g., forwarding table entries) 
- Examples of design choices informed by control-theoretic findings (e.g., hard limits, unavoidable tradeoffs)
- New use cases for self-driving networks in DCs, WANs, IXPs, wireless networks, cloud networks, CDNs, home networks, etc.
- Case studies demonstrating (dis)advantages of choosing AI/ML techniques for networking over more traditional ones
- New topology, algorithms, network protocols, and switch architectures for AI/ML applications
- Techniques to optimize distributed AI, ML and graph processing algorithms/systems with new networking options (e.g., PISA switches,  SmartNICs, RDMA, NVLink, etc.)
- Measurement and analysis of network traffic for AI & ML systems
        
### Submission Instructions
Submissions must be original, unpublished work, and not under consideration at another conference or journal. Submitted papers must be at most six (6) pages long, including all figures, tables, references, and appendices in two-column 10pt ACM format. This six-page limit does not include the reproducibility section (see below). Papers must include authors names and affiliations for single-blind peer reviewing by the PC. Authors of accepted papers are expected to present their papers at the workshop. Please submit your paper via https://netai19.hotcrp.com.

### Research Reproducibility

As the interest in coupling networking and AI/ML is growing, we recognize that reproducible work becomes ever more important, in particular, due to the somewhat inherent lack of interpretability associated with ML methods. 

- To encourage reproducibility,  authors are allowed an additional **but optional** page in addition to the six pages. This additional space is meant to be used to explicitly discuss the reproducibility and interpretability of their solution.  In general, all authors are encouraged to consult the [reproducibility checklist](https://www.cs.mcgill.ca/~jpineau/ReproducibilityChecklist.pdf) to verify that their submission is reproducible. 

- In NetAI, we want to encourage authors to go the extra mile and release their research artifacts. We plan to reward the reproducible work with special [ACM badging](https://www.acm.org/publications/policies/artifact-review-badging). All the accepted papers at the workshop are eligible for artifacts review. 

**Note:** While NetAI encourages reproducibility, the reviewers will not place any additional preferences, while reviewing,  towards papers with a reproducibility section.

### Authors Take Note
{% include workshop_authorstakenote.html %}

### Registration
{% include workshop_registration.html %}

### Camera-ready instructions
{% include camera-ready_ws_inst.html %}



### <i class="fa fa-calendar"></i> Important Dates

{% include dates2.html dates=page.dates %}

### Committees

{% include committees.html committees=page.committees %}


