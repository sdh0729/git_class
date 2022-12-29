# [1] 깃 초기 설정
* `$ git config --global user.name "이름"`
* ` $ git config --global user.email "메일주소"`
# [2] 깃 기본 명령어
* `git init` 시작
* `git status` 상태
* `git add .` working directory 에 추가 (전부)
* `git add a.txt` working directory 에 추가 (하나씩)
* `git commit -m "first commit"` - 깃에 커밋 
* `git log` - 로그 확인
    * `--oneline` : 한줄 축약
    * `--graph` : 브랜치와 머지 내역을 그래프로 보여줌
    * `--all` :모든 브랜치의 내역 보여줌
    * `--reverse` : 커밋내역을 역순으로 보여줌
    * `-p`: 파일의 변경 내용도 같이 보여줌
* .gitignore 파일에 무시할거 미리넣고 하기
# [3] 브랜치와 머지
* `$ git branch` -목록 확인
* `$ git branch -r` 원격저장소의 브랜치 목록 확인
* `$ git branch <브랜치이름>` - 브랜치 생성
* `$ git branch -d(D)<브랜치 이름>` - 삭제 (강제 삭제)
* `git switch (-c) 이름` - 브랜치 생성(과 이동  동시에)
* `git merge 브랜치이름` 현재 브랜치에 머지