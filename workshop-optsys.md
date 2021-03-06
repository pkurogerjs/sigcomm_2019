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
      date: August 19, 2019

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

### keynote speakers
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

**T. S. Eugene Ng**
<div style="overflow:hidden;">
<div style="float:left;width:15%">
<img style="display:block;width:100%" src="{{site.baseurl}}/files/workshop/OptSys/Eugene.png" alt="" />
</div>
<div style="float:right;width:80%">
<p>
T. S. Eugene Ng is a Professor of Computer Science and Electrical & Computer Engineering at Rice University. He was selected as an Alfred P. Sloan Research Fellow and received an IBM Faculty Award in 2009. He also received a National Science Foundation CAREER Award in 2005, and is a Kavli Fellow. He holds a B.S. in Computer Engineering with distinction and magna cum laude from University of Washington, a M.S. and a Ph.D. in Computer Science from Carnegie Mellon University. In recent years, he has pioneered a research direction called Big data and Optical Lightpaths Driven (BOLD) networked systems, which explores new networked systems architectures and mechanisms, such as optics, to support sophisticated big data application network traffic workloads in a scalable, affordable and environmentally sustainable manner, and develops innovative big data processing systems, applications and algorithms that are made possible by the new networked systems architectures and mechanisms.
</p>
</div>
</div>

**Hitesh Ballani**
<div style="overflow:hidden;">
<div style="float:left;width:15%">
<img style="display:block;width:100%" src="{{site.baseurl}}/files/workshop/OptSys/hiteshBallani.jpg" alt="" />
</div>
<div style="float:right;width:80%">
<p>
I am a researcher in the System and Networking group at Microsoft Research in Cambridge, UK. My research aims to build systems and networks for next-generation data centers. Our current focus is on developing optical technologies for the cloud. Earlier, I graduated from Cornell University where I indulged in follies like Scalable Internet Routing and Network Management.
<br />
I enjoy working on real-world problems, particularly ones that span technical domains. For example, as part of the Predictable Data Centers project (2010-15), we developed technologies for enabling predictable performance across shared cloud resources like networking and storage. Applying traditional networking ideas to the storage stack was key to a lot of our innovation, leading to the SMB Bandwidth Limiting feature in Windows Server 2012 R2, and inspiring the end-to-end Storage QoS feature in Windows Server 2016. This post discusses our journey from whiteboard discussions to a shipping product.
<br />
With our Optics for the Cloud effort (2016-), we are now delving deeper into the data center stack. Our team brings together hardware, optics, networking and application-level expertise to take a cross-stack view towards developing optical technologies that could underpin the next-generation of our cloud infrastructure.
</p>
</div>
</div>


### Workshop Program
{% include program-online.html type="optsys" %}

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






### <i class="fa fa-calendar"></i> Important Dates

{% include dates2.html dates=page.dates %}

### Committees

{% include committees.html committees=page.committees %}
