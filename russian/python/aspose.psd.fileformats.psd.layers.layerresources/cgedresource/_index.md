---
title: "Класс CgEdResource"
type: docs
weight: 130
url: /ru/python-net/aspose.psd.fileformats.psd.layers.layerresources/cgedresource/
---

**Summary:** Class CgEdResource. Content Generator Extra Data (Photoshop CS5)

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.CgEdResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [CgEdResource()](#CgEdResource__1) | Инициализирует новый экземпляр класса CgEdResource |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Подпись ресурса, специфичная для PSB. |
| RESOURCE_SIGNATURE [static] | int | r | Общая подпись ресурса. |
| TYPE_TOOL_KEY [static] | int | r | Ключ информации о типе инструмента. |
| auto | bool | r/w | Получает или задает значение, указывающее, является ли этот [CgEdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/cgedresource/) автоматическим. |
| яркость | int | r/w | Получает или задает яркость. |
| контраст | int | r/w | Получает или задает контраст. |
| key | int | r | Получает ключ ресурса слоя. |
| lab_color | bool | r/w | Получает или задает значение, указывающее, используется ли [lab color]. |
| длина | int | r | Получает длину ресурса слоя в байтах. |
| mean_value_for_brightness_and_contrast | int | r/w | Получает или задает среднее значение яркости и контраста. |
| psd_version | int | r | Получает минимальную версию PSD, требуемую для ресурса слоя. 0 означает отсутствие ограничений. |
| signature | int | r | Получает подпись. |
| use_legacy | bool | r/w | Получает или задает значение, указывающее, используется ли [use legacy]. |
| version | int | r/w | Получает или задает версию. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Сохраняет ресурс в указанный контейнер потока. |


### Constructor: CgEdResource() {#CgEdResource__1}


```
 CgEdResource() 
```

Инициализирует новый экземпляр класса CgEdResource

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

