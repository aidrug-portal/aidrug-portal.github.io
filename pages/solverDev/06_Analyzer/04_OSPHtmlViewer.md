---
title: OSPHtmlViewer
tags: 
keywords:
sidebar: solverdev_sidebar
permalink: solverdev_analyzer_OSPHtmlViewer.html
folder: solverDev
---


html 파일 형식을 가시화 해주는 뷰어입니다. 출력포트의 포트 타입을 File로 설정한 경우에만 동작합니다. Three.js등의 그래픽 자바스크립트 라이브러리를 활용하여, 결과 데이터를 가시화 할 수 있습니다. 해석기에서 생성된 결과 데이터를 읽어오는 경우에는 읽어오는 데이터의 확장자를 js로 변경해야 합니다.
(브라우저 보안 정책상 js등의 일부 파일 확장자를 제외한 다를 확장자를 브라우저에서 불러오는 경우 이를 차단하고 있습니다.)

> html 뷰어를 통한 가시화가 아닌 Analyzer를 개발하여 등록하면 이러한 문제를 해결할 수 있습니다.

{% include image.html file="solverdev/07/osphtml.jpg" caption="OSPHtmlViewer" %}

