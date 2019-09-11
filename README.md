# algorithm

Git Fork ~ Pull Request
Fork 를 눌러 본인의 원격 저장소에 해당 레퍼지토리 복사.
bash / command 창에서 로컬 저장소로 이동.
git clone https://github.com/[본인아이디]/[레퍼지토리명] -b [브랜치이름] --single-branch 명령으로 로컬 저장소에 해당 레퍼지토리 복사.
작업 후, git add [파일명 혹은 폴더명] 명령으로 존재하거나 새로운 파일 스테이징.
git commit -m "메시지" 명령으로 로컬에서 원격 저장소로 커밋.
git push origin [브랜치이름]
본인의 원격 저장소에서 기존의 원격 저장소로 create new pull request 수행.
기존 원격 저장소의 master가 아닌 본인 브랜치인지 확인할 것!
[참고] git add/commit/push 취소하기
