---
title: "ColorantCmyk-klass"
type: docs
weight: 20
url: /sv/python-net/aspose.psd.xmp.types.complex.colorant/colorantcmyk/
---

**Summary:** Represents CMYK Colorant.

**Module:** [aspose.psd.xmp.types.complex.colorant](/psd/python-net/aspose.psd.xmp.types.complex.colorant/)

**Full Name:** aspose.psd.xmp.types.complex.colorant.ColorantCmyk

**Inheritance:** IXmpType, ColorantBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [ColorantCmyk()](#ColorantCmyk__1) | Initierar en ny instans av [ColorantCmyk](/psd/python-net/aspose.psd.xmp.types.complex.colorant/colorantcmyk/) klassen. |
| [ColorantCmyk(black, cyan, magenta, yellow)](#ColorantCmyk_black_cyan_magenta_yellow_2) | Initierar en ny instans av [ColorantCmyk](/psd/python-net/aspose.psd.xmp.types.complex.colorant/colorantcmyk/) klassen. |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| COLOR_VALUE_MAX [static] | float | r | Maximalt färgvärde i CMYK-färgämne. |
| COLOR_VALUE_MIN [static] | float | r | Minimalt färgvärde i CMYK-färgämne. |
| svart | float | r/w | Hämtar eller anger värdet för den svarta komponenten. |
| color_type | [ColorType](/psd/python-net/aspose.psd.xmp.types.complex.colorant/colortype) | r/w | Hämtar eller anger färgens typ. |
| cyan | float | r/w | Hämtar eller anger värdet för cyan-komponenten. |
| magenta | float | r/w | Hämtar eller anger värdet för magenta-komponenten. |
| mode | [ColorMode](/psd/python-net/aspose.psd.xmp.types.complex.colorant/colormode) | r | Hämtar [ColorMode](/psd/python-net/aspose.psd.xmp.types.complex.colorant/colormode/). |
| namespace_uri | string | r | Hämtar standardnamnrymdens URI. |
| prefix | string | r | Hämtar prefixet. |
| swatch_name | string | r/w | Hämtar eller anger namnet på färgprovet. |
| gul | float | r/w | Hämtar eller anger värdet för gul-komponenten. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [get_xmp_representation()](#get_xmp_representation__1) | Hämtar strängens innehållsvärde i XMP-format. |


### Constructor: ColorantCmyk() {#ColorantCmyk__1}


```
 ColorantCmyk() 
```

Initierar en ny instans av [ColorantCmyk](/psd/python-net/aspose.psd.xmp.types.complex.colorant/colorantcmyk/) klassen.

### Constructor: ColorantCmyk(black, cyan, magenta, yellow) {#ColorantCmyk_black_cyan_magenta_yellow_2}


```
 ColorantCmyk(black, cyan, magenta, yellow) 
```

Initierar en ny instans av [ColorantCmyk](/psd/python-net/aspose.psd.xmp.types.complex.colorant/colorantcmyk/) klassen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| svart | float | Det svarta komponentvärdet. |
| cyan | float | Det cyan-färgkomponentvärdet. |
| magenta | float | Det magenta komponentvärdet. |
| gul | float | Det gula komponentvärdet. |

### Method: get_xmp_representation() {#get_xmp_representation__1}


```
 get_xmp_representation() 
```

Hämtar strängens innehållsvärde i XMP-format.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| string | Returnerar strängens innehållsvärde i XMP-format. |


