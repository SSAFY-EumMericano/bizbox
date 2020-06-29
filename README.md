>🏆🏆🏆🏆 삼성 청년 SW 아카데미 (SSAFY) 공통프로젝트 프로젝트 부분 [우수상] 수상 🎉🎊    
>🏆🏆🏆🏆 삼성 청년 SW 아카데미 (SSAFY) 공통프로젝트 UCC 부분 [우수상] 수상 🎉🎊    
<img src="./Awards.jpg" width="700" height="600">

---
title: "Biz Box"
date: 2020-03-03 08:26:28 -0400
categories: Project Web Vue
---
[공공데이터를 이용한 주요상권 분석 웹 서비스]

## Youtube 
   [UCC] https://www.youtube.com/watch?v=P4kjNc-x7uQ   
   [발표영상] https://www.youtube.com/watch?v=9MpUnlvdAog&t=46s   


## Table of Contents
- [상권 분석 웹 서비스](#%ec%8b%9d%eb%8b%b9-%eb%a6%ac%eb%b7%b0-sns)
  - [Table of Contents](#table-of-contents)
  - [About](#about)
  - [사용기술](#%ec%82%ac%ec%9a%a9%ea%b8%b0%ec%88%a0)
  - [Team](#team)
  - [Demo](#demo)
  - [Stack](#stack)
  - [license](#license)
  
## **about**

## 상권 분석 웹 서비스
주요 상권 분석 및 업소 관리 웹 서비스

![메인화면](https://user-images.githubusercontent.com/56620330/75970732-23a19c80-5f14-11ea-881a-5162d4d43549.png)

공공데이터를 기반으로 다양한 상권지표 제공 및 상권의 종합 점수를 제공합니다.

또한 지역별 업종의 주요고객과 시간대를 추천하고 해당 업종의 매출 현황을 제공합니다.

로그인 기능을 이용하여 자신의 업소를 등록 할수 있고 통계데이터에 반영됩니다.


## **MyRole**

**Project Manager**   

JIRA를 이용하여 팀의 일정을 관리하고 정해진 기한까지 순조롭게 완료될 수 있도록 조율하고   

매일 아침과 저녁 간단하게 팀 회의(스크럼)를 진행하여 그날의 목표를 정해주었고,   

성취도에 따라 다음날 무엇을 해야할지 프로젝트 전반에 대해 고민했습니다.   

**BackEnd** 

상권분석을 위한 공공데이터를 수집하고 `MySql`을 통해 DB를 구축하였습니다.

`Spring` 프레임워크를 이용하여 상권의 생활인구 (유동인구 + 거주인구), 개폐업률 , 매출등을 제공하는 `Rest Controller`를 구현하였습니다.

**FrontEnd**   

서울지역의 지도를 기본 UI로 사용하기 위해 `KakaoMap API`를 이용하여 구현하였습니다.

`chart.js`를 통해 맵위에 임시그래프를 보여주어 간단하게 그 지역의 상권정보를 알 수 있게 만들었고, 

kakaomap의 원그리기와 상권 범위분석 api를 이용하여 원검색을 통해   
   
해당 원 내의 상권정보를 알 수 있는 기능을 만들었고, MAP의 CSS작업을 주로 진행했습니다.   

**DevOps**   

`AWS` EC2 서버에 jar 파일을 통한 배포로   

웹상에서 해당 프로젝트를 이용해볼 수 있도록 만들었습니다.   



## 사용기술

Spring boot : 상권 데이터 제공 Rest Controller 구현 

Kakao Login API : 간편 소셜 로그인 

KakaoMap API : 행정동 별 상권지표에 따른 색 구분

SpringSecurity + JWT : 로그인한 사용자만 서비스를 사용가능 하도록(filter), Token을 계속 검사해서 유효한 회원인지 확인

JavaScript : 유동인구, 매출현황, 연령별 매출 등 데이터 그래프 출력

MySql : 공공데이터를 기반으로 DB 구축

AWS : 호스팅

Qgis : 서울시의 행정동 공간정보 

jusoAPI : 도로명, 지번 등 주소를 통한 검색 구현

## Team

- 음영현
- 김재현
- 문지현
- 문요한
- 양희철
- 오승완

## Demo
[bizbox] -배포 종료- 

## Stack
<img src="https://user-images.githubusercontent.com/56620330/75417977-a60ae900-5975-11ea-9e05-bc6b938fb197.png" alt="스프링" style="zoom: 33%;" />    <img src="https://user-images.githubusercontent.com/56620330/75418145-144fab80-5976-11ea-9650-5f9fab957792.png" alt="뷰제이에스" style="zoom: 33%;" /> <img src="https://user-images.githubusercontent.com/56620330/75418176-26c9e500-5976-11ea-9cb8-8ce5f42013cb.PNG" alt="마이에스큐엘" style="zoom: 50%;" />

   <img src="https://user-images.githubusercontent.com/56620330/75417523-9ccd4c80-5974-11ea-801a-eea0ead0865b.PNG" alt="카카오맵" style="zoom:33%;" /> 

[jekyll-gh]:   https://github.com/EumYoungHyun/bizbox
[jekyll-talk]: http://i02a207.p.ssafy.io/
