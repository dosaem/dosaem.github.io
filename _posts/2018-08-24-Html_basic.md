---
layout: post
title: "HTML 기본 01-04"
description: "간단정리"
categories: [FrontEnd]
tags: [HTML]
redirect_from:
  - /2018/08/24/
---
```

태그란?
HTML문서를 구성하고 있는 요소.
태그에는 이름과 속성이 있음.

HTML 전체적인 구조
<html>로 시작 </html>로 종료

사이에 크게 두단락 <head>, <body>
<head>는 주로 설정값
<body> 실제로 정보를 전달하기위한 내용
```

```
<!DOCTYPE html>

<html lang = "en" xmlns="http://www.w3.org/1999/xhtml">
<head>
    <meta charset="utf-8" />
    <title>TITLE</title>
</head>

<body>
    <h1> h1태그 입니다. </h1>
    <h2> h2태그 입니다. </h2>
    <h3> h3태그 입니다. </h3>
    <h4> h4태그 입니다. </h4>
    <h5> h5태그 입니다. </h5>
    <h6> h6태그 입니다. </h6>

    <p>주로 본문에 사용되는 태그, 단락구분<br />행바꿈 태그</p>

    <p><a href="https://www.google.co.kr/"> 구글홈페이지</a></p>

    <p><i>KOREA</i></p>
    <p>KOREA<sup>seoul</sup></p>
    <p><ins>KOREA</ins></p>
    <p><del>delete</del></p>


</body>

</html>
```


![캡처.JPG](C:\Users\dosaem\Desktop\캡처.JPG)