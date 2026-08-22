<h1 align="center"> Welcome to my lab notebook 👋</h1>

<p align="center">Multimodal ML that runs on a webcam and a microphone — no lab rig required.</p>

<p align="center">
  <img alt="Sejong University" src="https://img.shields.io/badge/Sejong%20University-Dept.%20of%20AI-1f2937?style=flat-square">
  <img alt="Class of 2027" src="https://img.shields.io/badge/Graduating-Feb%202027%20·%20early-2563eb?style=flat-square">
  <img alt="Location" src="https://img.shields.io/badge/Seoul-KR-0d9488?style=flat-square">
  <a href="https://github.com/evan-cloud4453?tab=followers"><img alt="Followers" src="https://img.shields.io/github/followers/evan-cloud4453?style=flat-square&logo=github&label=Followers&color=7c3aed"></a>
</p>

I am an AI undergraduate at **Sejong University**, Department of Artificial Intelligence, graduating early in February 2027. I build multimodal systems that assume ordinary hardware — a webcam and a microphone rather than dedicated eye-tracking or lab equipment — and I care more about whether an evaluation protocol can be trusted than about the headline metric it produces. Current interests: personalization under distribution shift, evaluation designs that survive a small sample, and the cases where a low-dimensional physical feature set outperforms an image encoder.

<details>
<summary><b>한국어 소개</b></summary>

<br>

세종대학교 인공지능학과 재학 중이며 2027년 2월 조기졸업 예정입니다. 웹캠과 마이크처럼 누구나 가진 장비만으로 동작하는 멀티모달 시스템을 만듭니다. 성능 수치 자체보다, 그 수치를 만들어낸 평가 방법을 신뢰할 수 있는지를 먼저 확인하는 편입니다. 관심 분야는 분포 변화 하에서의 개인화, 표본이 작을 때도 무너지지 않는 평가 설계, 이미지 인코더보다 저차원 물리 피처가 앞서는 조건입니다.

**진행 중 — SEE-ON (視溫)**

발표자가 **말하지 않은 시각 정보**를 화면 해설 내레이션으로 만들어 회의 흐름을 끊지 않는 지점에 넣는 멀티 에이전트 시스템입니다. AI Rookie 본선 진출작이며 팀장을 맡고 있습니다.

문제를 "화면 읽어주기"가 아니라 **"발화가 남긴 공백 보완"** 으로 정의했습니다. 공백을 5개 유형으로 나누고 유형별 전담 에이전트가 해당 지점에서만 내레이션을 생성합니다. 당사자 설문 24명·심층 인터뷰 11명에서 최대 불편으로 지목된 것이 내레이션과 회의 음성의 겹침이었기 때문에, **무엇을 말할지**만큼 **언제 말하지 않을지**를 같은 비중으로 다룹니다.

| 저장소 | 역할 |
|---|---|
| [seeon-meet](https://github.com/See-on26/seeon-meet) | 온라인 회의 빌드 — Google Meet 회의에서 화면과 오디오를 함께 취득 |
| [electron-seeon-experiment](https://github.com/See-on26/electron-seeon-experiment) | 실험실 빌드 — 녹화 영상을 1배속으로 재생해 실회의와 동일한 내레이션 체인에 투입 |

파이프라인은 화면 캡처(OpenCV·MediaPipe)와 음성(faster-whisper·webrtcvad)을 함께 받아 Amazon Bedrock의 Claude로 내레이션을 생성하고, Electron 앱이 이를 실시간 패널에 쌓습니다.

</details>

#### Stack

| Area | Tools |
|---|---|
| **Languages** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![VBA](https://img.shields.io/badge/VBA-217346?style=flat-square) |
| **ML / DL** | ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white) ![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white) ![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white) |
| **Vision / Audio** | ![Ultralytics](https://img.shields.io/badge/YOLOv8-0B0B0B?style=flat-square&logo=ultralytics&logoColor=white) ![MediaPipe](https://img.shields.io/badge/MediaPipe-0097A7?style=flat-square&logo=mediapipe&logoColor=white) ![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white) |
| **LLM / Speech** | ![Amazon Bedrock](https://img.shields.io/badge/Amazon%20Bedrock-232F3E?style=flat-square) ![Claude](https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=claude&logoColor=white) ![Whisper](https://img.shields.io/badge/faster--whisper-4B5563?style=flat-square) ![WebRTC VAD](https://img.shields.io/badge/webrtcvad-333333?style=flat-square&logo=webrtc&logoColor=white) |
| **Backend** | ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white) ![Socket.IO](https://img.shields.io/badge/Socket.IO-010101?style=flat-square&logo=socketdotio&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white) |
| **Desktop / Infra** | ![Electron](https://img.shields.io/badge/Electron-47848F?style=flat-square&logo=electron&logoColor=white) ![WebRTC](https://img.shields.io/badge/WebRTC-333333?style=flat-square&logo=webrtc&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) |

#### Currently building

**[SEE-ON](https://github.com/See-on26)** (視溫) — a multi-agent system that narrates the visual information a speaker leaves unsaid during a live video meeting. Team lead, AI Rookie finals.

The problem is framed as gap-filling rather than screen-reading. A presenter omits what the screen already shows, so a listener on the audio channel alone receives half the message. SEE-ON defines that missing half as five gap types and assigns a dedicated agent to each, generating narration only at those points. Because the loudest complaint in our user research (24 survey responses, 11 in-depth interviews) was narration colliding with meeting audio, *when not to speak* is treated as equal in weight to *what to say*.

| Repository | Role |
|---|---|
| **[seeon-meet](https://github.com/See-on26/seeon-meet)** | Live build — captures screen and audio from a Google Meet session |
| **[electron-seeon-experiment](https://github.com/See-on26/electron-seeon-experiment)** | Lab build — replays recordings at 1× through the same narration chain |

The pipeline pairs screen capture (OpenCV, MediaPipe) with speech (faster-whisper, webrtcvad), generates narration through Claude on Amazon Bedrock, and streams it into an Electron panel beside the meeting.
