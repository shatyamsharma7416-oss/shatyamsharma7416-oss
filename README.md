<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D0D0D,100:3A2A00&height=190&section=header&text=agent://satyam-sharma&fontSize=32&fontColor=FFB000&fontAlignY=38&desc=boot%20sequence%20initiated&descAlignY=55&descSize=16&descColor=E8DCC8&animation=fadeIn" alt="header" width="100%" />
</p>

### `$ whoami`

> BCA (New), Semester IV — self-directed track in **Data Science & AI Engineering**.
> No formal role yet; the training data is roadmaps, papers, and shipped projects instead of a job title.
> Core competency so far: Python, statistics, and classical ML. Current focus: making models *act*, not just predict.

### `$ ps aux | grep agent`

**PID 001 — `rag_pipeline`**
Document ingestion → chunking → embeddings → vector retrieval → grounded generation. The part where the model stops guessing and starts citing.

**PID 002 — `code_interpreter_agent`**
A sandboxed Python execution tool the agent can call mid-reasoning — so it can compute, debug, and self-correct instead of hallucinating an answer.

**PID 003 — `agent_roadmap` (background, 50-day)**
Six phases, 24 projects. Currently in the phases covering guardrails, observability/tracing, MCP integration, and async parallel execution.

### `$ git log --oneline --graph project_02`

```
* recommender-system   Amazon Electronics 5-core dataset
|\
| * collaborative-filtering   ALS / SVD (Surprise, implicit) → Precision@10, NDCG@10 → MLflow
| * two-tower-neural          64-dim embeddings, BPR loss, FAISS retrieval
| * hybrid-scoring            + TF-IDF blend for cold-start coverage
|/
* baseline established        lightweight CF → strong portfolio narrative
```

### `$ stat ~/skills`

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,pytorch,tensorflow,sklearn,docker,git,github,vscode,linux,postgres&theme=dark" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/PANDAS-000000?style=for-the-badge&logo=pandas&logoColor=FFB000" />
  <img src="https://img.shields.io/badge/NUMPY-000000?style=for-the-badge&logo=numpy&logoColor=FFB000" />
  <img src="https://img.shields.io/badge/LANGCHAIN-000000?style=for-the-badge&logo=langchain&logoColor=FFB000" />
  <img src="https://img.shields.io/badge/FAISS-000000?style=for-the-badge&logoColor=FFB000" />
  <img src="https://img.shields.io/badge/MLFLOW-000000?style=for-the-badge&logo=mlflow&logoColor=FFB000" />
  <img src="https://img.shields.io/badge/HUGGING%20FACE-000000?style=for-the-badge&logo=huggingface&logoColor=FFB000" />
</p>

### `$ ./contribution_snake.sh`

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/shatyamsharma7416-oss/shatyamsharma7416-oss/output/github-snake-dark.svg" />
    <img alt="contribution snake" src="https://raw.githubusercontent.com/shatyamsharma7416-oss/shatyamsharma7416-oss/output/github-snake.svg" width="100%" />
  </picture>
</p>

> ⚙️ This one needs a one-time setup — see **"Activating the contribution snake"** below. Until the Action runs once, this image will show broken.

### `$ curl -s stats.local/satyam | jq`

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=shatyamsharma7416-oss&show_icons=true&hide_border=true&bg_color=0D0D0D&title_color=FFB000&icon_color=FFB000&text_color=E8DCC8&count_private=true" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=shatyamsharma7416-oss&layout=compact&hide_border=true&bg_color=0D0D0D&title_color=FFB000&text_color=E8DCC8" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=shatyamsharma7416-oss&hide_border=true&background=0D0D0D&stroke=FFB000&ring=FFB000&fire=FFB000&currStreakLabel=FFB000&sideLabels=E8DCC8&currStreakNum=E8DCC8&sideNums=E8DCC8&dates=8A8266" />
</p>

### `$ cat featured_projects.log`

| process | description | stack |
|---|---|---|
| `agentic-ai-toolkit` | RAG + Python code-interpreter agent, tool-calling, guardrails | LangChain · FAISS · Claude/OpenAI API |
| `product-recommender` | CF baseline → two-tower neural retrieval → hybrid scoring | Surprise · PyTorch · FAISS · MLflow |
| `llm-proxy` | Self-hosted, Dockerized LLM proxy deployed on Render | Docker · Render |

*(swap in real repo links once public — `[project-name](https://github.com/shatyamsharma7416-oss/repo)`)*

### `$ cat contact.json`

```json
{
  "email":    "satyam77876@gmail.com",
  "linkedin": "linkedin.com/in/satyam-sharma-778383379",
  "kaggle":   "kaggle.com/satyamsharma47"
}
```

<p align="center">
  <a href="mailto:satyam77876@gmail.com"><img src="https://img.shields.io/badge/EMAIL-000000?style=for-the-badge&logo=gmail&logoColor=FFB000" /></a>
  <a href="https://www.linkedin.com/in/satyam-sharma-778383379/"><img src="https://img.shields.io/badge/LINKEDIN-000000?style=for-the-badge&logo=linkedin&logoColor=FFB000" /></a>
  <a href="https://www.kaggle.com/satyamsharma47"><img src="https://img.shields.io/badge/KAGGLE-000000?style=for-the-badge&logo=kaggle&logoColor=FFB000" /></a>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:3A2A00,100:0D0D0D&height=150&section=footer&text=process%20status:%20RUNNING&fontSize=20&fontColor=FFB000&fontAlignY=75&animation=fadeIn" alt="footer" width="100%" />
</p>

---

<details>
<summary><b>⚙️ Activating the contribution snake (one-time setup)</b></summary>

<br>

The snake section above reads from a branch called `output` that gets generated by a GitHub Action. To turn it on:

1. Copy the file at `.github/workflows/snake.yml` (included alongside this README) into your repo at that exact path.
2. Commit and push it to `main`.
3. Go to the **Actions** tab on your repo → you should see a workflow called *generate animated snake* → let it run once (or trigger it manually via "Run workflow").
4. It will create an `output` branch containing `github-snake.svg` and `github-snake-dark.svg`. Once that branch exists, the snake image in the README will render automatically — no further action needed, it updates itself every 12 hours.

</details>
