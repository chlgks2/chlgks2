<div align="center">

### 백엔드 · AI 개발자

**AI 모델 학습부터 백엔드 서비스 연동까지 End-to-End 로 수행합니다.**

[![Gmail](https://img.shields.io/badge/duddngud3@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:duddngud3@gmail.com)
[![HuggingFace](https://img.shields.io/badge/🤗_HuggingFace-FFD21E?style=for-the-badge&logoColor=black)](https://huggingface.co/chlgks)
[![Portfolio](https://img.shields.io/badge/Portfolio-0C0F16?style=for-the-badge&logo=githubpages&logoColor=5B8DFF)](https://chlgks2.github.io/)

</div>


## 🛠 기술 스택

<div align="center">

<sub>**LANGUAGE**</sub>

<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white">
<img src="https://img.shields.io/badge/Java_17-007396?style=for-the-badge&logo=openjdk&logoColor=white">
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white">
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black">

<sub>**BACKEND**</sub>

<img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white">
<img src="https://img.shields.io/badge/Django_/_DRF-092E20?style=for-the-badge&logo=django&logoColor=white">
<img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white">
<img src="https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white">
<img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white">

<sub>**AI / ML**</sub>

<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white">
<img src="https://img.shields.io/badge/🤗_Transformers-FFD21E?style=for-the-badge&logoColor=black">
<img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white">
<img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white">
<img src="https://img.shields.io/badge/YOLOv8-00C7B7?style=for-the-badge&logo=yolo&logoColor=white">
<img src="https://img.shields.io/badge/Stable_Diffusion-6E56CF?style=for-the-badge&logoColor=white">

<sub>**DATABASE**</sub>

<img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white">
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white">
<img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white">
<img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white">
<img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white">

<sub>**INFRA / TOOLS**</sub>

<img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white">
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white">
<img src="https://img.shields.io/badge/GitLab_CI-FC6D26?style=for-the-badge&logo=gitlab&logoColor=white">
<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white">
<img src="https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=jira&logoColor=white">
<img src="https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=notion&logoColor=white">

<br>

**알고리즘** · 백준 **골드 1~2 티어**

</div>

<br>

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


---

## 📚 배워온 길

교육 과정 **4개 · 3,300h+** — 과정마다 그 자리에서 프로젝트를 남겼습니다.

| 연도 | 과정 | 배운 것 |
|---|---|---|
| **2022** | 메타버스 아카데미 1기 — 네트워크 / 서버 `900h+` | 네트워크 기초 · Node.js · SQL · Linux |
| **2023** | 메타버스 아카데미 2기 — AI `900h+` | 딥러닝 · 생성형 AI · 컴퓨터 비전 · FastAPI / Flask |
| **2024** | 이어드림스쿨 4기 `652h` | 딥러닝 이론 · NLP / LLM · Vision · Diffusion |
| **2026** | 삼성 청년 SW 아카데미 (SSAFY) 15기 `925h` | Python · Django · Vue.js · MySQL · 알고리즘 |

**서버 → AI → 모델의 안쪽 → 다시 백엔드.**
옮길 때마다 직전 과정에서 부족하다고 느낀 것이 다음 과정을 고른 이유였습니다.

🏆 인공지능 해커톤 **최우수상** `2023.08` · 메타버스 아카데미 최종 프로젝트 **최우수상** `2023.12` · 인공지능 경진대회 **우수상** `2024.01`

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
