---
title: "SmartObjectProvider 클래스"
type: docs
weight: 1940
url: /ko/python-net/aspose.psd.fileformats.psd/smartobjectprovider/
---

**Summary:** Defines the smart object provider that provides getting / setting data sources from global link resources of the PSD file and their contents.

**Module:** [aspose.psd.fileformats.psd](/psd/python-net/aspose.psd.fileformats.psd/)

**Full Name:** aspose.psd.fileformats.psd.SmartObjectProvider

**Aspose.PSD Version:** 24.12.0

## **Methods**
| **Name** | **설명** |
| :- | :- |
| [convert_to_smart_object(layer_numbers)](#convert_to_smart_object_layer_numbers_1) | 레이어를 임베디드 스마트 객체로 변환합니다. |
| [convert_to_smart_object(layers)](#convert_to_smart_object_layers_2) | 레이어를 임베디드 스마트 객체로 변환합니다. |
| embed_all_linked() | 이미지에 연결된 모든 스마트 객체를 임베드합니다. |
| [new_smart_object_via_copy(source_layer)](#new_smart_object_via_copy_source_layer_3) | 소스 레이어를 복사하여 새로운 스마트 객체 레이어를 생성합니다. |
| update_all_modified_content() | 이미지에서 수정된 모든 스마트 객체의 내용을 업데이트합니다. |


### Method: convert_to_smart_object(layer_numbers) {#convert_to_smart_object_layer_numbers_1}


```
 convert_to_smart_object(layer_numbers) 
```

레이어를 임베디드 스마트 객체로 변환합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| layer_numbers | int | 레이어 번호. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) | 생성된 [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) 인스턴스. |


### Method: convert_to_smart_object(layers) {#convert_to_smart_object_layers_2}


```
 convert_to_smart_object(layers) 
```

레이어를 임베디드 스마트 객체로 변환합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| layers | [Layer[]](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | 레이어들입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) | 생성된 [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) 인스턴스. |


### Method: new_smart_object_via_copy(source_layer) {#new_smart_object_via_copy_source_layer_3}


```
 new_smart_object_via_copy(source_layer) 
```

소스 레이어를 복사하여 새로운 스마트 객체 레이어를 생성합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| source_layer | [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) | 소스 레이어. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) | 복제된 [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) 인스턴스. |


