<div align="center">

# 최영우 · Youngwoo Choi

### 백엔드 · AI 개발자

**AI 모델 학습부터 백엔드 서비스 연동까지 End-to-End 로 수행합니다.**

[![HuggingFace](https://img.shields.io/badge/🤗_HuggingFace-FFD21E?style=flat-square&logoColor=black)](https://huggingface.co/chlgks)

</div>

---

## 📌 프로젝트

| 프로젝트 | 한 줄 소개 | 규모 | 핵심 성과 |
|---|---|---|---|
| **[Emour](https://github.com/chlgks2/Emour)** | 커플 대화 감정 분석 메신저 | 6주 · 6인 | 실사용 **291명** · 감정분석 정확도 **2.2배** · 응답지연 **10초→1초** |
| **[PixG](https://github.com/chlgks2/PixG)** 🏆 | AI 픽셀 스프라이트 시트 생성기 | 6주 · 5인 | **최우수상** · 메타버스 플랫폼 ZEP 실적용 검증 |
| **[Blind Dating](https://github.com/chlgks2/blind_dating)** | 성향 기반 블라인드 소개팅 | 5주 · 2인 | GPU 추론 서버 분리 구축(pull) · ComfyUI 파이프라인 설계 |
| **[Dream Shaper](https://github.com/chlgks2/DreamShaper)** | AI 음성 커버 생성 서비스 | 1개월 · 6인 | 화자 5명 **약 194시간** 학습 · AI 서버 직접 구축 |
| **[엄마 이게뭐야](https://github.com/chlgks2/YOLO_v8-mediapipe_)** | YOLOv8 실시간 객체 탐지 앱 | 1개월 · 5인 | **94클래스 5,576장** 직접 라벨링 · 클래스 불균형 개선 |
| **[SNS Clone](https://github.com/chlgks2/nestjs_sns)** | NestJS 백엔드 | 1개월 · **개인** | 설계·구현 100% · DI 구조 · TypeORM 관계 설계 |

### 같은 문제, 다른 답 — 파일 전송 구조

3년에 걸쳐 같은 문제를 세 번 만났고, **매번 지켜야 할 것이 달라 답도 달랐습니다.**

| 프로젝트 | 방식 | 우선한 것 |
|---|---|---|
| Dream Shaper `2023.09` | 클라이언트 → S3 직접 | 서버가 대용량 음원 트래픽에서 빠지는 것 |
| Blind Dating `2026.06` | 워커 → 백엔드 → S3 | **GPU 서버에 자격증명을 두지 않는 것** — 일부러 반대로 갔습니다 |
| Emour `2026.08` | `FileStorage` 인터페이스 추상화 | DB에 전체 URL이 아니라 key만 저장해 저장소 이전 비용을 없애는 것 |

---

## 🛠 기술 스택

**Language**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java_17-007396?style=flat-square&logo=openjdk&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

**Backend**

![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Django](https://img.shields.io/badge/Django_/_DRF-092E20?style=flat-square&logo=django&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)

**AI / ML**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![HuggingFace](https://img.shields.io/badge/🤗_Transformers-FFD21E?style=flat-square&logoColor=black)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![YOLO](https://img.shields.io/badge/YOLOv8-00FFFF?style=flat-square&logo=yolo&logoColor=black)
![ComfyUI](https://img.shields.io/badge/ComfyUI_/_Stable_Diffusion-6E56CF?style=flat-square&logoColor=white)

**Database**

![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)

**Infra / Tools**

![AWS](https://img.shields.io/badge/AWS_S3_·_EC2-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitLab CI](https://img.shields.io/badge/GitLab_CI-FC6D26?style=flat-square&logo=gitlab&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Jira](https://img.shields.io/badge/Jira-0052CC?style=flat-square&logo=jira&logoColor=white)
![Notion](https://img.shields.io/badge/Notion-000000?style=flat-square&logo=notion&logoColor=white)

<details>
<summary><b>세부 사용 맥락 펼쳐 보기</b></summary>

<br>

| 구분 | 기술 | 어디서 썼는가 |
|---|---|---|
| 인증 / 보안 | JWT (Access·Refresh 분리) · OAuth 2.0(Google) · BCrypt · Spring Security | Emour — Refresh만 Redis에 TTL 저장해 토큰 회수 수단 확보, 계정 열거 방지 |
| 실시간 통신 | WebSocket (STOMP) · Django Channels · channels-redis | Emour 채팅 · Blind Dating — `BaseMiddleware` 상속해 쿼리스트링 JWT 인증 직접 구현 |
| ORM | Spring Data JPA / Hibernate · Django ORM · TypeORM | 세 프레임워크 모두 실전 사용 |
| NLP | KcELECTRA · kiwipiepy | Emour 감정 분류 15종 — 문장쌍 맥락 인코딩 |
| Vision | YOLOv8 · MediaPipe · SAM · IP-Adapter FaceID | 엄마 이게뭐야 커스텀 학습 · Blind Dating 아바타 생성 |
| 생성형 AI | Stable Diffusion (SD1.5/SDXL) · LoRA · ControlNet · AnimateDiff · DALL·E 2 | PixG 스프라이트 시트 · Blind Dating 아바타 · Dream Shaper 앨범 커버 |
| 음성 | SVC · RVC · HuBERT · NSF-HiFiGAN | Dream Shaper — 화자 5명 모델 학습 |

</details>

**알고리즘** — 백준 기준 **골드 3~4** 수준 *(계정이 남아 있지 않아 배지로 연결하지 않습니다)*

---

## 🤗 공개 모델

**[chlgks/emour-emotion-kcelectra-context-v2](https://huggingface.co/chlgks/emour-emotion-kcelectra-context-v2)**
한국어 커플 대화 감정 분류 (15종) — 문장 하나가 아니라 **직전 대화 맥락과 함께** 판단합니다.

`"됐어"` `"괜찮아"` 는 앞선 흐름에 따라 감정이 완전히 달라집니다.
**라벨링 단위를 문장 → 앞 10개 발화 묶음으로 바꾼 것**이 핵심 전환점이었습니다.

| 모델 | 단계 | test macro-F1 |
|---|---|---|
| [`emour-emotion-kcelectra`](https://huggingface.co/chlgks/emour-emotion-kcelectra) | 문장 단위 (baseline) | — |
| [`-context`](https://huggingface.co/chlgks/emour-emotion-kcelectra-context) | 맥락 인식 | 0.387 (n=111) |
| [**`-context-v2`**](https://huggingface.co/chlgks/emour-emotion-kcelectra-context-v2) | 맥락 + **실사용자 로그 재학습** | **0.5065** (n=660) |

> 두 맥락 모델의 점수는 **서로 다른 test 분할**에서 측정한 것이라 직접 비교할 수 없습니다.
> 누수 없는 동일 기준에서 방어되는 수치는 **0.175 → 0.39 (2.2배)** 입니다.

---

## 📊 GitHub

<div align="center">

<img src="https://github-readme-streak-stats.herokuapp.com/?user=chlgks2&hide_border=true&background=FFFFFF00&ring=3B6FD4&fire=E8833A&currStreakLabel=3B6FD4&sideLabels=6B7280&dates=9AA3B0" alt="GitHub Streak">

</div>

<!-- ─────────────────────────────────────────────────────────────
 아래 카드는 공용 인스턴스가 사용량 초과(503)일 때 깨져 보입니다.
 Vercel 에 직접 배포한 뒤 URL 의 도메인만 본인 것으로 바꾸면 안정적으로 동작합니다.
   1. github.com/anuraghazra/github-readme-stats  → Fork
   2. vercel.com → Add New Project → 그 저장소 선택
   3. Environment Variables 에  PAT_1 = (GitHub Personal Access Token, public_repo 권한)
   4. Deploy → 생성된 도메인으로 아래 두 줄의 도메인을 교체하고 주석을 해제
────────────────────────────────────────────────────────────── -->
<!--
<div align="center">
<img height="150" src="https://github-readme-stats.vercel.app/api?username=chlgks2&show_icons=true&include_all_commits=true&hide=issues&hide_border=true&title_color=3B6FD4&icon_color=E8833A">
<img height="150" src="https://github-readme-stats.vercel.app/api/top-langs/?username=chlgks2&layout=compact&hide_border=true&langs_count=8&title_color=3B6FD4&hide=css,html,scss,less&exclude_repo=Grounding-DINO,INITCLIENT">
</div>
-->

<div align="center">

**제 저장소의 모든 수치는 코드·로그·체크포인트에서 직접 확인한 실측값입니다.**

확인되지 않는 항목은 적지 않았고, 측정하지 않은 것은 **「측정하지 않았다」** 로 남겼습니다.

</div>
