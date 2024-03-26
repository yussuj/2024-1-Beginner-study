# 1주차 배운것 복습

깃을 설치해준다. (override the default~버전으로 설치해야 한다. 쓰는칸에는 main으로 작성해야 한다.)
깃을 설치한후 터미널에 git help를 쳤을때 다양한 명령어가 나온다면 잘 설치한것!

깃을 처음에 설치한 후 이름과 이메일을 지정해주어야 한다.
git config --global user.name "내가 지정할 이름"
git config --global user.email "내가 지정할 이메일"
을 터미널에다가 작성한다.

<폴더 만들기>   
로컬디스크c - 사용자 - jys_123 에 폴더를 미리 만들어놓은후, 비주얼스튜디오 시작에서 폴더 열기를 통해 내가 만들어놓은 폴더를 연다.

<파일 만들기>
열어진 폴더에서 새 파일 클릭 후 파일을 만든다. (대문자로 쓰고 마크다운 형식으로 끝에 .md 붙여준다.)
터미널도 새로 만들어준다.

<디렉토리에 git 저장소 만들기>    
터미널에다가 git init 를 작성해준다.

<현재 위치한 저장소에 대한 정보를 알려준다>
터미널에다가 git status 를 작성해준다.

<git으로 관리할 대상 등록하기>    
터미널에다가 git add . 을 작성해준다.

<파일 수정 후 로컬 저장소로 옮기기>
터미널에다가 git commit -m "담고 싶은 메세지" 을 작성해준다. 

<깃의 commit 정보 확인하기>
터미널에다가 git log 를 작성해준다.

<레포지토리로 옮기기>
내가 작성한 파일을 저장해준다.
깃허브에 들어가 새로운 레포지토리를 하나 만들어준다.
만든 레포지토리에 들어가 git remote add origin https://github.com/yussuj/2024-1-Beginner-study.git
git branch -M main
git push -u origin main
등 다양한 명령어를 복붙 한후 터미널에 작성해준다.


https://github.com/yussuj