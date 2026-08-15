---
title: "BlwhResource Класс"
type: docs
weight: 90
url: /ru/python-net/aspose.psd.fileformats.psd.layers.layerresources/blwhresource/
---

**Summary:** BlwhResource class is a resource of Black and White Adjustment Layer.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.BlwhResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [BlwhResource()](#BlwhResource__1) | Инициализирует новый экземпляр класса BlwhResource. |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Подпись ресурса, специфичная для PSB. |
| RESOURCE_SIGNATURE [static] | int | r | Общая подпись ресурса. |
| TYPE_TOOL_KEY [static] | int | r | Ключ информации о типе инструмента. |
| black_and_white_preset_file_name | string | r/w | Получает или задает имя файла предустановки черно-белого режима. |
| синие | int | r/w | Получает или задает значение синих. |
| bw_preset_kind | int | r/w | Получает или задает значение типа предустановки черно-белого режима. |
| циановые | int | r/w | Получает или задает значение циановых. |
| зеленые | int | r/w | Получает или задает значение зеленых. |
| key | int | r | Получает ключ ресурса слоя. |
| длина | int | r | Получает длину ресурса слоя в байтах. |
| пурпурные | int | r/w | Получает или задает значение пурпурных. |
| psd_version | int | r | Получает минимальную версию PSD, требуемую для ресурса слоя. 0 означает отсутствие ограничений. |
| красные | int | r/w | Получает или задает значение reds. |
| signature | int | r | Получает подпись. |
| tint_color | int | r/w | Получает или задает значение ARGB цвета оттенка. |
| use_tint | bool | r/w | Получает или задает значение, указывающее, используется ли [tint color]. |
| yellows | int | r/w | Получает или задает значение yellows. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Сохраняет ресурс в указанный контейнер потока. |


### Constructor: BlwhResource() {#BlwhResource__1}


```
 BlwhResource() 
```

Инициализирует новый экземпляр класса BlwhResource.

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

