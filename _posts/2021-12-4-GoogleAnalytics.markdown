---
layout: post
title:  "Google Analytics"
date:   2021-12-4
description: Gitbub page와 Google Analytics 연동 방법
comments: true
---

<br><br>
<p class="intro">Google Analytics란?<p>
<p class="gittext">구글에서 무료로 제공하고 있는 웹분석 서비스</p>
<br><br><br>
<p class="intro">Gitbub page와 Google Analytics 연동 방법<p>
<p class="list"><p class="listtitle">1. Google Analytics 계정 생성</p></p> 
<p class="list"><p class="listtitle">2. Google Analytics 속성 생성</p></p>
<p> </p>
<br>
<p class="picture"><img src="/assets/img/1.JPG" alt=""><p>
<p class="gittext">속성 열에서 속성만들기 클릭</p>
<br><br><br><br><br>
<p class="picture"><img src="/assets/img/2.JPG" alt=""></p>
<p class="gittext">속성 이름과 시간대, 통화 입력</p>
<br><br><br><br><br>
<p class="list"><p class="listtitle">단! 추적ID로 G-가 아닌 UA-가 필요하다면</p></p>
<p class="gittext"></p>
<p class="gittext">고급 옵션 보기 누르고</p>
<p class="picture"><img src="/assets/img/3.JPG" alt=""><p>
<p class="gittext">유니버설 애널리틱스 속성 만들기 활성화</p>
<p class="gittext">웹사이트 URL입력</p>
<p class="gittext">유니버설 애널리틱스 속성만 만들기 클릭</p>
<p> </p>
<br><br><br>
<p class="list"><p class="listtitle">3. 비즈니스 정보 선택</p></p>
<p class="picture"><img src="/assets/img/4.JPG" alt=""><p>
<p class="gittext">업종, 비즈니스 규모, 사용 계획 선택</p>
<p class="gittext">만들기 클릭</p>
<br><br><br><br><br>
<p class="list"><p class="listtitle">4. 추적 ID 얻기</p></p>
<p class="gittext">1)추적 ID로 G-를 얻고싶다면?</p>
<p class="picture"><img src="/assets/img/5.JPG" alt=""><p>
<p class="gittext">속성 열에서 데이터 스트림을 입력한 후 생성하면</p>
<br><br><br><br>
<p class="picture"><img src="/assets/img/7.JPG" alt=""><p>
<p class="gittext">속성 열 데이터 스트림에서 G- 확인, 복사하기</p>
<p> </p>
<br><br><br><br><br>
<p class="gittext">2)추적 ID로 UA-를 얻고싶다면?</p>
<p class="picture"><img src="/assets/img/6.JPG" alt=""></p>
<p class="gittext">속성 열 데이터 스트림에서</p>
<p class="gittext">추적 ID UA- 확인, 복사하기</p>
<p> </p>
<br><br><br><br>
<p class="list"><p class="listtitle">5._config.yml 수정하기</p></p>
<p class="picture"><img src="/assets/img/config.JPG" alt=""></p>
<p class="gittext">요구되는 형식에 맞춰 google_analytics 부분을 수정</p>
<p> </p>
<br><br><br><br><br>
<p class="list"><p class="listtitle">연동 완료</p></p>
<p class="picture"><img src="/assets/img/8.JPG" alt=""></p>
<br><br><br><br>