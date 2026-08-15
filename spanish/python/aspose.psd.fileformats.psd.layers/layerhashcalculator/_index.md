---
title: "Clase LayerHashCalculator"
type: docs
weight: 960
url: /es/python-net/aspose.psd.fileformats.psd.layers/layerhashcalculator/
---

**Summary:** Hash Calculator for PSD Layers. It can be used to found equals or different layers in different PSD files

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.LayerHashCalculator

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [LayerHashCalculator(layer)](#LayerHashCalculator_layer_1) | Inicializa una nueva instancia de la clase [LayerHashCalculator](/psd/python-net/aspose.psd.fileformats.psd.layers/layerhashcalculator/). |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [get_blending_hash()](#get_blending_hash__1) | Obtiene el hash de mezcla. |
| [get_channels_hash()](#get_channels_hash__2) | Obtiene el hash de los canales. |
| [get_content_hash()](#get_content_hash__3) | Obtiene el hash del contenido. |


### Constructor: LayerHashCalculator(layer) {#LayerHashCalculator_layer_1}


```
 LayerHashCalculator(layer) 
```

Inicializa una nueva instancia de la clase [LayerHashCalculator](/psd/python-net/aspose.psd.fileformats.psd.layers/layerhashcalculator/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| layer | [Layer](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | La capa. |

### Method: get_blending_hash() {#get_blending_hash__1}


```
 get_blending_hash() 
```

Obtiene el hash de mezcla.

**Returns**

| Tipo | Descripción |
| :- | :- |
| int | Hash único para Opciones de Mezcla de Capas |


### Method: get_channels_hash() {#get_channels_hash__2}


```
 get_channels_hash() 
```

Obtiene el hash de los canales.

**Returns**

| Tipo | Descripción |
| :- | :- |
| int | Hash de todos los canales de capa |


### Method: get_content_hash() {#get_content_hash__3}


```
 get_content_hash() 
```

Obtiene el hash del contenido.

**Returns**

| Tipo | Descripción |
| :- | :- |
| int | El hash de los parámetros significativos de las capas. Este hash es diferente para todos los tipos de capas. |


