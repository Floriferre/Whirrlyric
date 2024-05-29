# SpringBoot-React-Project
스프링부트 + JPA, React + Tailwind + TypeScript

## 🖥 프로젝트 소개
> **나만의 가사를 내 취향에 맞는 노래로! **

" 작곡에 대해 잘 모르지만, 이런 가사가 들어간 노래가 듣고 싶은 당신에게!
" 내 최애의 응원곡을 만들고 싶은 당신에게!
" 같은 가사로 여러 장르의 음악을 만들고 싶은 당신에게!

WHIRRLYRIC은 AI가 당신이 원하는 분위기와 가사로 빠르게 음악을 만들어드립니다!

1. AI 노래 만들기 : 원하는 분위기와 가사를 입력하면 WHIRRLYRIC의 AI가 노래를 만들어드립니다!
2. 노래에 맞는 앨범 커버 자동 제작 : 단색의 밋밋한 앨범 커버는 지겹다! WHYRRLYRIC은 DALL.E 기반으로 자동으로 앨범 커버를 만들어드립니다!
3. url 공유 및 다운로드 : 내가 만든 노래를 다른 사람에게 보여주고 싶다! URL을 통해 내가 만든 노래를 공유할 수 있으며, 다운로드도 할 수 있습니다!
4. 노래 추천 : 다른 사람들이 좋아하는 노래는 무엇일까? 실시간으로 노래 순위를 업데이트 하여 인기곡 순으로 여러분들께 들려드립니다!


## 목차

## 📆 개발 기간
* 24.04.08일 ~ 24.05.17일

## 🙎 멤버 구성
### FE
* 안수진 : 메인페이지, 마이페이지, 노래 상세 페이지, 라우팅 처리
* 정여민 : 랜딩페이지, 소셜로그인, 노래 제작 페이지, 프로필 사진

### BE
* 이지은(팀장) : 노래 생성 API, 가이드라인 API, 가사 타입 조회 API, 장르 조회 API
* 김예림 : KAKAO 소셜 로그인, 디자인
* 김진호 : 메인페이지 API, 마이페이지 API, 노래 상세 API, 노래 리스트 API

### INFRA
* 유호영 : AWS EC2, Docker, Jenkins 를 사용한 CI/CD 구축, QA


## ⚙ 개발 환경
### BE
* Java 17
* JDK 17.0.9
* IDE : intelliJ 2023.3.2
* Framework : SpringBoot(3.2.2)
* ORM : JPA
* DB : MariaDB v.10
* 웹서버 : Apache Tomcat

### FE
* React
* typescript(5.2.2)
* tailwindCSS(3.4.1)
* vite(5.0.8)


## 🎁 필수 조건
* Gradle : groovy
* 사용한 dependency
    * lombok
    * Hibernate
    * MySQL
    * Spring Web
    * Spring Data JPA
    * JSON


## 서비스 아키텍처

![기술스택](https://github.com/Floriferre/Cardian/assets/130302086/985b7be5-bf77-4be1-bad8-22fe53c43271)


## 📡 배포 가이드

    [노션 링크](https://sun-silica-4cf.notion.site/Whirrlyric-1c7694962c78469a9ec3a8f0cef25057?pvs=4)


## 📌주요 기능

### 랜딩페이지 : 카카오 소셜 로그인
![01_랜딩페이지](https://github.com/Floriferre/Cardian/assets/130302086/4aadef9d-a78b-473a-ace5-348eefdfe713)
![02_카카오로그인페이지](https://github.com/Floriferre/Cardian/assets/130302086/51482077-17b4-4de8-b66c-28d2e9e2592b)


### 메인페이지 : 인기곡 및 추천곡 조회
![03_메인페이지](https://github.com/Floriferre/Cardian/assets/130302086/bbfebea2-050b-4a8b-af35-736ebad8250d)
![04_메인페이지](https://github.com/Floriferre/Cardian/assets/130302086/149b0a64-a694-4c5b-bde1-dda06eb042be)

### 노래 제작 페이지 : 노래 제작 및 가이드라인
![08_노래제작페이지](https://github.com/Floriferre/Cardian/assets/130302086/4a96545c-40e0-4e0e-a758-a50972b6fa7f)
![09_노래제작페이지2](https://github.com/Floriferre/Cardian/assets/130302086/3dce5a8c-bb85-4548-b564-28b32994e4ac)
![10_노래제작페이지_가이드라인](https://github.com/Floriferre/Cardian/assets/130302086/86efd238-68b0-423e-9b9b-a061ac6c59de)

### 노래 재생 페이지 : 재생, 가사 조회, 다운로드
![05_노래재생페이지](https://github.com/Floriferre/Cardian/assets/130302086/9edf506c-1782-46a2-a044-03c085de3e24)

### 마이페이지 : 만든 노래 목록 조회, 닉네임 수정
![06_마이페이지](https://github.com/Floriferre/Cardian/assets/130302086/9b306968-03c3-4178-959a-e34eb349866e)
![07_닉네임수정페이지](https://github.com/Floriferre/Cardian/assets/130302086/b14f1986-9e1d-4af3-8e13-04ee1be80ff4)



