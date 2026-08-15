---
title: "LayerHashCalculator Klasse"
type: docs
weight: 960
url: /nl/python-net/aspose.psd.fileformats.psd.layers/layerhashcalculator/
---

**Summary:** Hash Calculator for PSD Layers. It can be used to found equals or different layers in different PSD files

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.LayerHashCalculator

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [LayerHashCalculator(layer)](#LayerHashCalculator_layer_1) | Initialiseert een nieuw exemplaar van de [LayerHashCalculator](/psd/python-net/aspose.psd.fileformats.psd.layers/layerhashcalculator/) klasse. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [get_blending_hash()](#get_blending_hash__1) | Haalt de menghash op. |
| [get_channels_hash()](#get_channels_hash__2) | Haalt de kanaalhash op. |
| [get_content_hash()](#get_content_hash__3) | Haalt de inhoudshash op. |


### Constructor: LayerHashCalculator(layer) {#LayerHashCalculator_layer_1}


```
 LayerHashCalculator(layer) 
```

Initialiseert een nieuw exemplaar van de [LayerHashCalculator](/psd/python-net/aspose.psd.fileformats.psd.layers/layerhashcalculator/) klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| layer | [Layer](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | De laag. |

### Method: get_blending_hash() {#get_blending_hash__1}


```
 get_blending_hash() 
```

Haalt de menghash op.

**Returns**

| Type | Beschrijving |
| :- | :- |
| int | Unieke hash voor Layer Blending Options |


### Method: get_channels_hash() {#get_channels_hash__2}


```
 get_channels_hash() 
```

Haalt de kanaalhash op.

**Returns**

| Type | Beschrijving |
| :- | :- |
| int | Hash van alle laagkanalen. |


### Method: get_content_hash() {#get_content_hash__3}


```
 get_content_hash() 
```

Haalt de inhoudshash op.

**Returns**

| Type | Beschrijving |
| :- | :- |
| int | De hash van de significante parameters van lagen. Deze hash is verschillend voor alle soorten lagen. |


