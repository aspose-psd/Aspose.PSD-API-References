---
title: "فئة AddNoiseSmartFilter"
type: docs
weight: 10
url: /ar/python-net/aspose.psd.fileformats.psd.layers.smartfilters/addnoisesmartfilter/
---

**Summary:** The AddNoise smart filter.

**Module:** [aspose.psd.fileformats.psd.layers.smartfilters](/psd/python-net/aspose.psd.fileformats.psd.layers.smartfilters/)

**Full Name:** aspose.psd.fileformats.psd.layers.smartfilters.AddNoiseSmartFilter

**Inheritance:** SmartFilter

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [AddNoiseSmartFilter()](#AddNoiseSmartFilter__1) | ينشئ مثيلًا جديدًا من الفئة [AddNoiseSmartFilter](/psd/python-net/aspose.psd.fileformats.psd.layers.smartfilters/addnoisesmartfilter/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| FILTER_TYPE [ثابت] | int | r | معرف الفلتر الذكي الحالي. |
| amount_noise | double | r/w | يحصل أو يعيّن مقدار قيمة الضوضاء. |
| blend_mode | [BlendMode](/psd/python-net/aspose.psd.fileformats.core.blending/blendmode/) | r/w | يحصل أو يعيّن وضع الدمج. |
| distribution | [NoiseDistribution](/psd/python-net/aspose.psd.fileformats.psd.layers.smartfilters/noisedistribution) | r/w | يحصل أو يعيّن توزيع فلتر الضوضاء. |
| filter_id | int | r | يحصل على معرف نوع الفلتر الذكي. |
| is_enabled | bool | r/w | يحصل أو يعيّن حالة التمكين للفلتر الذكي. |
| is_monochromatic | bool | r/w | يحصل أو يعيّن قيمة أحادية اللون. |
| name | string | r | يحصل على اسم الفلتر الذكي. |
| opacity | double | r/w | يحصل أو يعيّن قيمة الشفافية للفلتر الذكي. |
| source_descriptor | [DescriptorStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure/) | r | هيكل الوصف المصدر مع بيانات الفلتر الذكي. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [apply(raster_image)](#apply_raster_image_1) | يطبق الفلتر الحالي على صورة [RasterImage](/psd/python-net/aspose.psd/rasterimage/) المدخلة. |
| [apply_to_mask(layer_with_mask)](#apply_to_mask_layer_with_mask_2) | يطبق الفلتر الحالي على بيانات القناع [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) المدخلة. |
| [clone()](#clone__3) | ينشئ نسخة مستنسخة عضوًا من المثيل الحالي للنوع. |


### Constructor: AddNoiseSmartFilter() {#AddNoiseSmartFilter__1}


```
 AddNoiseSmartFilter() 
```

ينشئ مثيلًا جديدًا من الفئة [AddNoiseSmartFilter](/psd/python-net/aspose.psd.fileformats.psd.layers.smartfilters/addnoisesmartfilter/).

### Method: apply(raster_image) {#apply_raster_image_1}


```
 apply(raster_image) 
```

يطبق الفلتر الحالي على صورة [RasterImage](/psd/python-net/aspose.psd/rasterimage/) المدخلة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| raster_image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | صورة الراستر. |

### Method: apply_to_mask(layer_with_mask) {#apply_to_mask_layer_with_mask_2}


```
 apply_to_mask(layer_with_mask) 
```

يطبق الفلتر الحالي على بيانات القناع [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) المدخلة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| layer_with_mask | [Layer](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | الطبقة مع بيانات القناع. |

### Method: clone() {#clone__3}


```
 clone() 
```

ينشئ نسخة مستنسخة عضوًا من المثيل الحالي للنوع.

**Returns**

| النوع | الوصف |
| :- | :- |
| [SmartFilter](/psd/python-net/aspose.psd.fileformats.psd.layers.smartfilters/smartfilter) | يعيد النسخة المستنسخة عضوًا من المثيل الحالي للنوع. |


