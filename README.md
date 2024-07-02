# testGit
깃허브 기능을 익히기 위한 저장소(2024)

## 새로운 공부는 언제나 흥분을 불러일으키지만 가끔은 지칠 때가 있다.

- 작성 일자: 2024년 7월 1일
- 작성자: domafordarwin

# Git의 3가지 작업 영역에 대한 이해

|작업 영역| 설명|
|---|---|
|Working Directory| - 이력 관리 대상 파일들이 위치하는 영역<br> - 저장소 디렉토리에서 .git 폴더를 제외한 공간 <br> - 작업 중인 파일이나 코드가 저장되는 공간|
|Staging Area| - 이력을 기록할, 즉 커밋을 진행할 대상 파일들이 위치하는 영역 <br> - .git 폴더 하위에 파일 형태로 존재(index)|
|Repository| - 이력이 기록된 파일들이 있는 영역 <br> - .git 폴더에 이력 관리를 위한 모든 정보가 저장, 관리됨|


# 기본 명령어
* git init - 저장소 생성
* git config user.name "  "
* git config user.email "  "
* git config --list
* git config
* git help

---
# 기본 명령어 2
* git status
* git add
* git add.
* git commit
* git commit -m " "
* git commiit -am "  "

---
# 기본 명령어 3
* git status
* git status -s
* git log
* git log --pretty=oneline
* git log --oneline
* git log --graph

* git show
* git show HEAD
* git show HEAD^^^
* git show HEAD~n

---
# 기본 명령어 4
* git commit --amend
* git commit --amend -m "  "
  
