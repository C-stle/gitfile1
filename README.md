# gitfile1
해당 프로젝트 디렉토리로 이동
git init
git add .
- add 가 안되는 경우
git status 로 확인해서 untracked 상태를 tracked 상태로 바꿔주기
하나씩 바꿔줘야함
-> git add 파일명   으로 바꾸기

git commit -m "commit 네임"

git remote add origin (github 의 Repository 주소)

git push -u origin master

내려받기
git clone (해당 파일 주소)

변경된 내용 업데이트
git pull

아이디 / 이메일 설정
git config --global user.name "아이디"
git config --global user.email 
