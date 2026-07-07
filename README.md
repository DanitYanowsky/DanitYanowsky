<h1 align="center">Danit Yanowsky</h1>

<p align="center">
  M.Sc. Computer Science · Hebrew University of Jerusalem<br>
  Computer Vision &nbsp;·&nbsp; Representation Learning &nbsp;·&nbsp; 3D Vision &nbsp;·&nbsp; Generative Models
</p>

<p align="center">
  <a href="https://linkedin.com/in/danit-yanowsky-9122a6232">
    <img src="https://img.shields.io/badge/LinkedIn-danit--yanowsky-0A66C2?style=flat-square&logo=linkedin&logoColor=white"/>
  </a>
  &nbsp;
  <a href="mailto:danityanowsky@gmail.com">
    <img src="https://img.shields.io/badge/Email-danityanowsky%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white"/>
  </a>
</p>

---

I'm a graduate researcher at HUJI's [Weinshall Lab](https://www.cs.huji.ac.il/~daphna/), working on deep learning for visual perception. My work spans continual learning, 3D scene understanding, and controllable generation. Previously, I spent two years as an ML Ops engineer at Applied Materials, bridging research and production systems.

---

## Publication

**Leveraging Complementary Embeddings for Replay Selection in Continual Learning with Small Buffers**

Proposes **MERS** — a replay selection method that combines supervised and self-supervised embeddings (SimCLR, VICReg, DINO) to maximize buffer diversity under tight memory constraints. Formulated as weighted maximum coverage with greedy approximation guarantees.  
Improves over strong baselines on CIFAR-100 benchmarks: **+1.28 pp** at 100-sample buffers, **+1.49 pp** at 300 samples.

[![Code](https://img.shields.io/badge/Code-MERS-black?style=flat-square&logo=github)](https://github.com/DanitYanowsky/MERS)

---

## Featured Projects

### Pose-Controlled 3D Human Generation
Adapts **MVControl** (multi-view diffusion) to generate 3D humans from explicit skeleton poses using Gaussian Splatting and Score Distillation Sampling. Key contributions:
- Automatic pose-to-conditioning via **OpenPose ControlNet** + **MiDaS** depth
- Geometrically consistent 4-view masks from **SAM-3D Body** reconstruction for articulated poses
- Quantitative evaluation with MPJPE, RA-MPJPE, PCK@0.05 across three conditioning strategies

Stack: PyTorch · gsplat · ControlNet · SAM-3D · MiDaS · ViTPose · CUDA · C++

[![Repo](https://img.shields.io/badge/Code-Pose--Controlled--3D--Human--Generation-black?style=flat-square&logo=github)](https://github.com/DanitYanowsky/Pose-Controlled-3D-Human-Generation)

---

### Visual Odometry on KITTI (SLAM)
Full visual odometry pipeline on the **KITTI benchmark** (sequence #00). Implements stereo feature tracking, pose estimation, and trajectory reconstruction from raw stereo image pairs.

Stack: Python · OpenCV · NumPy

[![Repo](https://img.shields.io/badge/Code-SLAM-black?style=flat-square&logo=github)](https://github.com/DanitYanowsky/SLAM)

---

### Advanced Machine Learning Coursework
Implementations of modern generative and representation learning architectures:
**VAE** · **Normalizing Flows** · **Flow Matching** (conditional & unconditional) · Linear probing · Supervised classification

[![Repo](https://img.shields.io/badge/Code-Advanced--Course--in--Machine--Learning-black?style=flat-square&logo=github)](https://github.com/DanitYanowsky/Advanced-Course-in-Machine-Learning)

---

## Tech Stack

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white"/>
  <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white"/>
  <img src="https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white"/>
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white"/>
  <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white"/>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white"/>
</p>

---

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=DanitYanowsky&show_icons=true&hide_border=true&count_private=true&theme=default&hide_title=false" height="150"/>
  &nbsp;&nbsp;
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=DanitYanowsky&layout=compact&hide_border=true&theme=default" height="150"/>
</p>
