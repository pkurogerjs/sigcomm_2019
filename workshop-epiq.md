---
layout: default
title: ACM SIGCOMM 2019 Workshop on the Evolution, performance, and Interoperability of QUIC (EPIQ 2019)
group: Workshops


dates:
    - info: Submission deadline
      date: May 6, 2019 
    - info: Notification deadline
      date: May 31, 2019
    - info: Camera-ready deadline
      date: June 20, 2019
    - info: Workshop
      date: August 19 or 23, 2019

committees:
    - role: Program Committee Chairs
      people:
       - name:        Jörg Ott
         affiliation: TU Munich
       - name:        Lars Eggert
         affiliation: NetApp
    

    
    - role: Program Committee Members
      people:
       - name:        Vaibhav Bajpai
         affiliation: TU Munich
       - name:        Olivier Bonaventure
         affiliation: UC Louvain
       - name:        Anna Brunström
         affiliation: Karlstad University
       - name:        Stephen Farrell
         affiliation: Trinity College Dublin
       - name:        Anja Feldmann
         affiliation: MPI-INF
       - name:        Simone Ferlin
         affiliation: Ericsson
       - name:        Gonca Gürsun
         affiliation: Ozyegin University
       - name:        Oliver Hohlfeld
         affiliation: Brandenburg University of Technology
       - name:        Michio Honda
         affiliation: NEC Labs
       - name:        Jana Iyengar
         affiliation: Fastly
       - name:        Subodh Iyengar
         affiliation: Facebook
       - name:        Mirja Kühlewind
         affiliation: ETH Zurich
       - name:        Balachander Krishnamurthy
         affiliation: AT&T
       - name:        Colin Perkins
         affiliation: University of Glasgow
       - name:        Eric Rescorla
         affiliation: Mozilla
       - name:        Ian Swett
         affiliation: Google
       - name:        Michael Welzl
         affiliation: University of Oslo 
         
                              
---

# {{ page.title }}

### Call for Papers
The transport protocol QUIC has emerged from a proprietary effort undertaken by Google to a next generation transport protocol being standardized in the Internet Engineering Task Force (IETF). While its original motivation and design was to support next-generation Web traffic using HTTP/2, embedding QUIC into the Internet architecture raises exciting challenges beyond the necessary engineering efforts. Google QUIC has seen deployment and motivated research papers measuring, extending, and evaluating QUIC from various perspectives.     

The ACM SIGCOMM Workshop on the Evolution, Performance, and Interoperability of QUIC (EPIQ) seeks to foster this emerging community. We invite researchers from academia and industry as well as engineers to explore novel ideas and future directions of QUIC and its interaction with applications and networks. This is the second instance of EPIQ, following its debut at ACM CoNEXT 2018.

EPIQ solicits two types of submissions, for presentation and discussion at the workshop: academic papers and posters & demos. Submissions of both types should focus on topics related to the rise of QUIC on the mobile and fixed Internet as well as enterprise and datacenter networks. Papers focusing on either the original flavor of QUIC currently deployed by Google or the upcoming IETF standard of QUIC are in scope.  We encourage submissions of demos supporting growing a community, e.g., about tools for protocol testing, deployment, and performance evaluation, among others. Open source tools are preferred.

### Topics of Interest

- Qualitative and/or quantitative comparisons of QUIC to other protocols
- Tools for QUIC interoperability testing, validation, and conformance
- Formal models for and verification of the QUIC protocol architecture
- Measurements of QUIC traffic in the wild and profiling of QUIC implementations
- Acceleration techniques, including hardware offloading or specific OS improvements
- Scalable QUIC implementations and load balancing
- Advanced QUIC features, including integration of multicast or multipath connectivity
- Peer-to-peer QUIC and NAT/firewall traversal
- New abstractions and APIs for QUIC as a general-purpose transport protocol
- Troubleshooting, managing and monitoring of QUIC traffic in the network
- Privacy and security aspects of QUIC or of systems impacted by QUIC
- New applications for QUIC (e.g., real-time interactive)
- Novel approaches for congestion control enabled by QUIC
- QUIC as a substrate for non-HTTP applications
- Downscaling QUIC for IoT or embedded use
- Deployment challenges and economic considerations for with QUIC

We encourage the submission of early results, negative results, and independently reproduced results of previously published work.


### Submission Instructions
EPIQ solicits two types of submissions, for presentation and discussion at the workshop: academic papers and posters & demos.

Paper submissions may be up to six pages in length, including all figures, tables, and appendices, but excluding references, for which extra pages may be used. The review process is single-blind. Papers must otherwise follow the formatting requirements of the main ACM SIGCOMM 2019 conference. Accepted papers will be published in the ACM Digital Library. Authors of accepted papers are required to present and discuss their papers in person at the workshop.

Poster & demo submissions may be up to two pages in length, and should describe the content of the poster or demo. Demo submissions must describe any venue requirements beyond WLAN connectivity and table space. Accepted poster & demo submissions will be highlighted in a very short “lightning talk” to advertise their appearance in a dedicated joint poster & demo session. Poster & demo submissions will not be included in the proceedings, but may be made available via the workshop website.

Please submit papers and poster&demo proposals at [https://epiq19.hotcrp.com/.](https://epiq19.hotcrp.com/).

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

