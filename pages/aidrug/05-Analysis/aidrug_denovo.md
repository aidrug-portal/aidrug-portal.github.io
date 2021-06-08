---
title: De Novo Drug Discovery
tags: []
keywords:
summary: ""
sidebar: aidrug_sidebar
permalink: aidrug_denovo.html
folder: aidrug
---

상단 메뉴의 `Analysis` - `De Novo Drug Discovery`를 클릭하여 이동합니다.

`Mode`에서 생성 모델을 선택할 수 있습니다.

## Scaffold 기반 de novo

Scaffold는 사용자가 입력한 구조를 기반으로 하여 해당 구조를 포함하는 분자들을 생성하는 모델입니다.

{% include image.html file="aidrug/denovo_scaffold.png" caption="Scaffold 기반 de novo" %}

1. Input Type
- `Smiles`: Smiles 형태의 String을 입력으로 선택합니다.
- `InChI`: InChI 형태의 String을 입력으로 선택합니다.
- `Mol Editor`: 분자 구조 편집기를 통한 입력을 선택합니다.
2. Results
- 생성하고자 하는 분자의 개수를 입력합니다. 최대 999개 가능합니다.
3. Scaffold
- Smiles, InChI의 경우 text box를 통해서 입력할 수 있으며 Mol Editor를 선택할 경우에는 분자 구조 편집기를 통해서 입력할 수 있습니다.

해당 작업은 `Cloud Running`과 `Interactive Running` 중 선택하여 실행을 할 수 있습니다. (Introduction - About - How to Use 참고)

## Properties 기반 de novo

Properties는 입력된 특성 값들을 만족하는 분자들을 생성하는 모델입니다.

{% include image.html file="aidrug/denovo_properties.png" caption="Properties 기반 de novo" %}

1. `logP`
- 분배 계수를 의미합니다. -5 ~ 10 사이의 값을 입력 가능합니다.
2. `mw`
- 분자 질량을 의미합니다. 0 ~ 500 사이의 값을 입력 가능합니다.
3. `QED`
- 약물 유사성을 의미합니다. 0 ~ 1 사이의 값을 입력 가능합니다.
4. `Results`
- 생성하고자 하는 분자의 개수를 입력합니다. 최대 999개 가능합니다.

해당 작업은 `Cloud Running`과 `Interactive Running` 중 선택하여 실행을 할 수 있습니다. (Introduction - About - How to Use 참고)

## 결과 화면

타일 형태의 이미지로 생성된 결과를 확인할 수 있으며 copy 버튼을 눌러 해당 분자의 Smiles를 복사할 수 있습니다. 또한 생성된 분자들의 Smiles를 csv 파일로 다운로드 받을 수 있습니다.

{% include image.html file="aidrug/denovo_result.png" caption="결과 화면" %}