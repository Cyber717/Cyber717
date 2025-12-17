# Mark Vision

$$
\text{Mechatronics Engineer} \mid \text{Final Year} \mid \text{Control Systems} \rightarrow \text{Robotics}
$$

---

## Definition

Let $\mathcal{P}$ be the set of all projects, and $\mathcal{S}$ be the set of all skills. Define the mapping:

$$
f: \mathcal{P} \times \mathcal{S} \rightarrow \mathbb{R}^+
$$

where $f(p, s)$ represents the proficiency level of skill $s$ applied to project $p$.

---

## System Specification

### State Variables

| Variable | Domain | Description |
|----------|--------|-------------|
| $\lambda$ | $\{\text{Python}, \text{C++}, \text{MATLAB}\}$ | Primary languages |
| $\tau$ | $\{\text{OpenCV}, \text{NumPy}, \text{Git}\}$ | Toolchain |
| $\delta$ | $\{\text{Control}, \text{Vision}, \text{Planning}\}$ | Domain expertise |

### Projects

#### $\text{Project}_1$: Autonomous Vehicle Simulation

**Objective:** Implement vision-based lane following using camera input.

**Algorithm:**

$$
\begin{aligned}
\text{steering\_angle} &= \text{PurePursuit}(\mathbf{p}_{car}, \mathbf{p}_{goal}, d_{lookahead}) \\
\text{where} \quad \mathbf{p}_{goal} &= \arg\min_{\mathbf{p} \in \mathcal{L}} \|\mathbf{p} - \mathbf{p}_{car}\|_2 = d_{lookahead}
\end{aligned}
$$

**Repository:** [`autonomous-car-sim`](https://github.com/Cyber717/autonomous-car-sim)

---

#### $\text{Project}_2$: CAD Analyzer

**Objective:** Analyze STL meshes and estimate manufacturing parameters.

**Computation:**

$$
\begin{aligned}
M_{total} &= M_{shell} + M_{infill} \\
M_{shell} &= \rho \cdot A_{surface} \cdot t_{wall} \cdot n_{walls} \\
M_{infill} &= \rho \cdot (V_{total} - V_{shell}) \cdot \eta_{infill}
\end{aligned}
$$

**Repository:** [`cad-analyzer`](https://github.com/Cyber717/cad-analyzer)

---

#### $\text{Project}_3$: File Organizer

**Objective:** Automate file categorization based on extension mapping.

**Function:**

$$
\text{category}(f) = \begin{cases}
\mathcal{D} & \text{if } \text{ext}(f) \in \{.pdf, .docx, .txt\} \\
\mathcal{M} & \text{if } \text{ext}(f) \in \{.jpg, .png, .mp4\} \\
\mathcal{C} & \text{if } \text{ext}(f) \in \{.py, .js, .cpp\} \\
\mathcal{O} & \text{otherwise}
\end{cases}
$$

**Repository:** [`file-organizer`](https://github.com/Cyber717/file-organizer)

---

## Contact

$$
\begin{aligned}
\text{Email} &\in \mathbb{E} \\
\text{LinkedIn} &\in \mathbb{L} \\
\text{GitHub} &\in \mathbb{G}
\end{aligned}
$$

where $\mathbb{E} = \{\text{your.email@example.com}\}$, $\mathbb{L} = \{\text{linkedin.com/in/yourprofile}\}$, $\mathbb{G} = \{\text{github.com/Cyber717}\}$.

---

<div align="center">

*Currently seeking: $\text{position} \in \{\text{Robotics}, \text{Embedded Systems}, \text{Software Engineering}\}$*

</div>
