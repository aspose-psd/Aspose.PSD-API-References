---
title: "ColorantCmyk Klasse"
type: docs
weight: 20
url: /nl/python-net/aspose.psd.xmp.types.complex.colorant/colorantcmyk/
---

**Summary:** Represents CMYK Colorant.

**Module:** [aspose.psd.xmp.types.complex.colorant](/psd/python-net/aspose.psd.xmp.types.complex.colorant/)

**Full Name:** aspose.psd.xmp.types.complex.colorant.ColorantCmyk

**Inheritance:** IXmpType, ColorantBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [ColorantCmyk()](#ColorantCmyk__1) | Initialiseert een nieuw exemplaar van de [ColorantCmyk](/psd/python-net/aspose.psd.xmp.types.complex.colorant/colorantcmyk/) klasse. |
| [ColorantCmyk(black, cyan, magenta, yellow)](#ColorantCmyk_black_cyan_magenta_yellow_2) | Initialiseert een nieuw exemplaar van de [ColorantCmyk](/psd/python-net/aspose.psd.xmp.types.complex.colorant/colorantcmyk/) klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| COLOR_VALUE_MAX [static] | float | r | Maximale kleurwaarde in CMYK-kleurstof. |
| COLOR_VALUE_MIN [static] | float | r | Minimale kleurwaarde in CMYK-kleurstof. |
| zwart | float | r/w | Haalt of stelt de zwarte componentwaarde in. |
| color_type | [ColorType](/psd/python-net/aspose.psd.xmp.types.complex.colorant/colortype) | r/w | Haalt of stelt het type van de kleur in. |
| cyaan | float | r/w | Haalt of stelt de cyaan componentwaarde in. |
| magenta | float | r/w | Haalt of stelt de magenta componentwaarde in. |
| mode | [ColorMode](/psd/python-net/aspose.psd.xmp.types.complex.colorant/colormode) | r | Haalt [ColorMode](/psd/python-net/aspose.psd.xmp.types.complex.colorant/colormode/). |
| namespace_uri | string | r | Haalt de standaard namespace-URI op. |
| voorvoegsel | string | r | Haalt het voorvoegsel op. |
| swatch_name | string | r/w | Haalt of stelt de naam van de swatch in. |
| geel | float | r/w | Haalt of stelt de gele componentwaarde in. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [get_xmp_representation()](#get_xmp_representation__1) | Haalt de in de string aanwezige waarde op in XMP-indeling. |


### Constructor: ColorantCmyk() {#ColorantCmyk__1}


```
 ColorantCmyk() 
```

Initialiseert een nieuw exemplaar van de [ColorantCmyk](/psd/python-net/aspose.psd.xmp.types.complex.colorant/colorantcmyk/) klasse.

### Constructor: ColorantCmyk(black, cyan, magenta, yellow) {#ColorantCmyk_black_cyan_magenta_yellow_2}


```
 ColorantCmyk(black, cyan, magenta, yellow) 
```

Initialiseert een nieuw exemplaar van de [ColorantCmyk](/psd/python-net/aspose.psd.xmp.types.complex.colorant/colorantcmyk/) klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| zwart | float | De zwarte componentwaarde. |
| cyaan | float | De cyaan kleurcomponentwaarde. |
| magenta | float | De magenta componentwaarde. |
| geel | float | De gele componentwaarde. |

### Method: get_xmp_representation() {#get_xmp_representation__1}


```
 get_xmp_representation() 
```

Haalt de in de string aanwezige waarde op in XMP-indeling.

**Returns**

| Type | Beschrijving |
| :- | :- |
| string | Retourneert de in de string aanwezige waarde in XMP-indeling. |


