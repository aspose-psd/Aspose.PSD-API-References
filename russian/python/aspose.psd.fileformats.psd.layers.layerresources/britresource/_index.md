---
title: "Класс BritResource"
type: docs
weight: 120
url: /ru/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/
---

**Summary:** Class BritResource. Resource of Brightness/Contrast Adjustment Layer

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.BritResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [BritResource()](#BritResource__1) | Инициализирует новый экземпляр класса [BritResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/). |
| [BritResource(brightness, contrast, mean_value_for_brightness_and_contrast, lab_color)](#BritResource_brightness_contrast_mean_value_for_brightness_and_contrast_lab_color_2) | Инициализирует новый экземпляр класса [BritResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/). |
| [BritResource(bytes)](#BritResource_bytes_3) | Инициализирует новый экземпляр класса [BritResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/).<br/>            Спецификация формата PSD содержит следующее описание:<br/>            2 Яркость<br/>            2 Контраст<br/>            2 Среднее значение яркости и контраста<br/>            1 Только цвет Lab<br/>            Не используется в современных PSD (CS5 и выше), где используется CgEd. CgEd хранит свойства информации |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Подпись ресурса, специфичная для PSB. |
| RESOURCE_SIGNATURE [static] | int | r | Общая подпись ресурса. |
| TYPE_TOOL_KEY [static] | int | r | Ключ информации о типе инструмента. |
| яркость | short | r/w | Получает или задает яркость. |
| контраст | short | r/w | Получает или задает контраст. |
| key | int | r | Получает ключ ресурса слоя. |
| lab_color | bool | r/w | Получает или задает значение, указывающее, используется ли [lab color]. |
| длина | int | r | Получает длину ресурса слоя в байтах. |
| mean_value_for_brightness_and_contrast | short | r/w | Получает или задает среднее значение яркости и контраста. |
| psd_version | int | r | Получает минимальную версию PSD, требуемую для ресурса слоя. 0 означает отсутствие ограничений. |
| signature | int | r | Получает подпись. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Сохраняет ресурс в указанный контейнер потока. |


### Constructor: BritResource() {#BritResource__1}


```
 BritResource() 
```

Инициализирует новый экземпляр класса [BritResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/).

### Constructor: BritResource(brightness, contrast, mean_value_for_brightness_and_contrast, lab_color) {#BritResource_brightness_contrast_mean_value_for_brightness_and_contrast_lab_color_2}


```
 BritResource(brightness, contrast, mean_value_for_brightness_and_contrast, lab_color) 
```

Инициализирует новый экземпляр класса [BritResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| яркость | short | Яркость. |
| контраст | short | Контраст. |
| mean_value_for_brightness_and_contrast | short | Среднее значение яркости и контраста. |
| lab_color | bool | если установлено в <c>true</c> [lab color]. |

### Constructor: BritResource(bytes) {#BritResource_bytes_3}


```
 BritResource(bytes) 
```

Инициализирует новый экземпляр класса [BritResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/).<br/>            Спецификация формата PSD содержит следующее описание:<br/>            2 Яркость<br/>            2 Контраст<br/>            2 Среднее значение яркости и контраста<br/>            1 Только цвет Lab<br/>            Не используется в современных PSD (CS5 и выше), где используется CgEd. CgEd хранит свойства информации

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| байты | байт | Байты. |

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

