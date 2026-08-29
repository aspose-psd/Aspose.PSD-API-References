---
title: "Classe ColorantCmyk"
type: docs
weight: 20
url: /fr/python-net/aspose.psd.xmp.types.complex.colorant/colorantcmyk/
---

**Summary:** Represents CMYK Colorant.

**Module:** [aspose.psd.xmp.types.complex.colorant](/psd/python-net/aspose.psd.xmp.types.complex.colorant/)

**Full Name:** aspose.psd.xmp.types.complex.colorant.ColorantCmyk

**Inheritance:** IXmpType, ColorantBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [ColorantCmyk()](#ColorantCmyk__1) | Initialise une nouvelle instance de la classe [ColorantCmyk](/psd/python-net/aspose.psd.xmp.types.complex.colorant/colorantcmyk/) |
| [ColorantCmyk(black, cyan, magenta, yellow)](#ColorantCmyk_black_cyan_magenta_yellow_2) | Initialise une nouvelle instance de la classe [ColorantCmyk](/psd/python-net/aspose.psd.xmp.types.complex.colorant/colorantcmyk/) |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| COLOR_VALUE_MAX [static] | float | r | Valeur maximale de couleur dans le colorant CMYK. |
| COLOR_VALUE_MIN [static] | float | r | Valeur minimale de couleur dans le colorant CMYK. |
| noir | float | r/w | Obtient ou définit la valeur du composant noir. |
| color_type | [ColorType](/psd/python-net/aspose.psd.xmp.types.complex.colorant/colortype) | r/w | Obtient ou définit le type de couleur. |
| cyan | float | r/w | Obtient ou définit la valeur du composant cyan. |
| magenta | float | r/w | Obtient ou définit la valeur du composant magenta. |
| mode | [ColorMode](/psd/python-net/aspose.psd.xmp.types.complex.colorant/colormode) | r | Obtient [ColorMode](/psd/python-net/aspose.psd.xmp.types.complex.colorant/colormode/). |
| namespace_uri | chaîne | r | Obtient le namespace URI par défaut. |
| préfixe | chaîne | r | Obtient le préfixe. |
| swatch_name | chaîne | r/w | Obtient ou définit le nom du nuancier. |
| jaune | float | r/w | Obtient ou définit la valeur du composant jaune. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_xmp_representation()](#get_xmp_representation__1) | Obtient la valeur de chaîne contenue au format XMP. |


### Constructor: ColorantCmyk() {#ColorantCmyk__1}


```
 ColorantCmyk() 
```

Initialise une nouvelle instance de la classe [ColorantCmyk](/psd/python-net/aspose.psd.xmp.types.complex.colorant/colorantcmyk/)

### Constructor: ColorantCmyk(black, cyan, magenta, yellow) {#ColorantCmyk_black_cyan_magenta_yellow_2}


```
 ColorantCmyk(black, cyan, magenta, yellow) 
```

Initialise une nouvelle instance de la classe [ColorantCmyk](/psd/python-net/aspose.psd.xmp.types.complex.colorant/colorantcmyk/)

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| noir | float | La valeur du composant noir. |
| cyan | float | La valeur du composant couleur cyan. |
| magenta | float | La valeur du composant magenta. |
| jaune | float | La valeur du composant jaune. |

### Method: get_xmp_representation() {#get_xmp_representation__1}


```
 get_xmp_representation() 
```

Obtient la valeur de chaîne contenue au format XMP.

**Returns**

| Type | Description |
| :- | :- |
| chaîne | Renvoie la valeur de chaîne contenue au format XMP. |


