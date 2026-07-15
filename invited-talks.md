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

Other talks are coming soon!

