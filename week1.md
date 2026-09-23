git: 코드 변경점 기록 (버전 관리 도구)
github: 온라인 백업, 공유, 협업 (온라인 코드 저장소)

1. pwd(print working directory)
directory=폴더
: 현재 내가 작업하고 있는 폴더를 보여달라

~: home

2. ls(list)
: 내 폴더 안에 있는 폴더 & 파일 내역을 보여줌

3. ls -a(list all)
: 숨겨진 파일(보통 .으로 시작함)도 모두 볼 수 있음

4. cd 폴더명(change directory)
: ls 명령어에서 확인된 폴더로 이동 가능

4-1. ..
: 한 단계 위의 폴더

4-2. 폴더명/폴더명
: 한 번에 더 깊이 들어갈 수 있음

------------------------------------------
git init -> git을 본격적으로 사용하기 위해 초기 세팅

git add 파일명 -> 저장하기 전 저장할 파일 지정

git commit -m "메세지 작성" -> 실제로 저장하는 명령어

git status -> 저장 여부 확인 명령어

git add .  -> 내 프로젝트의 변경사항을 한 번에 지정함, 점( . )은 현재 나의 경로 내의 모든 변경된 파일들을 말함

git log -> 저장 내역을 확인하는 명령어

------------------------------------------------------

git push "github 주소" 브랜치명 == git push origin 브랜치명 

git push origin main == git push (온라인으로 업로드하는거)

git switch login, git checkout login -> 브랜치 이동 명령어

git switch -c 브랜치이름, git checkout -b 브랜치이름 -> 브랜치 한번에 생성 & 이동

git switch 최종브랜치이름 스위치하고 git merge 합칠브랜치이름 -> 브랜치 합치는 명령어

근데 git merge 잘 안씀

pull request -> 제 코드 합쳐도 될까요 물어보는거

git pull origin 브랜치명 -> 깃허브의 변경사항을 내 컴퓨터에 반영하는 명령어(내 컴퓨터로 가져오는거)
