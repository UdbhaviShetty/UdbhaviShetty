<div align="center">

<img src="assets/banner.svg" alt="Udbhavi Shetty: AI/ML student building computer vision and full-stack apps" width="100%">

</div>

<br>

<img src="assets/divider.svg" alt="" width="100%">

## 👋 About

I'm an AI/ML student who likes taking an idea past the notebook stage: into a browser tab, onto a phone, or in front of a real database. My strongest work so far is **SignSpeak AI**, a sign-language recognition app whose model runs entirely on the user's device.

I'm most interested in computer vision and in the engineering around a model: exporting it, shrinking it, shipping it, and testing the logic that surrounds it.

<table>
<tr>
<td width="33%" valign="top">

**🔒 On-device by default**<br>
<sub>SignSpeak moved from a paid cloud API to in-browser inference, so webcam frames never leave the device.</sub>

</td>
<td width="33%" valign="top">

**🧪 Logic you can test**<br>
<sub>TribalScholar's eligibility decisions come from a unit-tested rules engine, not a model's guess.</sub>

</td>
<td width="33%" valign="top">

**📋 Honest about status**<br>
<sub>My READMEs say what works, what is a prototype and what is not built yet.</sub>

</td>
</tr>
</table>

<br>

<img src="assets/divider.svg" alt="" width="100%">

## 🚀 Featured projects

<table>
<tr>
<td width="50%" valign="top">

### 🤟 [SignSpeak AI](https://github.com/UdbhaviShetty/Handgesture)
**Real-time sign-language recognition that runs in the browser.**

- Custom **YOLOv5s** detector (7.2M parameters), trained in PyTorch and exported to **ONNX**
- **INT8-quantised to 7.5 MB** and served with ONNX Runtime Web
- Recognises Hello, I love you, No, Please, Thanks, Yes and the ASL alphabet
- Adds a **MediaPipe** landmark classifier alongside the detector
- React + Vite frontend, configured for free static hosting on Vercel

![Computer Vision](https://img.shields.io/badge/Computer_Vision-0891B2?style=flat-square)
![PyTorch](https://img.shields.io/badge/PyTorch-0891B2?style=flat-square&logo=pytorch&logoColor=white)
![ONNX](https://img.shields.io/badge/ONNX-0891B2?style=flat-square&logo=onnx&logoColor=white)
![React](https://img.shields.io/badge/React-7C3AED?style=flat-square&logo=react&logoColor=white)

</td>
<td width="50%" valign="top">

### 🎓 [TribalScholar](https://github.com/UdbhaviShetty/TribalScholar)
**A mobile-first scholarship-support app for web, Android and iOS.**

- Built with **Expo / React Native** and **Supabase** (Auth + PostgreSQL)
- Eligibility comes from a **deterministic, unit-tested rules engine**, not an AI model
- Search, saved scholarships, application tracking and deadline alerts
- **50 automated tests** (21 core engine, 29 app data layer)
- Prototype status: bundled scholarship records are fictional demo data

![React Native](https://img.shields.io/badge/Expo-7C3AED?style=flat-square&logo=expo&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-4F46E5?style=flat-square&logo=typescript&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-0D9488?style=flat-square&logo=supabase&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-0D9488?style=flat-square&logo=postgresql&logoColor=white)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### ⚙️ [fastapiapp](https://github.com/UdbhaviShetty/fastapiapp)
**A full-stack app with a FastAPI backend and a TypeScript frontend.**

<!-- TODO: replace the line below with one sentence on what this app does. -->
- My most actively developed repository (42 commits)
- Separate `backend/` and `frontend/` folders with environment-based configuration

![FastAPI](https://img.shields.io/badge/FastAPI-0D9488?style=flat-square&logo=fastapi&logoColor=white)
![Python](https://img.shields.io/badge/Python-4F46E5?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-4F46E5?style=flat-square&logo=typescript&logoColor=white)

</td>
<td width="50%" valign="top">

### 🗂️ [employee_attendance](https://github.com/UdbhaviShetty/employee_attendance)
**An attendance and salary processor in core Python.**

- Computes attendance %, overtime pay and a 10% penalty for attendance below 75%
- Reads a 500-record CSV and exports a salary report with department-wise summaries
- Standard library only, with a unit-test suite

![Python](https://img.shields.io/badge/Python-4F46E5?style=flat-square&logo=python&logoColor=white)
![CSV](https://img.shields.io/badge/Data_Processing-334155?style=flat-square)
![Tests](https://img.shields.io/badge/Unit_Tested-0D9488?style=flat-square)

</td>
</tr>
</table>

<br>

<img src="assets/divider.svg" alt="" width="100%">

## 🧰 Tech stack

<table>
<tr>
<td width="150"><b>Languages</b></td>
<td>
<img src="https://img.shields.io/badge/Python-4F46E5?style=flat-square&logo=python&logoColor=white" alt="Python">
<img src="https://img.shields.io/badge/TypeScript-4F46E5?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript">
<img src="https://img.shields.io/badge/JavaScript-4F46E5?style=flat-square&logo=javascript&logoColor=white" alt="JavaScript">
</td>
</tr>
<tr>
<td><b>ML and vision</b></td>
<td>
<img src="https://img.shields.io/badge/PyTorch-0891B2?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch">
<img src="https://img.shields.io/badge/ONNX-0891B2?style=flat-square&logo=onnx&logoColor=white" alt="ONNX">
<img src="https://img.shields.io/badge/YOLOv5-0891B2?style=flat-square" alt="YOLOv5">
<img src="https://img.shields.io/badge/MediaPipe-0891B2?style=flat-square" alt="MediaPipe">
</td>
</tr>
<tr>
<td><b>Web and mobile</b></td>
<td>
<img src="https://img.shields.io/badge/React-7C3AED?style=flat-square&logo=react&logoColor=white" alt="React">
<img src="https://img.shields.io/badge/React_Native-7C3AED?style=flat-square&logo=react&logoColor=white" alt="React Native">
<img src="https://img.shields.io/badge/Expo-7C3AED?style=flat-square&logo=expo&logoColor=white" alt="Expo">
<img src="https://img.shields.io/badge/Vite-7C3AED?style=flat-square&logo=vite&logoColor=white" alt="Vite">
</td>
</tr>
<tr>
<td><b>Backend and data</b></td>
<td>
<img src="https://img.shields.io/badge/FastAPI-0D9488?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI">
<img src="https://img.shields.io/badge/Supabase-0D9488?style=flat-square&logo=supabase&logoColor=white" alt="Supabase">
<img src="https://img.shields.io/badge/PostgreSQL-0D9488?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL">
</td>
</tr>
<tr>
<td><b>Tooling</b></td>
<td>
<img src="https://img.shields.io/badge/Git-334155?style=flat-square&logo=git&logoColor=white" alt="Git">
<img src="https://img.shields.io/badge/GitHub-334155?style=flat-square&logo=github&logoColor=white" alt="GitHub">
<img src="https://img.shields.io/badge/Vercel-334155?style=flat-square&logo=vercel&logoColor=white" alt="Vercel">
<img src="https://img.shields.io/badge/Node.js-334155?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js">
</td>
</tr>
</table>

<br>

<img src="assets/divider.svg" alt="" width="100%">

<!--
GITHUB STATS: deliberately left out for now.
With a handful of young repositories the cards would show small numbers and
undersell your work. Once you have more activity, uncomment this block.

<div align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=UdbhaviShetty&layout=compact&hide_border=true&bg_color=0B1130&title_color=22D3EE&text_color=C7D2FE" alt="Top languages">
</div>
-->

<!--
CONNECT: add only the links you want recruiters to use, then uncomment.

## 📫 Connect

<a href="https://www.linkedin.com/in/YOUR-HANDLE"><img src="https://img.shields.io/badge/LinkedIn-4F46E5?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
<a href="mailto:YOUR-EMAIL"><img src="https://img.shields.io/badge/Email-0D9488?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
-->
