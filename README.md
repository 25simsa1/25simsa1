# Hey! I'm Simon

- Efficient Transformer Architectures Researcher @ In Simplicity Technologies
- Machine Learning Researcher @ Algoverse, working on learnability probes for LLM training data
- Linguistics & NLP Research Assistant @ Colby College
- Software Engineer Intern @ Parsifal Corporation
- Data Science Assistant @ Colby's McVey Center for Computational and Data Sciences
- Undergrad @ Colby College, class of 2029, Mathematics and Economics, minor in Computer Science
- Interested in post-training, training stability, LLM evaluation, local learning rules, and finance

## Workshop Papers (NeurIPS 2026, accepted):

- **Beyond Query Linearity: The Case for Nonlinear Queries**: co-author (5th of 10). Replaces the attention query projection with a parameter-matched bottleneck MLP. Accepted to the NeurIPS 2026 SLM-Agents workshop
- **Alignment Without Binding: A Credit-Depth Threshold for Cross-Modal Transfer in Local Learning**: with Anthony Yeh. Accepted to the NeurIPS 2026 DevAI and BabyVLM workshops

## Currently:

- **Training stability @ In Simplicity**: 757M-parameter GPT-style pretraining runs on H200s comparing linear and nonlinear attention queries. Traced a mid-run divergence in the linear baseline to unbounded attention-logit growth and removed it with a training-only z-loss, verified with matched-seed A/B runs
- **Learnability probes @ Algoverse**: whether a model's own internals reveal, before any sampling happens, which of its training questions will actually teach it something
- **Pragmatic competence in LLMs @ Colby**: a controlled evaluation framework that isolates conversational implicature and presupposition from lexical and syntactic surface cues, so real pragmatic inference can be told apart from surface pattern matching. No model tested so far clears the comprehension gate the design requires, which is a result in its own right
- **Bidirectional predictive coding** for cross-modal generation: scaled from 156M to 7.7B parameters to test whether local learning rules can bind vision and language, with a matched-optimizer backprop comparator that splits the headline gap into recipe, objective structure and reach ([encoder_encoder_PCN](https://github.com/25simsa1/encoder_encoder_PCN))
- **Software engineering @ Parsifal**: an MCP server that generates validated Power BI projects straight from a SQL database, over a multi-tenant, RLS-secured analytics platform spanning two warehouses
- **HPC support @ McVey**: user guides and office hours for Colby's 716-core, 15-GPU Slurm cluster

## Selected Work:

- **Pareto Multi-Attribute Negotiation**: Top 5 (5th of 125+ reviewed submissions) at [NANDAHack](https://www.media.mit.edu/posts/mit-media-lab-and-hcltech-host-nandahack-to-advance-agentic-ai-innovation/), the agentic-AI hackathon co-hosted by the MIT Media Lab and HCLTech. Merged upstream into NandaTown ([PR #30](https://github.com/projnanda/nandatown/pull/30)), standalone extraction at [nest-pareto-negotiation](https://github.com/25simsa1/nest-pareto-negotiation)
- [**1beyond_query_linearity**](https://github.com/25simsa1/1beyond_query_linearity): my fork of the reference implementation for "Beyond Linearity in Attention Projections: The Case for Nonlinear Queries" ([arXiv:2603.13381](https://arxiv.org/abs/2603.13381), ICLR 2026 GRaM workshop). The fork adds a stability and learning-rate audit of the GPT-3 Large comparison
- [**dependence-is-not-origin**](https://github.com/25simsa1/dependence-is-not-origin): audit of two attention nonlinearities on released checkpoints, with a gain waterfall of 81% training recipe, 4% scaffold, 15% nonlinearity. Dependence is not origin
- [**colby-major-guide**](https://github.com/25simsa1/colby-major-guide): all 101 Colby programs as one interactive chart, 397 requirement links, shared gateway courses and the exclusion rules that actually bite. Live at [colbymajorguide.com](https://colbymajorguide.com)
- [**throughline**](https://github.com/25simsa1/throughline): reads books, articles and papers, surfaces cross-source connections for a chapter thesis, then drafts prose from the ones you keep. Every quote is verified verbatim, anything unverifiable is flagged
- [**benefit-finder**](https://github.com/25simsa1/benefit-finder): screens a US household for public benefits, assistance programs and tax credits. Static rules engine, nothing stored

## Tech Stack:

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

**ML / Frameworks**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)

**Tools / Infra**

![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Slurm](https://img.shields.io/badge/Slurm-2E5C8A?style=for-the-badge)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white)
![Ruff](https://img.shields.io/badge/Ruff-D7FF64?style=for-the-badge&logo=ruff&logoColor=black)
![Apache Parquet](https://img.shields.io/badge/Apache_Parquet-50ABF1?style=for-the-badge&logo=apacheparquet&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white)

## GitHub Stats

<p align="center">
  <img src="https://streak-stats.demolab.com?user=25simsa1&hide_border=true&background=0D1117&stroke=A371F7&ring=A371F7&fire=FF7B29&currStreakLabel=A371F7&sideNums=A371F7&currStreakNum=C9D1D9&sideLabels=C9D1D9&dates=8B949E&border_radius=8" alt="GitHub streak stats" />
</p>

## Contact Me

- 📧 Email: [simonlapsang@gmail.com](mailto:simonlapsang@gmail.com)
- 💼 LinkedIn: [in/simonsang](https://linkedin.com/in/simonsang)
- ♟️ Chess.com: [simonschess06](https://www.chess.com/member/simonschess06)
