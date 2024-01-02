# 박세웅 포트폴리오


## :pushpin: Intro
사람들의 삶을 더욱 편리하게 만들며 즐겁게 개발하고 싶습니다. 이전에는 데이터 분야를 전반적으로 학습하고, 관련 업무를 하며 다양한 프로젝트를 수행하였습니다. 협업을 하면서, 어떻게 하면 팀 전체에게 긍정적인 영향을 줄 수 있을 지 고민합니다. 주 개발 언어로 Java를 사용하며, Python 또한 사용합니다. 클라우드 환경에서 일해본 경험이 있습니다.
</br>

## :pushpin: Contact
- 이메일: ert4263@gmail.com
- 블로그: https://seandailytech.tistory.com/
- 깃헙: https://github.com/Woonggss

</br>

## :pushpin: Projects(Development)

### 1. 건강을 지향하는 사람들의 커뮤니티, Shelter WellBeing
>Single Page Application 개발 프로젝트
>
>* Spring Boot와 MyBatis를 활용하여 RESTful API 서버 개발
>
>* Vue.js의 라우트 쿼리를 활용하여 페이지 전환 시 필요한 데이터만 서버에 요청 및 화면에 출력
>
>* Spring Security를 활용하여 인증/인가 관리
>  * Security Filter Chain에서 서버-클라이언트 통신 시 CORS 이슈 해결
>  * Bean Factory에서 관리되는 로그인 정보를 주입받아 JWT 토큰 생성
>* 프로젝트 기간 : 2023.10 ~ 2023.11(6주)
>  
>* 사용 기술
>  * Front-end : Javascript, Vue.js
>  * Back-end : Java, Spring Boot, MyBatis, MySQL, Spring Security
>  
>[프로젝트 상세 설명](https://nonchalant-peony-9fc.notion.site/Shelter-WellBeing-ac507c6f3ef645f68d97799ba6427a5e)
---

### 2. 사내 크리에이터 검색 웹 서비스, CO Search Tool
>사내 업무 지원을 위해 크리에이터 검색을 쉽게 할 수 있도록 돕는 웹 서비스
>
>* 글로벌 환경에서 개발자, 기획자, 디자이너, PM과의 협업 및 커뮤니케이션
>
>* DB 모델링, 데이터 수집을 위한 크롤러 작성 및 서버 API 엔드포인트 구현
>
>* 프로젝트 기간 : 2022.08 ~ 2022.10 (10주), 사내 프로젝트
>
>* 사용 기술 : Python, FAST API, GCP BigQuery

</br>


## :pushpin: Projects(Data Engineering)

### 1. 유튜브 트렌딩 데이터 파이프라인 구축
>Google Cloud Platform 상에서 매일 유튜브 데이터를 추출, 변형, 적재(Extract, Transform, Load)하는 파이프라인 구축
>
>* Python 및 GCP Cloud Function을 활용해 데이터 추출 및 변형
>
>* GCP BigQuery에 데이터 적재
>
>* 프로젝트 기간 : 2022.07 ~ 2022.08 (5주), 사내 프로젝트
>
>* 사용 기술 : Python, Google Cloud Platform(Cloud Function, Cloud Storage, Storage Transfer, BigQuery)

---

### 2. 사업개발팀 데이터 요청 대응 시스템 구축
>사업개발팀의 의사 결정에 필요한 데이터를 추출하는 업무 지원 시스템 구축
>
>* Python 및 SQL을 활용하여 데이터 요청에 대응하는 코드를 작성
>
>* Python 로컬 환경의 코드와 Cloud 환경의 테이블을 연동하여 보다 편리하게 데이터를 추출할 수 있도록 셋업
>
>* 프로젝트 기간 : 2022.04 ~ 2022.05 (5주), 사내 프로젝트
>
>* 사용 기술 : Python, Google Cloud Platform(Cloud Storage, BigQuery)

</br>

## :pushpin: Projects(Data Science & Analytics)

### 1. 크리에이터 컨설팅 데이터 분석 자동화 리포트 제작
>기존 리포트 코드 품질 및 작업 효율 개선, 데이터 분석 지표 추가
>
>* 필요한 정보를 입력하고 실행하면 자동으로 만들어지는 데이터 분석 레포트 제작
>
>* 크리에이터의 현황을 잘 나타낼 수 있는 데이터 분석 지표 고안
>
>* 기존 리포트 대비 Manual Work를 줄임으로써 업무 효율 개선
>
>* 기존 리포트 코드를 리팩토링하여 유지보수성 및 가독성 확보
>
>* 프로젝트 기간 : 2022.02 ~ 2022.04 (9주), 사내 프로젝트
>  
>* 사용 기술 : Python, Google Cloud Platform(Cloud Storage, BigQuery 등)

---

### 2. 자동차 휠 디자인 유사도 검증 모델 구축
>전이학습(Transfer Learning)을 활용한 이미지 처리 딥러닝 모델 구축(팀 프로젝트)
>
>* 프로젝트 기간: 2020.5 ~ 2020.7(9주)
>  
>* 사용 기술 : Python, Google Cloud Platform
>  * 데이터 수집 : beautifulsoup, selenium, fake_useragent, pyautogui
>  * 데이터 전처리(이미지 처리) : cv2, PIL, matplotlib, keras
>  * 모델 구축 : keras
>  * 휠 유사도 판별 : sklearn(scikit-learn), skimage(scikit-image) 
>  * GCP(Google Cloud Platform)를 활용하여 딥러닝 모델 구동  
>  
>[프로젝트 상세 설명](https://github.com/Woonggss/2020-deep-learning-project)

---

### 3. 따릉이 데이터 분석 및 전략 제안
>회귀분석 및 clustering 기법을 활용하여, 서울시 공공 자전거 따릉이 서비스의 지속적인 성장 방안 제시(팀 프로젝트)
>
>* 프로젝트 기간 : 2019.11 ~ 2019.12(5주)
>  
>* R을 활용한 데이터 분석 프로젝트
>  
>  
>[프로젝트 상세 설명](https://github.com/Woonggss/2019-data-project)

<br>


## :pushpin: Additional Activities

### 1. Quant
>* 데이터 분석을 기반으로 한 투자 의사결정 실습
>
>* 기술적 분석 세션 자료, 투자 전략 백테스팅 및 stockpicking, 엑셀과 VBA를 활용한 투자 이론 실습
>
>[활동 상세 설명](https://github.com/Woonggss/Quant)
