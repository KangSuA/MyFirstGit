# MyFirstGit
git connection test

---
###  0. github 계정 변경하기

git config --global user.name 계정_이름

git config --global user.email 계정_이메일

제어판 - 자격증명 관리자 - github관련 자격 증명 제거

일반 자격 증명 추가 - 연결할 github 계정 및 사용자 이름, 암호 입력

### 1. 지역 저장소 생성
지역 저장소(local repository) : 작업을 수행한 후 커밋을 저장한 컴퓨터

mkdir 디렉토리_이름

cd 디렉토리_이름

git init -> .git 디렉토리 생성 (숨김 폴더)

### 2. 원격 저장소 생성
원격 저장소(remote repository) : 지역 저장소가 아닌 컴퓨터나 서버에서 만든 저장소

github사이트에서 New repository선택

생성된 원격 저장소 주소는 <https://github.com/아이디/저장소이름>

git branch -M main // master브랜칭서 main브랜치로 변경 

### 3. 지역 저장소와 원격 저장소 연결

git remote add origin 저장소_주소

git remote -v // 원격 저장소 연결 확인

git push -u origin main // commit 완료한 상태에서 push해주어야 함.
