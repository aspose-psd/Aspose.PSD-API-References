---
title: "Κλάση LayerHashCalculator"
type: docs
weight: 960
url: /el/python-net/aspose.psd.fileformats.psd.layers/layerhashcalculator/
---

**Summary:** Hash Calculator for PSD Layers. It can be used to found equals or different layers in different PSD files

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.LayerHashCalculator

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Περιγραφή** |
| :- | :- |
| [LayerHashCalculator(layer)](#LayerHashCalculator_layer_1) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [LayerHashCalculator](/psd/python-net/aspose.psd.fileformats.psd.layers/layerhashcalculator/). |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [get_blending_hash()](#get_blending_hash__1) | Λαμβάνει το hash ανάμειξης. |
| [get_channels_hash()](#get_channels_hash__2) | Λαμβάνει το hash των καναλιών. |
| [get_content_hash()](#get_content_hash__3) | Λαμβάνει το hash του περιεχομένου. |


### Constructor: LayerHashCalculator(layer) {#LayerHashCalculator_layer_1}


```
 LayerHashCalculator(layer) 
```

Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [LayerHashCalculator](/psd/python-net/aspose.psd.fileformats.psd.layers/layerhashcalculator/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| layer | [Layer](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | Το στρώμα. |

### Method: get_blending_hash() {#get_blending_hash__1}


```
 get_blending_hash() 
```

Λαμβάνει το hash ανάμειξης.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| int | Μοναδικό hash για τις επιλογές ανάμειξης στρώματος |


### Method: get_channels_hash() {#get_channels_hash__2}


```
 get_channels_hash() 
```

Λαμβάνει το hash των καναλιών.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| int | Hash όλων των καναλιών στρώματος |


### Method: get_content_hash() {#get_content_hash__3}


```
 get_content_hash() 
```

Λαμβάνει το hash του περιεχομένου.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| int | Το hash των σημαντικών παραμέτρων των στρωμάτων. Αυτό το hash διαφέρει για όλους τους τύπους στρωμάτων. |


