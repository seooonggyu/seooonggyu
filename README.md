<div>
  <h2>안녕하세요! 백엔드와 AI, 두 레이어를 함께 보며<br>새로운 가치를 만들어가는 개발자 김성규입니다.</h2>
  <p>
    <a href="mailto:seooonggyu@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white"/></a>
    <!-- <a href="mailto:22100110@handong.ac.kr"><img src="https://img.shields.io/badge/School_Email-0052CC?style=flat-square&logo=mail&logoColor=white"/></a>
    <a href="https://github.com/seooonggyu"><img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white"/></a> -->
  </p>
  <p>
    <a href="https://github.com/seooonggyu">
      <img src="https://github-readme-stats.vercel.app/api?username=seooonggyu&show_icons=true&theme=default" alt="GitHub Stats" />
    </a>
    [![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=seooonggyu&langs_count=4&layout=compact)](https://github.com/anuraghazra/github-readme-stats)
    <a href="https://github.com/seooonggyu">
      <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=seooonggyu&layout=compact&theme=default" alt="Top Languages" />
    </a>
  </p>
</div>
---

### 🛠 Tech Stack

**Backend**<br>
![Java](https://img.shields.io/badge/java-007396?style=for-the-badge&logo=java&logoColor=white)
![Spring Boot](https://img.shields.io/badge/springboot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white)
![JPA](https://img.shields.io/badge/JPA-59666C?style=for-the-badge&logo=hibernate&logoColor=white)
![MyBatis](https://img.shields.io/badge/MyBatis-000000?style=for-the-badge&logo=mybatis&logoColor=white)

**AI / RAG**<br>
![Python](https://img.shields.io/badge/python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-121212?style=for-the-badge&logo=langchain&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white)
![Chroma](https://img.shields.io/badge/Chroma-FF6C37?style=for-the-badge&logo=chroma&logoColor=white)

**Infra & Database**<br>
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=MySQL&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)

---

### 🚀 Projects

#### 1. 인계점 — 챗봇을 활용한 인수인계 플랫폼
기존 일회성 인수인계의 '지식 단절'과 '문서 파편화'를 해결하는 지속형 온보딩 플랫폼 (2025.09 - 진행 중)
* **Backend Repository**: [capstone_backend](https://github.com/seooonggyu/capstone_backend.git)
* **Chatbot Repository**: [capstone_chatbot](https://github.com/seooonggyu/capstone_chatbot.git)
* **Key Features**:
    * Spring Boot 백엔드와 LangChain RAG를 연동한 문서 기반 질의응답 시스템
    * 단일 VectorDB(Chroma)에서 메타데이터 필터링을 통한 사용자/스페이스별 데이터 격리 구현 (기밀 유출 방지)
    * 인계자 → 인수자 → 관리자로 이어지는 3단계 순차 전자 서명 및 타임스탬프 결재 구현
    * Ollama를 활용한 오픈소스 LLM(Gemma 2) 로컬 서빙

#### 2. foundit — 교내 분실물 찾기 서비스 (소프트웨어 공학)
교내 분실물 등록·검색 및 사용자 간 매칭/채팅을 지원하는 서비스 (2026.03 - 진행 중)
* **Backend Repository**: [software_engineering](https://github.com/seooonggyu/software_engineering.git)
* **Key Features**:
    * Spring Boot 기반 분실물 등록 및 검색 API 구현
    * 실시간 사용자 간 채팅 기능 구현
    * (AI 파트 연동) 이미지 유사도 분석을 통한 분실물 매칭 로직 적용

#### 3. GRP 타지키스탄 관광 안내 챗봇 (팀 프로젝트)
인프라 미비 환경에서 로컬 LLM 기반 RAG를 구축한 관광 안내 챗봇 (2025.09 - 2026.02)
* **Key Features**:
    * 할루시네이션(Hallucination) 유형을 4가지로 직접 분류하고 정량 평가 기준 고안
    * GPU 서버가 없는 환경을 고려하여 모델과 프롬프트 조합의 최적화 진행

#### 4. Spring Boot Starter Template (기본 스프링 프로젝트)
새로운 Spring Boot 프로젝트를 시작할 때 기본 뼈대로 사용할 수 있는 초기 보일러플레이트 (Boilerplate)
* **Repository**: [sg.spring](https://github.com/seooonggyu/sg.spring.git)
* **Key Features**:
    * **사용자 인증 및 권한**: Spring Security + JWT 기반 인증 (Access/Refresh Token), 역할(Role) 및 상세 권한 관리 시스템
    * **데이터베이스 혼용**: 직관적인 CRUD는 Spring Data JPA, 복잡한 동적 쿼리는 MyBatis를 활용한 하이브리드 아키텍처
    * **하이브리드 렌더링**: Thymeleaf 기반의 일반 페이지 렌더링(Controller)과 JSON 기반 API(RestController) 환경 동시 세팅

---

### 🏆 Experience & Activities

**🔬 학부 연구실 Lab Insight** (활동 중)
> "생각을 행동으로, 혁신을 결과로" <br>
> 백엔드 개발과 인공지능 기술을 활용하여 현실의 문제를 창의적으로 해결하는 연구실입니다. 새로운 기술을 연구하고, 효율적이고 확장 가능한 시스템을 만들며 함께 성장하는 협업을 추구합니다.

**🛡️ 정보보안동아리 GHOST** (2024.03 - 2024.12, 2026.03 - 진행 중)
- 백엔드 개발자로서 필수적인 시스템 보안 및 네트워크 지식 습득

**🎓 기타 활동 및 수상 내역**
- **CJ 미래세대 기후행동 오픈 이노베이션**: 전국 Top 6 본선 진출 (2026.01)
- **ACM-ICPC 교내 예선**: 은상 (2025.11)
- **SW Festival 스마트 SW 공모전**: 장려상 (2024.11)
- **교내 프로그래밍 스튜디오 및 코딩 아워 TA** (2025.03 - 2025.11)
- **총학생회 문화국** (2021.03 - 2021.06)
