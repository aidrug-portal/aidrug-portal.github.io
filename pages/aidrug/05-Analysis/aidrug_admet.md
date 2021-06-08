---
title: AI based ADMET Analysis
tags: []
keywords:
summary: ""
sidebar: aidrug_sidebar
permalink: aidrug_admet.html
folder: aidrug
---

상단 메뉴의 `Analysis` - `AI based ADMET Analysis`를 클릭하여 이동합니다.

{% include image.html file="aidrug/admet_result.png" caption="ADMET Prediction" %}

예측하려는 분자의 Smiles 표현을 SMILES Input에 입력 후, `Predict` 버튼을 눌러 예측 모델을 실행합니다.

1. Structure에서 입력한 Smiles의 3차원 구조를 확인할 수 있습니다.
2. Properties에서 입력한 분자의 특성 값을 확인할 수 있습니다.
3. Abosrption, Distribution, Metabolism, Elimination, Toxicity에서 ADMET 예측을 확인할 수 있습니다.

ADMET 항목은 총 12개로 다음과 같습니다.
- `Absorption`: Passive Absorption (permeability)
- `Distribution`: Blood-Brain Barrier Penetration, P-gp Substrates (inhibitor)
- `Metabolism`: CYP1A2, CYP2D6, CYP2C9, CYP2C19, CYP3A4
- `Elimination`: Human, Mouse, Rat
- `Toxicity`: hERG inhibition