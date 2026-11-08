<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=180&color=0:0F172A,100:0D9488&text=Lubabah%20Hamouch&fontColor=FFFFFF&fontSize=46&fontAlign=50&fontAlignY=38&desc=Data%20Scientist%2C%20AI%20Engineer&descAlign=50&descAlignY=62&descSize=18&animation=fadeIn" width="100%" alt="Lubabah Hamouch, Data Scientist, AI Engineer">
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=18&pause=1200&color=0D9488&center=true&vCenter=true&width=600&lines=Computer+vision;Time-series+forecasting;LLM+evaluation;Shipped%2C+not+just+trained" alt="Computer vision, time-series forecasting, LLM evaluation, shipped not just trained">
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/lubabah-hamouch/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:lubabah.hamouch0@gmail.com"><img src="https://img.shields.io/badge/lubabah.hamouch0%40gmail.com-0F172A?style=flat-square&logo=gmail&logoColor=white" alt="Email: lubabah.hamouch0@gmail.com"></a>
  <a href="https://linktr.ee/lubabah.hamouch0"><img src="https://img.shields.io/badge/Resume_%26_Links-0D9488?style=flat-square" alt="Resume and links"></a>
  <img src="https://img.shields.io/badge/London%2C_UK-0D9488?style=flat-square" alt="London, UK">
</p>

<br>

Bachelor's in Applied Computer Science (Development track), then a Master's in Data Science
and AI (MSc equivalent), graduating top of my class. I build full systems end to end: the
models, but also the APIs, CI/CD, and infrastructure that get them in front of real users.
Six projects below cover computer vision, forecasting, and LLM evaluation, all deployed and
benchmarked against a real baseline. On three of them, the hardest part wasn't training the
model; it was proving it was lying to me, then fixing it.

Open to data science, ML engineering, and AI roles, and genuinely interested in talking
about any AI or data problem, not just the ones below.

<sub>*A couple of the live demos below run on free-tier hosting and go to sleep when idle, so the first load can take 30-50 seconds to wake up. Worth a second try if it looks stuck.*</sub>

---

### Featured work

**Brain-Tumour-Detector**
3D MRI tumour segmentation (Dice 0.90) and classification (98.3% accuracy). The classifier
was secretly keying off image resolution instead of real tumour features. Caught it with
Grad-CAM, fixed it with targeted augmentation, zero accuracy lost.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Three.js](https://img.shields.io/badge/Three.js-000000?style=flat-square&logo=threedotjs&logoColor=white)

[![Live demo](https://img.shields.io/badge/Live_demo-0D9488?style=flat-square&logo=vercel&logoColor=white)](https://brain-tumour-detector-iota.vercel.app)
[![Code](https://img.shields.io/badge/Code-0F172A?style=flat-square&logo=github&logoColor=white)](https://github.com/Lubabah-Hamouch/Brain-Tumour-Detector)

**AWS-codegen-1.5b**
Fine-tuned a 1.5B code model with QLoRA, served from AWS Lambda for roughly $0 a month.
Format compliance: 5.5% to 99.4%.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![AWS Lambda](https://img.shields.io/badge/AWS_Lambda-FF9900?style=flat-square&logo=awslambda&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)

[![Live demo](https://img.shields.io/badge/Live_demo-0D9488?style=flat-square&logo=awslambda&logoColor=white)](https://d2js86b0xg0ozs.cloudfront.net)
[![Code](https://img.shields.io/badge/Code-0F172A?style=flat-square&logo=github&logoColor=white)](https://github.com/Lubabah-Hamouch/AWS-codegen-1.5b)

**Demand-Bench**
SKU-level demand forecasting across 30,490 Walmart product series. WAPE 0.755 against a
0.916 naive baseline, leak-safe rolling-origin backtesting.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![LightGBM](https://img.shields.io/badge/LightGBM-02569B?style=flat-square)
![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=flat-square&logo=duckdb&logoColor=black)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)

[![Live demo](https://img.shields.io/badge/Live_demo-0D9488?style=flat-square&logo=render&logoColor=white)](https://demand-bench.onrender.com)
[![Code](https://img.shields.io/badge/Code-0F172A?style=flat-square&logo=github&logoColor=white)](https://github.com/Lubabah-Hamouch/Demand-Bench)

**RAG-Bench**
A controlled experiment on RAG prompting strategies with claim-level judging. Retrieval
mattered more than prompting: the best strategy gained +0.39 over a no-retrieval control
(95% CI 0.17 to 0.62).

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-0D9488?style=flat-square)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)

[![Live demo](https://img.shields.io/badge/Live_demo-0D9488?style=flat-square&logo=render&logoColor=white)](https://ragbench-ui.onrender.com)
[![Code](https://img.shields.io/badge/Code-0F172A?style=flat-square&logo=github&logoColor=white)](https://github.com/Lubabah-Hamouch/RAG-Bench)

**oil-spill-detection**
Aerial oil-spill detection and segmentation. 92.8% classification accuracy, 90.1%
segmentation Dice.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)

[![Live demo](https://img.shields.io/badge/Live_demo-0D9488?style=flat-square&logo=render&logoColor=white)](https://oil-spill-detection-bdg1.onrender.com/)
[![Code](https://img.shields.io/badge/Code-0F172A?style=flat-square&logo=github&logoColor=white)](https://github.com/Lubabah-Hamouch/oil-spill-detection)

**Student-Behaviour-Detector**
YOLOv8m classroom behaviour detection on a self-filmed, hand-labelled dataset. Caught data
leakage in an earlier version: honest mAP50 dropped from an inflated 0.77 to 0.502.
Documented the fix rather than hiding it.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![YOLOv8](https://img.shields.io/badge/YOLOv8-111F68?style=flat-square)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)

[![Code](https://img.shields.io/badge/Code-0F172A?style=flat-square&logo=github&logoColor=white)](https://github.com/Lubabah-Hamouch/Student-Behaviour-Detector)

---

### Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,pytorch,fastapi,react,nextjs,postgres,docker,aws&theme=dark" alt="Python, PyTorch, FastAPI, React, Next.js, PostgreSQL, Docker, AWS">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/CI/CD-GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="CI/CD: GitHub Actions">
  <img src="https://img.shields.io/badge/Deploy-Vercel-000000?style=flat-square&logo=vercel&logoColor=white" alt="Deploy: Vercel">
  <img src="https://img.shields.io/badge/Deploy-Render-46E3B7?style=flat-square&logo=render&logoColor=white" alt="Deploy: Render">
  <img src="https://img.shields.io/badge/Deploy-AWS_Lambda-FF9900?style=flat-square&logo=awslambda&logoColor=white" alt="Deploy: AWS Lambda">
</p>

---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=100&color=0:0D9488,100:0F172A&section=footer&animation=fadeIn" width="100%" alt="">
</p>
