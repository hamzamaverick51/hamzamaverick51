<div align="center">
  <img src="./assets/profile-sonar.svg" width="100%" alt="Hamza Raheel — research, machine learning, and software systems" />
</div>

<p align="center">
  <a href="#research"><img src="https://img.shields.io/badge/RESEARCH-071A2B?style=for-the-badge&logo=target&logoColor=27C7A8" alt="Research" /></a>
  <a href="#engineering"><img src="https://img.shields.io/badge/ENGINEERING-071A2B?style=for-the-badge&logo=code&logoColor=3BE8FF" alt="Engineering" /></a>
  <a href="#projects"><img src="https://img.shields.io/badge/PROJECTS-071A2B?style=for-the-badge&logo=github&logoColor=3BE8FF" alt="Projects" /></a>
  <a href="https://www.linkedin.com/in/hamza-raheel-829001319/"><img src="https://img.shields.io/badge/LINKEDIN-071A2B?style=for-the-badge&logo=linkedin&logoColor=3BE8FF" alt="LinkedIn" /></a>
  <a href="mailto:hamzaprofessionalwork@gmail.com"><img src="https://img.shields.io/badge/EMAIL-071A2B?style=for-the-badge&logo=gmail&logoColor=3BE8FF" alt="Email" /></a>
</p>

<h3 align="center">ML research, reliable evaluation, and software that makes the work usable.</h3>

<p align="center">
  I am a computer science student at FAST-NUCES working across computer vision,
  NLP, multimodal data, and software engineering. I build research tools, audit
  data and measurements, and turn results into claims another person can check.
  <br/><br/>
  <strong>BS Computer Science · FAST-NUCES Lahore · Expected 2028</strong>
</p>

<p align="center">
  <kbd>ML EVALUATION</kbd> &nbsp; <kbd>COMPUTER VISION</kbd> &nbsp;
  <kbd>MULTIMODAL DATA</kbd> &nbsp; <kbd>SOFTWARE SYSTEMS</kbd>
</p>

> **Open to:** research collaborations, research-engineering internships, and
> ML systems work where evaluation and reliability matter.

<br/>

<a id="research"></a>
<p align="center"><sub>01 / RESEARCH</sub></p>

<h2 align="center">Research across language, vision, and multimodal data.</h2>

<div align="center">
  <img src="./assets/research-paths.svg" width="100%" alt="Ongoing research collaborations at UNAM and JKU Linz, and a completed underwater vision collaboration with LABUST" />
</div>

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>GIL-IIMAS · UNAM</h3>
      <strong>Research Collaborator · Aug 2026–present</strong>
      <br/><br/>
      Working with Karla Salas-Jiménez, Francisco F. López-Ponce, and Diego
      Hernández-Bustamante under Dr. Helena Gómez Adorno on an ongoing NLP
      research collaboration. My contributions include evidence review, data
      analysis, evaluation design, and reproducible research workflows.
      <br/><br/>
      <code>ONGOING · NLP RESEARCH</code>
    </td>
    <td width="50%" valign="top">
      <h3>Johannes Kepler University Linz</h3>
      <strong>Research Collaborator · Aug 2026–present</strong>
      <br/><br/>
      Collaborating with Dr. Shah Nawaz at the Institute of Computational
      Perception on Urdu-language multimodal AI research. I contribute to
      dataset quality assessment and reproducible workflows for image-and-text
      data, including tools that support collection, organization, and review.
      <br/><br/>
      <code>ONGOING · MULTIMODAL AI</code>
    </td>
  </tr>
</table>

<br/>

<p align="center"><sub>02 / COMPLETED RESEARCH CASE STUDY</sub></p>

<h2 align="center">Beneath the Benchmark: underwater vision at LABUST.</h2>

<p align="center">
  July–September 2026 · Laboratory for Underwater Systems and Technologies,
  FER, University of Zagreb · Remote collaboration
</p>

The project began with underwater object detection under a shift from controlled
imagery to outdoor recordings. The most useful result was an audit of what the
supplied data could actually measure: **2,646 exports mapped to 1,206 distinct
frames from 17 videos**, and all 17 videos appeared on both sides of the
delivered training/evaluation split. Those counts describe that export, not an
unpublished paper split.

I traced video and frame lineage, built provisional video-separated partitions,
ran controlled detector studies, developed a Python-free C++/NCNN inference
path with ARM builds, and assembled an offline review package. That package
placed **704 candidate issues across 636 frames** in a human-review queue.
The inference software passed a 1,000-frame desktop stability test; physical
Raspberry Pi and ROV performance were not measured.

Later review found unresolved image-orientation and annotation issues. The
historical model comparisons remain useful diagnostics, but they do not support
a certified final detector-accuracy claim. The public case study keeps the
audit, engineering work, and evidence limits together.

<p align="center">
  <a href="https://github.com/hamzamaverick51/Beneath-The-Benchmark"><strong>Read the public case study →</strong></a>
  &nbsp;·&nbsp;
  <a href="https://hamzamaverick51.github.io/Beneath-The-Benchmark/">Explore the visual story →</a>
</p>

<br/>

<a id="engineering"></a>
<p align="center"><sub>03 / INDUSTRY ENGINEERING</sub></p>

<h2 align="center">AI workflows and software for real users.</h2>

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>NETSOL Technologies · 2026</h3>
      <strong>AI/ML Intern, Scientific Computing</strong>
      <br/><br/>
      Developed retrieval-augmented chat with speech input and output, plus
      authenticated AI-agent workflows for financial-document and database
      tasks. Worked on image classification, signature-forgery detection,
      application guardrails, and components of a credit-risk pipeline under
      the supervising AI/ML engineer.
      <br/><br/>
      <sub>PYTHON · RAG · AI WORKFLOWS · COMPUTER VISION</sub>
    </td>
    <td width="50%" valign="top">
      <h3>NETSOL Technologies · 2025</h3>
      <strong>Software Engineering Intern, UNITY</strong>
      <br/><br/>
      Built FastAPI services and serverless endpoints with AWS Lambda and API
      Gateway. Integrated Supabase authentication and PostgreSQL persistence,
      containerized services with Docker, and connected a Jinja-based frontend
      to S3/CloudFront delivery.
      <br/><br/>
      <sub>FASTAPI · POSTGRESQL · SUPABASE · DOCKER · AWS</sub>
    </td>
  </tr>
</table>

<br/>

<a id="projects"></a>
<p align="center"><sub>04 / SELECTED SOFTWARE</sub></p>

<h2 align="center">Research-minded builds, useful products, and real-time systems.</h2>

<table>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/hamzamaverick51/Dual-Finance-Tool">Dual Finance Tool ↗</a></h3>
      <code>FASTAPI · SUPABASE · JINJA2 · GEMINI</code>
      <br/><br/>
      A financial-planning application combining tax, installment, and reverse
      planning flows with authenticated history, external finance APIs, and
      generated explanations. Built during my 2025 NETSOL internship.
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/hamzamaverick51/GradientVision">GradientVision ↗</a></h3>
      <code>PYTHON · SYMPY · NUMPY · SCIKIT-LEARN · PLOTLY</code>
      <br/><br/>
      A mathematical analysis assistant with symbolic and numerical gradients,
      critical-point classification, natural-language queries, and interactive
      2D/3D visualization.
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/ARCH-Student-Portal/ARCH-Student-Portal">ARCH Student Portal ↗</a></h3>
      <code>REACT · NODE.JS · DATABASES · RBAC</code>
      <br/><br/>
      A team-built university portal for registration, grading, attendance,
      and role-based workflows. I worked on system design and the interfaces
      connecting student-facing pages to live APIs.
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/hamzamaverick51/Ballistic-Drift">Ballistic Drift ↗</a></h3>
      <code>C++ · RAYLIB · GAME AI · REAL-TIME GRAPHICS</code>
      <br/><br/>
      A Pong reinterpretation with local multiplayer, adaptive CPU opponents,
      collision handling, reactive effects, audio states, and persistent high
      scores.
    </td>
  </tr>
</table>

<br/>

<p align="center"><sub>05 / TECHNICAL BACKBONE</sub></p>

<h2 align="center">Tools for experiments and applications.</h2>

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,cpp,pytorch,opencv,sklearn,numpy,fastapi,react,ts,nodejs,postgres,supabase,aws,docker,git,linux&perline=8" alt="Python, C++, PyTorch, OpenCV, scikit-learn, NumPy, FastAPI, React, TypeScript, Node.js, PostgreSQL, Supabase, AWS, Docker, Git, and Linux" />
</p>

<details>
  <summary><strong>Open the technical inventory</strong></summary>
  <br/>

| Area | Tools and practices |
|---|---|
| Research computing | Python, PyTorch, NumPy, scikit-learn, OpenCV; dataset audits, controlled experiments, reproducible evaluation |
| Applications and APIs | FastAPI, React, Node.js, REST APIs, PostgreSQL, Supabase, authentication and access control |
| Deployment and systems | C++, NCNN, Docker, Linux, AWS Lambda/API Gateway/S3/CloudFront; desktop and ARM compatibility checks |
| Mathematical software | SymPy, numerical methods, classification, interactive visualization |

</details>

<br/>

<p align="center"><sub>06 / HOW I WORK</sub></p>

<h2 align="center">Make the evidence inspectable.</h2>

<p align="center">
  Audit the data before trusting a benchmark.<br/>
  Repeat a promising result before promoting it.<br/>
  Record failures and limitations alongside successes.<br/>
  Build tools another person can run and review.
</p>

<p align="center">
  <img width="96%" src="https://github-readme-activity-graph.vercel.app/graph?username=hamzamaverick51&bg_color=06131F&color=9BDFF2&line=27C7A8&point=3BE8FF&area=true&hide_border=true" alt="Hamza's GitHub contribution activity" />
</p>

---

<div align="center">

<sub>CONNECTION REQUEST</sub>

## Let’s build something that has to work.

I am interested in computer vision, NLP evaluation, multimodal AI, research
engineering, and software whose claims survive careful testing.

[**Repositories**](https://github.com/hamzamaverick51?tab=repositories)
&nbsp;·&nbsp;
[**LinkedIn**](https://www.linkedin.com/in/hamza-raheel-829001319/)
&nbsp;·&nbsp;
[**Email**](mailto:hamzaprofessionalwork@gmail.com)

<br/>

`Lahore, Pakistan` · `research with receipts` · `systems that ship`

</div>
