---
title: "الفئة Txt2Resource"
type: docs
weight: 970
url: /ar/python-net/aspose.psd.fileformats.psd.layers.layerresources/txt2resource/
---

**Summary:** Txt2 resource class

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.Txt2Resource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [Txt2Resource()](#Txt2Resource__1) | يُنشئ مثيلاً جديدًا من الفئة Txt2Resource |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | توقيع المورد الخاص بـ PSB. |
| RESOURCE_SIGNATURE [static] | int | r | توقيع المورد المشترك. |
| TYPE_TOOL_KEY [static] | int | r | مفتاح معلومات أداة النوع. |
| البيانات | byte | r/w | يحصل أو يعيّن البيانات. |
| key | int | r | يحصل على مفتاح مورد الطبقة. |
| الطول | int | r | يحصل على طول مورد الطبقة بالبايتات. |
| psd_version | int | r | يحصل على الحد الأدنى لإصدار psd المطلوب لمورد الطبقة. 0 يعني عدم وجود قيود. |
| signature | int | r | يحصل على التوقيع. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [add_text_record(text, bounds)](#add_text_record_text_bounds_1) | يضيف سجل النص إلى Resource ويعيد معرف سجل النص. |
| [get_text_data()](#get_text_data__2) | يحصل على سجل النص من بيانات المورد. |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_3) | يحفظ حاوية الدفق المحددة. |


### Constructor: Txt2Resource() {#Txt2Resource__1}


```
 Txt2Resource() 
```

يُنشئ مثيلاً جديدًا من الفئة Txt2Resource

### Method: add_text_record(text, bounds) {#add_text_record_text_bounds_1}


```
 add_text_record(text, bounds) 
```

يضيف سجل النص إلى Resource ويعيد معرف سجل النص.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| text | string | نص السجل. |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | الحدود. |

**Returns**

| النوع | الوصف |
| :- | :- |
| int | يعيد معرف سجل النص للمورد |


### Method: get_text_data() {#get_text_data__2}


```
 get_text_data() 
```

يحصل على سجل النص من بيانات المورد.

**Returns**

| النوع | الوصف |
| :- | :- |
| string | مصفوفة من سجل النص |


### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_3}


```
 save(stream_container, psd_version) 
```

يحفظ حاوية الدفق المحددة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | حاوية الدفق. |
| psd_version | int | إصدار PSD. |

