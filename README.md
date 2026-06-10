<!-- HEADER -->
<div align="center">

```
╔══════════════════════════════════════════════════════════════════════════════════╗
║  $ git log --all --oneline --graph --decorate --author="Arin Dixit"            ║
╚══════════════════════════════════════════════════════════════════════════════════╝
```

</div>

<!-- BRANCH STATUS -->
```
On branch: main   ──●  feat/open-to-opportunities
Remote: origin/arin-dixit.vercel.app
HEAD is 2 commits ahead of origin/main, 0 behind

Last sync: June 2025  ·  Status: ✔ working tree clean
```

---

<!-- COMMIT LOG HEADER -->
<div align="center">

### `git log --pretty=format:"%C(yellow)%h%Creset %C(cyan)%ai%Creset %s" --stat`

</div>

---

<!-- COMMIT 1 - APL WIN -->
```
commit a3f91c2d  (HEAD → main, tag: v21.6-champion)
Author: Arin Dixit <id2013663@gmail.com>
Date:   June 2025

    feat(achievement): 🏆 Google Cloud APL National Champion

    Won Google Cloud Build with AI: Agentic Premier League hackathon
    as 1 of 5 National Champions out of 3,000+ participants.
    Finale held at Google Ananta, Bengaluru.

    Powered by: Gemini AI · React · Supabase · Socket.io · GCP

    diff --stat
     stadium-crowd-safety-platform/   |  ++++++++++++++++++++  [NEW]
     ai-realtime-analytics/           |  ++++++++++++++++      [NEW]
     crowd-density-heatmap/           |  +++++++++++           [NEW]
     3 files changed, 847 insertions(+), 0 deletions(-)
```

---

<!-- COMMIT 2 - INTERNSHIP -->
```
commit 7b2d441e  (tag: v21.5-builder)
Author: Arin Dixit <id2013663@gmail.com>
Date:   May 2025

    feat(internship): IoT Air Quality Monitoring — Prof. Rishi Ranjan Kumar

    Joined research internship at K.R. Mangalam University.
    Leading dashboard + mobile app layers for IoT sensor network.

    Stack: React · React Native/Expo · Node.js · Express · MQTT

    diff --stat
     iot-dashboard/              |  +++++++++++++++++++  [NEW]
     mobile-app/expo/            |  +++++++++++++++      [NEW]
     sensor-data-pipeline/       |  ++++++++            [MODIFIED]
     3 files changed, 612 insertions(+), 47 deletions(-)
```

---

<!-- COMMIT 3 - APEX -->
```
commit 9c14f83a  (tag: v21.4-saas)
Author: Arin Dixit <id2013663@gmail.com>
Date:   March 2025

    feat(project): APEX — Full-stack Productivity SaaS

    End-to-end productivity platform with task queuing, real-time
    collaboration, and AI-powered scheduling. Built and shipped solo.

    Stack: Expo · Node.js · Prisma · BullMQ · Socket.IO · Zustand

    diff --stat
     apps/mobile/                |  ++++++++++++++++++++  [NEW]
     server/queue/               |  +++++++++++++         [NEW]
     server/realtime/            |  ++++++++++++          [NEW]
     packages/shared/            |  +++++                 [NEW]
     4 files changed, 2,341 insertions(+), 0 deletions(-)
```

---

<!-- COMMIT 4 - INFRAWATCH -->
```
commit 2e87b6c5  (tag: v21.3-gemini)
Author: Arin Dixit <id2013663@gmail.com>
Date:   February 2025

    feat(project): InfraWatch — Pothole Reporter · Google Gen AI Academy APAC

    AI-powered road damage detection using Gemini Vision 2.5 Flash.
    Zero backend. Shipped & documented for Google Meet the Builders.

    Stack: React · Gemini 2.5 Flash Vision API · Vite

    diff --stat
     src/vision-pipeline/        |  ++++++++++++++++  [NEW]
     src/map-renderer/           |  +++++++++         [NEW]
     public/                     |  +++               [NEW]
     3 files changed, 441 insertions(+), 0 deletions(-)
```

---

<!-- COMMIT 5 - BIOSARTHI -->
```
commit 5f3dc921  (tag: v20.7-flutter)
Author: Arin Dixit <id2013663@gmail.com>
Date:   July 2024

    feat(internship): Biosarthi — Flutter IoT Monitoring App

    Cross-platform Flutter app for biogas plant monitoring.
    Integrated live IoT sensor data via REST APIs. Responsive
    performance dashboards for field technicians.

    Stack: Flutter · Dart · REST APIs · Firebase

    diff --stat
     lib/screens/dashboard/      |  ++++++++++++++++  [NEW]
     lib/services/iot/           |  ++++++++++++      [NEW]
     lib/widgets/                |  +++++++           [NEW]
     3 files changed, 788 insertions(+), 0 deletions(-)
```

---

<!-- COMMIT 6 - COLLEGE / ORIGIN -->
```
commit 0000001a  (tag: v20.0-init, origin)
Author: Arin Dixit <id2013663@gmail.com>
Date:   August 2023

    init: enrolled B.Tech CSE (AI & ML) · K.R. Mangalam University

    First commit. Starting the build.
    Event Organizer role added. Repository initialized.

    diff --stat
     README.md                   |  +  [CREATED THIS FILE]
     1 file changed, 1 insertion(+), 0 deletions(-)
```

---

## `git diff HEAD~∞ HEAD -- skills/`

<!-- SKILLS DIFF -->
```diff
  # languages
+ JavaScript       ████████████████████  expert
+ TypeScript       ████████████████░░░░  proficient
+ Python           ███████████████░░░░░  proficient
+ Dart             ████████████░░░░░░░░  comfortable
+ C++              ██████████░░░░░░░░░░  familiar
+ Java             ████████░░░░░░░░░░░░  familiar
+ SQL              ██████████████░░░░░░  proficient

  # frontend
+ React            ████████████████████  expert
+ Next.js          ████████████████░░░░  proficient
+ React Native     █████████████████░░░  proficient
+ Flutter          ████████████░░░░░░░░  comfortable
+ Tailwind CSS     ████████████████████  expert

  # backend
+ Node.js          ████████████████████  expert
+ Express          ████████████████░░░░  proficient
+ FastAPI          ████████████░░░░░░░░  comfortable
+ Prisma           █████████████████░░░  proficient
+ BullMQ           ████████████░░░░░░░░  comfortable

  # databases
+ PostgreSQL        ██████████████████░░  proficient
+ MongoDB           ████████████████░░░░  proficient
+ Redis             ████████████░░░░░░░░  comfortable
+ Supabase          █████████████████░░░  proficient

  # ai / ml
+ Gemini API        ████████████████████  expert
+ LangChain         ████████████░░░░░░░░  comfortable
+ FAISS             ██████████░░░░░░░░░░  familiar
+ Embeddings/RAG    █████████████░░░░░░░  proficient

  # devops / tools
+ Git               ████████████████████  expert
+ Docker            ███████████░░░░░░░░░  familiar
+ GCP               ████████████░░░░░░░░  comfortable
+ Postman           ████████████████░░░░  proficient
+ Figma             ████████████░░░░░░░░  comfortable
+ Socket.IO         █████████████████░░░  proficient
```

---

## `cat package.json | jq '.projects'`

```json
{
  "projects": [
    {
      "name": "APEX",
      "type": "SaaS · Mobile + Backend",
      "stack": ["Expo", "Node.js", "Prisma", "BullMQ", "Socket.IO", "Zustand"],
      "status": "shipped 🚀"
    },
    {
      "name": "Collaborate",
      "url": "https://collaborater.vercel.app",
      "type": "AI Workspace · Full-stack",
      "stack": ["React", "MERN", "Gemini AI", "Socket.io"],
      "status": "live 🟢"
    },
    {
      "name": "InfraWatch",
      "type": "AI Civic Tool · Frontend",
      "stack": ["React", "Gemini 2.5 Flash Vision", "Vite"],
      "status": "shipped 🚀"
    },
    {
      "name": "NSL Research Website",
      "type": "Academic · Full-stack",
      "stack": ["React", "Vite", "Node.js", "Express", "Framer Motion"],
      "status": "in review 🔄"
    },
    {
      "name": "Rishtawaala",
      "type": "Matrimonial Platform · Full-stack",
      "url": "https://rishtawaala.com",
      "stack": ["React", "GCP", "Node.js"],
      "status": "building 🔨"
    },
    {
      "name": "Semantic Drift Detector",
      "type": "ML Engineering",
      "stack": ["Python", "FAISS", "GMM", "CUSUM/Page-Hinkley"],
      "status": "research 🔬"
    }
  ]
}
```

---

## `git shortlog -sn --no-merges`

```
  847  Arin Dixit
    1  caffeine
    0  sleep (never merged)
```

---

## `git remote -v  # let's connect`

```
origin      https://arin-nu.vercel.app                (portfolio)
linkedin    https://linkedin.com/in/arin-dixit         (reach out)
github      https://github.com/ArinDixit06             (collab)
email       mailto:id2013663@gmail.com                 (hire)
leetcode    https://leetcode.com/u/arinDixit1/         (grind)
```

---

<!-- OPEN TO WORK STATUS -->
```
┌─────────────────────────────────────────────────────────────────────┐
│  $ git status --porcelain                                           │
│                                                                     │
│  M  career/full-time-role.md         → open to internships         │
│  M  career/freelance.md              → open to freelance           │
│  ?  career/research-collab.md        → interested                  │
│  ?  career/startup-ideas.md          → let's talk                  │
│                                                                     │
│  nothing committed yet — waiting for the right PR                  │
└─────────────────────────────────────────────────────────────────────┘
```

---

<div align="center">

```
─────────────────────────────────────────────────────────────────────
  Arin Dixit · B.Tech CSE (AI & ML) · K.R. Mangalam University
  Building the future, one commit at a time.
─────────────────────────────────────────────────────────────────────
```

![Profile Views](https://komarev.com/ghpvc/?username=ArinDixit06&label=profile+views&color=39d353&style=flat-square)

</div>
