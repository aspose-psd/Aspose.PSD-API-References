---
title: "فئة RawColor"
type: docs
weight: 20
url: /ar/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/
---

**Summary:** Raw Color Class helps to store colors with any channels count, any color mode and any bit depth<br/>            Please note, some internal classes can have issues with converting RawColor to its' native format,<br/>            so if API provides for you CMYK color, it's more reliable to use the provided format.<br/>            Also, there are can be some cases when Raw Color can be converted

**Module:** [aspose.psd.fileformats.psd.core.rawcolor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/)

**Full Name:** aspose.psd.fileformats.psd.core.rawcolor.RawColor

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [RawColor(components)](#RawColor_components_1) | ينشئ مثلاً جديداً من الفئة [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/). |
| [RawColor(pixel_data_format, color_mode)](#RawColor_pixel_data_format_color_mode_2) | ينشئ مثلاً جديداً من الفئة [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) من تنسيق بيانات البكسل باستخدام أوضاع اللون المحددة مسبقاً |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| color_mode | short | r/w | الوضع الذي يجب أن يتبعه اللون. |
| components | [ColorComponent[]](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/colorcomponent) | r | يحصل على مكونات اللون. كل مكوّن هو قناة منفصلة، وإذا كنت تستخدم نظام ألوان غير شائع<br/>            فمن الأفضل العمل مع كل قناة على حدة. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [get_as_int()](#get_as_int__1) | يحصل على اللون كعدد صحيح في حال كان من الممكن الحصول عليه. |
| [get_as_long()](#get_as_long__2) | يحصل على اللون كعدد طويل في حال كان من الممكن الحصول عليه. |
| [get_bit_depth()](#get_bit_depth__3) | يحصل على عمق البت للون الخام. <br/>            على سبيل المثال، لون ARGB مع 8 بت لكل قناة/مكوّن هو 32<br/>            عمق البت للون ARGB الكامل مع 16 بت لكل قناة/مكوّن هو 64.<br/>            يتم جمع عمق البت من مجموع أعماق البت للقنوات. <br/>            هذا ممكن إذا كانت القنوات المختلفة لها أعماق بت مختلفة. |
| [get_color_mode_name()](#get_color_mode_name__4) | يحصل على اسم وضع اللون. اسم وضع اللون مُجمّع من أسماء القنوات/المكوّنات. |
| [set_as_int(value)](#set_as_int_value_5) | يعيّن البيانات إلى جميع القنوات من معامل عدد صحيح إذا كان ذلك ممكنًا. |
| [set_as_long(value)](#set_as_long_value_6) | يعيّن البيانات إلى جميع القنوات من معامل عدد صحيح إذا كان ذلك ممكنًا. |


### Constructor: RawColor(components) {#RawColor_components_1}


```
 RawColor(components) 
```

ينشئ مثلاً جديداً من الفئة [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| components | [ColorComponent[]](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/colorcomponent) | مكوّنات اللون المخصصة. |

### Constructor: RawColor(pixel_data_format, color_mode) {#RawColor_pixel_data_format_color_mode_2}


```
 RawColor(pixel_data_format, color_mode) 
```

ينشئ مثلاً جديداً من الفئة [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) من تنسيق بيانات البكسل باستخدام أوضاع اللون المحددة مسبقاً

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| pixel_data_format | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | تنسيق بيانات البكسل. |
| color_mode | short | الوضع الذي يجب أن يتبعه اللون. |

### Method: get_as_int() {#get_as_int__1}


```
 get_as_int() 
```

يحصل على اللون كعدد صحيح في حال كان من الممكن الحصول عليه.

**Returns**

| النوع | الوصف |
| :- | :- |
| int | بيانات القنوات مخزنة كعدد صحيح. |


### Method: get_as_long() {#get_as_long__2}


```
 get_as_long() 
```

يحصل على اللون كعدد طويل في حال كان من الممكن الحصول عليه.

**Returns**

| النوع | الوصف |
| :- | :- |
| long | بيانات القنوات مخزنة كعدد صحيح. |


### Method: get_bit_depth() {#get_bit_depth__3}


```
 get_bit_depth() 
```

يحصل على عمق البت للون الخام. <br/>            على سبيل المثال، لون ARGB مع 8 بت لكل قناة/مكوّن هو 32<br/>            عمق البت للون ARGB الكامل مع 16 بت لكل قناة/مكوّن هو 64.<br/>            يتم جمع عمق البت من مجموع أعماق البت للقنوات. <br/>            هذا ممكن إذا كانت القنوات المختلفة لها أعماق بت مختلفة.

**Returns**

| النوع | الوصف |
| :- | :- |
| int | مجموع جميع أعماق البت للقنوات. |


### Method: get_color_mode_name() {#get_color_mode_name__4}


```
 get_color_mode_name() 
```

يحصل على اسم وضع اللون. اسم وضع اللون مُجمّع من أسماء القنوات/المكوّنات.

**Returns**

| النوع | الوصف |
| :- | :- |
| string | سلسلة تحتوي على اسم وضع اللون. |


### Method: set_as_int(value) {#set_as_int_value_5}


```
 set_as_int(value) 
```

يعيّن البيانات إلى جميع القنوات من معامل عدد صحيح إذا كان ذلك ممكنًا.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| قيمة | int | القيمة العددية الصحيحة التي تحتوي على بيانات المكوّن. |

### Method: set_as_long(value) {#set_as_long_value_6}


```
 set_as_long(value) 
```

يعيّن البيانات إلى جميع القنوات من معامل عدد صحيح إذا كان ذلك ممكنًا.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| قيمة | long | القيمة العددية الصحيحة التي تحتوي على بيانات المكوّن. |

