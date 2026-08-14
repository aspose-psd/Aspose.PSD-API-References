---
title: "ColorantCmyk Klasse"
type: docs
weight: 20
url: /de/python-net/aspose.psd.xmp.types.complex.colorant/colorantcmyk/
---

**Summary:** Represents CMYK Colorant.

**Module:** [aspose.psd.xmp.types.complex.colorant](/psd/python-net/aspose.psd.xmp.types.complex.colorant/)

**Full Name:** aspose.psd.xmp.types.complex.colorant.ColorantCmyk

**Inheritance:** IXmpType, ColorantBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [ColorantCmyk()](#ColorantCmyk__1) | Initialisiert eine neue Instanz der [ColorantCmyk](/psd/python-net/aspose.psd.xmp.types.complex.colorant/colorantcmyk/) Klasse. |
| [ColorantCmyk(black, cyan, magenta, yellow)](#ColorantCmyk_black_cyan_magenta_yellow_2) | Initialisiert eine neue Instanz der [ColorantCmyk](/psd/python-net/aspose.psd.xmp.types.complex.colorant/colorantcmyk/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| COLOR_VALUE_MAX [statisch] | float | r | Maximaler Farbwert im CMYK-Colorant. |
| COLOR_VALUE_MIN [statisch] | float | r | Minimaler Farbwert im CMYK-Colorant. |
| schwarz | float | r/w | Liest oder setzt den Schwarz-Komponentenwert. |
| color_type | [ColorType](/psd/python-net/aspose.psd.xmp.types.complex.colorant/colortype) | r/w | Liest oder setzt den Typ der Farbe. |
| cyan | float | r/w | Liest oder setzt den Cyan-Komponentenwert. |
| magenta | float | r/w | Liest oder setzt den Magenta-Komponentenwert. |
| mode | [ColorMode](/psd/python-net/aspose.psd.xmp.types.complex.colorant/colormode) | r | Liest [ColorMode](/psd/python-net/aspose.psd.xmp.types.complex.colorant/colormode/). |
| namespace_uri | string | r | Liest die Standard-Namespace-URI. |
| prefix | string | r | Liest das Präfix. |
| swatch_name | string | r/w | Liest oder setzt den Namen des Swatch. |
| gelb | float | r/w | Liest oder setzt den Gelb-Komponentenwert. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [get_xmp_representation()](#get_xmp_representation__1) | Liest den im XMP-Format enthaltenen Zeichenkettenwert. |


### Constructor: ColorantCmyk() {#ColorantCmyk__1}


```
 ColorantCmyk() 
```

Initialisiert eine neue Instanz der [ColorantCmyk](/psd/python-net/aspose.psd.xmp.types.complex.colorant/colorantcmyk/) Klasse.

### Constructor: ColorantCmyk(black, cyan, magenta, yellow) {#ColorantCmyk_black_cyan_magenta_yellow_2}


```
 ColorantCmyk(black, cyan, magenta, yellow) 
```

Initialisiert eine neue Instanz der [ColorantCmyk](/psd/python-net/aspose.psd.xmp.types.complex.colorant/colorantcmyk/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| schwarz | float | Der Schwarz-Komponentenwert. |
| cyan | float | Der Cyan-Farbkomponentenwert. |
| magenta | float | Der Magenta-Komponentenwert. |
| gelb | float | Der Gelb-Komponentenwert. |

### Method: get_xmp_representation() {#get_xmp_representation__1}


```
 get_xmp_representation() 
```

Liest den im XMP-Format enthaltenen Zeichenkettenwert.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| string | Gibt den im String enthaltenen Wert im XMP-Format zurück. |


