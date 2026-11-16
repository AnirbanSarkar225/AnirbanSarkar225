# Anirban Sarkar

<p align="left">
  <strong>Undergraduate Software & AI Engineer</strong><br>
  B.Tech in Computer Science & Engineering (Artificial Intelligence) &bull; Brainware University (Expected 2028)<br>
  Kolkata, India
</p>

<p align="left">
  <a href="https://portfolio-chi-six-1rjbyr5rd0.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-Live_Site-2563EB?style=flat-square&logo=vercel&logoColor=white" alt="Portfolio"></a>
  <a href="https://linkedin.com/in/AnirbanSarkar"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:sarkaranirban405@gmail.com"><img src="https://img.shields.io/badge/Email-sarkaranirban405@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://github.com/AnirbanSarkar225"><img src="https://img.shields.io/badge/GitHub-AnirbanSarkar225-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub"></a>
</p>

---

## 👨‍💻 Engineering Profile

I am a third-year undergraduate engineering student specializing in Artificial Intelligence and Software Engineering. My technical work focuses on building robust, maintainable, and verifiable systems across three core areas:

1. **Applied Machine Learning & NLP:** Designing explainable classification pipelines, multi-model ensembles, and model evaluation suites backed by empirical metrics.
2. **Backend & Systems Engineering:** Building scalable API services with FastAPI, Express, and Java, emphasizing clean layered architecture (DAO/Service), database integrity, and asynchronous operations.
3. **Autonomous Robotics & Embedded Systems:** Developing test-driven navigation frameworks (ROS 2 Jazzy, Gazebo) with pure-Python algorithmic cores, hardware-in-the-loop telemetry, and threat-modeled security.

My focus is on engineering depth: writing clean, well-tested code, understanding algorithmic trade-offs, and documenting systems thoroughly.

---

## 🛠️ Technical Competencies

Verified through implemented, tested, and maintained repositories:

| Domain | Technologies & Frameworks |
|---|---|
| **Programming Languages** | Python, Java (21), C, JavaScript (ES6+), SQL |
| **AI & Machine Learning** | Scikit-learn, PyTorch, Hugging Face Transformers, ONNX Runtime, NLTK, SpaCy, SHAP, LIME |
| **Backend Architecture** | FastAPI, Uvicorn, Node.js, Express.js, RESTful APIs, WebSockets, Pydantic |
| **Database & Persistence** | PostgreSQL (Supabase, Neon), SQLite, SQLAlchemy (Async), JDBC, Schema Design |
| **Software Design** | 3-Tier Layered Architecture, DAO Pattern, Role-Based Access Control (RBAC), OOP |
| **Robotics & Simulation** | ROS 2 (Jazzy), Gazebo Harmonic, Nav2, SLAM Toolbox, Path Planning (A*, Dijkstra, BFS) |
| **Frontend & UI** | React.js, Vite, Streamlit, Java Swing, HTML5/CSS3, Chart.js |
| **DevOps & Verification** | Git, GitHub, Maven, Pytest, JUnit 5, MyPy, WSL2, Linux Environment |

---

## 🚀 Featured Engineering Projects

### 1. [TruthShield — AI Credibility Intelligence Platform](https://github.com/AnirbanSarkar225/Fake-News-Detector)
> **Stack:** Python &bull; Scikit-learn &bull; PyTorch &bull; Transformers &bull; Streamlit &bull; FastAPI &bull; SHAP &bull; ONNX
* Full-stack explainable AI platform that predicts article credibility using an ensemble classifier (`LinearSVC`, `LogisticRegression`, `PassiveAggressive`, `ExtraTrees`) trained across **128,769 verified news articles** with 75,000 TF-IDF features.
* Achieved **89.92% test accuracy**, **89.04% precision**, **93.36% recall**, and **0.9652 ROC-AUC** on an independent test split of 25,754 samples.
* Features sentence-level suspicion heatmaps, SHAP feature attribution, live Google Fact Check API integration, and automated PDF intelligence report export.

### 2. [Inventory Management System](https://github.com/AnirbanSarkar225/InventoryManagementSystem)
> **Stack:** Java 21 &bull; Java Swing &bull; SQLite (JDBC) &bull; Maven &bull; JUnit 5
* Desktop enterprise application implementing a clean 3-tier layered architecture (Presentation UI &rarr; Service Layer &rarr; Data Access Object Layer &rarr; SQLite).
* Built-in security with SHA-256 + salt password hashing and strict Role-Based Access Control (Admin, Manager, Cashier).
* Complete unit testing suite with JUnit 5 covering password hashing security, stock transaction integrity, and service validation rules.

### 3. [AegisNav — Autonomous Robot Navigation Framework](https://github.com/AnirbanSarkar225/AegisNav) *(Local Showcase)*
> **Stack:** Python 3.12+ &bull; ROS 2 Jazzy &bull; Gazebo Harmonic &bull; Nav2 &bull; SLAM Toolbox &bull; Pytest &bull; MyPy
* Modular, threat-modeled autonomous navigation framework developed across 7 progressive milestones (M1–M7).
* Pure-Python path planning core (A*, Dijkstra, BFS, Octile distance) decoupled from middleware, achieving **98.7% test coverage across 93 unit tests**.
* Integrated dynamic obstacle detection, real-time A* replanning, camera hazard detection, and formal security threat verification (T1–T9).

### 4. [AlphaRail — Railway Telemetry & Digital Twin Prototype](https://github.com/AnirbanSarkar225/AlphaRail)
> **Stack:** FastAPI &bull; Python &bull; SQLAlchemy (Async) &bull; aiosqlite &bull; JavaScript &bull; Chart.js
* Operational digital twin prototype providing real-time telemetry tracking and monitoring across major Indian railway corridors (Howrah – New Delhi, Patna – New Delhi).
* Features asynchronous database transactions, route collision detection heuristics, OpenWeatherMap weather impact modeling, and emergency SOS incident dispatch.

### 5. [Gita-NeuroSync — Biosignal Telemetry & Cognitive Wellness Platform](https://github.com/AnirbanSarkar225/Mind-health)
> **Stack:** React &bull; Node.js &bull; Express &bull; WebSocket &bull; PostgreSQL / In-Memory DB &bull; Google Gemini LLM &bull; ESP32
* Multi-tier wellness prototype bridging IoT hardware telemetry (ESP32 biosignals) with real-time mental state classification (Focus, Stress, Relaxed, Agitated).
* Leverages Google Gemini LLM prompts for philosophical cognitive reappraisal (Vedantic grounding) and WebSockets for low-latency live telemetry broadcasting.
* Features zero-dependency local in-memory fallback for offline operation alongside persistent cloud PostgreSQL support.

---

## 📈 Engineering Principles & Commitments

* **Empirical Validation:** Machine learning metrics are reported directly from evaluated test partitions, never confused with training figures or inflated.
* **Separation of Concerns:** Business logic, algorithmic engines, and data access layers remain cleanly decoupled from presentation frameworks.
* **Security & Reliability:** Zero tolerance for hardcoded credentials, active secrets in repositories, or unhandled null states.
* **Reproducibility:** Every major project contains pinned dependency manifests, clean `.env.example` configurations, and verified startup scripts.

---

## 📬 Contact & Links

* **Portfolio Website:** [portfolio-chi-six-1rjbyr5rd0.vercel.app](https://portfolio-chi-six-1rjbyr5rd0.vercel.app/)
* **LinkedIn:** [linkedin.com/in/AnirbanSarkar](https://linkedin.com/in/AnirbanSarkar)
* **Email:** [sarkaranirban405@gmail.com](mailto:sarkaranirban405@gmail.com)
* **GitHub:** [@AnirbanSarkar225](https://github.com/AnirbanSarkar225)
