## Yahya Akhrikhar

**Computer Engineering student at the Budapest University of Technology and Economics (BME), graduating January 2027.**
I do machine learning research on ranking and recommendation, support production trading platforms for the electricity market,
and build systems projects in C++ and Python.

<p>
  <a href="https://linkedin.com/in/yahya-akhrikhar"><img src="https://img.shields.io/badge/LinkedIn-yahya--akhrikhar-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://tdk.bme.hu/conference/VIK/2026/sessions/uzleti/paper/Intelligent-Content-Recommendation-System"><img src="https://img.shields.io/badge/BME%20TDK%202026-2nd%20place-B8860B?style=flat-square" alt="BME TDK 2026, 2nd place"></a>
  <a href="https://marketwatch.yahyaakh.dev"><img src="https://img.shields.io/badge/Live%20demo-Market%20Watch-24292F?style=flat-square" alt="Market Watch live demo"></a>
</p>

<p>
  <img src="https://skillicons.dev/icons?i=py,cpp,java,linux,bash,docker,postgres,pytorch,sklearn,django,react,azure,aws,githubactions,git&perline=15" alt="Python, C++, Java, Linux, Bash, Docker, PostgreSQL, PyTorch, scikit-learn, Django, React, Azure, AWS, GitHub Actions, Git">
</p>

---

### Experience

**Undergraduate Researcher, Machine Learning for Recommender Systems** · BME, Dept. of Automation and Applied Informatics · Sep 2026 – present<br>
2nd place, BME TDK Conference 2026 · qualified for the National Student Research Conference (OTDK) 2027 ·
[paper and talk](https://tdk.bme.hu/conference/VIK/2026/sessions/uzleti/paper/Intelligent-Content-Recommendation-System) ·
[code](https://github.com/yahyaakh/intelligent-content-recommendation)
- Benchmarked 15+ ranking models for new users on MovieLens 25M. A LightGBM + XGBoost learning-to-rank ensemble won the
  pre-registered test on 814 held-out users: +0.030 NDCG@10 over the strongest hybrid (p = 2 × 10⁻⁹).
- Tested LLMs (DeepSeek, Kimi, Gemma) as rerankers and data labellers, with cost and latency measured. Now extending the
  study to Microsoft MIND news data (2.2 million impressions).

**IT Support Specialist, Electricity Trading Platforms** · Supercharge, Budapest · Jan 2024 – present
- 24/7 monitoring of the production trading platforms of two cross-border electricity interconnectors: capacity auctions,
  nomination gates and deadline-critical scheduled workflows.
- Recovering failed SFTP / SOAP / REST / ECP exchanges before gate closure, triaging AWS CloudWatch alerts, escalating
  through Jira, validating auction data, and managing user access (two-factor authentication, SSO).

**AI Coding Evaluator, Software Engineering** · Alignerr · Aug 2026 – present
- Reproducing real bugs in open-source Python repositories (a PostgreSQL LISTEN/NOTIFY limit in *procrastinate*, a
  1.1 GB / 3.25 s trace-loading problem in *viztracer*) and grading AI coding agents' fixes against written acceptance
  criteria and their execution logs.

**AI Code Evaluator & Reviewer** · Outlier · Oct 2024 – Aug 2026
- Promoted to reviewer: final quality check on model-generated Python, C++ and Java code. Red-teamed LLM safeguards and
  annotated algorithmic and mathematical reasoning data.

---

### Featured projects

**[Market Watch](https://github.com/yahyaakh/stocks-crypto-prices-project)** · C++20, Python, Django, React, Docker, Azure ·
[live](https://marketwatch.yahyaakh.dev)
- A price-time priority matching engine that rebuilds a full Nasdaq trading day from 400,391 order messages, matching the
  published 10-level book 100% after every message, at 12–14 M operations/s on one thread.
- Checked by a 200,000-operation differential test under AddressSanitizer/UBSan; CI fails if the replay match drops below 100%.
- A market dashboard with merged news feeds and evaluated headline sentiment, deployed on Azure Container Apps.

**[Intelligent Content Recommendation System](https://github.com/yahyaakh/intelligent-content-recommendation)** · Python,
LightGBM, XGBoost, PyTorch, FAISS
- Where can a large language model help a recommender system with a new user? Classical methods, a learned ranker, LLMs
  and semantic IDs compared under one protocol, with every experiment written up and every final test pre-registered.

---

### Tools and where I use them

| | Tool | Where I used it |
|:---:|---|---|
| <img src="https://skillicons.dev/icons?i=py" width="36" alt="Python"> | **Python** | **Research:** every experiment, model and statistical test · **Market Watch:** Django backend, sentiment evaluation · **Alignerr:** reproducing bugs and running test suites in open-source repositories · **Outlier:** reviewing model-generated code |
| <img src="https://skillicons.dev/icons?i=cpp" width="36" alt="C++"> | **C++** | **Market Watch:** C++20 matching engine, CMake, AddressSanitizer/UBSan · **Outlier:** reviewing model-generated C++ |
| <img src="https://skillicons.dev/icons?i=java" width="36" alt="Java"> | **Java** | **Outlier:** reviewing model-generated Java · real-time chat application with Spring Boot and WebSockets |
| <img src="https://skillicons.dev/icons?i=linux" width="36" alt="Linux"> <img src="https://skillicons.dev/icons?i=bash" width="36" alt="Bash"> | **Linux, Bash** | **Alignerr:** Linux test environments for open-source test suites · **Market Watch:** Ubuntu CI, data download scripts |
| <img src="https://skillicons.dev/icons?i=docker" width="36" alt="Docker"> | **Docker** | **Alignerr:** throwaway PostgreSQL databases and Linux test containers · **Market Watch:** production image, health-checked in CI |
| <img src="https://skillicons.dev/icons?i=postgres" width="36" alt="PostgreSQL"> | **PostgreSQL, SQL** | **Alignerr:** triggers, LISTEN/NOTIFY, identifier limits, schema migrations |
| <img src="https://skillicons.dev/icons?i=sklearn" width="36" alt="scikit-learn"> | **LightGBM, XGBoost, scikit-learn** | **Research:** the learning-to-rank ensemble that won the final test · a LightGBM news ranker on MIND |
| <img src="https://skillicons.dev/icons?i=pytorch" width="36" alt="PyTorch"> | **PyTorch** | **Research:** neural collaborative filtering, two-tower and generative semantic-ID models |
| <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pandas/pandas-original.svg" width="36" alt="pandas"> | **pandas, NumPy** | **Research:** data pipelines for 25 million ratings and 2.2 million news impressions; paired tests and bootstrap confidence intervals |
| <picture><source media="(prefers-color-scheme: dark)" srcset="https://cdn.simpleicons.org/ollama/ffffff"><img src="https://cdn.simpleicons.org/ollama" width="36" alt="LLMs"></picture> | **LLMs (DeepSeek, Kimi, Gemma)** | **Research:** labelling the film catalog, reranking, parsing typed requests, with cost and latency measured · **Alignerr, Outlier:** evaluating and red-teaming models |
| <img src="https://skillicons.dev/icons?i=django" width="36" alt="Django"> <img src="https://skillicons.dev/icons?i=react" width="36" alt="React"> | **Django, React** | **Market Watch:** market dashboard · **Research:** web app that compares the recommendation methods |
| <img src="https://skillicons.dev/icons?i=azure" width="36" alt="Azure"> | **Azure** | **Market Watch:** Azure Container Apps with a custom domain and managed TLS |
| <img src="https://skillicons.dev/icons?i=aws" width="36" alt="AWS"> | **AWS** | **Supercharge:** triaging CloudWatch alerts on production trading platforms |
| <img src="https://skillicons.dev/icons?i=githubactions" width="36" alt="GitHub Actions"> | **GitHub Actions** | **Market Watch:** CI with sanitizer tests, a replay check on real Nasdaq data and a container health check |
| <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/jira/jira-original.svg" width="36" alt="Jira"> | **Jira** | **Supercharge:** incident tickets and escalation to engineering |
| <img src="https://skillicons.dev/icons?i=git" width="36" alt="Git"> | **Git** | Every project · **Alignerr:** reading issues and pull requests in open-source repositories |
