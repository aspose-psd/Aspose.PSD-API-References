---
title: "Classe LayerHashCalculator"
type: docs
weight: 960
url: /fr/python-net/aspose.psd.fileformats.psd.layers/layerhashcalculator/
---

**Summary:** Hash Calculator for PSD Layers. It can be used to found equals or different layers in different PSD files

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.LayerHashCalculator

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [LayerHashCalculator(layer)](#LayerHashCalculator_layer_1) | Initialise une nouvelle instance de la classe [LayerHashCalculator](/psd/python-net/aspose.psd.fileformats.psd.layers/layerhashcalculator/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_blending_hash()](#get_blending_hash__1) | Obtient le hachage de fusion. |
| [get_channels_hash()](#get_channels_hash__2) | Obtient le hachage des canaux. |
| [get_content_hash()](#get_content_hash__3) | Obtient le hachage du contenu. |


### Constructor: LayerHashCalculator(layer) {#LayerHashCalculator_layer_1}


```
 LayerHashCalculator(layer) 
```

Initialise une nouvelle instance de la classe [LayerHashCalculator](/psd/python-net/aspose.psd.fileformats.psd.layers/layerhashcalculator/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| layer | [Layer](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | Le calque. |

### Method: get_blending_hash() {#get_blending_hash__1}


```
 get_blending_hash() 
```

Obtient le hachage de fusion.

**Returns**

| Type | Description |
| :- | :- |
| int | Hachage unique pour les options de fusion de calque |


### Method: get_channels_hash() {#get_channels_hash__2}


```
 get_channels_hash() 
```

Obtient le hachage des canaux.

**Returns**

| Type | Description |
| :- | :- |
| int | Hachage de tous les canaux du calque |


### Method: get_content_hash() {#get_content_hash__3}


```
 get_content_hash() 
```

Obtient le hachage du contenu.

**Returns**

| Type | Description |
| :- | :- |
| int | Le hachage des paramètres significatifs des calques. Ce hachage est différent pour tous les types de calques. |


