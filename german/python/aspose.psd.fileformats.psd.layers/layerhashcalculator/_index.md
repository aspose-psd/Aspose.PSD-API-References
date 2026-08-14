---
title: "LayerHashCalculator Klasse"
type: docs
weight: 960
url: /de/python-net/aspose.psd.fileformats.psd.layers/layerhashcalculator/
---

**Summary:** Hash Calculator for PSD Layers. It can be used to found equals or different layers in different PSD files

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.LayerHashCalculator

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [LayerHashCalculator(layer)](#LayerHashCalculator_layer_1) | Initialisiert eine neue Instanz der [LayerHashCalculator](/psd/python-net/aspose.psd.fileformats.psd.layers/layerhashcalculator/) Klasse. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [get_blending_hash()](#get_blending_hash__1) | Liest den Misch-Hash. |
| [get_channels_hash()](#get_channels_hash__2) | Liest den Kanal-Hash. |
| [get_content_hash()](#get_content_hash__3) | Liest den Inhalts-Hash. |


### Constructor: LayerHashCalculator(layer) {#LayerHashCalculator_layer_1}


```
 LayerHashCalculator(layer) 
```

Initialisiert eine neue Instanz der [LayerHashCalculator](/psd/python-net/aspose.psd.fileformats.psd.layers/layerhashcalculator/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| layer | [Layer](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | Die Ebene. |

### Method: get_blending_hash() {#get_blending_hash__1}


```
 get_blending_hash() 
```

Liest den Misch-Hash.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int | Eindeutiger Hash für Ebenen-Mischoptionen. |


### Method: get_channels_hash() {#get_channels_hash__2}


```
 get_channels_hash() 
```

Liest den Kanal-Hash.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int | Hash aller Ebenenkanäle. |


### Method: get_content_hash() {#get_content_hash__3}


```
 get_content_hash() 
```

Liest den Inhalts-Hash.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int | Der Hash der signifikanten Parameter von Ebenen. Dieser Hash ist für alle Ebenentypen unterschiedlich. |


