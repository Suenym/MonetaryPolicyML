# MonetaryPolicyML  
*A curated list of research at the intersection of Machine Learning and the monetary‑policy transmission mechanism.*  

## About  
Central bankers and researchers increasingly leverage Machine Learning (ML)—from tree ensembles to deep and reinforcement learning—to model, forecast and **interpret** how monetary‑policy decisions propagate through the economy.  
This repository tracks that fast‑growing literature, highlights best practices, and welcomes contributions from the community.

---

## Table of Contents  
1. [Literature Reviews](#literature-reviews)  
2. [Forecasting & Nowcasting](#forecasting--nowcasting)  
3. [Causal Inference & Interpretation](#causal-inference--interpretation)  
4. [Policy Optimisation & Reinforcement Learning](#policy-optimisation--reinforcement-learning)  
5. [Text & Alternative Data](#text--alternative-data)  
6. [Datasets & Toolkits](#datasets--toolkits)  
7. [How to Participate](#how-to-participate)  
8. [Contributors](#contributors)

---

## Literature Reviews  
| Year | Authors | Title | Venue / DOI |
|------|---------|-------|-------------|
| 2022 | **Goulet Coulombe, K. et al.** | *Machine Learning in Macroeconomic Forecasting: When and Why Does It Work?* | Econometrics Journal — 10.1093/ectj/utad015 |
| 2021 | **Buckmann, J. & Joseph, A.** | *Opening the Black Box: Interpretable ML for Macroeconomic Forecasting* | BIS Working Paper 950 |
| 2020 | **Athey, S. & Imbens, G.** | *ML Methods for Causal Inference and Policy Evaluation* | NBER Working Paper 24963 |
| 2019 | **Blanchard, T. & Mikusheva, A.** | *Machine Learning: A Revolution in Econometrics?* | Annual Review of Economics 11 |

<details>
<summary>Show more reviews</summary>

* **Mosavi et al. (2020)** — *Comprehensive Review of Deep RL Methods and Applications in Economics* — Mathematics 8 (10):1640.
* **Charpentier et al. (2021)** — *Reinforcement Learning in Economics and Finance* — Computational Economics.
* **Tilbury (2022)** — *Reinforcement Learning for Economic Policy: A New Frontier?* — arXiv:2206.08781.
</details>

---

## Forecasting & Nowcasting  
- **DeepVAR**: _Chakraborty & Joseph (2017)_ demonstrate that a VAR implemented as a deep neural network captures nonlinear interactions between GDP, inflation and rates better than linear VARs.  
- **Random Forests / Gradient Boosting**: _Kiley (2020)_ shows that nonlinear ML models improve recession‑probability forecasts, especially around financial‑stress episodes.  
- **LSTM**: _Huber & Fischer (2023)_ apply stacked LSTMs to monthly CPI data, achieving a 15 % RMSE reduction versus SARIMA during the COVID‑19 shock.

> *Why it matters*: Accurate nowcasts feed directly into real‑time policy choices and enable better risk‑management for central banks.

---

## Causal Inference & Interpretation  
- **Double ML**: _Achernyi (2022)_ estimates heterogeneous regional effects of policy‑rate hikes across EU countries, combining LASSO with orthogonal score functions.  
- **Causal Forest**: _Tsang (2021)_ uncovers that credit‑channel strength explains up to 60 % of cross‑province variation in China’s monetary‑policy impact.  
- **SHAP & PDPs**: _Buckmann et al. (2021)_ utilise SHAP to rank drivers of inflation forecasts, linking model outputs to textbook channels (expectations, exchange‑rate, cost‑push).

---

## Policy Optimisation & Reinforcement Learning  
- **Hinterlang & Tänzer (2021)** — Deep RL learns an interest‑rate rule in a New Keynesian DSGE that closely approximates the fully optimal Ramsey policy.  
- **Chen et al. (2021)** — DRL agents embed in a money‑in‑utility model, recovering stable monetary equilibria without hand‑coded Taylor rules.  
- **Curry et al. (2022)** — Multi‑agent RL solves heterogeneous‑agent general‑equilibrium models with thousands of agents, enabling richer distributional analysis of policy.

---

## Text & Alternative Data  
- **Hansen et al. (2018)** — Topic modelling of FOMC transcripts quantifies shifts in transparency.  
- **Gorodnichenko et al. (2023)** — Audio sentiment of Fed press conferences predicts Treasury yields.  
- **Larsen et al. (2021)** — News‑based inflation‑expectation indices via BERT embeddings.

---

## Datasets & Toolkits  
| Resource | Contents |
|----------|----------|
| `fredapi / pandas-datareader` | Easy Python access to >700k FRED series. |
| `BIS Banking Statistics` | Quarterly cross‑country credit and housing indicators. |
| `ECON-BERT` | Pre‑trained language model on 1 M econ‑policy documents (open‑source). |
| `MonetaryPolicyGym` | RL environment that emulates a small‑scale DSGE for experimentation. |

---

## How to Participate  
This list is **community-curated** and will never be complete without your help!  
1. **Spot a missing paper?** – Open an issue with title *Add: Paper Title (Year)* and include a valid link/DOI.  
2. **Wrong link or metadata?** – Create an issue or PR.  
3. **Want to contribute directly?** – Fork → add entry to the relevant section (alphabetical order) → submit PR.  

> *Tip:* Each entry should cite the paper, include a working link, and add one-sentence context on why it matters for the monetary‑policy literature.

---

## Contributors  
| GitHub Handle | Added / Reviewed |
|---------------|-----------------|
| @Suenym       | Initial repo setup |

---

© 2025 MonetaryPolicyML • MIT License

