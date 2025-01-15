# Arm Server

---
## Arm Neoverse
https://www.arm.com/products/silicon-ip-cpu/neoverse

| Neoverse V  | Arch | Neoverse N | Arch | Neoverse E | Arch |
| :- | :- | :- | :- | :- | :- | 
| Neoverse V3 | Arm®v9.2-A | Neoverse N3 | Arm®v9.2-A | | |
| Neoverse V2 | Arm®v9.0-A | Neoverse N2 | Arm®v9.0-A | | |
| Neoverse V1 | Arm®v8.4-A | Neoverse N1 | Arm®v8.2-A | Neoverse E1 |  Arm®v8.2-A |

---

| AWS Gravito | | | Ampere | | | Marvell | | |
|:-             |:-                   |:-  |:-                |:-         |:-  |:-             |:-                       |:-  |
| AWS Graviton4 | Neoverse V2 (Armv9) | N4 | Ampere AmpereOne | Armv8.6+  | N5 | OCTEON 10 DPU | Neoverse N2 (Armv9.0-A) | N5 |
| AWS Graviton3 | Neoverse V1 (Armv9) | N5 | Ampere Altra     | Armv8.2+  | N7 |               |                         |    |
| AWS Graviton2 | Neoverse N1 (Armv8) | N7 |                  |           |    |               |                         |    |
 
 

 
---
<img src="https://github.com/user-attachments/assets/b34ff6a2-5bcf-4ad3-9f9a-249fa0215973" width=750>

---
<img src="https://github.com/user-attachments/assets/b25ba3bb-b8ed-49d8-b708-a2b43328521f" width=950>


---
### Arm® Neoverse™ V3 Core Technical Reference Manual
https://developer.arm.com/documentation/107734/0002/The-Neoverse--V3--core?lang=en

* The Neoverse™ V3 core is a high-performance and low-power product that implements the **Arm®v9.2-A** architecture.
* The Arm®v9.2-A architecture extends the architecture defined in the Arm®v8‑A architectures up to Arm®v8.7‑A.

---
### Arm® Neoverse™ V2 Core Technical Reference Manual
https://developer.arm.com/documentation/102375/0002?lang=en

* The Neoverse™ V2 core implements the **Arm®v9.0-A** architecture and supports all previous Armv8-A architectures up to Arm®v8.5-A .

---
### Arm® Neoverse™ V1 Core Technical Reference Manual
https://developer.arm.com/documentation/101427/0102/Functional-description/Introduction/About-the-core?lang=en

* The Arm®v8.4-A extension.
* The Reliability, Availability, and, Serviceability (RAS) extension
* The Statistical Profiling Extension (SPE).
* The Scalable Vector Extension (SVE) with a 256-bit vector length.
* The Arm®v8.4-A Memory Partitioning And Monitoring (MPAM) extension.
* The traps for EL0 and EL1 cache controls, PSTATE Speculative Store Bypass Safe (SSBS) bit, and the speculation barriers (CSDB, SSBB, PSSBB) instructions introduced in the Arm®v8.5‑A extension.

---
### Arm® Neoverse™ N3 Core Technical Reference Manual
https://developer.arm.com/documentation/107997/0000/The-Neoverse--N3--core?lang=en

* The Neoverse™ N3 core is a balanced-performance, low-power, and constrained area product that implements the **Arm®v9.2-A** architecture.
* The Arm®v9.2-A architecture extends the architecture defined in the Arm®v8‑A architectures up to Arm®v8.7‑A.

---
### Arm® Neoverse™ N2 Core Technical Reference Manual
https://developer.arm.com/documentation/102099/0003/The-Neoverse-N2--core?lang=en

* The Neoverse™ N2 core implements the **Arm®v9.0-A** architecture

---
### Arm® Neoverse™ N1 Core Technical Reference Manual

https://developer.arm.com/documentation/100616/0401/Introduction-to-the-Neoverse-N1-core/About-the-core?lang=en

* The Arm®v8.2-A extension.
* The RAS extension.
* The Statistical Profiling extension.
* The Load acquire (LDAPR) instructions introduced in the Arm®v8.3-A extension
* The Dot Product support instructions introduced in the Arm®v8.4-A extension.
* The traps for EL1 and EL0 cache controls, PSTATE SSBS (Speculative Store Bypass Safe) bit that supports software mitigation for Spectre Variant 4, and the speculation barriers (CSDB, SSBB, PSSBB) instructions introduced in the Arm®v8.5‑A extension.

---
### Arm® Neoverse™ E1 Core Technical Reference Manual

https://developer.arm.com/documentation/101560/0102/Introduction-to-the-Neoverse-E1-core/About-the-core?lang=en

* The Arm®v8.2-A extension.
* The Reliability, Availability, and Serviceability (RAS) extension
* The Load acquire (LDAPR) instructions introduced in the Arm®v8.3-A extension
* The Dot Product support instructions introduced in the Arm®v8.4-A extension.
* The PSTATE Speculative Store Bypass Safe (SSBS) bit that supports software mitigation for Spectre Variant 4 introduced in the Arm®v8.5‑A extensi

---
### Neoverse CMN-700
https://developer.arm.com/Processors/Neoverse%20CMN-700

* The Arm Neoverse CMN-700 Coherent Mesh Network is a high bandwidth, low-latency system interconnect that supports a wide range of applications. The application supported includes networking infrastructure, storage, server, HPC, automotive, and industrial solutions.
* The highly scalable mesh is optimized for Armv8.2 to Armv9.0 CPUs and can be customized across a wide range of performance, power, and area requirements.

#### Resource 
* Arm Neoverse CMN-700 Technical Reference Manual Addendum
  * https://developer.arm.com/documentation/108055/0301/?lang=en

  
---
## Blog
* Neoverse Compute Subsystems, the Fastest Path to Production Silicon
   * https://community.arm.com/arm-community-blogs/b/infrastructure-solutions-blog/posts/neoverse-compute-subsystems-css-the-fastest-path-to-production-silicon

---
## Arm Learning Path

---
### SIMD

* Learn how to write SIMD code on Arm using Rust
    * https://learn.arm.com/learning-paths/cross-platform/simd-on-rust/
* Migrating applications to Arm servers
    * https://learn.arm.com/learning-paths/servers-and-cloud-computing/migration/
* Run memcached on Arm servers and measure its performance
    * https://learn.arm.com/learning-paths/servers-and-cloud-computing/memcached/
* Get started with Geekbench on Arm
    * https://learn.arm.com/learning-paths/servers-and-cloud-computing/geekbench/

---
### LLM

* Run a Large Language Model (LLM) chatbot with PyTorch using KleidiAI on Arm servers
    * https://learn.arm.com/learning-paths/servers-and-cloud-computing/pytorch-llama/
* Deploy a Large Language Model (LLM) chatbot with llama.cpp using KleidiAI on Arm servers
    * https://learn.arm.com/learning-paths/servers-and-cloud-computing/llama-cpu/
* Build and Run a Virtual Large Language Model (vLLM) on Arm Servers
    * https://learn.arm.com/learning-paths/servers-and-cloud-computing/vllm/
* Accelerate Generative AI workloads using KleidiAI
    * https://learn.arm.com/learning-paths/cross-platform/kleidiai-explainer/
* Learn about LLVM Machine Code Analyzer
    * https://learn.arm.com/learning-paths/cross-platform/mca-godbolt/
* Accelerate Natural Language Processing (NLP) models from Hugging Face on Arm servers
    * https://learn.arm.com/learning-paths/servers-and-cloud-computing/benchmark-nlp/
      
---
### Vision AI

* Get started with Arm-based cloud instances
    * https://learn.arm.com/learning-paths/servers-and-cloud-computing/csp/
* Create and train a PyTorch model for digit classification using the MNIST dataset
    * https://learn.arm.com/learning-paths/cross-platform/pytorch-digit-classification-arch-training/
* Run x265 (H.265 codec) on Arm servers
    * https://learn.arm.com/learning-paths/servers-and-cloud-computing/codec/




--- 
## Reference




