<img width="1200" height="300" alt="forink_preview (2)" src="https://github.com/user-attachments/assets/f15c10f3-aef5-40de-984d-594fbeba7e0d" />

### 1. 프로젝트 소개
#### 1.1. 개발배경 및 필요성
<pre><i><b>"기숙사 위치를 물었지만 버디는 '모른다'고 답했고,
병원 위치를 물었을 땐 카카오톡 계정까지 차단당했습니다."</b></i></pre>
<p align='right'><a href='https://channelpnu.pusan.ac.kr/news/articleView.html?idxno=33110'>- 2023년 5월, 채널 PNU 기사 中</a></p>

한 외국인 유학생이 겪은 이 사례는 부산에 거주하는 외국인, 더 넓은 범위에서는 한국에 거주하는 외국인들이 마주한 현실을 상징적으로 보여주고 있어요. 정책적 지원 확대에도 불구하고, 이들은 여전히 보이지 않는 벽 앞에서 좌절하고 있어요.

---

<details>
  <summary>2023년 부산 외국인 주민 생활 실태조사로도 증명해볼 수 있어요</summary>
  <div markdown="1">
    <p align='right'><a href='https://www.bgli.re.kr/kor/CMS/Board/Board.do?mCode=MN091&page=2&mode=view&mgr_seq=20&board_seq=22645'>👉 실태조사 전문 보기</a></p>
    <p>부산여성가족과평생교육진흥원의「2023년 부산 외국인 주민 생활 실태조사」는 이 문제를 데이터로 증명하고 있어요.</p>
    <ul>
      <li>경제 활동 단절: <b>26.1%</b>가 '서툰 한국어' 때문에 경제활동을 못 하고 있음</li>
      <li>주거 정보 불평등: 집을 구할 때 <b>'정보 부족(29.8%)'</b>, '한국어로만 된 계약 설명(28.5%)' 등 언어와 정보 격차로 인한 어려움을 겪고 있음</li>
    </ul>
  </div>
</details>

---

기존의 공공 서비스는 오프라인 중심이거나 제한적인 다국어 지원에 그쳐, 외국인들이 원하는 시간에, 자국어로, 실시간으로 도움을 받기에는 한계가 명확해요.

## 결론적으로, 외국인 주민들은 다음과 같은 복합적인 문제에 직면해 있어요!
### `🤯 복잡한 행정 절차`
### `🗣️ 높은 언어 장벽`
### `❓ 부족한 생활 정보`
### `😥 지역 사회와의 단절`

<br>

#### 1.2. 개발 목표 및 주요 내용
본 프로젝트는 부산에 거주하는 외국인 주민들이 겪는 정보 비대칭, 언어 장벽, 적응의 어려움 등의 문제를 해결하는 것을 최우선 목표로 해요. 이를 위해 다음과 같은 세부 개발 목표를 설정했어요.

| 목표 | 핵심 기능 |
| :---: | :-- |
| **AI 기반 맞춤형 정착 로드맵** | 사용자의 **진단 결과**를 바탕으로 **개인에게 최적화**된 정착 로드맵을 자동 생성해요. |
| **신뢰 기반 가이드 생태계 조성** | 한국에 거주하고 있거나 정착해있는 주민이 '가이드'가 되어 신규 주민을 돕는 **선순환 가이드 시스템**을 구축해요. |
| **실시간 소통 및 정보 제공** | RAG 기술을 적용한 **AI 챗봇**이 24시간 개인화된 답변을 제공하여 정보 격차를 해소해요. |
| **사용자 참여를 통한 능동적 정착** | 로드맵 수행 등 활동에 **포인트**를 보상하여 자신의 정착 과정을 주도적으로 이끌도록 동기부여해요. |

#### 1.3. 세부내용
## 🗺️ AI 기반 개인 맞춤형 정착 로드맵

<img width="13161" height="832" alt="Group 71" src="https://github.com/user-attachments/assets/19a84923-5967-4305-8ef3-123449825fe5" />

사용자가 최초 가입 시 약 20개 문항의 진단 검사(체류 목적, 언어 수준 등)를 완료하면, AI가 그 결과를 분석하여 **개인에게 최적화된 로드맵**을 자동 생성해요.
- _**시각적 진행률**_: '행정/거주/언어/경력' 등 타입별 로드맵의 진행률(%)을 한눈에 파악할 수 있어요.
- _**체계적인 과제 관리**_:  각 로드맵은 상세 과제 목록으로 구성되며, 완료 시 체크 아이콘(✅)으로 구분되어 성취감을 제공해요.
- **_피드백 기반 보상_**: 과제 완료 후 피드백을 제출하면 **포인트**가 지급되며, 이는 '가이드 매칭' 등 서비스 내에서 화폐처럼 사용할 수 있어요.

## 🛡️ 신뢰 기반의 가이드 매칭 및 양성 시스템
정보만으로 해결할 수 없는 실질적인 어려움을 '사람'을 통해 해결해요.
- _**가이드 탐색 및 매칭**_: 사용자는 언어, 전문 분야 등 원하는 조건으로 인증된 가이드를 검색하고 '매칭 요청'을 보낼 수 있어요.
- **_체계적인 가이드 양성_**: 가이드가 되고자 하는 지원자는 '예비 가이드'로서 전용 로드맵을 수행하고, 전문 가이드들의 평가를 거쳐 정식 가이드로 승격돼요. 이 모든 과정은 투명하게 관리되어 시스템의 신뢰도를 높일 수 있어요.

## 🤖 RAG 기반 AI 챗봇 (Fori)
사용자 데이터를 기억하는 똑똑한 개인 비서 Fori가 24시간 대기 중이에요!
- _**개인화된 답변**_: 사용자의 진단 결과, 로드맵 진행 상황을 종합하여 가장 적절한 답변을 제공해요.
- _**환각 현상 방지**_: RAG DB에 없는 정보에 대해서는 '알 수 없는 정보'라고 명확히 답변하여 잘못된 정보 전달을 방지해요.
_**다국어 지원**_: 사용자의 언어 설정에 맞춰 다국어로 소통해요.

#### 1.4. 기존 서비스 대비 차별성
본 프로젝트는 기존 공공 서비스의 한계를 넘어, 실질적인 실행을 돕는 데 집중하여 다음과 같은 5가지 핵심 차별성을 가지기도 해요 🌠
| 구분 | 기존 방식에서 아쉬운 점 | ✨ 우리의 해결책 |
| :---: | :-- | :-- |
| **정보 제공 방식** | 사용자가 직접 본인에게 맞는 정보를 찾아야 하는 파편화된 정보 | `AI 진단`을 통해 개인에게 최적화된 **자동 맞춤형 로드맵** 제공 |
| **실행 관리** | 정보만 제공할 뿐, 사용자가 이행했는지 과정을 추적할 수 없음 | `체크리스트`와 `진행률 시각화`로 정착의 **모든 과정을 관리** |
| **문제 해결** | 비대면·정보 중심의 일방향 소통 | `블록체인으로 인증된 가이드`와의 **신뢰 기반 1:1 매칭** |
| **동기 부여** | 사용자의 의지에만 의존하여 이탈률이 높음 | `포인트 보상 시스템`을 통해 **지속적인 참여와 완주를 유도** |
| **정보의 범위** | 전국 단위의 일반적인 정보 | 부산의 행정 지침, 지역 커뮤니티 등 지역 특화 정보 지원 |

#### 1.5. 사회적가치 도입 계획
현재로써 부산시의 ‘글로벌 허브 도시 전략’ 및 ‘외국인 주민 사회통합 지원계획’에 발맞춰, 다음과 같은 사회적 가치를 실현하고자 해요. (추후에 더 넓은 범위로 확장할 수 있을 거예요!)
```
외국인의 초기 정착 실패율 감소 및 행정 이행률 제고
```
```
공공 정보 비대칭 해소 및 생활 효율성 증대
```
```
지역 주민과 외국인 간 상호 작용을 통한 사회통합 촉진
```
<p align='right'><b><i>궁극적으로는 각 지역이 외국인 지원에 대한 도시 경쟁력을 강화하고, 다양한 문화가 공존하는 열린 도시로 나아가는 데 기여하는 것을 목표로 하고 있어요 ‼️</i></b></p>

### 2. 상세설계
#### 2.1. 시스템 구성도
<img width="14784" height="11900" alt="service_archi_diagram" src="https://github.com/user-attachments/assets/bb1ed067-59e4-445a-90fc-ee34bb5a4920" />

#### 2.1. 사용 기술
##### Frontend
![React](https://img.shields.io/badge/React%2019.1.0-20232a?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript%205.8.3-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/Vite%207.0.0-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS%204.1.11-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)
![React Query](https://img.shields.io/badge/-React%20Query%205.83.0-FF4154?style=for-the-badge&logo=react%20query&logoColor=white)
  <details>
    <summary>기타 기술스택</summary>
    <div markdown="1">
      <code>zustand 5.0.7</code>
      <code>i18next 25.3.2</code>
      <code>reactflow 11.11.4</code>
      <code>Google Translate API</code>
    </div>
  </details>

##### Backend & DB
![Spring](https://img.shields.io/badge/Spring%206.2.8-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL%209.2.0-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white)
  <details>
    <summary>기타 기술스택</summary>
    <div markdown="1">
      <code>Spring Data JPA 3.5.1</code>
      <code>Spring Security 6.5.1</code>
      <code>Google OAuth Client 1.39.0</code>
      <code>JJWT 0.11.5</code>
      <code>Web3j 4.14.0</code>
      <code>JDK 21</code>
    </div>
  </details>

##### AI
![Python](https://img.shields.io/badge/python%203.13-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi)
  <details>
    <summary>기타 기술스택</summary>
    <div markdown="1">
      <code>Pinecone Vector Database</code>
      <code>Donut Parsing opensource model</code>
      <code>Upstage document-parsing API</code>
      <code>Upstage solar-llm API</code>
      <code>LangChain</code>
    </div>
  </details>

##### Blockchain
![Solidity](https://img.shields.io/badge/Solidity%200.8.29-%23363636.svg?style=for-the-badge&logo=solidity&logoColor=white)
  <details>
    <summary>기타 기술스택</summary>
    <div markdown="1">
      <code>Foundry</code>
    </div>
  </details>

### 3. 개발결과
#### 3.1. 전체시스템 흐름도
  <details>
    <summary>토글을 클릭하여 간단한 플로우 차트를 확인해보세요.</summary>
      <img width="771" height="1011" alt="forink drawio" src="https://github.com/user-attachments/assets/0e63eeeb-131a-4c62-9228-cfa7d13eeea2" />
  </details>

- ERD
  <img width="723" height="882" alt="forink db erd" src="https://github.com/user-attachments/assets/937b9be7-69b8-4642-aca8-abceb21eefa1" />

#### 3.2. 기능설명
`진단 검사 페이지`
- 맞춤형 정착 서비스를 원하는 일반 사용자라면, 회원가입 후 진단검사 페이지로 이동해요.
- 진단 검사는 약 20개의 문항으로 이루어져 있으며, 각 항목을 클릭하면 다음 항목으로 이동해요.
- 진단 검사 결과는 **개별 맞춤 로드맵 생성 데이터**로 활용돼요.

`로드맵 전체 조회 페이지`
- 진단 검사를 바탕으로 생성된 로드맵을 확인할 수 있어요.
  - 진단 검사 결과가 없다면 로드맵 생성이 어려워요.
- 각 로드맵 별 진행 사항을 진행 바(Progress Bar)로 확인할 수 있어요.
- 제공받을 수 있는 서비스의 타입을 다음과 같아요.
  - *나만의 행정 로드맵*: 비자, 건강 보험 및 등록에 대한 단계별 가이드를 받을 수 있어요.
  - *나만의 거주 로드맵*: 정착을 하기 위해 필요한 생활 정보들을 알 수 있어요.
  - *나만의 언어 로드맵*: 한국어 기초를 배워 정착하는 데 도움을 받을 수 있어요.
  - *나만의 경력 로드맵*: 한국에서 구직할 수 있도록 리소스와 가이드를 제공해요.
 
`로드맵 타입별 조회 페이지`
- 타입별 로드맵을 클릭하면 **맞춤 로드맵** 내역을 확인할 수 있어요.
- 로드맵의 각 항목은, 세부 항목 완료 후 피드백을 작성하면 초록색 체크 표시와 함께 완료처리가 돼요. 또한, 진행률에 즉시 반영 돼요.

`로드맵 타입별 상세 항목 조회 페이지`
- 로드맵의 각 항목을 클릭하면 상세 항목을 조회할 수 있어요.
- 사용자들은 로드맵을 수행하고 체크박스를 클릭해요. (사용자 실제 이행 유도)
- 모두 체크하면 상세 항목별 피드백을 제출할 수 있어요.
  - 상세 항목 피드백은 좋아요/별로예요 중 선택 가능하며, 완료 시 **5 point**가 지급돼요.
- 모든 상세 항목을 완료하면 항목의 전체 피드백을 제출할 수 있어요.
  - 항목 전체 피드백은 서술식으로 진행되며, 완료 시 **10 point**가 지급돼요.
- 포인트는 가이드 매칭 시 사용할 수 있어요.

`가이드 조회 페이지`
- 인증된 가이드 목록을 조회할 수 있어요.
  - 스마트 컨트랙트를 이용한 가이드 검증 시스템으로 인증된 가이드예요.
- 가이드의 이름, 국적, 매칭 경력, 전문 분야, 가능 언어를 프로필 카드로 확인할 수 있어요.
- 원하는 가이드에게 매칭을 요청할 수 있어요.

`가이드 이력서 페이지`
- 가이드로서의 역할을 하고 싶은 신규 가입자라면, 회원 가입 후 이력서 작성 페이지로 이동해요.
- 이름, 언어, 전문 분야 등 예비 가이드 등급을 얻기 위한 기본 정보를 입력해요.
- 가이드 이력서 작성을 완료하면 예비 가이드 권한을 얻게 돼요.

`예비 가이드 로드맵 페이지`
- 예비 가이드는 외국인 정착 지원에 대한 전문성을 평가받기 위해 예비 가이드 전용 로드맵을 수행해요.
- 일반 사용자가 로드맵을 이용했던 것처럼, 예비 가이드도 로드맵을 수행한 후 해당 정보들에 대한 지식을 피드백으로 제출해요.
- 이 피드백은 전문 가이드들이 예비 가이드를 평가하는 지표가 돼요.

`예비 가이드 평가 페이지 (전문 가이드용)`
- 전문 가이드들은 예비 가이드들의 로드맵 피드백을 보고 평가해요.
- 평가 항목은 전문 역량 점수, 도움 점수, 추천 점수로 이루어져 있어요.
- 각 항목에서 3.0 이상, 평균 4.0 이상의 점수를 받으면 예비 가이드는 전문 가이드로 승격돼요.

`예비 가이드 상태 페이지 (예비 가이드용)`
- 예비 가이드들은 전문 가이드들이 평가한 내역을 모니터링해요.
- 평가 상태에 따라 In progress/Almost/Formal guide로 나누어 현재 상태를 확인할 수 있어요.
- 예비 가이드가 전문 가이드로 전환되면, 예비 가이드 평가 페이지를 확인할 수 있어요.

`챗봇 페이지(기능)`
- 사용자가 서비스 이용 중 궁금한 점이 있다면 우측 하단의 챗봇 버튼을 눌러 질문할 수 있어요.
- 질문에 맞는 답변을 신뢰도 있는 기관에서의 데이터와 사용자 정보를 기반으로 AI가 답해요.
- AI가 답변을 생성할 때 참고하는 RAG DB에 포함되지 않는 내용에 대한 답변은 하지 않음으로서 환각 현상을 방지해요.
  - 사용자 정보를 기반으로 하기 때문에, 알 필요 없는 정보는 필터링을 거쳐서 제공해요.
 
`회원가입/로그인 페이지`
- 소셜 로그인(구글)을 이용하여 회원가입과 로그인을 해요.
- 유효하지 않은 정보라면 회원가입은 할 수 없어요.
- 진단 검사 또는 이력서 작성을 하지 않았다면 진단 검사 또는 이력서 작성 페이지로 이동되고, 완료했다면 랜딩페이지로 이동해요.
- 로그아웃 버튼을 클릭하면 로그아웃 할 수 있어요.

#### 3.3. 기능명세서
<img width="22027" height="18015" alt="Group 73" src="https://github.com/user-attachments/assets/ad174768-60e7-4507-89b7-255b8cea50b7" />

#### 3.4. 디렉토리 구조

##### Frontend
```shell
src/
│
├── 📁 apis/           # API 요청 함수 (axios 인스턴스)
├── 🖼️ assets/         # 이미지, 아이콘, 로고 등 정적 파일
│
├── 📁 components/     # 🧩 재사용 가능한 UI 컴포넌트
│   └── 📁 chatbot/     #    (예시: 챗봇 컴포넌트)
│       ├── ChatWindow.tsx #  - 전체 챗봇 창
│       ├── ChatLog.tsx    #  - 대화 기록 영역
│       └── ...
│
├── 🏛️ constants/      # 변하지 않는 상수 데이터
│
├── 🪝 hooks/          # 비즈니스 로직 및 상태 관리 커스텀 훅
│   └── useTranslation.ts  # 🌐 다국어 텍스트를 쉽게 사용하기 위한 커스텀 훅
│
├── 🏗️ layouts/        # 페이지 구조를 정의하는 레이아웃 (헤더, 푸터 등)
│   └── 📁 Header/
│       └── LanguageSelector.tsx # 🌐 언어 선택 UI 컴포넌트
│
├── 📄 pages/          # 각 라우팅 경로에 해당하는 페이지
│   └── 📁 roadmap/    #    (예시: 로드맵 페이지)
│       ├── RoadmapTypeSelectorPage.tsx # - 로드맵 타입 선택 페이지
│       └── 📁 template/               #   - 로드맵 페이지에서 사용하는 템플릿 컴포넌트
│           └── MilestoneNode.tsx     #     - 로드맵의 각 단계(마일스톤)
│
├── 🧭 routes/         # 페이지 라우팅 설정
│
├── ⚙️ services/       # API 호출 외의 비즈니스 로직
│   └── translationService.ts # 🌐 번역 관련 서비스 로직
│
├── 🗄️ stores/         # 전역 상태 관리 (Zustand)
│
├── App.tsx             # 최상위 애플리케이션 컴포넌트
├── main.tsx            # 애플리케이션 진입점 (Entry Point)
└── i18n.ts             # 🌐 i18next 라이브러리 설정 및 초기화 파일
```

##### Backend
```shell
src/main/java/com/forink/forink/
│
└── 📁 exam/  # 📝 진단 검사 도메인 예시
    ├── 📁 api/              # 📥 Presentation Layer: 외부 요청(Request) 및 응답(Response) 처리
    │   └── ExamController.java
    ├── 📁 application/      # 🧠 Business Layer: 핵심 비즈니스 로직 수행
    │   ├── 📁 dto/          #      - 계층 간 데이터 전송 객체 (Request/Response DTO)
    │   └── ExamService.java
    └── 📁 entity/            # 📦 Data Layer: 데이터베이스와 직접 통신
        ├── 📁 dao/          #      - 데이터 접근 객체 (Repository)
        │   └── ExamRepository.java
        └── Exam.java        #      - 데이터베이스 테이블과 매핑되는 객체 (JPA Entity)

... 아래 모듈들도 같은 계층 구조

├── 💬 chat/           # 챗봇 관련 API 및 로직
├── 🤝 guide/          # 가이드 매칭 및 관리 API
├── 👤 member/         # 회원 및 인증/인가 API
├── 📑 resume/         # 이력서 관리 API
├── 🗺️ roadmap/        # 로드맵 생성 및 관리 API
│
└── 🌍 global/         # 모든 도메인에서 사용하는 공통 모듈
    ├── 🤖 ai/          # 외부 AI 서비스 연동
    ├── ⚙️ config/     # 애플리케이션 주요 설정 (JPA, Security, Web3j 등)
    ├── ⚠️ error/      # 전역 예외 처리
    └── 🛡️ security/   # 인증/인가 로직 (JWT, OAuth)
```

##### AI
```shell
codes/
├── 📁 document_parsing_from_book/ # 📚 외부 문서(책)를 파싱하여 RAG 지식베이스 구축
│   ├── 📄 0_document_parser.ipynb    # 원본 문서 파싱 및 텍스트 추출
│   └── 📄 1_chunk_making_with_question_add.ipynb # 텍스트를 청크로 분할 및 질문/답변 쌍 생성
├── 📁 make_complete_roadmap/      # 🗺️ 사용자 진단 결과 기반 로드맵 생성 로직
│   ├── 📄 main.ipynb                 # 로드맵 생성 메인 프로세스
│   └── 📄 loadmap_blocks_db_upload.py # 생성된 로드맵 블록을 DB에 업로드
├── 📁 routers/                   # 📡 백엔드 서버와 통신하는 API 라우터 (FastAPI/Flask)
│   ├── 📄 router.py                  # API 엔드포인트 정의
│   └── 📄 config.py                   # API 서버 설정
│
├── 📄 searching_engine_with_storage_data.py # 🧠 벡터 스토리지 기반 검색 엔진
├── 📄 bfwc_crawled_data.csv       # 📊 크롤링된 원본 데이터 (부산국제교류재단 등)
├── 📄 extracted_articles.json     # 📑 정제 및 추출된 데이터
└── 📄 requirements.txt            # 📦 Python 패키지 의존성 목록
```

##### Blockchain
```shell
forink-contracts
├── 📜 src/            # Solidity 스마트 컨트랙트 소스 코드
│   └── GuideVerification.sol # 가이드 인증 및 평가 로직
├── 🧪 test/           # 스마트 컨트랙트 테스트 코드
├── 🚀 script/         # 배포 및 상호작용 스크립트
├── 📄 docs/           # API 및 기술 문서
├── .github/         # CI/CD (GitHub Actions) 설정
└── foundry.toml     # Foundry 프로젝트 설정 파일
```

### 4. 설치 및 사용 방법
##### Frontend
```shell
git clone https://github.com/For-In-K/forink-front.git
cd ./forink-front
npm install # + 기타 .env 환경변수 설정
npm run dev
```

##### Backend & DB
```shell
git clone https://github.com/For-In-K/forink-back.git
cd ./forink-back # + .env 파일 생성 및 DB 접속 정보 입력
docker-compose -f ./docker/docker-compose.yml up --build -d
```

##### AI
```shell
git clone https://github.com/For-In-K/forink-ai.git
cd ./forink-ai/codes
pip install -r requirements.txt # + .env 파일에 API KEY 및 DB 접속 정보 입력
uvicorn router:app --reload --host 0.0.0.0 --port 8000
```
##### Blockchain
```shell
git clone https://github.com/For-In-K/forink-contracts.git
cd ./forink-contracts # + .env 파일 생성 및 PRIVATE_KEY, SEPOLIA_RPC_URL, ETHERSCAN_API_KEY 입력
forge create src/GuideVerification.sol:GuideVerification --rpc-url $SEPOLIA_RPC_URL --private-key $PRIVATE_KEY # 스마트 컨트랙트 배포 주소 확인
```

### 5. 소개 및 시연 영상

https://github.com/user-attachments/assets/6af46090-f4c8-47d5-956c-85a9e0a820ec
<caption>10MB 제한으로 일부 기능 생략 후 시연한 영상입니다.</caption>

### 6. 팀 소개 및 해커톤 참여 후기
| 홍지연 | 팀장, 프론트엔드 개발자, 디자이너, 인프라 개발자 |
| :---: | :-- |
| <a href="https://github.com/redzzzi"><img src="https://github.com/redzzzi.png" width="200"/></a> | `💬 후기`<br>2달이라는 여름 방학 동안, 온전히 Sync 팀이 아이디어 창출부터 서비스화까지 모든 과정에 몰두할 수 있었던 시간이었습니다. 대회라는 명목으로 성사된 만남이었지만 다함께 머리를 맞대어 고민했던 많은 순간들이 기억에 남습니다.<br>이전에 참가했던 단기 해커톤에서는 결과를 중요시해서 가슴 졸이는 일이 있었는데, 충분한 시간이 주어진 이번에야 말로 팀원들과 협력하며 문제를 해결해나가는 값진 경험을 얻을 수 있었습니다. 이번 ForinK 프로젝트가 여기서 더 나아가, 실제로 목표한 사용자들에게 도움이 되는 결실을 맺기를 진심으로 바랍니다!<br>함께 해준 지민, 도형, 승한, 수환님 정말 수고 많으셨어요~!! 👏👏 |

| 이지민 | 백엔드 개발자 |
| :---: | :-- |
| <a href="https://github.com/jjimini"><img src="https://github.com/jjimini.png" width="200"/></a> | `💬 후기`<br>2짧은 기간이었지만 팀원들과 함께 주제를 논의하고 기능을 정리하며 개발을 진행하고, 오류와 보완점을 공유했던 시간이 의미 있었습니다. Forink가 단발성 프로젝트에 그치지 않고 실제 서비스로 이어져 많은 사람들에게 도움이 되기를 바랍니다. 모두 고생하셨습니다. |

| 정승한 | AI 개발자, 백엔드 개발자 |
| :---: | :-- |
| <a href="https://github.com/202255605"><img src="https://github.com/202255605.png" width="200"/></a> | `💬 후기`<br>사용자의 입장에서 과연 필요한 것이 무엇일지 고민해보고, 사용자가 더 편하게 더 사용하기 좋게 만들려면 우리는 어떤 로직과 기능을 추가해야 할 지를 또 고민하고, 그러한 기능과 로직을 최신의 기술에 맞춰 어떻게 하면 더 효율적으로 구현할 수 있을지를 고민하고 또 고민했던 것 같습니다.<br>비록 꼭 적용해야 겠다고 생각했던 기능들과 꼭 시도해보고 싶었던 기술들을 모두 아낌없이 다 풀어냈다라고는 말하지 못하고, 그에 따른 아쉬움이 많이 남습니다. 그러나, 첫 해커톤이라는 의미있는 과제를 훌륭하신 팀원들과 훌륭한 팀장님을 만나 정말 훌륭하게 끝낼 수 있음에 감사합니다. 앞으로도 더 기술적으로 궁금해 하고 발전하는 사람이 되겠습니다 모두 고생하셨습니다 감사합니다. |

| 황수환 | 백엔드 개발자, 스마트 컨트랙트 개발 |
| :---: | :-- |
| <a href="https://github.com/HSHwan"><img src="https://github.com/HSHwan.png" width="200"/></a> | `💬 후기`<br>이번 해커톤은 아이디어를 현실로 만드는 과정 속에서 '함께'라는 가치가 얼마나 큰 힘을 발휘하는지 온몸으로 느낄 수 있었던 소중한 시간이었습니다. 각자 다른 시각과 강점을 가진 팀원들이 모여 서비스 주제를 정하는 첫 단계부터, 하나의 목표를 향해 서비스의 구체적인 기능들을 하나하나 함께 논의하고 쌓아 올리는 과정은 그 자체로 즐거운 경험이었습니다.<br>예상치 못한 버그, 기획의 방향 수정 등 크고 작은 문제들이 발생하더라도 팀원들에게 공유하여 머리를 맞대고 해결책을 찾아 나갔습니다. 이처럼 어려움을 회피하지 않고 함께 해결해 나갔던 경험은 기술적인 성장보다 더 의미 있는 자산이 되었습니다. 지금의 'Forink'를 만드는 데 기여한 모든 팀원분들께 진심으로 감사드리며, 모두 정말 고생 많으셨습니다! |

| 송도형 | 데이터 수집, 서비스 현실화 |
| :---: | :-- |
| <a href="mailto:songdh1104@naver.com"><img src="https://github.com/user-attachments/assets/58ce234a-fb52-45f2-bd05-7832bfb4a45e" width="200"/></a> | `💬 후기`<br>짧은 시간이었지만 이번 해커톤은 저에게 매우 의미 있는 경험이었습니다. 정치외교학을 전공한 저에게 소프트웨어 개발은 낯선 영역이었지만, 컴퓨터공학을 전공한 팀원들과 함께 외국인 행정지원 플랫폼을 구상하고 구현하는 과정에서 학문 간 융합이 가진 힘을 직접 체감할 수 있었습니다.<br>서비스 주제를 정하고 기능을 설계하는 과정에서 저는 사회과학도의 시각으로 ‘사용자에게 진정 필요한 행정지원은 무엇일지’를 고민했고, 팀원들은 이를 기술적으로 어떻게 구현할 수 있을지를 구체화했습니다. 기획 단계에서부터 개발까지 이어진 이러한 협업은 서로 다른 전공적 배경이 만났을 때 얼마나 새로운 시너지가 발휘될 수 있는지를 보여주었습니다.<br>개발 과정에서는 예상치 못한 오류와 한계도 있었지만, 문제를 회피하기보다는 함께 토론하며 해결책을 찾아나갔습니다. 모든 기능을 완벽히 구현하지는 못했지만, 그보다 더 큰 배움은 바로 ‘다양한 관점이 모여야 실질적으로 필요한 서비스를 만들 수 있다’는 점이었습니다.<br>이번 경험을 통해 저는 기술 그 자체보다, 기술을 사회적 맥락에 적용하는 과정에서의 가치와 중요성을 배웠습니다. ‘Forink’가 단순한 프로젝트에 그치지 않고, 실제 외국인들에게 도움이 되는 서비스로 발전하기를 진심으로 기대합니다. 끝까지 함께 달려준 팀원들과 팀장님께 감사드리며, 앞으로도 더 깊이 배우고 성장해 나가겠습니다. |
