---
title: "فئة LayerHashCalculator"
type: docs
weight: 960
url: /ar/python-net/aspose.psd.fileformats.psd.layers/layerhashcalculator/
---

**Summary:** Hash Calculator for PSD Layers. It can be used to found equals or different layers in different PSD files

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.LayerHashCalculator

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [LayerHashCalculator(layer)](#LayerHashCalculator_layer_1) | ينشئ مثلاً جديداً من الفئة [LayerHashCalculator](/psd/python-net/aspose.psd.fileformats.psd.layers/layerhashcalculator/). |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [get_blending_hash()](#get_blending_hash__1) | يحصل على تجزئة الدمج. |
| [get_channels_hash()](#get_channels_hash__2) | يحصل على تجزئة القنوات. |
| [get_content_hash()](#get_content_hash__3) | يحصل على تجزئة المحتوى. |


### Constructor: LayerHashCalculator(layer) {#LayerHashCalculator_layer_1}


```
 LayerHashCalculator(layer) 
```

ينشئ مثلاً جديداً من الفئة [LayerHashCalculator](/psd/python-net/aspose.psd.fileformats.psd.layers/layerhashcalculator/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| layer | [Layer](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | الطبقة. |

### Method: get_blending_hash() {#get_blending_hash__1}


```
 get_blending_hash() 
```

يحصل على تجزئة الدمج.

**Returns**

| النوع | الوصف |
| :- | :- |
| int | تجزئة فريدة لخيارات دمج الطبقة |


### Method: get_channels_hash() {#get_channels_hash__2}


```
 get_channels_hash() 
```

يحصل على تجزئة القنوات.

**Returns**

| النوع | الوصف |
| :- | :- |
| int | تجزئة جميع قنوات الطبقة |


### Method: get_content_hash() {#get_content_hash__3}


```
 get_content_hash() 
```

يحصل على تجزئة المحتوى.

**Returns**

| النوع | الوصف |
| :- | :- |
| int | تجزئة المعلمات الهامة للطبقات. هذه التجزئة مختلفة لجميع أنواع الطبقات. |


