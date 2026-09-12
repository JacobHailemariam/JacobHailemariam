<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0A0A0B,60:4C1D95,100:7C3AED&height=200&section=header&text=Jacob%20Hailemariam&fontSize=52&fontColor=FFFFFF&fontAlignY=34&desc=Electrical%20Engineering%20student%20building%20software%20and%20ML%2FAI%20systems&descAlignY=54&descSize=16" width="100%" alt="Jacob Hailemariam" />

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=20&duration=3200&pause=900&color=A78BFA&center=true&vCenter=true&width=620&lines=Training+models+on+hyperspectral+data;Shipping+backend+services;Routing+my+own+PCBs" alt="Typing intro" />

<br />

[![Portfolio](https://img.shields.io/badge/Portfolio-0A0A0B?style=for-the-badge&logo=vercel&logoColor=white)](https://jacobhailemariam.github.io/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jacob-hailemariam)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:jacob.hailemariam@ucalgary.ca)
[![EngInQuire](https://img.shields.io/badge/EngInQuire-7C3AED?style=for-the-badge&logo=googlechrome&logoColor=white)](https://enginquire.com)

![University of Calgary](https://img.shields.io/badge/University_of_Calgary-D6001C?style=flat-square&logoColor=white)
![Year](https://img.shields.io/badge/2nd_Year-EE_+_CE_minor-4C1D95?style=flat-square)
![GPA](https://img.shields.io/badge/GPA-3.91_/_4.00-166534?style=flat-square)

</div>

---

## 🔬 What I'm working on

> **Undergraduate Researcher — NSERC USRA** · Geospatial Sensing & Intelligence Lab (Prof. Lincoln Xu)
>
> Machine learning on hyperspectral and LiDAR data for Earth observation. I own the pipeline end to end — ingesting and aligning multi-gigabyte sensor datasets, then building and training the fusion models in PyTorch. Custom dataset, transform, and training-loop code rather than framework defaults, with a reproducible multi-run benchmarking protocol across three independent datasets. First-author manuscript in progress.
>
> ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) ![Mamba](https://img.shields.io/badge/Mamba_/_SSM-7C3AED?style=flat-square) ![Hyperspectral](https://img.shields.io/badge/Hyperspectral_+_LiDAR-0E7490?style=flat-square)

> **Co-Founder — [EngInQuire](https://enginquire.com)**
>
> A pre-semester prep venture for incoming Schulich engineering students — built and shipped solo. The site, the serverless booking and email pipeline, a 20-question practice-test engine, and the First-Year Blueprint Generator: a Gemini-powered app that turns a student's course load into a personalized weekly schedule.
>
> ![Students](https://img.shields.io/badge/~100-students_taught-166534?style=flat-square) ![Hours](https://img.shields.io/badge/6_hrs-instruction_delivered-166534?style=flat-square) ![Partnerships](https://img.shields.io/badge/2-campus_partnerships-166534?style=flat-square)

---

## 🚀 Selected work

<sub>Numbers here are measured, not estimated.</sub>

### 🧠 [cifar10-vision-transformer](https://github.com/JacobHailemariam/cifar10-vision-transformer)

A 13.4M-parameter ViT written from the patch embedding up. No convolutions, no pretrained weights. CLS token, learned positional encoding, seven pre-LN attention blocks with stochastic depth, trained with MixUp/CutMix, EMA, RandAugment, label smoothing, AMP, and a cosine schedule with warmup.

![Accuracy](https://img.shields.io/badge/test_accuracy-89.63%25-EE4C2C?style=flat-square)
![Params](https://img.shields.io/badge/parameters-13.4M-EE4C2C?style=flat-square)
![Pretrained](https://img.shields.io/badge/pretrained_weights-0-EE4C2C?style=flat-square)

### ⚡ [url-shortener](https://github.com/JacobHailemariam/url-shortener)

A FastAPI REST service with a Redis cache-aside layer, so Postgres is never touched on a hit, and a per-client fixed-window rate limiter keyed on an atomic counter whose 60-second expiry *is* the window. Over-limit requests get a 429. Full stack containerized with Docker Compose.

![Throughput](https://img.shields.io/badge/1,114-req%2Fs_sustained-009688?style=flat-square)
![p50](https://img.shields.io/badge/40_ms-p50_latency-009688?style=flat-square)
![Failures](https://img.shields.io/badge/0_%2F_2000-failed_requests-009688?style=flat-square)

### 🌐 [jacobhailemariam.github.io](https://github.com/JacobHailemariam/JacobHailemariam.github.io)

Statically exported Next.js App Router site in TypeScript, published by a GitHub Actions pipeline on every push to `main`.

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

### 🔌 Simon Says — breadboard to fabricated board

Breadboard prototype → custom 2-layer PCB drawn in Altium → MicroPython firmware on a Raspberry Pi Pico, verified in simulation before fabrication. No repo — it's a board.

![Altium](https://img.shields.io/badge/Altium_Designer-A5915F?style=flat-square&logo=altiumdesigner&logoColor=white)
![Pico](https://img.shields.io/badge/Raspberry_Pi_Pico-A22846?style=flat-square&logo=raspberrypi&logoColor=white)
![MicroPython](https://img.shields.io/badge/MicroPython-2B2728?style=flat-square&logo=micropython&logoColor=white)

---

## 🛠️ Tools I actually reach for

**Machine learning**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Transformers](https://img.shields.io/badge/Vision_Transformers-7C3AED?style=for-the-badge)
![Mamba](https://img.shields.io/badge/Mamba_/_SSM-4C1D95?style=for-the-badge)

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)

**Backend & systems**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-FF4438?style=for-the-badge&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

**Web & deployment**

![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini_API-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white)

**Hardware & embedded**

![Altium](https://img.shields.io/badge/Altium_Designer-A5915F?style=for-the-badge&logo=altiumdesigner&logoColor=white)
![Raspberry Pi](https://img.shields.io/badge/Raspberry_Pi_Pico-A22846?style=for-the-badge&logo=raspberrypi&logoColor=white)
![MicroPython](https://img.shields.io/badge/MicroPython-2B2728?style=for-the-badge&logo=micropython&logoColor=white)

---

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=JacobHailemariam&show_icons=true&hide_border=true&bg_color=0A0A0B&title_color=A78BFA&icon_color=7C3AED&text_color=E5E5E5&include_all_commits=true" height="165" alt="GitHub stats" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=JacobHailemariam&layout=compact&hide_border=true&bg_color=0A0A0B&title_color=A78BFA&text_color=E5E5E5&langs_count=6" height="165" alt="Top languages" />

</div>

---

## 📬 Currently

Open to **part-time software/ML work now or Winter 2027**, and **full-time Summer 2027 internships**. Software engineering, ML, or anything where the model has to run on real hardware.

<sub>Off the clock: basketball, ping pong, anime, and a Smash Bros habit I'm not apologising for.</sub>

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:7C3AED,40:4C1D95,100:0A0A0B&height=120&section=footer" width="100%" alt="" />
</div>
