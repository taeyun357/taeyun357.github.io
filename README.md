# Jekyll Blog
Lanyon 테마를 이용해 작성한 Jekyll Blog

Github 프로젝트, 개발관련 지식 정리 -> [블로그 바로가기](https://haram8009.github.io)

## Blog Build 과정
### Jekyll 및 Lanyon 테마 설정하기
1. Lanyon 테마를 `fork`한다.
2. `_config.yml` 파일에서 `url`을 수정한다. [css 깨질시 포스트 참고](https://haram8009.github.io//2021/12/11/Css-%EA%B9%A8%EC%A7%90/)
3. 포스트 머릿말을 테마에 맞게 작성하고 포스팅한다.
### 테마 사이드바 설정
##### 사이드바 추가
마크다운 작성 시 파일 상단 머릿말을 다음과 같이 작성한다.
```
---
layout: page
title: About
---
페이지 내용
```
##### 기존 사이드바 수정
`_includes` 폴더 하위의 `sidebar.html`을 수정한다.

### 포스트 작성
`_posts` 폴더 안에 `년-월-일-제목.md`와 같은 이름으로 마크다운 파일을 생성한다.
머릿말의 layout을 post로 선택하면 `_layouts` 폴더 하위의 `post.html`을 이용해 페이지가 생성된다.


[참고한 블로그 사이트](https://velog.io/@eona1301/Github-Blog-%ED%8C%8C%EB%B9%84%EC%BD%98Favicon-%EC%84%B8%ED%8C%85%ED%95%98%EA%B8%B0)
