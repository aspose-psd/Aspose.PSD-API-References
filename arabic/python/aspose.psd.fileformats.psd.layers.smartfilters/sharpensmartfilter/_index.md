---
title: "فئة SharpenSmartFilter"
type: docs
weight: 40
url: /ar/python-net/aspose.psd.fileformats.psd.layers.smartfilters/sharpensmartfilter/
---

**Summary:** The Sharpen smart filter.

**Module:** [aspose.psd.fileformats.psd.layers.smartfilters](/psd/python-net/aspose.psd.fileformats.psd.layers.smartfilters/)

**Full Name:** aspose.psd.fileformats.psd.layers.smartfilters.SharpenSmartFilter

**Inheritance:** SmartFilter

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [SharpenSmartFilter()](#SharpenSmartFilter__1) | يُنشئ مثيلًا جديدًا من الفئة [SharpenSmartFilter](/psd/python-net/aspose.psd.fileformats.psd.layers.smartfilters/sharpensmartfilter/). |
| [SharpenSmartFilter(source_descriptor)](#SharpenSmartFilter_source_descriptor_2) | يُنشئ مثيلًا جديدًا من الفئة [SharpenSmartFilter](/psd/python-net/aspose.psd.fileformats.psd.layers.smartfilters/sharpensmartfilter/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| FILTER_TYPE [ثابت] | int | r | معرف الفلتر الذكي الحالي. |
| blend_mode | [BlendMode](/psd/python-net/aspose.psd.fileformats.core.blending/blendmode/) | r/w | يحصل أو يعيّن وضع الدمج. |
| filter_id | int | r | يحصل على معرف نوع الفلتر الذكي. |
| is_enabled | bool | r/w | يحصل أو يعيّن حالة التمكين للفلتر الذكي. |
| name | string | r | يحصل على اسم الفلتر الذكي. |
| opacity | double | r/w | يحصل أو يعيّن قيمة الشفافية للفلتر الذكي. |
| source_descriptor | [DescriptorStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure/) | r | هيكل الوصف المصدر مع بيانات الفلتر الذكي. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [apply(raster_image)](#apply_raster_image_1) | يطبق الفلتر الحالي على صورة [RasterImage](/psd/python-net/aspose.psd/rasterimage/) المدخلة. |
| [apply_to_mask(layer_with_mask)](#apply_to_mask_layer_with_mask_2) | يطبق الفلتر الحالي على بيانات القناع [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) المدخلة. |
| [clone()](#clone__3) | ينشئ نسخة مستنسخة عضوًا من المثيل الحالي للنوع. |


### Constructor: SharpenSmartFilter() {#SharpenSmartFilter__1}


```
 SharpenSmartFilter() 
```

يُنشئ مثيلًا جديدًا من الفئة [SharpenSmartFilter](/psd/python-net/aspose.psd.fileformats.psd.layers.smartfilters/sharpensmartfilter/).

### Constructor: SharpenSmartFilter(source_descriptor) {#SharpenSmartFilter_source_descriptor_2}


```
 SharpenSmartFilter(source_descriptor) 
```

يُنشئ مثيلًا جديدًا من الفئة [SharpenSmartFilter](/psd/python-net/aspose.psd.fileformats.psd.layers.smartfilters/sharpensmartfilter/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| source_descriptor | [DescriptorStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure/) | هيكل الوصف مع معلومات الفلتر الذكي. |

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


