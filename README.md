<img width="100%" src="assets/banner.svg" alt="Keshav Naram — ML engineer" />

<p align="center">
  I ship ML that works on real data, not just benchmarks. Models, agents, pipelines, cloud, evals, end to end.
</p>

<p align="center">
  <a href="https://linkedin.com/in/keshav-naram-33a834285/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:naramkeshav59@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://naramkeshav59.github.io"><img src="https://img.shields.io/badge/Portfolio-203a43?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio" /></a>
</p>

<p align="center">
  <sub>MS Applied Machine Learning, University of Maryland · B.Tech Electrical Engineering, IIT Dharwad</sub>
</p>

## Featured projects

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/Naramkeshav59/Shuttlecast"><img src="https://opengraph.githubassets.com/1/Naramkeshav59/Shuttlecast" alt="ShuttleCast" /></a>
      <p><b>ShuttleCast</b>: turns any badminton match video into per-rally coaching notes. Trained stroke models find the rallies; a ReAct agent decides which ones are worth analyzing. Runs as an async AWS service (Lambda → SQS → Fargate) with video upload.</p>
      <p>Hit detection <b>F1 0.87</b> on raw broadcast (vs 0.37 baseline) · evals lifted correct attribution <b>62% → 94%</b> · <a href="https://www.youtube.com/watch?v=1QtO1wVZCtc">▶ demo</a></p>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/Naramkeshav59/FHIRFlow"><img src="https://opengraph.githubassets.com/1/Naramkeshav59/FHIRFlow" alt="FHIRFlow" /></a>
      <p><b>FHIRFlow</b>: makes hospital lab data queryable across sources. FHIR R4 → DuckDB with data-quality rules, plus a retrieval-grounded LLM that maps local lab codes to LOINC and abstains instead of guessing.</p>
      <p><b>65%</b> exact LOINC match vs 17.5% rule baseline · MIMIC-IV lab rows LOINC-queryable from <b>0%</b></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/Naramkeshav59/finsight"><img src="https://opengraph.githubassets.com/1/Naramkeshav59/finsight" alt="FinSight" /></a>
      <p><b>FinSight</b>: a RAG system over SEC 10-K filings that answers with numbered citations, using hybrid dense + BM25 retrieval and optional cross-encoder reranking.</p>
      <p><b>9</b> chunking × retrieval strategies benchmarked; reranking <i>lowered</i> answer quality on 10-Ks · <a href="https://www.youtube.com/watch?v=IpwAQtVk1mU">▶ demo</a></p>
    </td>
    <td width="50%" valign="top">
      <p><b>Currently building:</b> a private AI medical scribe that turns doctor–patient audio into a clinical note on a single 6 GB GPU, with no audio leaving the machine.</p>
      <p><b>Writing:</b> <a href="https://naramkeshav59.github.io">OKF vs RAG, prompt injection vs jailbreaks, CUDA for ML engineers, and more</a></p>
    </td>
  </tr>
</table>

## Tech stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=py,pytorch,tensorflow,sklearn,aws,docker,kubernetes,flask,fastapi,postgres,git,linux,githubactions&perline=13" alt="Python, PyTorch, TensorFlow, scikit-learn, AWS, Docker, Kubernetes, Flask, FastAPI, PostgreSQL, Git, Linux, GitHub Actions" />
</p>
<p align="center"><sub>also: LangGraph · QLoRA · DINOv2 · Whisper · Wav2Vec 2.0 · DuckDB · FHIR · Airflow · MLflow · ChromaDB</sub></p>

## Journey

| Year | Focus | Work |
| --- | --- | --- |
| 2022 | Speech processing | Real-time voice activity detection and audio chunking ([audio_chunk_maker](https://github.com/Naramkeshav59/audio_chunk_maker)); built live transcription at an internship |
| 2023 | Speech apps | Real-time speech-to-text web app with emotion detection ([SpeechToTextApp](https://github.com/Naramkeshav59/SpeechToTextApp)) |
| 2025 | MLOps | CI/CD, Airflow orchestration, Fargate deployment ([Hotel-Booking-Demand-Predictor](https://github.com/Naramkeshav59/Hotel-Booking-Demand-Predictor)) |
| 2026 | LLM systems & healthcare data | RAG with benchmarking ([FinSight](https://github.com/Naramkeshav59/finsight)), agents and trained vision models on AWS ([ShuttleCast](https://github.com/Naramkeshav59/Shuttlecast)), clinical data interoperability ([FHIRFlow](https://github.com/Naramkeshav59/FHIRFlow)) |

<img width="100%" src="assets/footer.svg" alt="" />
