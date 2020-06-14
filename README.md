# 싸이월드 사진첩 이미지 백업을 위한 스크랩퍼

## 필요한 것

- `git clone` 할 수 있는 능력
- [node.js](https://nodejs.org/en/download/) app 를 실행할 수 있는 능력
- 웹 브라우저 개발자 도구에서 HTML 을 확인할 수 있는 능력

## 방법

1.  `npm install` 한다.

2.  백업하고 싶은 싸이월드 사진첩으로 간다.

3.  하단의 **더보기** 버튼을 계속 클릭하여 사진첩 끝까지 페이지를 로드한다.

4.  개발자도구를 열고 `<div class="postlist_area">` 부분을 찾고 해당 HTML 블록을 통째로 복사한다.

![image](https://user-images.githubusercontent.com/8033320/84590517-50017900-ae72-11ea-853e-c973cb09e1e3.png)

5.  프로젝트

## 사족

1. 내 것만 후딱 백업할려고
