## Invited Talks

<!--
Example format for each talk:

### Talk Title Here
**Speaker Name** (Affiliation)

Abstract or short description of the talk goes here.
-->

### SLASH: Open-Source Infrastructure for Domain-Specific Shells on the AMD Alveo V80

**Lucian Petrica**, AMD Research

**Abstract.**
AMD Versal datacenter FPGAs such as the AMD Alveo V80 are complex SoCs combining programmable fabric, ARM cores, PCIe, Networks-on-Chip, and HBM/DDR, offering domain experts, from physicists to data scientists, a wealth of capability they lack the expertise to exploit. What such users need is a shell: a set of interfaces, in hardware and software, that exposes the platform in familiar terms. But building a bespoke shell for every domain fragments effort and squanders IP reuse. SLASH is open-source infrastructure that instead provides a domain-agnostic core shell. Building on AMD's official AVED design, it partitions the fabric into two dynamically reconfigurable regions (one for user logic, one for privileged services such as networking) bound by a stable set of NoC interface contracts, and adds a host stack of kernel driver, daemon, and runtime that sit under a user-facing API. This core is specialized into a domain-specific shell by implementing the required services against its hardware contracts and a domain-specific API against its runtime, turning per-domain reinvention into reuse of a shared foundation. We demonstrate two user-facing APIs: VRT, familiar to XRT users migrating from UltraScale+ Alveo, and a compute-graph API for multi-device heterogeneous GPU+FPGA execution.
 
**BIO.**
Lucian Petrica is a principal engineer in AMD Research. He has 20 years of FPGA experience spanning industry and academia. He is a proud user and abuser of AMD FPGAs and EDA tools, has contributed to the FINN inference engine compiler, the ACCL collectives engine, and currently is building SLASH, an open-source, community-driven shell for Alveo V80. 

---

### Distributing a Quantum Error Correction Decoder Across an FPGA Cluster

**Jan Wichmann**, RIKEN Center for Computational Science

**Abstract.**
Quantum computing is an emerging technology, promising to solve problems that are classically intractable. Quantum error correction (QEC) is an approach to overcome qubit instabilities and quantum gate errors, allowing large-scale quantum computers to become a reality. An important part of the QEC process is decoding. It requires processing error correction data on classical hardware at microsecond timescales.

In this talk we present a novel decoding algorithm that distributes the workload across our FPGA cluster ESSPER 2 without excessive inter-FPGA communication. Previous works have demonstrated that FPGAs can meet most requirements for fast and accurate QEC decoding, though scaling has been limited by the size of an individual chip. Our syndrome subgraph algorithm overcomes this limitation through hybrid vertex-level and pipeline parallelism, opening a path to QEC decoders that scale a single decoding instance across many FPGAs, complementing established ensemble techniques.

**BIO.**
Jan Wichmann is a research scientist at the RIKEN Center for Computational Science in Kobe, Japan. A physicist by training, he specializes in quantum error correction, working closely with computer scientists to develop fast QEC decoding algorithms and implement them on FPGAs. He also works on system integration of the various components needed to build fault-tolerant quantum computers. He holds a PhD in condensed matter theory from Tohoku University.

---

### Invited Talk #3 (Title: TBD)

**Aaron Landy**, Microsoft

**Abstract.** 
A fast hardware pipeline is just the first step in building an accelerated cloud service. Building, deploying, and maintaining a cloud acceleration system is an end-to-end system design problem with numerous unique challenges. Where should accelerators be deployed, and how many are needed? Where is the data, how quickly can it reach the accelerator, and how must it be handled? How will developers efficiently design, validate, iterate, and monitor a complex hardware and software system? How will a new accelerator integrate into the existing cloud software and hardware landscape? Do hardware-level speedups yield end-to-end performance gains in a distributed system? Can those performance gains deliver real business value?

At Microsoft, we have used FPGAs to deploy accelerators for applications in search, software-defined networking, storage virtualization, machine learning, and data analytics, among others. In this talk, we discuss the challenges of building hardware accelerators in a hyperscale cloud, solutions we have employed, and lessons learned from more than a decade of FPGAs running production workloads at Microsoft.

**BIO.**
Aaron Landy is a hardware engineering manager at Microsoft Azure. He has spent the last 10 years working across the hardware and software stack to architect, build, optimize, deploy, and maintain FPGA-based accelerators in Azure. He currently leads a multi-disciplinary team focused on pathfinding new applications, pushing the limits of FPGA performance, and accelerating the hardware and software co-design process.

