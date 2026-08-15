---
title: "Класс AddNoiseSmartFilter"
type: docs
weight: 10
url: /ru/python-net/aspose.psd.fileformats.psd.layers.smartfilters/addnoisesmartfilter/
---

**Summary:** The AddNoise smart filter.

**Module:** [aspose.psd.fileformats.psd.layers.smartfilters](/psd/python-net/aspose.psd.fileformats.psd.layers.smartfilters/)

**Full Name:** aspose.psd.fileformats.psd.layers.smartfilters.AddNoiseSmartFilter

**Inheritance:** SmartFilter

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [AddNoiseSmartFilter()](#AddNoiseSmartFilter__1) | Инициализирует новый экземпляр класса [AddNoiseSmartFilter](/psd/python-net/aspose.psd.fileformats.psd.layers.smartfilters/addnoisesmartfilter/). |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| FILTER_TYPE [static] | int | r | Идентификатор текущего умного фильтра. |
| amount_noise | double | r/w | Получает или задает количество шума. |
| blend_mode | [BlendMode](/psd/python-net/aspose.psd.fileformats.core.blending/blendmode/) | r/w | Получает или задает режим смешивания. |
| distribution | [NoiseDistribution](/psd/python-net/aspose.psd.fileformats.psd.layers.smartfilters/noisedistribution) | r/w | Получает или задает распределение шумового фильтра. |
| filter_id | int | r | Получает идентификатор типа умного фильтра. |
| is_enabled | bool | r/w | Получает или задает статус включения умного фильтра. |
| is_monochromatic | bool | r/w | Получает или задает значение монохроматичности. |
| name | string | r | Получает имя умного фильтра. |
| opacity | double | r/w | Получает или задает значение непрозрачности умного фильтра. |
| source_descriptor | [DescriptorStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure/) | r | Структура дескриптора источника с данными умного фильтра. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [apply(raster_image)](#apply_raster_image_1) | Применяет текущий фильтр к входному изображению [RasterImage](/psd/python-net/aspose.psd/rasterimage/). |
| [apply_to_mask(layer_with_mask)](#apply_to_mask_layer_with_mask_2) | Применяет текущий фильтр к входным данным маски [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/). |
| [clone()](#clone__3) | Создаёт побочный клон текущего экземпляра типа. |


### Constructor: AddNoiseSmartFilter() {#AddNoiseSmartFilter__1}


```
 AddNoiseSmartFilter() 
```

Инициализирует новый экземпляр класса [AddNoiseSmartFilter](/psd/python-net/aspose.psd.fileformats.psd.layers.smartfilters/addnoisesmartfilter/).

### Method: apply(raster_image) {#apply_raster_image_1}


```
 apply(raster_image) 
```

Применяет текущий фильтр к входному изображению [RasterImage](/psd/python-net/aspose.psd/rasterimage/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| raster_image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | Растровое изображение. |

### Method: apply_to_mask(layer_with_mask) {#apply_to_mask_layer_with_mask_2}


```
 apply_to_mask(layer_with_mask) 
```

Применяет текущий фильтр к входным данным маски [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| layer_with_mask | [Layer](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | Слой с данными маски. |

### Method: clone() {#clone__3}


```
 clone() 
```

Создаёт побочный клон текущего экземпляра типа.

**Returns**

| Тип | Описание |
| :- | :- |
| [SmartFilter](/psd/python-net/aspose.psd.fileformats.psd.layers.smartfilters/smartfilter) | Возвращает побочный клон текущего экземпляра типа. |


