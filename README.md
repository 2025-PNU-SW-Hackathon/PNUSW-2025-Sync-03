<img width="1200" height="300" alt="forink_preview (2)" src="https://github.com/user-attachments/assets/f15c10f3-aef5-40de-984d-594fbeba7e0d" />

### 1. 프로젝트 소개
#### 1.1. 개발배경 및 필요성
> 프로젝트를 실행하게 된 배경 및 필요성을 작성하세요.

#### 1.2. 개발 목표 및 주요 내용
> 프로젝트의 목표 및 주요 내용을 작성하세요.

#### 1.3. 세부내용
> 위 내용을 작성하세요.

#### 1.4. 기존 서비스 대비 차별성
> 위 내용을 작성하세요.

#### 1.5. 사회적가치 도입 계획
> 위 내용을 작성하세요.


### 2. 상세설계
#### 2.1. 시스템 구성도
<img width="14784" height="11900" alt="service_archi_diagram" src="https://github.com/user-attachments/assets/bb1ed067-59e4-445a-90fc-ee34bb5a4920" />

#### 2.1. 사용 기술
##### 프론트엔드
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

##### 백엔드
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

##### 스마트 컨트랙트
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
> 위 레포지토리의 디렉토리 구조를 설명하세요.

### 4. 설치 및 사용 방법
> 제품을 설치하기 위헤 필요한 소프트웨어 및 설치 방법을 작성하세요.
>
> 제품을 설치하고 난 후, 실행 할 수 있는 방법을 작성하세요.

### 5. 소개 및 시연 영상
> 프로젝트에 대한 소개와 시연 영상을 넣으세요.
> 프로젝트 소개 동영상을 교육원 메일(swedu@pusan.ac.kr)로 제출 이후 센터에서 부여받은 youtube URL주소를 넣으세요.

### 6. 팀 소개
> 팀원 소개 & 구성원 별 역할 분담 & 간단한 연락처를 작성하세요.
### 7. 해커톤 참여 후기
> 팀원 별 해커톤 참여 후기를 작성하세요.
