---
title: AI based Virtual Screening
tags: []
keywords:
summary: ""
sidebar: aidrug_sidebar
permalink: aidrug_virtual_screening.html
folder: aidrug
---

상단 메뉴의 `Analysis` - `AI based Virtual Screening`을 클릭하여 이동합니다.

Target 단백질과 ligand list를 입력하여 원하는 약물을 screening 가능합니다.

각 단계별로 ON / OFF 기능을 통해서 필요한 단계만 선택하여 실행할 수 있습니다.

해당 작업은 `Cloud Running`과 `Interactive Running` 중 선택하여 실행을 할 수 있습니다. (Introduction - About - How to Use 참고)

## File Upload

{% include image.html file="aidrug/vs_upload.png" caption="File Upload" %}

- `Smiles List File`: Screening 하고자 하는 ligand를 담은 csv 파일을 업로드합니다. Ligand는 Smiles 형태이어야 합니다.
- `PDB File`: Target 단백질에 해당하는 pdb 파일을 업로드합니다.
- `FASTA File`: Target 단백질에 해당하는 fasta 파일을 업로드합니다.

## Pre Processing

{% include image.html file="aidrug/vs_preprocess.png" caption="Pre Processing" %}

`AlogP`, `Molecular Weight`, `HBA`, `HBD`, `PSA`, `Rotatable Bonds`, `Aromatic Rings`, `Heavy Atoms` 8개의 항목에 대해서 값의 범위를 설정하여 업로드한 ligand list를 1차 필터링합니다.

## Virtual Screening

{% include image.html file="aidrug/vs_screening.png" caption="Virtual Screening" %}

단백질과 ligand에 대해서 인공지능 모델 기반의 Drug-Target Interaction을 수행합니다. 

Screened Compound 개수를 설정하여 예측 값이 높은 ligand들을 우선적으로 필터링합니다.

## Post Processing

{% include image.html file="aidrug/vs_postprocess.png" caption="Post Processing" %}

최종적으로 필터링된 ligand에 대해서 인공지능 기반의 ADMET (Absorption, Distribution, Metabolism, Excretion and Toxicity) 분석을 통해 유효성을 검사합니다.

단계 선택 후 `Submit` 버튼을 눌러 실행합니다.

## 결과 화면

각 단계별로 입력 및 출력 개수를 확인할 수 있으며 csv 파일로 다운로드 받을 수 있습니다.


{% include image.html file="aidrug/vs_result1.png" caption="결과 화면 (1)" %}

Virtual Screening의 경우 입력된 ligand에 대한 drug-target interaction 예측 값의 분포를 확인할 수 있습니다.


{% include image.html file="aidrug/vs_result2.png" caption="결과 화면 (2)" %}

Post Processing에서는 최종 결과물의 일부에 대해서 각 단계별 결과 값을 바로 확인할 수 있습니다.


