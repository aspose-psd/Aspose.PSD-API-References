---
title: "PatternFillSettings क्लास"
type: docs
weight: 130
url: /hi/python-net/aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings/
---

**Summary:** Pattern fill effect settings

**Module:** [aspose.psd.fileformats.psd.layers.fillsettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/)

**Full Name:** aspose.psd.fileformats.psd.layers.fillsettings.PatternFillSettings

**Inheritance:** IFillSettings, IPatternFillSettings, BaseFillSettings

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **विवरण** |
| :- | :- |
| [PatternFillSettings()](#PatternFillSettings__1) | PatternFillSettings क्लास का नया उदाहरण प्रारंभ करता है। |
## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| align_with_layer | bool | r/w | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि [link with layer]। |
| कोण | डबल | r/w | कोण प्राप्त करता है या सेट करता है। |
| color | [Color](/psd/python-net/aspose.psd/color) | r/w | रंग प्राप्त करता है या सेट करता है। |
| fill_type | [FillType](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/filltype) | r | फ़िल प्रकार |
| horizontal_offset | int | r/w | क्षैतिज ऑफ़सेट प्राप्त करता है या सेट करता है। |
| linked | bool | r/w | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि यह [PatternFillSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings/) लिंक्ड है। |
| pattern_data | int | r/w | पैटर्न डेटा प्राप्त करता है या सेट करता है। |
| pattern_height | int | r/w | पैटर्न की ऊँचाई प्राप्त करता है या सेट करता है। |
| pattern_id | string | r/w | पैटर्न पहचानकर्ता प्राप्त करता है या सेट करता है। |
| pattern_name | string | r/w | पैटर्न का नाम प्राप्त करता है या सेट करता है। |
| pattern_width | int | r/w | पैटर्न की चौड़ाई प्राप्त करता है या सेट करता है। |
| point_type | string | r/w | बिंदु का प्रकार प्राप्त करता है या सेट करता है। |
| scale | डबल | r/w | scale को प्राप्त करता है या सेट करता है। |
| vertical_offset | int | r/w | ऊर्ध्वाधर ऑफ़सेट प्राप्त करता है या सेट करता है। |
## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| [generate_lfx_2_resource_nodes(point_type, color, pattern_name, identifier, scale, linked, offset)](#generate_lfx_2_resource_nodes_point_type_color_pattern_name_identifier_scale_linked_offset_1) | LFX2 संसाधन नोड्स उत्पन्न करता है। |


### Constructor: PatternFillSettings() {#PatternFillSettings__1}


```
 PatternFillSettings() 
```

PatternFillSettings क्लास का नया उदाहरण प्रारंभ करता है।

### Method: generate_lfx_2_resource_nodes(point_type, color, pattern_name, identifier, scale, linked, offset)  [static] {#generate_lfx_2_resource_nodes_point_type_color_pattern_name_identifier_scale_linked_offset_1}


```
 generate_lfx_2_resource_nodes(point_type, color, pattern_name, identifier, scale, linked, offset) 
```

LFX2 संसाधन नोड्स उत्पन्न करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| point_type | string | बिंदु का प्रकार। |
| color | [Color](/psd/python-net/aspose.psd/color) | रंग। |
| pattern_name | string | पैटर्न का नाम। |
| पहचानकर्ता | string | पहचानकर्ता। |
| scale | डबल | स्केल। |
| जुड़ा हुआ | bool | यदि <c>true</c> [linked] पर सेट किया गया हो। |
| offset | [PointF](/psd/python-net/aspose.psd/pointf) | ऑफ़सेट। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.PSD.FileFormats.Psd.Layers.LayerResources.OSTypeStructure> | [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) की सूची |


