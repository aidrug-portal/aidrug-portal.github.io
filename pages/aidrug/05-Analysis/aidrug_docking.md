---
title: Docking Simulation
tags: []
keywords:
summary: ""
sidebar: aidrug_sidebar
permalink: aidrug_docking.html
folder: aidrug
---

상단 메뉴의 `Analysis` - `Docking Simulation`를 클릭하여 이동합니다.

## File Upload

{% include image.html file="aidrug/docking_upload.png" caption="File Upload" %}

1. `Receptor`는 target 단백질로 하나의 파일을 (pdb, pdbqt, mol2) 업로드할 수 있습니다.
2. `Ligand`에는 csv, pdb, pdbqt, mol2 파일을 업로드할 수 있습니다.
- csv의 경우 ligand list를 포함한 하나의 csv를 업로드 합니다.
- 나머지 파일의 경우 여러개의 파일을 업로드할 수 있습니다.

## Select Pocket & Optional Parameters

{% include image.html file="aidrug/docking_pocket.png" caption="Select Pocket & Optional Parameters" %}

1. Select Pocket에서 `Auto`를 선택할 경우 자동으로 pocket의 위치와 크기를 계산합니다. `Custom`의 경우 3차원 pocket의 중심과 각 변의 길이를 입력합니다.
2. Optional Parameters에서 사용할 cpu의 개수를 설정합니다.

`Submit` 버튼을 눌러 실행합니다. 해당 작업은 `Cloud Running`으로만 실행 가능합니다.

## 결과 화면

Job Monitoring에서 제출한 작업을 확인합니다.

{% include image.html file="aidrug/docking_result1.png" caption="결과 화면 (1)" %}

실행된 시뮬레이션에 대해서 가장 좋은 점수를 기록한 ligand 순서로 정렬하여 결과를 보여줍니다.

실행 결과에 대한 결과를 csv로 다운로드 받을 수 있습니다.


{% include image.html file="aidrug/docking_result2.png" caption="결과 화면 (2)" %}

ligand 그림을 클릭하면 3D 뷰와 구체적인 시뮬레이션 결과를 확인할 수 있습니다.