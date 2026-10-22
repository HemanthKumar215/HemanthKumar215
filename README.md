<div align="center">

# Hi, I'm Hemanth Kumar 👋

<a href="https://hemanthkumar215.github.io">
  <img src="https://readme-typing-svg.demolab.com?font=IBM+Plex+Mono&weight=500&size=20&duration=3000&pause=900&color=6C78FF&center=true&vCenter=true&width=560&lines=AI%2FML+%26+Software+Engineering;Computer+vision+%C2%B7+LLM+apps+%C2%B7+Full+stack;Final-year+CSE+%40+SRMIST%2C+Chennai" alt="AI/ML & Software Engineering · Computer vision · LLM apps · Full stack" />
</a>

<p>
  <a href="https://hemanthkumar215.github.io"><img src="https://img.shields.io/badge/Portfolio-View-2F3BD9?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio"></a>
  <a href="mailto:15hemanthkumar215@gmail.com"><img src="https://img.shields.io/badge/Email-Contact-13151B?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
</p>

</div>

I build AI-powered software end to end: training or integrating the model, writing the API around it, and building the app that uses it.

- 🎓 B.Tech Computer Science and Engineering, SRM Institute of Science and Technology (2023–2027) · CGPA 9.10/10
- 💼 Interned at **LambdaDigital** (AI Development) and **IIT Madras** (Research)
- 🔭 Looking for **AI/ML and software engineering** roles and internships

---

## 🚀 Featured projects

<table>
<tr>
<td width="50%" valign="top">

### [RetinaFlow](https://github.com/HemanthKumar215/Retina-Flow)
Fine-tuned **Vision Transformer (ViT-B/16)** that grades diabetic retinopathy into five levels and explains each prediction with a **Grad-CAM** heatmap.

`PyTorch` `timm` `OpenCV` `FastAPI` `React`

<details>
<summary><b>How it works</b></summary>

1. Image uploaded to `POST /predict` (FastAPI)
2. Border crop + CLAHE contrast enhancement, resize to 224
3. ViT-B/16 with a 5-class head → grade + confidence
4. Grad-CAM adapted to transformer patch tokens (196 → 14×14 map)
5. JSON response drives a React result view, plus an AR heatmap view

Trained with Adam (lr 2e-5), 20 epochs, flip/rotation augmentation; quadratic weighted kappa logged per epoch. Technology demo, not a clinical tool.
</details>

</td>
<td width="50%" valign="top">

<img src="https://raw.githubusercontent.com/HemanthKumar215/Retina-Flow/main/final_project_results/Visual_Proof_Grade_2.png" alt="RetinaFlow: original fundus scan and Grad-CAM map" width="100%">

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [Smart Study Planner](https://github.com/HemanthKumar215/session-planner)
Flask app that reads past exam papers, scores topics with an **LLM**, and generates a day-by-day study schedule. Built during my LambdaDigital internship.

`Python` `Flask` `Groq · Llama 3` `PyPDF2` `JavaScript`

<details>
<summary><b>How it works</b></summary>

1. Extract text from PDF/TXT papers with PyPDF2
2. Prompt 1 → curriculum topics with 1–5 relevance scores (strict JSON)
3. Aggregate and rank topic weights in Python
4. Prompt 2 → `[{day, topics[]}]` schedule
5. Keyword and rule-based fallbacks if the LLM output is unusable
</details>

</td>
<td width="50%" valign="top">

### [HR Workflow Designer](https://github.com/HemanthKumar215/hr-workflow-designer)
TypeScript graph editor for HR workflows with **DFS cycle detection**, **BFS topological execution** and a simulator behind a swappable API layer.

`TypeScript` `React 19` `React Flow` `Vite`

<details>
<summary><b>How it works</b></summary>

- Five node types modelled as a discriminated union
- Pre-flight validation: cycles (DFS) and isolated nodes
- Mock `/simulate` API returns an ordered step log
- Workflows import and export as JSON
</details>

</td>
</tr>
</table>

---

## 🛠️ Tech stack

<div align="center">

**Languages**<br>
<img src="https://skillicons.dev/icons?i=py,java,js,ts,cpp" alt="Python, Java, JavaScript, TypeScript, C++" />

**AI / ML**<br>
<img src="https://skillicons.dev/icons?i=pytorch,sklearn,opencv" alt="PyTorch, scikit-learn, OpenCV" />

**Backend &amp; web**<br>
<img src="https://skillicons.dev/icons?i=fastapi,flask,react,tailwind" alt="FastAPI, Flask, React, Tailwind CSS" />

**Data &amp; tools**<br>
<img src="https://skillicons.dev/icons?i=mysql,mongodb,git,github,vite,vercel" alt="MySQL, MongoDB, Git, GitHub, Vite, Vercel" />

</div>

---

## 📊 GitHub stats

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=HemanthKumar215&show_icons=true&hide_border=true&theme=transparent&title_color=6C78FF&icon_color=6C78FF" alt="GitHub stats" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=HemanthKumar215&layout=compact&hide_border=true&theme=transparent&title_color=6C78FF" alt="Top languages" />
</p>

<div align="center">

📫 **15hemanthkumar215@gmail.com** · 🌐 [hemanthkumar215.github.io](https://hemanthkumar215.github.io)

</div>
