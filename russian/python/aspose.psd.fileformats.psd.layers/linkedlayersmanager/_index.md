---
title: "Класс LinkedLayersManager"
type: docs
weight: 1140
url: /ru/python-net/aspose.psd.fileformats.psd.layers/linkedlayersmanager/
---

**Summary:** Linked layers manager class.

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.LinkedLayersManager

**Aspose.PSD Version:** 24.12.0

## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [get_layers_by_link_group_id(link_group_id)](#get_layers_by_link_group_id_link_group_id_1) | Получает слои по идентификатору группы ссылок. |
| [get_link_group_id(layer)](#get_link_group_id_layer_2) | Получает идентификатор группы ссылок, связанный со слоем. |
| [link_layers(layers)](#link_layers_layers_3) | Связывает входные слои и возвращает LingGroupId. |
| [unlink_layer(layer)](#unlink_layer_layer_4) | Отсоединяет слой.. |


### Method: get_layers_by_link_group_id(link_group_id) {#get_layers_by_link_group_id_link_group_id_1}


```
 get_layers_by_link_group_id(link_group_id) 
```

Получает слои по идентификатору группы ссылок.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| link_group_id | short | Идентификатор группы ссылок. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Layer[]](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | Массив слоёв. |


### Method: get_link_group_id(layer) {#get_link_group_id_layer_2}


```
 get_link_group_id(layer) 
```

Получает идентификатор группы ссылок, связанный со слоем.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| layer | [Layer](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | Слой. |

**Returns**

| Тип | Описание |
| :- | :- |
| short | Идентификатор группы ссылок. |


### Method: link_layers(layers) {#link_layers_layers_3}


```
 link_layers(layers) 
```

Связывает входные слои и возвращает LingGroupId.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| layers | [Layer[]](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | Слои. |

**Returns**

| Тип | Описание |
| :- | :- |
| short | Идентификатор группы ссылок. |


### Method: unlink_layer(layer) {#unlink_layer_layer_4}


```
 unlink_layer(layer) 
```

Отсоединяет слой..

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| layer | [Layer](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | Слой. |

