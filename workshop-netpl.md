---
layout: default
title: "ACM SIGCOMM 2019 Workshop on Networking and Programming Languages (NetPL 2019)"
group: Workshops

dates:
    - info: Deadline to submit talk proposals (1 page, minimum 10 pt point)
      date: April 8, 2019
    - info: Acceptance notifications
      date: April 15, 2019
    - info: Workshop
      date: August 23, 2019

committees:
    - role: Workshop Organizers
      people:
       - name:        Costin Raiciu 
         affiliation: University Politehnica of Bucharest
       - name:        Ryan Beckett
         affiliation: Microsoft Research

    - role: General Chairs
      people:
       - name:        Marco Canini
         affiliation: KAUST
                           
---

# {{ page.title }}

### Call for Papers
The NetPL workshop provides a forum to bring together researchers and practitioners from the fields of programming languages, formal methods, software verification and networking.

**Motivaiton:**
Recent technological trends, such as Programmable Network Hardware, Software-Defined Networking, Network Functions Virtualization, have created an opportunity to design, implement and deploy exciting new applications with relative ease.  Networking can be improved by designing suitable languages for expressing operator’s needs, but such languages are rarely designed by language specialists. The result is a practitioner-driven development of languages that does not draw on the wealth of experience available in the PL community. Moreover, programs to be deployed in the network have been shown to have different types of bugs (e.g. recent P4 verification work); in deployment such bugs could cause damage to networks and prompt a new ossification wave that programmable networks are trying to undo.

NetPL 2019 will address this mismatch by bridging between the areas of PL, formal verification and networking, thus enabling language specialists to apply the wealth of theoretical and practical knowledge on designing and implementing languages and compilers that has been developed over the years. It would allow networking specialists to build systems that are provably robust and that can rely on the tooling and reasoning frameworks for such languages that in turn can improve the degree to which reasoning can be automated. This can make possible higher-level control of aspects of computer networks, the low-level details of which are managed automatically.

This is the fifth NetPL workshop; in prior years NetPL was collocated with Ecoop, Sigcomm and POPL. Talks from the previous editions of the workshop are on YouTube.

### Topics of Interest 
Language-centric research of the following aspects of computer networks is in scope:
- Specification and topology
- Automated verification, testing and measurement
- Packet/traffic generation
- Packet/traffic analysis
- Security
- Resource availability or control
- Policy languages
- Interoperability between networking-related languages
- Composition of networking-related languages

Practical aspects of languages, particularly if oriented towards solving networking problems, are also in scope:
- How to model and prototype languages rapidly
- What semantic structures are best suited to the networking domain

### Format 
The workshop will consist of invited and contributed talks, mini-tutorials, and a panel discussion to encourage interaction among attendees. The workshop is intended to stimulate dialog between communities, and not interfere with the publication of the ideas discussed -- there are larger venues for this, and with more archival record, for such dissemination. To this end, presenters may talk about previously published results, current developments, or speculate on future needs. 

Participation in the workshop is open to everyone. To give a talk, please submit a one page description of the proposed talk; these will be lightly reviewed by the workshop co-chairs.
 
**Paper Submission:**

Please submit your paper via [https://sigcomm19netpl.hotcrp.com/](https://sigcomm19netpl.hotcrp.com/). 

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
