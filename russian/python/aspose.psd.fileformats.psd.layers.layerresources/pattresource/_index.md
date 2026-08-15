---
title: "Класс PattResource"
type: docs
weight: 770
url: /ru/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresource/
---

**Summary:** Class PattResource. Resource with pattern data

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.PattResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [PattResource()](#PattResource__1) | Инициализирует новый экземпляр класса [PattResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresource/) |
| [PattResource(key, patterns)](#PattResource_key_patterns_2) | Инициализирует новый экземпляр класса [PattResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresource/) |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Подпись ресурса, специфичная для PSB. |
| RESOURCE_SIGNATURE [static] | int | r | Общая подпись ресурса. |
| TYPE_TOOL_KEY [static] | int | r | Ключ информации инструмента типа 'Patt' для 8‑бит. |
| TYPE_TOOL_KEY2 [static] | int | r | Ключ информации инструмента типа 'Pat2' для 16‑бит. |
| TYPE_TOOL_KEY3 [static] | int | r | Ключ информации инструмента типа 'Pat3' для 32‑бит. |
| key | int | r | Получает ключ ресурса слоя. |
| длина | int | r | Получает длину ресурса слоя в байтах. |
| patterns | [PattResourceData[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata) | r/w | Получает или задает данные шаблонов; |
| psd_version | int | r | Получает минимальную версию PSD, требуемую для ресурса слоя. 0 означает отсутствие ограничений. |
| signature | int | r | Получает подпись. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Сохраняет данные блока ресурсов. |


### Constructor: PattResource() {#PattResource__1}


```
 PattResource() 
```

Инициализирует новый экземпляр класса [PattResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresource/)

### Constructor: PattResource(key, patterns) {#PattResource_key_patterns_2}


```
 PattResource(key, patterns) 
```

Инициализирует новый экземпляр класса [PattResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresource/)

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| key | int | Ключ типа ресурса. |
| patterns | [PattResourceData[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata) | Данные шаблонов. |

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Сохраняет данные блока ресурсов.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Контейнер потока для сохранения. |
| psd_version | int | Версия PSD. |

