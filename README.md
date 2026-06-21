<h1 align="center">Hi, I'm Jihao Dong 👋</h1>

<p align="center">
  <b>Robotics · Reinforcement Learning · World Models</b><br>
  M.Sc. student @ <b>Karlsruhe Institute of Technology (KIT)</b> — Automation, Control & Robotics
</p>

---

I work at the intersection of **reinforcement learning** and **robot control**, with a focus on
**legged & humanoid locomotion**, **world models for planning**, and **sim-to-real transfer**.
Previously B.Eng. in Intelligent Manufacturing @ Shandong University; currently pursuing my
M.Sc. at KIT in Germany.

- 🔭 Currently working on **RL-based perceptive locomotion** for humanoid robots (Unitree G1)
- 🌱 Exploring **world models** (DreamerV3 / LeWM / DINO-WM) for planning & control
- 💬 Ask me about **RL, MPC, world models, sim-to-real, legged robots**
- 📫 Reach me at **Jihaodong6@gmail.com**

---

### 🧠 Research Interests

- **RL for locomotion** — humanoid & quadruped, perceptive locomotion, parkour, Teacher–Student / Asymmetric Actor-Critic
- **World models** — latent-space prediction & planning (DreamerV3, LeWM/JEPA, DINO-WM)
- **RL × MPC** — learning to shape model-predictive controllers for agile, robust gaits
- **Sim-to-real** — closing the sim2sim / sim2real gap for deployment on real hardware
- **Video prediction & representation learning** for dynamic scene understanding

---


### 🚀 Featured Projects

**🌍 [World Models — Multi-task Training & Evaluation](https://1yi-ding.github.io/wm/)**
Reproduced **DreamerV3** and **LeWM** from scratch across Minecraft, ProcGen CoinRun, Cube, and PushT on a dual-RTX 4090 workstation. Migrated the dataset from HDF5 to **Lance** to cut per-epoch time **67 → 55 min**, and stabilized long runs at ~45 fps with a bounded replay buffer. → [Project page](https://1yi-ding.github.io/wm/)

**🦿 RL-MPC Quadruped Locomotion**
Reproduced an RL + Model-Predictive-Control framework where an upper-level **PPO policy predicts MPC cost weights** for agile gaits (Trot/Walk/Bound/Pace/Pronk/Gallop). OSQP-Eigen solver at ~1 ms; Actor-Critic maps a 48-D observation to 12-D actions, running at **100 Hz** in Isaac Gym.

**🎥 MS-CVFNet — Video Prediction for Autonomous Driving**
Proposed a **Multi-Scale Content-aware Voxel Fusion Network** for urban traffic scene prediction. On Cityscapes & KITTI, beat the SOTA DMVFN on MS-SSIM by **~1.3%** and improved LPIPS by **~10%**.

---

### 📫 Connect

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/1YI-DING)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jihao-dong-53135a384)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:Jihaodong6@gmail.com)

---

### 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=1YI-DING&show_icons=true&theme=tokyonight" height="165" alt="stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=1YI-DING&layout=compact&theme=tokyonight" height="165" alt="top langs" />
</p>

<!--
**1YI-DING/1YI-DING** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
