![CUTE](/readme_img/preview.jpg)
# _MY GITHUB PAGE_250b_
#### _유레카 프로젝트 수업을 통해 만든 깃헙 블로그_
---
## _Build 과정_
- _Github계정 & 원격/로컬 Repository 생성하기_
- _Jekyll 설치하기_
- _테마 입히기_
- _테마와 Post 수정하기_
- _favicon 수정하기_
- _댓글 기능 추가하기_
- _Google Analytics 추가하기_
---
### ***1. Github계정 & 원격/로컬 Repository 생성하기***
_먼저 Git을 설치_  
_그 다음 Github 계정을 생성해야 하지만_  
_기존에 쓰던 Github 계정이 있기 때문에 따로 생성하진 않음_


_Github Page를 만들 것이기 때문에 Repository name을_  
_<username.github.io>로 지정해 Repository를 하나 생성_  
_내 username은 250b 이기 때문에 Repository name을 '250b.github.io'로 지정함_

_`clone` 명령어를 통해 원격저장소와 로컬저장소 연결_

_https://250b.github.io/blog/Git&Github/_  
ㄴ보다 자세한 과정과 사진은 위 Post에 포함되어있음  
(+ Git & Github에 대한 설명, Git 이용방법)


### _2. Jekyll 설치하기_
_https://rubyinstaller.org/downloads/_  
_위 페이지에서 윈도우용 루비 + 개발자킷(DevKit) 설치 프로그램을 다운로드 후 설치_
_루비 설치가 정상적으로 완료되면, Start Command Prompt with Ruby를 실행_


_` gem install jekyll bundler` 를 입력해 패키지 설치_  
_` jekyll -v` 를 입력해 jekyll이 잘 설치되었는지 확인_  
_자신의 블로그 디렉토리로 이동_  
_` jekyll new .` 를 입력해 현재 디렉토리 내부에 블로그 파일 생성_  
_` jekyll serve` 를 입력해 지킬 실행_  

_위의 과정을 통해 Jekyll 환경을 구성함_


### _3. 테마 입히기_  


_http://jekyllthemes.org/_  


_https://jekyllthemes.io/free_


_수업 notion의 두 사이트에서 마음에 드는 테마 선택_  
_테마 링크로 이동해 ZIP으로 다운_  


_ZIP내부 파일을 모두 복사해 250b.github.io 폴더에 넣어 덮어씌움_


### _4. 테마와 Post 수정하기_

*_config.yml의 title 을 수정함으로써 페이지의 제목을 BORI'S BLOG로 바꿈*   
_navigation, social 부분 또한 적절하게 수정_  


*_includes 폴더의 header 파일에서 불필요한 header는 없애고 내 github과 velog로 교체*  


_각 post 파일에 html 형식으로 글 작성_  


*작성한 post 파일들을 _post 폴더에 넣음*  


*_post 구성에 쓰인 사진들은 assets/img 폴더에 담음*  


_assets/css 폴더의 style.css를 수정해 여러 post의 디자인, 배치 조정_  


![modify](/readme_img/modify.JPG)  

### _5. favicon 수정하기_
_favicon이란?_
_즐겨찾기(favorites)와 아이콘(icon)의 합성어로,_
_주소창에 조그맣게 표시되는 아이콘_  


![fav](/readme_img/fav.JPG)  
_원하는 사진을 찾아 .ico로 변환한 후_
_파일 이름을 favicon으로 바꾸고_  
_assets/img에 넣어 기존의 것과 교체_  


### _6. 댓글 기능 추가하기_  

_https://disqus.com_  
_Disqus 가입_  

_"I want to install Disqus on my site"_ 선택  
_Website Name 기입 ( 나중에 필요하니 잘 기억해두기)_  
_나는 Git 계정 이름과 동일하게 250b로 지정함_  
_Category 는 Tech로 설정_  
_Create Site 클릭_  

_여러 버전 중 Basic을 선택, 하단 Subscribe Now 버튼 클릭_  
_Jekyll을 사용해 블로그를 만들었으므로, 많은 플랫폼 중 Jekyll 선택_  


_configure 버튼 클릭_  
_이전의 Website Name, Website URL, 입력_  
_나는 250b, https://250b.github.io 입력함_  
_Next 버튼 클릭_  

_두가지 선택사항이 나오는데 원하는 정책으로 선택_
_나는 Balanced를 선택했음_  
_Complete Setup 버튼 클릭_  


_해당 Website Name으로 지정되게 이동_
_Disqus Home의 상단 Admin 클릭_
_installing Disqus 클릭_  
_본문의 Universal Embed Code 클릭_  
_하단 코드 복사 (코드에 Example이 아닌 자신의 Website Name이 들어가있는지 확인)_  
_(사진은 강의자료 참고)_

![config](/readme_img/config.JPG)  
*_config.yml 파일을 열어 위와 같이 수정*  

![layout](/readme_img/layout.JPG)  
*_layouts/post.html 을 열어 복사해둔 코드 붙여넣기(테마마다 다를 수 있음)*  
_복사한 코드가 강의 자료의 코드와 달라 참고해 수정함_  


![comments](/readme_img/comments.JPG)  
_댓글 기능을 추가하고 싶은 post의 파일에 comments: true 설정을 추가_  



### _7. Google Analytics 추가하기_
_https://250b.github.io/blog/GoogleAnalytics/_  
_ㄴ자세한 과정과 사진이 위 post에 포함되어있음_  
_(추적 ID로 UA-형식이 필요했기 때문에 그에 따른 방법으로 진행함)_  

-----  


### _https://250b.github.io/blog/Git&Github/_  
### _위 링크에 적힌 방식처럼 Git에 commit하고, push해_
### _250b.github.io 파일 내부의 변화를 페이지에 적용시킴_