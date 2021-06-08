# Git 공부하기

## git 학습
1. 형상관리의 필요성 이해하기
2. git 분산형 버전 관리 시스템 이해하기
3. git의 논리적 단위 이해하기 (commit)
4. git과 svn의 차이

## git branch 관리 학습
1. git flow 이해하기
2. git flow 실습하기 (feature, develop, hotfix, master)

## git repository 실습
1. main repository fork 하기
2. main repository 를 등록하고 update 받도록 설정하기
```
$ git remote add upstream https://github.com/said1573/Red_Study_Group.git
$ git remote -v
$ git fetch upstream
$ git checkout main
$ git merge upstream/main
$ git push origin main
```
3. 본인 git에 fork해온 repository 로컬에 clone 하기
4. 내용 수정하기
5. 본인 repository 로 push
6. main repository 로 pull Request 날리기 (git에 있는 pull request > new pull request)
7. main repository 가서 merge 하기

## git 그 외 기능
1. commit 합치기
2. rebase 등 .. 이해하기



