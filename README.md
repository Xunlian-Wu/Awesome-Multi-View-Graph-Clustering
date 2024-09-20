# Awesome-Multi-View-Graph-Clustering
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com) ![GitHub stars](https://img.shields.io/github/stars/Xunlian-Wu/Awesome-Multi-View-Graph-Clustering?color=yellow&label=Stars) ![GitHub forks](https://img.shields.io/github/forks/Xunlian-Wu/Awesome-Multi-View-Graph-Clustering?color=blue&label=Forks) 

Welcome to the **Awesome Multi-View Graph Clustering** repository! This is a curated collection of resources, papers, and methodologies dedicated to **Multi-View Graph Clustering** in complex networks. Multi-view graph clustering, an advanced form of graph clustering, leverages multiple perspectives or views of data to reveal hidden structures and communities within networks. This repository aims to be a comprehensive guide for researchers and practitioners exploring this fascinating area, covering a wide range of topics from foundational theories to state-of-the-art techniques.

Multi-view graph clustering is pivotal for understanding complex systems where entities interact in multiple contexts, such as:

- **Social Networks**: Analyzing diverse interactions like friendships, professional connections, and shared interests to better understand community structures.
- **Biological Networks**: Integrating various biological interactions, such as gene regulation, protein-protein interactions, and metabolic pathways, to uncover functional modules.
- **Communication Networks**: Studying different types of communications, such as email exchanges and social media interactions, to detect underlying group dynamics.

Whether you are a researcher looking to delve into the nuances of multi-view graph clustering, a practitioner seeking to apply these techniques to real-world problems, or a student eager to learn about this cutting-edge field, this repository is your go-to resource for everything multi-view graph clustering!

---

📚 **Contents**

- [Papers](#papers)  
- [Datasets](#datasets)  
- [Useful Libraries](#useful-libraries)
- [References](#references)

---

## <a name="papers"></a> 📑 Papers

### Multi-view graph clustering

| Year | Title                                                        |       CA        |                       Institution                        | **Venue** |                            Paper                             |                         Code                         |
| :--: | :----------------------------------------------------------- | :-------------: | :------------------------------------------------------: | :-------: | :----------------------------------------------------------: | :--------------------------------------------------: |
| 2024 | **Dual Information Enhanced Multi-view Attributed Graph Clustering** | Chang-Dong Wang |                  Sun Yat-sen University                  |  *TNNLS*  |           [Link](https://arxiv.org/pdf/2211.14987)           |     [Link](https://github.com/JiaqiLin-AI/DIAGC)     |
| 2024 | **Graph ClusteringContrastive Multiview Attribute Graph Clustering With Adaptive Encoders** | Chang-Dong Wang |                  Sun Yat-sen University                  |  *TNNLS*  | [Link](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10509800) |                          --                          |
| 2024 | **Multi-view attributed graph clustering based on graph diffusion convolution with adaptive fusion** | Zhi hong Zhang  |                   Zhengzhou University                   |  *ESWA*   | [Link](https://www.sciencedirect.com/science/article/pii/S0957417424021535) |                          --                          |
| 2024 | **Scalable and Structural Multi-view Graph Clustering with Adaptive Anchor Fusion** |   Xinwang Liu   |        National University of Defense Technology         |   *TIP*   | [Link](https://ieeexplore.ieee.org/abstract/document/10643455) |  [Link](https://github.com/wangsiwei2010/SMVAGC-SF)  |
| 2024 | **Multi-view fair-augmentation contrastive graph clustering with reliable pseudo-labels** |     Wei Xu      |                    Renmin University                     |   *IS*    | [Link](https://www.sciencedirect.com/science/article/pii/S0020025524006534) |        [Link](https://github.com/buthi/MFCGC)        |
| 2023 | **Sample-level Multi-view Graph Clustering**                 |  Shudong Huang  |                    Sichuan University                    |  *CVPR*   | [Link](https://openaccess.thecvf.com/content/CVPR2023/papers/Tan_Sample-Level_Multi-View_Graph_Clustering_CVPR_2023_paper.pdf) | [Link](https://github.com/huangsd/Sample-Level-MVGC) |
| 2023 | **Metric Multi-View Graph Clustering**                       |  Shudong Huang  |                    Sichuan University                    |  *AAAI*   | [Link](https://ojs.aaai.org/index.php/AAAI/article/view/26188) |       [Link](https://github.com/huangsd/MMGC)        |
| 2023 | **Clustering Information-guided Multi-view Contrastive Graph Clustering** |   Jinke Wang    |                     Henan University                     | *ICPADS*  | [Link](https://ieeexplore.ieee.org/abstract/document/10476196/) |      [Link](https://github.com/tczgithub/IGMC)       |
| 2023 | **Simultaneous linear multi-view attributed graph representation learning and clustering** |  Mohamed Nadif  |                 *Université Paris Cité*                  |  *WSDM*   |      [Link](https://hal.science/hal-04467651/document)       |      [Link](https://github.com/chakib401/LMGEC)      |
| 2023 | **Deep multi-view graph clustering network with weighting mechanism and collaborative training** |   Fuyuan Cao    |                    Shanxi University                     |  *ESWA*   | [Link](https://www.sciencedirect.com/science/article/pii/S0957417423018006) |                          --                          |
| 2021 | **Multi-view Contrastive Graph Clustering**                  |    Zhao Kang    | University of Electronic Science and Technology of China |  *NIPS*   | [Link](https://proceedings.neurips.cc/paper/2021/file/10c66082c124f8afe3df4886f5e516e0-Paper.pdf) |        [Link](https://github.com/Panern/MCGC)        |
| 2021 | **Graph Filter-based Multi-view Attributed Graph Clustering** |    Zhao Kang    | University of Electronic Science and Technology of China |  *IJCAI*  |   [Link](https://www.ijcai.org/proceedings/2021/0375.pdf)    |       [Link](https://github.com/sckangz/MvAGC)       |
| 2021 | **Multi-view Attributed Graph Clustering**                   |    Zhao Kang    | University of Electronic Science and Technology of China |  *TKDE*   | [Link](https://www.researchgate.net/profile/Zhao-Kang-6/publication/353747180_Multi-view_Attributed_Graph_Clustering/links/612059cd0c2bfa282a5cd55e/Multi-view-Attributed-Graph-Clustering.pdf) |       [Link](https://github.com/sckangz/MAGC)        |
| 2020 | **Multi-View Attribute Graph Convolution Networks for Clustering** |  Quanxue *Gao*  |                    Xidian University                     |  *IJCAI*  |   [Link](https://www.ijcai.org/proceedings/2020/0411.pdf)    |       [Link](https://github.com/IMKBLE/MAGCN)        |
| 2019 | **Contextual Correlation Preserving Multiview Featured Graph Clustering** |    Yang Liu     |               Hong Kong Baptist Universit                |  *TCYB*   | [Link](https://dr.ntu.edu.sg/bitstream/10356/147805/2/T-Cyber-v19.pdf) |   [Link](https://github.com/he-tiantian/CCPMVFGC)    |

---

## <a name="datasets"></a> :label: Datasets

Links to publicly available multi-view graph datasets, including descriptions and recommended use cases.

| Datasets | Nodes | Edges | Features | Link |
| :------: | :---- | :---: | :------: | :--: |
|          |       |       |          |      |
|          |       |       |          |      |
|          |       |       |          |      |

---

## <a name="useful-libraries"></a> 📖 Useful Libraries

- [A Comprehensive Survey of Community Detection Approaches: From Statistical Modeling to Deep Learning](#)

---

Happy researching! If you find this repository useful, feel free to star ⭐ it and contribute.

