# 2주차 배운것 복습

<Fork>
다른 사용자의 레포지토리를 자신의 계정으로 복사하여 독립적으로 수정하고 관리한다.

<Star>
관심 있는 레포지토리나 프로젝트에 star을 달아 "북마크"와 같이 관리한다.

<Issue>
레포지토리에서 작업 계획, 토론 및 추적을 위해 활용한다.

<Branch>
기존 브랜치에서 분기되어 생성되는 별도의 작업 공간이다.
fork와 달리 같은 레포지토리에 생성된다.

<Branch Naming Convention>
"type/issue번호-간략한설명"

<Pull request>
분기된 브랜치를 다시 병합하기 위한 절차이다.
새로운 변경을 제안하거나 병합 시 발생하는 충돌을 해결한다.
Merge에 앞서 코드 리뷰

Merge에는 세가지 옵션이 존재한다.
1. Merge commit 
두 브랜치를 공통 부모로 하는 새로운 commit을 만든다. 
여러개의 커밋이 그대로 main 브랜치로 병합된다.

2. Squash and Merge
여러개의 커밋을 squash한다.
하나의 커밋으로 main 브랜치로 병합된다.

3. Rebase and Merge
여러개의 커밋의 base를 재설정한다.
모두 새로운 커밋으로 변경된다.
commit hash가 변경되어 무수한 충돌을 경험할 수 있으니 사용에 주의한다.

여기서 commit hash란?
commit id로 commit의 식별을 위해 사용하는 40자 길이의 16진수이다.
중복 확률은 2의 80제곱 분의 1
SHA-1 해시 함수를 사용한다.

<이슈 만들기>
레포지토리에 들어가 issues - new issue 로 들어가 타이틀과 description을 작성한다.
이슈 타이틀 #뒤에 숫자가 이슈번호이다.

<브랜치 만들기>
1. 현재 브랜치 확인하기
터미널을 열고 git branch 입력

2. 모든 브랜치 확인하기
터미널을 열고 git branch -a 입력
*이 붙어있는 브랜치가 현재 위치한 브랜치이다.

3. 브랜치 생성하기
터미널을 열고 git branch "브랜치 이름/이슈번호-간략한설명"  입력

4. 브랜치 삭제하기
터미널을 열고 git branch -D "삭제할 브랜치이름"
현재 있는 브랜치를 지우려면 다른 브랜치로 먼저 이동해야 한다.

5. 브랜치 이동하기
터미널을 열고 git checkout 브랜치이름  입력

6. 브랜치 생성 후 이동하기
터미널을 열고 git checkout -b "브랜치이름"  입력

<Pull request 하기>
레포지토리에서 Pull requests - new pull request 로 들어가 compare main에서 compare 내가 저장한 브랜치 이름으로 바꿔준다.
그러면 만들었던 commit들이 밑에 뜬다.
create pull request-타이틀을 작성해준후-create pull request

<Merge 하기>
3가지중 원하는 것으로 진행
원하는 merge를 선택 후, 선택한 merge 칸을 다시 눌러줌
confirm ~ merge 클릭
main 브런치에 파일이 저장되어 있음


https://github.com/yussuj/2024-1-Beginner-study/blob/main/README.md