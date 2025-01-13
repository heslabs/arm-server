# Amazon Graviton

---
## AWS Graviton Processor - Amazon EC2
https://aws.amazon.com/ec2/graviton/

| AWS Graviton | Arm Neoverse | Architecture | Memory | Process |
| :- | :- | :- | :- | :- |
| AWS Graviton4 | Arm Neoverse V2 cores (96-core) | Armv9 | DDR5-5600 | TSMC N4 |
| AWS Graviton3 | Arm Neoverse V1 cores (64-core) | Armv9 | DDR5 |TSMC N5 |
| AWS Graviton2 | Arm Neoverse N1 cores  (64-core) | Armv8 | DDR4 |TSMC N7 |


---
### AWS Graviton4

Performance gains with AWS Graviton4 – a DevitoPRO case study (2024.10) \
https://aws.amazon.com/blogs/hpc/performance-gains-with-aws-graviton4-a-devitopro-case-study/

* The AWS Graviton4 processor represents a significant leap forward, with **96 Neoverse V2 cores** and an enhanced memory subsystem.
* The **12 DDR5-5600 channels** provide up to 75% more memory bandwidth than Graviton3 which is beneficial for memory-bound HPC workloads like seismic imaging.

---
### Amazon Unveils Graviton4: A 96-Core ARM CPU with 536.7 GBps Memory Bandwidth (2023.11)
https://www.anandtech.com/show/21172/amazon-unveils-graviton4-a-96core-cpu-with-5367-gbs-memory-bandwidth

* The AWS Graviton4 processor packs 96 cores that offer on average 30% higher compute performance compared to Graviton3 and is 40% faster in database applications as well as 45% faster in Java applications, according to Amazon.
* Given that Amazon did not reveal many details about its Graviton4, it is hard to attribute performance increases to any particular characteristics of the CPU.
* NextPlatform believes that the processor uses **Arm Neoverse V2 cores**, which are more capable than V1 cores used in previous-generation AWS processors when it comes to instruction per clock (IPC).
* Furthermore, the new CPU is expected to be fabricated using one of **TSMC's N4 process** technologies (4nm-class), which offers a higher clock-speed potential than TSMC's N5 nodes.

---
#### Amazon Unveils Graviton4: A 96-Core ARM CPU with 536.7 GBps Memory Bandwidth (anandtech.com) 
https://news.ycombinator.com/item?id=38465736


---
## AWS Graviton3

https://www.arm.com/partners/aws

* AWS Graviton and Arm Neoverse Enable the Best Price-performance in Amazon EC2
* Based on **Arm Neoverse V1**, the AWS Graviton3 processor provides up 25% better compute performance, 2x faster cryptographic performance, and up to 3x better performance for ML workloads compared to AWS Graviton2.
* Arm and AWS have partnered to enable the best price performance and CPU silicon innovation in the Amazon cloud.
* The AWS Graviton3 and AWS Graviton3E processors use the Arm Neoverse V1 core.
* And the AWS Graviton2 processor uses **Arm Neoverse N1 cores** to deliver its computational horsepower.

--## AWS Graviton3 CPU with 64 Cores and DDR5 Memory Available with Three Sockets Per Motherboard
https://www.techpowerup.com/295203/aws-graviton3-cpu-with-64-cores-and-ddr5-memory-available-with-three-sockets-per-motherboard

* Graviton3's 64 cores run at 2.6 GHz clock speed, 300 GB/sec maximum memory bandwidth, DDR5 memory controller

---
### Best-in-class LLM performance on Arm Neoverse V1 based AWS Graviton3 CPUs
https://community.arm.com/arm-community-blogs/b/infrastructure-solutions-blog/posts/best-in-class-llm-performance

#### Performance comparisons
We also compared the performance of the LLaMa-3 8B int4 quantized model on AWS Graviton3 vs. other latest-generation server CPUs on AWS.

* AWS Graviton3: c7g.16xlarge, 64 VCPUs, 512 GB memory, $2.31/hr
* 4th Gen Intel Xeon: c7i.16xlarge, 64 VCPUs, 512 GB memory, $2.86/hr
* 4th Gen AMD EPYC: c7a.16xlarge, 64 VCPUs (SMT-off), 512 GB memory, $3.28/hr


---
## Amazon EC2 M8g Instances

https://aws.amazon.com/ec2/instance-types/m8g/

* Amazon Elastic Compute Cloud (Amazon EC2) M8g instances, powered by the latest-generation **AWS Graviton4 processors**, provide the best price performance in Amazon EC2 for general purpose workloads.
* Amazon EC2 M8g instances are ideal for workloads such as application servers, microservices, gaming servers, midsize data stores, and caching fleets.
* M8g instances offer up to 30% better performance and larger instance sizes with up to 3x more vCPUs and memory than the seventh-generation AWS Graviton3-based M7g instances.
* These instances include **DDR5-5600 memory** and are ideal for workloads such as application servers, microservices, gaming servers, midsize data stores, and caching fleets.
 

---
## Amazon EC2 M7g Instances

https://aws.amazon.com/ec2/instance-types/m7g/

* Amazon Elastic Compute Cloud (EC2) M7g instances, powered by the latest generation AWS Graviton3 processors, designed for general purpose workloads.
* M7g instances are ideal for workloads such as application servers, microservices, gaming servers, mid-size data stores, and caching fleets. They offer up to 25% better performance over the sixth-generation AWS Graviton2-based M6g instances.
* M7g instances feature Double Data Rate 5 (DDR5) memory, which provides 50% higher memory bandwidth compared to DDR4 memory to enable high-speed access to data in memory.
* M7g instances deliver up to 25% better performance over Graviton2-based M6g. They are ideal for general purpose applications, such as application servers, microservices, gaming servers, mid-size data stores, and caching fleets.

  
