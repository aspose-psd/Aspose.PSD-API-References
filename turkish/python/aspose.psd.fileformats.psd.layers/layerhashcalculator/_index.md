---
title: "LayerHashCalculator Sınıfı"
type: docs
weight: 960
url: /tr/python-net/aspose.psd.fileformats.psd.layers/layerhashcalculator/
---

**Summary:** Hash Calculator for PSD Layers. It can be used to found equals or different layers in different PSD files

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.LayerHashCalculator

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [LayerHashCalculator(layer)](#LayerHashCalculator_layer_1) | Yeni bir [LayerHashCalculator](/psd/python-net/aspose.psd.fileformats.psd.layers/layerhashcalculator/) sınıfı örneği başlatır. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [get_blending_hash()](#get_blending_hash__1) | Karıştırma karmasını alır. |
| [get_channels_hash()](#get_channels_hash__2) | Kanal karmasını alır. |
| [get_content_hash()](#get_content_hash__3) | İçerik karmasını alır. |


### Constructor: LayerHashCalculator(layer) {#LayerHashCalculator_layer_1}


```
 LayerHashCalculator(layer) 
```

Yeni bir [LayerHashCalculator](/psd/python-net/aspose.psd.fileformats.psd.layers/layerhashcalculator/) sınıfı örneği başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| layer | [Layer](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | Katman. |

### Method: get_blending_hash() {#get_blending_hash__1}


```
 get_blending_hash() 
```

Karıştırma karmasını alır.

**Returns**

| Tür | Açıklama |
| :- | :- |
| int | Katman Karıştırma Seçenekleri için benzersiz karma |


### Method: get_channels_hash() {#get_channels_hash__2}


```
 get_channels_hash() 
```

Kanal karmasını alır.

**Returns**

| Tür | Açıklama |
| :- | :- |
| int | Tüm katman kanallarının karması |


### Method: get_content_hash() {#get_content_hash__3}


```
 get_content_hash() 
```

İçerik karmasını alır.

**Returns**

| Tür | Açıklama |
| :- | :- |
| int | Katmanların önemli parametrelerinin karması. Bu karma, tüm katman türleri için farklıdır. |


