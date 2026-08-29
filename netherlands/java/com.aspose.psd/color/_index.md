---
title: "Color"
second_title: "Aspose.PSD voor Java API-referentie"
description: "De kleur van de pixel."
type: docs
weight: 19
url: /nl/java/com.aspose.psd/color/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class Color extends Struct<Color>
```

De kleur van de pixel.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [Color()](#Color--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(Color that)](#CloneTo-com.aspose.psd.Color-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Test of het opgegeven object een com.aspose.psd.Color‑structuur is en gelijk is aan deze com.aspose.psd.Color‑structuur. |
| [fromArgb(byte red, byte green, byte blue)](#fromArgb-byte-byte-byte-) | Maakt een com.aspose.psd.Color‑structuur aan op basis van de opgegeven 8‑bit kleurniveaus (rood, groen en blauw). |
| [fromArgb(byte alpha, byte red, byte green, byte blue)](#fromArgb-byte-byte-byte-byte-) | Maakt een com.aspose.psd.Color‑structuur aan op basis van de vier ARGB‑componenten (alpha, rood, groen en blauw). |
| [fromArgb(int argb)](#fromArgb-int-) | Maakt een  com.aspose.psd.Color  structuur aan vanuit een 32-bits ARGB-waarde. |
| [fromArgb(int alpha, Color baseColor)](#fromArgb-int-com.aspose.psd.Color-) | Maakt een  com.aspose.psd.Color  structuur aan vanuit de opgegeven  com.aspose.psd.Color  structuur, maar met de nieuw opgegeven alfa-waarde. |
| [fromArgb(int red, int green, int blue)](#fromArgb-int-int-int-) | Maakt een com.aspose.psd.Color‑structuur aan op basis van de opgegeven 8‑bit kleurniveaus (rood, groen en blauw). |
| [fromArgb(int alpha, int red, int green, int blue)](#fromArgb-int-int-int-int-) | Maakt een com.aspose.psd.Color‑structuur aan op basis van de vier ARGB‑componenten (alpha, rood, groen en blauw). |
| [fromKnownColor(int color)](#fromKnownColor-int-) | Maakt een  com.aspose.psd.Color  structuur aan vanuit de opgegeven vooraf gedefinieerde kleur. |
| [fromName(String name)](#fromName-java.lang.String-) | Maakt een  com.aspose.psd.Color  structuur aan vanuit de opgegeven naam van een vooraf gedefinieerde kleur. |
| [getA()](#getA--) | Haalt de alfa‑componentwaarde op van deze  com.aspose.psd.Color  structuur. |
| [getAliceBlue()](#getAliceBlue--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getAntiqueWhite()](#getAntiqueWhite--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getAqua()](#getAqua--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getAquamarine()](#getAquamarine--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getAzure()](#getAzure--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getB()](#getB--) | Haalt de blauwe componentwaarde op van deze  com.aspose.psd.Color  structuur. |
| [getBeige()](#getBeige--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getBisque()](#getBisque--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getBlack()](#getBlack--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getBlanchedAlmond()](#getBlanchedAlmond--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getBlue()](#getBlue--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getBlueViolet()](#getBlueViolet--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getBrightness()](#getBrightness--) | Haalt de helderheidswaarde van hue‑saturation‑brightness (HSB) op voor deze  com.aspose.psd.Color  structuur. |
| [getBrown()](#getBrown--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getBurlyWood()](#getBurlyWood--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getCadetBlue()](#getCadetBlue--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getChartreuse()](#getChartreuse--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getChocolate()](#getChocolate--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getClass()](#getClass--) |  |
| [getCoral()](#getCoral--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getCornflowerBlue()](#getCornflowerBlue--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getCornsilk()](#getCornsilk--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getCrimson()](#getCrimson--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getCyan()](#getCyan--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getDarkBlue()](#getDarkBlue--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getDarkCyan()](#getDarkCyan--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getDarkGoldenrod()](#getDarkGoldenrod--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getDarkGray()](#getDarkGray--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getDarkGreen()](#getDarkGreen--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getDarkKhaki()](#getDarkKhaki--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getDarkMagenta()](#getDarkMagenta--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getDarkOliveGreen()](#getDarkOliveGreen--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getDarkOrange()](#getDarkOrange--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getDarkOrchid()](#getDarkOrchid--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getDarkRed()](#getDarkRed--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getDarkSalmon()](#getDarkSalmon--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getDarkSeaGreen()](#getDarkSeaGreen--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getDarkSlateBlue()](#getDarkSlateBlue--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getDarkSlateGray()](#getDarkSlateGray--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getDarkTurquoise()](#getDarkTurquoise--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getDarkViolet()](#getDarkViolet--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getDeepPink()](#getDeepPink--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getDeepSkyBlue()](#getDeepSkyBlue--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getDimGray()](#getDimGray--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getDodgerBlue()](#getDodgerBlue--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getEmpty()](#getEmpty--) | Haalt een lege  Color  op. |
| [getFirebrick()](#getFirebrick--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getFloralWhite()](#getFloralWhite--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getForestGreen()](#getForestGreen--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getFuchsia()](#getFuchsia--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getG()](#getG--) | Haalt de groene componentwaarde op van deze  com.aspose.psd.Color  structuur. |
| [getGainsboro()](#getGainsboro--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getGhostWhite()](#getGhostWhite--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getGold()](#getGold--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getGoldenrod()](#getGoldenrod--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getGray()](#getGray--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getGreen()](#getGreen--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getGreenYellow()](#getGreenYellow--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getHoneydew()](#getHoneydew--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getHotPink()](#getHotPink--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getHue()](#getHue--) | Haalt de hue‑saturation‑brightness (HSB) tintwaarde, in graden, op voor deze  com.aspose.psd.Color  structuur. |
| [getIndianRed()](#getIndianRed--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getIndigo()](#getIndigo--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getIvory()](#getIvory--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getKhaki()](#getKhaki--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getLavender()](#getLavender--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getLavenderBlush()](#getLavenderBlush--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getLawnGreen()](#getLawnGreen--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getLemonChiffon()](#getLemonChiffon--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getLightBlue()](#getLightBlue--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getLightCoral()](#getLightCoral--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getLightCyan()](#getLightCyan--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getLightGoldenrodYellow()](#getLightGoldenrodYellow--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getLightGray()](#getLightGray--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getLightGreen()](#getLightGreen--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getLightPink()](#getLightPink--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getLightSalmon()](#getLightSalmon--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getLightSeaGreen()](#getLightSeaGreen--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getLightSkyBlue()](#getLightSkyBlue--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getLightSlateGray()](#getLightSlateGray--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getLightSteelBlue()](#getLightSteelBlue--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getLightYellow()](#getLightYellow--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getLime()](#getLime--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getLimeGreen()](#getLimeGreen--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getLinen()](#getLinen--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getMagenta()](#getMagenta--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getMaroon()](#getMaroon--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getMediumAquamarine()](#getMediumAquamarine--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getMediumBlue()](#getMediumBlue--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getMediumOrchid()](#getMediumOrchid--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getMediumPurple()](#getMediumPurple--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getMediumSeaGreen()](#getMediumSeaGreen--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getMediumSlateBlue()](#getMediumSlateBlue--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getMediumSpringGreen()](#getMediumSpringGreen--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getMediumTurquoise()](#getMediumTurquoise--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getMediumVioletRed()](#getMediumVioletRed--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getMidnightBlue()](#getMidnightBlue--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getMintCream()](#getMintCream--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getMistyRose()](#getMistyRose--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getMoccasin()](#getMoccasin--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getName()](#getName--) | Haalt de naam op van deze  com.aspose.psd.Color . |
| [getNavajoWhite()](#getNavajoWhite--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getNavy()](#getNavy--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getOldLace()](#getOldLace--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getOlive()](#getOlive--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getOliveDrab()](#getOliveDrab--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getOrange()](#getOrange--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getOrangeRed()](#getOrangeRed--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getOrchid()](#getOrchid--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getPaleGoldenrod()](#getPaleGoldenrod--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getPaleGreen()](#getPaleGreen--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getPaleTurquoise()](#getPaleTurquoise--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getPaleVioletRed()](#getPaleVioletRed--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getPapayaWhip()](#getPapayaWhip--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getPeachPuff()](#getPeachPuff--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getPeru()](#getPeru--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getPink()](#getPink--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getPlum()](#getPlum--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getPowderBlue()](#getPowderBlue--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getPurple()](#getPurple--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getR()](#getR--) | Haalt de rode componentwaarde op van deze  com.aspose.psd.Color  structuur. |
| [getRed()](#getRed--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getRosyBrown()](#getRosyBrown--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getRoyalBlue()](#getRoyalBlue--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getSaddleBrown()](#getSaddleBrown--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getSalmon()](#getSalmon--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getSandyBrown()](#getSandyBrown--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getSaturation()](#getSaturation--) | Haalt de verzadigingswaarde van hue‑saturation‑brightness (HSB) op voor deze  com.aspose.psd.Color  structuur. |
| [getSeaGreen()](#getSeaGreen--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getSeaShell()](#getSeaShell--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getSienna()](#getSienna--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getSilver()](#getSilver--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getSkyBlue()](#getSkyBlue--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getSlateBlue()](#getSlateBlue--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getSlateGray()](#getSlateGray--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getSnow()](#getSnow--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getSpringGreen()](#getSpringGreen--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getSteelBlue()](#getSteelBlue--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getTan()](#getTan--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getTeal()](#getTeal--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getThistle()](#getThistle--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getTomato()](#getTomato--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getTransparent()](#getTransparent--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getTurquoise()](#getTurquoise--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getViolet()](#getViolet--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getWheat()](#getWheat--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getWhite()](#getWhite--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getWhiteSmoke()](#getWhiteSmoke--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getYellow()](#getYellow--) | Haalt een systeem‑gedefinieerde kleur op. |
| [getYellowGreen()](#getYellowGreen--) | Haalt een systeem‑gedefinieerde kleur op. |
| [hashCode()](#hashCode--) | Retourneert een hash‑code voor deze  com.aspose.psd.Color  structuur. |
| [isEmpty()](#isEmpty--) | Haalt een waarde op die aangeeft of deze  com.aspose.psd.Color  structuur niet is geïnitialiseerd. |
| [isEquals(Color obj1, Color obj2)](#isEquals-com.aspose.psd.Color-com.aspose.psd.Color-) |  |
| [isKnownColor()](#isKnownColor--) | Haalt een waarde op die aangeeft of deze  com.aspose.psd.Color  structuur een vooraf gedefinieerde kleur is. |
| [isNamedColor()](#isNamedColor--) | Haalt een waarde op die aangeeft of deze  com.aspose.psd.Color  structuur een benoemde kleur is of een lid van de  Aspose.Imaging.KnownColor  enumeratie. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Equality(Color left, Color right)](#op-Equality-com.aspose.psd.Color-com.aspose.psd.Color-) | Test of twee opgegeven  com.aspose.psd.Color  structuren equivalent zijn. |
| [op_Inequality(Color left, Color right)](#op-Inequality-com.aspose.psd.Color-com.aspose.psd.Color-) | Test of twee opgegeven  com.aspose.psd.Color  structuren verschillend zijn. |
| [toArgb()](#toArgb--) | Haalt de 32-bits ARGB-waarde op van deze  com.aspose.psd.Color  structuur. |
| [toCmyk(Color pixel)](#toCmyk-com.aspose.psd.Color-) | De conversie van Color naar CmykColor. |
| [toCmyk(Color[] pixels)](#toCmyk-com.aspose.psd.Color---) | De conversie van Color naar CMYKColor. |
| [toCmykIcc(Color pixel)](#toCmykIcc-com.aspose.psd.Color-) | De conversie van Color naar CMYKColor met icc-conversie en standaardprofielen. |
| [toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIcc-com.aspose.psd.Color-java.io.InputStream-java.io.InputStream-) | De conversie van Color naar CMYKColor met icc-conversie en standaardprofielen. |
| [toCmykIcc(Color[] pixels)](#toCmykIcc-com.aspose.psd.Color---) | De conversie van Color naar CMYKColor met icc-conversie en standaardprofielen. |
| [toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIcc-com.aspose.psd.Color---java.io.InputStream-java.io.InputStream-) | De conversie van Color naar CMYKColor met icc-conversie. |
| [toCmykIcc_internalized(Color pixel, System.IO.Stream rgbIccStream, System.IO.Stream cmykIccStream)](#toCmykIcc-internalized-com.aspose.psd.Color-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-) |  |
| [toCmykIcc_internalized(Color[] pixels, System.IO.Stream rgbIccStream, System.IO.Stream cmykIccStream)](#toCmykIcc-internalized-com.aspose.psd.Color---com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-) |  |
| [toKnownColor()](#toKnownColor--) | Haalt de  Aspose.Imaging.KnownColor  waarde op van deze  com.aspose.psd.Color  structuur. |
| [toString()](#toString--) | Converteert deze  com.aspose.psd.Color  structuur naar een menselijk leesbare tekenreeks. |
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(Color that) {#CloneTo-com.aspose.psd.Color-}
```
public void CloneTo(Color that)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| that | [Color](../../com.aspose.psd/color) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Test of het opgegeven object een com.aspose.psd.Color‑structuur is en gelijk is aan deze com.aspose.psd.Color‑structuur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | java.lang.Object | Het object om te testen. |

**Returns:**
boolean - Waar als  obj  een  com.aspose.psd.Color  structuur is die gelijk is aan deze  com.aspose.psd.Color  structuur; anders, onwaar.
### fromArgb(byte red, byte green, byte blue) {#fromArgb-byte-byte-byte-}
```
public static Color fromArgb(byte red, byte green, byte blue)
```


Maakt een  com.aspose.psd.Color  structuur aan op basis van de opgegeven 8-bit kleurwaarden (rood, groen en blauw). De alpha‑waarde is impliciet 255 (volledig ondoorzichtig). Hoewel deze methode een 32-bit waarde toestaat voor elk kleurcomponent, is de waarde van elk component beperkt tot 8 bits.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rood | byte | De rode componentwaarde voor de nieuwe  com.aspose.psd.Color . Geldige waarden zijn 0 tot en met 255. |
| groen | byte | De groene componentwaarde voor de nieuwe  com.aspose.psd.Color . Geldige waarden zijn 0 tot en met 255. |
| blauw | byte | De blauwe componentwaarde voor de nieuwe  com.aspose.psd.Color . Geldige waarden zijn 0 tot en met 255. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  com.aspose.psd.Color  that this method creates.
### fromArgb(byte alpha, byte red, byte green, byte blue) {#fromArgb-byte-byte-byte-byte-}
```
public static Color fromArgb(byte alpha, byte red, byte green, byte blue)
```


Maakt een  com.aspose.psd.Color  structuur aan op basis van de vier ARGB component (alpha, rood, groen en blauw) waarden. Hoewel deze methode een 32-bit waarde toestaat voor elk component, is de waarde van elk component beperkt tot 8 bits.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| alpha | byte | De alpha‑component. Geldige waarden zijn 0 tot en met 255. |
| rood | byte | De rode component. Geldige waarden zijn 0 tot en met 255. |
| groen | byte | De groene component. Geldige waarden zijn 0 tot en met 255. |
| blauw | byte | De blauwe component. Geldige waarden zijn 0 tot en met 255. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  com.aspose.psd.Color  that this method creates.
### fromArgb(int argb) {#fromArgb-int-}
```
public static Color fromArgb(int argb)
```


Maakt een  com.aspose.psd.Color  structuur aan vanuit een 32-bits ARGB-waarde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| argb | int | Een waarde die de 32-bit ARGB‑waarde specificeert. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  com.aspose.psd.Color  structure that this method creates.
### fromArgb(int alpha, Color baseColor) {#fromArgb-int-com.aspose.psd.Color-}
```
public static Color fromArgb(int alpha, Color baseColor)
```


Maakt een  com.aspose.psd.Color  structuur aan op basis van de opgegeven  com.aspose.psd.Color  structuur, maar met de nieuw opgegeven alpha‑waarde. Hoewel deze methode een 32-bit waarde toestaat voor de alpha‑waarde, is de waarde beperkt tot 8 bits.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| alpha | int | De alpha‑waarde voor de nieuwe  com.aspose.psd.Color . Geldige waarden zijn 0 tot en met 255. |
| baseColor | [Color](../../com.aspose.psd/color) | De  com.aspose.psd.Color  waaruit de nieuwe  com.aspose.psd.Color  moet worden gemaakt. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  com.aspose.psd.Color  that this method creates.
### fromArgb(int red, int green, int blue) {#fromArgb-int-int-int-}
```
public static Color fromArgb(int red, int green, int blue)
```


Maakt een  com.aspose.psd.Color  structuur aan op basis van de opgegeven 8-bit kleurwaarden (rood, groen en blauw). De alpha‑waarde is impliciet 255 (volledig ondoorzichtig). Hoewel deze methode een 32-bit waarde toestaat voor elk kleurcomponent, is de waarde van elk component beperkt tot 8 bits.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rood | int | De rode componentwaarde voor de nieuwe  com.aspose.psd.Color . Geldige waarden zijn 0 tot en met 255. |
| groen | int | De groene componentwaarde voor de nieuwe  com.aspose.psd.Color . Geldige waarden zijn 0 tot en met 255. |
| blauw | int | De blauwe componentwaarde voor de nieuwe  com.aspose.psd.Color . Geldige waarden zijn 0 tot en met 255. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  com.aspose.psd.Color  that this method creates.
### fromArgb(int alpha, int red, int green, int blue) {#fromArgb-int-int-int-int-}
```
public static Color fromArgb(int alpha, int red, int green, int blue)
```


Maakt een  com.aspose.psd.Color  structuur aan op basis van de vier ARGB component (alpha, rood, groen en blauw) waarden. Hoewel deze methode een 32-bit waarde toestaat voor elk component, is de waarde van elk component beperkt tot 8 bits.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| alpha | int | De alpha‑component. Geldige waarden zijn 0 tot en met 255. |
| rood | int | De rode component. Geldige waarden zijn 0 tot en met 255. |
| groen | int | De groene component. Geldige waarden zijn 0 tot en met 255. |
| blauw | int | De blauwe component. Geldige waarden zijn 0 tot en met 255. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  com.aspose.psd.Color  that this method creates.
### fromKnownColor(int color) {#fromKnownColor-int-}
```
public static Color fromKnownColor(int color)
```


Maakt een  com.aspose.psd.Color  structuur aan vanuit de opgegeven vooraf gedefinieerde kleur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| kleur | int | Een element van de  Aspose.Imaging.KnownColor  enumeratie. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  com.aspose.psd.Color  that this method creates.
### fromName(String name) {#fromName-java.lang.String-}
```
public static Color fromName(String name)
```


Maakt een  com.aspose.psd.Color  structuur aan vanuit de opgegeven naam van een vooraf gedefinieerde kleur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| naam | java.lang.String | Een tekenreeks die de naam is van een vooraf gedefinieerde kleur. Geldige namen zijn dezelfde als de namen van de elementen van de  Aspose.Imaging.KnownColor  enumeratie. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  com.aspose.psd.Color  that this method creates.
### getA() {#getA--}
```
public byte getA()
```


Haalt de alfa‑componentwaarde op van deze  com.aspose.psd.Color  structuur.

**Returns:**
byte - De alpha‑componentwaarde van deze  com.aspose.psd.Color .
### getAliceBlue() {#getAliceBlue--}
```
public static Color getAliceBlue()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getAntiqueWhite() {#getAntiqueWhite--}
```
public static Color getAntiqueWhite()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getAqua() {#getAqua--}
```
public static Color getAqua()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getAquamarine() {#getAquamarine--}
```
public static Color getAquamarine()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getAzure() {#getAzure--}
```
public static Color getAzure()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getB() {#getB--}
```
public byte getB()
```


Haalt de blauwe componentwaarde op van deze  com.aspose.psd.Color  structuur.

**Returns:**
byte - De blauwe componentwaarde van deze  com.aspose.psd.Color .
### getBeige() {#getBeige--}
```
public static Color getBeige()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getBisque() {#getBisque--}
```
public static Color getBisque()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getBlack() {#getBlack--}
```
public static Color getBlack()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getBlanchedAlmond() {#getBlanchedAlmond--}
```
public static Color getBlanchedAlmond()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getBlue() {#getBlue--}
```
public static Color getBlue()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getBlueViolet() {#getBlueViolet--}
```
public static Color getBlueViolet()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getBrightness() {#getBrightness--}
```
public float getBrightness()
```


Haalt de helderheidswaarde van hue‑saturation‑brightness (HSB) op voor deze  com.aspose.psd.Color  structuur.

**Returns:**
float - De helderheid van deze  com.aspose.psd.Color . De helderheid varieert van 0.0 tot en met 1.0, waarbij 0.0 zwart vertegenwoordigt en 1.0 wit.
### getBrown() {#getBrown--}
```
public static Color getBrown()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getBurlyWood() {#getBurlyWood--}
```
public static Color getBurlyWood()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getCadetBlue() {#getCadetBlue--}
```
public static Color getCadetBlue()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getChartreuse() {#getChartreuse--}
```
public static Color getChartreuse()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getChocolate() {#getChocolate--}
```
public static Color getChocolate()
```


Haalt een systeem‑gedefinieerde kleur op.

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


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getCornflowerBlue() {#getCornflowerBlue--}
```
public static Color getCornflowerBlue()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getCornsilk() {#getCornsilk--}
```
public static Color getCornsilk()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getCrimson() {#getCrimson--}
```
public static Color getCrimson()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getCyan() {#getCyan--}
```
public static Color getCyan()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkBlue() {#getDarkBlue--}
```
public static Color getDarkBlue()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkCyan() {#getDarkCyan--}
```
public static Color getDarkCyan()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkGoldenrod() {#getDarkGoldenrod--}
```
public static Color getDarkGoldenrod()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkGray() {#getDarkGray--}
```
public static Color getDarkGray()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkGreen() {#getDarkGreen--}
```
public static Color getDarkGreen()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkKhaki() {#getDarkKhaki--}
```
public static Color getDarkKhaki()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkMagenta() {#getDarkMagenta--}
```
public static Color getDarkMagenta()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkOliveGreen() {#getDarkOliveGreen--}
```
public static Color getDarkOliveGreen()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkOrange() {#getDarkOrange--}
```
public static Color getDarkOrange()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkOrchid() {#getDarkOrchid--}
```
public static Color getDarkOrchid()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkRed() {#getDarkRed--}
```
public static Color getDarkRed()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkSalmon() {#getDarkSalmon--}
```
public static Color getDarkSalmon()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkSeaGreen() {#getDarkSeaGreen--}
```
public static Color getDarkSeaGreen()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkSlateBlue() {#getDarkSlateBlue--}
```
public static Color getDarkSlateBlue()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkSlateGray() {#getDarkSlateGray--}
```
public static Color getDarkSlateGray()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkTurquoise() {#getDarkTurquoise--}
```
public static Color getDarkTurquoise()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkViolet() {#getDarkViolet--}
```
public static Color getDarkViolet()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDeepPink() {#getDeepPink--}
```
public static Color getDeepPink()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDeepSkyBlue() {#getDeepSkyBlue--}
```
public static Color getDeepSkyBlue()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDimGray() {#getDimGray--}
```
public static Color getDimGray()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDodgerBlue() {#getDodgerBlue--}
```
public static Color getDodgerBlue()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getEmpty() {#getEmpty--}
```
public static Color getEmpty()
```


Haalt een lege  Color  op.

**Returns:**
[Color](../../com.aspose.psd/color) - The empty  Color .
### getFirebrick() {#getFirebrick--}
```
public static Color getFirebrick()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getFloralWhite() {#getFloralWhite--}
```
public static Color getFloralWhite()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getForestGreen() {#getForestGreen--}
```
public static Color getForestGreen()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getFuchsia() {#getFuchsia--}
```
public static Color getFuchsia()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getG() {#getG--}
```
public byte getG()
```


Haalt de groene componentwaarde op van deze  com.aspose.psd.Color  structuur.

**Returns:**
byte - De groene componentwaarde van deze com.aspose.psd.Color.
### getGainsboro() {#getGainsboro--}
```
public static Color getGainsboro()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getGhostWhite() {#getGhostWhite--}
```
public static Color getGhostWhite()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getGold() {#getGold--}
```
public static Color getGold()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getGoldenrod() {#getGoldenrod--}
```
public static Color getGoldenrod()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getGray() {#getGray--}
```
public static Color getGray()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  structure representing a system-defined color.
### getGreen() {#getGreen--}
```
public static Color getGreen()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getGreenYellow() {#getGreenYellow--}
```
public static Color getGreenYellow()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getHoneydew() {#getHoneydew--}
```
public static Color getHoneydew()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getHotPink() {#getHotPink--}
```
public static Color getHotPink()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getHue() {#getHue--}
```
public float getHue()
```


Haalt de hue‑saturation‑brightness (HSB) tintwaarde, in graden, op voor deze  com.aspose.psd.Color  structuur.

**Returns:**
float - De tint, in graden, van deze com.aspose.psd.Color. De tint wordt gemeten in graden, variërend van 0.0 tot 360.0, in de HSB-kleurruimte.
### getIndianRed() {#getIndianRed--}
```
public static Color getIndianRed()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getIndigo() {#getIndigo--}
```
public static Color getIndigo()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getIvory() {#getIvory--}
```
public static Color getIvory()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getKhaki() {#getKhaki--}
```
public static Color getKhaki()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLavender() {#getLavender--}
```
public static Color getLavender()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLavenderBlush() {#getLavenderBlush--}
```
public static Color getLavenderBlush()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLawnGreen() {#getLawnGreen--}
```
public static Color getLawnGreen()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLemonChiffon() {#getLemonChiffon--}
```
public static Color getLemonChiffon()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightBlue() {#getLightBlue--}
```
public static Color getLightBlue()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightCoral() {#getLightCoral--}
```
public static Color getLightCoral()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightCyan() {#getLightCyan--}
```
public static Color getLightCyan()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightGoldenrodYellow() {#getLightGoldenrodYellow--}
```
public static Color getLightGoldenrodYellow()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightGray() {#getLightGray--}
```
public static Color getLightGray()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightGreen() {#getLightGreen--}
```
public static Color getLightGreen()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightPink() {#getLightPink--}
```
public static Color getLightPink()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightSalmon() {#getLightSalmon--}
```
public static Color getLightSalmon()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightSeaGreen() {#getLightSeaGreen--}
```
public static Color getLightSeaGreen()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightSkyBlue() {#getLightSkyBlue--}
```
public static Color getLightSkyBlue()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightSlateGray() {#getLightSlateGray--}
```
public static Color getLightSlateGray()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightSteelBlue() {#getLightSteelBlue--}
```
public static Color getLightSteelBlue()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightYellow() {#getLightYellow--}
```
public static Color getLightYellow()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLime() {#getLime--}
```
public static Color getLime()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLimeGreen() {#getLimeGreen--}
```
public static Color getLimeGreen()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLinen() {#getLinen--}
```
public static Color getLinen()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMagenta() {#getMagenta--}
```
public static Color getMagenta()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMaroon() {#getMaroon--}
```
public static Color getMaroon()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMediumAquamarine() {#getMediumAquamarine--}
```
public static Color getMediumAquamarine()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMediumBlue() {#getMediumBlue--}
```
public static Color getMediumBlue()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMediumOrchid() {#getMediumOrchid--}
```
public static Color getMediumOrchid()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMediumPurple() {#getMediumPurple--}
```
public static Color getMediumPurple()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMediumSeaGreen() {#getMediumSeaGreen--}
```
public static Color getMediumSeaGreen()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMediumSlateBlue() {#getMediumSlateBlue--}
```
public static Color getMediumSlateBlue()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMediumSpringGreen() {#getMediumSpringGreen--}
```
public static Color getMediumSpringGreen()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMediumTurquoise() {#getMediumTurquoise--}
```
public static Color getMediumTurquoise()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMediumVioletRed() {#getMediumVioletRed--}
```
public static Color getMediumVioletRed()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMidnightBlue() {#getMidnightBlue--}
```
public static Color getMidnightBlue()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMintCream() {#getMintCream--}
```
public static Color getMintCream()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMistyRose() {#getMistyRose--}
```
public static Color getMistyRose()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMoccasin() {#getMoccasin--}
```
public static Color getMoccasin()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getName() {#getName--}
```
public String getName()
```


Haalt de naam op van deze  com.aspose.psd.Color .

**Returns:**
java.lang.String - De naam van deze com.aspose.psd.Color.
### getNavajoWhite() {#getNavajoWhite--}
```
public static Color getNavajoWhite()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getNavy() {#getNavy--}
```
public static Color getNavy()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getOldLace() {#getOldLace--}
```
public static Color getOldLace()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getOlive() {#getOlive--}
```
public static Color getOlive()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getOliveDrab() {#getOliveDrab--}
```
public static Color getOliveDrab()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getOrange() {#getOrange--}
```
public static Color getOrange()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getOrangeRed() {#getOrangeRed--}
```
public static Color getOrangeRed()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getOrchid() {#getOrchid--}
```
public static Color getOrchid()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPaleGoldenrod() {#getPaleGoldenrod--}
```
public static Color getPaleGoldenrod()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPaleGreen() {#getPaleGreen--}
```
public static Color getPaleGreen()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPaleTurquoise() {#getPaleTurquoise--}
```
public static Color getPaleTurquoise()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPaleVioletRed() {#getPaleVioletRed--}
```
public static Color getPaleVioletRed()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPapayaWhip() {#getPapayaWhip--}
```
public static Color getPapayaWhip()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPeachPuff() {#getPeachPuff--}
```
public static Color getPeachPuff()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPeru() {#getPeru--}
```
public static Color getPeru()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPink() {#getPink--}
```
public static Color getPink()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPlum() {#getPlum--}
```
public static Color getPlum()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPowderBlue() {#getPowderBlue--}
```
public static Color getPowderBlue()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPurple() {#getPurple--}
```
public static Color getPurple()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getR() {#getR--}
```
public byte getR()
```


Haalt de rode componentwaarde op van deze  com.aspose.psd.Color  structuur.

**Returns:**
byte - De rode componentwaarde van deze com.aspose.psd.Color.
### getRed() {#getRed--}
```
public static Color getRed()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getRosyBrown() {#getRosyBrown--}
```
public static Color getRosyBrown()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getRoyalBlue() {#getRoyalBlue--}
```
public static Color getRoyalBlue()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSaddleBrown() {#getSaddleBrown--}
```
public static Color getSaddleBrown()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSalmon() {#getSalmon--}
```
public static Color getSalmon()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSandyBrown() {#getSandyBrown--}
```
public static Color getSandyBrown()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSaturation() {#getSaturation--}
```
public float getSaturation()
```


Haalt de verzadigingswaarde van hue‑saturation‑brightness (HSB) op voor deze  com.aspose.psd.Color  structuur.

**Returns:**
float - De verzadiging van deze com.aspose.psd.Color. De verzadiging varieert van 0.0 tot 1.0, waarbij 0.0 grijswaarden is en 1.0 de meest verzadigde.
### getSeaGreen() {#getSeaGreen--}
```
public static Color getSeaGreen()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSeaShell() {#getSeaShell--}
```
public static Color getSeaShell()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSienna() {#getSienna--}
```
public static Color getSienna()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSilver() {#getSilver--}
```
public static Color getSilver()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSkyBlue() {#getSkyBlue--}
```
public static Color getSkyBlue()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSlateBlue() {#getSlateBlue--}
```
public static Color getSlateBlue()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSlateGray() {#getSlateGray--}
```
public static Color getSlateGray()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSnow() {#getSnow--}
```
public static Color getSnow()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSpringGreen() {#getSpringGreen--}
```
public static Color getSpringGreen()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSteelBlue() {#getSteelBlue--}
```
public static Color getSteelBlue()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getTan() {#getTan--}
```
public static Color getTan()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getTeal() {#getTeal--}
```
public static Color getTeal()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getThistle() {#getThistle--}
```
public static Color getThistle()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getTomato() {#getTomato--}
```
public static Color getTomato()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getTransparent() {#getTransparent--}
```
public static Color getTransparent()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getTurquoise() {#getTurquoise--}
```
public static Color getTurquoise()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getViolet() {#getViolet--}
```
public static Color getViolet()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getWheat() {#getWheat--}
```
public static Color getWheat()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getWhite() {#getWhite--}
```
public static Color getWhite()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getWhiteSmoke() {#getWhiteSmoke--}
```
public static Color getWhiteSmoke()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getYellow() {#getYellow--}
```
public static Color getYellow()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getYellowGreen() {#getYellowGreen--}
```
public static Color getYellowGreen()
```


Haalt een systeem‑gedefinieerde kleur op.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Retourneert een hash‑code voor deze  com.aspose.psd.Color  structuur.

**Returns:**
int - Een geheel getal dat de hashcode voor deze com.aspose.psd.Color specificeert.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Haalt een waarde op die aangeeft of deze  com.aspose.psd.Color  structuur niet is geïnitialiseerd.

**Returns:**
boolean - Deze eigenschap retourneert true als deze kleur niet is geïnitialiseerd; anders false.
### isEquals(Color obj1, Color obj2) {#isEquals-com.aspose.psd.Color-com.aspose.psd.Color-}
```
public static boolean isEquals(Color obj1, Color obj2)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj1 | [Color](../../com.aspose.psd/color) |  |
| obj2 | [Color](../../com.aspose.psd/color) |  |

**Returns:**
boolean
### isKnownColor() {#isKnownColor--}
```
public boolean isKnownColor()
```


Haalt een waarde op die aangeeft of deze com.aspose.psd.Color-structuur een vooraf gedefinieerde kleur is. Vooraf gedefinieerde kleuren worden weergegeven door de elementen van de Aspose.Imaging.KnownColor-enumeratie.

**Returns:**
boolean - True als deze com.aspose.psd.Color is gemaakt van een vooraf gedefinieerde kleur door gebruik te maken van de Aspose.Imaging.Color.FromName(String)-methode of de Aspose.Imaging.Color.FromKnownColor(Aspose.Imaging.KnownColor)-methode; anders false.
### isNamedColor() {#isNamedColor--}
```
public boolean isNamedColor()
```


Haalt een waarde op die aangeeft of deze  com.aspose.psd.Color  structuur een benoemde kleur is of een lid van de  Aspose.Imaging.KnownColor  enumeratie.

**Returns:**
boolean - True als deze com.aspose.psd.Color is gemaakt door gebruik te maken van de Aspose.Imaging.Color.FromName(String)-methode of de Aspose.Imaging.Color.FromKnownColor(Aspose.Imaging.KnownColor)-methode; anders false.
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


Test of twee opgegeven  com.aspose.psd.Color  structuren equivalent zijn.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| left | [Color](../../com.aspose.psd/color) | De com.aspose.psd.Color die zich links van de gelijkheidsoperator bevindt. |
| right | [Color](../../com.aspose.psd/color) | De com.aspose.psd.Color die zich rechts van de gelijkheidsoperator bevindt. |

**Returns:**
boolean - True als de twee com.aspose.psd.Color-structuren gelijk zijn; anders false.
### op_Inequality(Color left, Color right) {#op-Inequality-com.aspose.psd.Color-com.aspose.psd.Color-}
```
public static boolean op_Inequality(Color left, Color right)
```


Test of twee opgegeven  com.aspose.psd.Color  structuren verschillend zijn.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| left | [Color](../../com.aspose.psd/color) | De com.aspose.psd.Color die zich links van de ongelijkheidsoperator bevindt. |
| right | [Color](../../com.aspose.psd/color) | De com.aspose.psd.Color die zich rechts van de ongelijkheidsoperator bevindt. |

**Returns:**
boolean - True als de twee com.aspose.psd.Color-structuren verschillend zijn; anders false.
### toArgb() {#toArgb--}
```
public int toArgb()
```


Haalt de 32-bits ARGB-waarde op van deze  com.aspose.psd.Color  structuur.

**Returns:**
int - De 32-bit ARGB-waarde van deze com.aspose.psd.Color.
### toCmyk(Color pixel) {#toCmyk-com.aspose.psd.Color-}
```
public static CmykColor toCmyk(Color pixel)
```


De conversie van Color naar CmykColor. Deze methode is verouderd. Gebruik a.u.b. de effectievere CmykColorHelper.toCmyk(Color).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.psd/color) | De pixel van het type Color in RGB-indeling. |

**Returns:**
[CmykColor](../../com.aspose.psd/cmykcolor) - The  CmykColor .
### toCmyk(Color[] pixels) {#toCmyk-com.aspose.psd.Color---}
```
public static CmykColor[] toCmyk(Color[] pixels)
```


De conversie van Color naar CMYKColor. Deze methode is verouderd. Gebruik a.u.b. de effectievere CmykColorHelper.toCmyk(Color[]).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.psd/color) | De pixels van het type Color in RGB-indeling. |

**Returns:**
com.aspose.psd.CmykColor[] - De Aspose:Imaging:CmykColor[].
### toCmykIcc(Color pixel) {#toCmykIcc-com.aspose.psd.Color-}
```
public static CmykColor toCmykIcc(Color pixel)
```


De conversie van Color naar CMYKColor met icc-conversie en standaardprofielen. Deze methode is verouderd. Gebruik a.u.b. de effectievere CmykColorHelper.toCmykIcc(Color).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.psd/color) | De pixel van het type Color in RGB-indeling. |

**Returns:**
[CmykColor](../../com.aspose.psd/cmykcolor) - The  CmykColor .
### toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIcc-com.aspose.psd.Color-java.io.InputStream-java.io.InputStream-}
```
public static CmykColor toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream)
```


De conversie van Color naar CMYKColor met icc-conversie en standaardprofielen. Deze methode is verouderd. Gebruik a.u.b. de effectievere CmykColorHelper.toCmykIcc(Color, InputStream, InputStream).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.psd/color) | De pixel van het type Color in RGB-indeling. |
| rgbIccStream | java.io.InputStream | De stream die het icc rgb-profiel bevat. |
| cmykIccStream | java.io.InputStream | De stream die een icc cmyk-profiel bevat. |

**Returns:**
[CmykColor](../../com.aspose.psd/cmykcolor) - The  CmykColor[] .
### toCmykIcc(Color[] pixels) {#toCmykIcc-com.aspose.psd.Color---}
```
public static CmykColor[] toCmykIcc(Color[] pixels)
```


De conversie van Color naar CMYKColor met behulp van icc-conversie met standaardprofielen. Deze methode is verouderd. Gebruik een effectievere  CmykColorHelper.toCmykIcc(Color[]) .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.psd/color) | De pixels van het type Color in RGB-indeling. |

**Returns:**
com.aspose.psd.CmykColor[] - De  CmykColor[] .
### toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIcc-com.aspose.psd.Color---java.io.InputStream-java.io.InputStream-}
```
public static CmykColor[] toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)
```


De conversie van Color naar CMYKColor met behulp van icc-conversie. Deze methode is verouderd. Gebruik een effectievere  CmykColorHelper.toCmykIcc(Color[], InputStream, InputStream) .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.psd/color) | De pixels van het type Color in RGB-indeling. |
| rgbIccStream | java.io.InputStream | De stream die het icc rgb-profiel bevat. |
| cmykIccStream | java.io.InputStream | De stream die een icc cmyk-profiel bevat. |

**Returns:**
com.aspose.psd.CmykColor[] - De  CmykColor[] .
### toCmykIcc_internalized(Color pixel, System.IO.Stream rgbIccStream, System.IO.Stream cmykIccStream) {#toCmykIcc-internalized-com.aspose.psd.Color-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-}
```
public static CmykColor toCmykIcc_internalized(Color pixel, System.IO.Stream rgbIccStream, System.IO.Stream cmykIccStream)
```




**Parameters:**
| Parameter | Type | Beschrijving |
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
| Parameter | Type | Beschrijving |
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


Haalt de  Aspose.Imaging.KnownColor  waarde op van deze  com.aspose.psd.Color  structuur.

**Returns:**
int - Een element van de  Aspose.Imaging.KnownColor  enumeratie, als de  com.aspose.psd.Color  is gemaakt van een vooraf gedefinieerde kleur door gebruik te maken van de  Aspose.Imaging.Color.FromName(String)  methode of de  Aspose.Imaging.Color.FromKnownColor(Aspose.Imaging.KnownColor)  methode; anders, 0.
### toString() {#toString--}
```
public String toString()
```


Converteert deze  com.aspose.psd.Color  structuur naar een menselijk leesbare tekenreeks.

**Returns:**
java.lang.String - Een string die de naam is van deze  com.aspose.psd.Color , als de  com.aspose.psd.Color  is gemaakt van een vooraf gedefinieerde kleur door gebruik te maken van de  Aspose.Imaging.Color.FromName(String)  methode of de  Aspose.Imaging.Color.FromKnownColor(Aspose.Imaging.KnownColor)  methode; anders, een string die bestaat uit de namen van de ARGB-componenten en hun waarden.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

