# Tentative Syllabus for DAT515 Cloud Computing Technologies

## Topics

### Introduction

| Topic           | Paper                                                                                                                                                                                                                                                                                                                                |
| --------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Cloud Computing | Mache Creeger. [**Cloud Computing: An Overview**][1]. _Queue – Distributed Computing_, 7(5), 2009.                                                                                                                                                                                                                                   |
|                 | Michael Armbrust, Armando Fox, Rean Griffith, Anthony D. Joseph, Randy Katz, Andy Konwinski, Gunho Lee, David Patterson, Ariel Rabkin, Ion Stoica, and Matei Zaharia. [**Above the Clouds: A Berkeley View of Cloud Computing**][2]. Technical Report _UCB/EECS-2009-28_, EECS Department, University of California, Berkeley, 2009. |
|                 | Michael Armbrust, Armando Fox, Rean Griffith, Anthony D. Joseph, Randy Katz, Andy Konwinski, Gunho Lee, David Patterson, Ariel Rabkin, Ion Stoica, and Matei Zaharia. [**A View of Cloud Computing**][3]. _Communications of the ACM_, 53(4):50–58, 2010.                                                                            |

### Web Services

| Topic         | Paper                                                                                                                                                                                                                                                   |
| ------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| REST          | Roy Thomas Fielding. [**Architectural Styles and the Design of Network-based Software Architectures**][4]. PhD thesis, 2000.                                                                                                                            |
| REST vs. SOAP | Cesare Pautasso, Olaf Zimmermann, and Frank Leymann. [**Restful Web Services vs. "Big" Web Services: Making the Right Architectural Decision**][5]. In _Proceedings of the 17th International World Wide Web Conference (WWW’08)_, pages 805–814, 2008. |
| gRPC          | gRPC: A high-performance, open-source universal RPC framework. <https://grpc.io/>                                                                                                                                                                       |

### Virtualization

| Topic         | Paper                                                                                                                                                                                                                                                                                                           |
| ------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Basics        | Gerald J. Popek and Robert P. Goldberg. [**Formal Requirements for Virtualizable Third Generation Architectures**][6]. _Communications of the ACM_, 17(7):412–421, 1974.                                                                                                                                        |
|               | John S. Robin and Cynthia E. Irvine. [**Analysis of the Intel Pentium's Ability to Support a Secure Virtual Machine Monitor**][7]. In _Proceedings of the 9th USENIX Security Symposium (SSYM’00)_, pages 129–144, 2000.                                                                                        |
|               | Keith Adams and Ole Agesen. [**A Comparison of Software and Hardware Techniques for x86 Virtualization**][8]. In _Proceedings of the 12th International Conference on Architectural Support for Programming Languages and Operating Systems (ASPLOS’06)_, pages 2–13, 2006.                                     |
| Xen           | Paul Barham, Boris Dragovic, Keir Fraser, Steven Hand, Tim Harris, Alex Ho, Rolf Neugebauer, Ian Pratt, and Andrew Warfield. [**Xen and the Art of Virtualization**][9]. In _Proceedings of the 19th Symposium on Operating Systems Principles (SOSP’03)_, pages 164–177, 2003.                                 |
| Linux-VServer | Stephen Soltesz, Herbert Pötzl, Marc E. Fiuczynski, Andy Bavier, and Larry Peterson. [**Container-based Operating System Virtualization: A Scalable, High-Performance Alternative to Hypervisors**][10]. In _Proceedings of the 2nd European Conference on Computer Systems (EuroSys’07)_, pages 275–287, 2007. |
|               | Mendel Rosenblum and Tal Garfinkel. [**Virtual Machine Monitors: Current Technology and Future Trends**][42]. IEEE Computer, 38(5):39–47, 2005.                                                                                                                                                                 |

### Cloud Infrastructures

| Topic      | Paper                                                                                                                                                                                                                                                                                                                                                                               |
| ---------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Eucalyptus | Daniel Nurmi, Rich Wolski, Chris Grzegorczyk, Graziano Obertelli, Sunil Soman, Lamia Youseff, and Dmitrii Zagorodnov. [**The Eucalyptus Open-Source Cloud-Computing System**][11]. In _Proceedings of the 9th International Symposium on Cluster Computing and the Grid (CCGrid’09)_, pages 124–131, 2009.                                                                          |
| SDN        | Nick McKeown, Tom Anderson, Hari Balakrishnan, Guru Parulkar, Larry Peterson, Jennifer Rexford, Scott Shenker, and Jonathan Turner. [**OpenFlow: Enabling Innovation in Campus Networks**][12]. _SIGCOMM Computer Communication Review_, 38(2):69–74, 2008.                                                                                                                         |
|            | Teemu Koponen, Martin Casado, Natasha Gude, Jeremy Stribling, Leon Poutievski, Min Zhu, Rajiv Ramanathan, Yuichiro Iwata, Hiroaki Inoue, Takayuki Hama, and Scott Shenker. [**Onix: A Distributed Control Platform for Large-Scale Production Networks**][13]. In _Proceedings of the 9th Symposium on Operating Systems Design and Implementation (OSDI’10)_, pages 351–364, 2010. |
|            | Sushant Jain, Alok Kumar, Subhasree Mandal, Joon Ong, Leon Poutievski, Arjun Singh, Subbaiah Venkata, Jim Wanderer, Junlan Zhou, Min Zhu, Jon Zolla, Urs Hölzle, Stephen Stuart, and Amin Vahdat. [**B4: Experience with a Globally-Deployed Software Defined WAN**][14]. In _Proceedings of the 2013 SIGCOMM Conference (SIGCOMM’13)_, pages 3–14, 2013.                           |

### Data Storage and Processing

| Topic              | Paper                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| ------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Google File System | Sanjay Ghemawat, Howard Gobioff, and Shun-Tak Leung. [**The Google File System**][15]. In _Proceedings of the 19th Symposium on Operating Systems Principles (SOSP’03)_, pages 29–43, 2003.                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
|                    | Marshall K. McKusick and Sean Quinlan. [**GFS: Evolution on Fast-Forward**][16]. _Queue – File Systems_, 7(7):10–20, 2009.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
|                    | Denis Serenyi. [**Cluster-Level Storage @ Google**][17]. _Keynote at the 2nd Joint International Workshop on Parallel Data Storage & Data Intensive Scalable Intensive Computing Systems_, 2017.                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| HDFS               | Konstantin Shvachko, Hairong Kuang, Sanjay Radia, and Robert Chansler. [**The Hadoop Distributed File System**][18]. In _Proceedings of the 26th Symposium on Mass Storage Systems and Technologies (MSST’10)_, pages 1–10, 2010.                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| Bigtable           | Fay Chang, Jeffrey Dean, Sanjay Ghemawat, Wilson Hsieh, Deborah A. Wallach, Mike Burrows, Tushar Chandra, Andrew Fikes, and Robert E. Gruber. [**Bigtable: A Distributed Storage System for Structured Data**][19]. In _Proceedings of the 7th Symposium on Operating Systems Design and Implementation (OSDI’06)_, pages 205–218, 2006.                                                                                                                                                                                                                                                                                                                              |
| Azure Storage      | Brad Calder, Ju Wang, Aaron Ogus, Niranjan Nilakantan, Arild Skjolsvold, Sam McKelvie, Yikang Xu, Shashwat Srivastav, Jiesheng Wu, Huseyin Simitci, Jaidev Haridas, Chakravarthy Uddaraju, Hemal Khatri, Andrew Edwards, Vaman Bedekar, Shane Mainali, Rafay Abbasi, Arpit Agarwal, Mian Fahim ul Haq, Muhammad Ikram ul Haq, Deepali Bhardwaj, Sowmya Dayanand, Anitha Adusumilli, Marvin McNett, Sriram Sankaran, Kavitha Manivannan, and Leonidas Rigas. [**Windows Azure Storage: A Highly Available Cloud Storage Service with Strong Consistency**][20]. In _Proceedings of the 23rd Symposium on Operating Systems Principles (SOSP’11)_, pages 143–157, 2011. |
| Dynamo             | Giuseppe DeCandia, Deniz Hastorun, Madan Jampani, Gunavardhan Kakulapati, Avinash Lakshman, Alex Pilchin, Swaminathan Sivasubramanian, Peter Vosshall, and Werner Vogels. [**Dynamo: Amazon's Highly Available Key-Value Store**][21]. In _Proceedings of the 21st Symposium on Operating Systems Principles (SOSP’07)_, pages 205-220, 2007.                                                                                                                                                                                                                                                                                                                         |
| MapReduce          | Jeffrey Dean and Sanjay Ghemawat. [**MapReduce: Simplified Data Processing on Large Clusters**][22]. In _Proceedings of the 6th Symposium on Operating Systems Design and Implementation (OSDI’04)_, pages 137–150, 2004.                                                                                                                                                                                                                                                                                                                                                                                                                                             |
|                    | Michael Stonebraker, Daniel J. Abadi, David J. DeWitt, Samuel Madden, Erik Paulson, Andrew Pavlo, and Alexander Rasin. [**MapReduce and Parallel DBMSs: Friends or Foes?**][23]. _Communications of the ACM_, 53(1):64–71, 2010.                                                                                                                                                                                                                                                                                                                                                                                                                                      |

### Energy-Efficient Data Centers

| Topic                                   | Paper                                                                                                                                                                                                                                                                                                                         |
| --------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Overview                                | Gregory Mone. [**Redesigning the Data Center**][24]. _Communications of the ACM_, 55(10):14–16, 2012.                                                                                                                                                                                                                         |
| Yahoo Compute Coop                      | A. D. Robison, Christina Page, and Bob Lytle. [**Yahoo! Compute Coop (YCC): A Next-Generation Passive Cooling Design for Data Centers**][25]. Technical Report _DE-EE0002899_, Yahoo Inc., 2011.                                                                                                                              |
| Temperature-Dependent Load Distribution | Ratnesh K. Sharma, Cullen E. Bash, Chandrakant D. Patel, Richard J. Friedrich, and Jeffrey S. Chase. [**Balance of Power: Dynamic Thermal Management for Internet Data Centers**][26]. _IEEE Internet Computing_, 9(1):42–49, 2005.                                                                                           |
| GreenHDFS                               | Rini T. Kaushik, Milind Bhandarkar, and Klara Nahrstedt. [**Evaluation and Analysis of GreenHDFS: A Self-Adaptive, Energy-Conserving Variant of the Hadoop Distributed File System**][27]. In _Proceedings of the 2nd International Conference on Cloud Computing Technology and Science (CLOUDCOM’10)_, pages 274–287, 2010. |
| Energy-Efficient MapReduce              | Jacob Leverich and Christos Kozyrakis. [**On the Energy (In)Efficiency of Hadoop Clusters**][28]. _Operating Systems Review_, 44(1):61–65, 2010.                                                                                                                                                                              |
|                                         | Willis Lang and Jignesh M. Patel. [**Energy Management for MapReduce Clusters**][29]. _Proceedings of the VLDB Endowment_, 3(1-2):129–139, 2010.                                                                                                                                                                              |
|                                         | Yanpei Chen, Sara Alspaugh, Dhruba Borthakur, and Randy Katz. [**Energy Efficiency for Large-Scale MapReduce Workloads with Significant Interactive Analysis**][30]. In _Proceedings of the 7th European Conference on Computer Systems (EuroSys’12)_, pages 43–56, 2012.                                                     |

### Multi-Cloud Computing

| Topic | Paper                                                                                                                                                                                                       |
| ----- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| RACS  | Hussam Abu-Libdeh, Lonnie Princehouse, and Hakim Weatherspoon. [**RACS: A Case for Cloud Storage Diversity**][31]. In _Proceedings of the 1st Symposium on Cloud Computing (SoCC’10)_, pages 229–240, 2010. |

### Coordination Services

| Topic     | Paper                                                                                                                                                                                                                                       |
| --------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Chubby    | Mike Burrows. [**The Chubby Lock Service for Loosely-Coupled Distributed Systems**][32]. In _Proceedings of the 7th Symposium on Operating Systems Design and Implementation (OSDI’06)_, pages 335–350, 2006.                               |
| ZooKeeper | Patrick Hunt, Mahadev Konar, Flavio P. Junqueira, and Benjamin Reed. [**ZooKeeper: Wait-free Coordination for Internet-Scale Systems**][33]. In _Proceedings of the 2010 USENIX Annual Technical Conference (ATC’10)_, pages 145–158, 2010. |
|           | Benjamin Reed and Flavio P. Junqueira. [**A Simple Totally Ordered Broadcast Protocol**][34]. In _Proceedings of the 2nd Workshop on Large-Scale Distributed Systems and Middleware (LADIS’08)_, pages 1–6, 2008.                           |

### Latency Minimization in Data Centers

| Topic    | Paper                                                                                                          |
| -------- | -------------------------------------------------------------------------------------------------------------- |
| Overview | Jeffrey Dean and Luiz A. Barroso. [**The Tail at Scale**][35]. _Communications of the ACM_, 56(2):74–80, 2013. |

### Paper Discussion

| Topic                        | Paper                                                                                                                                                                                                                                                                                                                                                               |
| ---------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Conveyor                     | Boris Grubic, Yang Wang, Tyler Petrochko, Ran Yaniv, Brad Jones, David Callies, Matt Clarke-Lauer, Dan Kelley, Soteris Demetriou, Kenny Yu, and Chunqiang Tang. [**Conveyor: One-Tool-Fits-All Continuous Software Deployment at Meta**][36]. In _Proceedings of the 17th Symposium on Operating Systems Design and Implementation (OSDI’23)_, pages 325–342, 2023. |
| Reading and Reviewing Papers | Srinivasan Keshav. [**How to Read a Paper**][37]. _SIGCOMM Computer Communication Review_, 37(3):83–84, 2007.                                                                                                                                                                                                                                                       |
|                              | Timothy Roscoe. [**Writing Reviews for Systems Conferences**][38]. 2007.                                                                                                                                                                                                                                                                                            |
|                              | Graham Cormode. [**How NOT to Review a Paper: The Tools and Techniques of the Adversarial Reviewer**][39]. _SIGMOD Record_, 37(4):100–104 2009.                                                                                                                                                                                                                     |

### Virtualization-Based Fault Tolerance

| Topic        | Paper                                                                                                                                                                                                                                                                                                   |
| ------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Remus        | Brendan Cully, Geoffrey Lefebvre, Dutch Meyer, Mike Feeley, Norm Hutchinson, and Andrew Warfield. [**Remus: High Availability via Asynchronous Virtual Machine Replication**][40]. In _Proceedings of the 5th Symposium on Networked Systems Design and Implementation (NSDI’08)_, pages 161–174, 2008. |
| VM Migration | Christopher Clark, Keir Fraser, Steven Hand, Jacob G. Hansen, Eric Jul, Christian Limpach, Ian Pratt, and Andrew Warfield. [**Live Migration of Virtual Machines**][41]. In _Proceedings of the 2nd Symposium on Networked Systems Design and Implementation (NSDI’05)_, pages 273–286, 2005.           |

[1]: http://queue.acm.org/detail.cfm?id=1554608
[2]: http://www.eecs.berkeley.edu/Pubs/TechRpts/2009/EECS-2009-28.pdf
[3]: http://dl.acm.org/ft_gateway.cfm?id=1721672
[4]: http://www.ics.uci.edu/~fielding/pubs/dissertation/fielding_dissertation.pdf
[5]: http://www.jopera.org/files/www2008-restws-pautasso-zimmermann-leymann.pdf
[6]: http://dl.acm.org/ft_gateway.cfm?id=361073
[7]: http://static.usenix.org/events/sec00/full_papers/robin/robin.pdf
[8]: http://www.vmware.com/pdf/asplos235_adams.pdf
[9]: http://www.cl.cam.ac.uk/research/srg/netos/papers/2003-xensosp.pdf
[10]: http://dl.acm.org/ft_gateway.cfm?id=1273025
[11]: http://www.cs.ucsb.edu/~rich/publications/ccgrid09.pdf
[12]: http://ccr.sigcomm.org/online/files/p69-v38n2n-mckeown.pdf
[13]: https://www.usenix.org/legacy/event/osdi10/tech/full_papers/Koponen.pdf
[14]: http://conferences.sigcomm.org/sigcomm/2013/papers/sigcomm/p3.pdf
[15]: http://research.google.com/archive/gfs-sosp2003.pdf
[16]: http://queue.acm.org/detail.cfm?id=1594206
[17]: http://www.pdsw.org/pdsw-discs17/slides/PDSW-DISCS-Google-Keynote.pdf
[18]: https://storageconference.us/2010/Papers/MSST/Shvachko.pdf
[19]: http://usenix.org/event/osdi06/tech/chang/chang.pdf
[20]: http://sigops.org/sosp/sosp11/current/2011-Cascais/printable/11-calder.pdf
[21]: http://www.read.seas.harvard.edu/~kohler/class/cs239-w08/decandia07dynamo.pdf
[22]: http://static.usenix.org/event/osdi04/tech/full_papers/dean/dean.pdf
[23]: https://cacm.acm.org/magazines/2010/1/55743-mapreduce-and-parallel-dbmss-friends-or-foes/
[24]: http://dl.acm.org/ft_gateway.cfm?id=2347742
[25]: http://www.osti.gov/bridge/servlets/purl/1024347/1024347.pdf
[26]: https://ieeexplore.ieee.org/document/1407777
[27]: http://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=5708461
[28]: http://www.sigops.org/sosp/sosp09/papers/hotpower_2_leverich.pdf
[29]: http://pages.cs.wisc.edu/~jignesh/publ/MR-energy.pdf
[30]: http://dl.acm.org/ft_gateway.cfm?id=2168842
[31]: http://pubs.0xff.co/papers/racs-socc.pdf
[32]: http://research.google.com/archive/chubby-osdi06.pdf
[33]: http://www.usenix.org/events/usenix10/tech/full_papers/Hunt.pdf
[34]: http://dl.acm.org/ft_gateway.cfm?id=1529978
[35]: http://cacm.acm.org/magazines/2013/2/160173-the-tail-at-scale/pdf
[36]: https://www.usenix.org/system/files/osdi23-grubic.pdf
[37]: https://svr-sk818-web.cl.cam.ac.uk/keshav/papers/07/paper-reading.pdf
[38]: http://people.inf.ethz.ch/troscoe/pubs/review-writing.pdf
[39]: https://sigmodrecord.org/publications/sigmodRecord/0812/p100.open.cormode.pdf
[40]: http://www.cs.ubc.ca/~andy/papers/remus-nsdi-final.pdf
[41]: http://www.cl.cam.ac.uk/research/srg/netos/papers/2005-migration-nsdi-pre.pdf
[42]: https://course.ece.cmu.edu/~ece845/docs/virtual-future-computer05.pdf
