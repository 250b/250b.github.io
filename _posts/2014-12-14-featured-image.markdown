---
layout: post
title:  "Git & Github"
date:   2014-11-28
image: keyboard.gif
---
<br><br>
<p class="intro">Git이란?<p>
<p class="gittext">Git은 컴퓨터 파일의 변경사항을 추적하고 여러 명의 사용자들 간에</p>
<p class="gittext">해당 파일들의 작업을 조율하기 위한 분산 버전 관리 시스템</p>
<br><br><br>
<p class="intro">Github이란?<p>
<p class="gittext">GitHub은 Git을 기반으로 소스 코드를 호스팅 하고,</p>
<p class="gittext">협업 지원 기능들을 지원하는 웹서비스</p>
<br><br><br>
<p class="intro">Github 사용해보기!<p>
<p class="list"><p class="listtitle">1. Git 설치하기</p></p> 
<p> </p>    
<p class="gittext">설치 후 cmd창을 열어 git --version을 입력</p>
<p class="gittext">잘 나온다면 설치 성공!</p>
<br><br><br>        
<p class="list"><p class="listtitle">2. Github계정 & Repository 생성하기</p></p>
<p> </p>
<br>
<p class="picture"><img src="/assets/img/repository.JPG" alt=""><p>
<p class="gittext">초록색 new 버튼 클릭</p>
<br><br><br><br>
<p class="picture"><img src="/assets/img/create.JPG" alt=""></p>
<p class="gittext">Repository name을 입력한 후,</p>
<br><br>
<p class="gittext">누구나 볼 수 있는 public 으로 생성할 것인지,</p>
<p class="gittext">자신과 자신이 설정한 사람만 볼 수 있는</p>
<p class="gittext">private으로 생성할 것인지 선택</p>
<br><br>
<p class="gittext">아래 Initialize this repository with a README는</p>
<p class="gittext">README.md 파일을 생성할 것인지를 물어보는 것</p>
<br><br><br><br>
<p class="list"><p class="listtitle">3. 원격저장소와 로컬저장소 연결하기</p></p>
<p> </p>
<br>
<p class="gittext">로컬저장소의 경로를 정해 cd 명령어로 이동</p>
<p class="pictur"><img src="/assets/img/clone.JPG" alt=""></p>
<p class="gittext">위에 보이는 원격저장소 주소를 복사해</p>
<p class="gittext">cmd에 'git clone 원격저장소 주소'를 입력</p>  
<br><br><br><br>
<div class="gittext">   
    <p>.</p>
    <p>.</p>
    <p>.</p>
    <p>이러면</p>
</div>
<p> </p>
<p class="rmx">Github 사용준비 끝!<p>
<br><br>
<p class="picture"><img src="/assets/img/github.png" alt=""></p>    
<p class="list"><p class="listtitle">4. 파일의 생성/ 변경/ 삭제를 git 인덱스에 추가</p></p>
<p class="gittext">로컬저장소의 파일을 'git add 파일명' 명령으로 인덱스에 추가</p>
<p class="gittext">git 인덱스=</p>
<p class="gittext">저장소에 커밋을 할 준비를 하기위해 변경 내용을 임시로 저장할 위치</p>
<br><br><br>
<p class="list"><p class="listtitle">5. 변경 결과를 로컬 저장소에 커밋</p></p>
<p class="gittext">추가 된 파일을 'git commit -m "~~~~" 명령을 사용해 커밋</p>
<br><br><br>
<p class="list"><p class="listtitle">6. 원격저장소에 반영</p></p>
<p class="gittext">'git push origin master' 명령을 사용해</p>
<p class="gittext">로컬저장소의 변경 사항을 Github의 원격저장소에 반영</p>
