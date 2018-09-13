## OpenMessaging Project Organization  
[OpenMessageing](http://openmessaging.cloud) is a cloud native, vendor-neutral open specification for distributed messaging:

**Messaging tool maintainers:** "Provide a unified messaging interface for all services" is an unreasonable goal for any one particular messaging project or vendor. OpenMessaging essentially amortizes this work.        
**Software developers who build and deploy applications:** These developers want to use whatever messaging platform that work best within their organization's infrastructure, and they want to choose those tools independent of whatever third-party (open-source) software packages they happen to have built around.      
**Software developers who contribute to widely-used software:** Inasmuch as this software needs to exist within a microservices deployment, it must integrate with whatever messaging tool(s) its diverse users already depend on.        
OpenMessaging's project organization makes room for each of these constituencies.
   
## OpenMessaging Technical Steer Committee(OMTSC)
   The authors of any messaging tools that supports OpenMessaging are always invited to contribute to discussions about the future of OpenMessaging as a standard. 
   OpenMessaging endeavors to maintain a list of such authors and will occasionally solicit feedback from that group.    
   The Technical Steering Committee (the “TSC”) will be responsible for all technical oversight of the open source Project. The current OpenMessaging Technical Steer Committee is as follows:
- Vongosling([@vongosling](https://github.com/vongosling))(Chair) 
- Duheng([@duhengforever](https://github.com/duhengforever))       
- Sijie([@sijie](https://github.com/sijie))    
- Joe([@joe](https://github.com/joefk))     
- Merlimat([@merlimat](https://github.com/merlimat))
- Jiang Haiting([@Jason918](https://github.com/Jason918))     
- Liu Zhendong([@dongeforever](https://github.com/dongeforever))
    
OMTSC members have the following primary responsibilities:
- Define priorities for OpenMessaging as a project and standard  
- Accurately represent the concerns and needs of messaging and streaming tools   
- Strategize around possible third-party package integrations    
- Weigh in and offer tie-breaking votes for issues where consensus among the larger community has proven elusive     

## OpenMessaging Industrial Advisory Board (OMIAB)
OpenMessaging has an Industrial Advisory Board (OMIAB) that comprises engineers with detailed knowledge of tracing technology at companies of different scales and software maturity.
The OMTSC members engage with the OMIAB on a periodic basis to gather feedback about successes, challenges, and open-source packages which would benefit from greater OpenMessaging support.     
The current OpenMessaging Industrial Advisory Board is as follows:

- Jiazhai([@jiazhai](https://github.com/jiazhai))
- Zhouxinyu([@zhouxinyu](https://github.com/zhouxinyu))
- Cccc1999([@cccc1999](https://github.com/cccc1999))
- Qqeasonchen([@qqeasonchen](https://github.com/qqeasonchen))
- ShannonDing([@ShannonDing](https://github.com/ShannonDing))
- Yun1129([@yun1129](https://github.com/yun1129))
- Vintagewang([@vintagewang](https://github.com/vintagewang))
- Lizhanhui([@lizhanhui](https://github.com/lizhanhui)）    
OMIAB members have the following primary responsibilities:      
- Describe and rationalize messaging challenges within their own companies: it is particularly important that they are regularly exposed to instrumentation, integration, and usability issues related to messaging, and further that they are able to effectively distill these concerns and communicate them back to the OMTSC.
- Participate in periodic (but infrequent: monthly or less) calls with the OMTSC
- Provide feedback about possible priorities and/or specific proposals from the OMTSC
- Represent OpenMessaging’s interests within their own organizations


## Mailing List
- Mailing list: openmessaging-tsc@googlegroups.com    
- Join: https://groups.google.com/forum/#!forum/openmessaging-tsc
  
   
## Voting

In various situations the OpenMessaging TSC shall hold a vote. These votes can happen on the phone, email, or via a voting service, when appropriate. TOC members can either respond "agree, yes, +1", "disagree, no, -1", or "abstain". A vote passes with two-thirds vote of votes cast based on the charter (see 6(c)(viii)). An abstain vote equals not voting at all.

## Working Groups
The TSC has created the following working groups to investigate and discuss the following topics:

| Working Group | Chair            | Meeting Time                          | Minutes/Recordings |
|---------------|------------------|---------------------------------------|--------------------|
|Specification|Vongosling|||
|Runtime Interface|Duhengforever|||
|Benchemark Interface|Vongosling|||
|Connector Interface|Duhengforever|||
|Storage Interface|Vongosling|||

## Afterword: what's the point of OpenMessaging Organization?
Sometimes formal governance and acronyms like "OMTSC" or "OMIAB" signify hierarchy and exclusion in an open-source effort. The intention with OpenMessaging's organization is to do exactly the opposite: by guaranteeing participation from multiple constituencies and multiple software projects and organizations, 
these simple governance structures aim to bring more ideas to the table. Inasmuch as it's possible, all OpenMessaging discussions will take place out in the open and/or at clearly-advertised times and (virtual) places.     
If you would like to take on a more formal role on the OMTSC or OMIAB, please reach out to an existing OMTSC member and we can take it from there.






## Meeting Time
The TSC meets on the 1st and 3rd Tuesday of every month at 8AM. (UTC+8 Beijing):

https://zoom.us/j/6059773406

## Projects

**Project**|**Sponsor**|**TSC Deck**|**Accepted**|**Maturity Level**
:-----:|:-----:|:-----:|:-----:|:-----:
[1.0.0-preview](https://github.com/openmessaging/specification)|Vongosling|[05/09/18](https://github.com/openmessaging/specification)|05/10/18|Public Review



## Meeting Minutes 
If you're interested in presenting at a TSC call about your project, please open a github issue with the request. We can schedule a maximum of one community presentation per TSC meeting.     

**September 18st, 2018**, [1.0.0-preview](https://github.com/openmessaging/specification): Du Heng
