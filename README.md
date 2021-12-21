# GithubInstruction

Github 장점
1. 버전관리가 용이하다.(프로그래밍 등의 성격 상 자주 수정이 되는 작업이다. 종종 이전에 버전으로 돌아갈 일이 생기는데, 이때 github가 유용하다.
2. 가장 많은 프로그래밍 코드가 있고, 오픈소드의 성지라 불린다.
3. 가장 대중적이다.
4. 가지치기(브랜치)가 용의하다(1의 이유때문에)
5. 협업이 좋다.

Github 사용법
1. Fork 
1) 다른 사람의 저장소에서 내 저장소로 복사해 오는 행위
2. Pull
1) 복사해온 상대의 저장소에서 업데이트가 된 사항을 당겨와서 업데이트를 한다.


Github (vs code ver) 명령어

- git init 
빈 git 저장소 만들기
- git config --global user.name "이름"
- git config --global user.email "메일 주소"

- git status 
커밋되어 있는지 확인, 새로운 내용 생성, 삭제 등 변화를 보여줌
- git add -A
묻을 것들에 포함시킨다.(-A, * : 전부 //. : 부분?)
- git commit -m "간단정보" 
타임캡슐 묻기
- git log
캡슐의 정보와 일련번호등 뜸 (vi 에디터 접속시 :q로 탈출)
- git reset (일련번호6자리) --hard 
일련번호와 일치하는 버전으로 이동(이전최근 commit 삭제)
- git revert (6자리) 
이전 버전 유지 후 복구하는 법(:wq로 탈출) 새로운 commit 추가

- git branch my-idea
my-idea라는 가지를 생성(현상태 복사)
-git checkout my-idea
my -idea라는 가지로 이동
-git checkout master (이동할 장소 입력)
가지 뻗기 전으로 이동 
-git merge (변화를 가져올 브랜치 이름)
브랜치의 값을 기존으로 가져올 때(병합)
- git log --graph --all --decorate
브랜치 했던 것을 시각화
- git rebase (브랜치 이름)
브랜치의 값을 기존으로 가져올 때(재배치)
