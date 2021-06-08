---
title: Compound Search
tags: []
keywords:
summary: ""
sidebar: aidrug_sidebar
permalink: aidrug_compound_search.html
folder: aidrug
---

상단 메뉴의 `Data` - `Compound Search`를 클릭하여 이동합니다.

## 검색 옵션

{% include image.html file="aidrug/data_cs_input.png" caption="Compound Search 입력" %}

1. Search Type
- `Exact`: 입력된 화합물 구조와 정확하게 일치하는 compound를 검색합니다.
- `Similarity`: 입력된 화합물 구조와 유사한 compound를 검색합니다. 0 ~ 1 사이의 유사도 값을 지정하여 해당 값 이상의 유사도를 보여주는 모든 compound를 반환합니다.
- `Substructure`: 입력된 화합물 구조를 포함하고 있는 모든 compound를 검색합니다.
2. Input Type
- `Smiles`: Smiles 형태의 String을 입력으로 선택합니다.
- `InChI`: InChI 형태의 String을 입력으로 선택합니다.
- `Mol Editor`: 분자 구조 편집기를 통한 입력을 선택합니다.
3. Input String
- Smiles, InChI의 경우 text box를 통해서 입력할 수 있으며 Mol Editor를 선택할 경우에는 분자 구조 편집기를 통해서 입력할 수 있습니다.

{% include image.html file="aidrug/data_cs_editor.png" caption="분자 구조 편집기" %}


`Submit` 버튼을 눌러 실행합니다.

## 결과 화면

{% include image.html file="aidrug/data_cs_result.png" caption="검색 결과" %}

검색된 compound의 `image`, `id`, `Smiles`, `Similarity` 항목을 보여줍니다.

Similarity는 Similarity, Substructure 모드로 검색할 경우 값이 표시됩니다.

각 compound를 클릭하면 해당 데이터베이스의 상세페이지로 이동합니다. (CHEMBL, ZINC 등)