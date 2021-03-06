---
title: Analyzer (분석기)
tags: 
keywords:
sidebar: solverdev_sidebar
permalink: solverdev_analyzer.html
folder: solverDev
---

{% include image.html file="solverdev/03/image02_execution_scenario.png" caption="사이언스 앱 실행 시나리오" %}

분석기는 EDISON에서 앱 실행 결과 데이터를 분석/조회 할 수 있는 구성 요소를 말합니다. 현재 등록되어 있는 분석기 목록은 다음과 같습니다.

## 범용 분석기

|이름|설명|
|--|--|
|[OSPPlotViewer](./01_OSPPlotViewer.md)|[oneD](../03_Science_App_Programing/02_Output_programing/03_oneD.md) 파일 형식을 가시화하는 뷰어입니다.|
|[OSPTextViewer](./02_OSPTextViewer.md)|Text 결과 파일을 보여주는 뷰어입니다.|
|[OSPImageViewer](./03_OSPImageViewer.md)|JPG, PNG등 이미지 파일을 보여주는 뷰어입니다.|
|[OSPHtmlViewer](./04_OSPHtmlViewer.md)|Html 파일을 보여주는 뷰어입니다.|
|[JSMol](./05_JSmol.md)|Jmol의 자바스크립트 버전입니다.  |
|[ParaView](./06_ParaView.md)|PLOT3D등의 포멧을 가시화 해주는 3D 가시화 도구입니다.|
|[ProteinViewer](./07_ProteinViewer.md)|3D 단백질 뷰어입니다.|
|[PlotlyViewer](./08_PlotlyViewer.md)|[Plotly](../03_Science_App_Programing/02_Output_programing/04_Plotly.md) 라이브러리를 사용하여 다양한 Plot을 제공하는 뷰어입니다. |
|[NGLViewer](./09_NGLViewer.md)| Proteins and DNA/RNA 등의 분자 구조를 보여주는 뷰어입니다.|

그외 특정 앱에서 활용하는 분석기가 있습니다.
- SIESTA_analyzer
- runWTE_modeler
- runWTE_analyzer
