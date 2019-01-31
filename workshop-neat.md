---
layout: default
title: "ACM SIGCOMM 2019 Workshop on Networking for Emerging Applications and Technologies (NEAT 2019)"
group: Workshops

dates:
    - info: Workshop
      date: August 19 or 23 20, 2019
    - info: Camera-ready deadline
      date: TBA
    - info: Paper acceptance notification
      date: April 29, 2019
    - info: Submission deadline
      date: March 24, 2019
    - info: Paper registration deadline
      date: March 17, 2019

committees:
    - role: General Chairs
      people:
       - name:        K.K. Ramakrishnan
         affiliation: University of California, Riverside, USA
       - name:        Kiran Makhijani
         affiliation: Future Networks, Futurewei, Santa Clara, USA

    - role: Program Committee Chairs
      people:
       - name:        Richard Li
         affiliation: Future Networks, Futurewei, Santa Clara, USA
       - name:        Dipankar Raychaudhuri
         affiliation: Rutgers,USA 
       - name:        Stuart Clayman
         affiliation: University College London,UK

    - role: Technical Program Committee 
      people:
       - name:        Feng Qian  
         affiliation: UMN, USA
       - name:        Yong Liu
         affiliation: NYU, USA
       - name:        Marinos Charalambedes
         affiliation: UCL, UK 
       - name:        Daphne Tuncer
         affiliation: Imperial College. UK
       - name:        Muge Sayit
         affiliation: Ege University, Turkey 
       - name:        Lefteris Mamatas
         affiliation: University of Macedonia, Greece 
       - name:        Panagiotis Papadimitriou
         affiliation: University of Macedonia, Greece 
       - name:        Jo Zhang
         affiliation: Fujitsu Laboratories, USA
       - name:        Walter Ceroni
         affiliation: University of Bologna, Italy 
       - name:        Barbara Martini
         affiliation: CNIT, Italy 
       - name:        Stefano Secci
         affiliation: LIP6, France 
       - name:        Flavio Esposito
         affiliation: Saint Louis University, USA 
       - name:        Javier Rubio Loyola
         affiliation: CINVESTAV, Mexico
       - name:        Francesco Tusa
         affiliation: UCL, UK 
       - name:        Martin Serrano
         affiliation: DERI, Ireland
       - name:        Larysa Globa
         affiliation: Kiev Polytechnic Institute, Ukraine 
       - name:        Federica Paganelli
         affiliation: University of Florence, Italy 

  
                   
---

# {{ page.title }}


### Call for Papers

The 2nd NEAT workshop aims to provide a forum for both industry and academia to exchange ideas about network architectures, technologies, and protocols specifically in the context of emerging applications, with a particular focus on internetworking technologies that achieve accurate prescribed latency, high throughput, and meet service level objectives in complex and high scale networks.

Beyond the Internet of today, applications in Industrial Internet, Vehicular Networks, Tactile Internet, etc. are soon going to be the mainstream. A non-exhaustive list of such applications are Smart cities, Smart health, Smart agriculture, Industrial automation Remote-controlled operations, etc.; The insatiable demand of network resources from such new and emerging applications continue to grow and in the near future networks will be limited by how much and how fast can they deliver services within the framework of currently available technologies. 

“New Media” based applications are foreseen as well. They include not only Augmented Reality (AR) and Virtual Reality (VR) but hologram-based applications demanding a new communication methodology called Holographic Type Communications (HTC). Collectively they are going to influence not just the entertainment and gaming industry but are expected to inspire the next generation of immersive and visualization technologies in the fields of personal & social communications, education, design, medicine etc.

Overall, applications are advancing to be lot more immersive, remotely controlled, and fully automated. The interactions in future society, industry and manufacturing comprises of robotic automation of both mundane and sophisticated tasks, real-time interactive control between digital replica and their real counterparts. These applications mandate very tight resource constraints of reliability, performance, throughput, short latencies, etc. as well as programmability, customizability, and security. The challenge is a non-trivial one and asks researchers to think beyond traditional techniques of coarse-grained quality of service, congestion / management / traffic engineering, and flow control.

These applications may demand new kinds of absolute and precise communication attributes such as on-time, in-time and coordinated guarantees of services or alternatively, may allow networks with certain entropy or qualitative attributes such as tolerable degradation, partial packet reliability, recoverable loss of information as long as networks ensure that mandatory information is delivered intact.

The goal is to explore possibilities such as those beyond statistical resource scheduling in favor of deterministic packet delivery techniques, exploring new precision-based packet delivery, algorithms, switching and multiplexing technologies where ever necessary in large scale networks. Potential authors will be able to share their viewpoints, the latest research and project findings.
 
### Topics of Interest
We solicit stimulating, original, previously unpublished ideas on completed work, position papers, and/or work-in-progress papers in the form of extended abstracts. We further encourage papers that propose new research directions or could stimulate lively debate at the workshop. 

We invite submissions on a wide range of topics of interest, including, but not limited to:
- Architecture and frameworks for delivering high precision of services
- Convergence and optimizations of protocols for Industrial and Tactile networks
- Solutions for deterministic services in Industrial and Tactile networks
- Investigations, survey and techniques in data plane for Industrial and Tactile internet.
- Network challenges and requirements for emerging, resource-sensitive applications
- Mechanisms to support ultra-low-latency in packet based networks
- Internetworking frameworks for deterministic multi-access edge applications 
- Maximizing link utilization for high-throughput applications
- Architecture and protocols for reliable packet delivery
- Network security and privacy issues in Industrial and Tactile internet
- Resource allocation mechanisms deterministic and reliable data transmission
- Requirements and challenges in Holographic type communications 
- Networking requirements and challenges of VR/AR
- High-throughput transport for VR/AR and Holographic type communications
- Adaptive video streaming for network/user dynamics
- Video analytics and smart offloading for VR/AR
- Measurement study of existing VR/AR and HTC applications

### Submission Instructions
Submissions must be original, unpublished work, and not under consideration at another conference or journal. Submitted papers must use the new ACM template (using sigconf document type) from the  [2018 ACM consolidated template package](https://www.acm.org/publications/proceedings-template)[ (you can also use this barebone LaTeX template)](https://github.com/conference-websites/acmart-sigproc-template).The font size must be 9 points. The length of the final paper with all its content except references must not exceed 6 pages. Papers must include author’s names and affiliations for single-blind peer reviewing by the PC. Authors of accepted papers are expected to present their papers at the workshop. 

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

