---
title: LayerHashCalculator Class
type: docs
weight: 950
url: /python-net/aspose.psd.fileformats.psd.layers/layerhashcalculator/
---

**Summary:** Hash Calculator for PSD Layers. It can be used to found equals or different layers in different PSD files

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.LayerHashCalculator

**Aspose.PSD Version:** 24.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [LayerHashCalculator(layer)](#LayerHashCalculator_layer_1) | Initializes a new instance of the [LayerHashCalculator](/psd/python-net/aspose.psd.fileformats.psd.layers/layerhashcalculator/) class. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_blending_hash()](#get_blending_hash__1) | Gets the blending hash. |
| [get_channels_hash()](#get_channels_hash__2) | Gets the channels hash. |
| [get_content_hash()](#get_content_hash__3) | Gets the content hash. |


### Constructor: LayerHashCalculator(layer) {#LayerHashCalculator_layer_1}


```
 LayerHashCalculator(layer) 
```

Initializes a new instance of the [LayerHashCalculator](/psd/python-net/aspose.psd.fileformats.psd.layers/layerhashcalculator/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| layer | [Layer](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | The layer. |

### Method: get_blending_hash() {#get_blending_hash__1}


```
 get_blending_hash() 
```

Gets the blending hash.

**Returns**

| Type | Description |
| :- | :- |
| int | Unique hash for Layer Blending Options |


### Method: get_channels_hash() {#get_channels_hash__2}


```
 get_channels_hash() 
```

Gets the channels hash.

**Returns**

| Type | Description |
| :- | :- |
| int | Hash of all layer channels |


### Method: get_content_hash() {#get_content_hash__3}


```
 get_content_hash() 
```

Gets the content hash.

**Returns**

| Type | Description |
| :- | :- |
| int | The hash of the significant parameters of layers. This hash is different for all types of layers |


