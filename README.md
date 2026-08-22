### Gio Kim · 김지오

AI undergraduate at **Sejong University**, Department of Artificial Intelligence (3rd year). I build multimodal ML systems that run on commodity hardware — a webcam and a microphone rather than dedicated eye-tracking or lab equipment — and I care more about whether an evaluation protocol can be trusted than about the headline metric it produces.

- **Now** — `SEE-ON`, a multi-agent layer that narrates live video meetings for blind participants (LangGraph orchestration, WebRTC media control, NVDA add-on). Team lead, AI Rookie finals.
- **Recently** — `LEAM`, a concentration-assessment system that spends its first three minutes learning where a given user actually looks, then scores against that baseline instead of a fixed "is the user facing the screen" threshold.
- **Working on** — personalization under distribution shift, evaluation protocols that survive a small sample, and the cases where a low-dimensional physical feature set outperforms an image encoder.

#### Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white) ![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white) ![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white) ![Ultralytics](https://img.shields.io/badge/YOLOv8-0B0B0B?style=flat-square&logo=ultralytics&logoColor=white) ![MediaPipe](https://img.shields.io/badge/MediaPipe-0097A7?style=flat-square&logo=mediapipe&logoColor=white) ![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white)

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white) ![Socket.IO](https://img.shields.io/badge/Socket.IO-010101?style=flat-square&logo=socketdotio&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Electron](https://img.shields.io/badge/Electron-47848F?style=flat-square&logo=electron&logoColor=white)

#### Selected work

| Project | What it does | Stack |
|---|---|---|
| **[LEAM](https://github.com/evan-cloud4453/26-1DL_LEAM-Project)** | Calibrates to a user's gaze zones and ambient noise floor for three minutes, then applies a four-stage hierarchical check so that reading a book and dozing off are not scored the same way | PyTorch · L2CS-Net · YOLOv8n · PANNs · FastAPI |
| **[solar-wind-project-2026](https://github.com/evan-cloud4453/solar-wind-project-2026)** | Forecasts Earth-arriving solar wind speed at twelve horizons from SDO/AIA disk imagery. The strongest submission removes the CNN branch entirely in favour of ballistically aligned coronal-hole features | PyTorch · GRU · Jupyter |
| **[generative-ai-quiz](https://github.com/evan-cloud4453/generative-ai-quiz)** | Quiz trainer with a wrong-answer queue that maintains itself: missed items return for review and leave the queue once answered correctly. 215 items, single file, no build step | Vanilla JS · GitHub Pages |
| **[engQuiz](https://github.com/evan-cloud4453/engQuiz)** | TOEIC vocabulary CBT with live invigilation — the instructor watches progress and submissions over a websocket channel while the exam runs | Node.js · Socket.IO · MongoDB |
| **[sound-quiz-show](https://github.com/evan-cloud4453/sound-quiz-show)** | Real-time multiplayer game where players race to identify an audio clip, backed by an augmented sound-clip dataset | JavaScript · Python |
| **[coc-shortage-tracker](https://github.com/evan-cloud4453/coc-shortage-tracker)** | Automates a U.S. Army change-of-command property inventory through the GUI layer alone, on a terminal where no API or database access was permitted | VBA · Win32 API · Power Query |

<sub>All repositories → <a href="https://github.com/evan-cloud4453?tab=repositories">github.com/evan-cloud4453?tab=repositories</a></sub>

#### Activity

<a href="https://github.com/evan-cloud4453">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=evan-cloud4453&theme=github_dark">
    <img width="100%" alt="Contribution activity" src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=evan-cloud4453&theme=github_light">
  </picture>
</a>

<details>
<summary><b>한국어 소개</b></summary>

<br>

세종대학교 인공지능학과 3학년 김지오입니다. 웹캠과 마이크처럼 누구나 가진 장비만으로 동작하는 멀티모달 ML 시스템을 만듭니다. 성능 수치 자체보다, 그 수치를 만들어낸 평가 방법을 신뢰할 수 있는지를 먼저 확인하는 편입니다.

- **진행 중** — `SEE-ON`. 시각장애인 참여자를 위해 실시간 화상회의 상황을 서술하는 멀티 에이전트 시스템입니다. LangGraph 오케스트레이션, WebRTC 미디어 제어, NVDA 애드온으로 구성했고 팀장을 맡았습니다. AI Rookie 본선 진출작입니다.
- **최근** — `LEAM`. 세션 시작 후 3분간 사용자가 실제로 어디를 보는지 학습한 뒤, 그 개인 기준선에 대해 집중도를 평가합니다. "정면을 응시하는가"라는 고정 임계값을 쓰지 않기 때문에 독서대나 필기 환경에서도 오판이 줄어듭니다.
- **관심 분야** — 분포 변화 하에서의 개인화, 표본이 작을 때도 무너지지 않는 평가 설계, 이미지 인코더보다 저차원 물리 피처가 앞서는 조건.

**주요 프로젝트**

| 프로젝트 | 내용 | 스택 |
|---|---|---|
| **[LEAM](https://github.com/evan-cloud4453/26-1DL_LEAM-Project)** | 응시 밀도로 학습 Zone을, 환경음으로 기준 dB를 먼저 학습한 뒤 4단계 계층 판단으로 방해 요인을 순차 검증 | PyTorch · L2CS-Net · YOLOv8n · PANNs · FastAPI |
| **[solar-wind-project-2026](https://github.com/evan-cloud4453/solar-wind-project-2026)** | SDO/AIA 태양 원반 영상으로 12개 horizon의 지구 도달 태양풍 속도를 예측. 최고 제출은 CNN 분기를 제거하고 탄도 정렬된 코로나홀 피처만 사용한 모델 | PyTorch · GRU · Jupyter |
| **[generative-ai-quiz](https://github.com/evan-cloud4453/generative-ai-quiz)** | 틀린 문제가 자동으로 복습 큐에 들어가고 다시 맞히면 빠지는 오답 노트. 215문항, 단일 파일, 빌드 없음 | Vanilla JS · GitHub Pages |
| **[engQuiz](https://github.com/evan-cloud4453/engQuiz)** | 시험이 진행되는 동안 교사가 웹소켓으로 응시 상황과 제출을 실시간 감독하는 TOEIC 어휘 CBT | Node.js · Socket.IO · MongoDB |
| **[sound-quiz-show](https://github.com/evan-cloud4453/sound-quiz-show)** | 들려준 소리의 정체를 먼저 맞히는 실시간 멀티플레이 게임. 증강한 사운드 클립 데이터셋 기반 | JavaScript · Python |
| **[coc-shortage-tracker](https://github.com/evan-cloud4453/coc-shortage-tracker)** | API·DB 접근이 허용되지 않는 단말에서 GUI 계층만으로 미 육군 지휘관 이취임 재물조사를 자동화 | VBA · Win32 API · Power Query |

</details>
