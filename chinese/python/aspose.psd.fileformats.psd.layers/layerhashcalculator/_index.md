---
title: "LayerHashCalculator 类"
type: docs
weight: 960
url: /zh/python-net/aspose.psd.fileformats.psd.layers/layerhashcalculator/
---

**Summary:** Hash Calculator for PSD Layers. It can be used to found equals or different layers in different PSD files

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.LayerHashCalculator

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [LayerHashCalculator(layer)](#LayerHashCalculator_layer_1) | 初始化 [LayerHashCalculator](/psd/python-net/aspose.psd.fileformats.psd.layers/layerhashcalculator/) 类的新实例。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_blending_hash()](#get_blending_hash__1) | 获取混合哈希。 |
| [get_channels_hash()](#get_channels_hash__2) | 获取通道哈希。 |
| [get_content_hash()](#get_content_hash__3) | 获取内容哈希。 |


### Constructor: LayerHashCalculator(layer) {#LayerHashCalculator_layer_1}


```
 LayerHashCalculator(layer) 
```

初始化 [LayerHashCalculator](/psd/python-net/aspose.psd.fileformats.psd.layers/layerhashcalculator/) 类的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| layer | [Layer](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | 该图层。 |

### Method: get_blending_hash() {#get_blending_hash__1}


```
 get_blending_hash() 
```

获取混合哈希。

**Returns**

| 类型 | 描述 |
| :- | :- |
| int | 图层混合选项的唯一哈希 |


### Method: get_channels_hash() {#get_channels_hash__2}


```
 get_channels_hash() 
```

获取通道哈希。

**Returns**

| 类型 | 描述 |
| :- | :- |
| int | 所有图层通道的哈希 |


### Method: get_content_hash() {#get_content_hash__3}


```
 get_content_hash() 
```

获取内容哈希。

**Returns**

| 类型 | 描述 |
| :- | :- |
| int | 图层重要参数的哈希。此哈希对所有图层类型均不同。 |


