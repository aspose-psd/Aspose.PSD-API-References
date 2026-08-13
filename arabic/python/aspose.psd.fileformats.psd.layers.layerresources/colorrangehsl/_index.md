---
title: "فئة ColorRangeHsl"
type: docs
weight: 180
url: /ar/python-net/aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl/
---

**Summary:** [Hue2Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/hue2resource/) has 6 color ranges where you can change HSV parameters. <br/>            Every range has 4 key points to identify range borders. And it's ColorRangeHsl

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.ColorRangeHsl

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [ColorRangeHsl()](#ColorRangeHsl__1) | يُنشئ مثيلًا جديدًا من الفئة [ColorRangeHsl](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl/) . |
| [ColorRangeHsl(data)](#ColorRangeHsl_data_2) | يُنشئ مثيلًا جديدًا من الفئة [ColorRangeHsl](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl/) . |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| hue | short | r/w | يحصل أو يعيّن hue. |
| left_border | short | r/w | يحصل أو يعيّن الحد الأيسر. |
| lightness | short | r/w | يحصل أو يعيّن lightness. |
| most_left_border | short | r/w | يحصل أو يعيّن الحد الأيسر الأكثر. |
| most_right_border | short | r/w | يحصل أو يعيّن الحد الأيمن الأكثر. |
| right_border | short | r/w | يحصل أو يعيّن الحد الأيمن. |
| التشبع | short | r/w | يحصل أو يضبط التشبع. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [get_range_coefficient(hue)](#get_range_coefficient_hue_1) | يحصل على معامل النطاق. |
| [is_hue_in_big_range(hue)](#is_hue_in_big_range_hue_2) | يحدد ما إذا كان اللون في نطاق كبير. |
| [is_hue_in_small_range(hue)](#is_hue_in_small_range_hue_3) | يحدد ما إذا كان اللون في نطاق صغير. |
| [save(stream_container)](#save_stream_container_4) | يحفظ البيانات إلى حاوية التدفق المحددة. |


### Constructor: ColorRangeHsl() {#ColorRangeHsl__1}


```
 ColorRangeHsl() 
```

يُنشئ مثيلًا جديدًا من الفئة [ColorRangeHsl](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl/) .

### Constructor: ColorRangeHsl(data) {#ColorRangeHsl_data_2}


```
 ColorRangeHsl(data) 
```

يُنشئ مثيلًا جديدًا من الفئة [ColorRangeHsl](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl/) .

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| البيانات | byte | بيانات نطاق اللون. |

### Method: get_range_coefficient(hue) {#get_range_coefficient_hue_1}


```
 get_range_coefficient(hue) 
```

يحصل على معامل النطاق.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| hue | double | قيمة اللون. |

**Returns**

| النوع | الوصف |
| :- | :- |
| double | معامل نطاق التشبع. |


### Method: is_hue_in_big_range(hue) {#is_hue_in_big_range_hue_2}


```
 is_hue_in_big_range(hue) 
```

يحدد ما إذا كان اللون في نطاق كبير.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| hue | double | قيمة اللون. |

**Returns**

| النوع | الوصف |
| :- | :- |
| bool | <c>true</c> إذا كان اللون في نطاق كبير؛ وإلا، <c>false</c>. |


### Method: is_hue_in_small_range(hue) {#is_hue_in_small_range_hue_3}


```
 is_hue_in_small_range(hue) 
```

يحدد ما إذا كان اللون في نطاق صغير.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| hue | double | قيمة اللون. |

**Returns**

| النوع | الوصف |
| :- | :- |
| bool | <c>true</c> إذا كان اللون في نطاق صغير؛ وإلا <c>false</c>. |


### Method: save(stream_container) {#save_stream_container_4}


```
 save(stream_container) 
```

يحفظ البيانات إلى حاوية التدفق المحددة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | حاوية الدفق. |

