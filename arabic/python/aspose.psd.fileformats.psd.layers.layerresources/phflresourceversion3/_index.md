---
title: "فئة PhflResourceVersion3"
type: docs
weight: 810
url: /ar/python-net/aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/
---

**Summary:** Class PhflResource. Resource of Exposure Adjustment Layer<br/>            2 Version ( = 3 ) or ( = 2 )<br/>            12 4 bytes each for XYZ color(Only in Version 3)<br/>            10 2 bytes color space followed by 4 * 2 bytes color component(Only in Version 2)<br/>            4 Density<br/>            1 Preserve Luminosity

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.PhflResourceVersion3

**Inheritance:** PhflResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [PhflResourceVersion3()](#PhflResourceVersion3__1) | ينشئ مثيلاً جديدًا من الفئة [PhflResourceVersion3](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/) |
| [PhflResourceVersion3(data)](#PhflResourceVersion3_data_2) | ينشئ مثيلاً جديدًا من الفئة [PhflResourceVersion3](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/) |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | توقيع المورد الخاص بـ PSB. |
| RESOURCE_SIGNATURE [static] | int | r | توقيع المورد المشترك. |
| TYPE_TOOL_KEY [static] | int | r | مفتاح معلومات أداة النوع. |
| color_space | short | r | يحصل على مساحة اللون. |
| color_x | float | r/w | يحصل أو يضبط اللون X. |
| color_y | float | r/w | يحصل أو يضبط اللون Y. |
| color_z | float | r/w | يحصل أو يضبط اللون Z. |
| density | int | r/w | يحصل أو يضبط الكثافة. |
| key | int | r | يحصل على مفتاح مورد الطبقة. |
| الطول | int | r | يحصل على طول مورد الطبقة بالبايتات. |
| preserve_luminosity | bool | r/w | يحصل أو يضبط قيمة تشير إلى ما إذا كان [preserve luminosity]. |
| psd_version | int | r | يحصل على الحد الأدنى لإصدار psd المطلوب لمورد الطبقة. 0 يعني عدم وجود قيود. |
| signature | int | r | يحصل على التوقيع. |
| version | short | r | يحصل على الإصدار. الافتراضي هو 2 أو 3 |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [get_rgb_color()](#get_rgb_color__1) | يحصل على اللون. |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_2) | يحفظ المورد في حاوية الدفق المحددة. |
| [set_rgb_color(color)](#set_rgb_color_color_3) | يضبط لون RGB. |


### Constructor: PhflResourceVersion3() {#PhflResourceVersion3__1}


```
 PhflResourceVersion3() 
```

ينشئ مثيلاً جديدًا من الفئة [PhflResourceVersion3](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/)

### Constructor: PhflResourceVersion3(data) {#PhflResourceVersion3_data_2}


```
 PhflResourceVersion3(data) 
```

ينشئ مثيلاً جديدًا من الفئة [PhflResourceVersion3](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/)

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| البيانات | byte | بيانات المورد. |

### Method: get_rgb_color() {#get_rgb_color__1}


```
 get_rgb_color() 
```

يحصل على اللون.

**Returns**

| النوع | الوصف |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | لون RGB |


### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_2}


```
 save(stream_container, psd_version) 
```

يحفظ المورد في حاوية الدفق المحددة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | حاوية الدفق التي سيتم الحفظ فيها. |
| psd_version | int | إصدار PSD. |

### Method: set_rgb_color(color) {#set_rgb_color_color_3}


```
 set_rgb_color(color) 
```

يضبط لون RGB.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| color | [Color](/psd/python-net/aspose.psd/color) | اللون. |

