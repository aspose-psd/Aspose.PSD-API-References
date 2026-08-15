---
title: "Класс LclrResource"
type: docs
weight: 470
url: /ru/python-net/aspose.psd.fileformats.psd.layers.layerresources/lclrresource/
---

**Summary:** Class LclrResource.<br/>            This resource contains information about color of layer in layers' list is PS. It's only

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.LclrResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [LclrResource()](#LclrResource__1) | Инициализирует новый экземпляр класса [LclrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lclrresource/). |
| [LclrResource(color)](#LclrResource_color_2) | Инициализирует новый экземпляр класса [LclrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lclrresource/). |
| [LclrResource(data)](#LclrResource_data_3) | Инициализирует новый экземпляр класса [LclrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lclrresource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Подпись ресурса, специфичная для PSB. |
| RESOURCE_SIGNATURE [static] | int | r | Общая подпись ресурса. |
| TYPE_TOOL_KEY [static] | int | r | Ключ информации о типе инструмента. |
| color | [SheetColorHighlightEnum](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/sheetcolorhighlightenum) | r/w | Получает или задает цвет слоя. |
| key | int | r | Получает ключ ресурса слоя. |
| длина | int | r | Получает длину ресурса слоя в байтах. |
| psd_version | int | r | Получает минимальную версию PSD, требуемую для ресурса слоя. 0 означает отсутствие ограничений. |
| signature | int | r | Получает подпись. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Сохраняет ресурс в указанный контейнер потока. |


### Constructor: LclrResource() {#LclrResource__1}


```
 LclrResource() 
```

Инициализирует новый экземпляр класса [LclrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lclrresource/).

### Constructor: LclrResource(color) {#LclrResource_color_2}


```
 LclrResource(color) 
```

Инициализирует новый экземпляр класса [LclrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lclrresource/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| color | [SheetColorHighlightEnum](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/sheetcolorhighlightenum) | Цвет. |

### Constructor: LclrResource(data) {#LclrResource_data_3}


```
 LclrResource(data) 
```

Инициализирует новый экземпляр класса [LclrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lclrresource/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| данные | байт | Данные ресурса. |

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Сохраняет ресурс в указанный контейнер потока.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Контейнер потока для сохранения. |
| psd_version | int | Версия PSD. |

