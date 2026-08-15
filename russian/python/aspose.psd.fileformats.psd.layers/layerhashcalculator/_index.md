---
title: "Класс LayerHashCalculator"
type: docs
weight: 960
url: /ru/python-net/aspose.psd.fileformats.psd.layers/layerhashcalculator/
---

**Summary:** Hash Calculator for PSD Layers. It can be used to found equals or different layers in different PSD files

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.LayerHashCalculator

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [LayerHashCalculator(layer)](#LayerHashCalculator_layer_1) | Инициализирует новый экземпляр класса [LayerHashCalculator](/psd/python-net/aspose.psd.fileformats.psd.layers/layerhashcalculator/). |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [get_blending_hash()](#get_blending_hash__1) | Получает хеш смешивания. |
| [get_channels_hash()](#get_channels_hash__2) | Получает хеш каналов. |
| [get_content_hash()](#get_content_hash__3) | Получает хеш содержимого. |


### Constructor: LayerHashCalculator(layer) {#LayerHashCalculator_layer_1}


```
 LayerHashCalculator(layer) 
```

Инициализирует новый экземпляр класса [LayerHashCalculator](/psd/python-net/aspose.psd.fileformats.psd.layers/layerhashcalculator/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| layer | [Layer](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | Слой. |

### Method: get_blending_hash() {#get_blending_hash__1}


```
 get_blending_hash() 
```

Получает хеш смешивания.

**Returns**

| Тип | Описание |
| :- | :- |
| int | Уникальный хеш для параметров смешивания слоёв |


### Method: get_channels_hash() {#get_channels_hash__2}


```
 get_channels_hash() 
```

Получает хеш каналов.

**Returns**

| Тип | Описание |
| :- | :- |
| int | Хеш всех каналов слоя |


### Method: get_content_hash() {#get_content_hash__3}


```
 get_content_hash() 
```

Получает хеш содержимого.

**Returns**

| Тип | Описание |
| :- | :- |
| int | Хеш значимых параметров слоёв. Этот хеш отличается для всех типов слоёв. |


