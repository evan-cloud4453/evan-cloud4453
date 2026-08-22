<h1 align="center"> Welcome to my lab notebook 👋</h1>

Building ML systems end to end: perception models, forecasting pipelines, and the real-time applications that have to run them.

![Sejong University](https://img.shields.io/badge/Sejong%20University-Dept.%20of%20AI-1f2937?style=flat-square) ![Graduating](https://img.shields.io/badge/Graduating-Feb%202027%20·%20early-2563eb?style=flat-square) ![Location](https://img.shields.io/badge/Seoul-KR-0d9488?style=flat-square) [![Followers](https://img.shields.io/github/followers/evan-cloud4453?style=flat-square&logo=github&label=Followers&color=7c3aed)](https://github.com/evan-cloud4453?tab=followers)

I am an AI undergraduate at **Sejong University**, Department of Artificial Intelligence, graduating early in February 2027. Most of my work sits between a model and the thing that uses it — I train the model, then build the application that has to run it in real time, usually on ordinary hardware. Across all of it I care more about whether an evaluation protocol can be trusted than about the headline metric it produces.

<details>
<summary><b>한국어 소개</b></summary>

<br>

세종대학교 인공지능학과 재학 중이며 2027년 2월 조기졸업 예정입니다. 작업 대부분이 모델과 그 모델을 쓰는 물건 사이에 있습니다. 모델을 학습시킨 뒤, 그것을 실시간으로 돌려야 하는 애플리케이션까지 만듭니다. 특수 장비가 아니라 일반적인 하드웨어를 전제로 설계합니다. 어느 분야든 성능 수치 자체보다, 그 수치를 만들어낸 평가 방법을 신뢰할 수 있는지를 먼저 확인합니다.

## 작업 분야

| 분야 | 내용 |
|---|---|
| **멀티모달 인지** | 시선·자세·환경음을 함께 받아 고정 임계값이 아닌 사용자별 기준선으로 판정 |
| **시계열 예측** | 물리적 근거를 가진 피처로 다중 horizon 회귀. 작은 피처 집합이 이미지 인코더를 이기는 경우를 다룸 |
| **실시간 시스템** | WebSocket·WebRTC 파이프라인 — 원격 감독, 다중 참가자 동기화, 회의 화면·오디오 취득 |
| **LLM 응용** | Bedrock 경유 Claude로 내레이션 생성 및 변형 문제 출제 파이프라인 구성 |
| **데스크톱·자동화** | Electron 애플리케이션, 그리고 API가 없는 단말에서 GUI 계층만으로 수행하는 업무 자동화 |

## 진행 중

**SEE-ON** — 발표자가 말하지 않은 시각 정보를 화면 해설 내레이션으로 만들어 회의 흐름을 끊지 않는 지점에 넣는 멀티 에이전트 시스템입니다. AI Rookie 본선 진출작이며 팀장을 맡고 있습니다. [See-on26](https://github.com/See-on26) 조직에 두 개의 빌드가 공개되어 있습니다 — [seeon-meet](https://github.com/See-on26/seeon-meet)은 실제 Google Meet 회의에서 화면과 오디오를 취득하고, [electron-seeon-experiment](https://github.com/See-on26/electron-seeon-experiment)는 녹화 영상을 동일한 내레이션 체인에 투입하는 실험실 빌드입니다.

</details>

## What I work on

| Area | Focus |
|---|---|
| **Multimodal perception** | Gaze, pose, and ambient audio fused into a per-user baseline rather than a fixed threshold |
| **Time-series forecasting** | Multi-horizon regression on physically grounded features, including the cases where a small feature set beats an image encoder |
| **Real-time systems** | WebSocket and WebRTC pipelines — remote invigilation, synchronised multiplayer, live meeting capture |
| **LLM applications** | Narration and variant-question pipelines running on Claude via Amazon Bedrock |
| **Desktop & automation** | Electron applications, and GUI-layer automation for terminals that expose no API |

## Stack

| Area | Tools |
|---|---|
| **Languages** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![VBA](https://img.shields.io/badge/VBA-217346?style=flat-square) |
| **ML / DL** | ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white) ![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white) ![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white) |
| **Vision / Audio** | ![Ultralytics](https://img.shields.io/badge/YOLOv8-0B0B0B?style=flat-square&logo=ultralytics&logoColor=white) ![MediaPipe](https://img.shields.io/badge/MediaPipe-0097A7?style=flat-square&logo=mediapipe&logoColor=white) ![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white) |
| **LLM / Speech** | ![Amazon Bedrock](https://img.shields.io/badge/Amazon%20Bedrock-232F3E?style=flat-square) ![Claude](https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=claude&logoColor=white) ![faster-whisper](https://img.shields.io/badge/faster--whisper-4B5563?style=flat-square) ![webrtcvad](https://img.shields.io/badge/webrtcvad-333333?style=flat-square&logo=webrtc&logoColor=white) |
| **Backend** | ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white) ![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white) ![Socket.IO](https://img.shields.io/badge/Socket.IO-010101?style=flat-square&logo=socketdotio&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white) |
| **Frontend** | ![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black) ![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white) |
| **Desktop / Infra** | ![Electron](https://img.shields.io/badge/Electron-47848F?style=flat-square&logo=electron&logoColor=white) ![WebRTC](https://img.shields.io/badge/WebRTC-333333?style=flat-square&logo=webrtc&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) |

## Currently building

**SEE-ON** — a multi-agent system that narrates the visual information a speaker leaves unsaid during a live video meeting. Team lead, AI Rookie finals. Two builds are public under the [See-on26](https://github.com/See-on26) organisation: [seeon-meet](https://github.com/See-on26/seeon-meet) captures screen and audio from a live Google Meet session, and [electron-seeon-experiment](https://github.com/See-on26/electron-seeon-experiment) replays recordings through the same narration chain for evaluation.
