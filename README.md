# public
Just another repository

Git
Repository 생성하는 법
branch 만드는 법
Commit, Push, Pull, Branch, Merge

Repositoy = 저장소
작업공간을 Git이 제공하는 자료구조 안에 압축시켜 넣은 것
일반적으로 로컬 저장소를 말하고, git init 명령어로 생성한다. 

remote repository = 원격 저장소
내 PC의 프로젝트 폴더 안 x 다른 서버에 위치
여러 사람이 서버에 있는 하나의 저장소를 공유해 공동으로 작업 가능

commit = 커밋, 변경사항, 이력
어떤 순간 작업공간의 상태를 저장한 것

branch = 커밋에서 분기한 것, 한 갈래 (개발 라인)
master = 기본 설정된 브랜치에 붙는 이름
origin = 기본 설정된 원격 주소에 붙는 별명
Tag = 커밋에 달아주는 별명 (알아보기 쉽게)
HEAD = 현 시점에서 작업 중인 브랜치를 가리키는 포인터

원격 명령어
git clone = 로컬에서의 git init에 해당하는 명령어.
원격에서 저장소를 최초로 가져올 때 git pull 대신 git clone.
git fetch = 원격에서 업데이트 된 저장소를 받아와 로컬 저장소를 갱신하는 명령어
git pull = git fetch한 다음 작업공간까지 갱신하는 명령어
git push = 원격에 내 로컬 저장소를 올리는 명령어
