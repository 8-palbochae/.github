# 🦐여보소(SeaHere)

<p align="center">
  <img src="../image/logo.png">
  <br>
  전체 프로젝트 기간 : 2024-07-15 ~ 2024-08-29 <br>
  프로젝트 개요~~~~
</p>

<p align=center>
  <a href="https://www.notion.so/c6626df97574434a8b9f8358b00ece75?v=6f696739249448e392872058a527721e">팀 노션</a>
  &nbsp; | &nbsp; 
  <a href="https://www.notion.so/API-685de6db49e44954af21b2448a3d9df0">API 명세서</a>
  &nbsp; | &nbsp;
  <a href="https://www.notion.so/eadc3fae3a3e40c0a89e97525a234e04">요구사항 정의서</a>   &nbsp; | &nbsp;
  <a href="https://www.figma.com/design/hEmRP4qZuf1fJTlT32mOiE/SeaHere?node-id=0-1">figma</a> 
  <br />
  <a href="https://www.notion.so/GROUND-RULE-d227d18aba144bd8acc6459aacd075fa">그라운드 룰</a>
  &nbsp; | &nbsp; 
  <a href="https://www.notion.so/ebef5b8991c645f79bf462a5d37589c8">트러블 슈팅</a>
</p>

## 📢 SeaHere 사용해보기

<p align="center">
      https://broker.seahere.org/ <br>
      https://coustomer.seahere.org/

## ⚙️ 기술스택

 <div align= "center">
    <div style="text-align: center">
    <h3 style="border-bottom: 1px  color: #282d33;"> FrontEnd </h3>
        <div style="margin: ; text-align: left;" "text-align: left;"> 
          <img src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=Figma&logoColor=white">
          <img src="https://img.shields.io/badge/react-17219A?style=for-the-badge&logo=react&logoColor=white">
          <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=Node.js&logoColor=white">
          <img src="https://img.shields.io/badge/Tailwind CSS-06B6D4?style=for-the-badge&logo=Tailwind CSS&logoColor=white">
          <img src="https://img.shields.io/badge/vite-73563B?style=for-the-badge&logo=vite&logoColor=white">
          <img src="https://img.shields.io/badge/webpack-17263B?style=for-the-badge&logo=webpack&logoColor=white">
          <img src="https://img.shields.io/badge/reactquery-FF4154?style=for-the-badge&logo=reactquery&logoColor=white">
          <img src="https://img.shields.io/badge/Zustand-47211C?style=for-the-badge&logo=Zustand&logoColor=white">
        </div>
        </div>
        <h3 style="border-bottom: 1px solid #d8dee4; color: #282d33;"> BackEnd </h3>
          <div style="margin: ; text-align: center;">
              <img src="https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=java&logoColor=white">
              <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=MySQL&logoColor=white">
              <img src="https://img.shields.io/badge/Spring Boot-6DB33F?style=for-the-badge&logo=Spring Boot&logoColor=white">
              <img src="https://img.shields.io/badge/Spring Security-2AC89F?style=for-the-badge&logo=Spring Security&logoColor=white">
              <img src="https://img.shields.io/badge/JPA-17219A?style=for-the-badge&logo=JPA&logoColor=white">
              <img src="https://img.shields.io/badge/QueryDSL-8A084B?style=for-the-badge&logo=QueryDSL&logoColor=white">
              <img src="https://img.shields.io/badge/firebase-FE642E?style=for-the-badge&logo=firebase&logoColor=white">
              <img src="https://img.shields.io/badge/Redis-FE2E2E?style=for-the-badge&logo=Redis&logoColor=white">
        </div>

<h3 style="border-bottom: 1px solid #d8dee4; color: #282d33;"> Infra </h3>
    <div style="margin: ; text-align: left;" "text-align: left;">
          <img src="https://img.shields.io/badge/Amazon S3-02569B?style=for-the-badge&logo=Amazon S3&logoColor=white">
          <img src="https://img.shields.io/badge/Amazon AWS-232F3E?style=for-the-badge&logo=Amazon AWS&logoColor=white">
          <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=Docker&logoColor=white">
          <img src="https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=Jenkins&logoColor=white">
          <img src="https://img.shields.io/badge/Nginx-04B431?style=for-the-badge&logo=Nginx&logoColor=white">
    </div>

  <h3 style="border-bottom: 1px  color: #282d33;"> 협업 </h3>
    <div style="margin: ; text-align: left;" "text-align: left;">
      <img src="https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=Notion&logoColor=white">
      <img src="https://img.shields.io/badge/Git-94B431?style=for-the-badge&logo=Git&logoColor=white">
      <img src="https://img.shields.io/badge/slack-916?style=for-the-badge&logo=slack&logoColor=white">
    </div>
</div>

## 🏛️ 시스템 아키텍처

## 🗂️ Directory 구조도

### BE

```
📦main
 ┣ 📂generated
 ┣ 📂java
 ┃ ┗ 📂com
 ┃ ┃ ┗ 📂seahere
 ┃ ┃ ┃ ┗ 📂backend
 ┃ ┃ ┃ ┃ ┣ 📂adjust
 ┃ ┃ ┃ ┃ ┣ 📂alarm
 ┃ ┃ ┃ ┃ ┣ 📂auth
 ┃ ┃ ┃ ┃ ┣ 📂common
 ┃ ┃ ┃ ┃ ┣ 📂company
 ┃ ┃ ┃ ┃ ┣ 📂follow
 ┃ ┃ ┃ ┃ ┣ 📂history
 ┃ ┃ ┃ ┃ ┣ 📂incoming
 ┃ ┃ ┃ ┃ ┣ 📂inventory
 ┃ ┃ ┃ ┃ ┣ 📂ocr
 ┃ ┃ ┃ ┃ ┣ 📂outgoing
 ┃ ┃ ┃ ┃ ┣ 📂product
 ┃ ┃ ┃ ┃ ┣ 📂qr
 ┃ ┃ ┃ ┃ ┣ 📂redis
 ┃ ┃ ┃ ┃ ┣ 📂s3
 ┃ ┃ ┃ ┃ ┣ 📂sales
 ┃ ┃ ┃ ┃ ┣ 📂user
 ┃ ┃ ┃ ┃ ┗ 📜BackendApplication.java
 ┗ 📂resources
```

### FE

```
📦src
 ┣ 📂api
 ┣ 📂assets
 ┣ 📂components
 ┣ 📂constants
 ┣ 📂hooks
 ┣ 📂pages
 ┣ 📂stores
 ┣ 📂types
```

## 🚀 핵심 기능

### 🪸 공통

#### 회원가입

#### 로그인

#### 알림 내역

#### 설정

#### 푸쉬 알림

### 🦑 브로커

#### 사업자 등록

#### 입고

#### 재고

#### 출고

#### 교환

### 🐙 커스터머

#### 출고 요청

#### 팔로우

## 팀원 소개

|                       김도영                       |                        정기석                        |                      장호영                       |                      안채원                      |
| :------------------------------------------------: | :--------------------------------------------------: | :-----------------------------------------------: | :----------------------------------------------: |
| <img src="../image/profile_kim.png" width="100" /> | <img src="../image/profile_jeong.png" width="120" /> | <img src="../image/profile_jang.png" width="120"> | <img src="../image/profile_ahn.png" width="100"> |
|             **Full-Stack** ,**Leader**             |                    **Full-Stack**                    |                  **Full-Stack**                   |                  **Full-Stack**                  |
|     [@kimdodo97](https://github.com/kimdodo97)     |      [@wjdrltjr5](https://github.com/wjdrltjr5)      |      [@jang643](https://github.com/jang643)       |  [@woneveryday](https://github.com/woneveryday)  |
