---
title: "Класс LyvrResource"
type: docs
weight: 670
url: /ru/python-net/aspose.psd.fileformats.psd.layers.layerresources/lyvrresource/
---

**Summary:** The resource to represents photoshop version of Layer.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.LyvrResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [LyvrResource()](#LyvrResource__1) | Инициализирует новый экземпляр класса LyvrResource |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Подпись ресурса, специфичная для PSB. |
| RESOURCE_SIGNATURE [static] | int | r | Общая подпись ресурса. |
| TYPE_TOOL_KEY [static] | int | r | Ключ информации о типе инструмента. |
| key | int | r | Получает ключ ресурса слоя. |
| длина | int | r | <inheritdoc /> |
| psd_version | int | r | Получает минимальную версию PSD, требуемую для ресурса слоя. 0 означает отсутствие ограничений. |
| signature | int | r | Получает подпись. |
| version | int | r/w | Получает или задает версию Photoshop слоя. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Сохраняет ресурс в указанный контейнер потока. |


### Constructor: LyvrResource() {#LyvrResource__1}


```
 LyvrResource() 
```

Инициализирует новый экземпляр класса LyvrResource

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

