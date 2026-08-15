---
title: "Класс PtFlResource"
type: docs
weight: 860
url: /ru/python-net/aspose.psd.fileformats.psd.layers.layerresources/ptflresource/
---

**Summary:** Class PtFlResource. Contains Pattern Fill Layer Data.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.PtFlResource

**Inheritance:** FillLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [PtFlResource()](#PtFlResource__1) | Инициализирует новый экземпляр класса [PtFlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ptflresource/). |
| [PtFlResource(pattern_name, pattern_id)](#PtFlResource_pattern_name_pattern_id_2) | Инициализирует новый экземпляр класса [PtFlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ptflresource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Подпись ресурса, специфичная для PSB. |
| RESOURCE_SIGNATURE [static] | int | r | Общая подпись ресурса. |
| TYPE_TOOL_KEY [static] | int | r | Ключ информации о типе инструмента. |
| align_with_layer | bool | r/w | Получает или задает значение, указывающее, следует ли [align with layer]. |
| угол | double | r/w | Получает или задает угол. |
| is_linked_with_layer | bool | r/w | Получает или задает значение, указывающее, связан ли этот экземпляр с слоем. |
| key | int | r | Получает ключ ресурса слоя. |
| длина | int | r | Получает длину ресурса слоя в байтах. |
| offset | [Point](/psd/python-net/aspose.psd/point) | r/w | Получает или задает смещение. |
| pattern_id | string | r/w | Получает или задает идентификатор шаблона. |
| pattern_name | string | r/w | Получает или задает имя шаблона. |
| psd_version | int | r | Получает минимальную версию PSD, требуемую для ресурса слоя. 0 означает отсутствие ограничений. |
| scale | double | r/w | Получает или задает масштаб. |
| signature | int | r | Получает подпись. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Сохраняет ресурс в указанный контейнер потока. |


### Constructor: PtFlResource() {#PtFlResource__1}


```
 PtFlResource() 
```

Инициализирует новый экземпляр класса [PtFlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ptflresource/).

### Constructor: PtFlResource(pattern_name, pattern_id) {#PtFlResource_pattern_name_pattern_id_2}


```
 PtFlResource(pattern_name, pattern_id) 
```

Инициализирует новый экземпляр класса [PtFlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ptflresource/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pattern_name | string | Имя шаблона. |
| pattern_id | string | Идентификатор шаблона. |

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

