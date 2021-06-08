---
title: Easy AI Model Development
tags: []
keywords:
summary: ""
sidebar: aidrug_sidebar
permalink: aidrug_easy_dev.html
folder: aidrug
---

상단 메뉴의 `Analysis` - `Easy AI Model Development`를 클릭하여 이동합니다.

## File Upload

{% include image.html file="aidrug/easy_upload.png" caption="File Upload" %}

학습을 진행할 csv 파일 형태의 dataset을 업로드합니다. 해당 파일은 Smiles와 label 2개의 column으로 구성되어야 합니다. 

`CSV File template` 버튼을 눌러 예시 파일을 확인할 수 있습니다.

## Select Task & Optional Parameters

{% include image.html file="aidrug/easy_task.png" caption="Select Task & Optional Parameters" %}

1. Select Task
- Classification, Regression 중에서 업로드한 dataset에 알맞은 작업을 선택합니다.
2. Optional Parameters
- `Split ratio`: Train set / Valid set 비율을 설정합니다. Valid set의 절반은 Test set으로 사용됩니다.
- `Time`: 설정한 시간이 넘어가면 작업을 중간에 종료합니다.
- `nCores`: Cpu 개수를 선택합니다.

`Submit` 버튼을 눌러 실행합니다. 해당 작업은 `Cloud Running`으로만 실행 가능합니다.

## 결과 화면

Job Monitoring에서 제출한 작업을 확인합니다.

{% include image.html file="aidrug/easy_result.png" caption="결과 화면" %}

- `Ouput Info`: 학습에 사용된 파라미터 정보와 학습 결과에 대한 정보를 보여줍니다.
- `Loss Graph`: Epoch에 따른 train, validation loss를 보여줍니다.
- `Test Score`: Test set에 대한 예측 결과를 보여줍니다.
- `File Download`: 학습 모델과 학습 결과를 다운로드 받을 수 있습니다.
- `Create AI Service`: 학습된 모델을 기반으로 AI Service를 생성합니다. (To be developed)