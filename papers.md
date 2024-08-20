# Selected Research Papers on Cloud Computing

- [**How to Read a Paper**][37]. _SIGCOMM Computer Communication Review_, 37(3):83–84, 2007.

## Cloud Computing Overview

- [**A View of Cloud Computing**][3]. _Communications of the ACM_, 53(4):50–58, 2010.

## Deployment

- ServiceWeaver: [**Towards Modern Development of Cloud Applications**][1]. In _Proceedings of the 2023 Workshop on Hot Topics in Operating Systems (HotOS’23)_, 2023.
- [**Conveyor: One-Tool-Fits-All Continuous Software Deployment at Meta**][36]. In _Proceedings of the 17th Symposium on Operating Systems Design and Implementation (OSDI’23)_, pages 325–342, 2023.
- [**Borg, Omega, and Kubernetes: Lessons learned from three container-management systems over a decade**][2]. In _ACM Queue_, 2016.

## Web Services

- **REST**: [**Architectural Styles and the Design of Network-based Software Architectures**][4]. PhD thesis, 2000.
- **gRPC**: gRPC: A high-performance, open-source universal RPC framework. <https://grpc.io/>

## Virtualization

- [**The Ideal Versus the Real: Revisiting the History of Virtual Machines and Containers**][45]. In _ACM Computing Surveys 53, 1, Article 5 (January 2021)_.
- [**Xen and the Art of Virtualization**][9]. In _Proceedings of the 19th Symposium on Operating Systems Principles (SOSP’03)_, 2003.
- [**My VM is Lighter (and Safer) than your Container**][43]. ([video][44]) In _Proceedings of the 26th Symposium on Operating Systems Principles (SOSP’17)_, 2017.
- [**Remus: High Availability via Asynchronous Virtual Machine Replication**][40]. In _Proceedings of the 5th Symposium on Networked Systems Design and Implementation (NSDI’08)_, pages 161–174, 2008.
- [**Live Migration of Virtual Machines**][41]. In _Proceedings of the 2nd Symposium on Networked Systems Design and Implementation (NSDI’05)_, pages 273–286, 2005.

## Scalable Processing

- [**Autopilot: workload autoscaling at Google**][38]. In _Proceedings of the 15th European Conference on Computer Systems (EuroSys’20)_, 2020.
- [**The Tail at Scale**][35]. _Communications of the ACM_, 56(2):74–80, 2013.
- [**MapReduce: Simplified Data Processing on Large Clusters**][17]. In _OSDI_ 2004.

## Data Storage

- [**Colossus under the hood: a peek into Google's scalable storage system (blog)**][46] ([video][47])
- [**Spanner: Google’s Globally-Distributed Database**][20]. In _OSDI_ 2012.
- [**The Google File System**][15]. In _Proceedings of the 19th Symposium on Operating Systems Principles (SOSP’03)_, pages 29–43, 2003.
- [**GFS: Evolution on Fast-Forward**][16]. _Queue – File Systems_, 7(7):10–20, 2009.
- [**The Hadoop Distributed File System**][18]. In _Proceedings of the 26th Symposium on Mass Storage Systems and Technologies (MSST’10)_, pages 1–10, 2010.
- [**Bigtable: A Distributed Storage System for Structured Data**][19]. In _Proceedings of the 7th Symposium on Operating Systems Design and Implementation (OSDI’06)_, 2006.
- [**Dynamo: Amazon's Highly Available Key-value Store**][24]. In _Proceedings of the 21st Symposium on Operating Systems Principles (SOSP’07)_, 2007.
- [**Azure Data Lake Store: A Hyperscale Distributed File Service for Big Data Analytics**][5]. In _SIGMOD_ 2017.
- [**The Cosmos Big Data Platform at Microsoft: Over a Decade of Progress and a Decade to Look Forward**][6]. In _VLDB_ 2020.

## Multi-Cloud Computing

- [**RACS: A Case for Cloud Storage Diversity**][31]. In _Proceedings of the 1st Symposium on Cloud Computing (SoCC’10)_, pages 229–240, 2010.

## Cloud Networking

- [**B4: Experience with a Globally-Deployed Software Defined WAN**][14]. In _Proceedings of the 2013 SIGCOMM Conference (SIGCOMM’13)_, pages 3–14, 2013.

## Coordination Services

- Raft: [**In Search of an Understandable Consensus Algorithm**][30]. In _Proceedings of the 2014 USENIX Annual Technical Conference (ATC’14)_, pages 305–319, 2014.
- [**ZooKeeper: Wait-free Coordination for Internet-Scale Systems**][33]. In _Proceedings of the 2010 USENIX Annual Technical Conference (ATC’10)_, pages 145–158, 2010.
- [**The Chubby Lock Service for Loosely-Coupled Distributed Systems**][32]. In _Proceedings of the 7th Symposium on Operating Systems Design and Implementation (OSDI’06)_, pages 335–350, 2006.

[1]: https://sigops.org/s/conferences/hotos/2023/papers/ghemawat.pdf
[2]: https://dl.acm.org/doi/10.1145/2898442.2898444
[3]: http://dl.acm.org/ft_gateway.cfm?id=1721672
[4]: http://www.ics.uci.edu/~fielding/pubs/dissertation/fielding_dissertation.pdf
[5]: https://dl.acm.org/doi/pdf/10.1145/3035918.3056100
[6]: https://vldb.org/pvldb/vol14/p3148-jindal.pdf
[9]: http://www.cl.cam.ac.uk/research/srg/netos/papers/2003-xensosp.pdf
[14]: http://conferences.sigcomm.org/sigcomm/2013/papers/sigcomm/p3.pdf
[15]: http://research.google.com/archive/gfs-sosp2003.pdf
[16]: http://queue.acm.org/detail.cfm?id=1594206
[17]: http://research.google.com/archive/mapreduce-osdi04.pdf
[18]: https://storageconference.us/2010/Papers/MSST/Shvachko.pdf
[19]: http://usenix.org/event/osdi06/tech/chang/chang.pdf
[20]: http://research.google.com/archive/spanner-osdi2012.pdf
[24]: https://www.amazon.science/publications/dynamo-amazons-highly-available-key-value-store
[30]: https://www.usenix.org/conference/atc14/technical-sessions/presentation/ongaro
[31]: http://pubs.0xff.co/papers/racs-socc.pdf
[32]: http://research.google.com/archive/chubby-osdi06.pdf
[33]: http://www.usenix.org/events/usenix10/tech/full_papers/Hunt.pdf
[35]: http://cacm.acm.org/magazines/2013/2/160173-the-tail-at-scale/pdf
[36]: https://www.usenix.org/system/files/osdi23-grubic.pdf
[37]: https://svr-sk818-web.cl.cam.ac.uk/keshav/papers/07/paper-reading.pdf
[38]: https://research.google/pubs/autopilot-workload-autoscaling-at-google-scale/
[40]: http://www.cs.ubc.ca/~andy/papers/remus-nsdi-final.pdf
[41]: http://www.cl.cam.ac.uk/research/srg/netos/papers/2005-migration-nsdi-pre.pdf
[43]: https://dl.acm.org/doi/10.1145/3132747.3132763
[44]: https://dl.acm.org/ft_gateway.cfm?id=3132763&ftid=1938413&dwn=1
[45]: https://doi.org/10.1145/3365199
[46]: https://cloud.google.com/blog/products/storage-data-transfer/a-peek-behind-colossus-googles-file-system
[47]: https://youtu.be/q4WC_6SzBz4?si=Hf_PLwlLX4eIu4J1
