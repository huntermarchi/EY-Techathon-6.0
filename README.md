# 🧠 EY Techathon 6.0 — Agentic AI Solution for Pharmaceutical Innovation  
### Automating drug repurposing evaluation using a multi-agent AI pipeline  
---

This repository contains the **complete Round 2 implementation** for EY Techathon 6.0 by **Team Tech-Guys**.

Our solution accelerates drug repurposing research using a **multi-agent AI architecture**, providing evidence synthesis, ranking, scoring, and explainability — all in a single pipeline.

---

# 👥 Team — Tech-Guys
- **Shani Pratap Singh**  
- **Harsh Gupta**  
- **Shaik Khadeer**  
- **Lakshya Sachan**  
- **Aayushman Jodan**

---

# 🚀 What This Repository Includes

### ✔ Full Agentic AI Pipeline  
### ✔ Multi-Agent Architecture  
### ✔ Weighted Scoring System  
### ✔ Semantic Similarity Engine (SBERT MiniLM)  
### ✔ Ranking Tables  
### ✔ Component Contribution Charts  
### ✔ Dashboard Wireframes  
### ✔ Flowcharts & System Diagrams  
### ✔ PDF Report Generator  
### ✔ Complete Google Colab Notebook  
### ✔ LaTeX Beamer Presentation for Round 2  

---

# 🧩 Multi-Agent Architecture
User Query
│
▼
Master Agent ───────────────────────────────────────────┐
│ │
├── Literature Agent (Semantic biomedical insights)│
├── Patent Agent (FTO & IP analysis) │
├── Market Agent (Opportunity & feasibility) │
└── Internal Evidence Agent (Org-level data) │
│
▼ │
Weighted Scoring Model │
▼ │

---

# 📊 Scoring Model

| Component | Weight | Description |
|----------|--------|-------------|
| Literature Similarity | **40%** | Semantic evidence relevance |
| Patent Risk | **15%** | Freedom-to-operate & IP barriers |
| Market Opportunity | **25%** | Commercial viability |
| Internal Evidence | **20%** | R&D alignment & feasibility |

---

# 🧪 Example Final Output (Actual System Output)

```json
{
 "query": "Repurposing approved molecule for oncology and immunology applications",
 "summary": "Literature supports repurposing potential. Patent landscape suggests moderate FTO. Market demand indicates strong commercial relevance. Internal R&D supports feasibility. System Confidence: 73.22%",
 "accuracy": 73.22,
 "similarities": [0.8279, 0.6243, 0.7544, 0.7223],
 "outputs": [
  "Literature insights...",
  "Patent insights...",
  "Market insights...",
  "Internal R&D insights..."
 ]
}



