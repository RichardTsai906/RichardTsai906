# Hi, I'm Richard Tsai

CS student at Feng Chia University — ISTM-Monash Dual Degree Program
(Taiwan → Monash University, Australia for my junior and senior years).

I build products that solve real problems, and I learn by doing.

---

## What I'm building

**Havabite** — a diet tracking app I solo-developed and launched on
both iOS and Android. Full-stack solo build with custom LLM integration
for structured food analysis. Currently serving 6,000+ users and
preparing for MAIC (Apple Mobile Application Innovation Contest).

**Apple quality grader** — take a photo of an apple → ML pipeline classifies
it A/B/C/D → pulls agricultural open data for suggested market price.

System architecture:
  [Mobile App] → POST /analyze → [FastAPI @ Render.com]
    → OpenCV: 13 visual features → Random Forest (100 trees, 66,948 images)
    → Quality score (with defect penalty) → A/B/C/D
    → Agricultural open data → suggested price
  [Mobile App displays result]

**Gesture control** — control your computer with hand gestures
(OK, thumbs up, rock, etc.) mapped to mouse movement and keyboard
shortcuts. Built with MediaPipe HandLandmarker + Python, with pytest
test coverage.

**n8n automation pipeline** — Docker-based workflow that scrapes
YouTube/news, generates short-form videos, and pushes them via Discord
webhook. Hit 37K monthly views.

**Ren'Py visual novel** — integrated ComfyUI (art), Suno (music), and
GPT-SOVITS (voice) to produce a playable MVP with fully AI-generated
assets.

---

## Tech I work with

**Languages:** TypeScript, Python, JavaScript, C, C++, Java
**Frontend:** React, HTML/CSS
**Backend & infra:** Cloudflare Workers, FastAPI, Docker, Firebase, Vercel
**AI/ML:** LLM API integration (prompt engineering, structured output,
token cost optimization), scikit-learn, OpenCV, MediaPipe, ComfyUI
**Tools:** Git, VS Code, Figma, Colab, Notion, HackMD

---

## How I work

Top-down learner — when an idea hits, I build it and pick up the tools
along the way. I've taken Intro to AI at school and complement it with
hands-on research into LLMs and agent systems. I use AI to accelerate
development, but every line gets reviewed before it ships.

---

## Elsewhere

Havabite: https://linktr.ee/havabite_app

Instagram: https://www.instagram.com/rich._.moving/
