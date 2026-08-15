---
title: "LyidResource Класс"
type: docs
weight: 660
url: /ru/python-net/aspose.psd.fileformats.psd.layers.layerresources/lyidresource/
---

**Summary:** Class LyidResource.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.LyidResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [LyidResource(bytes)](#LyidResource_bytes_1) | Инициализирует новый экземпляр класса [LyidResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lyidresource/).<br/>            С пользовательским или неизвестным значением |
| [LyidResource(id)](#LyidResource_id_2) | Инициализирует новый экземпляр класса [LyidResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lyidresource/). |
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
| значение | int | r | Получает значение. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Сохраняет в указанный контейнер потока. |


### Constructor: LyidResource(bytes) {#LyidResource_bytes_1}


```
 LyidResource(bytes) 
```

Инициализирует новый экземпляр класса [LyidResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lyidresource/).<br/>            С пользовательским или неизвестным значением

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| байты | байт | Байты. |

### Constructor: LyidResource(id) {#LyidResource_id_2}


```
 LyidResource(id) 
```

Инициализирует новый экземпляр класса [LyidResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lyidresource/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| id | int | Идентификатор слоя. |

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

