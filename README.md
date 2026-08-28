# Michael Feldman

Robotics and research software engineering — embodied systems, simulation, and the data
infrastructure underneath them.

Previously RSE at **Stanford** ([METER-AI](https://meter-ai.web.app/team), Doerr School of
Sustainability), architecting cloud pipelines over 14M+ records and leading the open-sourcing of a
methane emissions dataset now used by [Planet](https://www.planet.com/) and
[CarbonMapper](https://carbonmapper.org/). Currently focused on physical AI: the NVIDIA Isaac and
Omniverse stack, vision-language-action models, and sim-to-real transfer — and working toward the
**NVIDIA OpenUSD Development Professional** certification.

Exploring **Gemini Robotics-ER** (Google DeepMind) for embodied reasoning — spatial grounding, and
how a general vision-language model's scene understanding maps onto a real robot's action space.

### 🤖&nbsp; Robotics

|     |     |     |
| :-: | :-: | :-- |
| [Chip's Robot Adventure](https://github.com/mfeldman143/Chip-s-Robot-Adventure) | ![](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white) | Browser maze game synchronized in real time to a physical LEGO MINDSTORMS Inventor hub over Bluetooth |

### 🕸️&nbsp; Graph Libraries

The `mgraph.*` suite — a modern ES module refactoring of the `ngraph.*` ecosystem, rebuilt with
typed entry points, Vitest, and Rollup bundles. All eight packages are published to npm.

|     |     |     |
| :-: | :-: | :-- |
| [mgraph.forcelayout](https://github.com/mfeldman143/mgraph.forcelayout) | ![](https://img.shields.io/npm/dm/mgraph.forcelayout?label=%E2%86%93&color=blue) | Force directed graph drawing layout |
| [mgraph.graph](https://github.com/mfeldman143/mgraph.graph) | ![](https://img.shields.io/npm/dm/mgraph.graph?label=%E2%86%93&color=blue) | Modern graph data structure for JavaScript |
| [mgraph.random](https://github.com/mfeldman143/mgraph.random) | ![](https://img.shields.io/npm/dm/mgraph.random?label=%E2%86%93&color=blue) | Seeded random number operations for `mgraph.*` |
| [mgraph.events](https://github.com/mfeldman143/mgraph.events) | ![](https://img.shields.io/npm/dm/mgraph.events?label=%E2%86%93&color=blue) | Modern eventing library for Node.js and browsers |
| [mgraph.merge](https://github.com/mfeldman143/mgraph.merge) | ![](https://img.shields.io/npm/dm/mgraph.merge?label=%E2%86%93&color=blue) | Simple merge utility to extend objects without extra dependencies |
| [mgraph.fromdot](https://github.com/mfeldman143/mgraph.fromdot) | ![](https://img.shields.io/npm/dm/mgraph.fromdot?label=%E2%86%93&color=blue) | Load DOT files into `mgraph.graph` |
| [mgraph.generators](https://github.com/mfeldman143/mgraph.generators) | ![](https://img.shields.io/npm/dm/mgraph.generators?label=%E2%86%93&color=blue) | Graph generators library |
| [mgraph.fromjson](https://github.com/mfeldman143/mgraph.fromjson) | ![](https://img.shields.io/npm/dm/mgraph.fromjson?label=%E2%86%93&color=blue) | Load graphs from a simple JSON format |

### 🧰&nbsp; Agents & Tooling

|     |     |     |
| :-: | :-: | :-- |
| [corrigible-mcp-tools](https://github.com/mfeldman143/corrigible-mcp-tools) | ![](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white) | Decorators adding confidence scoring, circuit breakers, provenance logging, and consequence-based checkpoints to MCP tools |
| [cerebras-neurips-2024-chatbot](https://github.com/mfeldman143/cerebras-neurips-2024-chatbot) | ![](https://img.shields.io/badge/deployed-vercel-black?logo=vercel) | Conference chatbot built on Cerebras inference, deployed for NeurIPS 2024 |

---

## What I'm Working Through

Not my code — the stack I read, run, and build against, grouped by where it sits in the pipeline.
Entries marked `*` are ones I've forked and am actively running.

### 🟩&nbsp; NVIDIA Physical AI

|     |     |     |
| :-: | :-: | :-- |
| [cosmos](https://github.com/NVIDIA/cosmos) | ![](https://img.shields.io/github/stars/NVIDIA/cosmos?label=%E2%98%85) | World foundation models, datasets, and tooling for physical AI |
| [Isaac-GR00T](https://github.com/NVIDIA/Isaac-GR00T) | ![](https://img.shields.io/github/stars/NVIDIA/Isaac-GR00T?label=%E2%98%85) | Foundation model for generalist humanoid robots |
| [IsaacLab](https://github.com/isaac-sim/IsaacLab) | ![](https://img.shields.io/github/stars/isaac-sim/IsaacLab?label=%E2%98%85) | Unified robot learning framework built on Isaac Sim |
| [IsaacSim](https://github.com/isaac-sim/IsaacSim) | ![](https://img.shields.io/github/stars/isaac-sim/IsaacSim?label=%E2%98%85) | Robotics simulation application built on Omniverse |
| [warp](https://github.com/NVIDIA/warp) | ![](https://img.shields.io/github/stars/NVIDIA/warp?label=%E2%98%85) | Python framework for GPU-accelerated simulation and robotics |
| [curobo](https://github.com/NVlabs/curobo) | ![](https://img.shields.io/github/stars/NVlabs/curobo?label=%E2%98%85) | CUDA-accelerated motion generation and collision-free planning |
| [RoboLab](https://github.com/NVlabs/RoboLab) | ![](https://img.shields.io/github/stars/NVlabs/RoboLab?label=%E2%98%85) | Simulation benchmark for evaluating generalist robot policies |
| [physicsnemo](https://github.com/NVIDIA/physicsnemo) | ![](https://img.shields.io/github/stars/NVIDIA/physicsnemo?label=%E2%98%85) | Physics-ML framework for training surrogate and operator models |

### 🔩&nbsp; Isaac ROS & Jetson Deployment

Where the models meet the robot — hardware-accelerated ROS 2 perception on the edge.

|     |     |     |
| :-: | :-: | :-- |
| [isaac_ros_visual_slam](https://github.com/NVIDIA-ISAAC-ROS/isaac_ros_visual_slam) | ![](https://img.shields.io/github/stars/NVIDIA-ISAAC-ROS/isaac_ros_visual_slam?label=%E2%98%85) | Visual SLAM and odometry built on GPU-accelerated cuVSLAM |
| [isaac_ros_nvblox](https://github.com/NVIDIA-ISAAC-ROS/isaac_ros_nvblox) | ![](https://img.shields.io/github/stars/NVIDIA-ISAAC-ROS/isaac_ros_nvblox?label=%E2%98%85) | Accelerated 3D scene reconstruction feeding Nav2 local costmaps |
| [isaac_ros_pose_estimation](https://github.com/NVIDIA-ISAAC-ROS/isaac_ros_pose_estimation) | ![](https://img.shields.io/github/stars/NVIDIA-ISAAC-ROS/isaac_ros_pose_estimation?label=%E2%98%85) | Deep-learned 3D object pose estimation |
| [isaac_ros_cumotion](https://github.com/NVIDIA-ISAAC-ROS/isaac_ros_cumotion) | ![](https://img.shields.io/github/stars/NVIDIA-ISAAC-ROS/isaac_ros_cumotion?label=%E2%98%85) | Accelerated arm motion planning and control |
| [isaac_ros_nitros](https://github.com/NVIDIA-ISAAC-ROS/isaac_ros_nitros) | ![](https://img.shields.io/github/stars/NVIDIA-ISAAC-ROS/isaac_ros_nitros?label=%E2%98%85) | Zero-copy transport for hardware-accelerated ROS 2 graphs |
| [jetson-containers](https://github.com/dusty-nv/jetson-containers) | ![](https://img.shields.io/github/stars/dusty-nv/jetson-containers?label=%E2%98%85) | ML container builds for Jetson and JetPack-L4T |
| [TensorRT](https://github.com/NVIDIA/TensorRT) | ![](https://img.shields.io/github/stars/NVIDIA/TensorRT?label=%E2%98%85) | High-performance inference SDK — the deployment target for edge policies |
| [holoscan-sdk](https://github.com/nvidia-holoscan/holoscan-sdk) | ![](https://img.shields.io/github/stars/nvidia-holoscan/holoscan-sdk?label=%E2%98%85) | Low-latency sensor processing SDK for streaming workflows |

### 🌐&nbsp; OpenUSD

Pursuing the **NVIDIA OpenUSD Development Professional** certification — scene description as the
interchange layer between simulation, synthetic data, and robot learning.

|     |     |     |
| :-: | :-: | :-- |
| [OpenUSD](https://github.com/PixarAnimationStudios/OpenUSD) | ![](https://img.shields.io/github/stars/PixarAnimationStudios/OpenUSD?label=%E2%98%85) | Universal Scene Description — the reference implementation |
| [LearnOpenUSD](https://github.com/NVIDIA-Omniverse/LearnOpenUSD) | ![](https://img.shields.io/github/stars/NVIDIA-Omniverse/LearnOpenUSD?label=%E2%98%85) | Tutorials and reference material for OpenUSD |
| [OpenUSD-Code-Samples](https://github.com/NVIDIA-Omniverse/OpenUSD-Code-Samples) | ![](https://img.shields.io/github/stars/NVIDIA-Omniverse/OpenUSD-Code-Samples?label=%E2%98%85) | Common code snippets for OpenUSD |
| [kit-app-template](https://github.com/NVIDIA-Omniverse/kit-app-template) | ![](https://img.shields.io/github/stars/NVIDIA-Omniverse/kit-app-template?label=%E2%98%85) | Omniverse Kit application scaffold |
| [PhysX](https://github.com/NVIDIA-Omniverse/PhysX) | ![](https://img.shields.io/github/stars/NVIDIA-Omniverse/PhysX?label=%E2%98%85) | NVIDIA PhysX SDK |

### 🦾&nbsp; Robot Learning & VLA Models

|     |     |     |
| :-: | :-: | :-- |
| [lerobot](https://github.com/huggingface/lerobot)* | ![](https://img.shields.io/github/stars/huggingface/lerobot?label=%E2%98%85) | End-to-end learning for real robots, with datasets and pretrained policies |
| [openpi](https://github.com/Physical-Intelligence/openpi) | ![](https://img.shields.io/github/stars/Physical-Intelligence/openpi?label=%E2%98%85) | Open vision-language-action models from Physical Intelligence |
| [real-time-chunking-kinetix](https://github.com/Physical-Intelligence/real-time-chunking-kinetix) | ![](https://img.shields.io/github/stars/Physical-Intelligence/real-time-chunking-kinetix?label=%E2%98%85) | Real-time execution of action-chunking flow policies |
| [aloha](https://github.com/Physical-Intelligence/aloha) | ![](https://img.shields.io/github/stars/Physical-Intelligence/aloha?label=%E2%98%85) | Bimanual teleoperation hardware and software stack |
| [dm_robotics](https://github.com/google-deepmind/dm_robotics) | ![](https://img.shields.io/github/stars/google-deepmind/dm_robotics?label=%E2%98%85) | Libraries, tools, and tasks used at DeepMind Robotics |
| [dreamerv3](https://github.com/danijar/dreamerv3)* | ![](https://img.shields.io/github/stars/danijar/dreamerv3?label=%E2%98%85) | Mastering diverse domains through world models |

### 🧪&nbsp; Simulation & Physics

|     |     |     |
| :-: | :-: | :-- |
| [mujoco](https://github.com/google-deepmind/mujoco) | ![](https://img.shields.io/github/stars/google-deepmind/mujoco?label=%E2%98%85) | Multi-joint dynamics with contact — general purpose physics simulator |
| [mujoco_playground](https://github.com/google-deepmind/mujoco_playground) | ![](https://img.shields.io/github/stars/google-deepmind/mujoco_playground?label=%E2%98%85) | GPU-accelerated robot learning and sim-to-real transfer |
| [mujoco_warp](https://github.com/google-deepmind/mujoco_warp) | ![](https://img.shields.io/github/stars/google-deepmind/mujoco_warp?label=%E2%98%85) | GPU-optimized MuJoCo built for NVIDIA hardware |
| [mujoco_mpc](https://github.com/google-deepmind/mujoco_mpc) | ![](https://img.shields.io/github/stars/google-deepmind/mujoco_mpc?label=%E2%98%85) | Real-time behavior synthesis via predictive control |
| [Genesis](https://github.com/Genesis-Embodied-AI/Genesis) | ![](https://img.shields.io/github/stars/Genesis-Embodied-AI/Genesis?label=%E2%98%85) | Simulation platform for general-purpose robotics and embodied AI |
| [drake](https://github.com/RobotLocomotion/drake) | ![](https://img.shields.io/github/stars/RobotLocomotion/drake?label=%E2%98%85) | Model-based design and verification for robotics |

### 🔌&nbsp; ROS 2 & Middleware

|     |     |     |
| :-: | :-: | :-- |
| [ros2](https://github.com/ros2/ros2) | ![](https://img.shields.io/github/stars/ros2/ros2?label=%E2%98%85) | The Robot Operating System — middleware, build system, and core stack |
| [navigation2](https://github.com/ros-navigation/navigation2) | ![](https://img.shields.io/github/stars/ros-navigation/navigation2?label=%E2%98%85) | ROS 2 navigation: planning, control, recovery behaviors |
| [moveit2](https://github.com/moveit/moveit2) | ![](https://img.shields.io/github/stars/moveit/moveit2?label=%E2%98%85) | Motion planning and manipulation for ROS 2 |
| [ros2_rust](https://github.com/ros2-rust/ros2_rust)* | ![](https://img.shields.io/github/stars/ros2-rust/ros2_rust?label=%E2%98%85) | Rust bindings for ROS 2 |

### 👁️&nbsp; Perception & 3D

|     |     |     |
| :-: | :-: | :-- |
| [FoundationPose](https://github.com/NVlabs/FoundationPose) | ![](https://img.shields.io/github/stars/NVlabs/FoundationPose?label=%E2%98%85) | Unified 6D pose estimation and tracking of novel objects |
| [FoundationStereo](https://github.com/NVlabs/FoundationStereo)* | ![](https://img.shields.io/github/stars/NVlabs/FoundationStereo?label=%E2%98%85) | Zero-shot stereo matching for depth perception |
| [BundleSDF](https://github.com/NVlabs/BundleSDF) | ![](https://img.shields.io/github/stars/NVlabs/BundleSDF?label=%E2%98%85) | Neural 6-DoF tracking and 3D reconstruction of unknown objects |
| [instant-ngp](https://github.com/NVlabs/instant-ngp) | ![](https://img.shields.io/github/stars/NVlabs/instant-ngp?label=%E2%98%85) | Instant neural graphics primitives for fast scene reconstruction |
| [ORB_SLAM3](https://github.com/UZ-SLAMLab/ORB_SLAM3) | ![](https://img.shields.io/github/stars/UZ-SLAMLab/ORB_SLAM3?label=%E2%98%85) | Visual, visual-inertial, and multi-map SLAM |
| [Open3D](https://github.com/isl-org/Open3D) | ![](https://img.shields.io/github/stars/isl-org/Open3D?label=%E2%98%85) | Modern library for 3D data processing |

---

## Learning From the Best

People whose code, teaching, and taste shape how I work.

|     |     |     |
| :-: | :-: | :-- |
| [karpathy](https://github.com/karpathy) | ![](https://img.shields.io/github/followers/karpathy?label=%F0%9F%91%A5) | Andrej Karpathy — nanoGPT, micrograd; teaching by building from scratch |
| [lucidrains](https://github.com/lucidrains) | ![](https://img.shields.io/github/followers/lucidrains?label=%F0%9F%91%A5) | Phil Wang — hundreds of faithful paper implementations, attention in every form |
| [ggerganov](https://github.com/ggerganov) | ![](https://img.shields.io/github/followers/ggerganov?label=%F0%9F%91%A5) | Georgi Gerganov — llama.cpp and whisper.cpp; inference at the edge, where robots live |
| [anvaka](https://github.com/anvaka) | ![](https://img.shields.io/github/followers/anvaka?label=%F0%9F%91%A5) | Andrei Kashcha — creator of the `ngraph.*` ecosystem my `mgraph.*` suite modernizes |
| [dusty-nv](https://github.com/dusty-nv) | ![](https://img.shields.io/github/followers/dusty-nv?label=%F0%9F%91%A5) | Dustin Franklin — the Jetson edge-AI container ecosystem |
| [AtsushiSakai](https://github.com/AtsushiSakai) | ![](https://img.shields.io/github/followers/AtsushiSakai?label=%F0%9F%91%A5) | Atsushi Sakai — PythonRobotics, the canonical readable robotics algorithms |
| [danijar](https://github.com/danijar) | ![](https://img.shields.io/github/followers/danijar?label=%F0%9F%91%A5) | Danijar Hafner — world models and Dreamer; this page's format borrows from his profile |
| [RussTedrake](https://github.com/RussTedrake) | ![](https://img.shields.io/github/followers/RussTedrake?label=%F0%9F%91%A5) | Russ Tedrake — Drake and *Underactuated Robotics*; rigor in robot dynamics |
| [mberman84](https://github.com/mberman84) | ![](https://img.shields.io/github/followers/mberman84?label=%F0%9F%91%A5) | Matthew Berman — hands-on AI tooling and model evaluations |

Off GitHub: **Ilya Sutskever**, whose research program and talks shape how I think about scaling
and generalization.

---

**Certifications** — NVIDIA OpenUSD Development Professional *(in progress)* · NVIDIA Agentic AI
(2026) · Google Cloud Professional Data Engineer (2025) · Neo4j Certified Professional and Graph
Data Science (2025) · Google Cloud Professional ML Engineer (2020) · Google Cloud Professional
Cloud Architect (2018, 2020)

**Education** — M.S. Applied Statistics, Penn State · B.S. Finance, minor in Statistics, Penn State
