---
title: "فئة BlwhResource"
type: docs
weight: 90
url: /ar/python-net/aspose.psd.fileformats.psd.layers.layerresources/blwhresource/
---

**Summary:** BlwhResource class is a resource of Black and White Adjustment Layer.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.BlwhResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [BlwhResource()](#BlwhResource__1) | ينشئ مثيلًا جديدًا من فئة BlwhResource class |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | توقيع المورد الخاص بـ PSB. |
| RESOURCE_SIGNATURE [static] | int | r | توقيع المورد المشترك. |
| TYPE_TOOL_KEY [static] | int | r | مفتاح معلومات أداة النوع. |
| black_and_white_preset_file_name | string | r/w | يحصل أو يضبط اسم ملف الإعدادات الأسود والأبيض. |
| الأزرق | int | r/w | يحصل أو يضبط قيمة الأزرق. |
| bw_preset_kind | int | r/w | يحصل أو يضبط قيمة نوع الإعداد الأسود والأبيض. |
| السماوي | int | r/w | يحصل أو يضبط قيمة السماوي. |
| الأخضر | int | r/w | يحصل أو يضبط قيمة الأخضر. |
| key | int | r | يحصل على مفتاح مورد الطبقة. |
| الطول | int | r | يحصل على طول مورد الطبقة بالبايتات. |
| الأرجواني | int | r/w | يحصل أو يضبط قيمة الأرجواني. |
| psd_version | int | r | يحصل على الحد الأدنى لإصدار psd المطلوب لمورد الطبقة. 0 يعني عدم وجود قيود. |
| الأحمر | int | r/w | يحصل أو يعيّن قيمة اللون الأحمر. |
| signature | int | r | يحصل على التوقيع. |
| tint_color | int | r/w | يحصل أو يضبط قيمة ARGB للون Tint Color. |
| use_tint | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كان [tint color] مستخدمًا. |
| yellows | int | r/w | يحصل أو يعيّن قيمة الأصفر. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | يحفظ المورد في حاوية الدفق المحددة. |


### Constructor: BlwhResource() {#BlwhResource__1}


```
 BlwhResource() 
```

ينشئ مثيلًا جديدًا من فئة BlwhResource class

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

