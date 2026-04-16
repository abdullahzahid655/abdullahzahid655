# Abdullah Zahid
### 🎯 ML/RL Engineer | Reinforcement Learning Researcher

<p align="center">
  <a href="https://www.linkedin.com/in/abdullahzahid655/">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="mailto:abdullahzahid6555@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
  </a>
  <a href="https://github.com/abdullahzahid655">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
  </a>
</p>

---

<div align="center">

![Header Banner](https://capsule-render.vercel.app/api?type=waving&height=300&color=gradient&customColorList=0,20,32,40,80,100&text=ML%20/%20RL%20Engineer&fontSize=70&animationFadeIn=easeOutQuart&desc=Building%20Intelligent%20Systems&descSize=30&descAlign=50)

</div>

---

## 🚀 About Me

<div align="center">

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=24&pause=1000&color=20FF00&center=true&vCenter=true&width=500&lines=Machine+Learning+Engineer;Reinforcement+Learning+Researcher;Aerospace+Systems+Designer;Autonomous+Agent+Developer" alt="Typing SVG"/>

</div>

I'm a results-driven **Machine Learning & Reinforcement Learning Engineer** from Pakistan with a passion for building intelligent systems that learn, adapt, and solve real-world challenges. My expertise spans deep RL algorithm design, autonomous agent development, and applied AI engineering.

I specialize in creating end-to-end systems—from training environments to aerospace-level simulations—combining rigorous mathematical foundations with practical engineering solutions.

> *"The agent doesn't need to be told the rules — it discovers them through experience."*

---

## 🔥 Featured Projects

### 1. 🎮 Cooperative 2v1 Tactical Air Combat via Multi-Agent PPO
**Multi-Agent Reinforcement Learning | High-Fidelity 6-DOF Simulation**

<div align="center">

![Air Combat](https://github.com/abdullahzahid655/Cooperative-2v1-Tactical-Air-Combat-via-Multi-Agent-PPO/raw/main/marl_diagram.png)

</div>

Training two cooperative autonomous Red agents (A0100, A0101) to achieve tactical positional dominance over a single adversarial Blue agent (B0100) in high-fidelity aerial combat.

```text
┌─────────────────────────────────────────────────────────────────────┐
│     🛩️ 2v1 TACTICAL AIR COMBAT - MULTI-AGENT PPO TRAINING        │
├─────────────────────────────────────────────────────────────────────┤
│                                                              ▲   │
│                         INTERCEPT PATH                        │   │
│                          ┌─────▼────┐  │   │
│        RED AGENT A0101 ──►│  BLUE   │◄─┘   │
│        (Cooperating)       │ TARGET  │         │
│              └───────┬─────┘────────┘         │
│                      │ PURSUIT                   │
│                      │ PATH                      │
│              ┌───────▼──────┐                   │
│        RED AGENT A0100 ────► (Cooperating)      │
│                                                              ▼   │
│         ┌──────────────────────────────────────────────┐        │
│         │     🔄 Multi-Agent PPO Training               │        │
│         │  • Shared Reward  • Centralized Critic       │        │
│         │  • Policy Optimization  • Team Coordination  │        │
│         └──────────────────────────────────────────────┘        │
└─────────────────────────────────────────────────────────────────────┘
```

**Tech Stack:** Python, PyTorch, Stable Baselines3, OpenAI Gym, JSBSim, Weights & Biases

**Key Features:**
- ✅ PPO-based Multi-Agent Reinforcement Learning
- ✅ 6-DOF Flight Dynamics
- ✅ Self-Play & vs-Baseline Training
- ✅ Reward Shaping for Air Combat
- ✅ Team Coordination Algorithms

<a href="https://github.com/abdullahzahid655/Cooperative-2v1-Tactical-Air-Combat-via-Multi-Agent-PPO">
  <img src="https://img.shields.io/badge/View_Project-007AFF?style=for-the-badge&logo=github" alt="View Project"/>
</a>

---

### 2. 🛰️ Satellite Power & Communication Subsystem for Space Tug in LEO
**Aerospace Engineering + Python Simulation + RL**

<div align="center">

![Satellite Power System](https://github.com/abdullahzahid655/Satellite-Power-Communication-Subsystem-for-Space-Tug-in-LEO/raw/main/power_margin.png)

</div>

<div align="center">

![Battery Life](https://github.com/abdullahzahid655/Satellite-Power-Communication-Subsystem-for-Space-Tug-in-LEO/raw/main/battery_life.png)

</div>

An end-to-end aerospace engineering project designing power and communication architecture for an autonomous Space Tug in Low Earth Orbit.

```text
┌─────────────────────────────────────────────────────────────────────┐
│              🛰️ H2Z SPACE TUG ORBITAL SYSTEM                     │
├─────────────────────────────────────────────────────────────────────┤
│                                                                     │
│   ☀️ SOLAR ARRAY ──► ⚡ MPPT ──► 🔋 BATTERY ──► 🎯 POWER LOAD      │
│                                                                     │
│        ┌─────────────────────────────────────────┐                  │
│        │         ORBITAL PARAMETERS              │                  │
│        │  • Altitude: 500 km                    │                  │
│        │  • Inclination: 97.4°                   │                  │
│        │  • Eclipse: 36.26 min                  │                  │
│        │  • Sunlight: 61.74 min                 │                  │
│        └─────────────────────────────────────────┘                  │
│                                                                     │
│   ┌──────────┐    ┌──────────┐    ┌──────────┐    ┌──────────┐     │
│   │  PCU    │    │   SDR   │    │  SAC RL │    │   DOE   │     │
│   │ Power  │    │   Comm  │    │ Battery │    │   Opt.  │     │
│   │Control │    │   Unit  │    │  Mgmt   │    │  Analysis│    │
│   └──────────┘    └──────────┘    └──────────┘    └──────────┘     │
└─────────────────────────────────────────────────────────────────────┘
```

**Tech Stack:** Python, NumPy, SciPy, Matplotlib, PyTorch, Stable Baselines3, SAC, Streamlit, Plotly

**Key Features:**
- ✅ Power Budget Analysis (Sunlight/Eclipse phases)
- ✅ Battery Lifecycle Optimization (SAC Reinforcement Learning)
- ✅ MPPT Efficiency Modeling
- ✅ Thermal Analysis (Stefan-Boltzmann)
- ✅ Design of Experiments (DOE) Optimization
- ✅ Interactive Streamlit Dashboard
- ✅ MLflow & W&B Experiment Tracking

<div align="center">

| Metric | Value |
|--------|-------|
| MPPT Efficiency | 97% |
| Battery SOH | 99.9% |
| Power Margin | 18.5% |
| Thermal Range | -90°C to +70°C |

</div>

<a href="https://github.com/abdullahzahid655/Satellite-Power-Communication-Subsystem-for-Space-Tug-in-LEO">
  <img src="https://img.shields.io/badge/View_Project-007AFF?style=for-the-badge&logo=github" alt="View Project"/>
</a>

---

### 3. 🛡️ Safety-Robust Reinforcement Learning
**Safe RL Implementation**

```text
┌─────────────────────────────────────────────────────────────────────┐
│           🛡️ SAFETY-ROBUST RL ARCHITECTURE                        │
├─────────────────────────────────────────────────────────────────────┤
│                                                                     │
│   ┌──────────────┐    ┌──────────────┐    ┌──────────────┐        │
│   │   OFFLINE   │    │   SAFETY    │    │    ONLINE   │        │
│   │   PRETRAIN  │───►│ CONSTRAINT  │───►│   FINE-TUNE │        │
│   │(Behaviour   │    │(PPO-Lagrangian)│  │   (PPO)    │        │
│   │ Cloning)    │    │   λ-γδ  ⚠️  │    │             │        │
│   └──────────────┘    └──────────────┘    └──────────────┘        │
│          │                   │                   │                 │
│          └───────────────────┼───────────────────┘                 │
│                              ▼                                    │
│                    ┌─────────────────┐                           │
│                    │  ✅ SAFE ROBUST  │                           │
│                    │      AGENT      │                           │
│                    └─────────────────┘                           │
└─────────────────────────────────────────────────────────────────────┘
```

**Tech Stack:** PyTorch, Gymnasium, Ray RLlib, Stable Baselines3

<a href="https://github.com/abdullahzahid655/safety-robust-RL-">
  <img src="https://img.shields.io/badge/View_Project-007AFF?style=for-the-badge&logo=github" alt="View Project"/>
</a>

---

### 4. 🎓 Advanced Reinforcement Learning Roadmap
**Educational Resource | Research-Grade Curriculum**

<div align="center">

```text
╔═════════════════════════════════════════════════════════════════════╗
║           📚 RL ROADMAP - Phases 1-6 (Research Grade)               ║
╠═════════════════════════════════════════════════════════════════════╣
║                                                                     ║
║  Phase 1    Phase 2    Phase 3    Phase 4    Phase 5    Phase 6   ║
║  ┌─────┐    ┌─────┐    ┌─────┐    ┌─────┐    ┌─────┐    ┌─────┐  ║
║  │ MDP │───►│ DQN │───►│Policy│───►│ A2C │───►│ PPO │───►│ MARL│  ║
║  │     │    │ DDQN │    │Grade │    │ A3C │    │ SAC │    │RLHF │  ║
║  └─────┘    └─────┘    └─────┘    └─────┘    └─────┘    └─────┘  ║
║     │         │         │         │         │         │          ║
║  ┌──┴───┐  ┌──┴───┐  ┌──┴───┐  ┌──┴───┐  ┌──┴───┐  ┌──┴───┐       ║
║  │Found.│  │Deep │  │Actor│  │Async│  │Policy│  │Frontier│       ║
║  │ation │  │ RL  │  │Critic│  │RL   │  │Opt. │  │ iers │       ║
║  └──────┘  └──────┘  └──────┘  └──────┘  └──────┘  └──────┘       ║
║                                                                     ║
╚═════════════════════════════════════════════════════════════════════╝
```

</div>

**Algorithms Covered:**
- 📖 Classical RL: MDP, Dynamic Programming, Q-Learning, SARSA, Monte Carlo, TD
- 🧠 Deep RL: DQN, Double DQN, Dueling DQN, REINFORCE, Actor-Critic, A2C/A3C, DDPG
- 🚀 Advanced: PPO, SAC, TD3, TRPO, Distributional RL
- 🌐 Frontiers: Multi-Agent RL, Hierarchical RL, Model-Based RL, Offline RL, RLHF

<a href="https://github.com/abdullahzahid655/Advanced_RL_roadmap">
  <img src="https://img.shields.io/badge/View_Project-007AFF?style=for-the-badge&logo=github" alt="View Project"/>
</a>

---

### 5. 📊 Sentiment Analysis System (NLP)
**Production-Ready Pipeline | 92.1% Accuracy**

**Tech Stack:** Python, TensorFlow, Keras, NLTK, Scikit-learn

---

### 6. 🚦 Traffic Sign Recognition (Computer Vision)
**Custom CNN + MobileNetV2 Transfer Learning | 43 Classes**

**Tech Stack:** Python, TensorFlow, OpenCV, NumPy

---

## 💼 Experience

### 🤖 Reinforcement Learning Intern
**NASTP Center of Artificial Intelligence Cluster, Rawalpindi** | *Nov 2025 – Present*

- Design and train advanced RL agents (DQN, PPO) for autonomous swarming
- Develop end-to-end data pipelines for agent training
- Engineer 1v1 pursuit-evasion simulations using JSBSim and OpenAI Gym
- Architecting multi-agent 2v1 coordination framework

### 🔧 Freelance Machine Learning Engineer
**Self-Employed** | *Aug 2025 – Oct 2025*

- Built scalable ML models (Regression, KNN, SVM) for business automation
- Integrated CodeCarbon for carbon footprint tracking in ML pipelines

### 🛰️ Project Leader - Satellite Control Unit
**Shocks & Stars Engineering, Ltd, Islamabad** | *June 2024 – May 2025*

- Led embedded systems using ESP32 and Verilog-based logic
- Integrated SDR for real-time telemetry
- Delivered low-power PCU optimization algorithm for CubeSats

---

## 🎓 Education

### BSc Electrical Engineering
**Air University, Islamabad** | *2021 - 2025* | CGPA: 2.62/4.0

**Relevant Coursework:**
- Embedded Systems, Control Systems, Circuits
- Programming (C++, Python, HTML)
- AI & Machine Learning, Reinforcement Learning
- Data Structures & Algorithms

---

## 🛠️ Tech Stack

<div align="center">

| Category | Technologies |
|----------|-------------|
| **AI/ML/DL** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white) ![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white) ![Keras](https://img.shields.io/badge/Keras-D00000?style=flat&logo=keras&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white) |
| **RL Frameworks** | ![OpenAI Gym](https://img.shields.io/badge/OpenAI_Gym-0081A5?style=flat&logo=openai&logoColor=white) ![Stable Baselines3](https://img.shields.io/badge/Stable_Baselines3-FFFFFF?style=flat) ![Ray RLlib](https://img.shields.io/badge/Ray_RLlib-FFFFFF?style=flat) ![Gymnasium](https://img.shields.io/badge/Gymnasium-FFFFFF?style=flat) |
| **Data Science** | ![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white) ![SciPy](https://img.shields.io/badge/SciPy-8FCBFF?style=flat&logo=scipy&logoColor=white) ![Matplotlib](https://img.shields.io/badge/Matplotlib-FFFFFF?style=flat) |
| **Dev Tools** | ![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white) |

</div>

---

## 📈 RL Expertise Matrix

<div align="center">

| Category | Algorithms |
|----------|------------|
| **Classical RL** | MDP, Dynamic Programming, Q-Learning, SARSA, Monte Carlo, TD |
| **Deep RL** | DQN, Double DQN, Dueling DQN, Policy Gradient, REINFORCE, Actor-Critic, A2C/A3C, DDPG |
| **Advanced Deep RL** | PPO, SAC, TD3, TRPO, Distributional RL |
| **Frontiers** | Multi-Agent RL, Hierarchical RL, Model-Based RL, Offline/Batch RL, RLHF |

</div>

---

## 🎯 What I'm Working On

<div align="center">

- 🔭 Advancing through **Phase 5+6** of RL Roadmap (Safe, Robust, Explainable RL)
- 🛰️ Extending **Satellite Power & Communication** simulations
- 🧠 Exploring **Model-Based RL** (World Models, Dreamer)
- 📖 Reading: *Reinforcement Learning: An Introduction* (Sutton & Barto)
- 🌱 Growing in: Offline RL, Hierarchical RL, Agent Alignment
- 💬 Open to: Research collaborations, ML/RL engineering roles

</div>

---

## 📊 GitHub Stats

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=abdullahzahid655&show_icons=true&theme=radical&hide_border=true&bg_color=0,d11932,1d1e33&title_color=39FF14&text_color=FFFFFF)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=abdullahzahid655&layout=compact&theme=radical&hide_border=true&bg_color=0,d11932,1d1e33&title_color=39FF14&text_color=FFFFFF)

</div>

---

## 📞 Contact

<div align="center">

| Contact Method | Link |
|----------------|------|
| 📧 **Email** | [abdullahzahid6555@gmail.com](mailto:abdullahzahid6555@gmail.com) |
| 🔗 **LinkedIn** | [linkedin.com/in/abdullahzahid655](https://www.linkedin.com/in/abdullahzahid655/) |
| 💻 **GitHub** | [github.com/abdullahzahid655](https://github.com/abdullahzahid655) |

</div>

---

<div align="center">

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=abdullahzahid655&label=Profile%20Views&style=flat&color=0e75b6" alt="Profile Views"/>
  <img src="https://img.shields.io/github/followers/abdullahzahid655?style=flat&color=0e75b6" alt="GitHub Followers"/>
</p>

---

⭐ *Star my repositories if you find them helpful!*

</div>

---

<div align="center">

![Footer](https://capsule-render.vercel.app/api?type=waving&height=100&color=gradient&customColorList=0,20,32,40,80,100)

</div>
