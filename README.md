<p align="center">
  <img src="./profile-banner.svg" alt="Kevin Loggenberg · Full-stack software developer and Intelligent Transport Systems professional · Johannesburg, South Africa" width="100%">
</p>

<p align="center">
  <a href="https://kevlog.co.za/"><img alt="Portfolio" src="https://img.shields.io/badge/Portfolio-176C62?style=for-the-badge&amp;logo=firefoxbrowser&amp;logoColor=white" height="26"></a>
  <a href="https://kevlog.co.za/blog/"><img alt="Writing" src="https://img.shields.io/badge/Writing-5146A4?style=for-the-badge&amp;logo=markdown&amp;logoColor=white" height="26"></a>
  <a href="https://www.linkedin.com/in/ksloggenberg/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-245C92?style=for-the-badge&amp;logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0yIDhoNHYxNEgyem0yLTZhMiAyIDAgMSAxIDAgNCAyIDIgMCAwIDEgMC00em01IDZoNHYyYzEtMiA0LTMgNi0yIDIgMSAzIDMgMyA2djhoLTR2LThjMC0zLTUtMy01IDB2OEg5eiIvPjwvc3ZnPg%3D%3D&amp;logoColor=white" height="26"></a>
  <a href="https://github.com/V4LKYR13101?tab=repositories"><img alt="Repositories" src="https://img.shields.io/badge/Repositories-292640?style=for-the-badge&amp;logo=github&amp;logoColor=white" height="26"></a>
</p>

I build software across the web, desktop, mobile and embedded devices. My projects range from a workout tracker that follows a session onto a watch to a Pico on my desk that shows how this portfolio is doing.

## ✦ Projects

Newest first. Select any row to open the project.

<details>
<summary><picture><img alt="WaTenancy" src="https://img.shields.io/badge/WaTenancy-176C62?style=for-the-badge&amp;logo=whatsapp&amp;logoColor=white" height="22" align="middle"></picture> &nbsp; A company-scoped WhatsApp messaging service &nbsp; <code>Messaging</code></summary>

An ASP.NET Core and Blazor Server application that wraps <code>wacli</code> so companies can manage multiple WhatsApp numbers, team access, API keys and webhook endpoints within their own workspace.

[Source on GitHub](https://github.com/V4LKYR13101/WA_TENANCY)

</details>

<details>
<summary><picture><img alt="Smoke Jumper" src="https://img.shields.io/badge/Smoke_Jumper-1D4ED8?style=for-the-badge&amp;logo=docker&amp;logoColor=white" height="22" align="middle"></picture> &nbsp; Run .NET apps and restore databases in Docker &nbsp; <code>Dev Tools</code></summary>

I built a Windows tool for spinning up local test environments from a .NET project or a published build. You can run the application, restore a database copy, or bring both up together. Each workspace keeps its containers, ports, logs and backup history in one place.

For recovery drills, it restores MySQL or SQL Server backups into separate containers and reports checks such as backup checksums, restored data comparisons and HTTP smoke tests individually.

<img alt="C#" src="https://img.shields.io/badge/C%23-a044b3?style=flat-square&amp;logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHRleHQgeD0iMCIgeT0iMTgiIGZvbnQtZmFtaWx5PSJBcmlhbCxzYW5zLXNlcmlmIiBmb250LXNpemU9IjE3IiBmb250LXdlaWdodD0iYm9sZCIgZmlsbD0id2hpdGUiPkMjPC90ZXh0Pjwvc3ZnPg%3D%3D&amp;logoColor=white" height="19"> &nbsp; ASP.NET Core &nbsp; <img alt="Docker" src="https://img.shields.io/badge/Docker-1D4ED8?style=flat-square&amp;logo=docker&amp;logoColor=white" height="19"> &nbsp; <img alt="MySQL" src="https://img.shields.io/badge/MySQL-245C92?style=flat-square&amp;logo=mysql&amp;logoColor=white" height="19"> &nbsp; SQL Server

[Project walkthrough and screenshots](https://kevlog.co.za/projects/smoke-jumper/) · [Backup and recovery write-up](https://kevlog.co.za/blog/smoke-jumper-backup-recovery/)

</details>

<details>
<summary><picture><img alt="Pico Studio" src="https://img.shields.io/badge/Pico_Studio-A31554?style=for-the-badge&amp;logo=raspberrypi&amp;logoColor=white" height="22" align="middle"></picture> &nbsp; A desktop workspace for developing on the Raspberry Pi Pico &nbsp; <code>Dev Tools</code></summary>

I built Pico Studio to bring device files, a Python editor, diagnostics and the USB console into one desktop app. It can listen to a running board as soon as it connects. You enter the REPL explicitly when you need file access.

The editor includes syntax checks and Pyflakes diagnostics. You can transfer folders and ZIP archives and opt into live monitoring for heap usage, filesystem space and clock frequency.

<img alt="Python" src="https://img.shields.io/badge/Python-245C92?style=flat-square&amp;logo=python&amp;logoColor=white" height="19"> &nbsp; Tkinter &nbsp; <img alt="MicroPython" src="https://img.shields.io/badge/MicroPython-292640?style=flat-square&amp;logo=micropython&amp;logoColor=white" height="19"> &nbsp; pyserial &nbsp; mpremote

[Project walkthrough and screenshots](https://kevlog.co.za/projects/pico-studio/)

</details>

<details>
<summary><picture><img alt="Kevlog Desk Display" src="https://img.shields.io/badge/Kevlog_Desk_Display-176C62?style=for-the-badge&amp;logo=micropython&amp;logoColor=white" height="22" align="middle"></picture> &nbsp; Portfolio analytics on a Pico e-paper screen &nbsp; <code>Embedded</code></summary>

A Raspberry Pi Pico 2 W pulls aggregate analytics from my portfolio and cycles through daily, weekly, monthly and all-time views on a 2.13-inch Waveshare e-paper panel. It shows browser views, visitor estimates and download starts.

The firmware uses partial refreshes for routine updates, remembers multiple Wi-Fi networks and shows the last reading as stale if it loses access to the API. A setup portal lets me configure the device from a phone.

<img alt="MicroPython" src="https://img.shields.io/badge/MicroPython-292640?style=flat-square&amp;logo=micropython&amp;logoColor=white" height="19"> &nbsp; <img alt="Raspberry Pi Pico 2 W" src="https://img.shields.io/badge/Raspberry_Pi_Pico_2_W-A31554?style=flat-square&amp;logo=raspberrypi&amp;logoColor=white" height="19"> &nbsp; Waveshare e-paper

</details>

<details>
<summary><picture><img alt="Kevlog" src="https://img.shields.io/badge/Kevlog-245C92?style=for-the-badge&amp;logo=sqlite&amp;logoColor=white" height="22" align="middle"></picture> &nbsp; A self-hosted portfolio, blog and writing studio &nbsp; <code>Web</code></summary>

I built the site behind this profile as a place to document projects, share technical notes and publish interactive examples. It has a SQLite-backed CMS for editing articles and project galleries, searchable topics, and aggregate analytics that also power my e-paper display.

<img alt="Python" src="https://img.shields.io/badge/Python-245C92?style=flat-square&amp;logo=python&amp;logoColor=white" height="19"> &nbsp; <img alt="SQLite" src="https://img.shields.io/badge/SQLite-245C92?style=flat-square&amp;logo=sqlite&amp;logoColor=white" height="19"> &nbsp; <img alt="JavaScript" src="https://img.shields.io/badge/JavaScript-8F4B12?style=flat-square&amp;logo=javascript&amp;logoColor=white" height="19">

[Live portfolio](https://kevlog.co.za/) · [Blog](https://kevlog.co.za/blog/)

</details>

<details>
<summary><picture><img alt="Forge" src="https://img.shields.io/badge/Forge-6D28D9?style=for-the-badge&amp;logo=fitbit&amp;logoColor=white" height="22" align="middle"></picture> &nbsp; Local-first strength training with a 3D muscle map &nbsp; <code>Fitness</code></summary>

I designed Forge to keep workout logging close to the session, whether you have your phone or just your watch. It spans Android, Windows and the web, with a native Wear OS companion for logging sets and tracking rest timers.

- A 3D Strength Map shows progression by muscle group.
- An optional AI coach uses your own provider key and lets you review proposed changes before applying them.

<a href="https://kevlog.co.za/projects/forge/"><img src="https://kevlog.co.za/assets/forge-mockups/map.webp" alt="Forge's 3D Strength Map shown in a phone mockup" width="260"></a>

[Project walkthrough and screenshots](https://kevlog.co.za/projects/forge/)

</details>

<details>
<summary><picture><img alt="K2.Python" src="https://img.shields.io/badge/K2.Python-245C92?style=for-the-badge&amp;logo=python&amp;logoColor=white" height="22" align="middle"></picture> &nbsp; A terminal client that gives OpenClaw local tools &nbsp; <code>AI Clients</code></summary>

K2.Python streams replies from a self-hosted OpenClaw gateway into the terminal and accepts text or voice input. Its tool layer lets the agent work in a local development environment by reading and editing files, running shell commands, using Git and making web requests.

<img alt="Python" src="https://img.shields.io/badge/Python-245C92?style=flat-square&amp;logo=python&amp;logoColor=white" height="19"> &nbsp; WebSockets &nbsp; <img alt="OpenClaw" src="https://img.shields.io/badge/OpenClaw-A31554?style=flat-square&amp;logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0xMiA1YTcgNyAwIDAgMC02IDRDMiA0LTIgOSAyIDEzbDMtMWMwIDQgMiA2IDQgN3YzaDJ2LTNoMnYzaDJ2LTNjMi0xIDQtMyA0LTdsMyAxYzQtNCAwLTktNC00YTcgNyAwIDAgMC02LTR6Ii8%2BPHBhdGggc3Ryb2tlPSJ3aGl0ZSIgZmlsbD0ibm9uZSIgZD0ibTkgNi0zLTRtOSA0IDMtNCIvPjxjaXJjbGUgY3g9IjkiIGN5PSIxMCIgcj0iMS40IiBmaWxsPSIjYTMxNTU0Ii8%2BPGNpcmNsZSBjeD0iMTUiIGN5PSIxMCIgcj0iMS40IiBmaWxsPSIjYTMxNTU0Ii8%2BPC9zdmc%2B&amp;logoColor=white" height="19">

[Source on GitHub](https://github.com/V4LKYR13101/K2.Python)

</details>

<details>
<summary><picture><img alt="OpenClaw Skills" src="https://img.shields.io/badge/OpenClaw_Skills-A31554?style=for-the-badge&amp;logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0xMiA1YTcgNyAwIDAgMC02IDRDMiA0LTIgOSAyIDEzbDMtMWMwIDQgMiA2IDQgN3YzaDJ2LTNoMnYzaDJ2LTNjMi0xIDQtMyA0LTdsMyAxYzQtNCAwLTktNC00YTcgNyAwIDAgMC02LTR6Ii8%2BPHBhdGggc3Ryb2tlPSJ3aGl0ZSIgZmlsbD0ibm9uZSIgZD0ibTkgNi0zLTRtOSA0IDMtNCIvPjxjaXJjbGUgY3g9IjkiIGN5PSIxMCIgcj0iMS40IiBmaWxsPSIjYTMxNTU0Ii8%2BPGNpcmNsZSBjeD0iMTUiIGN5PSIxMCIgcj0iMS40IiBmaWxsPSIjYTMxNTU0Ii8%2BPC9zdmc%2B&amp;logoColor=white" height="22" align="middle"></picture> &nbsp; Reusable capabilities for self-hosted agents &nbsp; <code>Automation</code></summary>

A collection of installable agent skills, including a fitness data connector that retrieves metrics such as steps, distance and active minutes.

[Source on GitHub](https://github.com/V4LKYR13101/Skills)

</details>

<details>
<summary><picture><img alt="K2.Maui" src="https://img.shields.io/badge/K2.Maui-176C62?style=for-the-badge&amp;logo=android&amp;logoColor=white" height="22" align="middle"></picture> &nbsp; An Android voice and chat client for OpenClaw &nbsp; <code>AI Clients</code></summary>

A .NET MAUI client for talking to a self-hosted OpenClaw agent from Android. I built a messaging-style interface with voice input, spoken replies and a persistent WebSocket connection that can run in the background.

<img alt="C#" src="https://img.shields.io/badge/C%23-a044b3?style=flat-square&amp;logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHRleHQgeD0iMCIgeT0iMTgiIGZvbnQtZmFtaWx5PSJBcmlhbCxzYW5zLXNlcmlmIiBmb250LXNpemU9IjE3IiBmb250LXdlaWdodD0iYm9sZCIgZmlsbD0id2hpdGUiPkMjPC90ZXh0Pjwvc3ZnPg%3D%3D&amp;logoColor=white" height="19"> &nbsp; <img alt=".NET MAUI" src="https://img.shields.io/badge/.NET_MAUI-512BD4?style=flat-square&amp;logo=dotnet&amp;logoColor=white" height="19"> &nbsp; <img alt="Android" src="https://img.shields.io/badge/Android-176C62?style=flat-square&amp;logo=android&amp;logoColor=white" height="19"> &nbsp; WebSockets

[Source on GitHub](https://github.com/V4LKYR13101/K2.Maui) · [Portfolio screenshots](https://kevlog.co.za/projects/k2-maui/)

</details>

<details>
<summary><picture><img alt="Twenty4Hire" src="https://img.shields.io/badge/Twenty4Hire-6D28D9?style=for-the-badge&amp;logo=blazor&amp;logoColor=white" height="22" align="middle"></picture> &nbsp; Conversational interview practice and job discovery &nbsp; <code>Recruitment</code></summary>

At Dynamic Data Technologies, I helped design and develop a recruitment platform with spoken interview simulations, adaptive follow-up questions and candidate reports. The platform also includes map-based job discovery, PayFast payments and scheduled background processing.

<img alt=".NET" src="https://img.shields.io/badge/.NET-512BD4?style=flat-square&amp;logo=dotnet&amp;logoColor=white" height="19"> &nbsp; <img alt="Blazor" src="https://img.shields.io/badge/Blazor-6D28D9?style=flat-square&amp;logo=blazor&amp;logoColor=white" height="19"> &nbsp; EF Core &nbsp; <img alt="ONNX Runtime" src="https://img.shields.io/badge/ONNX_Runtime-245C92?style=flat-square&amp;logo=onnx&amp;logoColor=white" height="19"> &nbsp; PayFast

[Project overview](https://kevlog.co.za/projects/twenty4hire/)

</details>

<details>
<summary><picture><img alt="BlazorComponents" src="https://img.shields.io/badge/BlazorComponents-6D28D9?style=for-the-badge&amp;logo=blazor&amp;logoColor=white" height="22" align="middle"></picture> &nbsp; Reusable UI components for Blazor &nbsp; <code>Web</code></summary>

A collection of Blazor components you can copy into a project and adapt directly.

[Source on GitHub](https://github.com/V4LKYR13101/BlazorComponents)

</details>

<details>
<summary><picture><img alt="ZettelAi" src="https://img.shields.io/badge/ZettelAi-6D28D9?style=for-the-badge&amp;logo=obsidian&amp;logoColor=white" height="22" align="middle"></picture> &nbsp; A desktop assistant with searchable notes &nbsp; <code>AI Clients</code></summary>

Zettel combines AI chat and note-taking in a translucent desktop overlay. You can dictate text, switch AI providers and create, search or edit notes from the same workspace.

[Source on GitHub](https://github.com/V4LKYR13101/ZettelAi)

</details>

<details>
<summary><picture><img alt="LinkedIn Profile Analyser" src="https://img.shields.io/badge/LinkedIn_Profile_Analyser-245C92?style=for-the-badge&amp;logo=googlechrome&amp;logoColor=white" height="22" align="middle"></picture> &nbsp; Ask questions about a profile from Chrome &nbsp; <code>Browser Extension</code></summary>

A Chrome extension that reads the profile you have open and passes its text to a selected Google AI model for analysis. A sidebar lets you save and reuse questions across profiles.

[Source on GitHub](https://github.com/V4LKYR13101/LinkedIn-Profile-Analyser)

</details>

<details>
<summary><picture><img alt="BERT Fine-Tuning" src="https://img.shields.io/badge/BERT_Fine--Tuning-8F4B12?style=for-the-badge&amp;logo=huggingface&amp;logoColor=white" height="22" align="middle"></picture> &nbsp; Train a text classifier on a laptop &nbsp; <code>Applied ML</code></summary>

A hands-on fine-tuning example using trading-related text as the classification problem.

[Source on GitHub](https://github.com/V4LKYR13101/Bert-finetune)

</details>

<details>
<summary><picture><img alt="MauiVisionONNX" src="https://img.shields.io/badge/MauiVisionONNX-245C92?style=for-the-badge&amp;logo=onnx&amp;logoColor=white" height="22" align="middle"></picture> &nbsp; Live camera classification on Android &nbsp; <code>Applied ML</code></summary>

I adapted the .NET MAUI ONNX sample to classify images from the live camera using inference on the device.

[Source on GitHub](https://github.com/V4LKYR13101/MauiVisionONNX)

</details>

<details>
<summary><picture><img alt="Local Phi-3 inference" src="https://img.shields.io/badge/Local_Phi--3_inference-6D28D9?style=for-the-badge&amp;logo=dotnet&amp;logoColor=white" height="22" align="middle"></picture> &nbsp; Run a language model on the CPU with .NET &nbsp; <code>Applied ML</code></summary>

A .NET and ONNX experiment that runs Phi-3 on the CPU and explores what local language-model inference looks like without a dedicated GPU.

[Source on GitHub](https://github.com/V4LKYR13101/local-inference-phi3)

</details>

<details>
<summary><picture><img alt="Local Whisper transcription" src="https://img.shields.io/badge/Local_Whisper_transcription-176C62?style=for-the-badge&amp;logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZD0iTTIgMTB2NG01LTh2MTJtNS0xNnYyMG01LTE2djEybTUtOHY0IiBzdHJva2U9IndoaXRlIiBzdHJva2Utd2lkdGg9IjIiIHN0cm9rZS1saW5lY2FwPSJyb3VuZCIvPjwvc3ZnPg%3D%3D&amp;logoColor=white" height="22" align="middle"></picture> &nbsp; Run speech-to-text on your own machine &nbsp; <code>Applied ML</code></summary>

An experiment in using OpenAI's Whisper model to turn audio into text locally.

[Source on GitHub](https://github.com/V4LKYR13101/local-transcption-openai-whisper)

</details>

---

> If something is broken, understand it. If it can be improved, improve it. If it does not exist, build it.
