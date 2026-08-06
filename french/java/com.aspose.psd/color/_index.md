---
title: "Color"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "La couleur du pixel."
type: docs
weight: 19
url: /fr/java/com.aspose.psd/color/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class Color extends Struct<Color>
```

La couleur du pixel.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Color()](#Color--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(Color that)](#CloneTo-com.aspose.psd.Color-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Teste si l'objet spécifié est une structure  com.aspose.psd.Color  et est équivalente à cette structure  com.aspose.psd.Color . |
| [fromArgb(byte red, byte green, byte blue)](#fromArgb-byte-byte-byte-) | Crée une structure  com.aspose.psd.Color  à partir des valeurs de couleur 8 bits spécifiées (rouge, vert et bleu). |
| [fromArgb(byte alpha, byte red, byte green, byte blue)](#fromArgb-byte-byte-byte-byte-) | Crée une structure  com.aspose.psd.Color  à partir des quatre valeurs des composants ARGB (alpha, rouge, vert et bleu). |
| [fromArgb(int argb)](#fromArgb-int-) | Crée une structure  com.aspose.psd.Color  à partir d'une valeur ARGB 32 bits. |
| [fromArgb(int alpha, Color baseColor)](#fromArgb-int-com.aspose.psd.Color-) | Crée une structure  com.aspose.psd.Color  à partir de la structure  com.aspose.psd.Color  spécifiée, mais avec la nouvelle valeur alpha spécifiée. |
| [fromArgb(int red, int green, int blue)](#fromArgb-int-int-int-) | Crée une structure  com.aspose.psd.Color  à partir des valeurs de couleur 8 bits spécifiées (rouge, vert et bleu). |
| [fromArgb(int alpha, int red, int green, int blue)](#fromArgb-int-int-int-int-) | Crée une structure  com.aspose.psd.Color  à partir des quatre valeurs des composants ARGB (alpha, rouge, vert et bleu). |
| [fromKnownColor(int color)](#fromKnownColor-int-) | Crée une structure  com.aspose.psd.Color  à partir de la couleur prédéfinie spécifiée. |
| [fromName(String name)](#fromName-java.lang.String-) | Crée une structure  com.aspose.psd.Color  à partir du nom spécifié d'une couleur prédéfinie. |
| [getA()](#getA--) | Obtient la valeur du composant alpha de cette structure  com.aspose.psd.Color . |
| [getAliceBlue()](#getAliceBlue--) | Obtient une couleur définie par le système. |
| [getAntiqueWhite()](#getAntiqueWhite--) | Obtient une couleur définie par le système. |
| [getAqua()](#getAqua--) | Obtient une couleur définie par le système. |
| [getAquamarine()](#getAquamarine--) | Obtient une couleur définie par le système. |
| [getAzure()](#getAzure--) | Obtient une couleur définie par le système. |
| [getB()](#getB--) | Obtient la valeur du composant bleu de cette  com.aspose.psd.Color  structure. |
| [getBeige()](#getBeige--) | Obtient une couleur définie par le système. |
| [getBisque()](#getBisque--) | Obtient une couleur définie par le système. |
| [getBlack()](#getBlack--) | Obtient une couleur définie par le système. |
| [getBlanchedAlmond()](#getBlanchedAlmond--) | Obtient une couleur définie par le système. |
| [getBlue()](#getBlue--) | Obtient une couleur définie par le système. |
| [getBlueViolet()](#getBlueViolet--) | Obtient une couleur définie par le système. |
| [getBrightness()](#getBrightness--) | Obtient la valeur de luminosité teinte-saturation-brillance (HSB) pour cette  com.aspose.psd.Color  structure. |
| [getBrown()](#getBrown--) | Obtient une couleur définie par le système. |
| [getBurlyWood()](#getBurlyWood--) | Obtient une couleur définie par le système. |
| [getCadetBlue()](#getCadetBlue--) | Obtient une couleur définie par le système. |
| [getChartreuse()](#getChartreuse--) | Obtient une couleur définie par le système. |
| [getChocolate()](#getChocolate--) | Obtient une couleur définie par le système. |
| [getClass()](#getClass--) |  |
| [getCoral()](#getCoral--) | Obtient une couleur définie par le système. |
| [getCornflowerBlue()](#getCornflowerBlue--) | Obtient une couleur définie par le système. |
| [getCornsilk()](#getCornsilk--) | Obtient une couleur définie par le système. |
| [getCrimson()](#getCrimson--) | Obtient une couleur définie par le système. |
| [getCyan()](#getCyan--) | Obtient une couleur définie par le système. |
| [getDarkBlue()](#getDarkBlue--) | Obtient une couleur définie par le système. |
| [getDarkCyan()](#getDarkCyan--) | Obtient une couleur définie par le système. |
| [getDarkGoldenrod()](#getDarkGoldenrod--) | Obtient une couleur définie par le système. |
| [getDarkGray()](#getDarkGray--) | Obtient une couleur définie par le système. |
| [getDarkGreen()](#getDarkGreen--) | Obtient une couleur définie par le système. |
| [getDarkKhaki()](#getDarkKhaki--) | Obtient une couleur définie par le système. |
| [getDarkMagenta()](#getDarkMagenta--) | Obtient une couleur définie par le système. |
| [getDarkOliveGreen()](#getDarkOliveGreen--) | Obtient une couleur définie par le système. |
| [getDarkOrange()](#getDarkOrange--) | Obtient une couleur définie par le système. |
| [getDarkOrchid()](#getDarkOrchid--) | Obtient une couleur définie par le système. |
| [getDarkRed()](#getDarkRed--) | Obtient une couleur définie par le système. |
| [getDarkSalmon()](#getDarkSalmon--) | Obtient une couleur définie par le système. |
| [getDarkSeaGreen()](#getDarkSeaGreen--) | Obtient une couleur définie par le système. |
| [getDarkSlateBlue()](#getDarkSlateBlue--) | Obtient une couleur définie par le système. |
| [getDarkSlateGray()](#getDarkSlateGray--) | Obtient une couleur définie par le système. |
| [getDarkTurquoise()](#getDarkTurquoise--) | Obtient une couleur définie par le système. |
| [getDarkViolet()](#getDarkViolet--) | Obtient une couleur définie par le système. |
| [getDeepPink()](#getDeepPink--) | Obtient une couleur définie par le système. |
| [getDeepSkyBlue()](#getDeepSkyBlue--) | Obtient une couleur définie par le système. |
| [getDimGray()](#getDimGray--) | Obtient une couleur définie par le système. |
| [getDodgerBlue()](#getDodgerBlue--) | Obtient une couleur définie par le système. |
| [getEmpty()](#getEmpty--) | Obtient une couleur vide  Color . |
| [getFirebrick()](#getFirebrick--) | Obtient une couleur définie par le système. |
| [getFloralWhite()](#getFloralWhite--) | Obtient une couleur définie par le système. |
| [getForestGreen()](#getForestGreen--) | Obtient une couleur définie par le système. |
| [getFuchsia()](#getFuchsia--) | Obtient une couleur définie par le système. |
| [getG()](#getG--) | Obtient la valeur du composant vert de cette  com.aspose.psd.Color  structure. |
| [getGainsboro()](#getGainsboro--) | Obtient une couleur définie par le système. |
| [getGhostWhite()](#getGhostWhite--) | Obtient une couleur définie par le système. |
| [getGold()](#getGold--) | Obtient une couleur définie par le système. |
| [getGoldenrod()](#getGoldenrod--) | Obtient une couleur définie par le système. |
| [getGray()](#getGray--) | Obtient une couleur définie par le système. |
| [getGreen()](#getGreen--) | Obtient une couleur définie par le système. |
| [getGreenYellow()](#getGreenYellow--) | Obtient une couleur définie par le système. |
| [getHoneydew()](#getHoneydew--) | Obtient une couleur définie par le système. |
| [getHotPink()](#getHotPink--) | Obtient une couleur définie par le système. |
| [getHue()](#getHue--) | Obtient la valeur de teinte teinte-saturation-brillance (HSB), en degrés, pour cette  com.aspose.psd.Color  structure. |
| [getIndianRed()](#getIndianRed--) | Obtient une couleur définie par le système. |
| [getIndigo()](#getIndigo--) | Obtient une couleur définie par le système. |
| [getIvory()](#getIvory--) | Obtient une couleur définie par le système. |
| [getKhaki()](#getKhaki--) | Obtient une couleur définie par le système. |
| [getLavender()](#getLavender--) | Obtient une couleur définie par le système. |
| [getLavenderBlush()](#getLavenderBlush--) | Obtient une couleur définie par le système. |
| [getLawnGreen()](#getLawnGreen--) | Obtient une couleur définie par le système. |
| [getLemonChiffon()](#getLemonChiffon--) | Obtient une couleur définie par le système. |
| [getLightBlue()](#getLightBlue--) | Obtient une couleur définie par le système. |
| [getLightCoral()](#getLightCoral--) | Obtient une couleur définie par le système. |
| [getLightCyan()](#getLightCyan--) | Obtient une couleur définie par le système. |
| [getLightGoldenrodYellow()](#getLightGoldenrodYellow--) | Obtient une couleur définie par le système. |
| [getLightGray()](#getLightGray--) | Obtient une couleur définie par le système. |
| [getLightGreen()](#getLightGreen--) | Obtient une couleur définie par le système. |
| [getLightPink()](#getLightPink--) | Obtient une couleur définie par le système. |
| [getLightSalmon()](#getLightSalmon--) | Obtient une couleur définie par le système. |
| [getLightSeaGreen()](#getLightSeaGreen--) | Obtient une couleur définie par le système. |
| [getLightSkyBlue()](#getLightSkyBlue--) | Obtient une couleur définie par le système. |
| [getLightSlateGray()](#getLightSlateGray--) | Obtient une couleur définie par le système. |
| [getLightSteelBlue()](#getLightSteelBlue--) | Obtient une couleur définie par le système. |
| [getLightYellow()](#getLightYellow--) | Obtient une couleur définie par le système. |
| [getLime()](#getLime--) | Obtient une couleur définie par le système. |
| [getLimeGreen()](#getLimeGreen--) | Obtient une couleur définie par le système. |
| [getLinen()](#getLinen--) | Obtient une couleur définie par le système. |
| [getMagenta()](#getMagenta--) | Obtient une couleur définie par le système. |
| [getMaroon()](#getMaroon--) | Obtient une couleur définie par le système. |
| [getMediumAquamarine()](#getMediumAquamarine--) | Obtient une couleur définie par le système. |
| [getMediumBlue()](#getMediumBlue--) | Obtient une couleur définie par le système. |
| [getMediumOrchid()](#getMediumOrchid--) | Obtient une couleur définie par le système. |
| [getMediumPurple()](#getMediumPurple--) | Obtient une couleur définie par le système. |
| [getMediumSeaGreen()](#getMediumSeaGreen--) | Obtient une couleur définie par le système. |
| [getMediumSlateBlue()](#getMediumSlateBlue--) | Obtient une couleur définie par le système. |
| [getMediumSpringGreen()](#getMediumSpringGreen--) | Obtient une couleur définie par le système. |
| [getMediumTurquoise()](#getMediumTurquoise--) | Obtient une couleur définie par le système. |
| [getMediumVioletRed()](#getMediumVioletRed--) | Obtient une couleur définie par le système. |
| [getMidnightBlue()](#getMidnightBlue--) | Obtient une couleur définie par le système. |
| [getMintCream()](#getMintCream--) | Obtient une couleur définie par le système. |
| [getMistyRose()](#getMistyRose--) | Obtient une couleur définie par le système. |
| [getMoccasin()](#getMoccasin--) | Obtient une couleur définie par le système. |
| [getName()](#getName--) | Obtient le nom de cette  com.aspose.psd.Color . |
| [getNavajoWhite()](#getNavajoWhite--) | Obtient une couleur définie par le système. |
| [getNavy()](#getNavy--) | Obtient une couleur définie par le système. |
| [getOldLace()](#getOldLace--) | Obtient une couleur définie par le système. |
| [getOlive()](#getOlive--) | Obtient une couleur définie par le système. |
| [getOliveDrab()](#getOliveDrab--) | Obtient une couleur définie par le système. |
| [getOrange()](#getOrange--) | Obtient une couleur définie par le système. |
| [getOrangeRed()](#getOrangeRed--) | Obtient une couleur définie par le système. |
| [getOrchid()](#getOrchid--) | Obtient une couleur définie par le système. |
| [getPaleGoldenrod()](#getPaleGoldenrod--) | Obtient une couleur définie par le système. |
| [getPaleGreen()](#getPaleGreen--) | Obtient une couleur définie par le système. |
| [getPaleTurquoise()](#getPaleTurquoise--) | Obtient une couleur définie par le système. |
| [getPaleVioletRed()](#getPaleVioletRed--) | Obtient une couleur définie par le système. |
| [getPapayaWhip()](#getPapayaWhip--) | Obtient une couleur définie par le système. |
| [getPeachPuff()](#getPeachPuff--) | Obtient une couleur définie par le système. |
| [getPeru()](#getPeru--) | Obtient une couleur définie par le système. |
| [getPink()](#getPink--) | Obtient une couleur définie par le système. |
| [getPlum()](#getPlum--) | Obtient une couleur définie par le système. |
| [getPowderBlue()](#getPowderBlue--) | Obtient une couleur définie par le système. |
| [getPurple()](#getPurple--) | Obtient une couleur définie par le système. |
| [getR()](#getR--) | Obtient la valeur du composant rouge de cette  com.aspose.psd.Color  structure. |
| [getRed()](#getRed--) | Obtient une couleur définie par le système. |
| [getRosyBrown()](#getRosyBrown--) | Obtient une couleur définie par le système. |
| [getRoyalBlue()](#getRoyalBlue--) | Obtient une couleur définie par le système. |
| [getSaddleBrown()](#getSaddleBrown--) | Obtient une couleur définie par le système. |
| [getSalmon()](#getSalmon--) | Obtient une couleur définie par le système. |
| [getSandyBrown()](#getSandyBrown--) | Obtient une couleur définie par le système. |
| [getSaturation()](#getSaturation--) | Obtient la valeur de saturation teinte-saturation-brillance (HSB) pour cette  com.aspose.psd.Color  structure. |
| [getSeaGreen()](#getSeaGreen--) | Obtient une couleur définie par le système. |
| [getSeaShell()](#getSeaShell--) | Obtient une couleur définie par le système. |
| [getSienna()](#getSienna--) | Obtient une couleur définie par le système. |
| [getSilver()](#getSilver--) | Obtient une couleur définie par le système. |
| [getSkyBlue()](#getSkyBlue--) | Obtient une couleur définie par le système. |
| [getSlateBlue()](#getSlateBlue--) | Obtient une couleur définie par le système. |
| [getSlateGray()](#getSlateGray--) | Obtient une couleur définie par le système. |
| [getSnow()](#getSnow--) | Obtient une couleur définie par le système. |
| [getSpringGreen()](#getSpringGreen--) | Obtient une couleur définie par le système. |
| [getSteelBlue()](#getSteelBlue--) | Obtient une couleur définie par le système. |
| [getTan()](#getTan--) | Obtient une couleur définie par le système. |
| [getTeal()](#getTeal--) | Obtient une couleur définie par le système. |
| [getThistle()](#getThistle--) | Obtient une couleur définie par le système. |
| [getTomato()](#getTomato--) | Obtient une couleur définie par le système. |
| [getTransparent()](#getTransparent--) | Obtient une couleur définie par le système. |
| [getTurquoise()](#getTurquoise--) | Obtient une couleur définie par le système. |
| [getViolet()](#getViolet--) | Obtient une couleur définie par le système. |
| [getWheat()](#getWheat--) | Obtient une couleur définie par le système. |
| [getWhite()](#getWhite--) | Obtient une couleur définie par le système. |
| [getWhiteSmoke()](#getWhiteSmoke--) | Obtient une couleur définie par le système. |
| [getYellow()](#getYellow--) | Obtient une couleur définie par le système. |
| [getYellowGreen()](#getYellowGreen--) | Obtient une couleur définie par le système. |
| [hashCode()](#hashCode--) | Renvoie un code de hachage pour cette  com.aspose.psd.Color  structure. |
| [isEmpty()](#isEmpty--) | Obtient une valeur indiquant si cette  com.aspose.psd.Color  structure est non initialisée. |
| [isEquals(Color obj1, Color obj2)](#isEquals-com.aspose.psd.Color-com.aspose.psd.Color-) |  |
| [isKnownColor()](#isKnownColor--) | Obtient une valeur indiquant si cette  com.aspose.psd.Color  structure est une couleur prédéfinie. |
| [isNamedColor()](#isNamedColor--) | Obtient une valeur indiquant si cette  com.aspose.psd.Color  structure est une couleur nommée ou un membre de l'énumération  Aspose.Imaging.KnownColor  . |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Equality(Color left, Color right)](#op-Equality-com.aspose.psd.Color-com.aspose.psd.Color-) | Teste si deux structures  com.aspose.psd.Color  spécifiées sont équivalentes. |
| [op_Inequality(Color left, Color right)](#op-Inequality-com.aspose.psd.Color-com.aspose.psd.Color-) | Teste si deux structures  com.aspose.psd.Color  spécifiées sont différentes. |
| [toArgb()](#toArgb--) | Obtient la valeur ARGB 32 bits de cette  com.aspose.psd.Color  structure. |
| [toCmyk(Color pixel)](#toCmyk-com.aspose.psd.Color-) | La conversion de Color vers CmykColor. |
| [toCmyk(Color[] pixels)](#toCmyk-com.aspose.psd.Color---) | La conversion de Color vers CMYKColor. |
| [toCmykIcc(Color pixel)](#toCmykIcc-com.aspose.psd.Color-) | La conversion de Color vers CMYKColor utilisant la conversion icc avec les profils par défaut. |
| [toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIcc-com.aspose.psd.Color-java.io.InputStream-java.io.InputStream-) | La conversion de Color vers CMYKColor utilisant la conversion icc avec les profils par défaut. |
| [toCmykIcc(Color[] pixels)](#toCmykIcc-com.aspose.psd.Color---) | La conversion de Color vers CMYKColor utilisant la conversion icc avec les profils par défaut. |
| [toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIcc-com.aspose.psd.Color---java.io.InputStream-java.io.InputStream-) | La conversion de Color vers CMYKColor utilisant la conversion icc. |
| [toCmykIcc_internalized(Color pixel, System.IO.Stream rgbIccStream, System.IO.Stream cmykIccStream)](#toCmykIcc-internalized-com.aspose.psd.Color-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-) |  |
| [toCmykIcc_internalized(Color[] pixels, System.IO.Stream rgbIccStream, System.IO.Stream cmykIccStream)](#toCmykIcc-internalized-com.aspose.psd.Color---com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-) |  |
| [toKnownColor()](#toKnownColor--) | Obtient la valeur  Aspose.Imaging.KnownColor  de cette  com.aspose.psd.Color  structure. |
| [toString()](#toString--) | Convertit cette  com.aspose.psd.Color  structure en une chaîne lisible par l'homme. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Color() {#Color--}
```
public Color()
```


### Clone() {#Clone--}
```
public Color Clone()
```




**Returns:**
[Color](../../com.aspose.psd/color)
### CloneTo(T arg0) {#CloneTo-T-}
```
public abstract void CloneTo(T arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(Color that) {#CloneTo-com.aspose.psd.Color-}
```
public void CloneTo(Color that)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| that | [Color](../../com.aspose.psd/color) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Teste si l'objet spécifié est une structure  com.aspose.psd.Color  et est équivalente à cette structure  com.aspose.psd.Color .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | L'objet à tester. |

**Returns:**
booléen - Vrai si  obj  est une structure  com.aspose.psd.Color  équivalente à cette  com.aspose.psd.Color  structure ; sinon, faux.
### fromArgb(byte red, byte green, byte blue) {#fromArgb-byte-byte-byte-}
```
public static Color fromArgb(byte red, byte green, byte blue)
```


Crée une structure  com.aspose.psd.Color  à partir des valeurs de couleur 8 bits spécifiées (rouge, vert et bleu). La valeur alpha est implicitement 255 (complètement opaque). Bien que cette méthode permette de passer une valeur 32 bits pour chaque composant de couleur, la valeur de chaque composant est limitée à 8 bits.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rouge | byte | La valeur du composant rouge pour le nouveau  com.aspose.psd.Color . Les valeurs valides sont de 0 à 255. |
| vert | byte | La valeur du composant vert pour le nouveau com.aspose.psd.Color. Les valeurs valides sont de 0 à 255. |
| bleu | byte | La valeur du composant bleu pour le nouveau com.aspose.psd.Color. Les valeurs valides sont de 0 à 255. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  com.aspose.psd.Color  that this method creates.
### fromArgb(byte alpha, byte red, byte green, byte blue) {#fromArgb-byte-byte-byte-byte-}
```
public static Color fromArgb(byte alpha, byte red, byte green, byte blue)
```


Crée une structure com.aspose.psd.Color à partir des quatre valeurs de composant ARGB (alpha, rouge, vert et bleu). Bien que cette méthode permette de transmettre une valeur de 32 bits pour chaque composant, la valeur de chaque composant est limitée à 8 bits.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| alpha | byte | Le composant alpha. Les valeurs valides sont de 0 à 255. |
| rouge | byte | Le composant rouge. Les valeurs valides sont de 0 à 255. |
| vert | byte | Le composant vert. Les valeurs valides sont de 0 à 255. |
| bleu | byte | Le composant bleu. Les valeurs valides sont de 0 à 255. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  com.aspose.psd.Color  that this method creates.
### fromArgb(int argb) {#fromArgb-int-}
```
public static Color fromArgb(int argb)
```


Crée une structure  com.aspose.psd.Color  à partir d'une valeur ARGB 32 bits.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| argb | int | Une valeur spécifiant la valeur ARGB de 32 bits. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  com.aspose.psd.Color  structure that this method creates.
### fromArgb(int alpha, Color baseColor) {#fromArgb-int-com.aspose.psd.Color-}
```
public static Color fromArgb(int alpha, Color baseColor)
```


Crée une structure com.aspose.psd.Color à partir de la structure com.aspose.psd.Color spécifiée, mais avec la nouvelle valeur alpha spécifiée. Bien que cette méthode permette de transmettre une valeur de 32 bits pour la valeur alpha, celle-ci est limitée à 8 bits.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| alpha | int | La valeur alpha pour le nouveau com.aspose.psd.Color. Les valeurs valides sont de 0 à 255. |
| baseColor | [Color](../../com.aspose.psd/color) | Le com.aspose.psd.Color à partir duquel créer le nouveau com.aspose.psd.Color. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  com.aspose.psd.Color  that this method creates.
### fromArgb(int red, int green, int blue) {#fromArgb-int-int-int-}
```
public static Color fromArgb(int red, int green, int blue)
```


Crée une structure  com.aspose.psd.Color  à partir des valeurs de couleur 8 bits spécifiées (rouge, vert et bleu). La valeur alpha est implicitement 255 (complètement opaque). Bien que cette méthode permette de passer une valeur 32 bits pour chaque composant de couleur, la valeur de chaque composant est limitée à 8 bits.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rouge | int | La valeur du composant rouge pour le nouveau  com.aspose.psd.Color . Les valeurs valides sont de 0 à 255. |
| vert | int | La valeur du composant vert pour le nouveau com.aspose.psd.Color. Les valeurs valides sont de 0 à 255. |
| bleu | int | La valeur du composant bleu pour le nouveau com.aspose.psd.Color. Les valeurs valides sont de 0 à 255. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  com.aspose.psd.Color  that this method creates.
### fromArgb(int alpha, int red, int green, int blue) {#fromArgb-int-int-int-int-}
```
public static Color fromArgb(int alpha, int red, int green, int blue)
```


Crée une structure com.aspose.psd.Color à partir des quatre valeurs de composant ARGB (alpha, rouge, vert et bleu). Bien que cette méthode permette de transmettre une valeur de 32 bits pour chaque composant, la valeur de chaque composant est limitée à 8 bits.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| alpha | int | Le composant alpha. Les valeurs valides sont de 0 à 255. |
| rouge | int | Le composant rouge. Les valeurs valides sont de 0 à 255. |
| vert | int | Le composant vert. Les valeurs valides sont de 0 à 255. |
| bleu | int | Le composant bleu. Les valeurs valides sont de 0 à 255. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  com.aspose.psd.Color  that this method creates.
### fromKnownColor(int color) {#fromKnownColor-int-}
```
public static Color fromKnownColor(int color)
```


Crée une structure  com.aspose.psd.Color  à partir de la couleur prédéfinie spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| couleur | int | Un élément de l'énumération Aspose.Imaging.KnownColor. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  com.aspose.psd.Color  that this method creates.
### fromName(String name) {#fromName-java.lang.String-}
```
public static Color fromName(String name)
```


Crée une structure  com.aspose.psd.Color  à partir du nom spécifié d'une couleur prédéfinie.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nom | java.lang.String | Une chaîne qui est le nom d'une couleur prédéfinie. Les noms valides sont les mêmes que les noms des éléments de l'énumération Aspose.Imaging.KnownColor. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  com.aspose.psd.Color  that this method creates.
### getA() {#getA--}
```
public byte getA()
```


Obtient la valeur du composant alpha de cette structure  com.aspose.psd.Color .

**Returns:**
byte - La valeur du composant alpha de ce com.aspose.psd.Color.
### getAliceBlue() {#getAliceBlue--}
```
public static Color getAliceBlue()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getAntiqueWhite() {#getAntiqueWhite--}
```
public static Color getAntiqueWhite()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getAqua() {#getAqua--}
```
public static Color getAqua()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getAquamarine() {#getAquamarine--}
```
public static Color getAquamarine()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getAzure() {#getAzure--}
```
public static Color getAzure()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getB() {#getB--}
```
public byte getB()
```


Obtient la valeur du composant bleu de cette  com.aspose.psd.Color  structure.

**Returns:**
byte - La valeur du composant bleu de ce com.aspose.psd.Color.
### getBeige() {#getBeige--}
```
public static Color getBeige()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getBisque() {#getBisque--}
```
public static Color getBisque()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getBlack() {#getBlack--}
```
public static Color getBlack()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getBlanchedAlmond() {#getBlanchedAlmond--}
```
public static Color getBlanchedAlmond()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getBlue() {#getBlue--}
```
public static Color getBlue()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getBlueViolet() {#getBlueViolet--}
```
public static Color getBlueViolet()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getBrightness() {#getBrightness--}
```
public float getBrightness()
```


Obtient la valeur de luminosité teinte-saturation-brillance (HSB) pour cette  com.aspose.psd.Color  structure.

**Returns:**
float - La luminosité de ce com.aspose.psd.Color. La luminosité varie de 0,0 à 1,0, où 0,0 représente le noir et 1,0 représente le blanc.
### getBrown() {#getBrown--}
```
public static Color getBrown()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getBurlyWood() {#getBurlyWood--}
```
public static Color getBurlyWood()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getCadetBlue() {#getCadetBlue--}
```
public static Color getCadetBlue()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getChartreuse() {#getChartreuse--}
```
public static Color getChartreuse()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getChocolate() {#getChocolate--}
```
public static Color getChocolate()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCoral() {#getCoral--}
```
public static Color getCoral()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getCornflowerBlue() {#getCornflowerBlue--}
```
public static Color getCornflowerBlue()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getCornsilk() {#getCornsilk--}
```
public static Color getCornsilk()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getCrimson() {#getCrimson--}
```
public static Color getCrimson()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getCyan() {#getCyan--}
```
public static Color getCyan()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkBlue() {#getDarkBlue--}
```
public static Color getDarkBlue()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkCyan() {#getDarkCyan--}
```
public static Color getDarkCyan()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkGoldenrod() {#getDarkGoldenrod--}
```
public static Color getDarkGoldenrod()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkGray() {#getDarkGray--}
```
public static Color getDarkGray()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkGreen() {#getDarkGreen--}
```
public static Color getDarkGreen()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkKhaki() {#getDarkKhaki--}
```
public static Color getDarkKhaki()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkMagenta() {#getDarkMagenta--}
```
public static Color getDarkMagenta()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkOliveGreen() {#getDarkOliveGreen--}
```
public static Color getDarkOliveGreen()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkOrange() {#getDarkOrange--}
```
public static Color getDarkOrange()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkOrchid() {#getDarkOrchid--}
```
public static Color getDarkOrchid()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkRed() {#getDarkRed--}
```
public static Color getDarkRed()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkSalmon() {#getDarkSalmon--}
```
public static Color getDarkSalmon()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkSeaGreen() {#getDarkSeaGreen--}
```
public static Color getDarkSeaGreen()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkSlateBlue() {#getDarkSlateBlue--}
```
public static Color getDarkSlateBlue()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkSlateGray() {#getDarkSlateGray--}
```
public static Color getDarkSlateGray()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkTurquoise() {#getDarkTurquoise--}
```
public static Color getDarkTurquoise()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkViolet() {#getDarkViolet--}
```
public static Color getDarkViolet()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDeepPink() {#getDeepPink--}
```
public static Color getDeepPink()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDeepSkyBlue() {#getDeepSkyBlue--}
```
public static Color getDeepSkyBlue()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDimGray() {#getDimGray--}
```
public static Color getDimGray()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDodgerBlue() {#getDodgerBlue--}
```
public static Color getDodgerBlue()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getEmpty() {#getEmpty--}
```
public static Color getEmpty()
```


Obtient une couleur vide  Color .

**Returns:**
[Color](../../com.aspose.psd/color) - The empty  Color .
### getFirebrick() {#getFirebrick--}
```
public static Color getFirebrick()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getFloralWhite() {#getFloralWhite--}
```
public static Color getFloralWhite()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getForestGreen() {#getForestGreen--}
```
public static Color getForestGreen()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getFuchsia() {#getFuchsia--}
```
public static Color getFuchsia()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getG() {#getG--}
```
public byte getG()
```


Obtient la valeur du composant vert de cette  com.aspose.psd.Color  structure.

**Returns:**
byte - La valeur du composant vert de ce com.aspose.psd.Color.
### getGainsboro() {#getGainsboro--}
```
public static Color getGainsboro()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getGhostWhite() {#getGhostWhite--}
```
public static Color getGhostWhite()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getGold() {#getGold--}
```
public static Color getGold()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getGoldenrod() {#getGoldenrod--}
```
public static Color getGoldenrod()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getGray() {#getGray--}
```
public static Color getGray()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  structure representing a system-defined color.
### getGreen() {#getGreen--}
```
public static Color getGreen()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getGreenYellow() {#getGreenYellow--}
```
public static Color getGreenYellow()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getHoneydew() {#getHoneydew--}
```
public static Color getHoneydew()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getHotPink() {#getHotPink--}
```
public static Color getHotPink()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getHue() {#getHue--}
```
public float getHue()
```


Obtient la valeur de teinte teinte-saturation-brillance (HSB), en degrés, pour cette  com.aspose.psd.Color  structure.

**Returns:**
float - La teinte, en degrés, de ce com.aspose.psd.Color. La teinte est mesurée en degrés, allant de 0,0 à 360,0, dans l'espace colorimétrique HSB.
### getIndianRed() {#getIndianRed--}
```
public static Color getIndianRed()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getIndigo() {#getIndigo--}
```
public static Color getIndigo()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getIvory() {#getIvory--}
```
public static Color getIvory()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getKhaki() {#getKhaki--}
```
public static Color getKhaki()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLavender() {#getLavender--}
```
public static Color getLavender()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLavenderBlush() {#getLavenderBlush--}
```
public static Color getLavenderBlush()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLawnGreen() {#getLawnGreen--}
```
public static Color getLawnGreen()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLemonChiffon() {#getLemonChiffon--}
```
public static Color getLemonChiffon()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightBlue() {#getLightBlue--}
```
public static Color getLightBlue()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightCoral() {#getLightCoral--}
```
public static Color getLightCoral()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightCyan() {#getLightCyan--}
```
public static Color getLightCyan()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightGoldenrodYellow() {#getLightGoldenrodYellow--}
```
public static Color getLightGoldenrodYellow()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightGray() {#getLightGray--}
```
public static Color getLightGray()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightGreen() {#getLightGreen--}
```
public static Color getLightGreen()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightPink() {#getLightPink--}
```
public static Color getLightPink()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightSalmon() {#getLightSalmon--}
```
public static Color getLightSalmon()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightSeaGreen() {#getLightSeaGreen--}
```
public static Color getLightSeaGreen()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightSkyBlue() {#getLightSkyBlue--}
```
public static Color getLightSkyBlue()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightSlateGray() {#getLightSlateGray--}
```
public static Color getLightSlateGray()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightSteelBlue() {#getLightSteelBlue--}
```
public static Color getLightSteelBlue()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightYellow() {#getLightYellow--}
```
public static Color getLightYellow()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLime() {#getLime--}
```
public static Color getLime()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLimeGreen() {#getLimeGreen--}
```
public static Color getLimeGreen()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLinen() {#getLinen--}
```
public static Color getLinen()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMagenta() {#getMagenta--}
```
public static Color getMagenta()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMaroon() {#getMaroon--}
```
public static Color getMaroon()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMediumAquamarine() {#getMediumAquamarine--}
```
public static Color getMediumAquamarine()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMediumBlue() {#getMediumBlue--}
```
public static Color getMediumBlue()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMediumOrchid() {#getMediumOrchid--}
```
public static Color getMediumOrchid()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMediumPurple() {#getMediumPurple--}
```
public static Color getMediumPurple()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMediumSeaGreen() {#getMediumSeaGreen--}
```
public static Color getMediumSeaGreen()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMediumSlateBlue() {#getMediumSlateBlue--}
```
public static Color getMediumSlateBlue()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMediumSpringGreen() {#getMediumSpringGreen--}
```
public static Color getMediumSpringGreen()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMediumTurquoise() {#getMediumTurquoise--}
```
public static Color getMediumTurquoise()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMediumVioletRed() {#getMediumVioletRed--}
```
public static Color getMediumVioletRed()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMidnightBlue() {#getMidnightBlue--}
```
public static Color getMidnightBlue()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMintCream() {#getMintCream--}
```
public static Color getMintCream()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMistyRose() {#getMistyRose--}
```
public static Color getMistyRose()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMoccasin() {#getMoccasin--}
```
public static Color getMoccasin()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getName() {#getName--}
```
public String getName()
```


Obtient le nom de cette  com.aspose.psd.Color .

**Returns:**
java.lang.String - Le nom de ce com.aspose.psd.Color.
### getNavajoWhite() {#getNavajoWhite--}
```
public static Color getNavajoWhite()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getNavy() {#getNavy--}
```
public static Color getNavy()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getOldLace() {#getOldLace--}
```
public static Color getOldLace()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getOlive() {#getOlive--}
```
public static Color getOlive()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getOliveDrab() {#getOliveDrab--}
```
public static Color getOliveDrab()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getOrange() {#getOrange--}
```
public static Color getOrange()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getOrangeRed() {#getOrangeRed--}
```
public static Color getOrangeRed()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getOrchid() {#getOrchid--}
```
public static Color getOrchid()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPaleGoldenrod() {#getPaleGoldenrod--}
```
public static Color getPaleGoldenrod()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPaleGreen() {#getPaleGreen--}
```
public static Color getPaleGreen()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPaleTurquoise() {#getPaleTurquoise--}
```
public static Color getPaleTurquoise()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPaleVioletRed() {#getPaleVioletRed--}
```
public static Color getPaleVioletRed()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPapayaWhip() {#getPapayaWhip--}
```
public static Color getPapayaWhip()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPeachPuff() {#getPeachPuff--}
```
public static Color getPeachPuff()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPeru() {#getPeru--}
```
public static Color getPeru()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPink() {#getPink--}
```
public static Color getPink()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPlum() {#getPlum--}
```
public static Color getPlum()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPowderBlue() {#getPowderBlue--}
```
public static Color getPowderBlue()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPurple() {#getPurple--}
```
public static Color getPurple()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getR() {#getR--}
```
public byte getR()
```


Obtient la valeur du composant rouge de cette  com.aspose.psd.Color  structure.

**Returns:**
byte - La valeur du composant rouge de ce com.aspose.psd.Color.
### getRed() {#getRed--}
```
public static Color getRed()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getRosyBrown() {#getRosyBrown--}
```
public static Color getRosyBrown()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getRoyalBlue() {#getRoyalBlue--}
```
public static Color getRoyalBlue()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSaddleBrown() {#getSaddleBrown--}
```
public static Color getSaddleBrown()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSalmon() {#getSalmon--}
```
public static Color getSalmon()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSandyBrown() {#getSandyBrown--}
```
public static Color getSandyBrown()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSaturation() {#getSaturation--}
```
public float getSaturation()
```


Obtient la valeur de saturation teinte-saturation-brillance (HSB) pour cette  com.aspose.psd.Color  structure.

**Returns:**
float - La saturation de ce com.aspose.psd.Color. La saturation varie de 0,0 à 1,0, où 0,0 est en niveaux de gris et 1,0 est la plus saturée.
### getSeaGreen() {#getSeaGreen--}
```
public static Color getSeaGreen()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSeaShell() {#getSeaShell--}
```
public static Color getSeaShell()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSienna() {#getSienna--}
```
public static Color getSienna()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSilver() {#getSilver--}
```
public static Color getSilver()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSkyBlue() {#getSkyBlue--}
```
public static Color getSkyBlue()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSlateBlue() {#getSlateBlue--}
```
public static Color getSlateBlue()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSlateGray() {#getSlateGray--}
```
public static Color getSlateGray()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSnow() {#getSnow--}
```
public static Color getSnow()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSpringGreen() {#getSpringGreen--}
```
public static Color getSpringGreen()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSteelBlue() {#getSteelBlue--}
```
public static Color getSteelBlue()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getTan() {#getTan--}
```
public static Color getTan()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getTeal() {#getTeal--}
```
public static Color getTeal()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getThistle() {#getThistle--}
```
public static Color getThistle()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getTomato() {#getTomato--}
```
public static Color getTomato()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getTransparent() {#getTransparent--}
```
public static Color getTransparent()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getTurquoise() {#getTurquoise--}
```
public static Color getTurquoise()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getViolet() {#getViolet--}
```
public static Color getViolet()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getWheat() {#getWheat--}
```
public static Color getWheat()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getWhite() {#getWhite--}
```
public static Color getWhite()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getWhiteSmoke() {#getWhiteSmoke--}
```
public static Color getWhiteSmoke()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getYellow() {#getYellow--}
```
public static Color getYellow()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getYellowGreen() {#getYellowGreen--}
```
public static Color getYellowGreen()
```


Obtient une couleur définie par le système.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Renvoie un code de hachage pour cette  com.aspose.psd.Color  structure.

**Returns:**
int - Une valeur entière qui spécifie le code de hachage pour ce com.aspose.psd.Color.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Obtient une valeur indiquant si cette  com.aspose.psd.Color  structure est non initialisée.

**Returns:**
boolean - Cette propriété renvoie true si cette couleur n'est pas initialisée ; sinon, false.
### isEquals(Color obj1, Color obj2) {#isEquals-com.aspose.psd.Color-com.aspose.psd.Color-}
```
public static boolean isEquals(Color obj1, Color obj2)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj1 | [Color](../../com.aspose.psd/color) |  |
| obj2 | [Color](../../com.aspose.psd/color) |  |

**Returns:**
booléen
### isKnownColor() {#isKnownColor--}
```
public boolean isKnownColor()
```


Obtient une valeur indiquant si cette  com.aspose.psd.Color  structure est une couleur prédéfinie. Les couleurs prédéfinies sont représentées par les éléments de l'énumération  Aspose.Imaging.KnownColor .

**Returns:**
boolean - True si cette  com.aspose.psd.Color  a été créée à partir d'une couleur prédéfinie en utilisant soit la méthode  Aspose.Imaging.Color.FromName(String) , soit la méthode  Aspose.Imaging.Color.FromKnownColor(Aspose.Imaging.KnownColor) ; sinon, false.
### isNamedColor() {#isNamedColor--}
```
public boolean isNamedColor()
```


Obtient une valeur indiquant si cette  com.aspose.psd.Color  structure est une couleur nommée ou un membre de l'énumération  Aspose.Imaging.KnownColor  .

**Returns:**
boolean - True si cette  com.aspose.psd.Color  a été créée en utilisant soit la méthode  Aspose.Imaging.Color.FromName(String) , soit la méthode  Aspose.Imaging.Color.FromKnownColor(Aspose.Imaging.KnownColor) ; sinon, false.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### op_Equality(Color left, Color right) {#op-Equality-com.aspose.psd.Color-com.aspose.psd.Color-}
```
public static boolean op_Equality(Color left, Color right)
```


Teste si deux structures  com.aspose.psd.Color  spécifiées sont équivalentes.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| left | [Color](../../com.aspose.psd/color) | Le  com.aspose.psd.Color  qui se trouve à gauche de l'opérateur d'égalité. |
| right | [Color](../../com.aspose.psd/color) | Le  com.aspose.psd.Color  qui se trouve à droite de l'opérateur d'égalité. |

**Returns:**
boolean - True si les deux structures  com.aspose.psd.Color  sont égales ; sinon, false.
### op_Inequality(Color left, Color right) {#op-Inequality-com.aspose.psd.Color-com.aspose.psd.Color-}
```
public static boolean op_Inequality(Color left, Color right)
```


Teste si deux structures  com.aspose.psd.Color  spécifiées sont différentes.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| left | [Color](../../com.aspose.psd/color) | Le  com.aspose.psd.Color  qui se trouve à gauche de l'opérateur d'inégalité. |
| right | [Color](../../com.aspose.psd/color) | Le  com.aspose.psd.Color  qui se trouve à droite de l'opérateur d'inégalité. |

**Returns:**
boolean - True si les deux structures  com.aspose.psd.Color  sont différentes ; sinon, false.
### toArgb() {#toArgb--}
```
public int toArgb()
```


Obtient la valeur ARGB 32 bits de cette  com.aspose.psd.Color  structure.

**Returns:**
int - La valeur ARGB 32 bits de ce  com.aspose.psd.Color .
### toCmyk(Color pixel) {#toCmyk-com.aspose.psd.Color-}
```
public static CmykColor toCmyk(Color pixel)
```


La conversion de Color vers CmykColor. Cette méthode est obsolète. Veuillez utiliser la méthode plus efficace  CmykColorHelper.toCmyk(Color) .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.psd/color) | Le pixel de type Color au format RGB. |

**Returns:**
[CmykColor](../../com.aspose.psd/cmykcolor) - The  CmykColor .
### toCmyk(Color[] pixels) {#toCmyk-com.aspose.psd.Color---}
```
public static CmykColor[] toCmyk(Color[] pixels)
```


La conversion de Color vers CMYKColor. Cette méthode est obsolète. Veuillez utiliser la méthode plus efficace  CmykColorHelper.toCmyk(Color[]) .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.psd/color) | Les pixels de type Color au format RGB. |

**Returns:**
com.aspose.psd.CmykColor[] - Le  Aspose:Imaging:CmykColor[] .
### toCmykIcc(Color pixel) {#toCmykIcc-com.aspose.psd.Color-}
```
public static CmykColor toCmykIcc(Color pixel)
```


La conversion de Color vers CMYKColor en utilisant la conversion icc avec les profils par défaut. Cette méthode est obsolète. Veuillez utiliser la méthode plus efficace  CmykColorHelper.toCmykIcc(Color) .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.psd/color) | Le pixel de type Color au format RGB. |

**Returns:**
[CmykColor](../../com.aspose.psd/cmykcolor) - The  CmykColor .
### toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIcc-com.aspose.psd.Color-java.io.InputStream-java.io.InputStream-}
```
public static CmykColor toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream)
```


La conversion de Color vers CMYKColor en utilisant la conversion icc avec les profils par défaut. Cette méthode est obsolète. Veuillez utiliser la méthode plus efficace  CmykColorHelper.toCmykIcc(Color, InputStream, InputStream) .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.psd/color) | Le pixel de type Color au format RGB. |
| rgbIccStream | java.io.InputStream | Le flux contenant le profil icc rgb. |
| cmykIccStream | java.io.InputStream | Le flux contenant le profil icc cmyk. |

**Returns:**
[CmykColor](../../com.aspose.psd/cmykcolor) - The  CmykColor[] .
### toCmykIcc(Color[] pixels) {#toCmykIcc-com.aspose.psd.Color---}
```
public static CmykColor[] toCmykIcc(Color[] pixels)
```


La conversion de Color vers CMYKColor en utilisant la conversion icc avec les profils par défaut. Cette méthode est obsolète. Veuillez utiliser la méthode plus efficace  CmykColorHelper.toCmykIcc(Color[]) .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.psd/color) | Les pixels de type Color au format RGB. |

**Returns:**
com.aspose.psd.CmykColor[] - Le  CmykColor[] .
### toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIcc-com.aspose.psd.Color---java.io.InputStream-java.io.InputStream-}
```
public static CmykColor[] toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)
```


La conversion de Color vers CMYKColor en utilisant la conversion icc. Cette méthode est obsolète. Veuillez utiliser la méthode plus efficace  CmykColorHelper.toCmykIcc(Color[], InputStream, InputStream) .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.psd/color) | Les pixels de type Color au format RGB. |
| rgbIccStream | java.io.InputStream | Le flux contenant le profil icc rgb. |
| cmykIccStream | java.io.InputStream | Le flux contenant le profil icc cmyk. |

**Returns:**
com.aspose.psd.CmykColor[] - Le  CmykColor[] .
### toCmykIcc_internalized(Color pixel, System.IO.Stream rgbIccStream, System.IO.Stream cmykIccStream) {#toCmykIcc-internalized-com.aspose.psd.Color-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-}
```
public static CmykColor toCmykIcc_internalized(Color pixel, System.IO.Stream rgbIccStream, System.IO.Stream cmykIccStream)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.psd/color) |  |
| rgbIccStream | com.aspose.ms.System.IO.Stream |  |
| cmykIccStream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
[CmykColor](../../com.aspose.psd/cmykcolor)
### toCmykIcc_internalized(Color[] pixels, System.IO.Stream rgbIccStream, System.IO.Stream cmykIccStream) {#toCmykIcc-internalized-com.aspose.psd.Color---com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-}
```
public static CmykColor[] toCmykIcc_internalized(Color[] pixels, System.IO.Stream rgbIccStream, System.IO.Stream cmykIccStream)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.psd/color) |  |
| rgbIccStream | com.aspose.ms.System.IO.Stream |  |
| cmykIccStream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
com.aspose.psd.CmykColor[]
### toKnownColor() {#toKnownColor--}
```
public int toKnownColor()
```


Obtient la valeur  Aspose.Imaging.KnownColor  de cette  com.aspose.psd.Color  structure.

**Returns:**
int - Un élément de l'énumération  Aspose.Imaging.KnownColor , si le  com.aspose.psd.Color  est créé à partir d'une couleur prédéfinie en utilisant soit la méthode  Aspose.Imaging.Color.FromName(String) , soit la méthode  Aspose.Imaging.Color.FromKnownColor(Aspose.Imaging.KnownColor) ; sinon, 0.
### toString() {#toString--}
```
public String toString()
```


Convertit cette  com.aspose.psd.Color  structure en une chaîne lisible par l'homme.

**Returns:**
java.lang.String - Une chaîne qui est le nom de ce  com.aspose.psd.Color , si le  com.aspose.psd.Color  est créé à partir d'une couleur prédéfinie en utilisant soit la méthode  Aspose.Imaging.Color.FromName(String)  soit la méthode  Aspose.Imaging.Color.FromKnownColor(Aspose.Imaging.KnownColor) ; sinon, une chaîne qui consiste en les noms des composants ARGB et leurs valeurs.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

