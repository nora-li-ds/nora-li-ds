# Hi, I’m Nora (Xinnuo) Li (｡•̀ᴗ-)✧

I work at the intersection of **Data Science**, **Financial Crime**, and **Forensic Analytics**.  
Right now, I’m focused on a practical gap in crypto compliance: moving beyond black-box **risk scores** toward **auditable, regulator-friendly signals** — i.e., *why a pattern matters, what would change under a counterfactual scenario, and how to document decisions in regulated environments (MiCA).*  

🎓 **MSc Crime Science with Data Science** @ UCL (2025–2026)  
🎓 **MSc Environmental Data Science & Machine Learning** @ Imperial College London  
🎓 **BSc Statistics** @ Lancaster University  

---

## 🛡️ Current Research Focus (2026)

- **Crypto / Stablecoin Compliance (MiCA-aligned):** designing monitoring logic that can support **explanation + audit trails**, not just alerts.  
- **Causal ML for Forensics:** using **causal stress testing**, robustness checks, and counterfactual reasoning to produce reviewable signals.  
- **Graph + Network Analytics:** applying graph methods to transaction networks and typologies, while being careful about attribution and label scarcity.

---

## ⭐ Flagship Project (MSc Dissertation Direction)

### **Causal Stress Testing for Stablecoin Monitoring (Ethereum)**
**Goal:** build a *white-box* metric that helps distinguish **market-driven urgency** (e.g., arbitrage/hedging) from behaviour **consistent with non-market constraints** (e.g., enforcement-driven urgency), without making definitive claims about illegality.

**Core idea:** within **stable market regimes**, transaction costs can spike (gas fees).  
Profit-driven actors typically slow down when costs rise; some entities remain unusually **cost-rigid**.  
I measure **cost sensitivity / rigidity (elasticity)** as an interpretable signal designed to support **escalation + audit narratives** and complement black-box graph models.

**Planned pipeline (work in progress):**
- Dune SQL extraction for USDC/USDT redemption-related on-chain signals
- regime filtering (reduce confounding from market stress)
- entity aggregation / clustering + sensitivity analysis
- elasticity/rigidity estimation + robustness tests
- positive–unlabeled (PU) evaluation using sanctions/heist positives (without treating others as “clean”)

---

## 🧪 Research Prototypes

### **[Elliptic AML Analysis](https://github.com/nora-li-ds/elliptic-aml-analysis)**
- *Goal:* classify illicit Bitcoin transactions on the Elliptic dataset and understand error patterns.
- *Status:* baseline ML (LogReg, RF, XGBoost) completed.
- *Next:* GraphSAGE baseline + analysis of false positives + interpretable signals for investigation workflows.

### **Strategic Risk & Intervention Modelling (planned)**
- *Goal:* evaluate intervention policies (e.g., friction, throttling, freezing) using scenario-based simulation.
- *Approach:* link risk signals to dynamic models to study attacker adaptation and network resilience.

---

## 🎓 Academic Journey (selected)

- **BSc Statistics (Lancaster):** probability, inference, statistical modelling.
- **MSc EDSML (Imperial):** deep learning + data engineering; experience with high-dimensional data and model evaluation.
- **MSc Crime Science (UCL):** cybercrime, crime prevention, research design, and translating quantitative methods into real security / compliance problems.

---

## 🗂️ Technical Training (Coursework & Team Projects)

- **[Deep Learning Frameworks](https://github.com/nora-li-ds/dl-assessment-1-edsml-xl522)**: CNNs, VAEs, generative modelling (PyTorch).
- **[Flood Risk Prediction Tool](https://github.com/nora-li-ds/ads-deluge-Avon)**: group project; packaged ML pipeline (XGBoost/KNN) + testing + geospatial visualisation.
- **[Wildfire Prediction](https://github.com/nora-li-ds/ads-wildfire-thomas)**: sequence modelling (RNN) with satellite-driven signals.
- **[Advanced Programming – C++17](https://github.com/nora-li-ds/advanced-programming-group-huffman)**: modular algorithms + unit testing (3D image processing).

---

## 🚀 Toolkit
Python • SQL • R • Git • Jupyter  
Interests: **FinCrime analytics**, **blockchain forensics**, **causal reasoning**, **model risk / explainability**

---

### 📫 Contact
- **Location:** London, UK  
- **GitHub:** [nora-li-ds](https://github.com/nora-li-ds)  
- **Certification:** ACAMS candidate (planned 2026)  
