---
title: "GradientFillSettings क्लास"
type: docs
weight: 50
url: /hi/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/
---

**Summary:** Gradient fill effect settings.

**Module:** [aspose.psd.fileformats.psd.layers.fillsettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/)

**Full Name:** aspose.psd.fileformats.psd.layers.fillsettings.GradientFillSettings

**Inheritance:** IFillSettings, IGradientFillSettings, BaseGradientFillSettings

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **विवरण** |
| :- | :- |
| [GradientFillSettings()](#GradientFillSettings__1) | नया उदाहरण प्रारंभ करता है [GradientFillSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/) क्लास का। |
## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| align_with_layer | bool | r/w | एक मान प्राप्त करता है या सेट करता है जो यह दर्शाता है कि [align with layer]। |
| कोण | डबल | r/w | कोण प्राप्त करता है या सेट करता है। |
| color | [Color](/psd/python-net/aspose.psd/color) | r/w | रंग प्राप्त करता है या सेट करता है। |
| color_points | [IGradientColorPoint[]](/psd/python-net/aspose.psd.fileformats.psd.layers/igradientcolorpoint) | r/w | रंग बिंदुओं को प्राप्त करता है या सेट करता है। |
| dither | bool | r/w | एक मान प्राप्त करता है या सेट करता है जो यह दर्शाता है कि यह [BaseGradientFillSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings/) डिथर है। |
| fill_type | [FillType](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/filltype) | r | भरण प्रकार। |
| gradient_mode | [GradientKind](/psd/python-net/aspose.psd.fileformats.psd.layers.gradient/gradientkind/) | r | इस ग्रेडिएंट के लिए मोड प्राप्त करता है।<br/>            निर्धारित करता है 'Gradient Type' = 'Solid/Noise' (0/1). |
| gradient_name | string | r/w | ग्रेडिएंट का नाम प्राप्त करता है या सेट करता है। |
| gradient_type | [GradientType](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradienttype) | r/w | ग्रेडिएंट का प्रकार प्राप्त करता है या सेट करता है। |
| horizontal_offset | डबल | r/w | प्रतिशत में क्षैतिज ऑफसेट प्राप्त करता है या सेट करता है। |
| इंटरपोलेशन | short | r/w | इंटरपोलेशन। निर्धारित करता है स्मूदनेस, जब 'Gradient Type' = 'Solid'। मान सीमा: 0-4096। |
| reverse | bool | r/w | एक मान प्राप्त करता है या सेट करता है जो यह दर्शाता है कि यह [BaseGradientFillSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings/) रिवर्स है। |
| scale | int | r/w | scale को प्राप्त करता है या सेट करता है। |
| transparency_points | [IGradientTransparencyPoint[]](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint) | r/w | पारदर्शिता बिंदुओं को प्राप्त करता है या सेट करता है। |
| vertical_offset | डबल | r/w | प्रतिशत में लंबवत ऑफसेट प्राप्त करता है या सेट करता है। |
## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| [add_color_point()](#add_color_point__1) | रंग बिंदु जोड़ता है। |
| [add_transparency_point()](#add_transparency_point__2) | रंग बिंदु जोड़ता है। |
| [generate_lfx_2_resource_nodes()](#generate_lfx_2_resource_nodes__3) | LFX2 संसाधन नोड्स उत्पन्न करता है। |
| [remove_color_point(point)](#remove_color_point_point_4) | रंग बिंदु हटाता है। |
| [remove_transparency_point(point)](#remove_transparency_point_point_5) | पारदर्शिता बिंदु हटाता है। |


### Constructor: GradientFillSettings() {#GradientFillSettings__1}


```
 GradientFillSettings() 
```

नया उदाहरण प्रारंभ करता है [GradientFillSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/) क्लास का।

### Method: add_color_point() {#add_color_point__1}


```
 add_color_point() 
```

रंग बिंदु जोड़ता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [GradientColorPoint](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradientcolorpoint) | रंग बिंदु बनाया गया |


### Method: add_transparency_point() {#add_transparency_point__2}


```
 add_transparency_point() 
```

रंग बिंदु जोड़ता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [GradientTransparencyPoint](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradienttransparencypoint) | पारदर्शिता बिंदु बनाया गया |


### Method: generate_lfx_2_resource_nodes()  [static] {#generate_lfx_2_resource_nodes__3}


```
 generate_lfx_2_resource_nodes() 
```

LFX2 संसाधन नोड्स उत्पन्न करता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| System.Collections.Generic.List<Aspose.PSD.FileFormats.Psd.Layers.LayerResources.OSTypeStructure> | जेनरेटेड सूची [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) की। |


### Method: remove_color_point(point) {#remove_color_point_point_4}


```
 remove_color_point(point) 
```

रंग बिंदु हटाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| point | [IGradientColorPoint](/psd/python-net/aspose.psd.fileformats.psd.layers/igradientcolorpoint) | बिंदु। |

### Method: remove_transparency_point(point) {#remove_transparency_point_point_5}


```
 remove_transparency_point(point) 
```

पारदर्शिता बिंदु हटाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| point | [IGradientTransparencyPoint](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint) | बिंदु। |

