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
- Du Heng([@duhenglucky](https://github.com/duhenglucky))       
- Joe([@joe](https://github.com/joefk))     
- Merlimat([@merlimat](https://github.com/merlimat))
- Jiang Haiting([@Jason918](https://github.com/Jason918))     
- Liu Zhendong([@dongeforever](https://github.com/dongeforever))
    
OMTSC members have the following primary responsibilities:
- Coordinating the technical direction of the Project;
- Approving project or system proposals (including, but not limited to, incubation, deprecation, and changes to a sub-project’s scope);
- organizing sub-projects and removing projects;
- Creating sub-committees or working groups to focus on cross-project technical issues and requirements;
- Appointing representatives to work with other open source or open standards communities;
- Establishing community norms, workflows, issuing releases, and security issue reporting policies;
- Approving and implementing policies and processes for contributing (to be published in the CONTRIBUTING file) and coordinating with the Series Manager to resolve matters or concerns that may arise as set forth in Section 7 of this Charter;
- Discussions, seeking consensus, and where necessary, voting on technical matters relating to the code base that affect multiple projects; and
- Coordinating any marketing, events, or communications regarding the Project with the LF Projects Manager or their designee.

## OpenMessaging Industrial Advisory Board (OMIAB)
OpenMessaging has an Industrial Advisory Board (OMIAB) that comprises engineers with detailed knowledge of messaging
technology at companies of different scales and software maturity.
The OMTSC members engage with the OMIAB on a periodic basis to gather feedback about successes, challenges, and open-source packages which would benefit from greater OpenMessaging support.     
The current OpenMessaging Industrial Advisory Board members are as follows:

- Jiazhai([@jiazhai](https://github.com/jiazhai))
- Zhouxinyu([@zhouxinyu](https://github.com/zhouxinyu))
- Cccc1999([@cccc1999](https://github.com/cccc1999))
- Qqeasonchen([@qqeasonchen](https://github.com/qqeasonchen))
- ShannonDing([@ShannonDing](https://github.com/ShannonDing))
- Yun1129([@yun1129](https://github.com/yun1129))
- Vintagewang([@vintagewang](https://github.com/vintagewang))
- Lizhanhui([@lizhanhui](https://github.com/lizhanhui)）  
- Psoft007([@psoft007](https://github.com/psoft007))
- Wlliqipeng([@wlliqipeng](https://github.com/wlliqipeng)))
- YangJodie([@YangJodie](https://github.com/YangJodie))
- Hill007299([@hill007299](https://github.com/hill007299))
- Zhouli11([@zhouli11](https://github.com/zhouli11))
- Ustcchensu([@ustcchensu](https://github.com/ustcchensu))
- Nera0([@nera0](https://github.com/nera0))
- Rayzhou2017([@rayzhou2017](https://github.com/rayzhou2017))
- Ssssssnake([@ssssssnake](https://github.com/ssssssnake))
- Zongtanghu([@zongtanghu](https://github.com/zongtanghu))
- Nkurihar([@nkurihar](https://github.com/nkurihar))
- Emqplus([@emqplus](https://github.com/emqplus))
- Bluefish0007([@bluefish0007](https://github.com/bluefish0007))
- Luomaidi([@luomaidi](https://github.com/aluomaidi))
- Li Wei([@francisoliverlee](https://github.com/francisoliverlee))
- Mao Li([@WildWolfBang](https://github.com/WildWolfBang))
- Maning8([@Maning8](https://github.com/Maning8))
- Liangliang Chen([@bluecll](https://github.com/bluecll))
- xiaoweiwei([@xiaoweiwei](https://github.com/xiaoweiwei))
- Qiang Li([@momofish](https://github.com/momofish))
- Li Aixiong/([@liaixiong](https://github.com/liaixiong))
- Peiyu Lin/([@mathspanda](https://github.com/mathspanda))
- Ji Ma/([@TalkingData](https://github.com/TalkingData))
- Xiaojun Yue/([@junedo](https://github.com/junedo))
- Xu Han/([@superhx]( https://github.com/superhx))
- Lin Xin/([@dbl-x]( https://github.com/dbl-x))

OMIAB members have the following primary responsibilities:  
    
- Describe and rationalize messaging challenges within their own companies: it is particularly important that they are regularly exposed to instrumentation, integration, and usability issues related to messaging, and further that they are able to effectively distill these concerns and communicate them back to the OMTSC.
- Participate in periodic (but infrequent: monthly or less) calls with the OMTSC
- Provide feedback about possible priorities and/or specific proposals from the OMTSC
- Represent OpenMessaging’s interests within their own organizations

**[Election](election.md)**

## Mailing List
- Mailing list: openmessaging@googlegroups.com
  
   
## Voting

In various situations the OpenMessaging TSC shall hold a vote. These votes can happen on the phone, email, or via a voting service, when appropriate. TSC members can either respond "agree, yes, +1", "disagree, no, -1", or "abstain". A vote passes with two-thirds vote of votes cast based on the charter (see 6(c)(viii)). An abstain vote equals not voting at all.

## Working Groups
The TSC has created the following working groups to investigate and discuss the following topics:

| Working Group | Co-chair/Sponsor           | 
|---------------|------------------|
|Specification|Vongosling,Duhengforever|
|Runtime|Duhengforever,Vongosling|
|Benchmark|Vongosling,Duhengforever|
|Storage|Vongosling,Duhengforever|
|OpenConnect|Duhengforever,Vongosling|
|OpenChaos|Vongosling,Duhengforever|
|OpenSchema|Duhengforever,Vongosling|

## Afterword: what's the point of OpenMessaging Organization?
Sometimes formal governance and acronyms like "OMTSC" or "OMIAB" signify hierarchy and exclusion in an open-source effort. The intention with OpenMessaging's organization is to do exactly the opposite: by guaranteeing participation from multiple constituencies and multiple software projects and organizations, 
these simple governance structures aim to bring more ideas to the table. Inasmuch as it's possible, all OpenMessaging discussions will take place out in the open and/or at clearly-advertised times and (virtual) places.     
If you would like to take on a more formal role on the OMTSC or OMIAB, please reach out to an existing OMTSC member and we can take it from there.






## Meeting Time
The TSC meets on the 1st Tuesday of every month at 19:00 PM. (UTC+8 Beijing):    
Join from PC, Mac, Linux, iOS or Android: https://zoom.us/j/134543135        

Or iPhone one-tap :     
    US: +16468769923,,134543135#  or +14086380986,,134543135#       
Or Telephone:      
    Dial(for higher quality, dial a number based on your current location):    
        US: +1 646 876 9923  or +1 408 638 0986       
    Meeting ID: 134 543 135     
    International numbers available: https://zoom.us/u/ajgNRM70p     


## Projects

**Project**|**Sponsor**|**TSC Deck**|**Accepted**|**Maturity Level**
:-----:|:-----:|:-----:|:-----:|:-----:
[1.0.0-preview](https://github.com/openmessaging/specification)|Vongosling|[05/09/18](https://github.com/openmessaging/specification)|05/10/18|Public Review



## [Meeting Minutes](https://docs.google.com/document/d/1w9G1-7d4HqZ9s6VoarjFYg4mYhGK4pEoSYoheynM83o/edit#) 
If you're interested in presenting at a TSC call about your project, please open a github issue with the request. We can schedule a maximum of one community presentation per TSC meeting.     

**September 18st, 2018**, [1.0.0-preview](https://github.com/openmessaging/specification): Du Heng
