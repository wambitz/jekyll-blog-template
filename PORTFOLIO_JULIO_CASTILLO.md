# Julio Castillo — Portfolio Projects and Technical Achievements

GitHub: https://github.com/wambitz
Generated on: 2026-06-05

## Executive Summary

This portfolio highlights the strongest public evidence of my software engineering work based on my GitHub repositories and commit history. The focus is on projects that best demonstrate practical engineering ability, architectural thinking, systems work, robotics/autonomy interests, C++ depth, developer tooling, and applied AI experimentation.

This is intentionally curated. It does not try to present every repository equally. A good portfolio is selective.

## Strongest Technical Themes

- Modern C++ development and systems programming
- Robotics and autonomous systems tooling
- Sensor fusion, simulation, and point cloud workflows
- Developer environments using Docker and devcontainers
- Performance tooling and profiling workflows
- Applied AI and LAG/RAG-style experimentation
- Technical writing and knowledge packaging

## Most Impressive Achievements

### 1. Built and refactored a C++ game engine prototype with inversion of control
**Repository:** `wambitz/game-engine`

Why it matters:
- Shows architectural thinking, not just feature coding
- Demonstrates awareness of decoupling and extensibility
- Indicates you think in terms of plugin systems and engine boundaries

Evidence from commit history:
- `feat: Implement inversion of control for plugin architecture`
- `feat: add render to engine namespace`
- `feat: add headers for render and plugin`
- `ci: debugging and build VS Code configs`
- `chores: apply clang-format`

Portfolio angle:
- This is more impressive than a toy app because it points to architectural intent.
- The inversion-of-control refactor is exactly the kind of thing that signals software design maturity.

### 2. Created a ROS Noetic development environment using Docker
**Repository:** `wambitz/ros-noetic-workspace`

Why it matters:
- Shows practical robotics workflow engineering
- Demonstrates environment standardization and reproducibility
- Useful for teams, onboarding, and reducing local setup friction

Portfolio angle:
- This is the kind of project hiring teams actually care about because it solves setup pain.
- It shows you can package complex tooling, not just write source code.

### 3. Worked hands-on with autonomous driving / robotics simulation ecosystems
**Repositories:**
- `wambitz/carla`
- `wambitz/IsaacSim`
- `wambitz/sensor-fusion-lidar-obstacle-detection`
- `wambitz/sensor-fusion-camera`
- `wambitz/ros2-point-cloud-clustering-and-segmentation-devcontainer`
- `wambitz/pcl-examples`

Why it matters:
- These repos establish a clear technical direction: robotics, autonomy, simulation, and perception
- Even where some repositories are forks or course-based, the overall body of work is coherent
- The cluster is stronger than any one repo alone because it shows repeated investment in the same technical domain

Portfolio angle:
- Present this as a specialization thread, not as isolated repos.
- The signal is: “I am not randomly dabbling. I have a sustained interest in robotics/simulation/perception tooling.”

### 4. Implemented a C++ memory-management teaching chatbot project
**Repository:** `wambitz/memory-management-chatbot`

Why it matters:
- Shows ability to combine C++ concepts with interactive application behavior
- Commit history suggests progressive implementation of ownership semantics and memory-safety concepts
- Signals that you can explain technical topics, not only use them

Evidence from commit history:
- `feat: task 0, solve double pointer deletion.`
- `feat: task 1, exclusive ownership 1`
- `feat: task 2, the rule of five`
- `feat: task 3, exclusive ownership 2`
- `feat: task 4, moving smart pointers`
- `feat: task 5, moving the chatbot`
- `feat: implement chatbot`

Portfolio angle:
- This is a good showcase piece because it combines engineering, pedagogy, and C++ fundamentals.
- It is stronger than generic CRUD work because it reflects real technical subject matter.

### 5. Built tooling around Intel VTune and containerized profiling workflows
**Repositories:**
- `wambitz/vtune-docker-image`
- `wambitz/vtune-image`
- `wambitz/vtune-profiling`

Why it matters:
- Shows performance-engineering awareness
- Demonstrates comfort with systems tooling, containerization, and profiling workflows
- Indicates you care about observability and optimization, not just feature delivery

Portfolio angle:
- This is niche in a good way.
- It differentiates you from candidates who only build apps but never think about runtime behavior or measurement.

### 6. Built and maintained C++ interview preparation material with runnable examples
**Repository:** `wambitz/cpp-interview-preparation`

Why it matters:
- Shows organized technical communication
- Demonstrates ability to distill core language concepts into examples
- Good evidence of structured knowledge in modern C++

Evidence from commit history:
- `Add C++ interview preparation code examples`

Portfolio angle:
- This is a supporting project, not the centerpiece.
- Use it to reinforce your identity as someone strong in C++ fundamentals.

### 7. Created technical content infrastructure and engineering write-ups
**Repositories:**
- `wambitz/tech-blog`
- `wambitz/jekyll-blog-template`

Why it matters:
- Technical writing is underrated and useful
- Shows you can document, explain, and package ideas for others
- Makes the portfolio more credible because it adds narrative and context

Portfolio angle:
- Don’t oversell this as “product engineering.”
- Sell it honestly as technical communication and developer education.

### 8. Explored applied AI workflows, prompts, and generative tooling
**Repositories:**
- `wambitz/llm-prompts`
- `wambitz/agents-guidelines`
- `wambitz/rag-stable-difussion-models`
- `wambitz/ComfyUI`

Why it matters:
- Shows awareness of current AI tooling and workflow design
- Suggests experimentation with prompt engineering, agent guardrails, and diffusion pipelines
- Useful as a secondary theme, especially when framed as tooling exploration rather than inflated “AI platform” claims

Portfolio angle:
- Keep this grounded.
- If these repos are exploratory, say so. That is still legitimate.
- The credible framing is: applied experimentation with LLM workflows, agent constraints, and image-generation ecosystems.

## Best Repositories to Present Publicly

If I were curating the portfolio hard, I would prioritize these:

1. `game-engine`
2. `ros-noetic-workspace`
3. `memory-management-chatbot`
4. `sensor-fusion-lidar-obstacle-detection`
5. `pcl-examples`
6. `ros2-point-cloud-clustering-and-segmentation-devcontainer`
7. `vtune-docker-image`
8. `cpp-interview-preparation`
9. `tech-blog`
10. `rag-stable-difussion-models`

## Repositories to Treat as Supporting Evidence, Not Headliners

These are still useful, but should not dominate a portfolio unless they are much more substantial than the surface metadata suggests:

- `cpp-template`
- `docker-installer`
- `PythonFlask-JobBoard`
- `FlaskRESTfulAPI`
- `rest-apis-flask-python`
- `snake-game`
- `concurrent-traffic-simulation`
- `pet-image-classifier`
- `mongo-python-api`
- `AdvancedGit`

Why:
- Some look educational, template-based, or starter-like
- Some are useful but not especially differentiating
- Some may be better kept as supporting breadth rather than primary signal

## Suggested Portfolio Narrative

### Short Version
I am a software engineer with strong interest and hands-on work in modern C++, systems programming, robotics/autonomy tooling, simulation environments, point cloud processing, containerized developer workflows, and applied AI experimentation.

### Stronger Version
My work emphasizes practical engineering over hype: C++ systems and architecture, robotics/simulation environments, reproducible developer tooling, and technical projects that show both implementation ability and conceptual depth. I tend to work close to the tooling, infrastructure, and runtime behavior of software rather than only building thin application layers.

## Personal Projects

### game-engine
A C++ game engine prototype focused on engine structure, rendering boundaries, and plugin architecture. Most relevant because it shows architectural intent and inversion-of-control refactoring rather than just basic feature work.

### memory-management-chatbot
A C++ educational chatbot project built around memory management concepts such as ownership, smart pointers, move semantics, and the Rule of Five.

### ros-noetic-workspace
A Dockerized ROS development environment for consistent setup and reproducible robotics workflows.

### vtune-docker-image / vtune-image / vtune-profiling
Containerized performance-analysis workflow work centered around Intel VTune and profiling in controlled environments.

### cpp-interview-preparation
A structured repository of C++ concepts and examples intended for interview preparation and knowledge reinforcement.

### tech-blog
A technical blog repository for publishing write-ups, tutorials, and engineering notes.

### rag-stable-difussion-models
An AI-focused experimental project likely aimed at retrieval-augmented or diffusion-related workflows.

## Project Customization / Specialized Technical Work

### Robotics and Simulation Ecosystem Customization
These repositories suggest adaptation and experimentation around larger platforms, course projects, and simulation stacks:
- `carla`
- `IsaacSim`
- `ComfyUI`
- `sensor-fusion-lidar-obstacle-detection`
- `sensor-fusion-camera`
- `ros2-point-cloud-clustering-and-segmentation-devcontainer`
- `pcl-examples`

How to present this honestly:
- Customization of existing platforms and environments
- Local experimentation and workflow setup
- Applied learning in simulation, autonomy, point clouds, and AI tooling

This is valid portfolio material if framed correctly. Don’t pretend forks are original products. Present them as customization, environment work, experiments, and technical adaptation.

## Recommended Resume-Ready Achievement Bullets

- Designed and refactored a C++ game engine prototype, introducing inversion-of-control concepts for a plugin-oriented architecture.
- Built Docker-based robotics development environments to improve reproducibility and simplify ROS setup workflows.
- Developed C++ educational tooling around memory management concepts including ownership, move semantics, smart pointers, and the Rule of Five.
- Worked across robotics and simulation ecosystems including ROS, CARLA, Isaac Sim, PCL, and sensor-fusion projects.
- Created containerized performance-profiling workflows using Intel VTune for reproducible systems analysis.
- Produced technical documentation, blog content, and study materials to package and communicate engineering knowledge effectively.
- Explored practical AI workflows involving prompts, agent guardrails, and generative tooling experimentation.

## Honest Assessment

Your strongest portfolio angle is not “full-stack product engineer.”
It is closer to:
- C++ / systems-minded engineer
- robotics and simulation focused developer
- developer tooling / environment engineering
- technically curious builder with applied AI experimentation

That is the honest and strong story.

The weak angle would be trying to present everything as polished products. A lot of the value here is in technical depth, tooling, experimentation, learning velocity, and systems orientation. That is respectable, but it should be framed correctly.

## What Should Be Improved Next

If you want this portfolio to hit harder, the next practical upgrades are:

1. Add stronger READMEs to the top 5 repos
   - problem
   - architecture
   - stack
   - screenshots / diagrams
   - what you implemented vs what came from upstream

2. Pin your best repositories on GitHub
   - game-engine
   - ros-noetic-workspace
   - memory-management-chatbot
   - vtune-docker-image
   - one robotics/sensor-fusion repo
   - one AI/tooling repo

3. Add outcome-oriented proof
   - demos
   - screenshots
   - short architecture diagrams
   - benchmark/profiling results
   - before/after customization notes

4. Separate “original projects” from “forks/customizations” clearly
   - this increases credibility immediately

5. Reduce noise
   - archive weak experiments
   - improve naming where needed
   - fix typos like `difussion` if the repo is meant to be showcased

## Suggested Portfolio Title

**Julio Castillo — C++ Systems, Robotics Tooling, and Applied AI Projects**

## Contact Section Template

- GitHub: https://github.com/wambitz
- Focus areas: C++, robotics/simulation, developer tooling, performance workflows, applied AI
- Portfolio summary: Systems-minded engineer with hands-on work in C++, ROS, simulation platforms, containerized workflows, and technical learning projects.
