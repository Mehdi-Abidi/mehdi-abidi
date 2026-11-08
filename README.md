<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,100:2563eb&height=170&section=header&text=Mehdi%20Abidi&fontColor=ffffff&fontSize=52&fontAlignY=36&desc=AI%20Security%20Research%20Lead&descSize=18&descAlignY=58" alt="Mehdi Abidi" />

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&pause=1200&color=3B82F6&center=true&vCenter=true&width=620&lines=Guardrails+for+LLM+agents;Prompt+injection+defence+and+secure+tool+use;Agentic+AI%2C+RAG+and+applied+ML;BS+CS+at+FAST+NUCES%2C+four+time+gold+medalist" alt="Typing intro" />
</p>

<p align="center">
  <a href="https://mehdi-abidi.github.io/My_Portfolio/"><img src="https://img.shields.io/badge/Portfolio-2563EB?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio" /></a>
  <a href="https://www.linkedin.com/in/mehdiiabidii/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:mehdiali78666@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://leetcode.com/u/Mehdi_Abidi/"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode" /></a>
  <a href="https://mehdi-abidi.github.io/My_Portfolio/Mehdi_Abidi_CV.pdf"><img src="https://img.shields.io/badge/CV-111827?style=for-the-badge&logo=readdotcv&logoColor=white" alt="CV" /></a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=Mehdi-Abidi&label=Profile%20views&color=2563eb&style=flat-square" alt="Profile views" />
  <img src="https://img.shields.io/github/followers/Mehdi-Abidi?label=Followers&style=flat-square&color=2563eb" alt="Followers" />
  <img src="https://img.shields.io/github/stars/Mehdi-Abidi?label=Stars&style=flat-square&color=2563eb" alt="Stars" />
</p>

## About me

I'm Mehdi, a CS graduate from FAST NUCES Karachi working on AI security. Most of my time goes into runtime guardrails for LLM agents. That means stopping prompt injection, keeping tool calls inside policy and making sure every model request can be traced back to whoever sent it. Lately I've also been looking at attacks that hide in places a text filter never sees, like code-mixed prompts and words written inside images.

I finished my degree in eight semesters with a 3.85 CGPA, four gold medals and four spots on the Rector's list.

- **Working on:** guardrails, policy engines and LLM routing for production agents
- **Researching:** multilingual jailbreak detection, typographic attacks on vision-language models and AI coding assistant governance
- **Leading:** IEEE FAST NUCES student branch as President (2025 to 2026)
- **Teaching:** TA for Computer Networks, Theory of Automata, Discrete Structures and COAL
- **Open to:** research collaborations in LLM security and AI safety

## Featured projects

| Project | What it does | Built with |
|---|---|---|
| **LangCode 2027 Task 2** | Flags unsafe prompts written in code-mixed and transliterated text across 10 scripts, for the NAACL 2027 LangCode shared task. A logistic probe on the frozen hidden states of Qwen3-8B lifts the Safety Score from 44.55 (zero-shot) to 79.03, with no fine-tuning. | Qwen3-8B, PyTorch, Transformers, scikit-learn, Kaggle |
| **PixelGuard** | A controlled study of text written inside images. It asks whether blur, JPEG and OCR inpainting protect vision-language models against false labels as well as they do against injected commands, and what those defences cost. | Qwen3-VL, SmolVLM, OpenCV, COCO, TextVQA |
| **SecureSphere-LLM** | Security middleware between VS Code and AI coding assistants. It catches prompt injection, jailbreaks and leaked secrets, redacts PII and logs every request. Final year project, nominated for Best FYP. | Node.js, NeMo Guardrails, Presidio, FastAPI, React |
| [**JComit**](https://github.com/Mehdi-Abidi/JComit) | Private finance agent for the Nebius x NVIDIA hackathon. It redacts your statements locally and runs Nemotron inside a sandbox that can reach nothing else. | Python, NVIDIA Nemotron, OpenShell, Docker |
| [**Hybrid Job Recommender**](https://github.com/Mehdi-Abidi/Hybrid_Job_Recommendation_System) | Two tower retrieval, LambdaMART ranking, then an LLM that reorders the shortlist and explains each match. | PyTorch, FAISS, XGBoost, Llama 3.1, FastAPI, Next.js |
| [**PathoChat 2.0**](https://github.com/Mehdi-Abidi/Pathochat) | Pathology assistant that answers only from its textbooks and says "I don't know" otherwise. Later rebuilt as an n8n agent. | LangChain, Mistral-7B, FAISS, n8n, Pinecone |
| [**Fingerprint Matcher**](https://github.com/Mehdi-Abidi/Fingerprint-Matcher) | Identifies a person from a phone photo of their thumb, with a Kotlin [Android app](https://github.com/Mehdi-Abidi/thumb-recognizer). | U²-Net, OpenCV SIFT, Flask, PostgreSQL, Kotlin |
| [**AQI Predictor**](https://github.com/Mehdi-Abidi/Weather_AQI_Predictor) | Forecasts Karachi's air quality 72 hours ahead, with hourly features and daily retraining on Actions. | scikit-learn, Hopsworks, GitHub Actions, SHAP |
| [**BotTax**](https://github.com/Mehdi-Abidi/Bottax) and [**US TaxPatriot**](https://github.com/Mehdi-Abidi/UsTaxPatriot) | Voice enabled GPT-4 tax assistants that cite the document and page behind each answer. | GPT-4, LangChain, Pinecone, Streamlit |

## Research in progress

- **Script-invariant intent probing:** our LangCode 2027 Task 2 entry on multilingual adversarial prompt detection. A probe on layer 24 of a frozen Qwen3-8B reaches 79.03 on the dev set. Paper due February 2027.
- **Typographic context vs instruction:** do cheap image defences protect VLMs against both? It covers 200 COCO images, three open VLMs, six defences and an attacker who knows the defence. Draft due 28 November 2026.
- **SecureSphere-LLM:** an identity aware interception proxy with programmable guardrails for AI coding assistants. It blocks 31 of 31 attack prompts at a 66 ms median. Targeting the NAACL 2027 LangCode workshop.
- **NexusHire:** a candidate side decision support layer over a five stage job recommendation cascade covering 123K postings. Targeting ACM RecSys 2027.

## Honours

- Four time gold medalist at FAST NUCES, Rector's list four times, Dean's list three times
- Top 5 teams at the AgentX Hackathon (Astera Software, California)
- Nebius x NVIDIA Global AI Hackathon 2026 entry with JComit
- Special honour in the International Computer Science Competition 2026 qualifier
- Perfect 50 out of 50 on the Data Structures and Algorithms final
- Stanford Supervised Machine Learning (99.66%) and DeepLearning.AI CNNs (98.87%)

## Tech stack

**AI and LLM security**

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langgraph&logoColor=white)
![NeMo Guardrails](https://img.shields.io/badge/NeMo_Guardrails-76B900?style=for-the-badge&logo=nvidia&logoColor=white)
![Presidio](https://img.shields.io/badge/Presidio-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![Anthropic](https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=anthropic&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![MCP](https://img.shields.io/badge/MCP-111827?style=for-the-badge&logo=modelcontextprotocol&logoColor=white)
![Temporal](https://img.shields.io/badge/Temporal-000000?style=for-the-badge&logo=temporal&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white)
![Pinecone](https://img.shields.io/badge/Pinecone-000000?style=for-the-badge&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=for-the-badge&logo=meta&logoColor=white)
![pgvector](https://img.shields.io/badge/pgvector-336791?style=for-the-badge&logo=postgresql&logoColor=white)

**Machine learning**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-189FDD?style=for-the-badge&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)

**Languages, web, data and cloud**

<p>
  <img src="https://skillicons.dev/icons?i=py,cpp,c,ts,js,kotlin,rust,bash,fastapi,django,flask,nodejs,nextjs,react,tailwind,postgres,mongodb,mysql,sqlite,docker,azure,githubactions,jenkins,linux,git,vscode&perline=13&theme=dark" alt="Languages and tools" />
</p>

## GitHub stats

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Mehdi-Abidi&theme=tokyonight" alt="Profile details" />
</p>

<p align="center">
  <img height="165" src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=Mehdi-Abidi&theme=tokyonight" alt="Stats" />
  <img height="165" src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=Mehdi-Abidi&theme=tokyonight&utcOffset=5" alt="Productive time" />
</p>

<p align="center">
  <img height="165" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=Mehdi-Abidi&theme=tokyonight" alt="Repos per language" />
  <img height="165" src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=Mehdi-Abidi&theme=tokyonight" alt="Most commit language" />
</p>

<p align="center">
  <a href="https://git.io/streak-stats"><img src="https://streak-stats.demolab.com?user=Mehdi-Abidi&theme=tokyonight&hide_border=true" alt="GitHub streak" /></a>
</p>

<p align="center">
  <img src="https://github-trophies.vercel.app/?username=Mehdi-Abidi&theme=tokyonight&no-frame=true&no-bg=true&column=7&margin-w=8" alt="Trophies" />
</p>

## LeetCode

<p align="center">
  <a href="https://leetcode.com/u/Mehdi_Abidi/"><img src="https://leetcard.jacoblin.cool/Mehdi_Abidi?theme=dark&font=Fira%20Code&ext=heatmap" alt="LeetCode stats" /></a>
</p>

## Contribution snake

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Mehdi-Abidi/mehdi-abidi/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Mehdi-Abidi/mehdi-abidi/output/github-snake.svg" />
  <img alt="Contribution snake" src="https://raw.githubusercontent.com/Mehdi-Abidi/mehdi-abidi/output/github-snake.svg" />
</picture>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:2563eb,100:0f172a&height=110&section=footer" alt="" />
