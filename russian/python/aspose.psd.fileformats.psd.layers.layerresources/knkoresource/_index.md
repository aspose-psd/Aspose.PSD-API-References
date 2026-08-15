---
title: "Класс KnkoResource"
type: docs
weight: 450
url: /ru/python-net/aspose.psd.fileformats.psd.layers.layerresources/knkoresource/
---

**Summary:** Class KnkoResource.<br/>            This resource contains information about blending of clipped element.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.KnkoResource

**Inheritance:** BooleanResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [KnkoResource()](#KnkoResource__1) | Инициализирует новый экземпляр класса [KnkoResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/knkoresource/). |
| [KnkoResource(data)](#KnkoResource_data_2) | Инициализирует новый экземпляр класса [KnkoResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/knkoresource/) класс.<br/>            С пользовательским или неизвестным значением |
| [KnkoResource(knockout)](#KnkoResource_knockout_3) | Инициализирует новый экземпляр класса [KnkoResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/knkoresource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Подпись ресурса, специфичная для PSB. |
| RESOURCE_SIGNATURE [static] | int | r | Общая подпись ресурса. |
| TYPE_TOOL_KEY [static] | int | r | Ключ информации о типе инструмента. |
| key | int | r | Получает ключ ресурса слоя. |
| выключение | bool | r/w | Получает или задает значение, указывающее, [blend interior elements]. |
| длина | int | r | Получает длину ресурса слоя в байтах. |
| psd_version | int | r | Получает минимальную версию PSD, требуемую для ресурса слоя. 0 означает отсутствие ограничений. |
| signature | int | r | Получает подпись. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Сохраняет указанный контейнер потока. |


### Constructor: KnkoResource() {#KnkoResource__1}


```
 KnkoResource() 
```

Инициализирует новый экземпляр класса [KnkoResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/knkoresource/).

### Constructor: KnkoResource(data) {#KnkoResource_data_2}


```
 KnkoResource(data) 
```

Инициализирует новый экземпляр класса [KnkoResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/knkoresource/) класс.<br/>            С пользовательским или неизвестным значением

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| данные | байт | Данные ресурса. |

### Constructor: KnkoResource(knockout) {#KnkoResource_knockout_3}


```
 KnkoResource(knockout) 
```

Инициализирует новый экземпляр класса [KnkoResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/knkoresource/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| выключение | bool | если установлено в <c>true</c> [blend interior elements]. |

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

