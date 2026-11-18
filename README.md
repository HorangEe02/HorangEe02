## 박준영 · AI 개발자

챗봇, LLM 애플리케이션, AI 에이전트를 만들고 배포합니다.
지금은 레몬헬스케어 AI Agent 파트에서 건강의신 앱의 AI 건강상담 챗봇 ‘레모니’를 만들고 있고,
개인적으로는 식단·운동·걷기 앱 세 개를 하나로 묶은 웰니스 AI 에이전트를 만들고 있습니다.

🔗 **Portfolio** · https://junyeong-portfolio-one.vercel.app

### Now building · 웰니스 AI 에이전트

식단·혈당·근력·걷기·영양제 기록을 보고 답하는 AI 코치. LangGraph.js로 안전 판정 → 라우터 → 도메인 노드 7개 → 코치를 잇고, 숫자는 원래 앱의 계산 함수가 만들며 모델(LFM3-1.7B, d1-2B)은 PC 안에서만 돌립니다. 안드로이드 앱 + WSL 서버, 앱 화면도 직접 디자인했습니다. (개발 중 · [상세](https://junyeong-portfolio-one.vercel.app/projects/wellness-agent/))

<img src="assets/wellness-agent.png" alt="웰니스 AI 에이전트 앱 화면: AI 코치, 홈, 산책" width="720">

### Selected Work

| 프로젝트 | 내용 | 역할 | 링크 |
|---|---|---|---|
| **웰니스 AI 에이전트** | 앱 세 개를 LangGraph로 묶은 로컬 AI 코치. 숫자는 도구가, 설명은 로컬 LLM이 | 개인 (설계·개발·앱 디자인, 진행 중) | [상세](https://junyeong-portfolio-one.vercel.app/projects/wellness-agent/) |
| **레모니 · AI 건강상담 챗봇** | 식단·영양·걷기·영양제 질문에 답하는 건강상담 챗봇. 위기 대응은 규칙이, 문장은 로컬 LLM이 맡는 구조 | 레몬헬스케어 수습 계약직 (설계·개발·평가) | [상세](https://junyeong-portfolio-one.vercel.app/projects/lemoni-chatbot/) |
| **KBO 원정 응원 플래너** | 경기 하나를 고르면 티켓·교통·맛집·숙소·관광을 Gemini Tool Calling 챗봇이 한 번에 구성 | 팀 (KDT 12기) | [코드](https://github.com/HorangEe02/KNU_KDT_12th/tree/main/Phase12) |
| **AJIN Compliance** 🏆 | 직원 649명의 6개 업무를 한 화면에서 처리하는 온프레미스 제조 AI 통합 콘솔 | 팀장 (Backend·LLM Router·Infra) | [코드](https://github.com/HorangEe02/Project_yeong/tree/main/04_AJIN) · [데모](https://ajin-ai-assistant-frontend.vercel.app/showcase) |
| **직장인 점심 추천 AI** | 날씨·영양·팀 선호·음식점 4축 추천 파이프라인 + NLP 7모듈 + RAG 챗봇 | 팀 (KDT 12기) | [코드](https://github.com/HorangEe02/KNU_KDT_12th/tree/main/Phase13%2614) |
| **Lemon AID** | 영양제 라벨을 OCR·로컬 LLM으로 구조화하고 KDRIs 기준으로 해석하는 헬스케어 앱 | 팀 · 영양제 분석 파트 | [코드](https://github.com/Lemon-Aid-KDT/Lemon-sin) |
| **헬창지피티** | 자연어 한 문장을 프로필 분석→식단→운동 루틴→피드백으로 잇는 로컬 LLM 코칭 파이프라인 | 팀 (KDT 12기) | [코드](https://github.com/HorangEe02/KNU_KDT_12th/tree/main/Phase11) |
| **CAD Vision** | 이미지·텍스트·구조 3채널 멀티모달 RAG로 도면 검색을 1분 이내로 줄인 검색 엔진 | 개인 | [코드](https://github.com/HorangEe02/Project_yeong/tree/main/01_CAD) |

### Awards

- 🏆 **2026** KNU×아진산업 제3회 실리 AX 기술전(AX 부문) 인기상 · AJIN Compliance
- 🏆 **2025** 계명대학교 캡스톤디자인 우수상 · 대학생 307명 설문 기반 통계분석

### Stack

`LangGraph` `LlamaIndex` `Ollama` `Gemma` `Qwen` `Gemini` `ChromaDB` `bge-m3` `PaddleOCR` `PyTorch` `FastAPI` `PostgreSQL` `Next.js` `React` `Docker`

### Background

계명대학교 통계학과 · KDT 12기 수료 · ADsP · SAS Base Programming · Google AI Essentials
