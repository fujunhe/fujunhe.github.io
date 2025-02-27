---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---
## Publicaitons
Please check my [CV](http://fujunhe.github.io/files/Curriculum_Vitae.pdf) (full list), [Google Scholar](https://scholar.google.co.jp/citations?user=1x7F0AMAAAAJ&hl=en), [DBLP](https://dblp.org/pid/34/7779.html), and [Researchmap](https://researchmap.jp/fujunhe) for publications.

Selected ones are listed below.

## Grants
* Robust Optimization for Resource Allocation in Cloud Providers
  * Funding agency: JSPS Grant-in-Aid for Early-Career Scientists
  * Grant number: [21K17733](https://kaken.nii.ac.jp/en/grant/KAKENHI-PROJECT-21K17733/)
  * Duration: Apr. 2021 – Mar. 2024
  * Role: Principal Investigator
  * Amount: 4,290,000 JPY

## Recent research projects

### Network virtualization/softwarization
Network virtualization/softwarization has been introduced as a key role in the next-generation networking paradigm to fend off the ossification of traditional networks. While network virtualization/softwarization leads to a more flexible network by adopting the technologies of **computer virtualization**, **network function virtualization (NFV)**, and **software-defined networking (SDN)**, it brings challenges for network management, one of which is how to efficiently allocate network resources considering different requirements such as reliability and latency. We study resource allocation for different problems with typical application scenarios in network virtualization/softwarization.
  * **F. He** and E. Oki, “[Preventive priority setting against multiple controller failures in software defined networks](https://ieeexplore.ieee.org/document/10149508),” *IEEE Transactions on Parallel and Distributed Systems*, vol. 34, no. 8, pp. 547–562, Aug. 2023.
  * **F. He** and E. Oki, “[Service deployment with priority queueing for traffic processing and transmission in network function virtualization](https://ieeexplore.ieee.org/abstract/document/10129126),” *IEEE Transactions on Network and Service Management*, vol. 20, no. 4, pp. 4861–4874, Dec. 2023.
  * **F. He** and E. Oki, “[Robust virtual network function deployment against uncertain traffic arrival rates](https://ieeexplore.ieee.org/document/9492607),” in *Proc. IEEE NetSoft 2021*, Online, June 2021, pp. 339-347.
  * **F. He** and E. Oki, “[Backup allocation model with probabilistic protection for virtual networks against multiple facility node failures](https://ieeexplore.ieee.org/document/9415681),” *IEEE Transactions on Network and Service Management*, vol. 18, no. 3, pp. 2943-2959, Sept. 2021.
  * **F. He** and E. Oki, “[Main and secondary controller assignment with optimal priority policy against multiple failures](https://ieeexplore.ieee.org/document/9372933),” *IEEE Transactions on Network and Service Management*, vol. 18, no. 4, pp. 4391-4405, Dec. 2021.
  * **F. He**, T. Sato, B. C. Chatterjee, T. Kurimoto, S. Urushidani, and E. Oki, “[Robust optimization model for primary and backup resource allocation in cloud providers](https://ieeexplore.ieee.org/document/9320544),” *IEEE Transactions on Cloud Computing*, vol. 10, no. 4, pp. 2920-2935, Oct.-Dec. 2022.
  * **F. He** and E. Oki, “[Unavailability-aware shared virtual backup allocation for middleboxes: a queueing approach](https://ieeexplore.ieee.org/document/9204642),” *IEEE Transactions on Network and Service Management*, vol. 18, no. 2, pp. 2388-2404, June 2021.
  * **F. He**, T. Sato, and E. Oki, “[Optimization model for backup resource allocation in middleboxes with importance](https://ieeexplore.ieee.org/document/8786912),” *IEEE/ACM Transactions on Networking*, vol. 27, no. 4, pp. 1742-1755, Aug. 2019.
 
### Optical networks
Data traffic has tremendously increased with the grouth of network applications. Different optical networking technologies has been introduced to make the transmission capacity closely follow this exponential growth. We study various aspects of these emergeing technologies, especially elastic optical networks (EON) and space division multiplexing (SDM) networks, to relileze extremely high capacity networks.
  * **F. He** and E. Oki, “[Shared protection-based virtual network embedding over elastic optical networks](https://ieeexplore.ieee.org/abstract/document/9782680),” *IEEE Transactions on Network and Service Management*, vol. 19, no. 3, pp. 2869-2884, Sept. 2022.
  * B. C. Chatterjee, **F. He**, E. Oki, A. Fumagalli, and N. Yamanaka, “[A span power management scheme for rapid lightpath provisioning and releasing in multi-core fiber networks](https://ieeexplore.ieee.org/abstract/document/8637057),” *IEEE/ACM Transactions on Networking*, vol. 27, no. 2, pp. 734-747, Apr. 2019.

<!--- 
### Reliable resource allocation in network virtualization
Network virtualization has been introduced as a key role in the next-generation networking paradigm to fend off the ossification of traditional networks. While network virtualization leads to a more flexible network by adopting the technologies of **computer virtualization**, **network function virtualization (NFV)**, and **software-defined networking (SDN)**, it brings challenges for network management, one of which is how to efficiently allocate resources with concerning the reliability issue. Resource allocation with **protection** strategies is an essential requirement for network virtualization. We study reliable resource allocation for different problems with typical application scenarios in network virtualization.
* **F. He** and E. Oki, “[Backup allocation model with probabilistic protection for virtual networks against multiple facility node failures](https://ieeexplore.ieee.org/document/9415681),” *IEEE Transactions on Network and Service Management*, vol. 18, no. 3, pp. 2943--2959, Sept. 2021.
* **F. He**, and E. Oki, “[Main and secondary controller assignment with optimal priority policy against multiple failures](https://ieeexplore.ieee.org/document/9372933),” *IEEE Transactions on Network and Service Management*, vol. 18, no. 4, pp. 4391--4405, Dec. 2021. 
* **F. He**, T. Sato, B. C. Chatterjee, T. Kurimoto, S. Urushidani, and E. Oki, “[Robust optimization model for primary and backup resource allocation in cloud providers](https://ieeexplore.ieee.org/document/9320544),” *IEEE Transactions on Cloud Computing*, early access, Jan. 2021, doi: 10.1109/TCC.2021.3051018.
* **F. He** and E. Oki, “[Unavailability-aware shared virtual backup allocation for middleboxes: a queueing approach](https://ieeexplore.ieee.org/document/9204642),” *IEEE Transactions on Network and Service Management*, early access, Sept. 2020, doi: 10.1109/TNSM.2020.3026218.
* **F. He**, T. Sato, and E. Oki, “[Optimization model for backup resource allocation in middleboxes with importance](https://ieeexplore.ieee.org/document/8786912),” *IEEE/ACM Transactions on Networking*, vol. 27, no. 4, pp. 1742-1755, Aug. 2019.

### Latency-aware service deployment
NFV provides a flexible and efficient way to implement network functions traditionally deployed on dedicated devices as virtual network functions (VNFs) running on commodity servers. Network resources with NFV can be provisioned elastically to support heterogeneous services, each of which is represented by a forwarding graph constructed by a set of VNFs. A critical problem for service providers is hwo to deploy the requested services, including **placing VNFs**, **allocating resources**, and **scheduling traffic**.
* **F. He** and E. Oki, “Robust virtual network function deployment against uncertain traffic arrival rates,” *Proc. IEEE NetSoft 2021*, Online, Jun. 2021, pp. 1-9.
--->
