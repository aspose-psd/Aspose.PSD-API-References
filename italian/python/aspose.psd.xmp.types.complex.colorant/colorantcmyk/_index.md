---
title: "Classe ColorantCmyk"
type: docs
weight: 20
url: /it/python-net/aspose.psd.xmp.types.complex.colorant/colorantcmyk/
---

**Summary:** Represents CMYK Colorant.

**Module:** [aspose.psd.xmp.types.complex.colorant](/psd/python-net/aspose.psd.xmp.types.complex.colorant/)

**Full Name:** aspose.psd.xmp.types.complex.colorant.ColorantCmyk

**Inheritance:** IXmpType, ColorantBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [ColorantCmyk()](#ColorantCmyk__1) | Inizializza una nuova istanza della classe [ColorantCmyk](/psd/python-net/aspose.psd.xmp.types.complex.colorant/colorantcmyk/). |
| [ColorantCmyk(black, cyan, magenta, yellow)](#ColorantCmyk_black_cyan_magenta_yellow_2) | Inizializza una nuova istanza della classe [ColorantCmyk](/psd/python-net/aspose.psd.xmp.types.complex.colorant/colorantcmyk/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| COLOR_VALUE_MAX [static] | float | r | Valore massimo del colore nel colorante CMYK. |
| COLOR_VALUE_MIN [static] | float | r | Valore minimo del colore nel colorante CMYK. |
| nero | float | r/w | Ottiene o imposta il valore del componente nero. |
| color_type | [ColorType](/psd/python-net/aspose.psd.xmp.types.complex.colorant/colortype) | r/w | Ottiene o imposta il tipo di colore. |
| ciano | float | r/w | Ottiene o imposta il valore del componente ciano. |
| magenta | float | r/w | Ottiene o imposta il valore del componente magenta. |
| mode | [ColorMode](/psd/python-net/aspose.psd.xmp.types.complex.colorant/colormode) | r | Ottiene [ColorMode](/psd/python-net/aspose.psd.xmp.types.complex.colorant/colormode/). |
| namespace_uri | string | r | Ottiene l'URI del namespace predefinito. |
| prefisso | string | r | Ottiene il prefisso. |
| swatch_name | string | r/w | Ottiene o imposta il nome del campione. |
| giallo | float | r/w | Ottiene o imposta il valore del componente giallo. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_xmp_representation()](#get_xmp_representation__1) | Ottiene il valore stringa contenuto in formato XMP. |


### Constructor: ColorantCmyk() {#ColorantCmyk__1}


```
 ColorantCmyk() 
```

Inizializza una nuova istanza della classe [ColorantCmyk](/psd/python-net/aspose.psd.xmp.types.complex.colorant/colorantcmyk/).

### Constructor: ColorantCmyk(black, cyan, magenta, yellow) {#ColorantCmyk_black_cyan_magenta_yellow_2}


```
 ColorantCmyk(black, cyan, magenta, yellow) 
```

Inizializza una nuova istanza della classe [ColorantCmyk](/psd/python-net/aspose.psd.xmp.types.complex.colorant/colorantcmyk/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| nero | float | Il valore del componente nero. |
| ciano | float | Il valore del componente colore ciano. |
| magenta | float | Il valore del componente magenta. |
| giallo | float | Il valore del componente giallo. |

### Method: get_xmp_representation() {#get_xmp_representation__1}


```
 get_xmp_representation() 
```

Ottiene il valore stringa contenuto in formato XMP.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| string | Restituisce il valore stringa contenuto in formato XMP. |


