---
layout: post
title: Git & Github
comments: true
---
## Git
분산 버전관리 시스템 (형상 관리 도구)
- 버전 관리 시트템은 파일 변화를 시간에 따라 기록했다가 나중에 특정 시점의 버전을 다시 꺼내올 수 있는 시스템이다.
- 각 파일/프로젝트를 이전 상태로 되돌릴 수 있고 시간에 따른 수정내용을 비교할 수 있다.
- 소스코드를 주고 받을 필요 없이, 같은 파일을 여러 명이 동시에 작업하는 병렬 개발이 가능하다.

Git은 로컬시스템에서도 버전 관리가 가능하고 Git을 호스팅하는 원격시스템(서버)을 통해 다른 사람들과 협업도 가능하다.
## Github
Git 웹호스팅 서비스
원격서버에 복제본을 저장한다.

## Git 저장소 생성 및 파일관리
### 저장소 생성
로컬 저장소 생성 : `git init`
원격 저장소 생성 : Github 사이트 로그인 후 원격저장소 생성

원격저장소를 로컬 저장소에 clone
`git clone <원격저장소 경로>`
로컬저장소 변경 내용 원격저장소에 push
`git push`
원격저장소 내용을 로컬 저장소에 pull
`git pull`

### 파일관리
`git status`를 통해 파일 상태 확인
![파일관리](https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=http%3A%2F%2Fcfile26.uf.tistory.com%2Fimage%2F998E643C5AA61E2D0F3FA8)

##### 파일의 상태
- Tracked(관리 대상임)
    - Unmodified : 수정하지 않음
    - Modified : 파일이 변경되었음
    - Staged  : 커밋으로 저장소에 기록할 상태
- Untracked(관리 대상이 아님)
