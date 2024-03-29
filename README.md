# GIT

### GIT 기초
 - git init -master
 - git add
 - git commit
 - git log

### GIT 원격저장소
 - git remote add: git remote add [저장소이름] [저장소주소]
 - git remote: 원격저장소의 리스트(이름)
 - git remote -v: 원격저장소 목록보기

## GIT Branch

### GIT Branch 사용법
 - git branch: Branch의 리스트
 - git branch [브랜치이름]: 새로운 Branch 생성
 - git checkout -b [브랜치이름] & git switch -c [브랜치이름]: Branch 생성 후 해당 branch로 이동
 - git checkout [브랜치이름] & git switch [브랜치이름]: Branch 이동
 - git checkout -d [브랜치이름]: Branch 삭제
 - git merge [브랜치이름]: '현재 브랜치'에서 특정 브랜치를 병합

### GIT Merge 시나리오
 1. fast-forward merge
 2. auto-merge (without conflict)
 3. merge with conflict

#### Fast-forward: master에서 시작된 branch가 하나인 경우(master와 branch의 구분이 모호한 상황(?))
#### Auto-merge: master와 branch에서 수정한 파일이 서로 다른 경우
#### merge with conflict: master와 branch에서 같은 파일의 같은 부분을 수정한 경우

### Conflict의 정의
 - 동일 파일의 동일 내용을 변경할때