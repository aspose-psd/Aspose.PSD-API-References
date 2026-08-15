---
title: "FxrpResource Класс"
type: docs
weight: 320
url: /ru/python-net/aspose.psd.fileformats.psd.layers.layerresources/fxrpresource/
---

**Summary:** Class FxrpResource. The reference point of layer

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.FxrpResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [FxrpResource()](#FxrpResource__1) | Инициализирует новый экземпляр класса [FxrpResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/fxrpresource/). |
| [FxrpResource(data)](#FxrpResource_data_2) | Инициализирует новый экземпляр класса [FxrpResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/fxrpresource/).<br/>            С пользовательским или неизвестным значением |
| [FxrpResource(x, y)](#FxrpResource_x_y_3) | Инициализирует новый экземпляр класса [FxrpResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/fxrpresource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Подпись ресурса, специфичная для PSB. |
| RESOURCE_SIGNATURE [static] | int | r | Общая подпись ресурса. |
| TYPE_TOOL_KEY [static] | int | r | Ключ информации о типе инструмента. |
| key | int | r | Получает ключ ресурса слоя. |
| длина | int | r | Получает длину ресурса слоя в байтах. |
| psd_version | int | r | Получает минимальную версию PSD, требуемую для ресурса слоя. 0 означает отсутствие ограничений. |
| signature | int | r | Получает подпись. |
| x | double | r/w | Получает или задает x опорной точки |
| y | double | r/w | Получает или задает y опорной точки |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Сохраняет в указанный контейнер потока. |


### Constructor: FxrpResource() {#FxrpResource__1}


```
 FxrpResource() 
```

Инициализирует новый экземпляр класса [FxrpResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/fxrpresource/).

### Constructor: FxrpResource(data) {#FxrpResource_data_2}


```
 FxrpResource(data) 
```

Инициализирует новый экземпляр класса [FxrpResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/fxrpresource/).<br/>            С пользовательским или неизвестным значением

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| данные | байт | Данные ресурса. |

### Constructor: FxrpResource(x, y) {#FxrpResource_x_y_3}


```
 FxrpResource(x, y) 
```

Инициализирует новый экземпляр класса [FxrpResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/fxrpresource/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x | double | Координата x опорной точки |
| y | double | Координата y опорной точки |

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Сохраняет в указанный контейнер потока.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Контейнер потока. |
| psd_version | int | Версия PSD. |

