<h1 align="center">Hi, I'm Jayanta Roy 👋</h1>

<p align="center">
  <b>Aspiring AI Engineer</b> · Final-year CSE @ BRAC University · Dhaka, Bangladesh<br/>
  I build retrieval-augmented LLM systems and computer vision pipelines, and I like measuring whether they actually work.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/jayanta-roy-b80357407"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:jroyakash4@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  <img src="https://img.shields.io/badge/Open%20to-AI%2FML%20internships%20%26%20new--grad%20roles-2ea44f?style=for-the-badge" alt="Open to AI/ML roles"/>
</p>

---

### 🧑‍💻 About me

- 🎓 B.Sc. in Computer Science & Engineering, **BRAC University**, graduating **January 2027**
- 🔭 Currently building a **bilingual legal RAG assistant** and **CineScope**, a computer-vision "X-Ray" engine for films
- 🧠 Thesis: **healthy-reference-guided brain MRI classification** (Healthy / Alzheimer's / Parkinson's / MS) with ConvNeXt + Swin, prototype memory and a KAN head
- 📜 DataCamp **AI Engineer for Developers** (Associate) · DataCamp **Data Analyst** (Associate)


---

### 🚀 Featured projects

<table>
<tr>
<td width="50%" valign="top">

#### ⚖️ [bd-legal-rag](https://github.com/roy032/bd-legal-rag)
Bilingual (Bangla + English) question answering over the statutes of Bangladesh. Every answer cites its section, and the system refuses when the law doesn't answer the question.

- Structure-aware ingestion: Act → Chapter → Section, cross-act references
- Hybrid retrieval: **bge-m3** dense + Bangla-aware **BM25**, RRF fusion, cross-encoder rerank
- Guardrails: citation and verbatim-quote checks, abstention, prompt-injection handling
- Agent mode with tool calls (`search`, `get_section`, `follow_refs`)
- Eval kit: graded nDCG, failure taxonomy, ablations · **200+ offline tests**
- Streaming API + UI · Docker · runs on OpenAI, Anthropic or local **Ollama**

`Python` `RAG` `LLMs` `Qdrant` `Docker` · 🚧 *active*

</td>
<td width="50%" valign="top">

#### 🎬 [CineScope](https://github.com/roy032/cinescope)
An X-Ray engine for films: shot cuts, framing, character timelines, scene search and 3D fly-throughs. It's a 26-week roadmap through computer vision. For each phase I **implement the idea from scratch first, then benchmark it against the production library**.

- Classical CV: convolution, optical flow, RANSAC homographies, shot-cut detection
- Autograd engine + ResNet-18 from scratch, matched to `torchvision` to 1e-10
- CenterNet face detection with COCO / WIDER FACE evaluation re-implemented
- Next: tracking, segmentation, SfM / Gaussian splatting, CLIP scene search

`Python` `PyTorch` `OpenCV` `NumPy` · 🚧 *phase 2 of 9*

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 🧠 Brain MRI Classification (undergraduate thesis)
Four-class MRI classifier (HC / AD / PD / MS). ImageNet-pretrained ConvNeXt-Tiny and Swin-Tiny are adapted to MRI with masked-autoencoder pre-training. A memory of 8 learnable "healthy" prototypes is retrieved via cross-attention, and a Kolmogorov–Arnold Network head makes the prediction.

`PyTorch` `timm` `ViT` `Self-supervised` · 🔬 *in progress*

</td>
<td width="50%" valign="top">

#### 🎓 [academic-success-prediction](https://github.com/roy032/academic-success-prediction)
End-to-end ML pipeline that flags students at risk of poor academic outcomes. It covers EDA, imputation and mutual-information feature selection, and compares Logistic Regression, Naive Bayes and an MLP. KMeans + PCA handle the unsupervised analysis.

`scikit-learn` `pandas` `Jupyter`

</td>
</tr>
</table>

<details>
<summary><b>More projects</b></summary>
<br/>

| Project | What it is | Stack |
|---|---|---|
| [Travelo](https://github.com/roy032/Travelo) | Full-stack group-travel planner: collaborative trips, budgeting, real-time updates, JWT auth | React · Vite · Node/Express · MongoDB · Socket.IO |
| [penalty-shootout-opengl](https://github.com/roy032/penalty-shootout-opengl) | 3D penalty-shootout game with a goalkeeper AI that predicts shot direction | Python · PyOpenGL |
| [network-design-vlsm](https://github.com/roy032/network-design-vlsm) | Department-based enterprise network design with VLSM subnet planning and a subnet calculator | Networking · Python |

</details>

---

### 🛠️ Tech stack

**Languages**<br/>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/> <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white"/> <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black"/> <img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white"/>

**ML / Deep learning**<br/>
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white"/> <img src="https://img.shields.io/badge/timm-FFD21E?style=flat-square&logo=huggingface&logoColor=black"/> <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white"/> <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white"/> <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white"/> <img src="https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white"/>

**LLMs & retrieval**<br/>
<img src="https://img.shields.io/badge/RAG-000000?style=flat-square&logo=openai&logoColor=white"/> <img src="https://img.shields.io/badge/Sentence--Transformers-FFD21E?style=flat-square&logo=huggingface&logoColor=black"/> <img src="https://img.shields.io/badge/Qdrant-DC244C?style=flat-square&logo=qdrant&logoColor=white"/> <img src="https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white"/>

**Engineering & tools**<br/>
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/> <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white"/> <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black"/> <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white"/> <img src="https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white"/> <img src="https://img.shields.io/badge/Kaggle-20BEFF?style=flat-square&logo=kaggle&logoColor=white"/> <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB"/> <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white"/>

---


