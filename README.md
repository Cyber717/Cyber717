# Mark Vision

**Mechatronics Engineer** · Control Systems · Robotics

---

### 🧠 System Architecture

```mermaid
graph TD
    User([Mark Vision]) -->|Specializes In| Control[Control Systems]
    User -->|Specializes In| Soft[Software Engineering]
    User -->|Specializes In| Auto[Automation]

    Control -->|Tools| A[Python] & B[MATLAB] & C[C++]
    Soft -->|Tools| D[Git] & E[OpenCV] & F[Linux]
    Auto -->|Tools| G[SolidWorks] & H[Fusion 360]

    style User fill:#58a6ff,stroke:#58a6ff,color:#fff
    style Control fill:#f0f6fc,stroke:#58a6ff,stroke-width:2px
    style Soft fill:#f0f6fc,stroke:#58a6ff,stroke-width:2px
    style Auto fill:#f0f6fc,stroke:#58a6ff,stroke-width:2px
```

---

### 🛠️ Deployed Projects

#### 1. Autonomous Vehicle Simulation
*Lane-following implementation using computer vision and control theory.*

```mermaid
flowchart LR
    Cam[Camera Input] -->|OpenCV| Vision[Lane Detection]
    Vision -->|Path Error| Controller{Controller}
    
    Controller -- Heading Error --> Stanley[Stanley Control]
    Controller -- Look-Ahead --> Pure[Pure Pursuit]
    
    Stanley --> Steer[Steering Output]
    Pure --> Steer

    style Cam fill:#1f2328,stroke:#58a6ff,color:#fff
    style Steer fill:#1f2328,stroke:#58a6ff,color:#fff
    style Controller fill:#58a6ff,stroke:#58a6ff,color:#fff
```
→ **[View Repository](https://github.com/Cyber717/autonomous-car-sim)**

<br>

#### 2. CAD Analyzer
*Desktop utility for manufacturing estimation.*

```mermaid
sequenceDiagram
    participant User
    participant App
    participant Engine as Mesh Engine
    
    User->>App: Drag & Drop STL
    App->>Engine: Calculate Volume & Surface
    Engine->>Engine: Shell vs Infill Mass
    Engine-->>App: Return Estimates
    App-->>User: Display Time & Cost

```
→ **[View Repository](https://github.com/Cyber717/cad-analyzer)**

---

### ⚡ Quick Status

| Attribute | Status |
| :--- | :--- |
| **Education** | Final Year Mechatronics Engineering |
| **Focus** | Bridging Hardware & Software |
| **Location** | Available for Remote/Relocation |
| **Contact** | [your.email@example.com](mailto:your.email@example.com) |

