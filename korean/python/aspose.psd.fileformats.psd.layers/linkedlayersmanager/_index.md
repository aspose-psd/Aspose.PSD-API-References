---
title: "LinkedLayersManager 클래스"
type: docs
weight: 1140
url: /ko/python-net/aspose.psd.fileformats.psd.layers/linkedlayersmanager/
---

**Summary:** Linked layers manager class.

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.LinkedLayersManager

**Aspose.PSD Version:** 24.12.0

## **Methods**
| **Name** | **설명** |
| :- | :- |
| [get_layers_by_link_group_id(link_group_id)](#get_layers_by_link_group_id_link_group_id_1) | 링크 그룹 ID로 레이어를 가져옵니다. |
| [get_link_group_id(layer)](#get_link_group_id_layer_2) | 레이어와 연결된 링크 그룹 ID를 가져옵니다. |
| [link_layers(layers)](#link_layers_layers_3) | 입력 레이어를 연결하고 LingGroupId를 반환합니다. |
| [unlink_layer(layer)](#unlink_layer_layer_4) | 레이어의 연결을 해제합니다. |


### Method: get_layers_by_link_group_id(link_group_id) {#get_layers_by_link_group_id_link_group_id_1}


```
 get_layers_by_link_group_id(link_group_id) 
```

링크 그룹 ID로 레이어를 가져옵니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| link_group_id | short | 링크 그룹 ID입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [Layer[]](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | 레이어 배열입니다. |


### Method: get_link_group_id(layer) {#get_link_group_id_layer_2}


```
 get_link_group_id(layer) 
```

레이어와 연결된 링크 그룹 ID를 가져옵니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| layer | [Layer](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | 레이어. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| short | 링크 그룹 ID입니다. |


### Method: link_layers(layers) {#link_layers_layers_3}


```
 link_layers(layers) 
```

입력 레이어를 연결하고 LingGroupId를 반환합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| layers | [Layer[]](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | 레이어들입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| short | 링크 그룹 ID입니다. |


### Method: unlink_layer(layer) {#unlink_layer_layer_4}


```
 unlink_layer(layer) 
```

레이어의 연결을 해제합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| layer | [Layer](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | 레이어. |

