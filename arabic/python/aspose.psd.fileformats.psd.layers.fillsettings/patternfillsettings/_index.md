---
title: "PatternFillSettings فئة"
type: docs
weight: 130
url: /ar/python-net/aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings/
---

**Summary:** Pattern fill effect settings

**Module:** [aspose.psd.fileformats.psd.layers.fillsettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/)

**Full Name:** aspose.psd.fileformats.psd.layers.fillsettings.PatternFillSettings

**Inheritance:** IFillSettings, IPatternFillSettings, BaseFillSettings

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [PatternFillSettings()](#PatternFillSettings__1) | ينشئ مثلاً جديداً من فئة PatternFillSettings |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| align_with_layer | bool | r/w | يحصل أو يضبط قيمة تشير إلى ما إذا كان [link with layer]. |
| الزاوية | double | r/w | يحصل أو يضبط الزاوية. |
| color | [Color](/psd/python-net/aspose.psd/color) | r/w | يحصل أو يعيّن اللون. |
| fill_type | [FillType](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/filltype) | r | نوع التعبئة |
| horizontal_offset | int | r/w | يحصل أو يضبط الإزاحة الأفقية. |
| linked | bool | r/w | يحصل أو يضبط قيمة تشير إلى ما إذا كان هذا [PatternFillSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings/) مرتبطاً. |
| pattern_data | int | r/w | يحصل أو يضبط بيانات النمط. |
| pattern_height | int | r/w | الحصول أو تعيين ارتفاع النمط. |
| pattern_id | string | r/w | الحصول أو تعيين معرف النمط. |
| pattern_name | string | r/w | الحصول أو تعيين اسم النمط. |
| pattern_width | int | r/w | الحصول أو تعيين عرض النمط. |
| point_type | string | r/w | الحصول أو تعيين نوع النقطة. |
| scale | double | r/w | يحصل أو يضبط المقياس. |
| vertical_offset | int | r/w | الحصول أو تعيين الإزاحة العمودية. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [generate_lfx_2_resource_nodes(point_type, color, pattern_name, identifier, scale, linked, offset)](#generate_lfx_2_resource_nodes_point_type_color_pattern_name_identifier_scale_linked_offset_1) | ينشئ عقد موارد LFX2. |


### Constructor: PatternFillSettings() {#PatternFillSettings__1}


```
 PatternFillSettings() 
```

ينشئ مثلاً جديداً من فئة PatternFillSettings

### Method: generate_lfx_2_resource_nodes(point_type, color, pattern_name, identifier, scale, linked, offset)  [static] {#generate_lfx_2_resource_nodes_point_type_color_pattern_name_identifier_scale_linked_offset_1}


```
 generate_lfx_2_resource_nodes(point_type, color, pattern_name, identifier, scale, linked, offset) 
```

ينشئ عقد موارد LFX2.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| point_type | string | نوع النقطة. |
| color | [Color](/psd/python-net/aspose.psd/color) | اللون. |
| pattern_name | string | اسم النمط. |
| معرف | string | المعرف. |
| scale | double | المقياس. |
| مرتبط | bool | إذا تم تعيينه إلى <c>true</c> [linked]. |
| offset | [PointF](/psd/python-net/aspose.psd/pointf) | الإزاحة. |

**Returns**

| النوع | الوصف |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.PSD.FileFormats.Psd.Layers.LayerResources.OSTypeStructure> | قائمة [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) |


