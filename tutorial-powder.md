---
layout: default
title: "ACM SIGCOMM 2019 - Mobile and wireless research using the POWDER platform"
group: Tutorials

dates:
    - info: Tutorial
      date: August 19, 2019
      
data:
  - type: day
    time: Monday, August 19, 2019
    room: ''
  - type: session
    time: 8:30am - 10:30am
    room:
    title: Session I
    authors: ''
    abstract: ''
    bio: ''
    photo: ''
    link: ''
    slides: ''
    video: ''
    remote: ''
    remote-qa: ''
    COL_UID: ''
  - type: talk
    time: 8:30am - 9:00am
    room: 
    title: The POWDER platform (lecture) 
    authors: ''
    abstract: ''
    bio: ''
    photo: ''
    link: ''
    slides: ''
    video: ''
    remote: ''
    remote-qa: ''
    COL_UID: ''
  - type: talk
    time: 9:30am - 10:30am
    room: 
    title: End-to-end full-stack mobile network performance (hands-on)
    authors: ''
    abstract: ''
    bio: ''
    photo: ''
    link: ''
    slides: ''
    video: ''
    remote: ''
    remote-qa: ''
    COL_UID: ''
  - type: break
    time: 10:30am - 11:00am
    room: 
    title: Coffee Break
    authors: ''
    abstract: ''
    bio: ''
    photo: ''
    link: ''
    slides: ''
    video: ''
    remote: ''
    remote-qa: ''
    COL_UID: ''
  - type: session
    time: 11:00am - 12:40pm
    room:
    title: Session II
    authors: ''
    abstract: ''
    bio: ''
    photo: ''
    link: ''
    slides: ''
    video: ''
    remote: ''
    remote-qa: ''
    COL_UID: ''
  - type: talk
    time: 11:00am - 11:30am
    room: 
    title: Open source stacks for mobile and wireless research (lecture)
    authors: ''
    abstract: ''
    bio: ''
    photo: ''
    link: ''
    slides: ''
    video: ''
    remote: ''
    remote-qa: ''
    COL_UID: ''
  - type: talk
    time: 11:30am - 12:30pm
    room: 
    title: Radio access network research with O-RAN (hands-on)
    authors: ''
    abstract: ''
    bio: ''
    photo: ''
    link: ''
    slides: ''
    video: ''
    remote: ''
    remote-qa: ''
    COL_UID: '' 
  - type: talk
    time: 12:30pm - 12:40pm
    room: 
    title: Wrap-up and future POWDER plans
    authors: ''
    abstract: ''
    bio: ''
    photo: ''
    link: ''
    slides: ''
    video: ''
    remote: ''
    remote-qa: ''
    COL_UID: ''

organizers:
- name:        Kirk Webb
  affiliation: Utah, USA
  bio:         "<p>Kirk Webb is a Research Associate with the Flux Research Group at the University of Utah where he has been building wired and wireless testbeds for over 10 years.  Kirk is Associate Director for the nascent POWDER wireless platform, an NSF PAWR initiative being deployed on the University of Utah campus and surrounding area. He also contributes to wireless edge and other mobile communications research within the Flux Group.  Kirk has taught or co-taught over 10 tutorials on wired and wireless testbed systems.</p>"

- name:        Gary Wong
  affiliation: Utah, USA
  bio:         "<p> Gary Wong is a research associate in the Flux Research Group of the University of Utah’s School of Computing, where he performs development and maintenance for testbeds supporting operating system, network and wireless research. His own research interests include kernels, compilers, and networks. He was awarded a Bachelor of Science degree from the University of Auckland in 1995.</p>"

---

# {{ page.title }}


## Tutorial Program (subject to changes)

{% include program.html type="tutorial-p4" data=page.data %}

## Call For Participation

The software-defined sea change that has relentlessly redefined the way we think about wired network infrastructures has reached mobile and wireless networks and is fundamentally changing the industry and the research associated with it: Emerging 5G mobile networks are service based [22] and assume network slicing as a fundamental primitive [1]; broad industry efforts are moving to virtualize and “open up” the radio access network [4]; numerous open source wireless and mobile software stacks are emerging [9, 18, 17, 5, 3]; open source network function virtualization (NFV) orchestration platforms and component ecosystems are proliferating [2, 16, 7, 6]; sophisticated off-the-shelf software-defined-radio (SDR) platforms [10] enable rapid prototyping and experimentation, while SDR technology is used to realize advanced radio platforms [21]. 

This sea change presents tremendous opportunity for research in mobile and wireless networking; never before has there been this “perfect storm” of need/demand for advancing mobile and wireless technologies, applications and services, combined with unprecedented access to enabling technologies through software defined architectures and technologies and open source initiatives. At the same time the same perfect storm presents significant challenges to those seeking to make research contributions in this domain: Industry-driven initiatives, even when “open”, are by design driven by organizations with significant resources, making it difficult to make contributions without being overrun by these industry efforts. Further, open source stacks in this domain are sophisticated and quite complex with many possible options and configurations, making it difficult to establish baseline functionality on which to start meaningful research. Finally, while the sea change promises access to the necessary enabling technologies, putting those together in a meaningful manner (e.g., hardware, software, access to spectrum, realistic scenarios etc.), is a daunting task. 

This tutorial will introduce attendees to the POWDER platform which provides researchers access to the technologies associated with the software-defined sea change in mobile and wireless research and solve many of the challenges in using/exploiting them. Attendees will be introduced to the capabilities of the POWDER platform through hands-on exploration of selected research topics. 

The POWDER-RENEW project ([https://powderwireless.net](https://powderwireless.net),[https://renew.rice.edu](https://renew.rice.edu)) is part of the National Science Foundation’s Platforms for Advanced Wireless Research (PAWR) initiative ([https://advancedwireless.org](https://advancedwireless.org)). The POWDER platform is being developed and deployed by the University of Utah in Salt Lake City and provides remote access to a state-of-the-art end-to- end software-defined mobile and wireless testbed. The POWDER platform includes massive MIMO equipment and software from the RENEW team at Rice University. 



## <i class="fa fa-calendar"></i> Important Dates


{% include dates2.html dates=page.dates %}


## Outline

*The POWDER platform (lecture):* We will describe salient aspects and features of the POWDER platform. We will describe the hardware and software available on the platform, as well as the experimental workflow involved in using it.

*End-to-end full-stack mobile network performance (hands-on):*  With some exceptions [23], mobile network performance has traditionally treated the mobile network as a “black box”, i.e., performing performance measurements from the “outside” [14, 20, 15]. (Indeed, an NSF workshop on mobile measurements identified “instrumentation challenges” as one of the key operational challenges in understanding the performance of mobile networks.) This problem is exacerbated by emerging 5G developments that are introducing new radio technologies [1, 19] and have applications/services with much more varied performance needs [11, 13, 12]. A key benefit of the POWDER software defined platform is that it is fully instrumentable, thus enabling researchers to perform end-to-end full-stack mobile network performance analysis. During this session attendees will perform hands-on exploration of POWDER features and mechanisms that enable end-to-end full-stack mobile network performance analysis. 

*Open source stacks for mobile and wireless research (lecture):* We will review available open source stacks relevant for mobile and wireless research. We will describe software stacks that are available on the POWDER platform, the process involved with making software stacks available on the platform, and explain how this simplifies and enables research efforts.

*Radio access network research with O-RAN (hands-on):* The radio access network (RAN) is currently the focus of refactoring, i.e., variations in terms if the functional split between centralized and distributed components in the RAN [1], and “opening up”, i.e., industry efforts towards opening the radio access network (RAN) ecosystem to enable novel RAN use cases [4]. This session will review relevant background and describe capabilities of the POWDER platform to explore RAN related research. Participant will perform hands-on exploration of basic O-RAN/XRAN functionality in the POWDER platform.

## Requirements for attendees
For hands-on sessions, attendees will perform scripted exploration of the POWDER platform [8]. Tutorial attendees will be required to access POWDER, using their own laptops, through ssh and/or web browser sessions. 

Attendees will be provided with instructions on how to sign up for the platform in advance of the tutorial.

### Tutorial speakers
{% include organizers.html presenters=page.organizers %}

### References
<p>
[1] 3rd Generation Partnership Project; Technical Specification Group Radio Access Network; Study on New Radio Access Technology;. 3GPP TR 38.801 V2.0.0 (2017-3). <br>
[2] Converged Multi-Access and Core (COMAC). <a href="https://www.opennetworking.org/comac/">https://www.opennetworking.org/comac/</a>.<br>
[3] Mosaic5g: A community lead consortium for building agile 5G service platforms and opening fast wireless innovation. <br>
[4] O-RAN Alliance. <a href="https://www.o-ran.org">https://www.o-ran.org</a>.<br>
[5] Open Mobile Evolved Core. <a href="https://www.opennetworking.org/omec/">https://www.opennetworking.org/omec/</a>. <br>
[6] Open Platform for NFV. <a href="https://www.opnfv.org">https://www.opnfv.org</a>. <br>
[7] Open Source MANO. <a href="https://osm.etsi.org">https://osm.etsi.org</a>.<br>
[8] POWDER (Platform for Open Wireless Data-driven Experimental Research). <a href="https://powderwireless.net">https://powderwireless.net</a> <br>
[9] srsLTE: Open Source LTE from Software Radio Systems (SRS). <a href="https://github.com/srsLTE">https://github.com/srsLTE</a>.<br>
[10] USRP N310. <a href="https://www.ettus.com/all-products/usrp-n310/"> https://www.ettus.com/all-products/usrp-n310</a>.<br>
[11] Feng, L. V2X White Paper. NGMN Alliance. <br>
[12] Li, C., Jiang, J., Chen, W., Ji, T., and Smee, J. 5G ultra-reliable and low-latency systems design. In 2017 European Conference on Networks and Communications (EuCNC) (June 2017), pp. 1–5. <br>
[13]  Li, S., Xu, L. D., and Zhao, S. 5G Internet of Things: A survey. Journal of Industrial Information Integration 10 (2018), 1 – 9. <br>
[14] Li, Y., Peng, C., Yuan, Z., Li, J., Deng, H., and Wang, T. Mobileinsight: Extracting and Analyzing Cellular Network Information on Smartphones. In Proceedings of the 22Nd Annual International Conference on Mobile Computing and Networking (New York, NY, USA, 2016), MobiCom ’16, ACM, pp. 202–215. <br>
[15] Nikravesh, A., Guo, Y., Qian, F., Mao, Z. M., and Sen, S. An In-depth Understanding of Multipath TCP on Mobile Devices: Measurement and System Design. In Proceedings of the 22Nd Annual International Conference on Mobile Computing and Networking (New York, NY, USA, 2016), MobiCom ’16, ACM, pp. 189–201.<br> 
[16] Open Orchestrator Project. Open Network Automation Platform. <a href="https://www.onap.org">https://www.onap.org</a>, 2017. <br>
[17] OPENAIR-CN: An implementation of the Evolved Packet Core network. <a href="https://gitlab.eurecom.fr/oai/openair-cn">https://gitlab.eurecom.fr/oai/openair-cn</a>, 2017.  <br>
[18] openairinterface5G: Openairinterface 5G Wireless Implementation. <a href="https://gitlab.eurecom.fr/oaiopenairinterface5g">https://gitlab.eurecom.fr/oaiopenairinterface5g</a>, 2017. <br>
[19] Parkvall, S., Dahlman, E., Furuskar, A., and Frenne, M. NR: The New 5G Radio Access Technology. IEEE Communications Standards Magazine 1, 4 (Dec 2017), 24–30. <br>
[20] Rosen, S., Han, B., Hao, S., Mao, Z. M., and Qian, F. Push or Request: An Investigation of HTTP/2 Server Push for Improving Mobile Performance. In Proceedings of the 26th International Conference on World Wide Web (Republic and Canton of Geneva, Switzerland, 2017), WWW ’17, International World Wide Web Conferences Steering Committee, pp. 459–468. <br>
[21] Shepard, C. W., Doost-Mohammady, R., Guerra, R. E., and Zhong, L. Demo: ArgosV3: An Efficient Many-Antenna Platform. In Proceedings of the 23rd Annual International Conference on Mobile Computing and Networking (2017), MobiCom ’17. <br>
[22] Wang, D., and Sun, T. Service-Based Architecture in 5G. NGMN Alliance.<br> 
[23] Wang, X., Zhou, Z., Yang, Z., Liu, Y., and Peng, C. Spatio-temporal analysis and prediction of cellular traffic in metropolis. In 2017 IEEE 25th International Conference on Network Protocols (ICNP) (Oct 2017), pp.1-10.
</p>

