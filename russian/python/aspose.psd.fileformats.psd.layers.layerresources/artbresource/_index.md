---
title: "Класс ArtBResource"
type: docs
weight: 50
url: /ru/python-net/aspose.psd.fileformats.psd.layers.layerresources/artbresource/
---

**Summary:** The Artboard info data for [Layer.resources](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/).

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.ArtBResource

**Inheritance:** BaseArtboardInfoResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [ArtBResource()](#ArtBResource__1) | Инициализирует новый экземпляр класса ArtBResource |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Подпись ресурса, специфичная для PSB. |
| RESOURCE_SIGNATURE [static] | int | r | Общая подпись ресурса. |
| TYPE_TOOL_KEY [static] | int | r | Ключ информации о типе инструмента. |
| artboard_background_type | int | r/w | Получает или задает [ArtBResource.artboard_background_type](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/artbresource/) |
| color | [Color](/psd/python-net/aspose.psd/color) | r/w | Получает или задает [ArtBResource.color](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/artbresource/) |
| items | [OSTypeStructure[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | r/w | Получает или задает элементы [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/). |
| key | int | r | Получает ключ ресурса слоя. |
| длина | int | r | <inheritdoc /> |
| psd_version | int | r | Получает минимальную версию PSD, требуемую для ресурса слоя. 0 означает отсутствие ограничений. |
| signature | int | r | Получает подпись. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Сохраняет ресурс в указанный контейнер потока. |


### Constructor: ArtBResource() {#ArtBResource__1}


```
 ArtBResource() 
```

Инициализирует новый экземпляр класса ArtBResource

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

