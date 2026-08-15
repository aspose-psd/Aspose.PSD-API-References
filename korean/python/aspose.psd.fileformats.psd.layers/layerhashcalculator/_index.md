---
title: "LayerHashCalculator 클래스"
type: docs
weight: 960
url: /ko/python-net/aspose.psd.fileformats.psd.layers/layerhashcalculator/
---

**Summary:** Hash Calculator for PSD Layers. It can be used to found equals or different layers in different PSD files

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.LayerHashCalculator

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **설명** |
| :- | :- |
| [LayerHashCalculator(layer)](#LayerHashCalculator_layer_1) | [LayerHashCalculator](/psd/python-net/aspose.psd.fileformats.psd.layers/layerhashcalculator/) 클래스의 새 인스턴스를 초기화합니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [get_blending_hash()](#get_blending_hash__1) | 블렌딩 해시를 가져옵니다. |
| [get_channels_hash()](#get_channels_hash__2) | 채널 해시를 가져옵니다. |
| [get_content_hash()](#get_content_hash__3) | 콘텐츠 해시를 가져옵니다. |


### Constructor: LayerHashCalculator(layer) {#LayerHashCalculator_layer_1}


```
 LayerHashCalculator(layer) 
```

[LayerHashCalculator](/psd/python-net/aspose.psd.fileformats.psd.layers/layerhashcalculator/) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| layer | [Layer](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | 레이어. |

### Method: get_blending_hash() {#get_blending_hash__1}


```
 get_blending_hash() 
```

블렌딩 해시를 가져옵니다.

**Returns**

| 유형 | 설명 |
| :- | :- |
| int | 레이어 블렌딩 옵션에 대한 고유 해시 |


### Method: get_channels_hash() {#get_channels_hash__2}


```
 get_channels_hash() 
```

채널 해시를 가져옵니다.

**Returns**

| 유형 | 설명 |
| :- | :- |
| int | 모든 레이어 채널의 해시 |


### Method: get_content_hash() {#get_content_hash__3}


```
 get_content_hash() 
```

콘텐츠 해시를 가져옵니다.

**Returns**

| 유형 | 설명 |
| :- | :- |
| int | 레이어의 중요한 매개변수에 대한 해시입니다. 이 해시는 모든 레이어 유형마다 다릅니다. |


