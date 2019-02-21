---
layout: default
title: "ACM SIGCOMM 2019 Workshop on Optical Systems Design (OptSys)"
group: Workshops

dates:
    - info: Abstract submission deadline
      date: May 7, 2019
    - info: Acceptance notification for presentations
      date: May 24, 2019
    - info: Camera-ready due (1-page extended abstract)
      date: June 20, 2019
    - info: WorkShop
      date: Aug 19 or 23, 2019

committees:
    - role: General Chairs
      people:
       - name:        Chen Avin
         affiliation: Ben Gurion University, Israel
       - name:        Paolo Costa
         affiliation: Microsoft Research, UK
       - name:        Ramakrishnan Durairajan
         affiliation: University of Oregon, USA
       - name:        Manya Ghobadi
         affiliation: MIT, USA
       - name:        Stefan Schmid
         affiliation: University of Vienna, Austria

               

                   
---

# {{ page.title }}

### Call for Oral Presentations

Optical equipment is a fundamental component of modern systems. Today, nearly all wide-area, metro, and data center communications are carried over optical technology making optics a billion dollar industry. Optics is posed to play an even bigger role in next-generation networks. The high bandwidth and ultra-low latency requirements of modern Cloud-centric systems, such as machine learning and business analytics, are hard to meet in a cost-effective manner with traditional electrical devices. 

The OptSys workshop focuses on the design and implementation of optical networked systems for the next-generation Cloud infrastructure. These systems pose a number of research challenges spanning multiple research areas, e.g., physical layer, scheduling, synchronization, congestion control, orchestration, and topology reconfiguration, which require cross-layer and cross-disciplinary solutions. The workshop aims to bring together participants across the optics, networking, systems, and distributed algorithms community to jointly tackle these challenges and foster discussions and collaboration opportunities across these communities.
 
### Topics of Interest
Topics of interest include, but are not limited to, the following areas:  

- Cross-layer optimization problems
- Systems design leveraging recent advances in Optical technology
- Optical designs leveraging recent advances in Systems and Cloud
- Novel optical network architectures
- Emerging optical technologies impacting the design of rack-scale, data-center, metro, and wide-area networks
- New congestion control and network stacks for optical networks
- Scheduling and time synchronization algorithms for microsecond/nanosecond Optical Circuit Switches 
- Programming abstractions for orchestration between the SDN/IP layer and optical devices
- Reconfigurable optical topologies
- Analysis and experience with operational optical networks
- Models, algorithms, and theory for optical networks 
- Economic and cost aspects of optical networks
- Monitoring and diagnosis of performance issues across layers
- Free-space optical interconnects

### Submission Instructions
Submissions must be original, unpublished work, and not under consideration at another conference or journal. Submitted papers must use the new ACM template (using sigconf document type) from the  [2018 ACM consolidated template package](https://www.acm.org/publications/proceedings-template)[ (you can also use this barebone LaTeX template)](https://github.com/conference-websites/acmart-sigproc-template). The font size must be 9 points. The length of the final extended abstract with all its content except references must not exceed 1 page. The extended abstract must include author’s names and affiliations for single-blind peer reviewing by the PC. Use this link for submission: [https://optsys19.hotcrp.com](https://optsys19.hotcrp.com). Abstracts will not be published.  

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
