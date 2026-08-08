---
title: "Färg"
second_title: "Aspose.PSD för Java API-referens"
description: "Färgen på pixeln."
type: docs
weight: 19
url: /sv/java/com.aspose.psd/color/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class Color extends Struct<Color>
```

Färgen på pixeln.
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [Color()](#Color--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(Color that)](#CloneTo-com.aspose.psd.Color-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Testar om det angivna objektet är en  com.aspose.psd.Color  struktur och är ekvivalent med denna  com.aspose.psd.Color  struktur. |
| [fromArgb(byte red, byte green, byte blue)](#fromArgb-byte-byte-byte-) | Skapar en  com.aspose.psd.Color  struktur från de angivna 8-bitars färgvärdena (röd, grön och blå). |
| [fromArgb(byte alpha, byte red, byte green, byte blue)](#fromArgb-byte-byte-byte-byte-) | Skapar en  com.aspose.psd.Color  struktur från de fyra ARGB-komponenterna (alpha, röd, grön och blå) värdena. |
| [fromArgb(int argb)](#fromArgb-int-) | Skapar en  com.aspose.psd.Color  struktur från ett 32-bitars ARGB‑värde. |
| [fromArgb(int alpha, Color baseColor)](#fromArgb-int-com.aspose.psd.Color-) | Skapar en  com.aspose.psd.Color  struktur från den angivna  com.aspose.psd.Color  strukturen, men med det nya angivna alfavärdet. |
| [fromArgb(int red, int green, int blue)](#fromArgb-int-int-int-) | Skapar en  com.aspose.psd.Color  struktur från de angivna 8-bitars färgvärdena (röd, grön och blå). |
| [fromArgb(int alpha, int red, int green, int blue)](#fromArgb-int-int-int-int-) | Skapar en  com.aspose.psd.Color  struktur från de fyra ARGB-komponenterna (alpha, röd, grön och blå) värdena. |
| [fromKnownColor(int color)](#fromKnownColor-int-) | Skapar en  com.aspose.psd.Color  struktur från den angivna fördefinierade färgen. |
| [fromName(String name)](#fromName-java.lang.String-) | Skapar en  com.aspose.psd.Color  struktur från det angivna namnet på en fördefinierad färg. |
| [getA()](#getA--) | Hämtar alfakomponentens värde för denna  com.aspose.psd.Color  struktur. |
| [getAliceBlue()](#getAliceBlue--) | Hämtar en systemdefinierad färg. |
| [getAntiqueWhite()](#getAntiqueWhite--) | Hämtar en systemdefinierad färg. |
| [getAqua()](#getAqua--) | Hämtar en systemdefinierad färg. |
| [getAquamarine()](#getAquamarine--) | Hämtar en systemdefinierad färg. |
| [getAzure()](#getAzure--) | Hämtar en systemdefinierad färg. |
| [getB()](#getB--) | Hämtar blåkomponentens värde för denna  com.aspose.psd.Color  struktur. |
| [getBeige()](#getBeige--) | Hämtar en systemdefinierad färg. |
| [getBisque()](#getBisque--) | Hämtar en systemdefinierad färg. |
| [getBlack()](#getBlack--) | Hämtar en systemdefinierad färg. |
| [getBlanchedAlmond()](#getBlanchedAlmond--) | Hämtar en systemdefinierad färg. |
| [getBlue()](#getBlue--) | Hämtar en systemdefinierad färg. |
| [getBlueViolet()](#getBlueViolet--) | Hämtar en systemdefinierad färg. |
| [getBrightness()](#getBrightness--) | Hämtar ljusstyrkevärdet för nyans‑mättnad‑ljusstyrka (HSB) för denna  com.aspose.psd.Color  struktur. |
| [getBrown()](#getBrown--) | Hämtar en systemdefinierad färg. |
| [getBurlyWood()](#getBurlyWood--) | Hämtar en systemdefinierad färg. |
| [getCadetBlue()](#getCadetBlue--) | Hämtar en systemdefinierad färg. |
| [getChartreuse()](#getChartreuse--) | Hämtar en systemdefinierad färg. |
| [getChocolate()](#getChocolate--) | Hämtar en systemdefinierad färg. |
| [getClass()](#getClass--) |  |
| [getCoral()](#getCoral--) | Hämtar en systemdefinierad färg. |
| [getCornflowerBlue()](#getCornflowerBlue--) | Hämtar en systemdefinierad färg. |
| [getCornsilk()](#getCornsilk--) | Hämtar en systemdefinierad färg. |
| [getCrimson()](#getCrimson--) | Hämtar en systemdefinierad färg. |
| [getCyan()](#getCyan--) | Hämtar en systemdefinierad färg. |
| [getDarkBlue()](#getDarkBlue--) | Hämtar en systemdefinierad färg. |
| [getDarkCyan()](#getDarkCyan--) | Hämtar en systemdefinierad färg. |
| [getDarkGoldenrod()](#getDarkGoldenrod--) | Hämtar en systemdefinierad färg. |
| [getDarkGray()](#getDarkGray--) | Hämtar en systemdefinierad färg. |
| [getDarkGreen()](#getDarkGreen--) | Hämtar en systemdefinierad färg. |
| [getDarkKhaki()](#getDarkKhaki--) | Hämtar en systemdefinierad färg. |
| [getDarkMagenta()](#getDarkMagenta--) | Hämtar en systemdefinierad färg. |
| [getDarkOliveGreen()](#getDarkOliveGreen--) | Hämtar en systemdefinierad färg. |
| [getDarkOrange()](#getDarkOrange--) | Hämtar en systemdefinierad färg. |
| [getDarkOrchid()](#getDarkOrchid--) | Hämtar en systemdefinierad färg. |
| [getDarkRed()](#getDarkRed--) | Hämtar en systemdefinierad färg. |
| [getDarkSalmon()](#getDarkSalmon--) | Hämtar en systemdefinierad färg. |
| [getDarkSeaGreen()](#getDarkSeaGreen--) | Hämtar en systemdefinierad färg. |
| [getDarkSlateBlue()](#getDarkSlateBlue--) | Hämtar en systemdefinierad färg. |
| [getDarkSlateGray()](#getDarkSlateGray--) | Hämtar en systemdefinierad färg. |
| [getDarkTurquoise()](#getDarkTurquoise--) | Hämtar en systemdefinierad färg. |
| [getDarkViolet()](#getDarkViolet--) | Hämtar en systemdefinierad färg. |
| [getDeepPink()](#getDeepPink--) | Hämtar en systemdefinierad färg. |
| [getDeepSkyBlue()](#getDeepSkyBlue--) | Hämtar en systemdefinierad färg. |
| [getDimGray()](#getDimGray--) | Hämtar en systemdefinierad färg. |
| [getDodgerBlue()](#getDodgerBlue--) | Hämtar en systemdefinierad färg. |
| [getEmpty()](#getEmpty--) | Hämtar en tom  Color . |
| [getFirebrick()](#getFirebrick--) | Hämtar en systemdefinierad färg. |
| [getFloralWhite()](#getFloralWhite--) | Hämtar en systemdefinierad färg. |
| [getForestGreen()](#getForestGreen--) | Hämtar en systemdefinierad färg. |
| [getFuchsia()](#getFuchsia--) | Hämtar en systemdefinierad färg. |
| [getG()](#getG--) | Hämtar den gröna komponentens värde för denna  com.aspose.psd.Color  struktur. |
| [getGainsboro()](#getGainsboro--) | Hämtar en systemdefinierad färg. |
| [getGhostWhite()](#getGhostWhite--) | Hämtar en systemdefinierad färg. |
| [getGold()](#getGold--) | Hämtar en systemdefinierad färg. |
| [getGoldenrod()](#getGoldenrod--) | Hämtar en systemdefinierad färg. |
| [getGray()](#getGray--) | Hämtar en systemdefinierad färg. |
| [getGreen()](#getGreen--) | Hämtar en systemdefinierad färg. |
| [getGreenYellow()](#getGreenYellow--) | Hämtar en systemdefinierad färg. |
| [getHoneydew()](#getHoneydew--) | Hämtar en systemdefinierad färg. |
| [getHotPink()](#getHotPink--) | Hämtar en systemdefinierad färg. |
| [getHue()](#getHue--) | Hämtar nyansvärdet för nyans‑mättnad‑ljusstyrka (HSB), i grader, för denna  com.aspose.psd.Color  struktur. |
| [getIndianRed()](#getIndianRed--) | Hämtar en systemdefinierad färg. |
| [getIndigo()](#getIndigo--) | Hämtar en systemdefinierad färg. |
| [getIvory()](#getIvory--) | Hämtar en systemdefinierad färg. |
| [getKhaki()](#getKhaki--) | Hämtar en systemdefinierad färg. |
| [getLavender()](#getLavender--) | Hämtar en systemdefinierad färg. |
| [getLavenderBlush()](#getLavenderBlush--) | Hämtar en systemdefinierad färg. |
| [getLawnGreen()](#getLawnGreen--) | Hämtar en systemdefinierad färg. |
| [getLemonChiffon()](#getLemonChiffon--) | Hämtar en systemdefinierad färg. |
| [getLightBlue()](#getLightBlue--) | Hämtar en systemdefinierad färg. |
| [getLightCoral()](#getLightCoral--) | Hämtar en systemdefinierad färg. |
| [getLightCyan()](#getLightCyan--) | Hämtar en systemdefinierad färg. |
| [getLightGoldenrodYellow()](#getLightGoldenrodYellow--) | Hämtar en systemdefinierad färg. |
| [getLightGray()](#getLightGray--) | Hämtar en systemdefinierad färg. |
| [getLightGreen()](#getLightGreen--) | Hämtar en systemdefinierad färg. |
| [getLightPink()](#getLightPink--) | Hämtar en systemdefinierad färg. |
| [getLightSalmon()](#getLightSalmon--) | Hämtar en systemdefinierad färg. |
| [getLightSeaGreen()](#getLightSeaGreen--) | Hämtar en systemdefinierad färg. |
| [getLightSkyBlue()](#getLightSkyBlue--) | Hämtar en systemdefinierad färg. |
| [getLightSlateGray()](#getLightSlateGray--) | Hämtar en systemdefinierad färg. |
| [getLightSteelBlue()](#getLightSteelBlue--) | Hämtar en systemdefinierad färg. |
| [getLightYellow()](#getLightYellow--) | Hämtar en systemdefinierad färg. |
| [getLime()](#getLime--) | Hämtar en systemdefinierad färg. |
| [getLimeGreen()](#getLimeGreen--) | Hämtar en systemdefinierad färg. |
| [getLinen()](#getLinen--) | Hämtar en systemdefinierad färg. |
| [getMagenta()](#getMagenta--) | Hämtar en systemdefinierad färg. |
| [getMaroon()](#getMaroon--) | Hämtar en systemdefinierad färg. |
| [getMediumAquamarine()](#getMediumAquamarine--) | Hämtar en systemdefinierad färg. |
| [getMediumBlue()](#getMediumBlue--) | Hämtar en systemdefinierad färg. |
| [getMediumOrchid()](#getMediumOrchid--) | Hämtar en systemdefinierad färg. |
| [getMediumPurple()](#getMediumPurple--) | Hämtar en systemdefinierad färg. |
| [getMediumSeaGreen()](#getMediumSeaGreen--) | Hämtar en systemdefinierad färg. |
| [getMediumSlateBlue()](#getMediumSlateBlue--) | Hämtar en systemdefinierad färg. |
| [getMediumSpringGreen()](#getMediumSpringGreen--) | Hämtar en systemdefinierad färg. |
| [getMediumTurquoise()](#getMediumTurquoise--) | Hämtar en systemdefinierad färg. |
| [getMediumVioletRed()](#getMediumVioletRed--) | Hämtar en systemdefinierad färg. |
| [getMidnightBlue()](#getMidnightBlue--) | Hämtar en systemdefinierad färg. |
| [getMintCream()](#getMintCream--) | Hämtar en systemdefinierad färg. |
| [getMistyRose()](#getMistyRose--) | Hämtar en systemdefinierad färg. |
| [getMoccasin()](#getMoccasin--) | Hämtar en systemdefinierad färg. |
| [getName()](#getName--) | Hämtar namnet på denna  com.aspose.psd.Color . |
| [getNavajoWhite()](#getNavajoWhite--) | Hämtar en systemdefinierad färg. |
| [getNavy()](#getNavy--) | Hämtar en systemdefinierad färg. |
| [getOldLace()](#getOldLace--) | Hämtar en systemdefinierad färg. |
| [getOlive()](#getOlive--) | Hämtar en systemdefinierad färg. |
| [getOliveDrab()](#getOliveDrab--) | Hämtar en systemdefinierad färg. |
| [getOrange()](#getOrange--) | Hämtar en systemdefinierad färg. |
| [getOrangeRed()](#getOrangeRed--) | Hämtar en systemdefinierad färg. |
| [getOrchid()](#getOrchid--) | Hämtar en systemdefinierad färg. |
| [getPaleGoldenrod()](#getPaleGoldenrod--) | Hämtar en systemdefinierad färg. |
| [getPaleGreen()](#getPaleGreen--) | Hämtar en systemdefinierad färg. |
| [getPaleTurquoise()](#getPaleTurquoise--) | Hämtar en systemdefinierad färg. |
| [getPaleVioletRed()](#getPaleVioletRed--) | Hämtar en systemdefinierad färg. |
| [getPapayaWhip()](#getPapayaWhip--) | Hämtar en systemdefinierad färg. |
| [getPeachPuff()](#getPeachPuff--) | Hämtar en systemdefinierad färg. |
| [getPeru()](#getPeru--) | Hämtar en systemdefinierad färg. |
| [getPink()](#getPink--) | Hämtar en systemdefinierad färg. |
| [getPlum()](#getPlum--) | Hämtar en systemdefinierad färg. |
| [getPowderBlue()](#getPowderBlue--) | Hämtar en systemdefinierad färg. |
| [getPurple()](#getPurple--) | Hämtar en systemdefinierad färg. |
| [getR()](#getR--) | Hämtar den röda komponentens värde för denna  com.aspose.psd.Color  struktur. |
| [getRed()](#getRed--) | Hämtar en systemdefinierad färg. |
| [getRosyBrown()](#getRosyBrown--) | Hämtar en systemdefinierad färg. |
| [getRoyalBlue()](#getRoyalBlue--) | Hämtar en systemdefinierad färg. |
| [getSaddleBrown()](#getSaddleBrown--) | Hämtar en systemdefinierad färg. |
| [getSalmon()](#getSalmon--) | Hämtar en systemdefinierad färg. |
| [getSandyBrown()](#getSandyBrown--) | Hämtar en systemdefinierad färg. |
| [getSaturation()](#getSaturation--) | Hämtar mättnadsvärdet för nyans‑mättnad‑ljusstyrka (HSB) för denna  com.aspose.psd.Color  struktur. |
| [getSeaGreen()](#getSeaGreen--) | Hämtar en systemdefinierad färg. |
| [getSeaShell()](#getSeaShell--) | Hämtar en systemdefinierad färg. |
| [getSienna()](#getSienna--) | Hämtar en systemdefinierad färg. |
| [getSilver()](#getSilver--) | Hämtar en systemdefinierad färg. |
| [getSkyBlue()](#getSkyBlue--) | Hämtar en systemdefinierad färg. |
| [getSlateBlue()](#getSlateBlue--) | Hämtar en systemdefinierad färg. |
| [getSlateGray()](#getSlateGray--) | Hämtar en systemdefinierad färg. |
| [getSnow()](#getSnow--) | Hämtar en systemdefinierad färg. |
| [getSpringGreen()](#getSpringGreen--) | Hämtar en systemdefinierad färg. |
| [getSteelBlue()](#getSteelBlue--) | Hämtar en systemdefinierad färg. |
| [getTan()](#getTan--) | Hämtar en systemdefinierad färg. |
| [getTeal()](#getTeal--) | Hämtar en systemdefinierad färg. |
| [getThistle()](#getThistle--) | Hämtar en systemdefinierad färg. |
| [getTomato()](#getTomato--) | Hämtar en systemdefinierad färg. |
| [getTransparent()](#getTransparent--) | Hämtar en systemdefinierad färg. |
| [getTurquoise()](#getTurquoise--) | Hämtar en systemdefinierad färg. |
| [getViolet()](#getViolet--) | Hämtar en systemdefinierad färg. |
| [getWheat()](#getWheat--) | Hämtar en systemdefinierad färg. |
| [getWhite()](#getWhite--) | Hämtar en systemdefinierad färg. |
| [getWhiteSmoke()](#getWhiteSmoke--) | Hämtar en systemdefinierad färg. |
| [getYellow()](#getYellow--) | Hämtar en systemdefinierad färg. |
| [getYellowGreen()](#getYellowGreen--) | Hämtar en systemdefinierad färg. |
| [hashCode()](#hashCode--) | Returnerar en hashkod för denna  com.aspose.psd.Color  struktur. |
| [isEmpty()](#isEmpty--) | Hämtar ett värde som indikerar om denna  com.aspose.psd.Color  struktur är oinitierad. |
| [isEquals(Color obj1, Color obj2)](#isEquals-com.aspose.psd.Color-com.aspose.psd.Color-) |  |
| [isKnownColor()](#isKnownColor--) | Hämtar ett värde som indikerar om denna  com.aspose.psd.Color  struktur är en fördefinierad färg. |
| [isNamedColor()](#isNamedColor--) | Hämtar ett värde som indikerar om denna  com.aspose.psd.Color  struktur är en namngiven färg eller en medlem av  Aspose.Imaging.KnownColor ‑enumerationen. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Equality(Color left, Color right)](#op-Equality-com.aspose.psd.Color-com.aspose.psd.Color-) | Testar om två angivna  com.aspose.psd.Color  strukturer är ekvivalenta. |
| [op_Inequality(Color left, Color right)](#op-Inequality-com.aspose.psd.Color-com.aspose.psd.Color-) | Testar om två angivna  com.aspose.psd.Color  strukturer är olika. |
| [toArgb()](#toArgb--) | Hämtar det 32-bitars ARGB‑värdet för denna  com.aspose.psd.Color  struktur. |
| [toCmyk(Color pixel)](#toCmyk-com.aspose.psd.Color-) | Konverteringen från Color till CmykColor. |
| [toCmyk(Color[] pixels)](#toCmyk-com.aspose.psd.Color---) | Konverteringen från Color till CMYKColor. |
| [toCmykIcc(Color pixel)](#toCmykIcc-com.aspose.psd.Color-) | Konverteringen från Color till CMYKColor med icc‑konvertering och standardprofiler. |
| [toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIcc-com.aspose.psd.Color-java.io.InputStream-java.io.InputStream-) | Konverteringen från Color till CMYKColor med icc‑konvertering och standardprofiler. |
| [toCmykIcc(Color[] pixels)](#toCmykIcc-com.aspose.psd.Color---) | Konverteringen från Color till CMYKColor med icc‑konvertering och standardprofiler. |
| [toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIcc-com.aspose.psd.Color---java.io.InputStream-java.io.InputStream-) | Konverteringen från Color till CMYKColor med icc-konvertering. |
| [toCmykIcc_internalized(Color pixel, System.IO.Stream rgbIccStream, System.IO.Stream cmykIccStream)](#toCmykIcc-internalized-com.aspose.psd.Color-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-) |  |
| [toCmykIcc_internalized(Color[] pixels, System.IO.Stream rgbIccStream, System.IO.Stream cmykIccStream)](#toCmykIcc-internalized-com.aspose.psd.Color---com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-) |  |
| [toKnownColor()](#toKnownColor--) | Hämtar  Aspose.Imaging.KnownColor  värdet för denna  com.aspose.psd.Color  struktur. |
| [toString()](#toString--) | Konverterar denna  com.aspose.psd.Color  struktur till en människoläsbar sträng. |
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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(Color that) {#CloneTo-com.aspose.psd.Color-}
```
public void CloneTo(Color that)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| that | [Color](../../com.aspose.psd/color) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Testar om det angivna objektet är en  com.aspose.psd.Color  struktur och är ekvivalent med denna  com.aspose.psd.Color  struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | Objektet att testa. |

**Returns:**
boolean - Sant om  obj  är en  com.aspose.psd.Color  struktur som är ekvivalent med denna  com.aspose.psd.Color  struktur; annars falskt.
### fromArgb(byte red, byte green, byte blue) {#fromArgb-byte-byte-byte-}
```
public static Color fromArgb(byte red, byte green, byte blue)
```


Skapar en  com.aspose.psd.Color  struktur från de angivna 8-bitars färgvärdena (röd, grön och blå). Alfa‑värdet är implicit 255 (fullt ogenomskinligt). Även om denna metod tillåter ett 32-bitars värde att skickas för varje färgkomponent, är värdet för varje komponent begränsat till 8 bitar.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| röd | byte | Rödkomponentens värde för den nya  com.aspose.psd.Color . Giltiga värden är 0 till 255. |
| grön | byte | Grönkomponentens värde för den nya  com.aspose.psd.Color . Giltiga värden är 0 till 255. |
| blå | byte | Blåkomponentens värde för den nya  com.aspose.psd.Color . Giltiga värden är 0 till 255. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  com.aspose.psd.Color  that this method creates.
### fromArgb(byte alpha, byte red, byte green, byte blue) {#fromArgb-byte-byte-byte-byte-}
```
public static Color fromArgb(byte alpha, byte red, byte green, byte blue)
```


Skapar en  com.aspose.psd.Color  struktur från de fyra ARGB‑komponenterna (alfa, röd, grön och blå). Även om denna metod tillåter ett 32-bitars värde att skickas för varje komponent, är värdet för varje komponent begränsat till 8 bitar.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| alfa | byte | Alfakomponenten. Giltiga värden är 0 till 255. |
| röd | byte | Rödkomponenten. Giltiga värden är 0 till 255. |
| grön | byte | Grönkomponenten. Giltiga värden är 0 till 255. |
| blå | byte | Blåkomponenten. Giltiga värden är 0 till 255. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  com.aspose.psd.Color  that this method creates.
### fromArgb(int argb) {#fromArgb-int-}
```
public static Color fromArgb(int argb)
```


Skapar en  com.aspose.psd.Color  struktur från ett 32-bitars ARGB‑värde.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| argb | int | Ett värde som specificerar 32-bitars ARGB‑värdet. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  com.aspose.psd.Color  structure that this method creates.
### fromArgb(int alpha, Color baseColor) {#fromArgb-int-com.aspose.psd.Color-}
```
public static Color fromArgb(int alpha, Color baseColor)
```


Skapar en  com.aspose.psd.Color  struktur från den angivna  com.aspose.psd.Color  strukturen, men med det nya angivna alfa‑värdet. Även om denna metod tillåter ett 32-bitars värde att skickas för alfa‑värdet, är värdet begränsat till 8 bitar.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| alfa | int | Alfa‑värdet för den nya  com.aspose.psd.Color . Giltiga värden är 0 till 255. |
| baseColor | [Color](../../com.aspose.psd/color) | Den  com.aspose.psd.Color  som den nya  com.aspose.psd.Color  ska skapas från. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  com.aspose.psd.Color  that this method creates.
### fromArgb(int red, int green, int blue) {#fromArgb-int-int-int-}
```
public static Color fromArgb(int red, int green, int blue)
```


Skapar en  com.aspose.psd.Color  struktur från de angivna 8-bitars färgvärdena (röd, grön och blå). Alfa‑värdet är implicit 255 (fullt ogenomskinligt). Även om denna metod tillåter ett 32-bitars värde att skickas för varje färgkomponent, är värdet för varje komponent begränsat till 8 bitar.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| röd | int | Rödkomponentens värde för den nya  com.aspose.psd.Color . Giltiga värden är 0 till 255. |
| grön | int | Grönkomponentens värde för den nya  com.aspose.psd.Color . Giltiga värden är 0 till 255. |
| blå | int | Blåkomponentens värde för den nya  com.aspose.psd.Color . Giltiga värden är 0 till 255. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  com.aspose.psd.Color  that this method creates.
### fromArgb(int alpha, int red, int green, int blue) {#fromArgb-int-int-int-int-}
```
public static Color fromArgb(int alpha, int red, int green, int blue)
```


Skapar en  com.aspose.psd.Color  struktur från de fyra ARGB‑komponenterna (alfa, röd, grön och blå). Även om denna metod tillåter ett 32-bitars värde att skickas för varje komponent, är värdet för varje komponent begränsat till 8 bitar.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| alfa | int | Alfakomponenten. Giltiga värden är 0 till 255. |
| röd | int | Rödkomponenten. Giltiga värden är 0 till 255. |
| grön | int | Grönkomponenten. Giltiga värden är 0 till 255. |
| blå | int | Blåkomponenten. Giltiga värden är 0 till 255. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  com.aspose.psd.Color  that this method creates.
### fromKnownColor(int color) {#fromKnownColor-int-}
```
public static Color fromKnownColor(int color)
```


Skapar en  com.aspose.psd.Color  struktur från den angivna fördefinierade färgen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| färg | int | Ett element i  Aspose.Imaging.KnownColor ‑enumerationen. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  com.aspose.psd.Color  that this method creates.
### fromName(String name) {#fromName-java.lang.String-}
```
public static Color fromName(String name)
```


Skapar en  com.aspose.psd.Color  struktur från det angivna namnet på en fördefinierad färg.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | java.lang.String | En sträng som är namnet på en fördefinierad färg. Giltiga namn är samma som namnen på elementen i  Aspose.Imaging.KnownColor ‑enumerationen. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  com.aspose.psd.Color  that this method creates.
### getA() {#getA--}
```
public byte getA()
```


Hämtar alfakomponentens värde för denna  com.aspose.psd.Color  struktur.

**Returns:**
byte - Alfakomponentens värde för denna  com.aspose.psd.Color .
### getAliceBlue() {#getAliceBlue--}
```
public static Color getAliceBlue()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getAntiqueWhite() {#getAntiqueWhite--}
```
public static Color getAntiqueWhite()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getAqua() {#getAqua--}
```
public static Color getAqua()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getAquamarine() {#getAquamarine--}
```
public static Color getAquamarine()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getAzure() {#getAzure--}
```
public static Color getAzure()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getB() {#getB--}
```
public byte getB()
```


Hämtar blåkomponentens värde för denna  com.aspose.psd.Color  struktur.

**Returns:**
byte - Blåkomponentens värde för denna  com.aspose.psd.Color .
### getBeige() {#getBeige--}
```
public static Color getBeige()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getBisque() {#getBisque--}
```
public static Color getBisque()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getBlack() {#getBlack--}
```
public static Color getBlack()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getBlanchedAlmond() {#getBlanchedAlmond--}
```
public static Color getBlanchedAlmond()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getBlue() {#getBlue--}
```
public static Color getBlue()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getBlueViolet() {#getBlueViolet--}
```
public static Color getBlueViolet()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getBrightness() {#getBrightness--}
```
public float getBrightness()
```


Hämtar ljusstyrkevärdet för nyans‑mättnad‑ljusstyrka (HSB) för denna  com.aspose.psd.Color  struktur.

**Returns:**
float - Ljusstyrkan för detta com.aspose.psd.Color . Ljusstyrkan varierar från 0.0 till 1.0, där 0.0 representerar svart och 1.0 representerar vitt.
### getBrown() {#getBrown--}
```
public static Color getBrown()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getBurlyWood() {#getBurlyWood--}
```
public static Color getBurlyWood()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getCadetBlue() {#getCadetBlue--}
```
public static Color getCadetBlue()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getChartreuse() {#getChartreuse--}
```
public static Color getChartreuse()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getChocolate() {#getChocolate--}
```
public static Color getChocolate()
```


Hämtar en systemdefinierad färg.

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


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getCornflowerBlue() {#getCornflowerBlue--}
```
public static Color getCornflowerBlue()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getCornsilk() {#getCornsilk--}
```
public static Color getCornsilk()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getCrimson() {#getCrimson--}
```
public static Color getCrimson()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getCyan() {#getCyan--}
```
public static Color getCyan()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkBlue() {#getDarkBlue--}
```
public static Color getDarkBlue()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkCyan() {#getDarkCyan--}
```
public static Color getDarkCyan()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkGoldenrod() {#getDarkGoldenrod--}
```
public static Color getDarkGoldenrod()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkGray() {#getDarkGray--}
```
public static Color getDarkGray()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkGreen() {#getDarkGreen--}
```
public static Color getDarkGreen()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkKhaki() {#getDarkKhaki--}
```
public static Color getDarkKhaki()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkMagenta() {#getDarkMagenta--}
```
public static Color getDarkMagenta()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkOliveGreen() {#getDarkOliveGreen--}
```
public static Color getDarkOliveGreen()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkOrange() {#getDarkOrange--}
```
public static Color getDarkOrange()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkOrchid() {#getDarkOrchid--}
```
public static Color getDarkOrchid()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkRed() {#getDarkRed--}
```
public static Color getDarkRed()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkSalmon() {#getDarkSalmon--}
```
public static Color getDarkSalmon()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkSeaGreen() {#getDarkSeaGreen--}
```
public static Color getDarkSeaGreen()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkSlateBlue() {#getDarkSlateBlue--}
```
public static Color getDarkSlateBlue()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkSlateGray() {#getDarkSlateGray--}
```
public static Color getDarkSlateGray()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkTurquoise() {#getDarkTurquoise--}
```
public static Color getDarkTurquoise()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkViolet() {#getDarkViolet--}
```
public static Color getDarkViolet()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDeepPink() {#getDeepPink--}
```
public static Color getDeepPink()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDeepSkyBlue() {#getDeepSkyBlue--}
```
public static Color getDeepSkyBlue()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDimGray() {#getDimGray--}
```
public static Color getDimGray()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDodgerBlue() {#getDodgerBlue--}
```
public static Color getDodgerBlue()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getEmpty() {#getEmpty--}
```
public static Color getEmpty()
```


Hämtar en tom  Color .

**Returns:**
[Color](../../com.aspose.psd/color) - The empty  Color .
### getFirebrick() {#getFirebrick--}
```
public static Color getFirebrick()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getFloralWhite() {#getFloralWhite--}
```
public static Color getFloralWhite()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getForestGreen() {#getForestGreen--}
```
public static Color getForestGreen()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getFuchsia() {#getFuchsia--}
```
public static Color getFuchsia()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getG() {#getG--}
```
public byte getG()
```


Hämtar den gröna komponentens värde för denna  com.aspose.psd.Color  struktur.

**Returns:**
byte - Det gröna komponentvärdet för detta com.aspose.psd.Color .
### getGainsboro() {#getGainsboro--}
```
public static Color getGainsboro()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getGhostWhite() {#getGhostWhite--}
```
public static Color getGhostWhite()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getGold() {#getGold--}
```
public static Color getGold()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getGoldenrod() {#getGoldenrod--}
```
public static Color getGoldenrod()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getGray() {#getGray--}
```
public static Color getGray()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  structure representing a system-defined color.
### getGreen() {#getGreen--}
```
public static Color getGreen()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getGreenYellow() {#getGreenYellow--}
```
public static Color getGreenYellow()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getHoneydew() {#getHoneydew--}
```
public static Color getHoneydew()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getHotPink() {#getHotPink--}
```
public static Color getHotPink()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getHue() {#getHue--}
```
public float getHue()
```


Hämtar nyansvärdet för nyans‑mättnad‑ljusstyrka (HSB), i grader, för denna  com.aspose.psd.Color  struktur.

**Returns:**
float - Nyansen, i grader, för detta com.aspose.psd.Color . Nyansen mäts i grader och varierar från 0.0 till 360.0 i HSB-färgrymden.
### getIndianRed() {#getIndianRed--}
```
public static Color getIndianRed()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getIndigo() {#getIndigo--}
```
public static Color getIndigo()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getIvory() {#getIvory--}
```
public static Color getIvory()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getKhaki() {#getKhaki--}
```
public static Color getKhaki()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLavender() {#getLavender--}
```
public static Color getLavender()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLavenderBlush() {#getLavenderBlush--}
```
public static Color getLavenderBlush()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLawnGreen() {#getLawnGreen--}
```
public static Color getLawnGreen()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLemonChiffon() {#getLemonChiffon--}
```
public static Color getLemonChiffon()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightBlue() {#getLightBlue--}
```
public static Color getLightBlue()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightCoral() {#getLightCoral--}
```
public static Color getLightCoral()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightCyan() {#getLightCyan--}
```
public static Color getLightCyan()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightGoldenrodYellow() {#getLightGoldenrodYellow--}
```
public static Color getLightGoldenrodYellow()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightGray() {#getLightGray--}
```
public static Color getLightGray()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightGreen() {#getLightGreen--}
```
public static Color getLightGreen()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightPink() {#getLightPink--}
```
public static Color getLightPink()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightSalmon() {#getLightSalmon--}
```
public static Color getLightSalmon()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightSeaGreen() {#getLightSeaGreen--}
```
public static Color getLightSeaGreen()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightSkyBlue() {#getLightSkyBlue--}
```
public static Color getLightSkyBlue()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightSlateGray() {#getLightSlateGray--}
```
public static Color getLightSlateGray()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightSteelBlue() {#getLightSteelBlue--}
```
public static Color getLightSteelBlue()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightYellow() {#getLightYellow--}
```
public static Color getLightYellow()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLime() {#getLime--}
```
public static Color getLime()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLimeGreen() {#getLimeGreen--}
```
public static Color getLimeGreen()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLinen() {#getLinen--}
```
public static Color getLinen()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMagenta() {#getMagenta--}
```
public static Color getMagenta()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMaroon() {#getMaroon--}
```
public static Color getMaroon()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMediumAquamarine() {#getMediumAquamarine--}
```
public static Color getMediumAquamarine()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMediumBlue() {#getMediumBlue--}
```
public static Color getMediumBlue()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMediumOrchid() {#getMediumOrchid--}
```
public static Color getMediumOrchid()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMediumPurple() {#getMediumPurple--}
```
public static Color getMediumPurple()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMediumSeaGreen() {#getMediumSeaGreen--}
```
public static Color getMediumSeaGreen()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMediumSlateBlue() {#getMediumSlateBlue--}
```
public static Color getMediumSlateBlue()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMediumSpringGreen() {#getMediumSpringGreen--}
```
public static Color getMediumSpringGreen()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMediumTurquoise() {#getMediumTurquoise--}
```
public static Color getMediumTurquoise()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMediumVioletRed() {#getMediumVioletRed--}
```
public static Color getMediumVioletRed()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMidnightBlue() {#getMidnightBlue--}
```
public static Color getMidnightBlue()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMintCream() {#getMintCream--}
```
public static Color getMintCream()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMistyRose() {#getMistyRose--}
```
public static Color getMistyRose()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMoccasin() {#getMoccasin--}
```
public static Color getMoccasin()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getName() {#getName--}
```
public String getName()
```


Hämtar namnet på denna  com.aspose.psd.Color .

**Returns:**
java.lang.String - Namnet på detta com.aspose.psd.Color .
### getNavajoWhite() {#getNavajoWhite--}
```
public static Color getNavajoWhite()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getNavy() {#getNavy--}
```
public static Color getNavy()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getOldLace() {#getOldLace--}
```
public static Color getOldLace()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getOlive() {#getOlive--}
```
public static Color getOlive()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getOliveDrab() {#getOliveDrab--}
```
public static Color getOliveDrab()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getOrange() {#getOrange--}
```
public static Color getOrange()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getOrangeRed() {#getOrangeRed--}
```
public static Color getOrangeRed()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getOrchid() {#getOrchid--}
```
public static Color getOrchid()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPaleGoldenrod() {#getPaleGoldenrod--}
```
public static Color getPaleGoldenrod()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPaleGreen() {#getPaleGreen--}
```
public static Color getPaleGreen()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPaleTurquoise() {#getPaleTurquoise--}
```
public static Color getPaleTurquoise()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPaleVioletRed() {#getPaleVioletRed--}
```
public static Color getPaleVioletRed()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPapayaWhip() {#getPapayaWhip--}
```
public static Color getPapayaWhip()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPeachPuff() {#getPeachPuff--}
```
public static Color getPeachPuff()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPeru() {#getPeru--}
```
public static Color getPeru()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPink() {#getPink--}
```
public static Color getPink()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPlum() {#getPlum--}
```
public static Color getPlum()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPowderBlue() {#getPowderBlue--}
```
public static Color getPowderBlue()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPurple() {#getPurple--}
```
public static Color getPurple()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getR() {#getR--}
```
public byte getR()
```


Hämtar den röda komponentens värde för denna  com.aspose.psd.Color  struktur.

**Returns:**
byte - Det röda komponentvärdet för detta com.aspose.psd.Color .
### getRed() {#getRed--}
```
public static Color getRed()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getRosyBrown() {#getRosyBrown--}
```
public static Color getRosyBrown()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getRoyalBlue() {#getRoyalBlue--}
```
public static Color getRoyalBlue()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSaddleBrown() {#getSaddleBrown--}
```
public static Color getSaddleBrown()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSalmon() {#getSalmon--}
```
public static Color getSalmon()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSandyBrown() {#getSandyBrown--}
```
public static Color getSandyBrown()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSaturation() {#getSaturation--}
```
public float getSaturation()
```


Hämtar mättnadsvärdet för nyans‑mättnad‑ljusstyrka (HSB) för denna  com.aspose.psd.Color  struktur.

**Returns:**
float - Mättnaden för detta com.aspose.psd.Color . Mättnaden varierar från 0.0 till 1.0, där 0.0 är gråskala och 1.0 är mest mättad.
### getSeaGreen() {#getSeaGreen--}
```
public static Color getSeaGreen()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSeaShell() {#getSeaShell--}
```
public static Color getSeaShell()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSienna() {#getSienna--}
```
public static Color getSienna()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSilver() {#getSilver--}
```
public static Color getSilver()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSkyBlue() {#getSkyBlue--}
```
public static Color getSkyBlue()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSlateBlue() {#getSlateBlue--}
```
public static Color getSlateBlue()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSlateGray() {#getSlateGray--}
```
public static Color getSlateGray()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSnow() {#getSnow--}
```
public static Color getSnow()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSpringGreen() {#getSpringGreen--}
```
public static Color getSpringGreen()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSteelBlue() {#getSteelBlue--}
```
public static Color getSteelBlue()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getTan() {#getTan--}
```
public static Color getTan()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getTeal() {#getTeal--}
```
public static Color getTeal()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getThistle() {#getThistle--}
```
public static Color getThistle()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getTomato() {#getTomato--}
```
public static Color getTomato()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getTransparent() {#getTransparent--}
```
public static Color getTransparent()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getTurquoise() {#getTurquoise--}
```
public static Color getTurquoise()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getViolet() {#getViolet--}
```
public static Color getViolet()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getWheat() {#getWheat--}
```
public static Color getWheat()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getWhite() {#getWhite--}
```
public static Color getWhite()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getWhiteSmoke() {#getWhiteSmoke--}
```
public static Color getWhiteSmoke()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getYellow() {#getYellow--}
```
public static Color getYellow()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getYellowGreen() {#getYellowGreen--}
```
public static Color getYellowGreen()
```


Hämtar en systemdefinierad färg.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returnerar en hashkod för denna  com.aspose.psd.Color  struktur.

**Returns:**
int - Ett heltalsvärde som specificerar hash‑koden för detta com.aspose.psd.Color .
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Hämtar ett värde som indikerar om denna  com.aspose.psd.Color  struktur är oinitierad.

**Returns:**
boolean - Denna egenskap returnerar true om denna färg är oinitierad; annars false.
### isEquals(Color obj1, Color obj2) {#isEquals-com.aspose.psd.Color-com.aspose.psd.Color-}
```
public static boolean isEquals(Color obj1, Color obj2)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj1 | [Color](../../com.aspose.psd/color) |  |
| obj2 | [Color](../../com.aspose.psd/color) |  |

**Returns:**
boolean
### isKnownColor() {#isKnownColor--}
```
public boolean isKnownColor()
```


Hämtar ett värde som indikerar om denna com.aspose.psd.Color struktur är en fördefinierad färg. Fördefinierade färger representeras av elementen i Aspose.Imaging.KnownColor‑enumerationen.

**Returns:**
boolean - True om denna com.aspose.psd.Color skapades från en fördefinierad färg genom att använda antingen Aspose.Imaging.Color.FromName(String) metoden eller Aspose.Imaging.Color.FromKnownColor(Aspose.Imaging.KnownColor) metoden; annars false.
### isNamedColor() {#isNamedColor--}
```
public boolean isNamedColor()
```


Hämtar ett värde som indikerar om denna  com.aspose.psd.Color  struktur är en namngiven färg eller en medlem av  Aspose.Imaging.KnownColor ‑enumerationen.

**Returns:**
boolean - True om denna com.aspose.psd.Color skapades genom att använda antingen Aspose.Imaging.Color.FromName(String) metoden eller Aspose.Imaging.Color.FromKnownColor(Aspose.Imaging.KnownColor) metoden; annars false.
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


Testar om två angivna  com.aspose.psd.Color  strukturer är ekvivalenta.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| left | [Color](../../com.aspose.psd/color) | Den com.aspose.psd.Color som är till vänster om likhetsoperatorn. |
| right | [Color](../../com.aspose.psd/color) | Den com.aspose.psd.Color som är till höger om likhetsoperatorn. |

**Returns:**
boolean - True om de två com.aspose.psd.Color strukturerna är lika; annars false.
### op_Inequality(Color left, Color right) {#op-Inequality-com.aspose.psd.Color-com.aspose.psd.Color-}
```
public static boolean op_Inequality(Color left, Color right)
```


Testar om två angivna  com.aspose.psd.Color  strukturer är olika.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| left | [Color](../../com.aspose.psd/color) | Den com.aspose.psd.Color som är till vänster om ojämlikhetsoperatorn. |
| right | [Color](../../com.aspose.psd/color) | Den com.aspose.psd.Color som är till höger om ojämlikhetsoperatorn. |

**Returns:**
boolean - True om de två com.aspose.psd.Color strukturerna är olika; annars false.
### toArgb() {#toArgb--}
```
public int toArgb()
```


Hämtar det 32-bitars ARGB‑värdet för denna  com.aspose.psd.Color  struktur.

**Returns:**
int - 32‑bits ARGB‑värdet för detta com.aspose.psd.Color .
### toCmyk(Color pixel) {#toCmyk-com.aspose.psd.Color-}
```
public static CmykColor toCmyk(Color pixel)
```


Konverteringen från Color till CmykColor. Denna metod är föråldrad. Använd den mer effektiva CmykColorHelper.toCmyk(Color) .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.psd/color) | Pixeln av typen Color i RGB‑format. |

**Returns:**
[CmykColor](../../com.aspose.psd/cmykcolor) - The  CmykColor .
### toCmyk(Color[] pixels) {#toCmyk-com.aspose.psd.Color---}
```
public static CmykColor[] toCmyk(Color[] pixels)
```


Konverteringen från Color till CMYKColor. Denna metod är föråldrad. Använd den mer effektiva CmykColorHelper.toCmyk(Color[]) .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.psd/color) | Pixlarna av typen Color i RGB‑format. |

**Returns:**
com.aspose.psd.CmykColor[] - Aspose:Imaging:CmykColor[] .
### toCmykIcc(Color pixel) {#toCmykIcc-com.aspose.psd.Color-}
```
public static CmykColor toCmykIcc(Color pixel)
```


Konverteringen från Color till CMYKColor med icc‑konvertering och standardprofiler. Denna metod är föråldrad. Använd den mer effektiva CmykColorHelper.toCmykIcc(Color) .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.psd/color) | Pixeln av typen Color i RGB‑format. |

**Returns:**
[CmykColor](../../com.aspose.psd/cmykcolor) - The  CmykColor .
### toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIcc-com.aspose.psd.Color-java.io.InputStream-java.io.InputStream-}
```
public static CmykColor toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream)
```


Konverteringen från Color till CMYKColor med icc‑konvertering och standardprofiler. Denna metod är föråldrad. Använd den mer effektiva CmykColorHelper.toCmykIcc(Color, InputStream, InputStream) .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.psd/color) | Pixeln av typen Color i RGB‑format. |
| rgbIccStream | java.io.InputStream | Strömmen som innehåller icc rgb-profilen. |
| cmykIccStream | java.io.InputStream | Strömmen som innehåller icc cmyk-profilen. |

**Returns:**
[CmykColor](../../com.aspose.psd/cmykcolor) - The  CmykColor[] .
### toCmykIcc(Color[] pixels) {#toCmykIcc-com.aspose.psd.Color---}
```
public static CmykColor[] toCmykIcc(Color[] pixels)
```


Konverteringen från Color till CMYKColor med icc-konvertering med standardprofiler. Denna metod är föråldrad. Använd mer effektiv  CmykColorHelper.toCmykIcc(Color[]) .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.psd/color) | Pixlarna av typen Color i RGB‑format. |

**Returns:**
com.aspose.psd.CmykColor[] - CmykColor[]-arrayen.
### toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIcc-com.aspose.psd.Color---java.io.InputStream-java.io.InputStream-}
```
public static CmykColor[] toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)
```


Konverteringen från Color till CMYKColor med icc-konvertering. Denna metod är föråldrad. Använd mer effektiv  CmykColorHelper.toCmykIcc(Color[], InputStream, InputStream) .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.psd/color) | Pixlarna av typen Color i RGB‑format. |
| rgbIccStream | java.io.InputStream | Strömmen som innehåller icc rgb-profilen. |
| cmykIccStream | java.io.InputStream | Strömmen som innehåller icc cmyk-profilen. |

**Returns:**
com.aspose.psd.CmykColor[] - CmykColor[]-arrayen.
### toCmykIcc_internalized(Color pixel, System.IO.Stream rgbIccStream, System.IO.Stream cmykIccStream) {#toCmykIcc-internalized-com.aspose.psd.Color-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-}
```
public static CmykColor toCmykIcc_internalized(Color pixel, System.IO.Stream rgbIccStream, System.IO.Stream cmykIccStream)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
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
| Parameter | Typ | Beskrivning |
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


Hämtar  Aspose.Imaging.KnownColor  värdet för denna  com.aspose.psd.Color  struktur.

**Returns:**
int - Ett element i  Aspose.Imaging.KnownColor -enumerationen, om  com.aspose.psd.Color  skapas från en fördefinierad färg genom att använda antingen  Aspose.Imaging.Color.FromName(String) -metoden eller  Aspose.Imaging.Color.FromKnownColor(Aspose.Imaging.KnownColor) -metoden; annars 0.
### toString() {#toString--}
```
public String toString()
```


Konverterar denna  com.aspose.psd.Color  struktur till en människoläsbar sträng.

**Returns:**
java.lang.String - En sträng som är namnet på detta  com.aspose.psd.Color , om  com.aspose.psd.Color  skapas från en fördefinierad färg genom att använda antingen  Aspose.Imaging.Color.FromName(String) -metoden eller  Aspose.Imaging.Color.FromKnownColor(Aspose.Imaging.KnownColor) -metoden; annars en sträng som består av ARGB -komponentnamnen och deras värden.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

