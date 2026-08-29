---
title: "LayerHashCalculator-klass"
type: docs
weight: 960
url: /sv/python-net/aspose.psd.fileformats.psd.layers/layerhashcalculator/
---

**Summary:** Hash Calculator for PSD Layers. It can be used to found equals or different layers in different PSD files

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.LayerHashCalculator

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [LayerHashCalculator(layer)](#LayerHashCalculator_layer_1) | Initierar en ny instans av klassen [LayerHashCalculator](/psd/python-net/aspose.psd.fileformats.psd.layers/layerhashcalculator/). |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [get_blending_hash()](#get_blending_hash__1) | Hämtar blandningshashen. |
| [get_channels_hash()](#get_channels_hash__2) | Hämtar kanalerhashen. |
| [get_content_hash()](#get_content_hash__3) | Hämtar innehållshashen. |


### Constructor: LayerHashCalculator(layer) {#LayerHashCalculator_layer_1}


```
 LayerHashCalculator(layer) 
```

Initierar en ny instans av klassen [LayerHashCalculator](/psd/python-net/aspose.psd.fileformats.psd.layers/layerhashcalculator/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| layer | [Layer](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | Lagret. |

### Method: get_blending_hash() {#get_blending_hash__1}


```
 get_blending_hash() 
```

Hämtar blandningshashen.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int | Unik hash för lagerblandningsalternativ |


### Method: get_channels_hash() {#get_channels_hash__2}


```
 get_channels_hash() 
```

Hämtar kanalerhashen.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int | Hash för alla lagerkanaler |


### Method: get_content_hash() {#get_content_hash__3}


```
 get_content_hash() 
```

Hämtar innehållshashen.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int | Hash för de betydande parametrarna för lager. Denna hash är olika för alla lagertyper. |


