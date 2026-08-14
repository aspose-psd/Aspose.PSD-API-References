---
title: "Classe LayerHashCalculator"
type: docs
weight: 960
url: /it/python-net/aspose.psd.fileformats.psd.layers/layerhashcalculator/
---

**Summary:** Hash Calculator for PSD Layers. It can be used to found equals or different layers in different PSD files

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.LayerHashCalculator

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [LayerHashCalculator(layer)](#LayerHashCalculator_layer_1) | Inizializza una nuova istanza della classe [LayerHashCalculator](/psd/python-net/aspose.psd.fileformats.psd.layers/layerhashcalculator/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_blending_hash()](#get_blending_hash__1) | Ottiene l'hash di fusione. |
| [get_channels_hash()](#get_channels_hash__2) | Ottiene l'hash dei canali. |
| [get_content_hash()](#get_content_hash__3) | Ottiene l'hash del contenuto. |


### Constructor: LayerHashCalculator(layer) {#LayerHashCalculator_layer_1}


```
 LayerHashCalculator(layer) 
```

Inizializza una nuova istanza della classe [LayerHashCalculator](/psd/python-net/aspose.psd.fileformats.psd.layers/layerhashcalculator/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| layer | [Layer](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | Il livello. |

### Method: get_blending_hash() {#get_blending_hash__1}


```
 get_blending_hash() 
```

Ottiene l'hash di fusione.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int | Hash univoco per le opzioni di fusione del livello. |


### Method: get_channels_hash() {#get_channels_hash__2}


```
 get_channels_hash() 
```

Ottiene l'hash dei canali.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int | Hash di tutti i canali del livello. |


### Method: get_content_hash() {#get_content_hash__3}


```
 get_content_hash() 
```

Ottiene l'hash del contenuto.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int | L'hash dei parametri significativi dei livelli. Questo hash è diverso per tutti i tipi di livelli. |


