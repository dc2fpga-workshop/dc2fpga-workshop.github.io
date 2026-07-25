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
TBD

**BIO.**
TBD

