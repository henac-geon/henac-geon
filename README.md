## 🙋‍♂️ 소개 (Introduction)

게임 시스템 설계와 백엔드 개발에 강점을 가진 신입 개발자 제갈건입니다. RPG 게임 '세인트 세이버'에서 팀장을 맡아 전반적인 시스템을 개발했으며, Flutter & Spring Boot 기반의 주류 AI 추천 플랫폼 등 다양한 프로젝트를 진행했습니다. 팀장을 맡아 프로젝트를 진행한 경험이 많아 커뮤니케이션을 중요하게 여기며 노력하는 개발자입니다. 몰입감 있는 게임을 위해 기술과 감성을 함께 고민하고 있습니다.

-----

## 💻 기술 스택 (Tech Stack)

  * **언어 및 프레임워크:** Java, C++, Python, Dart, Lua, Spring Boot, Flutter
  * **데이터베이스:** MySQL, MongoDB, Pinecone
  * **협업 및 버전 관리:** Slack, GitHub, Git
  * **클라우드/기타:** Colab, Notion, AI, STOMP, RAG 등 최신 기술에 관심이 많아 게임에 접목하려는 시도를 이어가고 있습니다.
  * **게임 개발 상세:**
      * **Lua 스크립팅:** '세인트 세이버' 프로젝트에서 Lua 스크립트를 사용하여 플레이어의 행동(점프, 이동, 공격) 및 몬스터와의 충돌 감지 로직을 구현했습니다.
      * **데이터 핸들링:** CSV 파일을 활용하여 몬스터의 스탯(HP, 방어력 등)과 같은 게임 데이터를 관리하는 시스템을 구축했습니다.
      * **백엔드/서버 로직:** 사용자의 게임 데이터(플레이어 정보, 인벤토리, 키 설정 등)를 저장하고 관리하는 서버 핸들러 로직을 개발했습니다.

-----

## 📁 경력 및 프로젝트 (Experience & Projects)

### 엘릭서 스튜디오 | 인턴 (2025.01\~2025.02)

  * 게임 개발 R\&D 인턴으로 근무했습니다.

### 세인트 세이버 (2022.08 \~ 현재)

  * 메이플월드에서 진행한 1인 RPG 프로젝트입니다.
  * **기술 스택:** Lua
  * **담당 업무:** 플레이어의 행동을 관리하는 `PlayerActionComponent`를 개발하여 점프, 이동, 공격, 대시 등의 액션을 구현했습니다. 또한 몬스터의 충돌 검사 로직을 구현하여 몬스터와의 상호작용을 처리했습니다.
  * **깃허브 링크:** [https://github.com/henac-geon/saintsavior](https://www.google.com/search?q=https://github.com/henac-geon/saintsavior)
  * **시연 영상:** [https://youtu.be/wfPhetOps5M](https://www.google.com/search?q=https://youtu.be/wfPhetOps5M)

### ALChive (2024.09 \~ 2025.06)

  * Flutter & Spring Boot 기반의 캡스톤 디자인 프로젝트입니다.
  * **담당 업무:** 주류 AI 추천 플랫폼의 백엔드 시스템을 개발했습니다.
  * **시연 영상:** [https://youtu.be/RnfwJ3rg4Hs](https://www.google.com/search?q=https://youtu.be/RnfwJ3rg4Hs)

#### ⏱️ 프로젝트 기간

  * 2024.09 \~ 2025.06 (캡스톤 디자인 프로젝트)

#### ✨ 프로젝트 개요

ALChive AI 서버는 주류 AI 추천 플랫폼의 백엔드 시스템으로, 사용자 질문에 응답하고 맞춤형 칵테일 레시피를 제공하는 AI 챗봇 기능을 담당합니다. FastAPI를 기반으로 RESTful API를 구축했으며, OpenAI의 GPT 모델과 벡터 데이터베이스인 Pinecone을 활용하여 검색 증강 생성(RAG) 기술을 적용했습니다. AI 챗봇은 '알프레도'라는 이름의 친절한 바텐더 페르소나를 가지고 사용자에게 응답합니다.

-----

#### 🛠️ 주요 기술 스택

  * **언어 및 프레임워크:** Python (FastAPI, Uvicorn)
  * **AI & 벡터 DB:** OpenAI (GPT 모델), Pinecone
  * **데이터:** JSONL, JSON 파일 (시나리오, 전통주 문서)

-----

#### 🚀 주요 기능 및 구현 내용

  * **AI 챗봇 기능:** 일반적인 주류 질문에 대한 응답과 사용자가 선택한 재료를 기반으로 한 맞춤형 칵테일 레시피를 제공합니다.
  * **RAG(검색 증강 생성):** 사용자의 프롬프트와 관련된 예상 시나리오 및 전통주 정보를 Pinecone 벡터 데이터베이스에서 검색하여 GPT 모델의 답변을 보강합니다.
  * **맞춤형 칵테일 추천:** 전통주 ID와 재료 목록을 입력받아 해당 전통주 정보를 불러온 후, 이를 기반으로 칵테일 레시피, 비율, 만드는 방법, 예상 도수 및 어울리는 잔(`둥근와인잔`, `삼각칵테일잔`, `양은주전자`, `원통글라스`, `스파클링 와인잔`, `청주잔` 중 하나)을 추천하는 로직을 구현했습니다.
  * **자동화된 데이터 업로드:** 칵테일 시나리오 및 전통주 정보를 Pinecone에 자동으로 업로드하는 스크립트를 개발하여 AI 모델 학습 및 데이터 관리를 용이하게 했습니다.
  * **CI/CD 파이프라인:** GitHub Actions를 활용한 CI/CD 파이프라인을 구축하여 자동화된 테스트 및 배포가 가능합니다.

-----

#### 🔗 링크

  * **GitHub 리포지토리:** [https://github.com/henac-geon/alchive\_ai\_server](https://www.google.com/search?q=https://github.com/henac-geon/alchive_ai_server)
  * **시연 영상:** [https://youtu.be/RnfwJ3rg4Hs](https://www.google.com/search?q=https://youtu.be/RnfwJ3rg4Hs)

-----

#### ✨ 프로젝트 개요

ALChive 백엔드 서버는 주류 AI 추천 플랫폼의 핵심 시스템으로, 사용자에게 주류 및 칵테일 정보를 제공하고, 커뮤니티 기능, 실시간 채팅, 그리고 AI 서버와의 연동을 담당합니다. **Spring Boot**와 **Gradle** 기반으로 개발되었으며, **마이크로서비스 아키텍처**를 활용하여 AI 서버와 분리된 구조를 가집니다.

-----

#### 🛠️ 기술 스택

  * **백엔드 프레임워크:** Java, Spring Boot, Spring Security, Spring Data JPA, STOMP
  * **데이터베이스:** MySQL
  * **인증 및 보안:** Keycloak, OAuth 2.0, JWT
  * **배포 및 운영:** Docker, GitHub Actions를 활용한 CI/CD
  * **서버 통신:** RESTful API, WebSocket (STOMP)

-----

#### 🚀 주요 기능 및 구현 내용

  * **주류 정보 API:** 전통주 및 칵테일 정보를 관리하며, 사용자 요청에 따라 검색 및 상세 정보를 제공하는 RESTful API를 구현했습니다.
  * **사용자 인증 시스템:** **Keycloak**을 연동하여 **OAuth 2.0** 기반의 사용자 인증 및 권한 관리를 구축했습니다. \*\*JWT(JSON Web Token)\*\*를 활용해 안전한 사용자 세션 관리를 제공합니다.
  * **실시간 채팅 서비스:** **STOMP** 프로토콜을 활용한 **WebSocket** 통신으로 실시간 채팅 기능을 구현했습니다. 이를 통해 챗봇(AI)과의 대화를 실시간으로 주고받을 수 있습니다.
  * **AI 서버 연동:** `SuggestController`에서 `WebClient`를 사용해 별도로 구축된 AI 서버에 HTTP 요청을 보내고 응답을 처리합니다. 이는 백엔드와 AI 로직을 분리한 **마이크로서비스 아키텍처**의 핵심입니다.
  * **커뮤니티 기능:** 댓글과 좋아요 기능을 구현하여 사용자 간의 상호작용을 지원합니다.
  * **CI/CD 파이프라인:** **GitHub Actions**를 활용하여 빌드, 테스트, **Docker** 이미지 생성 및 배포를 자동화하는 CI/CD 파이프라인을 구축했습니다.

-----

#### 🔗 링크

  * **GitHub 리포지토리:** [https://github.com/henac-geon/alchive\_back](https://www.google.com/search?q=https://github.com/henac-geon/alchive_back)
  * **시연 영상:** [https://youtu.be/RnfwJ3rg4Hs](https://www.google.com/search?q=https://youtu.be/RnfwJ3rg4Hs)


### ALChive (AI 주류 추천 플랫폼)

-----

#### ⏱️ 프로젝트 기간

  * 2024.09 \~ 2025.06 (캡스톤 디자인 프로젝트)

#### 📝 프로젝트 개요

`ALChive`는 주류에 대한 정보 제공, AI 기반 칵테일 추천, 그리고 커뮤니티 기능을 통합한 모바일 애플리케이션입니다. Flutter를 사용하여 프론트엔드를 구축하고, Spring Boot 기반의 백엔드와 FastAPI 기반의 AI 서버를 마이크로서비스 아키텍처로 분리하여 개발했습니다. 실시간 채팅, 커뮤니티, 맞춤형 칵테일 추천 등 다양한 기능을 제공합니다.

#### 🛠️ 기술 스택

  * **프론트엔드:** Dart, Flutter, Riverpod, STOMP
  * **백엔드:** Java, Spring Boot, Spring Security, MySQL
  * **AI 서버:** Python, FastAPI, OpenAI, Pinecone (RAG)
  * **데이터베이스:** MySQL, Firebase Firestore
  * **인증 및 배포:** Firebase Auth, Keycloak, Docker, GitHub Actions

#### 🚀 주요 기능 및 상세 구현

  * **모바일 클라이언트 (Flutter):** 사용자 친화적인 UI/UX를 제공하는 모바일 앱을 Flutter로 개발했습니다. 상태 관리를 위해 `Riverpod`를 사용했으며, 백엔드 및 AI 서버와 연동하여 주류 정보 조회, 칵테일 추천, 실시간 채팅, 커뮤니티 등의 기능을 구현했습니다.
  * **백엔드 서버 (Spring Boot):**
      * **RESTful API:** 주류 정보, 커뮤니티(댓글/좋아요) 등 다양한 기능을 처리하는 RESTful API를 구축했습니다.
      * **인증:** Keycloak을 활용하여 OAuth 2.0 기반의 사용자 인증 시스템을 구현했습니다.
      * **실시간 통신:** STOMP 프로토콜을 사용한 WebSocket 통신을 통해 실시간 채팅 기능을 구현하여 AI 챗봇과의 원활한 대화를 지원합니다.
  * **AI 서버 (FastAPI):**
      * **RAG(검색 증강 생성):** OpenAI의 GPT 모델과 Pinecone 벡터 데이터베이스를 연동하여 RAG 시스템을 구축했습니다. 사용자 질문에 대해 정확한 전통주 정보를 검색하고, 예상 시나리오를 참고하여 답변의 품질을 높였습니다.
      * **맞춤형 칵테일 추천:** 사용자가 선택한 재료와 전통주 정보를 바탕으로 칵테일 레시피와 어울리는 잔을 추천하는 로직을 구현했습니다.
  * **CI/CD:** GitHub Actions를 사용하여 프론트, 백엔드, AI 서버의 빌드, 테스트, 배포를 자동화하는 파이프라인을 구축했습니다.

#### 🔗 링크

  * **GitHub 리포지토리:** [https://github.com/henac-geon/alchive\_front](https://www.google.com/search?q=https://github.com/henac-geon/alchive_front), [https://github.com/henac-geon/alchive\_back](https://www.google.com/search?q=https://github.com/henac-geon/alchive_back), [https://github.com/henac-geon/alchive\_ai\_server](https://www.google.com/search?q=https://github.com/henac-geon/alchive_ai_server)
  * **시연 영상:** [https://youtu.be/RnfwJ3rg4Hs](https://www.google.com/search?q=https://youtu.be/RnfwJ3rg4Hs)

### Project BS: 쿠르드의 마법서점 (krud's Magic book Store) 📚

  * **기간:** 2025.03 \~ 2025.06
  * **기술 스택:** C++14 이상, CMake, PlantUML, Chat-GPT API
  * **요약:** 책 대여와 NPC 상호작용, 미니게임을 중심으로 한 **텍스트 기반 콘솔 게임**입니다. 객체지향 설계와 UML 기반으로 설계되었으며, 하루 단위 루프로 진행되는 점수, 레벨, 보상 시스템을 갖추고 있습니다.
  * **수상 경력:** 마이크로디그리 EXPO에서 최우수상을 수상했습니다.

#### 🔎 주요 기술 및 구현 내용

  * **📖 Book System:** 책의 장르, 분위기 속성과 손상, 수리, 상태 구분이 가능한 구조로 설계되었으며, 팩토리 패턴을 통해 책을 자동 생성합니다.
  * **🧙‍♂️ NPC System:** NPC의 선호 장르에 기반한 책 요청 시스템과 피해 보상 시스템을 구현했습니다. NPC 유형별로 행동 다형성을 지원하여 게임의 상호작용을 풍부하게 만들었습니다.
  * **🧠 Game Loop & Manager:** `GameManager`를 통해 하루 단위로 게임을 진행하고, 사용자/관리자 모드 전환, 점수, 레벨 시스템을 통합 관리합니다.
  * **🎮 MiniGame System:** `MiniGame` 인터페이스를 기반으로 다양한 게임 방식(타자 게임, 퍼즐 등)을 도입할 수 있도록 확장 가능한 구조로 설계했습니다.
  * **💬 Chat-GPT API 활용:** Chat-GPT API를 활용하여 고객 다이얼로그 자동 생성 시스템을 구축하여 NPC와의 대화가 더욱 자연스럽고 다양하도록 구현했습니다.

#### 🔗 링크

  * **GitHub 리포지토리:** [https://github.com/henac-geon/Project-BS](https://github.com/henac-geon/Project-BS)
  * **시연 영상:**
      * [cite\_start][https://youtu.be/B90QArCYViQ](https://www.google.com/search?q=https://youtu.be/B90QArCYViQ)
      * [https://youtu.be/B9qQArcYyiQ](https://youtu.be/B9qQArcYyiQ)

-----

## 🎓 교육 및 자격 (Education & Certifications)

  * **계명대학교 컴퓨터공학과:** (2020\~2026), 학점: 4.08/4.5
  * **D5 청년인재 혁신아카데미:** 추가 교육을 수료했습니다.
  * **KT 그룹창조인대장학생:** (2022\~2025)
  * **컴퓨터활용능력 2급:** 대한상공회의소 (2024)
  * **정보처리기사:** 과학기술정보통신부 (2025, 예정)
  * **SQLD:** (2025, 예정)
  * **주류 데이터를 활용한 AI모델 학습에 대한 연구:** 한국 정보 기술 학회 하계 학술 대회 및 대학생 논문 경진 대회 논문 채택 (2022 \~ 2025)
