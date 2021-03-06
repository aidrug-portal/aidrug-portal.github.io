---
title: Science App 프로그래밍 개요
tags: [EDISON, Platform, Science App, Programing]
keywords:
sidebar: solverdev_sidebar
permalink: solverdev_Science_App_Programing.html
folder: solverDev 
---

EDISON 플랫폼은 리눅스(CentOS)기반에서 동작하고 있으며, 시뮬레이션 SW의 경우 리눅스 환경에서 동작해야 합니다. 컴파일이 필요한 언어인 경우 리눅스(CentOS)에서 컴파일이 완료 되어야 합니다. 이를 위해 시뮬레이션 SW 개발자들을 위한 개발자(Bulb) 서버를 제공하고 있으며, Bulb 환경에서 동작하는 실행 파일(or 스크립트)로 개발 되어야 합니다.

{% include image.html file="solverdev/03/image04.png" caption="사이언스 앱 구성" %}

 - 입력 데이터를 받는 방법은 명령행 인자(Command Line Argument) 방식을 이용해 입력 데이터를 파일 형태로 읽어야 합니다.
 - 해석 결과 데이터는 파일 형태로 출력해야 하며, result 폴더에 생성되어야 합니다.
 - ```stdout```, ```stderr``` 함수를 이용해 실행 사용자에게 제공하고자 하는 정보를 전달할 수 있습니다.

입출력 프로그래밍에 대한 기본적인 방법에 대해 알아보고, 각 언어별 프로그래밍 방법을 배워봅시다.
