# DeepLearningStudy
2021 Skuniv DeepLearningStudy


## 목차
- [A TEAM](#A-Team-SOMSearch-Of-Music): S.O.M(Search Of Music)  
  안무 분석을 통한 음악 검색 앱  
  - 제안배경 및 소비자 분석  
  - 활용기술 및 시연  
  - 수익모델 및 시장분석  
  - 사회공헌 및 팀 역량  
- [B TEAM](#B-Team-Helper): Helper  
  국내 사회적 약자를 대상으로한 기부 앱  
  - 서비스 개요 및 상세  
  - 시연 및 기대효과  
  - 문제점 및 해결방안  
  - 예선 후 계획  
- [C TEAM](#C-Team-AI-Indoor-Sterilization-Service): AI 실내 살균 서비스  
  - 프로젝트 개요
  - 프로젝트 수행결과
  - 프로젝트 수행방법
  - 기대효과 및 활용분야
  - 참고자료
- [D TEAM](#D-Team-딥러닝-졸음감지-서비스): 딥러닝 졸음감지 서비스  
  - 요구사항 분석
  - 아키텍처 설계
  - 기능 설계
  - 개발/구현
  - 참조





## A Team: S.O.M(Search Of Music)
    안무 분석을 통한 음악 검색 앱  
  - [제안배경 및 소비자 분석](#제안배경-및-소비자-분석)  
    - 제안배경 및 현황  
      - K-POP이 세계적으로 유행 중이며, 중독적인 멜로디뿐만 아니라 안무적인 요소도 있음  
    - 기존기술 및 서비스  
      - 제목/가수를 통한 음악 검색 서비스  
      - 음성을 통한 음악 검색 서비스  
      - 가사를 통한 음악 검색 서비스  
    - 소비자 분석  
      - YouTube, TikTok 등의 SNS상에 급상승 중인 K-POP 안무에 관심이 있는 사람  
      - 언어장벽 등의 이유로 곡 정보를 찾기 힘들어하는 해외 K-POP 팬  
  - [활용기술 및 시연](#활용기술-및-시연)  
    - 핵심기술 및 구현  
      - 영상입력  
      - 입력영상 관절인식  
      - 안무가 나오는 음악 검출  
      - 데이터 베이스에서 음악정보 검색  
      - 음악정보 출력  
    - 모델 학습 과정  
      - 입력  
      - 바운딩 박스 및 관절 추출  
      - 관절 연결 이미지 추출  
      - CRNN 사용  
  - [수익모델 및 시장분석](#수익모델-및-시장분석)  
    - 수익모델  
      - 어플리케이션 판매  
      - 엔터테인먼트와 홍보계약  
      - 무료 프로그램 내 광고  
    - 시장분석  
      - BTS, 한국어 곡으로 빌보드 싱글 1위  
      - 2020, 전 세계 K-POP 관련 67억 트윗 발생  
      - 미국 TIME 선정 2021 주목할 K-POP 그룹 언급  
      - 미국 K-POP 팬덤 92% 여성/만 13세  
      - K-POP 첫 대면 통로는 음악 스트리밍  
      - 2015년 약 27조 달러에서 2018년 44조 달러로 매년 한국 콘텐츠 수출액 증가  
      - 한류 전체 시장이 12.3조 규모로 K-POP 시장규모는 이 중 7.2조를 차지  
    - 중장기 전략  
      - 2021 안무를 이용한 음악 검색 프로그램  
      - 2022 중국어 서비스  
      - 2023 안무를 배우는 기능  
      - 2024 안무 인식 시 음악 재생 기능  
      - 2025 서비자 안무 추가 기능  
  - [사회공헌 및 팀 역량](#사회공헌-및-팀-역량)  
    - 사회공헌  
      - 재활치료  
      - 홈트레이닝  
      - `사용자의 관절을 분석하여 관절 가동범위를 측정하고, 관절 가동범위 내의 가벼운 안무나 동작을 추천하여`,  
        `재미와 운동효과가 높은 재활치료를 집에서도 할 수 있도록 서비스`  
    - 팀 역량  
      - 시장분석  
        10년이상 매년 콘서트를 다니며 시장흐름과 소비자의 니즈를 파악  
      - 어플리케이션 개발  
        안드로이드 스튜디오를 이용한 어플리케이션 개발 경험  
      - AI 프로그래밍  
        팀원 전원 Python을 이용한 AI 프로그래밍 가능  
      - AI 개발 프로젝트 참여  
        AI 개발 연구에 소속되어 활동한 경험  

![슬라이드1](https://user-images.githubusercontent.com/59362257/152639519-65d7963d-6617-4983-b005-eaeab46c0c0f.JPG)
![슬라이드2](https://user-images.githubusercontent.com/59362257/152639520-6ac34ff8-684c-4cd5-9e17-67d2a8697f59.JPG)
***
## 제안배경 및 소비자 분석  
![슬라이드3](https://user-images.githubusercontent.com/59362257/152639521-617e3c9d-dc44-49ef-b25b-ddb4d6b96f5f.JPG)
![슬라이드4](https://user-images.githubusercontent.com/59362257/152639522-bce100aa-aa47-41b0-b823-5883d2a2115c.JPG)
![슬라이드5](https://user-images.githubusercontent.com/59362257/152639523-2d2cd2e7-6146-45dd-8645-07460b39df88.JPG)
[목차로 돌아가기](#목차)
***
## 활용기술 및 시연  
![슬라이드6](https://user-images.githubusercontent.com/59362257/152639525-9f88bbd5-3ed5-46fd-9342-d4e6beec5ba2.JPG)
![슬라이드7](https://user-images.githubusercontent.com/59362257/152639527-f60cf8ec-e8ab-4598-8e65-2c40f195c79c.JPG)
![슬라이드8](https://user-images.githubusercontent.com/59362257/152639529-e2e8ce49-a12c-47ec-8a18-5031fb0e0977.JPG)
![슬라이드9](https://user-images.githubusercontent.com/59362257/152639530-17a0d53b-d935-46d6-9e8b-249c2ac2ed06.JPG)
![슬라이드10](https://user-images.githubusercontent.com/59362257/152639531-2c4e2953-d599-4e55-a16a-7572da015be9.JPG)
![슬라이드11](https://user-images.githubusercontent.com/59362257/152639532-5e4ce3b3-95cf-4fa1-bbb5-115c9cd56c42.JPG)
[목차로 돌아가기](#목차)
***
## 수익모델 및 시장분석  
![슬라이드12](https://user-images.githubusercontent.com/59362257/152639533-ec52cafc-3d7e-4dd6-88e3-4c58390dfe32.JPG)
![슬라이드13](https://user-images.githubusercontent.com/59362257/152639534-967436fe-3d5a-4248-a507-1846573bd39f.JPG)
![슬라이드14](https://user-images.githubusercontent.com/59362257/152639535-e291b575-ba3f-4332-8951-c3d11d4b7bc2.JPG)
![슬라이드15](https://user-images.githubusercontent.com/59362257/152639537-75d390d5-a37f-4d6c-a411-3992024df45b.JPG)
[목차로 돌아가기](#목차)
***
## 사회공헌 및 팀 역량  
![슬라이드16](https://user-images.githubusercontent.com/59362257/152639540-c7554264-b7dd-4391-af48-eeb65753b11a.JPG)
![슬라이드17](https://user-images.githubusercontent.com/59362257/152639541-262cf4f0-6c34-4615-9ff0-2d6795a871d1.JPG)
[목차로 돌아가기](#목차)





## B Team: Helper  
    국내 사회적 약자를 대상으로한 기부 앱  
  - [서비스 개요 및 상세](#서비스-개요-및-상세)  
    - 서비스 개요  
      - 급하게 도움이 필요한 사회적 약자 계층 대상  
      - 기부대상으로 선정되지 못한 사회적 약자 계층 대상  
      - 1대 1로 간편하고 신속한 도움  
    - 서비스 상세  
      - 기부 대상자  
        주변에서 쉽게 볼 수 있는 개개인 대상  
      - 메신저 기능  
        기부자와 기부대상 간의 1대1 커뮤니케이션 가능  
      - 간단한 신청  
        금전적/비금전적 도움을 게시판 형태를 통해 간단히 요청  
      - 캠페인 참여  
        유니세프/어린이재단 등 큰 규모의 기부캠페인도 참여 가능  
  - [시연 및 기대효과](#시연-및-기대효과)  
    - 시연화면  
      - 특정단체의 불특정 다수가 아닌 특정 개인을 후원  
      - 메신저를 통한 기부 대상자의 즉각적인 피드백  
    - 기대효과  
      - 사회적 약자의 삶의 질 개선  
      - 기부의 일상화  
      - 기부의 본질 개선  
  - [문제점 및 해결방안](#문제점-및-해결방안)  
    - 문제점  
      - 상황을 과장하거나 거짓으로 후원 유도  
      - 후원받은 기부금을 원래 용도가 아닌 용도로 사용  
    - 해결방안  
      - 간단한 신청서 작성을 통해 사실확인 및 심사과정을 거침  
      - 후원 종료 후 기부대상자의 후기와 기부자의 비공개 평과가정을 거침  
  - [예선 후 계획](#예선-후-계획)  
    - 개발 심화 계획  
      - Android Studio 앱 개발  
      - Firebase Realtime Database를 활용한 메신저 구축  
      - SQL Server를 활용한 회원정보 등의 유지관리  
    - 홍보/마케팅 계획  
      - SNS 활용  
      - TV 프로그램 제보 및 출연  

![슬라이드1](https://user-images.githubusercontent.com/59362257/152640125-4c6dec9a-c6c5-47f1-ba04-90f2d2f785e4.JPG)
![슬라이드2](https://user-images.githubusercontent.com/59362257/152640126-121486d3-9840-4e86-8c3a-97a20f794875.JPG)
***
## 서비스 개요 및 상세
![슬라이드3](https://user-images.githubusercontent.com/59362257/152640127-3ad5c4e2-f60e-4548-83a3-f735e58b4318.JPG)
![슬라이드4](https://user-images.githubusercontent.com/59362257/152640128-5bdc3a6e-938c-4be2-8d14-5844e28cc973.JPG)
[목차로 돌아가기](#목차)
***
## 시연 및 기대효과
![슬라이드5](https://user-images.githubusercontent.com/59362257/152640130-3294a675-4631-4e0d-89a5-c65a01212132.JPG)
![슬라이드6](https://user-images.githubusercontent.com/59362257/152640131-36145511-1175-431e-a219-fa5a8bc59c66.JPG)
[목차로 돌아가기](#목차)
***
## 문제점 및 해결방안
![슬라이드7](https://user-images.githubusercontent.com/59362257/152640132-623c641b-2d30-4388-a47d-821a914c500e.JPG)
[목차로 돌아가기](#목차)
***
## 예선 후 계획
![슬라이드8](https://user-images.githubusercontent.com/59362257/152640135-e0bce30f-3f13-4d95-aefd-9c654cdcc168.JPG)
![슬라이드9](https://user-images.githubusercontent.com/59362257/152640136-70c2e00b-b649-48e2-9fce-6f8eab6c05bf.JPG)
[목차로 돌아가기](#목차)





## C Team: AI Indoor Sterilization Service  
  - [프로젝트 개요](#프로젝트-개요)  
    - 프로젝트 소개  
      - 안전한 실내 환경을 위한 사용자 맞춤형 살균 서비스  
      - 사용자 인식 및 사용자 생활 패턴 기반 살균 서비스  
    - 개발배경 및 필요성  
      - 방역에 대한 관심 증대  
    - 작품 구성도  
      - 전체 구성도  
      - 기능처리 및 서비스 흐름도  
    - 작품의 특징 및 장점  
      - 사용자 활동패턴에 기반한 AI 자동 살균기  
      - 앱을 통한 살균기 제어  
  - [프로젝트 수행결과](#프로젝트-수행결과)  
    - 주요기능  
      - 살균 서비스  
      - 온습도 측정  
      - 실시간 카메라 영상 인식  
      - 사용자 패턴기반 살균 알고리즘  
      - 사용자 패턴기반 군집화 알고리즘  
      - 라즈베리 파이 웹서버 연결  
      - 라즈베리 파이 아두이노 연결  
    - 프로젝트 개발환경  
      - Ubuntu 16.04, 라즈비안  
      - VS Code, PyCharm  
      - Android Studio, MySQL  
      - Python3, JAVA  
      - 라즈베리파이4, 아두이노 UNO  
      - 릴레이 모듈, 가습기 모듈  
    - 장비  
      - 라즈베리파이4  
      - 아두이노 UNO  
      - 릴레이 모듈  
      - 가습기 모듈  
    - 프로그램 작동 동영상  
      - https://youtu.be/fu_6OlAMkt8  
    - 결과물 상세 이미지  
    - 달성성과  
      - 한국 정보처리 학회지 논문게재, "AI와 친환경 소재 IOT를 활용한 사용자 활동기반 댁내 살균 서비스"  
      - 2021 한이음 공모전 출품  
  - [프로젝트 수행방법](#프로젝트-수행방법)  
    - 업무분장  
      - 서버/DB구축  
      - SW/HW 개발  
      - 인공지능 설계  
    - 프로젝트 수행일정  
      - 계획  
      - 분석  
      - 설계  
      - 개발  
      - 테스트  
      - 종료  
    - 문제점 및 해결방안  
      - 업무분담으로 인한 상호간 프로젝트 이해도 차이    
        주기적인 회의롤 통한 의사소통 과정을 거쳐 전체 개발 진행과정 공유  
      - 객체 인식률 저하  
        임베디드 시스템에 적합한 YOLOv4-tiny 모델 사용  
      - 분무기능 개발의 어려움  
        - 가습기 모듈을 이용하여 아두이노와 라즈베리 파이간 시리얼 통신을 통해 분무기능 구현  
      - DB 보안 취약 문제  
        - 해킹당한 기존 데이터베이스 삭제, root 권한 조정 후 비밀번호 재설정  
  - [기대효과 및 활용분야](#기대효과-및-활용분야)  
    - 작품의 기대효과  
      - Covid19와 관련한 실내 환경 이슈 대응  
      - 살균의 자동화를 통한 삶의 질 향상  
      - 개인화된 살균 서비스로 개인위생에 대한 인식 향상  
      - 생활패턴 분석에 기반한 인공지능 자동화 살균으로, 살균의 효율성 증대와 비용절감  
      - 객체인식으로 수집된 사용자 데이터를 기반으로 다양한 서비스 제공 등 응용 프로그램 발전 가능  
    - 작품의 활용분야  
      - 학교/직장/공공시설 등 다양한 실내 시설에 설치 및 활용  
      - Covid19뿐만 아니라 기타 질병에 대한 예방 가능  
      - 응용 프로그램을 공기청정기와 결합, 효과적인 살균 및 공기정화 효과 기대  
  - [참고자료](#참고자료)  
    - 참고 및 인용자료  
      - Ankur A.Patel, "핸즈온 비지도 학습 (강재원, 권재철 옮김), 서울, 한비미디어, 2020  
      - Scikit-learn, Available: http://scikit-learn.org.stable/  

![서식  2021년 한이음 ICT멘토링 프로젝트 결과보고서001](https://user-images.githubusercontent.com/59362257/152640567-e399894e-8007-4314-85e5-7c22ee36388e.jpg)
***
## 프로젝트 개요
![서식  2021년 한이음 ICT멘토링 프로젝트 결과보고서002](https://user-images.githubusercontent.com/59362257/152640569-06cdab5a-0a29-4b8c-a039-0559e457d7f6.jpg)
[목차로 돌아가기](#목차)
***
## 프로젝트 수행결과
![서식  2021년 한이음 ICT멘토링 프로젝트 결과보고서003](https://user-images.githubusercontent.com/59362257/152640570-99cf7901-8e6f-490c-ad57-67cc2a59722e.jpg)
[목차로 돌아가기](#목차)
***
## 프로젝트 수행방법
![서식  2021년 한이음 ICT멘토링 프로젝트 결과보고서004](https://user-images.githubusercontent.com/59362257/152640571-6d4a0f12-f315-43db-85bd-f0f9a1a2492c.jpg)
[목차로 돌아가기](#목차)
***
## 기대효과 및 활용분야
![서식  2021년 한이음 ICT멘토링 프로젝트 결과보고서005](https://user-images.githubusercontent.com/59362257/152640572-15dd2a64-9d24-47c4-b369-f12a20dcad95.jpg)
[목차로 돌아가기](#목차)
***
## 참고자료
![서식  2021년 한이음 ICT멘토링 프로젝트 결과보고서006](https://user-images.githubusercontent.com/59362257/152640573-88783c91-d4be-405c-989d-096302d4dc45.jpg)
[목차로 돌아가기](#목차)





## D Team: 딥러닝 졸음감지 서비스  
  - [요구사항 분석](#요구사항-분석)
    - 요구사항 정의서
      - 졸음 감지
      - 눈 깜빡임 감지
      - 통계 서비스
      - 투두리스트
      - 로그인 및 회원가입
      - 게시판
  - [아키텍처 설계](#아키텍처-설계)
    - 서비스 구성도(시스템 구성도)
      - 사용자 영상 데이터 전송 및 서비스 요청
      - 사용자 정보 전송
      - 서비스 데이터 전송
      - 요청된 서비스 제공
    - 서비스 흐름도(데이터 흐름도)
      - 사용자 영상 데이터 전송 및 서비스 요청
      - 사용자 영상 데이터 및 서비스 정보를 서버로 전송
      - 사용자 영상 데이터와 요청된 서비스 정보를 전송, 사용자 데이터 DB 저장
      - 사용자 데이터 및 서비스 데이터 서버로 전송
      - 요청된 서비스 데이터를 웹페이지/앱으로 전송
      - 요청된 서비스를 사용자에게 제공
  - [기능 설계](#기능-설계)
    - 메뉴 구성도
      - 마이페이지
      - Task Manager
      - 졸음 감지 시스템
      - 눈깜빡임 측정 시스템
      - 게시판
    - 화면 설계서
      - 로그인/회원가입 화면
      - 메인 화면
      - 통합 기능 페이지 화면
      - 게시판 화면
      - 랭킹 게시판 화면
      - 마이페이지
    - 엔티티 관계도
      - 이미지 참조
    - 기능 처리도(기능 흐름도)
      - 이미지 참조
    - 알고리즘 명세서/설명서
      - Base64 Encoding & Decoding
      - dlib 사람 얼굴 검출 알고리즘
    - 데이터 수집처리 정의서
      - 이미지 참조
  - [개발/구현](#개발구현)
    - 프로그램 목록
      - 졸음 감지
      - 눈 깜빡임 감지
      - 통계 서비스
      - 투두리스트
      - 로그인 및 회원가입
      - 게시판
    - 테이블 정의서
      - 이미지 참조
    - 핵심 소스코드
      - 영상처리 및 감지 함수 호출
      - 눈동자 검출
      - 졸음 감지
      - 졸음 감지 알림
      - 깜빡임 횟수 측정
      - 깜빡임 횟수 부족 알림
      - 웹소켓 통신
  - [참조](#참조)
    - 개발 환경 및 설명
      - 감지 애플리케이션 개발
      - 서버 애플리케이션 개발
    - S/W 기능 실사 사진
      - 웹 서비스 페이지
      - 졸음 감지 시연
      - 앱 서비스 화면
    - 프로젝트 관리
      - 프로젝트 관리
      - 형상관리
      - 이슈관리

![슬라이드1](https://user-images.githubusercontent.com/59362257/152640610-7ca8b65c-575c-4cd7-a024-7dc5c92f476d.JPG)
![슬라이드2](https://user-images.githubusercontent.com/59362257/152640612-b6791b0f-a623-4fc2-9029-1dafaecf048e.JPG)
***
## 요구사항 분석
![슬라이드3](https://user-images.githubusercontent.com/59362257/152640613-a0ce6bcd-9270-4136-ac62-8ccbd1188f61.JPG)
[목차로 돌아가기](#목차)
***
## 아키텍처 설계
![슬라이드4](https://user-images.githubusercontent.com/59362257/152640614-59c2e7ce-c957-486d-a9ac-ccd946772bb7.JPG)
![슬라이드5](https://user-images.githubusercontent.com/59362257/152640616-5bf82ac7-4a68-411e-b1f8-7814052420f7.JPG)
[목차로 돌아가기](#목차)
***
## 기능 설계
![슬라이드6](https://user-images.githubusercontent.com/59362257/152640618-0add2e99-8898-450a-a55f-9ef8ae2432d6.JPG)
![슬라이드7](https://user-images.githubusercontent.com/59362257/152640619-e25028a6-eef3-4bcf-8613-38bd21ca34fa.JPG)
![슬라이드8](https://user-images.githubusercontent.com/59362257/152640620-1f0b8692-2429-4035-8fa8-cff574ed97eb.JPG)
![슬라이드9](https://user-images.githubusercontent.com/59362257/152640621-03a1c9df-b3be-46c0-a652-94cd1263e0a8.JPG)
![슬라이드10](https://user-images.githubusercontent.com/59362257/152640622-a77deb84-ab80-4315-b1c5-50a1698fd1d3.JPG)
![슬라이드11](https://user-images.githubusercontent.com/59362257/152640623-cdfcbecf-62a9-4645-bf67-73ac0d8c6ee8.JPG)
![슬라이드12](https://user-images.githubusercontent.com/59362257/152640624-8b4d12b8-f5e2-4db7-9bcc-581eae537ee6.JPG)
![슬라이드13](https://user-images.githubusercontent.com/59362257/152640625-902859ca-a5f3-4aec-a46d-577014d66f3e.JPG)
![슬라이드14](https://user-images.githubusercontent.com/59362257/152640626-ad0108aa-5133-45e6-a290-ba280965700b.JPG)
![슬라이드15](https://user-images.githubusercontent.com/59362257/152640627-73465294-40f8-4959-bc1f-1f6e363ce65e.JPG)
![슬라이드16](https://user-images.githubusercontent.com/59362257/152640628-ad8b17e4-9656-4343-8273-2e53dc61f2f4.JPG)
![슬라이드17](https://user-images.githubusercontent.com/59362257/152640630-b0b7e5ab-b9c0-48f8-b5b6-80c247d3c3c5.JPG)
![슬라이드18](https://user-images.githubusercontent.com/59362257/152640631-fdfc7d01-20f0-4e6d-bb29-1354c488fccf.JPG)
![슬라이드19](https://user-images.githubusercontent.com/59362257/152640632-f019963b-1f14-4d03-bf3f-5cf24a6e52dd.JPG)
![슬라이드20](https://user-images.githubusercontent.com/59362257/152640635-5e6493b9-5d40-4a2f-abca-fdc8974fdb82.JPG)
![슬라이드21](https://user-images.githubusercontent.com/59362257/152640636-11ae6e25-b441-4b07-b875-81279a0715a2.JPG)
![슬라이드22](https://user-images.githubusercontent.com/59362257/152640637-c8c358f0-83ee-4e63-9b5a-79154960f046.JPG)
![슬라이드23](https://user-images.githubusercontent.com/59362257/152640638-a074a4cc-8e16-4d21-ab6f-247dd995a421.JPG)
![슬라이드24](https://user-images.githubusercontent.com/59362257/152640639-ed3e81dd-60d5-478d-8fbb-c59e384ccd2b.JPG)
[목차로 돌아가기](#목차)
***
## 개발/구현
![슬라이드25](https://user-images.githubusercontent.com/59362257/152640643-586b3859-9ac7-4ca8-8003-ad323377cae7.JPG)
![슬라이드26](https://user-images.githubusercontent.com/59362257/152640644-94109a5f-35ba-4f88-8014-71ec3d0b9ebb.JPG)
![슬라이드27](https://user-images.githubusercontent.com/59362257/152640645-a3ebf4ec-2ecf-401d-9749-4df26934c0e9.JPG)
![슬라이드28](https://user-images.githubusercontent.com/59362257/152640647-3a4b194d-4fd2-443a-b653-ce709ef4befc.JPG)
![슬라이드29](https://user-images.githubusercontent.com/59362257/152640649-27cba2cb-b78d-454d-96d9-65790781b4ed.JPG)
![슬라이드30](https://user-images.githubusercontent.com/59362257/152640650-68f6a9b3-9223-47a4-bead-b9658713f413.JPG)
![슬라이드31](https://user-images.githubusercontent.com/59362257/152640652-9e921224-e48f-4df1-87ab-9c18e52b7330.JPG)
![슬라이드32](https://user-images.githubusercontent.com/59362257/152640653-87df3d98-972a-4cf0-b04a-3f6e90936f79.JPG)
![슬라이드33](https://user-images.githubusercontent.com/59362257/152640654-6d305506-2c5d-46ac-a4d1-32e99adf11b9.JPG)
![슬라이드34](https://user-images.githubusercontent.com/59362257/152640655-b6b0fea3-3d04-42e6-b03a-0f7845c56188.JPG)
![슬라이드35](https://user-images.githubusercontent.com/59362257/152640656-7f2399d0-1092-44e5-bdfb-1ff7cb180309.JPG)
![슬라이드36](https://user-images.githubusercontent.com/59362257/152640657-74c14d4d-b773-440b-a207-9a92ad3b4803.JPG)
![슬라이드37](https://user-images.githubusercontent.com/59362257/152640658-dad63227-727c-444a-bcb9-70787e9954e5.JPG)
![슬라이드38](https://user-images.githubusercontent.com/59362257/152640660-57651c79-1703-47fc-a633-d940170acef2.JPG)
[목차로 돌아가기](#목차)
***
## 참조
![슬라이드39](https://user-images.githubusercontent.com/59362257/152640661-b6be6316-713b-4631-9061-3d226d960ea9.JPG)
![슬라이드40](https://user-images.githubusercontent.com/59362257/152640663-cac1af32-0864-462d-8571-2715e7d3f016.JPG)
![슬라이드41](https://user-images.githubusercontent.com/59362257/152640664-8a7a3e67-f5ad-49ab-9911-cbe69f890727.JPG)
![슬라이드42](https://user-images.githubusercontent.com/59362257/152640665-721be875-c0de-416b-a12d-c4738c96f943.JPG)
![슬라이드43](https://user-images.githubusercontent.com/59362257/152640666-ad2c2f3f-e97f-480f-ba7e-4dbcdfa1b8e6.JPG)
![슬라이드44](https://user-images.githubusercontent.com/59362257/152640667-ab27af3a-e69c-4a86-966f-5275152985c9.JPG)
[목차로 돌아가기](#목차)
