---
title: "فئة BritResource"
type: docs
weight: 120
url: /ar/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/
---

**Summary:** Class BritResource. Resource of Brightness/Contrast Adjustment Layer

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.BritResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [BritResource()](#BritResource__1) | يقوم بتهيئة نسخة جديدة من الفئة [BritResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/). |
| [BritResource(brightness, contrast, mean_value_for_brightness_and_contrast, lab_color)](#BritResource_brightness_contrast_mean_value_for_brightness_and_contrast_lab_color_2) | يقوم بتهيئة نسخة جديدة من الفئة [BritResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/). |
| [BritResource(bytes)](#BritResource_bytes_3) | يقوم بتهيئة نسخة جديدة من الفئة [BritResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/).<br/>            يحتوي مواصفات تنسيق PSD على الوصف التالي:<br/>            2 السطوع<br/>            2 التباين<br/>            2 القيمة المتوسطة للسطوع والتباين<br/>            1 لون Lab فقط<br/>            لا يُستخدم في إصدارات PSD الحديثة (CS5 وما فوق) حيث يوجد CgEd. CgEd يخزن خصائص المعلومات |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | توقيع المورد الخاص بـ PSB. |
| RESOURCE_SIGNATURE [static] | int | r | توقيع المورد المشترك. |
| TYPE_TOOL_KEY [static] | int | r | مفتاح معلومات أداة النوع. |
| السطوع | short | r/w | الحصول على أو تعيين السطوع. |
| التباين | short | r/w | الحصول على أو تعيين التباين. |
| key | int | r | يحصل على مفتاح مورد الطبقة. |
| lab_color | bool | r/w | يحصل أو يضبط قيمة تشير إلى ما إذا كان [lab color]. |
| الطول | int | r | يحصل على طول مورد الطبقة بالبايتات. |
| mean_value_for_brightness_and_contrast | short | r/w | الحصول على أو تعيين القيمة المتوسطة للسطوع والتباين. |
| psd_version | int | r | يحصل على الحد الأدنى لإصدار psd المطلوب لمورد الطبقة. 0 يعني عدم وجود قيود. |
| signature | int | r | يحصل على التوقيع. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | يحفظ المورد في حاوية الدفق المحددة. |


### Constructor: BritResource() {#BritResource__1}


```
 BritResource() 
```

يقوم بتهيئة نسخة جديدة من الفئة [BritResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/).

### Constructor: BritResource(brightness, contrast, mean_value_for_brightness_and_contrast, lab_color) {#BritResource_brightness_contrast_mean_value_for_brightness_and_contrast_lab_color_2}


```
 BritResource(brightness, contrast, mean_value_for_brightness_and_contrast, lab_color) 
```

يقوم بتهيئة نسخة جديدة من الفئة [BritResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| السطوع | short | السطوع. |
| التباين | short | التباين. |
| mean_value_for_brightness_and_contrast | short | القيمة المتوسطة للسطوع والتباين. |
| lab_color | bool | إذا تم تعيينه إلى <c>true</c> [lab color]. |

### Constructor: BritResource(bytes) {#BritResource_bytes_3}


```
 BritResource(bytes) 
```

يقوم بتهيئة نسخة جديدة من الفئة [BritResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/).<br/>            يحتوي مواصفات تنسيق PSD على الوصف التالي:<br/>            2 السطوع<br/>            2 التباين<br/>            2 القيمة المتوسطة للسطوع والتباين<br/>            1 لون Lab فقط<br/>            لا يُستخدم في إصدارات PSD الحديثة (CS5 وما فوق) حيث يوجد CgEd. CgEd يخزن خصائص المعلومات

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| بايت | byte | الـ بايت. |

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

يحفظ المورد في حاوية الدفق المحددة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | حاوية الدفق التي سيتم الحفظ فيها. |
| psd_version | int | إصدار PSD. |

