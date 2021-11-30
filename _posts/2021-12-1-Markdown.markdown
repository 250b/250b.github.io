---
layout: post
title:  "Markdown"
date:   2021-12-1
---


<p class="intro">Markdown이란?<p>
<p class="gittext">Markdown은 텍스트 기반의 마크업언어로</p>
<p class="gittext">쉽게 쓰고 읽을 수 있으며 HTML로 변환이 가능</p>
<p class="gittext">특수기호와 문자를 이용한 매우 간단한 구조의 문법을 사용하여</p>
<p class="gittext">웹에서도 보다 빠르게 컨텐츠를 작성하고 보다 직관적으로 인식할 수 있음</p>
<br><br>
<p class="gittext">마크다운이 최근 각광받기 시작한 이유는 Github 덕분</p>
<p class="gittext">깃헙의 Repository에 관한 정보를 기록하는 README.md는</p>
<p class="gittext">Github을 사용하는 사람이라면 가장 먼저 접하게 되는 마크다운 문서임</p>
<p class="gittext">마크다운을 통해서 설치방법, 소스코드 설명, 이슈 등을 간단하게 기록하고</p>
<p class="gittext">가독성을 높일 수 있다는 강점이 부각되면서 여러 곳으로 퍼져가게 되었음</p>
<br><br><br><br>
<p class="intro">Markdown 문법<p>
<p class="list"><p class="listtitle">1. 제목-title</p></p> 
<p> </p>    
<p class="gittext">#를 1-6개 붙여서 제목 표현 가능</p>
<br>
<p class="gittext"># 제목1 - H1</p>
<p class="gittext"># 제목2 - H2</p>
<p class="gittext"># 제목3 - H3</p>
<p class="gittext"># 제목4 - H4</p>
<p class="gittext"># 제목5 - H5</p>
<p class="gittext"># 제목6 - H6</p>
<br>
<p class="picture"><img src="/assets/img/h.JPG" alt=""><p>
<br><br><br>
<p class="list"><p class="listtitle">2. 강조 - Emphasis</p></p> 
<p> </p>    
<p class="gittext">본문에 특정 문자에 서식(볼드, 이텔릭, 밑줄, 취소선)을 적용해 강조 가능</p>
<br>
<p class="gittext">*single asterisks 이텔릭체*</p>
<p class="gittext">_single underscores 이텔릭체_</p>
<p class="gittext">**double asterisks 볼드체**</p>
<p class="gittext">__double underscores 볼드체__</p>
<p class="gittext">***triple asterisks 볼드+이텔릭체***</p>
<p class="gittext">___tripple underscores 볼드+이텔릭체___</p>
<p class="gittext">~~cancelline 취소선~~</p>
<p class="gittext">**~~bold cancelline 볼드+취소선~~**</p>
<br><br>
<p class="picture"><img src="/assets/img/font.JPG" alt=""><p>
<br><br><br>
<p class="list"><p class="listtitle">3. 코드 - code</p></p> 
<p> </p> 
<p class="gittext">` (Grave)문자를 입력해서 본문의 내용중 코드강조 처리 가능</p>   
<br>
<p class="gittext">`<abbr>`요소를 대신 사용하십시오.</p>
<br>
<p class="picture"><img src="/assets/img/code.JPG" alt=""><p>
<br><br><br>
<p class="list"><p class="listtitle">4. 코드블럭 block</p></p>
<p> </p> 
<p class="gittext">태그 이용방식</p>   
<br>
<p class="picture"><img src="/assets/img/pre.JPG" alt=""><p>
<br>
<p class="gittext">코드블럭코드("```") 이용방식</p>   
<br>
<p class="picture"><img src="/assets/img/codeblock.JPG" alt=""><p>
<br><br><br>
<p class="list"><p class="listtitle">5. 수평선 - Horizontal Rule</p></p>
<p> </p>
<p class="gittext">'-','*','' 문자중 하나를 3번 연속 입력하여 추가</p>
<br><br>
<p class="gittext">* * *</p>
<p class="gittext">***</p>
<p class="gittext">*****</p>
<p class="gittext">_ _ _</p>
<br>
<p class="picture"><img src="/assets/img/hr.JPG" alt=""><p>
<br><br><br>
<p class="list"><p class="listtitle">6. 링크 - link</p></p>
<p> </p>
<p class="gittext">![title][link]로 링크 추가 가능</p>
<br><br><br>
<p class="list"><p class="listtitle">7. 이미지 - images</p></p>
<p> </p>
<p class="gittext">![대체텍스트](이미지 URLorPath "이미지설명")</p>
<p class="gittext">Link 와 문법이 비슷함, 앞에 !만 추가된 것</p>
<br><br><br>
