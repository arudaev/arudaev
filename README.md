# Alexander Rudaev

**Software Engineer** · Full-Stack · AI Systems  
B.A.Sc. Artificial Intelligence @ [Deggendorf Institute of Technology](https://www.th-deg.de/en)

I gravitate toward the role of technical anchor – the person who makes sure things actually ship, then keeps them running. Most of my professional experience is full-stack web (Next.js, Python, Docker); on my own time I build products people around me use and ML systems I can defend in a paper. I'm comfortable owning architecture decisions and writing the boring-but-critical infrastructure, though I've been actively practicing *not* over-engineering early – scoping to the simplest thing that proves the idea before the abstractions show up.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-arudaev-0A66C2?style=flat&logo=linkedin)](https://www.linkedin.com/in/arudaev/)
[![Email](https://img.shields.io/badge/Email-alex.rudaev@outlook.com-EA4335?style=flat&logo=gmail)](mailto:alex.rudaev@outlook.com)

---

### Tech Stack

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=ts,js,python,kotlin,java,cs,cpp&theme=dark" alt="Languages" />
  </a>
</p>
<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=react,nextjs,nodejs,fastapi,pytorch,supabase,postgres,docker,kubernetes,linux,git,aws,azure&theme=dark" alt="Tools & Frameworks" />
  </a>
</p>

---

### Built for fun, lately

Harold, a yellow rubber debugging duck, runs through all three.

| Project | Stack | What it is |
|---------|-------|-----------|
| 🦆 **[Voyager // 56K](https://arudaev.github.io)** | TypeScript, React Three Fiber, Three.js, Supabase | This portfolio as a game: sail Harold through the flooded internet of 1999, where every island is a project. PS1-style rendering with a CRT bezel, hand-rolled buoyancy instead of a physics engine, a nautical chart with fog of war, and phone play as an installable PWA. |
| 📺 **[Webkeeper](https://arudaev.github.io/webkeeper/)** | JavaScript, Canvas, WebGL2, Web Audio | The game on the couch's TV inside Voyager, also on its own page. A meadow drawn in text characters, with grass and flowers swaying in a WebGL2 shader, and synthesized sound where every letter is a note, so typing a word plays a tune. |
| 🐤 **[Duckwalk](https://arudaev.github.io/duckwalk/)** | C, Flipper Zero SDK, USB HID, Python | A Flipper Zero app that keeps your computer awake by walking the cursor along random paths, and doubles as its remote. GPL-3.0, with CI builds and a 24-hour soak-test harness. First release in progress. |

### Featured Projects

> These are the ones I'd actually walk you through in an interview.

| Project | Stack | What it does |
|---------|-------|-------------|
| 🏫 **[THD Room Finder](https://arudaev.github.io/THD-Room-Finder/)** | React, TypeScript, Vite, Capacitor | Which THD study rooms are free **right now – and for how long**. One codebase as an installable PWA and an Android app: duration-first ranking, 2.5D campus map, live EN/DE, framework-free unit-tested domain core, and studying together with friends. Used by students. [Open the app](https://thd-room-finder.vercel.app/) |
| 🩻 **[CheXVision](https://arudaev.github.io/chexvision/)** | Python, PyTorch, DenseNet-121, Hugging Face, Kaggle | Chest X-ray pathology detection on 112,120 NIH images. A custom SE-ResNet from scratch (**0.814** macro AUC-ROC) against DenseNet-121 transfer learning (**0.846**, vs the published CheXNet 0.841) under one fixed protocol. Architecture & cloud lead, team of four. [Paper](https://arudaev.github.io/chexvision/report/) · [live demo](https://huggingface.co/spaces/arudaev/chexvision-demo) |
| 🚢 **[Full-Stack ML Platform](https://github.com/random-iceberg/docker-compose)** | React, FastAPI, PostgreSQL, Docker | Five-service product for auth, model training and inference, and per-user prediction history. Led the seven-person team: architecture, proposal, user stories, and a review on every PR. |
| ☕ **[Kaffeelisten](https://kaffeelisten.de)** | React, TypeScript, Supabase, Vercel | Replaced the paper coffee sheet at ITC1 Deggendorf, a 28-company coworking campus – no login, under 15 seconds per entry, monthly PDF + Excel statements. Two-developer team; I owned the data model, row-level security, billing and reporting. Started at the B4Y3RW4LD Hackathon. [Pitch deck](https://arudaev.github.io/kaffeelisten) |
| 🗑️ **[Waste Sorting Assistant](https://waste-sorting-assistant.streamlit.app/)** | Python, YOLOv8, PyTorch, Streamlit, Docker | Real-time bin detection for international students in Germany: YOLOv8 fine-tuned on 466 local images, 95.2% mAP@0.5. Three-person team; I owned DevOps and deployment. |
| 🌊 **GKD4HYDRO** *(private client repo)* | Python, pandas, SciPy, Parquet, pytest | Led a four-person client project that turns Lower Bavarian river data into reproducible oscillation analyses – ramp rates, cycles, seasonal percentiles – from a single command. |

<details>
<summary><strong>Other projects</strong> (earlier work, prototypes, learning projects)</summary>

- 🌿 **[Zelara](https://github.com/zelara-ai)** – Edge-first app core: shared state, device linking, and conditional builds where inference stays on-device.
- 🚂 **[Deutsche Bahn Delay Predictor](https://arudaev.github.io/ml-db-delay-paper/)** – 2.06 million DB records, 16 engineered features, three regression approaches compared on held-out data. Team of three.
- 🏥 **[Project Apero](https://github.com/arudaev/Project-Arepo)** – Educational stroke-risk study app with a locally run Rasa assistant. Not a clinical product.
- 🤖 **Devablos V2** – Real-time React/Node.js app with OpenAI over secure WebSockets; led the five-person first-year team.
- 🌍 **[iTravel](https://github.com/arudaev/iTravel)** – Android travel app with map discovery, GPS-validated reviews, and weather/photo feeds.
- 📄 **Document Conversion Solutions** – Format-conversion toolkit across Python APIs, a web frontend, and npm packages.
- 🦄 **UNICorn** – Pre-ChatGPT university assistant on GPT-3, Whisper, and semantic search.
- 🎮 **WildForFood** – Web-based Unity game built around rapid gameplay iteration.

</details>

---

### What I'm working on right now

- **[Duckwalk](https://github.com/arudaev/duckwalk)**'s first release: Harold on a Flipper Zero
- New islands and **[Webkeeper](https://arudaev.github.io/webkeeper/)** chapters for **[Voyager // 56K](https://arudaev.github.io)**
- Final stretch of my **B.A.Sc. in AI** at THD
- A twelve-month, build-led **robotics** programme: control, state estimation, electronics, CAD

---

<p align="center">
  <sub>Let's talk → <a href="mailto:alex.rudaev@outlook.com">alex.rudaev@outlook.com</a></sub>
</p>
