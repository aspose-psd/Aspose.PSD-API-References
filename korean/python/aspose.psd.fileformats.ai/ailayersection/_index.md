---
title: "AiLayerSection 클래스"
type: docs
weight: 50
url: /ko/python-net/aspose.psd.fileformats.ai/ailayersection/
---

**Summary:** The Ai format Layer Section

**Module:** [aspose.psd.fileformats.ai](/psd/python-net/aspose.psd.fileformats.ai/)

**Full Name:** aspose.psd.fileformats.ai.AiLayerSection

**Inheritance:** AiDataSection

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| 파랑 | int | r/w | 파란색 구성 요소를 가져오거나 설정합니다. |
| color_index | int | r/w | 색상의 인덱스를 가져오거나 설정합니다.<br/>            이 인자는 –1에서 26 사이의 값을 가질 수 있습니다. 각 정수는<br/>            사용자 식별을 위해 레이어에 할당될 수 있는 색상을 나타냅니다. |
| color_number | int | r/w | 색상 번호를 가져오거나 설정합니다. -1은 Red, Green, Blue 속성에서 가져온 사용자 정의 색상 값입니다.<br/>            레이어의 색상 설정을 지정합니다. |
| dim_value | int | r/w | 디밍 값을 백분율로 가져오거나 설정합니다.<br/>            레이어에 포함된 연결된 이미지와 비트맵 이미지의 강도를 지정된 백분율로 감소시킵니다. |
| disposed | bool | r | 이 인스턴스가 해제되었는지 여부를 나타내는 값을 가져옵니다. |
| 초록 | int | r/w | 녹색 색상 구성 요소를 가져오거나 설정합니다. |
| has_multi_layer_masks | bool | r/w | 이 인스턴스에 다중 레이어 마스크가 있는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| is_images_dimmed | bool | r/w | 이 레이어가 어두워졌는지 여부를 나타내는 값을 가져오거나 설정합니다.<br/>            레이어에 포함된 연결된 이미지와 비트맵 이미지의 강도를 감소시킵니다. |
| is_locked | bool | r/w | 이 레이어가 잠겨 있는지 여부를 나타내는 값을 가져오거나 설정합니다.<br/>            항목에 대한 변경을 방지합니다. |
| is_preview | bool | r/w | 이 레이어가 미리 보기인지 여부를 나타내는 값을 가져오거나 설정합니다.<br/>            레이어에 포함된 아트워크를 윤곽선 대신 색상으로 표시합니다. |
| is_printed | bool | r/w | 이 레이어가 인쇄되는지 여부를 나타내는 값을 가져오거나 설정합니다.<br/>            true인 경우 레이어에 포함된 아트워크를 인쇄 가능하게 합니다. |
| is_shown | bool | r/w | 이 레이어가 표시되는지 여부를 나타내는 값을 가져오거나 설정합니다.<br/>            true인 경우 레이어에 포함된 모든 아트워크를 아트보드에 표시합니다. |
| is_template | bool | r/w | 이 레이어가 템플릿 레이어인지 여부를 나타내는 값을 가져오거나 설정합니다. |
| name | 문자열 | r/w | 레이어 이름을 가져오거나 설정합니다.<br/>            레이어 패널에 표시되는 항목의 이름을 지정합니다. |
| raster_images | [AiRasterImageSection[]](/psd/python-net/aspose.psd.fileformats.ai/airasterimagesection) | r | 래스터 이미지를 가져옵니다. |
| 빨강 | int | r/w | 빨간색 색상 구성 요소를 가져오거나 설정합니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [add_raster_image(raster_image)](#add_raster_image_raster_image_1) | 래스터 이미지를 추가합니다. |
| [get_data()](#get_data__2) | 문자열 데이터를 가져옵니다. |


### Method: add_raster_image(raster_image) {#add_raster_image_raster_image_1}


```
 add_raster_image(raster_image) 
```

래스터 이미지를 추가합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| raster_image | [AiRasterImageSection](/psd/python-net/aspose.psd.fileformats.ai/airasterimagesection) | 래스터 이미지. |

### Method: get_data() {#get_data__2}


```
 get_data() 
```

문자열 데이터를 가져옵니다.

**Returns**

| 유형 | 설명 |
| :- | :- |
| 문자열 | 섹션의 문자열 데이터 |


