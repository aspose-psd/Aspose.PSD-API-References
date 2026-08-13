---
title: "فئة GradientFillSettings"
type: docs
weight: 50
url: /ar/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/
---

**Summary:** Gradient fill effect settings.

**Module:** [aspose.psd.fileformats.psd.layers.fillsettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/)

**Full Name:** aspose.psd.fileformats.psd.layers.fillsettings.GradientFillSettings

**Inheritance:** IFillSettings, IGradientFillSettings, BaseGradientFillSettings

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [GradientFillSettings()](#GradientFillSettings__1) | ينشئ مثيلاً جديداً من الفئة [GradientFillSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/) . |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| align_with_layer | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كان [align with layer]. |
| الزاوية | double | r/w | يحصل أو يضبط الزاوية. |
| color | [Color](/psd/python-net/aspose.psd/color) | r/w | يحصل أو يعيّن اللون. |
| color_points | [IGradientColorPoint[]](/psd/python-net/aspose.psd.fileformats.psd.layers/igradientcolorpoint) | r/w | يحصل أو يعيّن نقاط اللون. |
| dither | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا [BaseGradientFillSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings/) مُبهّر. |
| fill_type | [FillType](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/filltype) | r | نوع التعبئة. |
| gradient_mode | [GradientKind](/psd/python-net/aspose.psd.fileformats.psd.layers.gradient/gradientkind/) | r | يحصل على الوضع لهذا التدرج.<br/>            يحدد 'Gradient Type' = 'Solid/Noise' (0/1). |
| gradient_name | string | r/w | يحصل أو يعيّن اسم التدرج. |
| gradient_type | [GradientType](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradienttype) | r/w | يحصل أو يعيّن نوع التدرج. |
| horizontal_offset | double | r/w | يحصل أو يعيّن الإزاحة الأفقية بالنسبة المئوية. |
| الاستيفاء | short | r/w | الاستيفاء. يحدد السلاسة عندما يكون 'Gradient Type' = 'Solid'. نطاق القيمة: 0-4096. |
| reverse | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا [BaseGradientFillSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings/) معكوسًا. |
| scale | int | r/w | يحصل أو يضبط المقياس. |
| transparency_points | [IGradientTransparencyPoint[]](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint) | r/w | يحصل أو يعيّن نقاط الشفافية. |
| vertical_offset | double | r/w | يحصل أو يعيّن الإزاحة العمودية بالنسبة المئوية. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [add_color_point()](#add_color_point__1) | يضيف نقطة اللون. |
| [add_transparency_point()](#add_transparency_point__2) | يضيف نقطة اللون. |
| [generate_lfx_2_resource_nodes()](#generate_lfx_2_resource_nodes__3) | ينشئ عقد موارد LFX2. |
| [remove_color_point(point)](#remove_color_point_point_4) | يزيل نقطة اللون. |
| [remove_transparency_point(point)](#remove_transparency_point_point_5) | يزيل نقطة الشفافية. |


### Constructor: GradientFillSettings() {#GradientFillSettings__1}


```
 GradientFillSettings() 
```

ينشئ مثيلاً جديداً من الفئة [GradientFillSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/) .

### Method: add_color_point() {#add_color_point__1}


```
 add_color_point() 
```

يضيف نقطة اللون.

**Returns**

| النوع | الوصف |
| :- | :- |
| [GradientColorPoint](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradientcolorpoint) | تم إنشاء نقطة اللون |


### Method: add_transparency_point() {#add_transparency_point__2}


```
 add_transparency_point() 
```

يضيف نقطة اللون.

**Returns**

| النوع | الوصف |
| :- | :- |
| [GradientTransparencyPoint](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradienttransparencypoint) | تم إنشاء نقطة الشفافية |


### Method: generate_lfx_2_resource_nodes()  [static] {#generate_lfx_2_resource_nodes__3}


```
 generate_lfx_2_resource_nodes() 
```

ينشئ عقد موارد LFX2.

**Returns**

| النوع | الوصف |
| :- | :- |
| System.Collections.Generic.List<Aspose.PSD.FileFormats.Psd.Layers.LayerResources.OSTypeStructure> | قائمة مُولَّدة من [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) |


### Method: remove_color_point(point) {#remove_color_point_point_4}


```
 remove_color_point(point) 
```

يزيل نقطة اللون.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| point | [IGradientColorPoint](/psd/python-net/aspose.psd.fileformats.psd.layers/igradientcolorpoint) | النقطة. |

### Method: remove_transparency_point(point) {#remove_transparency_point_point_5}


```
 remove_transparency_point(point) 
```

يزيل نقطة الشفافية.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| point | [IGradientTransparencyPoint](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint) | النقطة. |

