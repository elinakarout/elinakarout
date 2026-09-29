<div align="center">

# Hi, I'm Elina 👋

**42 Beirut Student · Full-Stack & AI Explorer · Low-Level Programming & Systems Thinker**

</div>

---

## About Me

I'm a student at **42 Beirut**, a peer-to-peer coding school where you learn by doing — no teachers, no lectures, just projects and persistence.

I'm drawn to what happens **under the hood**: memory management, system architecture, and the elegant logic of low-level code. **Algorithms** are a particular passion of mine too. I believe understanding the foundations makes you a better engineer at every level

- 🔭 Currently working through the 42 curriculum
- 🌱 Learning **C** and **Python**
- ⚙️ Passionate about **low-level programming**, **computer architecture**, and the elegance of well-crafted **algorithms**
- 🧠 Exploring applied **AI systems** — retrieval-augmented generation, LLM tool use, and grounded assistants
- 🌐 Branching into **full-stack web development** with React, FastAPI, and PostgreSQL
- 📍 Based in **Beirut, Lebanon**

---

## 🛠️ Tech Stack

**Languages**

![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)

**Frameworks & Libraries**

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)

**Tools & Environment**

![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![Vim](https://img.shields.io/badge/VIM-%2311AB00.svg?style=for-the-badge&logo=vim&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)

---

## 🚀 Featured Projects

### 🐾 [Vet Clinic Web App](https://github.com/elinakarout/Vet-Clinic-Web-App)
> Full-stack veterinary clinic platform with role-based accounts, appointment scheduling, and an AI assistant grounded in a clinic knowledge base.

A deep dive into full-stack web development and applied RAG. The challenge: build a production-style clinic platform where pet owners, vets, and admins each get a tailored view, and where an AI assistant answers questions and proposes — but never auto-books — appointments.

- Built a React + TypeScript frontend and a FastAPI + SQLAlchemy backend with role-based access control
- Implemented appointment scheduling, confirmation, and cancellation flows across owner, vet, and admin roles
- Grounded a chat assistant in a ChromaDB knowledge base, using tool use to propose confirmable appointments
- Deployed with Docker, PostgreSQL in production, and schema migrations via Alembic
- Written in **Python** and **TypeScript**

---

### 🧠 [RAG against the machine](https://github.com/elinakarout/RAG)
> Retrieval-Augmented Generation system that answers natural-language questions about the vLLM codebase.

A deep dive into information retrieval and grounded generation. The challenge: retrieve the right source chunks from a large real-world codebase before generating an answer, judged primarily on retrieval recall against a held-out question set.

- Built a BM25 lexical index and a semantic embedding index (`all-MiniLM-L6-v2`), fused via Reciprocal Rank Fusion for hybrid retrieval
- Chunked docs and Python source with boundary-aware splitting, tracking exact character offsets back into the original files
- Generated grounded answers with a local `Qwen3-0.6B` model over retrieved context
- Reached 0.81 recall@5 on docs and 0.54 recall@5 on code against the real grader
- Written in **Python**

---

### 🐚 [minishell](https://github.com/achoukei-ekarout/minishell)
> Unix shell implementation in C with support for parsing, execution, pipes, redirections, and environment management.

A deep dive into systems programming and shell internals, focused on recreating core Bash behaviors and handling complex command execution.

- Implemented parsing, environment expansion, pipes, and redirections
- Managed processes and signals using Unix system calls
- Built an AST-based execution flow
- Built an automatic garbage collector
- Written in **C**

---

### 🚁 [Fly_In](https://github.com/elinakarout/fly_in)
> Drone routing and simulation project exploring graph-based pathfinding.

A deep dive into graph algorithms and optimization, simulating a fleet of drones navigating a network of waypoints. The challenge: compute efficient routes while handling constraints like distance, capacity, and time windows.

- Modeled the delivery network as a weighted graph
- Implemented pathfinding/routing algorithms to optimize drone trips
- Added visual representation of routes and simulation state
- Written in **Python**

---

### 👻 [Pac-Craft](https://github.com/elinakarout/pacman)
> Minecraft-themed recreation of Pac-Man in Python with `pygame`, featuring generated mazes and four ghosts with distinct AI behaviors.

A deep dive into game architecture and simple AI behavior design, built in pairs across feature branches and pull requests. The challenge: recreate faithful Pac-Man ghost logic — chase, flee, and corner behaviors — with BFS pathfinding across ten procedurally generated maze levels.

- Built a scene-based architecture (menu, level, highscores, instructions) with pydantic-validated JSON configuration
- Implemented four ghosts as a state machine with BFS pathfinding and distinct targeting behaviors (Blinky, Pinky, Inky, Clyde)
- Added a persistent JSON highscore list and a cheat mode for peer review
- Written in **Python** with **pygame**

---

### 📞 [call_me_maybe](https://github.com/elinakarout/call_me_maybe)
> Function calling in LLMs using constrained decoding, built around a small Qwen model.

A deep dive into structured generation and grammar-constrained decoding. The challenge: force a language model to reliably produce valid, schema-conformant JSON for function calls instead of hoping it gets the format right.

- Implemented constrained decoding to enforce valid JSON output
- Demonstrated dramatic reliability gains over unconstrained generation
- Benchmarked structured vs. free-form generation accuracy
- Written in **Python**

---

### 🌀 [a_maze_ing](https://github.com/AliChoukeir/A_maz_ing)
> Maze generation and solving project in Python.

Exploring different Maze generation and solving algorithms, notably DFS algorithm, Kruskal's Algorithm, and A* algorithm.

- Added visual representation of the maze.
- Written in **Python**

---

### 🔧 [codexion](https://github.com/elinakarout/Codexion)
> Multithreading simulation in C where coders debug and compile code using shared resources protected by dongles (mutexes).

A deep dive into concurrent programming, thread synchronization, and deadlock prevention. The challenge: coordinate multiple coders competing for limited debugging and compilation dongles without causing race conditions or deadlocks.

- Implemented thread-safe resource management using mutexes
- Prevented deadlocks with careful lock ordering
- Visualized thread states and resource allocation
- Written in **C**with **pthreads**

---

### 🔀 [push_swap](https://github.com/agnesabimoussa/push-swap)
> Sorting algorithm implementation in C using two stacks and a limited set of operations.

A deep dive into algorithmic thinking and complexity optimization. The challenge: sort a stack of integers using the fewest possible moves with only push, swap, and rotate operations.

- Implemented efficient sorting strategies for various input sizes
- Focused on minimizing instruction count
- Pure **C**, no external libraries


## 📊 GitHub Stats

<div align="center">

![Elina's GitHub Stats](https://github-readme-stats.vercel.app/api?username=elinakarout&show_icons=true&theme=tokyonight&hide_border=true&count_private=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=elinakarout&layout=compact&theme=tokyonight&hide_border=true)

![GitHub Streak](https://streak-stats.demolab.com?user=elinakarout&theme=tokyonight&hide_border=true)

</div>

---

## 📫 Get in Touch

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-elinakarout-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](www.linkedin.com/in/elinakarout) &nbsp; &nbsp; [![Gmail](https://img.shields.io/badge/Gmail-elinakarout-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:elliekarout@gmail.com)
</div>

---

<div align="center">
  <i>"First, solve the problem. Then, write the code."</i>
</div>
