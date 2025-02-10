# awesome-multi-robot-system [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
Recent multi-robot projects and papers: Including SLAM, datasets, place recognition, Large Language Models navigation, etc. Welcome to contribute together!


---
## Overview

  - [Multi-robot Datasets](#Multi-robot-Datasets)

  - [Multi-robot SLAM](#Multi-robot-SLAM)
    - [Visual-Based](#Visual-Based)
    - [Lidar-Based](#Lidar-Based)
    - [Distributed-Optimization](#Distributed-Optimization)
    
  - [Multi-robot Place Recognition](#Multi-robot-Place-Recognition)
  
  - [Multi-robot LLM navigation](#Multi-robot-LLM-navigation)

  - [Citation](#citation)

---


## Multi-robot Datasets

- **SubT-MRS Dataset**: Pushing SLAM Towards All-weather Environments, *CVPR, 2024*. [[Paper](https://arxiv.org/pdf/2307.07607.pdf)] [[Webpage](https://superodometry.com/datasets)]
- **DiSCO-SLAM Dataset**: - [The Park Dataset](https://drive.google.com/file/d/1-2zsRSB_9ORQ9WQdtUbGdoS4YXU3cBQt/view?usp=sharing) , [KITTI 08 Dataset](https://drive.google.com/file/d/1U6z_1VHlPJa_DJ2i8VwxkKLjf5JxMo0f/view?usp=sharing)
- **DiTER++ Dataset** - Diverse Terrain and Multi-modal Dataset for Multi-Robot Navigation in Multi-session Outdoor Environments, [[Webpage](https://sites.google.com/view/diter-plusplus)]

## Multi-robot SLAM

### Visual-Based
- **maplab 2.0**: A Modular and Multi-Modal Mapping Framework, *IEEE RA-L 2023*. [[Paper](https://arxiv.org/pdf/2212.00654.pdf)] [[Code](https://github.com/ethz-asl/maplab)]


### Lidar-Based
- **Swarm-SLAM**: Sparse Decentralized Collaborative Simultaneous Localization and Mapping Framework for Multi-Robot Systems, *RA-L 2024*. [[Paper](https://ieeexplore.ieee.org/document/10321649)] [[Code](https://github.com/MISTLab/Swarm-SLAM)]
- **DCL-SLAM**: A Distributed Collaborative LiDAR SLAM Framework for a Robotic Swarm, *IEEE SENSORS JOURNAL 2024*. [[Paper](https://ieeexplore.ieee.org/document/10375928)] [[Code](https://github.com/PengYu-Team/DCL-SLAM)]
- **CoLRIO**: LiDAR-Ranging-Inertial Centralized State Estimation for Robotic Swarms, *ICRA 2024*. [[Paper](https://arxiv.org/abs/2402.11790)] [[Code](https://github.com/PengYu-Team/Co-LRIO)]
- **Swarm-LIO**: Decentralized Swarm LiDAR-inertial Odometry, *ICRA 2023*. [[Paper](https://ieeexplore.ieee.org/document/10161355)]
- **DiSCo-SLAM**: Distributed Scan Context-Enabled Multi-Robot LiDAR SLAM With Two-Stage Global-Local Graph Optimization, *RA-L 2022*. [[Paper](https://ieeexplore.ieee.org/abstract/document/9662965)] [[Code](https://github.com/RobustFieldAutonomyLab/DiSCo-SLAM)]
- Ground and Aerial Collaborative Mapping in Urban Environments, *RA-L 2021*. [[Paper](https://ieeexplore.ieee.org/document/9234707)] [[Code](https://github.com/SYSU-RoboticsLab/GAC-Mapping)]



### Distributed-Optimization
- Distributed Trajectory Estimation with Privacy and Communication Constraints: a Two-Stage Distributed Gauss-Seidel Approach, *ICRA 2016*. [[Paper](https://ieeexplore.ieee.org/abstract/document/7487736)] [[Code](https://github.com/CogRob/distributed-mapper)]
- Distributed Mapping with Privacy and Communication Constraints: Lightweight Algorithms and Object-based Models, *CoRR 2017*.  [[Paper](http://arxiv.org/abs/1702.03435)] [[Code](https://github.com/CogRob/distributed-mapper)]
- Distributed Scan Context-Enabled Multi-Robot LiDAR SLAM With Two-Stage Global-Local Graph Optimization, *2022*. [[Paper](https://ieeexplore.ieee.org/document/9662965)] [[Code](https://github.com/RobustFieldAutonomyLab/DiSCo-SLAM)]
- Loop Closure Prioritization for Efficient and Scalable Multi-Robot SLAM, *IEEE RA-L 2022*. [[Paper](https://ieeexplore.ieee.org/abstract/document/9830830/)]
- Distributed Pose-graph Optimization with Multi-level Partitioning for Collaborative SLAM, *2024*. [[Paper](https://arxiv.org/pdf/2401.01657.pdf)] [[Code](https://github.com/tjcunhao/dpo)]


## Multi-robot Place Recognition

- **RecNet**: An Invertible Point Cloud Encoding through Range Image Embeddings for Multi-Robot Map Sharing and Reconstruction, *2024*.[[Paper](https://arxiv.org/pdf/2402.02192.pdf)] [[Webpage](https://www.youtube.com/watch?v=f9BnK34XkuQ)]
- Descriptor Distillation for Efficient Multi-Robot SLAM, *ICRA 2023*. [[Paper](https://arxiv.org/pdf/2303.08420.pdf)]
- Loop Closure Prioritization for Efficient and Scalable Multi-Robot SLAM, *IEEE RA-L 2022*. [[Paper](https://ieeexplore.ieee.org/document/9830830)] [[Code](https://github.com/NeBula-Autonomy/LAMP)]
- SlideSLAM: Sparse, Lightweight, Decentralized Metric-Semantic SLAM for Multi-Robot Navigation, *arXiv*. [[Paper](https://arxiv.org/abs/2406.17249)] [[Code](https://github.com/XuRobotics/slide-slam)]



## Multi-robot LLM navigation

- **Co-NavGPT**: Multi-Robot Cooperative Visual Semantic Navigation using Large Language Models, *2023*. [[Paper](https://arxiv.org/pdf/2310.07937.pdf)] [[Webpage](https://sites.google.com/view/co-navgpt)]



----
## Citation

If you find this repository useful, please consider citing this list:
```
@misc{grand2024awesomemultirobotpaperlist,
    title = {awesome-multi-robot-system},
    author = {Xiongwei Zhao, Zhixing Song, Juwon Kim, Gilhwan Kang},
    journal = {GitHub repository},
    email = {grandzhaoxw@gmail.com, szx504115681@gmail.com, lambertkim317@gmail.com, rlfghks527@gmail.com},
    url = {https://github.com/Grandzxw/awesome-multi-robot-system},
    year = {2024},
}
```


