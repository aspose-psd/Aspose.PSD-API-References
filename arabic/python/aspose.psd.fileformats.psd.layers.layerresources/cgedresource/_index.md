---
title: "فئة CgEdResource"
type: docs
weight: 130
url: /ar/python-net/aspose.psd.fileformats.psd.layers.layerresources/cgedresource/
---

**Summary:** Class CgEdResource. Content Generator Extra Data (Photoshop CS5)

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.CgEdResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [CgEdResource()](#CgEdResource__1) | يُنشئ مثالا جديدًا من فئة CgEdResource |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | توقيع المورد الخاص بـ PSB. |
| RESOURCE_SIGNATURE [static] | int | r | توقيع المورد المشترك. |
| TYPE_TOOL_KEY [static] | int | r | مفتاح معلومات أداة النوع. |
| auto | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا [CgEdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/cgedresource/) تلقائيًا. |
| السطوع | int | r/w | الحصول على أو تعيين السطوع. |
| التباين | int | r/w | الحصول على أو تعيين التباين. |
| key | int | r | يحصل على مفتاح مورد الطبقة. |
| lab_color | bool | r/w | الحصول على أو تعيين قيمة تشير إلى ما إذا كان [lab color] مستخدمًا. |
| الطول | int | r | يحصل على طول مورد الطبقة بالبايتات. |
| mean_value_for_brightness_and_contrast | int | r/w | الحصول على أو تعيين القيمة المتوسطة للسطوع والتباين. |
| psd_version | int | r | يحصل على الحد الأدنى لإصدار psd المطلوب لمورد الطبقة. 0 يعني عدم وجود قيود. |
| signature | int | r | يحصل على التوقيع. |
| use_legacy | bool | r/w | الحصول على أو تعيين قيمة تشير إلى ما إذا كان [use legacy]. |
| version | int | r/w | يحصل أو يعيّن الإصدار. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | يحفظ المورد في حاوية الدفق المحددة. |


### Constructor: CgEdResource() {#CgEdResource__1}


```
 CgEdResource() 
```

يُنشئ مثالا جديدًا من فئة CgEdResource

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

