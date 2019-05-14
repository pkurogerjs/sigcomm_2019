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
    - role: Program Chairs
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

Optical equipment is a fundamental component of modern systems. Today, nearly all wide-area, metro, and data center communications are carried over optical technology making optics a billion dollar industry. Optics is poised to play an even bigger role in next-generation networks. The high bandwidth and ultra-low latency requirements of modern Cloud-centric systems, such as machine learning and business analytics, are hard to meet in a cost-effective manner with traditional electrical devices. 

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
Submissions include an extended abstract for oral presentation at the workshop. Authors are encouraged to submit an extended abstract that includes previously published work.  Submitted papers must use the new ACM template (using sigconf document type) from the  [2018 ACM consolidated template package](https://www.acm.org/publications/proceedings-template)[ (you can also use this barebone LaTeX template)](https://github.com/conference-websites/acmart-sigproc-template). The font size must be 9 points. The length of the final extended abstract with all its content except references must not exceed 1 page. The extended abstract must include author’s names and affiliations for single-blind peer reviewing by the PC. Use this link for submission: [https://optsys19.hotcrp.com](https://optsys19.hotcrp.com). Abstracts will not be published.  

### Registration
{% include workshop_registration.html %}

### Speakers
**Keren Bergman**
<div style="overflow:hidden;">
<div style="float:left;width:15%">
<img style="display:block;width:100%" src="{{site.baseurl}}/files/workshop/OptSys/Bergman_photo.jpg" alt="" />
</div>
<div style="float:right;width:80%;">
<p>Keren Bergman is the Charles Batchelor Professor of Electrical Engineering at Columbia University where she also serves as the Faculty Director of the Columbia Nano Initiative. Bergman (Ph.D. M.I.T. 1994) leads the Lightwave Research Laboratory encompassing multiple cross-disciplinary programs at the intersection of computing and photonics. She serves on the Leadership Council of the American Institute of Manufacturing (AIM) Photonics leading projects that support the institute’s silicon photonics manufacturing capabilities and Datacom applications. Bergman is a Fellow of the Optical Society of America (OSA) and IEEE.</p>
</div>
</div>

**George Porter**
<div style="overflow:hidden;">
<div style="float:left;width:15%">
<img style="display:block;width:100%" src="{{site.baseurl}}/files/workshop/OptSys/george-porter.jpg" alt="" />
</div>
<div style="float:right;width:80%">
<p>
George Porter is an Associate Professor at UC San Diego and the Co-Director of UCSD's Center for Networked Systems, working on topics related to data-intensive computing and data center networking.  He has received a Google Focused Research Award, a NetApp Faculty Fellowship, a Cisco Research award, the NSF CAREER award, and the USENIX NSDI 2017 “Test of Time” award. He received his B.S. from the University of Texas at Austin and his Ph.D. from the University of California, Berkeley.
</p>
</div>
</div>

**Eitan Zahavi**
<div style="overflow:hidden;">
<div style="float:left;width:15%">
<img style="display:block;width:100%" src="{{site.baseurl}}/files/workshop/OptSys/eitan_photo_2019.JPG" alt="" />
</div>
<div style="float:right;width:80%">
<p>
Dr. Eitan Zahavi, just joined Amazon AWS Networking as a Senior Principal Engineer.Previously, Eitan led the Mellanox network architecture group focusing on cluster level performance.He also acted as a co-chair of the IBTA technical working group.He received his Ph.D. about “Forwarding in Compute Clusters” in 2015 and Bs.C. in 1987 both at the EE department of the Technion, Israel institute of technology.
</p>
</div>
</div>

### Camera-ready instructions
{% include camera-ready_ws_inst.html %}


### <i class="fa fa-calendar"></i> Important Dates

{% include dates2.html dates=page.dates %}

### Committees

{% include committees.html committees=page.committees %}
