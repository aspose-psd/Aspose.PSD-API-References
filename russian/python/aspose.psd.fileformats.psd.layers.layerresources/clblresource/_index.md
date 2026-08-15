---
title: "Класс ClblResource"
type: docs
weight: 160
url: /ru/python-net/aspose.psd.fileformats.psd.layers.layerresources/clblresource/
---

**Summary:** Class ClblResource.<br/>            This resource contains information about blending of clipped element.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.ClblResource

**Inheritance:** BooleanResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [ClblResource()](#ClblResource__1) | Создаёт новый экземпляр класса [ClblResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/clblresource/). |
| [ClblResource(blend_clipped_elements)](#ClblResource_blend_clipped_elements_2) | Создаёт новый экземпляр класса [ClblResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/clblresource/). |
| [ClblResource(data)](#ClblResource_data_3) | Создаёт новый экземпляр класса [ClblResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/clblresource/).<br/>            С пользовательским или неизвестным значением |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Подпись ресурса, специфичная для PSB. |
| RESOURCE_SIGNATURE [static] | int | r | Общая подпись ресурса. |
| TYPE_TOOL_KEY [static] | int | r | Ключ информации о типе инструмента. |
| blend_clipped_elements | bool | r/w | Получает или задаёт значение, указывающее, включено ли [blend clipped elements]. |
| key | int | r | Получает ключ ресурса слоя. |
| длина | int | r | Получает длину ресурса слоя в байтах. |
| psd_version | int | r | Получает минимальную версию PSD, требуемую для ресурса слоя. 0 означает отсутствие ограничений. |
| signature | int | r | Получает подпись. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Сохраняет указанный контейнер потока. |


### Constructor: ClblResource() {#ClblResource__1}


```
 ClblResource() 
```

Создаёт новый экземпляр класса [ClblResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/clblresource/).

### Constructor: ClblResource(blend_clipped_elements) {#ClblResource_blend_clipped_elements_2}


```
 ClblResource(blend_clipped_elements) 
```

Создаёт новый экземпляр класса [ClblResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/clblresource/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| blend_clipped_elements | bool | если установлено в <c>true</c> [blend clipped elements]. |

### Constructor: ClblResource(data) {#ClblResource_data_3}


```
 ClblResource(data) 
```

Создаёт новый экземпляр класса [ClblResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/clblresource/).<br/>            С пользовательским или неизвестным значением

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| данные | байт | Данные ресурса. |

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Сохраняет указанный контейнер потока.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Контейнер потока. |
| psd_version | int | Версия PSD. |

