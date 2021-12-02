![CUTE](/preview.jpg)
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
### _1. Github계정 & 원격/로컬 Repository 생성하기_
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
![theme2](/theme1.JPG)
_http://jekyllthemes.org/_


![theme2](/theme2.JPG)
_https://jekyllthemes.io/free_


_수업 notion의 두 사이트에서 마음에 드는 테마 선택_  
_테마 링크로 이동해 ZIP으로 다운_


![folder](/folder.JPG)  
_ZIP내부 파일을 모두 복사해 250b.github.io 폴더에 넣어 덮어씌움_


### _4. 테마와 Post 수정하기_
![config](/config.JPG)  
_config.yml의 title 을 수정함으로써 페이지의 제목을 BORI'S BLOG로 바꿨음  
navigation, social 부분 또한 적절하게 수정해 내 정보로 바꿔 넣었음  


![header](/header.JPG)  
_includes 폴더의 header 파일에서 불필요한 header는 없애고 내 github과 velog로 교체함  


![post](/post.JPG)  
각 post 파일에 글 작성  


![posts](/posts.JPG)  
_post 폴더에 작성한 post 파일들을 넣음 


![img](/img.JPG)  
post 구성에 쓰인 사진들은 기존 테마에서와 같게 assets/img 폴더에 담아 정리함  


![css](/css.JPG)  
assets/css 폴더의 style.css를 수정해 여러 post의 디자인을 조정.  
