---
title: "Класс InfxResource"
type: docs
weight: 420
url: /ru/python-net/aspose.psd.fileformats.psd.layers.layerresources/infxresource/
---

**Summary:** Class InfxResource.<br/>            This resource contains information about blending of clipped element.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.InfxResource

**Inheritance:** BooleanResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [InfxResource()](#InfxResource__1) | Инициализирует новый экземпляр класса [InfxResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/infxresource/). |
| [InfxResource(blend_interior_elements)](#InfxResource_blend_interior_elements_2) | Инициализирует новый экземпляр класса [InfxResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/infxresource/). |
| [InfxResource(data)](#InfxResource_data_3) | Инициализирует новый экземпляр класса [InfxResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/infxresource/).<br/>            С пользовательским или неизвестным значением |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Подпись ресурса, специфичная для PSB. |
| RESOURCE_SIGNATURE [static] | int | r | Общая подпись ресурса. |
| TYPE_TOOL_KEY [static] | int | r | Ключ информации о типе инструмента. |
| blend_interior_elements | bool | r/w | Получает или задает значение, указывающее, [blend interior elements]. |
| key | int | r | Получает ключ ресурса слоя. |
| длина | int | r | Получает длину ресурса слоя в байтах. |
| psd_version | int | r | Получает минимальную версию PSD, требуемую для ресурса слоя. 0 означает отсутствие ограничений. |
| signature | int | r | Получает подпись. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Сохраняет указанный контейнер потока. |


### Constructor: InfxResource() {#InfxResource__1}


```
 InfxResource() 
```

Инициализирует новый экземпляр класса [InfxResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/infxresource/).

### Constructor: InfxResource(blend_interior_elements) {#InfxResource_blend_interior_elements_2}


```
 InfxResource(blend_interior_elements) 
```

Инициализирует новый экземпляр класса [InfxResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/infxresource/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| blend_interior_elements | bool | если установлено в <c>true</c> [blend interior elements]. |

### Constructor: InfxResource(data) {#InfxResource_data_3}


```
 InfxResource(data) 
```

Инициализирует новый экземпляр класса [InfxResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/infxresource/).<br/>            С пользовательским или неизвестным значением

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

