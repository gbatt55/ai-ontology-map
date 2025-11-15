# ONTOLOGY PRIMER  
AI Supply Chain Ontology — Conceptual Overview

## Purpose
This ontology is a structured, multi-layer map of the modern AI industrial system.  
It identifies:
- key actors (companies, technologies, institutions),
- cross-layer dependencies,
- strategic bottlenecks,
- competition dynamics,
- leverage pathways,
- and structural constraints on AI scaling.

It is a **living system** designed for iterative updates.  
AI suggests changes; the human operator chooses what to adopt.

---

# 1. The Seven Layers (Conceptual Altitude Model)

### **Layer 1 — Physical Power & Electro-Industrial Base**
Electricity supply, transmission constraints, HVAC/cooling, datacenter siting, physical infrastructure.

### **Layer 2 — Compute Fabric (Silicon, Packaging, Systems)**
GPUs/ASICs/TPUs, foundries, HBM, packaging (CoWoS), memory, thermal bounds, servers.

### **Layer 3 — Cluster OS & Distributed Systems**
Hyperscaler infrastructure, cluster orchestration, CUDA, networking stacks, distributed training frameworks.

### **Layer 4 — Foundation Model Training**
Frontier labs, internal models, data pipelines, training runs, compute consumption, scaling laws.

### **Layer 5 — Model Serving, Routing, Inference Systems**
Inference fabrics, routing layers, agentic orchestration, model switching/ensembles.

### **Layer 6 — Applications & Domain Workflows**
Enterprise copilots, vertical apps, workflow automation, domain-specific AI tools.

### **Layer 7 — Organizational & Societal Embedding**
Regulators, governments, enterprise distribution channels, institutional adoption, geopolitical constraints.

Each layer has unique actors, bottlenecks, and failure modes.

---

# 2. Node Types
Nodes represent distinct entities or concepts.

- **company** — Corporate actors (NVIDIA, AWS, TSMC, etc.)  
- **technology** — Technical primitives (HBM, CUDA, CoWoS)  
- **platform** — Cloud or OS-like layers (Azure, GCP)  
- **infrastructure** — Physical or resource constraints (grid power, cooling)  
- **institution** — Regulators, policy actors  
- **concept** — High-level abstractions (Enterprise AI apps, etc.)  

Nodes carry:
- `id`, `name`, `layer`, `type`, `description`.

---

# 3. Edge Types
Edges express directional relationships:

### **dependency**
A → B means **A requires B** to operate or scale.

Examples:  
- OpenAI → Azure  
- NVIDIA → TSMC  
- Grid Power → AWS  

### **competition**
A ↔ B means **A and B contest the same market or capability frontier**.

Examples:  
- NVIDIA ↔ AMD  
- AWS ↔ Microsoft  
- OpenAI ↔ xAI  

### **leverage**
A → B means **A can influence, pressure, or constrain B**  
through capital, regulation, distribution, or strategic power.

Examples:  
- Microsoft → OpenAI  
- US Regulators → NVIDIA  
- Hyperscalers → Model labs (pricing + access)

---

# 4. Philosophy of Use
This ontology follows **three principles**:

### **1. Rule-Free Core**
No formal logic engine.  
The graph remains flexible, understandable, and cheap to maintain.

### **2. Slice-Based AI Review**
Each update targets a small portion of the graph:
- a single layer,  
- or a single node (ego-network),  
- or a scenario overlay.

### **3. Human-in-the-Loop Control**
AI proposes up to 5 edits.  
You review, approve, modify, or reject.  
You manually update `ontology.json`.  
This prevents drift and ensures strategic accuracy.

---

# 5. Update Workflow

### **Step 1 — Choose Review Type**
- Layer Review  
- Node (ego-network) Review  
- Scenario/Hypothetical Review  

### **Step 2 — Prime the AI**
Paste this Primer first in any new session.

### **Step 3 — Paste the Appropriate Prompt Template**
From `/prompts/`:
- `layer-review.txt`  
- `node-review.txt`  
- `scenario-review.txt`  

### **Step 4 — Paste the Slice from ontology.json**
Only nodes + edges relevant to the review.

### **Step 5 — Evaluate AI Suggestions**
Choose which to:
- accept  
- reject  
- modify  
- expand upon  

### **Step 6 — Update ontology.json Manually**
Add nodes, add edges, adjust weights, or delete edges.

### **Step 7 — Commit to GitHub**
Each commit is a recorded evolution event.

---

# 6. Design Boundaries
- Do **not** attempt a rule engine.  
- Keep edges limited to **dependency / competition / leverage**.  
- Keep layers stable (modifications are rare).  
- Avoid flooding the ontology with minor actors; prioritise leverage and bottlenecks.  
- Maintain conceptual clarity over completeness.

---

# 7. Intended Use Cases
- Track power shifts across the AI stack  
- Detect bottlenecks or fragilities (TSMC, HBM, energy)  
- Understand competitive geometry (AWS vs MSFT vs Google)  
- Map leverage relations (regulators, hyperscalers)  
- Stress-test scenarios (new entrant, export control, hardware shock)  
- Evolve your strategic worldview systematically  

---

# 8. Scope of the Ontology
This ontology maps **structure**, not:
- financials  
- corporate KPIs  
- minor feature releases  
- PR cycles  

It captures **strategic shape and evolution**, not noise.

---

End of Primer.
