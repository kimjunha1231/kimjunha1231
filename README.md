<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=36:86a1a9,100:b2cfb6&height=200&section=header&text=Welcome%20to%20junha's%20GitHub%20👋&fontSize=40" width="100%" />
</p>

💻 **Frontend-focused Fullstack Developer**<br />
🎓 **숭실대학교 컴퓨터학부** (2020.03 ~ 2026.08 졸업)

> AI를 도구로 활용해 개발 생산성을 높이고, 성능 최적화·UI/UX·데이터 흐름·코드 품질을 함께 개선하는 개발자입니다.

🔗 [Portfolio](https://kimjunha.vercel.app) · [Tech Blog](https://kimjunha.vercel.app/blog) · [GitHub](https://github.com/kimjunha1231)

---

## 🏃 Activities

* Google Developer Groups on Campus (숭실대학교) Member `2024.09 - 2025.09`
* 개발 팀 포키 활동 · 창업 사무실 선정 `2024.03 - 2025.09`
* University MakeUs Challenge (숭실대학교) 수료 `2023.09 - 2024.02`
* 숭실대학교 학생복지위원회 학생복지위원장 `2023.09 - 2025.03`
* 미래와 소프트웨어와 함께하는 꿈찾기 캠프 프로그래밍 STAFF `2024.01`

## 🏆 Awards

* **MSA 기반 Full Stack 개발 전문가 양성 과정 최종 프로젝트 우수상** · 한국인공지능소프트웨어산업협회 `2026.09` · StockFit
* **2025년 한이음 드림업(ICT 멘토링) 공모전 장려상** · 한국정보산업연합회장상 `2025.11`
* **제15회 숭실캡스톤디자인 경진대회 장려상** `2025.10` · Dearfam
* **2024 클라우드 아이디어 공모전 대상** · 부산광역시장상 `2024.12` · Dearfam
* **2024년 한이음 ICT 멘토링 공모전 은상** · 정보통신기획평가원장상 `2024.12` · TITO
* **숭실 발명아이디어 경진대회 최우수상** · 숭실대학교 총장상 `2024.11`

## 🌱 Open Source Contribution

### [dnd-kit #2135 · Track late signal reads across framework adapters](https://github.com/clauderic/dnd-kit/pull/2135) `Merged · 2026.09`

오픈소스 드래그 앤 드롭 라이브러리 [dnd-kit](https://github.com/clauderic/dnd-kit)에서 컴포넌트가 첫 렌더링 이후 새로 읽은 `Signal` 속성을 다음 상태 변경부터 구독하지 못하는 문제를 재현하고 수정했습니다.

* `Proxy`가 기록한 늦은 상태 읽기를 커밋 이후 구독 목록에 반영
* 대상 교체·unmount·Strict Mode에서 구독 정리 보완
* React·Vue·Solid·Svelte adapter 회귀 테스트와 조건부 상태 예제 추가
* build 16개, unit test 150개, framework별 Chromium 회귀 테스트 검증

> 개인 프로젝트 JobSecretary의 칸반보드에서 시작한 관찰을 최소 재현 코드와 테스트로 줄여 라이브러리 수정으로 연결한 기여입니다.

## 🚀 Projects

### StockFit · 현대그린푸드 재고관리 플랫폼 `2026.08`

[FrontEnd](https://github.com/kosa11-final-project/FrontEnd) · [BackEnd](https://github.com/kosa11-final-project/BackEnd)

React·Spring Boot 기반 B2B 재고 운영 플랫폼입니다. 여러 판매 채널과 물류센터의 재고를 SKU 단위로 통합하고, 필터·정렬·수요예측·위험 재고·동기화 상태를 한 화면에서 관리했습니다.

* 최종 프로젝트 **우수상**
* AND 다중 필터 조회 목록 17.99초 관찰 → 726ms 관찰
* production preview Lighthouse Performance 99점, LCP 0.8초 관찰

### Smart Messaging System · AI 통합 메시징 서비스 `2026.07`

[Repository](https://github.com/kosa-second-project/smart-messaging-system)

Spring Boot·Oracle·Redis 기반 메시징 서비스입니다. 고객 조회, Redis Draft 수신자 관리, 링크 추적과 발송·통계 화면을 담당했습니다.

* 고객 목록 API 1.99초 → 265ms
* 고객 정보 API 8.46초 → 350ms
* 메시지 이력 API 5.03초 → 315ms

### 식권대장 KOSA · 교육생 식사 정보 서비스 `2026.06`

[Repository](https://github.com/kimjunha1231/sikdae-kosa) · [Service](https://sikdae-kosa.vercel.app/)

Next.js·Firebase·Vercel Cron으로 송파 IT벤처타워 주변 84개 식당의 메뉴와 가격을 제공하는 개인 프로젝트입니다. 실시간 식당 선택, 룰렛, 게임, K밥상 메뉴 자동 갱신을 구현했습니다.

### JobSecretary · AI 취업 준비 통합 관리 서비스 `2025.11 - 2025.12`

[Repository](https://github.com/kimjunha1231/JobSecretary) · [Project record](https://kimjunha.vercel.app/projects/jobsecretary)

Next.js·TypeScript·Supabase·Gemini 기반 개인 프로젝트입니다. 채용 공고, 지원 현황 칸반보드, 자기소개서, 면접 준비를 하나의 흐름으로 연결했습니다.

* 칸반보드 Profiler 전체 커밋 271회 → 98회
* 영향을 받지 않은 카드 렌더링 표시 약 268~269회 → 0회
* Lighthouse 접근성 80점대 → 95점대

### Dearfam · AI 가족 추억 콘텐츠 서비스 `2024.11 - 2025.09`

[Repository](https://github.com/TEAM-POKIE/Dearfam-FrontEnd)

React·TypeScript·Flutter 기반 가족 추억 앨범 서비스입니다. 프론트엔드 리드로 MVP의 웹 전환, AI 콘텐츠 제작 흐름, 상태 관리와 API 연동을 담당했습니다.

* 2024 클라우드 아이디어 공모전 **대상**
* 제15회 숭실캡스톤디자인 경진대회 **장려상**
* Pre-스타트업 선정 및 창업 사무실 입주

### TITO · LLM 기반 실시간 토론 보조 서비스 `2024.03 - 2024.12`

[Repository](https://github.com/TEAM-POKIE/Tito-FrontEnd)

Flutter·Dart·WebSocket 기반 토론 서비스입니다. 프론트엔드 리드로 인증, 토론 진행, 실시간 채팅·투표, LLM 주제 생성과 논리 코칭을 구현했습니다.

* 2024년 한이음 ICT 멘토링 공모전 **은상**
* One Store·App Store 배포 및 운영

### POPPET · 노약자를 위한 AI 말동무 서비스 `2025.05`

[Repository](https://github.com/gdsc-ssu/poppet-app)

Flutter·Riverpod 기반 음성 대화 서비스입니다. 음성 녹음·업로드·응답 재생, 보호자 설정, 인증과 API 연동을 담당했습니다.

### 여행의 이유 · 여행 코스 공유 커뮤니티 `2024.01 - 2024.02`

[Repository](https://github.com/Here-You/FrontEnd)

React·JavaScript 기반 대규모 팀 프로젝트입니다. 로그인·소셜 로그인과 마이페이지를 담당했습니다.

### SSYUNG · 융합특성화 자유전공학부 커뮤니티 `2021.01 - 2021.03`

[Repository](https://github.com/Convergence-Specialization/CS-Front)

React·JavaScript 기반 학부 커뮤니티입니다. 비대면 환경에서 전공 정보와 선후배 소통을 연결했고, 런칭 초기 실시간 동시 접속자 50명을 달성했습니다.

## 🎖️ Certifications

| 자격증 | 발급처 | 취득일자 |
| :--- | :--- | :--- |
| TOEIC Speaking · IM3 | TOEIC | 2026.06 |
| SQLD | 한국데이터진흥원 | 2026.06 |
| 정보처리기사 | 한국산업인력공단 | 2025.12 |
| MOS Excel Expert 2016 | Microsoft | 2024.06 |

---

## 🛠️ Tech Stack

### Languages

<img src="https://img.shields.io/badge/TypeScript-%233178C6?style=for-the-badge&logo=typescript&logoColor=white"/> <img src="https://img.shields.io/badge/Java-%23007396?style=for-the-badge&logo=openjdk&logoColor=white"/> <img src="https://img.shields.io/badge/JavaScript-%23F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/> <img src="https://img.shields.io/badge/Dart-%230175C2?style=for-the-badge&logo=dart&logoColor=white"/>
<img src="https://img.shields.io/badge/HTML5-%23E34F26?style=for-the-badge&logo=html5&logoColor=white"/> <img src="https://img.shields.io/badge/CSS3-%231572B6?style=for-the-badge&logo=css3&logoColor=white"/>

### Frontend

<img src="https://img.shields.io/badge/React-%2361DAFB?style=for-the-badge&logo=react&logoColor=black"/> <img src="https://img.shields.io/badge/Next.js-%23000000?style=for-the-badge&logo=nextdotjs&logoColor=white"/> <img src="https://img.shields.io/badge/Flutter-%2302569B?style=for-the-badge&logo=flutter&logoColor=white"/>

### Backend & Data

<img src="https://img.shields.io/badge/Spring%20Boot-%236DB33F?style=for-the-badge&logo=springboot&logoColor=white"/> <img src="https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white"/> <img src="https://img.shields.io/badge/Redis-%23DC382D?style=for-the-badge&logo=redis&logoColor=white"/>

### State & Styling

<img src="https://img.shields.io/badge/TanStack%20Query-%23FF4154?style=for-the-badge&logo=reactquery&logoColor=white"/> <img src="https://img.shields.io/badge/Zustand-%23443E38?style=for-the-badge&logo=react&logoColor=white"/> <img src="https://img.shields.io/badge/Tailwind%20CSS-%2306B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white"/> <img src="https://img.shields.io/badge/styled--components-%23DB7093?style=for-the-badge&logo=styledcomponents&logoColor=white"/>

### Services & Tools

<img src="https://img.shields.io/badge/Firebase-%23FFCA28?style=for-the-badge&logo=firebase&logoColor=black"/> <img src="https://img.shields.io/badge/Supabase-%233ECF8E?style=for-the-badge&logo=supabase&logoColor=white"/> <img src="https://img.shields.io/badge/Git-%23F05032?style=for-the-badge&logo=git&logoColor=white"/> <img src="https://img.shields.io/badge/GitHub-%23181717?style=for-the-badge&logo=github&logoColor=white"/> <img src="https://img.shields.io/badge/Sentry-%23362D59?style=for-the-badge&logo=sentry&logoColor=white"/>
