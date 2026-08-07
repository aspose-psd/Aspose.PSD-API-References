---
title: "Color"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Il colore del pixel."
type: docs
weight: 19
url: /it/java/com.aspose.psd/color/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class Color extends Struct<Color>
```

Il colore del pixel.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Color()](#Color--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(Color that)](#CloneTo-com.aspose.psd.Color-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Verifica se l'oggetto specificato è una struttura com.aspose.psd.Color ed è equivalente a questa struttura com.aspose.psd.Color. |
| [fromArgb(byte red, byte green, byte blue)](#fromArgb-byte-byte-byte-) | Crea una struttura com.aspose.psd.Color dai valori di colore a 8 bit specificati (rosso, verde e blu). |
| [fromArgb(byte alpha, byte red, byte green, byte blue)](#fromArgb-byte-byte-byte-byte-) | Crea una struttura com.aspose.psd.Color dai quattro valori dei componenti ARGB (alpha, rosso, verde e blu). |
| [fromArgb(int argb)](#fromArgb-int-) | Crea una struttura  com.aspose.psd.Color  da un valore ARGB a 32 bit. |
| [fromArgb(int alpha, Color baseColor)](#fromArgb-int-com.aspose.psd.Color-) | Crea una struttura  com.aspose.psd.Color  dalla struttura  com.aspose.psd.Color  specificata, ma con il nuovo valore alfa specificato. |
| [fromArgb(int red, int green, int blue)](#fromArgb-int-int-int-) | Crea una struttura com.aspose.psd.Color dai valori di colore a 8 bit specificati (rosso, verde e blu). |
| [fromArgb(int alpha, int red, int green, int blue)](#fromArgb-int-int-int-int-) | Crea una struttura com.aspose.psd.Color dai quattro valori dei componenti ARGB (alpha, rosso, verde e blu). |
| [fromKnownColor(int color)](#fromKnownColor-int-) | Crea una struttura  com.aspose.psd.Color  dal colore predefinito specificato. |
| [fromName(String name)](#fromName-java.lang.String-) | Crea una struttura  com.aspose.psd.Color  dal nome specificato di un colore predefinito. |
| [getA()](#getA--) | Restituisce il valore del componente alfa di questa  com.aspose.psd.Color  struttura. |
| [getAliceBlue()](#getAliceBlue--) | Restituisce un colore definito dal sistema. |
| [getAntiqueWhite()](#getAntiqueWhite--) | Restituisce un colore definito dal sistema. |
| [getAqua()](#getAqua--) | Restituisce un colore definito dal sistema. |
| [getAquamarine()](#getAquamarine--) | Restituisce un colore definito dal sistema. |
| [getAzure()](#getAzure--) | Restituisce un colore definito dal sistema. |
| [getB()](#getB--) | Restituisce il valore del componente blu di questa  com.aspose.psd.Color  struttura. |
| [getBeige()](#getBeige--) | Restituisce un colore definito dal sistema. |
| [getBisque()](#getBisque--) | Restituisce un colore definito dal sistema. |
| [getBlack()](#getBlack--) | Restituisce un colore definito dal sistema. |
| [getBlanchedAlmond()](#getBlanchedAlmond--) | Restituisce un colore definito dal sistema. |
| [getBlue()](#getBlue--) | Restituisce un colore definito dal sistema. |
| [getBlueViolet()](#getBlueViolet--) | Restituisce un colore definito dal sistema. |
| [getBrightness()](#getBrightness--) | Restituisce il valore di luminosità (HSB) della tonalità-saturazione-luminosità per questa  com.aspose.psd.Color  struttura. |
| [getBrown()](#getBrown--) | Restituisce un colore definito dal sistema. |
| [getBurlyWood()](#getBurlyWood--) | Restituisce un colore definito dal sistema. |
| [getCadetBlue()](#getCadetBlue--) | Restituisce un colore definito dal sistema. |
| [getChartreuse()](#getChartreuse--) | Restituisce un colore definito dal sistema. |
| [getChocolate()](#getChocolate--) | Restituisce un colore definito dal sistema. |
| [getClass()](#getClass--) |  |
| [getCoral()](#getCoral--) | Restituisce un colore definito dal sistema. |
| [getCornflowerBlue()](#getCornflowerBlue--) | Restituisce un colore definito dal sistema. |
| [getCornsilk()](#getCornsilk--) | Restituisce un colore definito dal sistema. |
| [getCrimson()](#getCrimson--) | Restituisce un colore definito dal sistema. |
| [getCyan()](#getCyan--) | Restituisce un colore definito dal sistema. |
| [getDarkBlue()](#getDarkBlue--) | Restituisce un colore definito dal sistema. |
| [getDarkCyan()](#getDarkCyan--) | Restituisce un colore definito dal sistema. |
| [getDarkGoldenrod()](#getDarkGoldenrod--) | Restituisce un colore definito dal sistema. |
| [getDarkGray()](#getDarkGray--) | Restituisce un colore definito dal sistema. |
| [getDarkGreen()](#getDarkGreen--) | Restituisce un colore definito dal sistema. |
| [getDarkKhaki()](#getDarkKhaki--) | Restituisce un colore definito dal sistema. |
| [getDarkMagenta()](#getDarkMagenta--) | Restituisce un colore definito dal sistema. |
| [getDarkOliveGreen()](#getDarkOliveGreen--) | Restituisce un colore definito dal sistema. |
| [getDarkOrange()](#getDarkOrange--) | Restituisce un colore definito dal sistema. |
| [getDarkOrchid()](#getDarkOrchid--) | Restituisce un colore definito dal sistema. |
| [getDarkRed()](#getDarkRed--) | Restituisce un colore definito dal sistema. |
| [getDarkSalmon()](#getDarkSalmon--) | Restituisce un colore definito dal sistema. |
| [getDarkSeaGreen()](#getDarkSeaGreen--) | Restituisce un colore definito dal sistema. |
| [getDarkSlateBlue()](#getDarkSlateBlue--) | Restituisce un colore definito dal sistema. |
| [getDarkSlateGray()](#getDarkSlateGray--) | Restituisce un colore definito dal sistema. |
| [getDarkTurquoise()](#getDarkTurquoise--) | Restituisce un colore definito dal sistema. |
| [getDarkViolet()](#getDarkViolet--) | Restituisce un colore definito dal sistema. |
| [getDeepPink()](#getDeepPink--) | Restituisce un colore definito dal sistema. |
| [getDeepSkyBlue()](#getDeepSkyBlue--) | Restituisce un colore definito dal sistema. |
| [getDimGray()](#getDimGray--) | Restituisce un colore definito dal sistema. |
| [getDodgerBlue()](#getDodgerBlue--) | Restituisce un colore definito dal sistema. |
| [getEmpty()](#getEmpty--) | Restituisce un  Color  vuoto. |
| [getFirebrick()](#getFirebrick--) | Restituisce un colore definito dal sistema. |
| [getFloralWhite()](#getFloralWhite--) | Restituisce un colore definito dal sistema. |
| [getForestGreen()](#getForestGreen--) | Restituisce un colore definito dal sistema. |
| [getFuchsia()](#getFuchsia--) | Restituisce un colore definito dal sistema. |
| [getG()](#getG--) | Restituisce il valore del componente verde di questa  com.aspose.psd.Color  struttura. |
| [getGainsboro()](#getGainsboro--) | Restituisce un colore definito dal sistema. |
| [getGhostWhite()](#getGhostWhite--) | Restituisce un colore definito dal sistema. |
| [getGold()](#getGold--) | Restituisce un colore definito dal sistema. |
| [getGoldenrod()](#getGoldenrod--) | Restituisce un colore definito dal sistema. |
| [getGray()](#getGray--) | Restituisce un colore definito dal sistema. |
| [getGreen()](#getGreen--) | Restituisce un colore definito dal sistema. |
| [getGreenYellow()](#getGreenYellow--) | Restituisce un colore definito dal sistema. |
| [getHoneydew()](#getHoneydew--) | Restituisce un colore definito dal sistema. |
| [getHotPink()](#getHotPink--) | Restituisce un colore definito dal sistema. |
| [getHue()](#getHue--) | Restituisce il valore di tonalità (HSB), in gradi, per questa  com.aspose.psd.Color  struttura. |
| [getIndianRed()](#getIndianRed--) | Restituisce un colore definito dal sistema. |
| [getIndigo()](#getIndigo--) | Restituisce un colore definito dal sistema. |
| [getIvory()](#getIvory--) | Restituisce un colore definito dal sistema. |
| [getKhaki()](#getKhaki--) | Restituisce un colore definito dal sistema. |
| [getLavender()](#getLavender--) | Restituisce un colore definito dal sistema. |
| [getLavenderBlush()](#getLavenderBlush--) | Restituisce un colore definito dal sistema. |
| [getLawnGreen()](#getLawnGreen--) | Restituisce un colore definito dal sistema. |
| [getLemonChiffon()](#getLemonChiffon--) | Restituisce un colore definito dal sistema. |
| [getLightBlue()](#getLightBlue--) | Restituisce un colore definito dal sistema. |
| [getLightCoral()](#getLightCoral--) | Restituisce un colore definito dal sistema. |
| [getLightCyan()](#getLightCyan--) | Restituisce un colore definito dal sistema. |
| [getLightGoldenrodYellow()](#getLightGoldenrodYellow--) | Restituisce un colore definito dal sistema. |
| [getLightGray()](#getLightGray--) | Restituisce un colore definito dal sistema. |
| [getLightGreen()](#getLightGreen--) | Restituisce un colore definito dal sistema. |
| [getLightPink()](#getLightPink--) | Restituisce un colore definito dal sistema. |
| [getLightSalmon()](#getLightSalmon--) | Restituisce un colore definito dal sistema. |
| [getLightSeaGreen()](#getLightSeaGreen--) | Restituisce un colore definito dal sistema. |
| [getLightSkyBlue()](#getLightSkyBlue--) | Restituisce un colore definito dal sistema. |
| [getLightSlateGray()](#getLightSlateGray--) | Restituisce un colore definito dal sistema. |
| [getLightSteelBlue()](#getLightSteelBlue--) | Restituisce un colore definito dal sistema. |
| [getLightYellow()](#getLightYellow--) | Restituisce un colore definito dal sistema. |
| [getLime()](#getLime--) | Restituisce un colore definito dal sistema. |
| [getLimeGreen()](#getLimeGreen--) | Restituisce un colore definito dal sistema. |
| [getLinen()](#getLinen--) | Restituisce un colore definito dal sistema. |
| [getMagenta()](#getMagenta--) | Restituisce un colore definito dal sistema. |
| [getMaroon()](#getMaroon--) | Restituisce un colore definito dal sistema. |
| [getMediumAquamarine()](#getMediumAquamarine--) | Restituisce un colore definito dal sistema. |
| [getMediumBlue()](#getMediumBlue--) | Restituisce un colore definito dal sistema. |
| [getMediumOrchid()](#getMediumOrchid--) | Restituisce un colore definito dal sistema. |
| [getMediumPurple()](#getMediumPurple--) | Restituisce un colore definito dal sistema. |
| [getMediumSeaGreen()](#getMediumSeaGreen--) | Restituisce un colore definito dal sistema. |
| [getMediumSlateBlue()](#getMediumSlateBlue--) | Restituisce un colore definito dal sistema. |
| [getMediumSpringGreen()](#getMediumSpringGreen--) | Restituisce un colore definito dal sistema. |
| [getMediumTurquoise()](#getMediumTurquoise--) | Restituisce un colore definito dal sistema. |
| [getMediumVioletRed()](#getMediumVioletRed--) | Restituisce un colore definito dal sistema. |
| [getMidnightBlue()](#getMidnightBlue--) | Restituisce un colore definito dal sistema. |
| [getMintCream()](#getMintCream--) | Restituisce un colore definito dal sistema. |
| [getMistyRose()](#getMistyRose--) | Restituisce un colore definito dal sistema. |
| [getMoccasin()](#getMoccasin--) | Restituisce un colore definito dal sistema. |
| [getName()](#getName--) | Restituisce il nome di questo  com.aspose.psd.Color . |
| [getNavajoWhite()](#getNavajoWhite--) | Restituisce un colore definito dal sistema. |
| [getNavy()](#getNavy--) | Restituisce un colore definito dal sistema. |
| [getOldLace()](#getOldLace--) | Restituisce un colore definito dal sistema. |
| [getOlive()](#getOlive--) | Restituisce un colore definito dal sistema. |
| [getOliveDrab()](#getOliveDrab--) | Restituisce un colore definito dal sistema. |
| [getOrange()](#getOrange--) | Restituisce un colore definito dal sistema. |
| [getOrangeRed()](#getOrangeRed--) | Restituisce un colore definito dal sistema. |
| [getOrchid()](#getOrchid--) | Restituisce un colore definito dal sistema. |
| [getPaleGoldenrod()](#getPaleGoldenrod--) | Restituisce un colore definito dal sistema. |
| [getPaleGreen()](#getPaleGreen--) | Restituisce un colore definito dal sistema. |
| [getPaleTurquoise()](#getPaleTurquoise--) | Restituisce un colore definito dal sistema. |
| [getPaleVioletRed()](#getPaleVioletRed--) | Restituisce un colore definito dal sistema. |
| [getPapayaWhip()](#getPapayaWhip--) | Restituisce un colore definito dal sistema. |
| [getPeachPuff()](#getPeachPuff--) | Restituisce un colore definito dal sistema. |
| [getPeru()](#getPeru--) | Restituisce un colore definito dal sistema. |
| [getPink()](#getPink--) | Restituisce un colore definito dal sistema. |
| [getPlum()](#getPlum--) | Restituisce un colore definito dal sistema. |
| [getPowderBlue()](#getPowderBlue--) | Restituisce un colore definito dal sistema. |
| [getPurple()](#getPurple--) | Restituisce un colore definito dal sistema. |
| [getR()](#getR--) | Restituisce il valore del componente rosso di questa  com.aspose.psd.Color  struttura. |
| [getRed()](#getRed--) | Restituisce un colore definito dal sistema. |
| [getRosyBrown()](#getRosyBrown--) | Restituisce un colore definito dal sistema. |
| [getRoyalBlue()](#getRoyalBlue--) | Restituisce un colore definito dal sistema. |
| [getSaddleBrown()](#getSaddleBrown--) | Restituisce un colore definito dal sistema. |
| [getSalmon()](#getSalmon--) | Restituisce un colore definito dal sistema. |
| [getSandyBrown()](#getSandyBrown--) | Restituisce un colore definito dal sistema. |
| [getSaturation()](#getSaturation--) | Restituisce il valore di saturazione (HSB) per questa  com.aspose.psd.Color  struttura. |
| [getSeaGreen()](#getSeaGreen--) | Restituisce un colore definito dal sistema. |
| [getSeaShell()](#getSeaShell--) | Restituisce un colore definito dal sistema. |
| [getSienna()](#getSienna--) | Restituisce un colore definito dal sistema. |
| [getSilver()](#getSilver--) | Restituisce un colore definito dal sistema. |
| [getSkyBlue()](#getSkyBlue--) | Restituisce un colore definito dal sistema. |
| [getSlateBlue()](#getSlateBlue--) | Restituisce un colore definito dal sistema. |
| [getSlateGray()](#getSlateGray--) | Restituisce un colore definito dal sistema. |
| [getSnow()](#getSnow--) | Restituisce un colore definito dal sistema. |
| [getSpringGreen()](#getSpringGreen--) | Restituisce un colore definito dal sistema. |
| [getSteelBlue()](#getSteelBlue--) | Restituisce un colore definito dal sistema. |
| [getTan()](#getTan--) | Restituisce un colore definito dal sistema. |
| [getTeal()](#getTeal--) | Restituisce un colore definito dal sistema. |
| [getThistle()](#getThistle--) | Restituisce un colore definito dal sistema. |
| [getTomato()](#getTomato--) | Restituisce un colore definito dal sistema. |
| [getTransparent()](#getTransparent--) | Restituisce un colore definito dal sistema. |
| [getTurquoise()](#getTurquoise--) | Restituisce un colore definito dal sistema. |
| [getViolet()](#getViolet--) | Restituisce un colore definito dal sistema. |
| [getWheat()](#getWheat--) | Restituisce un colore definito dal sistema. |
| [getWhite()](#getWhite--) | Restituisce un colore definito dal sistema. |
| [getWhiteSmoke()](#getWhiteSmoke--) | Restituisce un colore definito dal sistema. |
| [getYellow()](#getYellow--) | Restituisce un colore definito dal sistema. |
| [getYellowGreen()](#getYellowGreen--) | Restituisce un colore definito dal sistema. |
| [hashCode()](#hashCode--) | Restituisce un codice hash per questa  com.aspose.psd.Color  struttura. |
| [isEmpty()](#isEmpty--) | Restituisce un valore che indica se questa  com.aspose.psd.Color  struttura è non inizializzata. |
| [isEquals(Color obj1, Color obj2)](#isEquals-com.aspose.psd.Color-com.aspose.psd.Color-) |  |
| [isKnownColor()](#isKnownColor--) | Restituisce un valore che indica se questa  com.aspose.psd.Color  struttura è un colore predefinito. |
| [isNamedColor()](#isNamedColor--) | Restituisce un valore che indica se questa  com.aspose.psd.Color  struttura è un colore con nome o un membro dell'enumerazione  Aspose.Imaging.KnownColor  enumerazione. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Equality(Color left, Color right)](#op-Equality-com.aspose.psd.Color-com.aspose.psd.Color-) | Verifica se due strutture  com.aspose.psd.Color  specificate sono equivalenti. |
| [op_Inequality(Color left, Color right)](#op-Inequality-com.aspose.psd.Color-com.aspose.psd.Color-) | Verifica se due strutture  com.aspose.psd.Color  specificate sono diverse. |
| [toArgb()](#toArgb--) | Restituisce il valore ARGB a 32 bit di questa  com.aspose.psd.Color  struttura. |
| [toCmyk(Color pixel)](#toCmyk-com.aspose.psd.Color-) | La conversione da Color a CmykColor. |
| [toCmyk(Color[] pixels)](#toCmyk-com.aspose.psd.Color---) | La conversione da Color a CMYKColor. |
| [toCmykIcc(Color pixel)](#toCmykIcc-com.aspose.psd.Color-) | La conversione da Color a CMYKColor usando la conversione icc con profili predefiniti. |
| [toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIcc-com.aspose.psd.Color-java.io.InputStream-java.io.InputStream-) | La conversione da Color a CMYKColor usando la conversione icc con profili predefiniti. |
| [toCmykIcc(Color[] pixels)](#toCmykIcc-com.aspose.psd.Color---) | La conversione da Color a CMYKColor usando la conversione icc con profili predefiniti. |
| [toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIcc-com.aspose.psd.Color---java.io.InputStream-java.io.InputStream-) | La conversione da Color a CMYKColor usando la conversione icc. |
| [toCmykIcc_internalized(Color pixel, System.IO.Stream rgbIccStream, System.IO.Stream cmykIccStream)](#toCmykIcc-internalized-com.aspose.psd.Color-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-) |  |
| [toCmykIcc_internalized(Color[] pixels, System.IO.Stream rgbIccStream, System.IO.Stream cmykIccStream)](#toCmykIcc-internalized-com.aspose.psd.Color---com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-) |  |
| [toKnownColor()](#toKnownColor--) | Ottiene il valore  Aspose.Imaging.KnownColor  di questa struttura  com.aspose.psd.Color . |
| [toString()](#toString--) | Converte questa struttura  com.aspose.psd.Color  in una stringa leggibile dall'uomo. |
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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(Color that) {#CloneTo-com.aspose.psd.Color-}
```
public void CloneTo(Color that)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| that | [Color](../../com.aspose.psd/color) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Verifica se l'oggetto specificato è una struttura com.aspose.psd.Color ed è equivalente a questa struttura com.aspose.psd.Color.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | java.lang.Object | L'oggetto da testare. |

**Returns:**
boolean - True se  obj  è una struttura  com.aspose.psd.Color  equivalente a questa struttura  com.aspose.psd.Color ; altrimenti, false.
### fromArgb(byte red, byte green, byte blue) {#fromArgb-byte-byte-byte-}
```
public static Color fromArgb(byte red, byte green, byte blue)
```


Crea una struttura  com.aspose.psd.Color  dai valori di colore a 8 bit specificati (rosso, verde e blu). Il valore alfa è implicitamente 255 (completamente opaco). Sebbene questo metodo consenta di passare un valore a 32 bit per ciascun componente colore, il valore di ciascun componente è limitato a 8 bit.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rosso | byte | Il valore del componente rosso per il nuovo  com.aspose.psd.Color . I valori validi sono da 0 a 255. |
| verde | byte | Il valore del componente verde per il nuovo  com.aspose.psd.Color . I valori validi sono da 0 a 255. |
| blu | byte | Il valore del componente blu per il nuovo  com.aspose.psd.Color . I valori validi sono da 0 a 255. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  com.aspose.psd.Color  that this method creates.
### fromArgb(byte alpha, byte red, byte green, byte blue) {#fromArgb-byte-byte-byte-byte-}
```
public static Color fromArgb(byte alpha, byte red, byte green, byte blue)
```


Crea una struttura  com.aspose.psd.Color  dai quattro valori dei componenti ARGB (alfa, rosso, verde e blu). Sebbene questo metodo consenta di passare un valore a 32 bit per ciascun componente, il valore di ciascun componente è limitato a 8 bit.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| alpha | byte | Il componente alfa. I valori validi sono da 0 a 255. |
| rosso | byte | Il componente rosso. I valori validi sono da 0 a 255. |
| verde | byte | Il componente verde. I valori validi sono da 0 a 255. |
| blu | byte | Il componente blu. I valori validi sono da 0 a 255. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  com.aspose.psd.Color  that this method creates.
### fromArgb(int argb) {#fromArgb-int-}
```
public static Color fromArgb(int argb)
```


Crea una struttura  com.aspose.psd.Color  da un valore ARGB a 32 bit.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| argb | int | Un valore che specifica il valore ARGB a 32 bit. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  com.aspose.psd.Color  structure that this method creates.
### fromArgb(int alpha, Color baseColor) {#fromArgb-int-com.aspose.psd.Color-}
```
public static Color fromArgb(int alpha, Color baseColor)
```


Crea una struttura  com.aspose.psd.Color  dalla struttura  com.aspose.psd.Color  specificata, ma con il nuovo valore alfa specificato. Sebbene questo metodo consenta di passare un valore a 32 bit per il valore alfa, il valore è limitato a 8 bit.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| alpha | int | Il valore alfa per il nuovo  com.aspose.psd.Color . I valori validi sono da 0 a 255. |
| baseColor | [Color](../../com.aspose.psd/color) | Il  com.aspose.psd.Color  da cui creare il nuovo  com.aspose.psd.Color . |

**Returns:**
[Color](../../com.aspose.psd/color) - The  com.aspose.psd.Color  that this method creates.
### fromArgb(int red, int green, int blue) {#fromArgb-int-int-int-}
```
public static Color fromArgb(int red, int green, int blue)
```


Crea una struttura  com.aspose.psd.Color  dai valori di colore a 8 bit specificati (rosso, verde e blu). Il valore alfa è implicitamente 255 (completamente opaco). Sebbene questo metodo consenta di passare un valore a 32 bit per ciascun componente colore, il valore di ciascun componente è limitato a 8 bit.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rosso | int | Il valore del componente rosso per il nuovo  com.aspose.psd.Color . I valori validi sono da 0 a 255. |
| verde | int | Il valore del componente verde per il nuovo  com.aspose.psd.Color . I valori validi sono da 0 a 255. |
| blu | int | Il valore del componente blu per il nuovo  com.aspose.psd.Color . I valori validi sono da 0 a 255. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  com.aspose.psd.Color  that this method creates.
### fromArgb(int alpha, int red, int green, int blue) {#fromArgb-int-int-int-int-}
```
public static Color fromArgb(int alpha, int red, int green, int blue)
```


Crea una struttura  com.aspose.psd.Color  dai quattro valori dei componenti ARGB (alfa, rosso, verde e blu). Sebbene questo metodo consenta di passare un valore a 32 bit per ciascun componente, il valore di ciascun componente è limitato a 8 bit.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| alpha | int | Il componente alfa. I valori validi sono da 0 a 255. |
| rosso | int | Il componente rosso. I valori validi sono da 0 a 255. |
| verde | int | Il componente verde. I valori validi sono da 0 a 255. |
| blu | int | Il componente blu. I valori validi sono da 0 a 255. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  com.aspose.psd.Color  that this method creates.
### fromKnownColor(int color) {#fromKnownColor-int-}
```
public static Color fromKnownColor(int color)
```


Crea una struttura  com.aspose.psd.Color  dal colore predefinito specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| colore | int | Un elemento dell'enumerazione  Aspose.Imaging.KnownColor . |

**Returns:**
[Color](../../com.aspose.psd/color) - The  com.aspose.psd.Color  that this method creates.
### fromName(String name) {#fromName-java.lang.String-}
```
public static Color fromName(String name)
```


Crea una struttura  com.aspose.psd.Color  dal nome specificato di un colore predefinito.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nome | java.lang.String | Una stringa che è il nome di un colore predefinito. I nomi validi sono gli stessi dei nomi degli elementi dell'enumerazione  Aspose.Imaging.KnownColor . |

**Returns:**
[Color](../../com.aspose.psd/color) - The  com.aspose.psd.Color  that this method creates.
### getA() {#getA--}
```
public byte getA()
```


Restituisce il valore del componente alfa di questa  com.aspose.psd.Color  struttura.

**Returns:**
byte - Il valore del componente alfa di questo  com.aspose.psd.Color .
### getAliceBlue() {#getAliceBlue--}
```
public static Color getAliceBlue()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getAntiqueWhite() {#getAntiqueWhite--}
```
public static Color getAntiqueWhite()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getAqua() {#getAqua--}
```
public static Color getAqua()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getAquamarine() {#getAquamarine--}
```
public static Color getAquamarine()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getAzure() {#getAzure--}
```
public static Color getAzure()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getB() {#getB--}
```
public byte getB()
```


Restituisce il valore del componente blu di questa  com.aspose.psd.Color  struttura.

**Returns:**
byte - Il valore del componente blu di questo  com.aspose.psd.Color .
### getBeige() {#getBeige--}
```
public static Color getBeige()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getBisque() {#getBisque--}
```
public static Color getBisque()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getBlack() {#getBlack--}
```
public static Color getBlack()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getBlanchedAlmond() {#getBlanchedAlmond--}
```
public static Color getBlanchedAlmond()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getBlue() {#getBlue--}
```
public static Color getBlue()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getBlueViolet() {#getBlueViolet--}
```
public static Color getBlueViolet()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getBrightness() {#getBrightness--}
```
public float getBrightness()
```


Restituisce il valore di luminosità (HSB) della tonalità-saturazione-luminosità per questa  com.aspose.psd.Color  struttura.

**Returns:**
float - La luminosità di questo  com.aspose.psd.Color . La luminosità varia da 0.0 a 1.0, dove 0.0 rappresenta il nero e 1.0 rappresenta il bianco.
### getBrown() {#getBrown--}
```
public static Color getBrown()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getBurlyWood() {#getBurlyWood--}
```
public static Color getBurlyWood()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getCadetBlue() {#getCadetBlue--}
```
public static Color getCadetBlue()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getChartreuse() {#getChartreuse--}
```
public static Color getChartreuse()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getChocolate() {#getChocolate--}
```
public static Color getChocolate()
```


Restituisce un colore definito dal sistema.

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


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getCornflowerBlue() {#getCornflowerBlue--}
```
public static Color getCornflowerBlue()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getCornsilk() {#getCornsilk--}
```
public static Color getCornsilk()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getCrimson() {#getCrimson--}
```
public static Color getCrimson()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getCyan() {#getCyan--}
```
public static Color getCyan()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkBlue() {#getDarkBlue--}
```
public static Color getDarkBlue()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkCyan() {#getDarkCyan--}
```
public static Color getDarkCyan()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkGoldenrod() {#getDarkGoldenrod--}
```
public static Color getDarkGoldenrod()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkGray() {#getDarkGray--}
```
public static Color getDarkGray()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkGreen() {#getDarkGreen--}
```
public static Color getDarkGreen()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkKhaki() {#getDarkKhaki--}
```
public static Color getDarkKhaki()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkMagenta() {#getDarkMagenta--}
```
public static Color getDarkMagenta()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkOliveGreen() {#getDarkOliveGreen--}
```
public static Color getDarkOliveGreen()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkOrange() {#getDarkOrange--}
```
public static Color getDarkOrange()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkOrchid() {#getDarkOrchid--}
```
public static Color getDarkOrchid()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkRed() {#getDarkRed--}
```
public static Color getDarkRed()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkSalmon() {#getDarkSalmon--}
```
public static Color getDarkSalmon()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkSeaGreen() {#getDarkSeaGreen--}
```
public static Color getDarkSeaGreen()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkSlateBlue() {#getDarkSlateBlue--}
```
public static Color getDarkSlateBlue()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkSlateGray() {#getDarkSlateGray--}
```
public static Color getDarkSlateGray()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkTurquoise() {#getDarkTurquoise--}
```
public static Color getDarkTurquoise()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkViolet() {#getDarkViolet--}
```
public static Color getDarkViolet()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDeepPink() {#getDeepPink--}
```
public static Color getDeepPink()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDeepSkyBlue() {#getDeepSkyBlue--}
```
public static Color getDeepSkyBlue()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDimGray() {#getDimGray--}
```
public static Color getDimGray()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDodgerBlue() {#getDodgerBlue--}
```
public static Color getDodgerBlue()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getEmpty() {#getEmpty--}
```
public static Color getEmpty()
```


Restituisce un  Color  vuoto.

**Returns:**
[Color](../../com.aspose.psd/color) - The empty  Color .
### getFirebrick() {#getFirebrick--}
```
public static Color getFirebrick()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getFloralWhite() {#getFloralWhite--}
```
public static Color getFloralWhite()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getForestGreen() {#getForestGreen--}
```
public static Color getForestGreen()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getFuchsia() {#getFuchsia--}
```
public static Color getFuchsia()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getG() {#getG--}
```
public byte getG()
```


Restituisce il valore del componente verde di questa  com.aspose.psd.Color  struttura.

**Returns:**
byte - Il valore del componente verde di questo  com.aspose.psd.Color .
### getGainsboro() {#getGainsboro--}
```
public static Color getGainsboro()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getGhostWhite() {#getGhostWhite--}
```
public static Color getGhostWhite()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getGold() {#getGold--}
```
public static Color getGold()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getGoldenrod() {#getGoldenrod--}
```
public static Color getGoldenrod()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getGray() {#getGray--}
```
public static Color getGray()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  structure representing a system-defined color.
### getGreen() {#getGreen--}
```
public static Color getGreen()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getGreenYellow() {#getGreenYellow--}
```
public static Color getGreenYellow()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getHoneydew() {#getHoneydew--}
```
public static Color getHoneydew()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getHotPink() {#getHotPink--}
```
public static Color getHotPink()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getHue() {#getHue--}
```
public float getHue()
```


Restituisce il valore di tonalità (HSB), in gradi, per questa  com.aspose.psd.Color  struttura.

**Returns:**
float - La tonalità, in gradi, di questo  com.aspose.psd.Color . La tonalità è misurata in gradi, variando da 0.0 a 360.0, nello spazio colore HSB.
### getIndianRed() {#getIndianRed--}
```
public static Color getIndianRed()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getIndigo() {#getIndigo--}
```
public static Color getIndigo()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getIvory() {#getIvory--}
```
public static Color getIvory()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getKhaki() {#getKhaki--}
```
public static Color getKhaki()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLavender() {#getLavender--}
```
public static Color getLavender()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLavenderBlush() {#getLavenderBlush--}
```
public static Color getLavenderBlush()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLawnGreen() {#getLawnGreen--}
```
public static Color getLawnGreen()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLemonChiffon() {#getLemonChiffon--}
```
public static Color getLemonChiffon()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightBlue() {#getLightBlue--}
```
public static Color getLightBlue()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightCoral() {#getLightCoral--}
```
public static Color getLightCoral()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightCyan() {#getLightCyan--}
```
public static Color getLightCyan()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightGoldenrodYellow() {#getLightGoldenrodYellow--}
```
public static Color getLightGoldenrodYellow()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightGray() {#getLightGray--}
```
public static Color getLightGray()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightGreen() {#getLightGreen--}
```
public static Color getLightGreen()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightPink() {#getLightPink--}
```
public static Color getLightPink()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightSalmon() {#getLightSalmon--}
```
public static Color getLightSalmon()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightSeaGreen() {#getLightSeaGreen--}
```
public static Color getLightSeaGreen()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightSkyBlue() {#getLightSkyBlue--}
```
public static Color getLightSkyBlue()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightSlateGray() {#getLightSlateGray--}
```
public static Color getLightSlateGray()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightSteelBlue() {#getLightSteelBlue--}
```
public static Color getLightSteelBlue()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightYellow() {#getLightYellow--}
```
public static Color getLightYellow()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLime() {#getLime--}
```
public static Color getLime()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLimeGreen() {#getLimeGreen--}
```
public static Color getLimeGreen()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLinen() {#getLinen--}
```
public static Color getLinen()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMagenta() {#getMagenta--}
```
public static Color getMagenta()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMaroon() {#getMaroon--}
```
public static Color getMaroon()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMediumAquamarine() {#getMediumAquamarine--}
```
public static Color getMediumAquamarine()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMediumBlue() {#getMediumBlue--}
```
public static Color getMediumBlue()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMediumOrchid() {#getMediumOrchid--}
```
public static Color getMediumOrchid()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMediumPurple() {#getMediumPurple--}
```
public static Color getMediumPurple()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMediumSeaGreen() {#getMediumSeaGreen--}
```
public static Color getMediumSeaGreen()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMediumSlateBlue() {#getMediumSlateBlue--}
```
public static Color getMediumSlateBlue()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMediumSpringGreen() {#getMediumSpringGreen--}
```
public static Color getMediumSpringGreen()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMediumTurquoise() {#getMediumTurquoise--}
```
public static Color getMediumTurquoise()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMediumVioletRed() {#getMediumVioletRed--}
```
public static Color getMediumVioletRed()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMidnightBlue() {#getMidnightBlue--}
```
public static Color getMidnightBlue()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMintCream() {#getMintCream--}
```
public static Color getMintCream()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMistyRose() {#getMistyRose--}
```
public static Color getMistyRose()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMoccasin() {#getMoccasin--}
```
public static Color getMoccasin()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getName() {#getName--}
```
public String getName()
```


Restituisce il nome di questo  com.aspose.psd.Color .

**Returns:**
java.lang.String - Il nome di questo  com.aspose.psd.Color .
### getNavajoWhite() {#getNavajoWhite--}
```
public static Color getNavajoWhite()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getNavy() {#getNavy--}
```
public static Color getNavy()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getOldLace() {#getOldLace--}
```
public static Color getOldLace()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getOlive() {#getOlive--}
```
public static Color getOlive()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getOliveDrab() {#getOliveDrab--}
```
public static Color getOliveDrab()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getOrange() {#getOrange--}
```
public static Color getOrange()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getOrangeRed() {#getOrangeRed--}
```
public static Color getOrangeRed()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getOrchid() {#getOrchid--}
```
public static Color getOrchid()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPaleGoldenrod() {#getPaleGoldenrod--}
```
public static Color getPaleGoldenrod()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPaleGreen() {#getPaleGreen--}
```
public static Color getPaleGreen()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPaleTurquoise() {#getPaleTurquoise--}
```
public static Color getPaleTurquoise()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPaleVioletRed() {#getPaleVioletRed--}
```
public static Color getPaleVioletRed()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPapayaWhip() {#getPapayaWhip--}
```
public static Color getPapayaWhip()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPeachPuff() {#getPeachPuff--}
```
public static Color getPeachPuff()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPeru() {#getPeru--}
```
public static Color getPeru()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPink() {#getPink--}
```
public static Color getPink()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPlum() {#getPlum--}
```
public static Color getPlum()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPowderBlue() {#getPowderBlue--}
```
public static Color getPowderBlue()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPurple() {#getPurple--}
```
public static Color getPurple()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getR() {#getR--}
```
public byte getR()
```


Restituisce il valore del componente rosso di questa  com.aspose.psd.Color  struttura.

**Returns:**
byte - Il valore del componente rosso di questo  com.aspose.psd.Color .
### getRed() {#getRed--}
```
public static Color getRed()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getRosyBrown() {#getRosyBrown--}
```
public static Color getRosyBrown()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getRoyalBlue() {#getRoyalBlue--}
```
public static Color getRoyalBlue()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSaddleBrown() {#getSaddleBrown--}
```
public static Color getSaddleBrown()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSalmon() {#getSalmon--}
```
public static Color getSalmon()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSandyBrown() {#getSandyBrown--}
```
public static Color getSandyBrown()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSaturation() {#getSaturation--}
```
public float getSaturation()
```


Restituisce il valore di saturazione (HSB) per questa  com.aspose.psd.Color  struttura.

**Returns:**
float - La saturazione di questo  com.aspose.psd.Color . La saturazione varia da 0.0 a 1.0, dove 0.0 è in scala di grigi e 1.0 è la massima saturazione.
### getSeaGreen() {#getSeaGreen--}
```
public static Color getSeaGreen()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSeaShell() {#getSeaShell--}
```
public static Color getSeaShell()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSienna() {#getSienna--}
```
public static Color getSienna()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSilver() {#getSilver--}
```
public static Color getSilver()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSkyBlue() {#getSkyBlue--}
```
public static Color getSkyBlue()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSlateBlue() {#getSlateBlue--}
```
public static Color getSlateBlue()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSlateGray() {#getSlateGray--}
```
public static Color getSlateGray()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSnow() {#getSnow--}
```
public static Color getSnow()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSpringGreen() {#getSpringGreen--}
```
public static Color getSpringGreen()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSteelBlue() {#getSteelBlue--}
```
public static Color getSteelBlue()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getTan() {#getTan--}
```
public static Color getTan()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getTeal() {#getTeal--}
```
public static Color getTeal()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getThistle() {#getThistle--}
```
public static Color getThistle()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getTomato() {#getTomato--}
```
public static Color getTomato()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getTransparent() {#getTransparent--}
```
public static Color getTransparent()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getTurquoise() {#getTurquoise--}
```
public static Color getTurquoise()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getViolet() {#getViolet--}
```
public static Color getViolet()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getWheat() {#getWheat--}
```
public static Color getWheat()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getWhite() {#getWhite--}
```
public static Color getWhite()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getWhiteSmoke() {#getWhiteSmoke--}
```
public static Color getWhiteSmoke()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getYellow() {#getYellow--}
```
public static Color getYellow()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getYellowGreen() {#getYellowGreen--}
```
public static Color getYellowGreen()
```


Restituisce un colore definito dal sistema.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Restituisce un codice hash per questa  com.aspose.psd.Color  struttura.

**Returns:**
int - Un valore intero che specifica il codice hash per questo  com.aspose.psd.Color .
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Restituisce un valore che indica se questa  com.aspose.psd.Color  struttura è non inizializzata.

**Returns:**
boolean - Questa proprietà restituisce true se questo colore non è inizializzato; altrimenti, false.
### isEquals(Color obj1, Color obj2) {#isEquals-com.aspose.psd.Color-com.aspose.psd.Color-}
```
public static boolean isEquals(Color obj1, Color obj2)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj1 | [Color](../../com.aspose.psd/color) |  |
| obj2 | [Color](../../com.aspose.psd/color) |  |

**Returns:**
boolean
### isKnownColor() {#isKnownColor--}
```
public boolean isKnownColor()
```


Restituisce un valore che indica se questa struttura  com.aspose.psd.Color  è un colore predefinito. I colori predefiniti sono rappresentati dagli elementi dell'enumerazione  Aspose.Imaging.KnownColor .

**Returns:**
boolean - True se questo  com.aspose.psd.Color  è stato creato da un colore predefinito usando il metodo  Aspose.Imaging.Color.FromName(String)  o il metodo  Aspose.Imaging.Color.FromKnownColor(Aspose.Imaging.KnownColor) ; altrimenti, false.
### isNamedColor() {#isNamedColor--}
```
public boolean isNamedColor()
```


Restituisce un valore che indica se questa  com.aspose.psd.Color  struttura è un colore con nome o un membro dell'enumerazione  Aspose.Imaging.KnownColor  enumerazione.

**Returns:**
boolean - True se questo  com.aspose.psd.Color  è stato creato usando il metodo  Aspose.Imaging.Color.FromName(String)  o il metodo  Aspose.Imaging.Color.FromKnownColor(Aspose.Imaging.KnownColor) ; altrimenti, false.
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


Verifica se due strutture  com.aspose.psd.Color  specificate sono equivalenti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| left | [Color](../../com.aspose.psd/color) | Il  com.aspose.psd.Color  che si trova a sinistra dell'operatore di uguaglianza. |
| right | [Color](../../com.aspose.psd/color) | Il  com.aspose.psd.Color  che si trova a destra dell'operatore di uguaglianza. |

**Returns:**
boolean - True se le due strutture  com.aspose.psd.Color  sono uguali; altrimenti, false.
### op_Inequality(Color left, Color right) {#op-Inequality-com.aspose.psd.Color-com.aspose.psd.Color-}
```
public static boolean op_Inequality(Color left, Color right)
```


Verifica se due strutture  com.aspose.psd.Color  specificate sono diverse.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| left | [Color](../../com.aspose.psd/color) | Il  com.aspose.psd.Color  che si trova a sinistra dell'operatore di disuguaglianza. |
| right | [Color](../../com.aspose.psd/color) | Il  com.aspose.psd.Color  che si trova a destra dell'operatore di disuguaglianza. |

**Returns:**
boolean - True se le due strutture  com.aspose.psd.Color  sono diverse; altrimenti, false.
### toArgb() {#toArgb--}
```
public int toArgb()
```


Restituisce il valore ARGB a 32 bit di questa  com.aspose.psd.Color  struttura.

**Returns:**
int - Il valore ARGB a 32 bit di questo  com.aspose.psd.Color .
### toCmyk(Color pixel) {#toCmyk-com.aspose.psd.Color-}
```
public static CmykColor toCmyk(Color pixel)
```


La conversione da Color a CmykColor. Questo metodo è deprecato. Si prega di utilizzare il più efficace  CmykColorHelper.toCmyk(Color) .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.psd/color) | Il pixel di tipo Color in formato RGB. |

**Returns:**
[CmykColor](../../com.aspose.psd/cmykcolor) - The  CmykColor .
### toCmyk(Color[] pixels) {#toCmyk-com.aspose.psd.Color---}
```
public static CmykColor[] toCmyk(Color[] pixels)
```


La conversione da Color a CMYKColor. Questo metodo è deprecato. Si prega di utilizzare il più efficace  CmykColorHelper.toCmyk(Color[]) .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.psd/color) | I pixel di tipo Color in formato RGB. |

**Returns:**
com.aspose.psd.CmykColor[] - Il  Aspose:Imaging:CmykColor[] .
### toCmykIcc(Color pixel) {#toCmykIcc-com.aspose.psd.Color-}
```
public static CmykColor toCmykIcc(Color pixel)
```


La conversione da Color a CMYKColor usando la conversione icc con profili predefiniti. Questo metodo è deprecato. Si prega di utilizzare il più efficace  CmykColorHelper.toCmykIcc(Color) .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.psd/color) | Il pixel di tipo Color in formato RGB. |

**Returns:**
[CmykColor](../../com.aspose.psd/cmykcolor) - The  CmykColor .
### toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIcc-com.aspose.psd.Color-java.io.InputStream-java.io.InputStream-}
```
public static CmykColor toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream)
```


La conversione da Color a CMYKColor usando la conversione icc con profili predefiniti. Questo metodo è deprecato. Si prega di utilizzare il più efficace  CmykColorHelper.toCmykIcc(Color, InputStream, InputStream) .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.psd/color) | Il pixel di tipo Color in formato RGB. |
| rgbIccStream | java.io.InputStream | Il flusso contenente il profilo icc rgb. |
| cmykIccStream | java.io.InputStream | Il flusso contenente il profilo icc cmyk. |

**Returns:**
[CmykColor](../../com.aspose.psd/cmykcolor) - The  CmykColor[] .
### toCmykIcc(Color[] pixels) {#toCmykIcc-com.aspose.psd.Color---}
```
public static CmykColor[] toCmykIcc(Color[] pixels)
```


La conversione da Color a CMYKColor usando la conversione icc con profili predefiniti. Questo metodo è deprecato. Si prega di utilizzare il più efficace CmykColorHelper.toCmykIcc(Color[]).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.psd/color) | I pixel di tipo Color in formato RGB. |

**Returns:**
com.aspose.psd.CmykColor[] - Il CmykColor[] .
### toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIcc-com.aspose.psd.Color---java.io.InputStream-java.io.InputStream-}
```
public static CmykColor[] toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)
```


La conversione da Color a CMYKColor usando la conversione icc. Questo metodo è deprecato. Si prega di utilizzare il più efficace CmykColorHelper.toCmykIcc(Color[], InputStream, InputStream).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.psd/color) | I pixel di tipo Color in formato RGB. |
| rgbIccStream | java.io.InputStream | Il flusso contenente il profilo icc rgb. |
| cmykIccStream | java.io.InputStream | Il flusso contenente il profilo icc cmyk. |

**Returns:**
com.aspose.psd.CmykColor[] - Il CmykColor[] .
### toCmykIcc_internalized(Color pixel, System.IO.Stream rgbIccStream, System.IO.Stream cmykIccStream) {#toCmykIcc-internalized-com.aspose.psd.Color-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-}
```
public static CmykColor toCmykIcc_internalized(Color pixel, System.IO.Stream rgbIccStream, System.IO.Stream cmykIccStream)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
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
| Parametro | Tipo | Descrizione |
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


Ottiene il valore  Aspose.Imaging.KnownColor  di questa struttura  com.aspose.psd.Color .

**Returns:**
int - Un elemento dell'enumerazione Aspose.Imaging.KnownColor, se il com.aspose.psd.Color è creato da un colore predefinito usando il metodo Aspose.Imaging.Color.FromName(String) o il metodo Aspose.Imaging.Color.FromKnownColor(Aspose.Imaging.KnownColor); altrimenti, 0.
### toString() {#toString--}
```
public String toString()
```


Converte questa struttura  com.aspose.psd.Color  in una stringa leggibile dall'uomo.

**Returns:**
java.lang.String - Una stringa che è il nome di questo com.aspose.psd.Color, se il com.aspose.psd.Color è creato da un colore predefinito usando il metodo Aspose.Imaging.Color.FromName(String) o il metodo Aspose.Imaging.Color.FromKnownColor(Aspose.Imaging.KnownColor); altrimenti, una stringa che consiste nei nomi dei componenti ARGB e nei loro valori.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

