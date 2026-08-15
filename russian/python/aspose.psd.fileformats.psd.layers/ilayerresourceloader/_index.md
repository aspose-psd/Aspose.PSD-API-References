---
title: "ILayerResourceLoader Класс"
type: docs
weight: 720
url: /ru/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader/
---

**Summary:** The layer resource loader.

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.ILayerResourceLoader

**Aspose.PSD Version:** 24.12.0

## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [can_load(stream_container, psd_version)](#can_load_stream_container_psd_version_1) | Определяет, может ли ресурс слоя быть загружен из указанного [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/). |
| [load(stream_container, psd_version)](#load_stream_container_psd_version_2) | Загружает [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/). |


### Method: can_load(stream_container, psd_version) {#can_load_stream_container_psd_version_1}


```
 can_load(stream_container, psd_version) 
```

Определяет, может ли ресурс слоя быть загружен из указанного [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Контейнер потока. |
| psd_version | int | Версия PSD. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | <c>true</c> если ресурс слоя может быть загружен из указанного [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/); в противном случае <c>false</c>. |


### Method: load(stream_container, psd_version) {#load_stream_container_psd_version_2}


```
 load(stream_container, psd_version) 
```

Загружает [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Контейнер потока, из которого загружать. |
| psd_version | int | Версия PSD. |

**Returns**

| Тип | Описание |
| :- | :- |
| [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource) | Загруженный ресурс. |


