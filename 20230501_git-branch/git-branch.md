# Git branch

## git을 활용한 project를 할 경우 init 초기화를 하기 전에 README.md(설명서, 개요), .gitignore 를 생성한다.

- `git commit -am` : 기존의 트래킹 하고 있는 것을 스테이지에 올리면서 `commit` 함
  
## branch
- `master branch` : 상징적인 branch, 제대로 작동하는 SW
- 터미널~~~(master) <- branch : (스티커/ 책갈피)와 비슷한 의미
- HEAD : 현재 작업중인 커밋 / branch , `commit`은 HEAD가 위치한 곳에서 한다.
- `git chechout` : SHA 가 사용됨(전에 작업한 곳으로 사용) HEAD 이동
- `git log` : SHA, `commit -m` 날짜 등 모두 표기
- `git log --oneline` : 로그 짧게 한줄로 표시
- `git log --oneline --graph` : 짧게 보여준 로그를 그래프화
- `git branch` : branch 목록 보기
- `git branch <name>` : HEAD위치에 <name>란 branch 생성
- `git branch -d <name>` : branch 삭제
- `git switch <branch name>` : branch 이동 <-- HEAD 이동, SHA 필요 없음
- `git switch -c` : branch 생성 & 이동
- `checkout` : branch와 commit id 두개 모두를 사용가능함
- `switch` : branch 이름만 사용
- `git merge` : branch 와 branch를 합치는 명령어 / 움직여야 하는(합침을 당하는쪽에) branch에서 사용
  
  1. FF (Fast Forward)
  2. Auto Commit