# Relational Emergence Theory (RET) - Minimal Reproducible Simulation

This repository contains the **minimal reproducible example** for the preprint  
**Relational Emergence Theory** by Hiroki Bone (March 2026).

- 128-node Φ-weighted 3-regular graph proxy  
- Laplacian eigenvalue mass proxies  
- Directional entanglement-entropy gradient (arrow of time)  

Runs in <10 seconds on any laptop. Exactly reproduces the lepton ratios from the paper.

**Full high-precision results** (Tables 1–4) come from private 2048-node ensembles (available upon request).

## Quick Start
```bash
git clone https://github.com/hirokibone/Relational-Emergence-Theory.git
cd Relational-Emergence-Theory
pip install -r requirements.txt
python ret_minimal.py
