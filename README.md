# Abdullah Zahid
### ML/RL Engineer | Reinforcement Learning Researcher

<p align="left">
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

## About Me

I'm a results-driven **Machine Learning & Reinforcement Learning Engineer** from Pakistan with a passion for building intelligent systems that learn, adapt, and solve real-world challenges. My expertise spans deep RL algorithm design, autonomous agent development, and applied AI engineering.

I specialize in creating end-to-end systems—from training environments to aerospace-level simulations—combining rigorous mathematical foundations with practical engineering solutions.

---

##  Experience

### Reinforcement Learning Intern
**NASTP Center of Artificial Intelligence Cluster, Rawalpindi** | *Nov 2025 – Present*

A premier hub for aerospace and AI innovation; pioneering intelligent decision-making agents for dynamic environments. Work blends cutting-edge RL research with practical simulations, focusing on autonomous swarming and tactical aerial coordination.

- **Key Responsibilities**
  - Design and train advanced RL agents from scratch using DQN and PPO architectures
  - Optimize complex reward systems for stable policy convergence in custom environments
  - Develop end-to-end data pipelines utilizing NumPy and Matplotlib for visualization

- **Key Achievements**
  - Engineered 1v1 pursuit-evasion simulation using JSBSim and OpenAI Gym
  - Achieved optimal "tail-chase" positioning via PPO and reward shaping
  - Architecting multi-agent 2v1 coordination for swarm behavior

### Freelance Machine Learning Engineer
**Self-Employed** | *Aug 2025 – Oct 2025*

Provided tailored AI solutions for global clients, focusing on bridging raw data and intelligent decision-support tools.

- **Key Responsibilities**
  - Built scalable ML models (Regression, KNN, SVM) for business automation
  - Integrated CodeCarbon for carbon footprint tracking in ML pipelines
  - Optimized business intelligence workflows across energy and IoT sectors

### Project Leader in Satellite Control Unit
**Shocks & Stars Engineering, Ltd, Islamabad** | *June 2024 – May 2025*

Aerospace consultancy delivering high-integrity engineering solutions. Led development of Satellite Control Unit with AI-driven optimization.

- **Key Responsibilities**
  - Led embedded systems using ESP32 and Verilog-based logic
  - Integrated SDR for real-time telemetry
  - Developed system modeling in MATLAB and Python

- **Key Achievements**
  - Delivered low-power PCU optimization algorithm for CubeSats
  - Achieved aerospace reliability standards through FPGA simulation

---

## Education

### BSc Electrical Engineering
**Air University, Islamabad** | *Sept 2021 – June 2025* | CGPA: 2.62/4.0

**Coursework:**
- Embedded Systems, Control Systems, Circuits
- Programming (C++, Python, HTML)
- Renewable Energy, PCB Design
- Data Structures & Algorithms
- Artificial Intelligence & Machine Learning

---

## Featured Projects

### 1. 🛰️ Satellite Power & Communication Subsystem for Space Tug in LEO
**Aerospace Engineering + Python Simulation**

An end-to-end aerospace engineering project designing power and communication architecture for an autonomous Space Tug in Low Earth Orbit.

```text
┌─────────────────────────────────────────────────────────────────────┐
│                    SPACE TUG ORBITAL SYSTEM                        │
├─────────────────────────────────────────────────────────────────────┤
│                                                                     │
│                         ┌─────────────┐                              │
│                         │ SOLAR ARRAY │                              │
│                         │  PANELS    │                              │
│                         └──────┬──────┘                              │
│                                │                                     │
│                                ▼                                     │
│                    ┌───────────────────┐                              │
│                    │   POWER CONTROL  │                              │
│                    │     UNIT (PCU)   │◄────┐                       │
│                    └────────┬────────┘     │                        │
│                             │              │                        │
│              ┌──────────────┼──────────────┘                        │
│              ▼              ▼                                         │
│     ┌─────────────┐  ┌─────────────┐                                  │
│     │  BATTERY   │  │    SDR     │                                  │
│     │  STORAGE  │  │COMMUNICAT.  │──────► GROUND STATION            │
│     └───────────┘  └───────────┘                                  │
│                                                                     │
└─────────────────────────────────────────────────────────────────────┘
```

- **Tech Stack:** Python, NumPy, SciPy, Matplotlib, Pandas
- **Techniques:** Design of Experiments (DOE), Power System Modeling, SDR Communication

---

### 2. 🎯 Cooperative 2v1 Tactical Air Combat via Multi-Agent PPO
**Multi-Agent Reinforcement Learning**

Training two cooperative autonomous agents to achieve tactical positional dominance over a single adversarial target in air combat scenarios.

```text
┌─────────────────────────────────────────────────────────────────────┐
│              2v1 TACTICAL AIR COMBAT SCENARIO                      │
├─────────────────────────────────────────────────────────────────────┤
│                                                              ▲   │
│                                              INTERCEPT    │   │
│                                                PATH     │   │
│                                              ┌─────▼────┐  │   │
│                         RED AGENT A0101 ─────►│ TARGET  │◄──┘   │
│                         (Cooperating)         │(HOSTILE)│         │
│                               └───────┬──────┘────────┘         │
│                                       │                          │
│                                       │ PURSUIT                  │
│                                       │ PATH                     │
│                               ┌───────▼──────┐                   │
│                         RED AGENT A0100 ─────► (Cooperating)      │
│                                                              ▼   │
│                   ┌─────────────────────────────────────────┐    │
│                   │      MULTI-AGENT PPO TRAINING          │    │
│                   │  Shared Reward → Policy Optimization   │    │
│                   └─────────────────────────────────────────┘    │
└─────────────────────────────────────────────────────────────────────┘
```

- **Tech Stack:** PyTorch, Stable Baselines3, OpenAI Gym, Weights & Biases
- **Algorithms:** PPO, Multi-Agent RL, Reward Shaping

---

### 3. 🛡️ Safety-Robust Reinforcement Learning
**Safe RL Implementation**

A unified RL agent combining offline pre-training with safety constraints.

```text
┌─────────────────────────────────────────────────────────────────────┐
│              SAFETY-ROBUST RL ARCHITECTURE                          │
├─────────────────────────────────────────────────────────────────────┤
│                                                                     │
│   ┌──────────────┐    ┌──────────────┐    ┌──────────────┐        │
│   │   OFFLINE   │    │   SAFETY    │    │    ONLINE   │        │
│   │   PRETRAIN  │───►│ CONSTRAINT  │───►│   FINE-TUNE │        │
│   │(Behaviour   │    │(PPO-Lagrangian)│  │   (PPO)    │        │
│   │ Cloning)    │    │              │    │            │        │
│   └──────────────┘    └──────────────┘    └──────────────┘        │
│          │                   │                   │                 │
│          └───────────────────┴───────────────────┘                 │
│                              │                                      │
│                              ▼                                      │
│                    ┌─────────────────┐                             │
│                    │  SAFE ROBUST    │                             │
│                    │      AGENT     │                             │
│                    └─────────────────┘                             │
└──────────────────────────────────────────────────────────────��─��────┘
```

- **Tech Stack:** PyTorch, Gymnasium, Ray RLlib, Stable Baselines3

---

### 4. 🎓 Advanced Reinforcement Learning Roadmap
**Educational Resource**

Research-grade structured curriculum for deep RL practitioners—Phases 1-6 covering foundational to frontier methods.

```text
┌─────────────────────────────────────────────────────────────────────┐
│                   RL ROADMAP PHASES                                │
├─────────────────────────────────────────────────────────────────────┤
│                                                                     │
│  Phase 1    Phase 2    Phase 3    Phase 4    Phase 5    Phase 6   │
│  ┌─────┐    ┌─────┐    ┌─────┐    ┌─────┐    ┌─────┐    ┌─────┐ │
│  │ MDP │───►│ DQN │───►│Policy│───►│ A2C │───►│ PPO │───►│ MARL│ │
│  │     │    │     │    │Grade │    │ A3C │    │     │    │     │ │
│  └─────┘    └─────┘    └─────┘    └─────┘    └─────┘    └─────┘ │
│                                                                     │
│  Classical RL          Deep RL           Advanced Deep RL    Frontiers │
│                                                                     │
└─────────────────────────────────────────────────────────────────────┘
```

- **Algorithms Covered:** DQN, DDQN, REINFORCE, Actor-Critic, A2C/A3C, PPO, SAC, TD3, TRPO, DDPG, MARL, RLHF
- **Resources:** Slides, Code Implementations, Research Papers

---

### 5. 📊 Sentiment Analysis System
**NLP Pipeline**

Production-ready sentiment analysis pipeline on IMDB dataset achieving 92.1% accuracy.

- **Tech Stack:** Python, TensorFlow, Keras, NLTK, Scikit-learn

---

### 6. 🚦 Traffic Sign Recognition
**Computer Vision**

Custom CNN and MobileNetV2 transfer learning for 43-class German traffic sign classification.

- **Tech Stack:** Python, TensorFlow, OpenCV, NumPy

---

## Tech Stack

### 🤖 AI / ML / Deep Learning
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=flat&logo=keras&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)

### 🎮 Reinforcement Learning
![OpenAI Gym](https://img.shields.io/badge/OpenAI_Gym-0081A5?style=flat&logo=openai&logoColor=white)
![Stable Baselines3](https://img.shields.io/badge/Stable_Baselines3-FFFFFF?style=flat)
![Ray RLlib](https://img.shields.io/badge/Ray_RLlib-FFFFFF?style=flat)
![Gymnasium](https://img.shields.io/badge/Gymnasium-FFFFFF?style=flat)
![Weights & Biases](https://img.shields.io/badge/Weights_&_Biases-FFBE0B?style=flat&logo=wandb&logoColor=white)

### 📊 Data Science & Scientific Computing
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8FCBFF?style=flat&logo=scipy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-FFFFFF?style=flat)
![Pandas](https://img.shields.io/badge/Plotly-3F4F75?style=flat&logo=plotly&logoColor=white)

### 🛠️ Dev Tools & Infrastructure
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=flat&logo=visual-studio-code&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)

---

## RL Expertise Matrix

| Category | Algorithms |
|----------|------------|
| **Classical RL** | MDP, Dynamic Programming, Q-Learning, SARSA, Monte Carlo, TD |
| **Deep RL** | DQN, Double DQN, Dueling DQN, Policy Gradient, REINFORCE, Actor-Critic, A2C/A3C, DDPG |
| **Advanced Deep RL** | PPO, SAC, TD3, TRPO, Distributional RL |
| **Frontiers** | Multi-Agent RL, Hierarchical RL, Model-Based RL, Offline/Batch RL, RLHF |

---

## What I'm Working On

- 🔭 Advancing through **Phase 5+6** of RL Roadmap (Safe, Robust, Explainable RL)
- 🛰️ Extending **Satellite Power & Communication** simulations
- 🧠 Exploring **Model-Based RL** (World Models, Dreamer)
- 📖 Reading: *Reinforcement Learning: An Introduction* (Sutton & Barto)
- 🌱 Growing in: Offline RL, Hierarchical RL, Agent Alignment
- 💬 Open to: Research collaborations, ML/RL engineering roles

---

## Contact

- 📧 **Email:** abdullahzahid6555@gmail.com
- 🔗 **LinkedIn:** [linkedin.com/in/abdullahzahid655](https://www.linkedin.com/in/abdullahzahid655/)
- 💻 **GitHub:** [github.com/abdullahzahid655](https://github.com/abdullahzahid655)

---

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=abdullahzahid655&label=Profile%20Views&style=flat&color=0e75b6" alt="Profile Views"/>
  <img src="https://img.shields.io/github/followers/abdullahzahid655?style=flat&color=0e75b6" alt="GitHub Followers"/>
</p>

---

> *"The agent doesn't need to be told the rules — it discovers them through experience."*