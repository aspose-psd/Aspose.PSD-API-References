---
title: "Farbe"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Die Farbe des Pixels."
type: docs
weight: 19
url: /de/java/com.aspose.psd/color/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class Color extends Struct<Color>
```

Die Farbe des Pixels.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Color()](#Color--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(Color that)](#CloneTo-com.aspose.psd.Color-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Prüft, ob das angegebene Objekt eine  com.aspose.psd.Color  Struktur ist und dieser  com.aspose.psd.Color  Struktur entspricht. |
| [fromArgb(byte red, byte green, byte blue)](#fromArgb-byte-byte-byte-) | Erstellt eine  com.aspose.psd.Color  Struktur aus den angegebenen 8-Bit-Farbwerten (Rot, Grün und Blau). |
| [fromArgb(byte alpha, byte red, byte green, byte blue)](#fromArgb-byte-byte-byte-byte-) | Erstellt eine  com.aspose.psd.Color  Struktur aus den vier ARGB-Komponenten (Alpha, Rot, Grün und Blau) Werten. |
| [fromArgb(int argb)](#fromArgb-int-) | Erstellt eine  com.aspose.psd.Color  Struktur aus einem 32‑Bit‑ARGB‑Wert. |
| [fromArgb(int alpha, Color baseColor)](#fromArgb-int-com.aspose.psd.Color-) | Erstellt eine  com.aspose.psd.Color  Struktur aus der angegebenen  com.aspose.psd.Color  Struktur, jedoch mit dem neu angegebenen Alpha‑Wert. |
| [fromArgb(int red, int green, int blue)](#fromArgb-int-int-int-) | Erstellt eine  com.aspose.psd.Color  Struktur aus den angegebenen 8-Bit-Farbwerten (Rot, Grün und Blau). |
| [fromArgb(int alpha, int red, int green, int blue)](#fromArgb-int-int-int-int-) | Erstellt eine  com.aspose.psd.Color  Struktur aus den vier ARGB-Komponenten (Alpha, Rot, Grün und Blau) Werten. |
| [fromKnownColor(int color)](#fromKnownColor-int-) | Erstellt eine  com.aspose.psd.Color  Struktur aus der angegebenen vordefinierten Farbe. |
| [fromName(String name)](#fromName-java.lang.String-) | Erstellt eine  com.aspose.psd.Color  Struktur aus dem angegebenen Namen einer vordefinierten Farbe. |
| [getA()](#getA--) | Liefert den Alpha‑Komponentenwert dieser  com.aspose.psd.Color  Struktur. |
| [getAliceBlue()](#getAliceBlue--) | Liefert eine systemdefinierte Farbe. |
| [getAntiqueWhite()](#getAntiqueWhite--) | Liefert eine systemdefinierte Farbe. |
| [getAqua()](#getAqua--) | Liefert eine systemdefinierte Farbe. |
| [getAquamarine()](#getAquamarine--) | Liefert eine systemdefinierte Farbe. |
| [getAzure()](#getAzure--) | Liefert eine systemdefinierte Farbe. |
| [getB()](#getB--) | Liefert den Blau‑Komponentenwert dieser  com.aspose.psd.Color  Struktur. |
| [getBeige()](#getBeige--) | Liefert eine systemdefinierte Farbe. |
| [getBisque()](#getBisque--) | Liefert eine systemdefinierte Farbe. |
| [getBlack()](#getBlack--) | Liefert eine systemdefinierte Farbe. |
| [getBlanchedAlmond()](#getBlanchedAlmond--) | Liefert eine systemdefinierte Farbe. |
| [getBlue()](#getBlue--) | Liefert eine systemdefinierte Farbe. |
| [getBlueViolet()](#getBlueViolet--) | Liefert eine systemdefinierte Farbe. |
| [getBrightness()](#getBrightness--) | Liefert den Helligkeitswert des Farbton‑Sättigungs‑Helligkeits‑Modells (HSB) für diese  com.aspose.psd.Color  Struktur. |
| [getBrown()](#getBrown--) | Liefert eine systemdefinierte Farbe. |
| [getBurlyWood()](#getBurlyWood--) | Liefert eine systemdefinierte Farbe. |
| [getCadetBlue()](#getCadetBlue--) | Liefert eine systemdefinierte Farbe. |
| [getChartreuse()](#getChartreuse--) | Liefert eine systemdefinierte Farbe. |
| [getChocolate()](#getChocolate--) | Liefert eine systemdefinierte Farbe. |
| [getClass()](#getClass--) |  |
| [getCoral()](#getCoral--) | Liefert eine systemdefinierte Farbe. |
| [getCornflowerBlue()](#getCornflowerBlue--) | Liefert eine systemdefinierte Farbe. |
| [getCornsilk()](#getCornsilk--) | Liefert eine systemdefinierte Farbe. |
| [getCrimson()](#getCrimson--) | Liefert eine systemdefinierte Farbe. |
| [getCyan()](#getCyan--) | Liefert eine systemdefinierte Farbe. |
| [getDarkBlue()](#getDarkBlue--) | Liefert eine systemdefinierte Farbe. |
| [getDarkCyan()](#getDarkCyan--) | Liefert eine systemdefinierte Farbe. |
| [getDarkGoldenrod()](#getDarkGoldenrod--) | Liefert eine systemdefinierte Farbe. |
| [getDarkGray()](#getDarkGray--) | Liefert eine systemdefinierte Farbe. |
| [getDarkGreen()](#getDarkGreen--) | Liefert eine systemdefinierte Farbe. |
| [getDarkKhaki()](#getDarkKhaki--) | Liefert eine systemdefinierte Farbe. |
| [getDarkMagenta()](#getDarkMagenta--) | Liefert eine systemdefinierte Farbe. |
| [getDarkOliveGreen()](#getDarkOliveGreen--) | Liefert eine systemdefinierte Farbe. |
| [getDarkOrange()](#getDarkOrange--) | Liefert eine systemdefinierte Farbe. |
| [getDarkOrchid()](#getDarkOrchid--) | Liefert eine systemdefinierte Farbe. |
| [getDarkRed()](#getDarkRed--) | Liefert eine systemdefinierte Farbe. |
| [getDarkSalmon()](#getDarkSalmon--) | Liefert eine systemdefinierte Farbe. |
| [getDarkSeaGreen()](#getDarkSeaGreen--) | Liefert eine systemdefinierte Farbe. |
| [getDarkSlateBlue()](#getDarkSlateBlue--) | Liefert eine systemdefinierte Farbe. |
| [getDarkSlateGray()](#getDarkSlateGray--) | Liefert eine systemdefinierte Farbe. |
| [getDarkTurquoise()](#getDarkTurquoise--) | Liefert eine systemdefinierte Farbe. |
| [getDarkViolet()](#getDarkViolet--) | Liefert eine systemdefinierte Farbe. |
| [getDeepPink()](#getDeepPink--) | Liefert eine systemdefinierte Farbe. |
| [getDeepSkyBlue()](#getDeepSkyBlue--) | Liefert eine systemdefinierte Farbe. |
| [getDimGray()](#getDimGray--) | Liefert eine systemdefinierte Farbe. |
| [getDodgerBlue()](#getDodgerBlue--) | Liefert eine systemdefinierte Farbe. |
| [getEmpty()](#getEmpty--) | Liefert ein leeres  Color . |
| [getFirebrick()](#getFirebrick--) | Liefert eine systemdefinierte Farbe. |
| [getFloralWhite()](#getFloralWhite--) | Liefert eine systemdefinierte Farbe. |
| [getForestGreen()](#getForestGreen--) | Liefert eine systemdefinierte Farbe. |
| [getFuchsia()](#getFuchsia--) | Liefert eine systemdefinierte Farbe. |
| [getG()](#getG--) | Liefert den Grün‑Komponentenwert dieser  com.aspose.psd.Color  Struktur. |
| [getGainsboro()](#getGainsboro--) | Liefert eine systemdefinierte Farbe. |
| [getGhostWhite()](#getGhostWhite--) | Liefert eine systemdefinierte Farbe. |
| [getGold()](#getGold--) | Liefert eine systemdefinierte Farbe. |
| [getGoldenrod()](#getGoldenrod--) | Liefert eine systemdefinierte Farbe. |
| [getGray()](#getGray--) | Liefert eine systemdefinierte Farbe. |
| [getGreen()](#getGreen--) | Liefert eine systemdefinierte Farbe. |
| [getGreenYellow()](#getGreenYellow--) | Liefert eine systemdefinierte Farbe. |
| [getHoneydew()](#getHoneydew--) | Liefert eine systemdefinierte Farbe. |
| [getHotPink()](#getHotPink--) | Liefert eine systemdefinierte Farbe. |
| [getHue()](#getHue--) | Liefert den Farbtonwert des Farbton‑Sättigungs‑Helligkeits‑Modells (HSB) in Grad für diese  com.aspose.psd.Color  Struktur. |
| [getIndianRed()](#getIndianRed--) | Liefert eine systemdefinierte Farbe. |
| [getIndigo()](#getIndigo--) | Liefert eine systemdefinierte Farbe. |
| [getIvory()](#getIvory--) | Liefert eine systemdefinierte Farbe. |
| [getKhaki()](#getKhaki--) | Liefert eine systemdefinierte Farbe. |
| [getLavender()](#getLavender--) | Liefert eine systemdefinierte Farbe. |
| [getLavenderBlush()](#getLavenderBlush--) | Liefert eine systemdefinierte Farbe. |
| [getLawnGreen()](#getLawnGreen--) | Liefert eine systemdefinierte Farbe. |
| [getLemonChiffon()](#getLemonChiffon--) | Liefert eine systemdefinierte Farbe. |
| [getLightBlue()](#getLightBlue--) | Liefert eine systemdefinierte Farbe. |
| [getLightCoral()](#getLightCoral--) | Liefert eine systemdefinierte Farbe. |
| [getLightCyan()](#getLightCyan--) | Liefert eine systemdefinierte Farbe. |
| [getLightGoldenrodYellow()](#getLightGoldenrodYellow--) | Liefert eine systemdefinierte Farbe. |
| [getLightGray()](#getLightGray--) | Liefert eine systemdefinierte Farbe. |
| [getLightGreen()](#getLightGreen--) | Liefert eine systemdefinierte Farbe. |
| [getLightPink()](#getLightPink--) | Liefert eine systemdefinierte Farbe. |
| [getLightSalmon()](#getLightSalmon--) | Liefert eine systemdefinierte Farbe. |
| [getLightSeaGreen()](#getLightSeaGreen--) | Liefert eine systemdefinierte Farbe. |
| [getLightSkyBlue()](#getLightSkyBlue--) | Liefert eine systemdefinierte Farbe. |
| [getLightSlateGray()](#getLightSlateGray--) | Liefert eine systemdefinierte Farbe. |
| [getLightSteelBlue()](#getLightSteelBlue--) | Liefert eine systemdefinierte Farbe. |
| [getLightYellow()](#getLightYellow--) | Liefert eine systemdefinierte Farbe. |
| [getLime()](#getLime--) | Liefert eine systemdefinierte Farbe. |
| [getLimeGreen()](#getLimeGreen--) | Liefert eine systemdefinierte Farbe. |
| [getLinen()](#getLinen--) | Liefert eine systemdefinierte Farbe. |
| [getMagenta()](#getMagenta--) | Liefert eine systemdefinierte Farbe. |
| [getMaroon()](#getMaroon--) | Liefert eine systemdefinierte Farbe. |
| [getMediumAquamarine()](#getMediumAquamarine--) | Liefert eine systemdefinierte Farbe. |
| [getMediumBlue()](#getMediumBlue--) | Liefert eine systemdefinierte Farbe. |
| [getMediumOrchid()](#getMediumOrchid--) | Liefert eine systemdefinierte Farbe. |
| [getMediumPurple()](#getMediumPurple--) | Liefert eine systemdefinierte Farbe. |
| [getMediumSeaGreen()](#getMediumSeaGreen--) | Liefert eine systemdefinierte Farbe. |
| [getMediumSlateBlue()](#getMediumSlateBlue--) | Liefert eine systemdefinierte Farbe. |
| [getMediumSpringGreen()](#getMediumSpringGreen--) | Liefert eine systemdefinierte Farbe. |
| [getMediumTurquoise()](#getMediumTurquoise--) | Liefert eine systemdefinierte Farbe. |
| [getMediumVioletRed()](#getMediumVioletRed--) | Liefert eine systemdefinierte Farbe. |
| [getMidnightBlue()](#getMidnightBlue--) | Liefert eine systemdefinierte Farbe. |
| [getMintCream()](#getMintCream--) | Liefert eine systemdefinierte Farbe. |
| [getMistyRose()](#getMistyRose--) | Liefert eine systemdefinierte Farbe. |
| [getMoccasin()](#getMoccasin--) | Liefert eine systemdefinierte Farbe. |
| [getName()](#getName--) | Liefert den Namen dieser  com.aspose.psd.Color . |
| [getNavajoWhite()](#getNavajoWhite--) | Liefert eine systemdefinierte Farbe. |
| [getNavy()](#getNavy--) | Liefert eine systemdefinierte Farbe. |
| [getOldLace()](#getOldLace--) | Liefert eine systemdefinierte Farbe. |
| [getOlive()](#getOlive--) | Liefert eine systemdefinierte Farbe. |
| [getOliveDrab()](#getOliveDrab--) | Liefert eine systemdefinierte Farbe. |
| [getOrange()](#getOrange--) | Liefert eine systemdefinierte Farbe. |
| [getOrangeRed()](#getOrangeRed--) | Liefert eine systemdefinierte Farbe. |
| [getOrchid()](#getOrchid--) | Liefert eine systemdefinierte Farbe. |
| [getPaleGoldenrod()](#getPaleGoldenrod--) | Liefert eine systemdefinierte Farbe. |
| [getPaleGreen()](#getPaleGreen--) | Liefert eine systemdefinierte Farbe. |
| [getPaleTurquoise()](#getPaleTurquoise--) | Liefert eine systemdefinierte Farbe. |
| [getPaleVioletRed()](#getPaleVioletRed--) | Liefert eine systemdefinierte Farbe. |
| [getPapayaWhip()](#getPapayaWhip--) | Liefert eine systemdefinierte Farbe. |
| [getPeachPuff()](#getPeachPuff--) | Liefert eine systemdefinierte Farbe. |
| [getPeru()](#getPeru--) | Liefert eine systemdefinierte Farbe. |
| [getPink()](#getPink--) | Liefert eine systemdefinierte Farbe. |
| [getPlum()](#getPlum--) | Liefert eine systemdefinierte Farbe. |
| [getPowderBlue()](#getPowderBlue--) | Liefert eine systemdefinierte Farbe. |
| [getPurple()](#getPurple--) | Liefert eine systemdefinierte Farbe. |
| [getR()](#getR--) | Liefert den Rot‑Komponentenwert dieser  com.aspose.psd.Color  Struktur. |
| [getRed()](#getRed--) | Liefert eine systemdefinierte Farbe. |
| [getRosyBrown()](#getRosyBrown--) | Liefert eine systemdefinierte Farbe. |
| [getRoyalBlue()](#getRoyalBlue--) | Liefert eine systemdefinierte Farbe. |
| [getSaddleBrown()](#getSaddleBrown--) | Liefert eine systemdefinierte Farbe. |
| [getSalmon()](#getSalmon--) | Liefert eine systemdefinierte Farbe. |
| [getSandyBrown()](#getSandyBrown--) | Liefert eine systemdefinierte Farbe. |
| [getSaturation()](#getSaturation--) | Liefert den Sättigungswert des Farbton‑Sättigungs‑Helligkeits‑Modells (HSB) für diese  com.aspose.psd.Color  Struktur. |
| [getSeaGreen()](#getSeaGreen--) | Liefert eine systemdefinierte Farbe. |
| [getSeaShell()](#getSeaShell--) | Liefert eine systemdefinierte Farbe. |
| [getSienna()](#getSienna--) | Liefert eine systemdefinierte Farbe. |
| [getSilver()](#getSilver--) | Liefert eine systemdefinierte Farbe. |
| [getSkyBlue()](#getSkyBlue--) | Liefert eine systemdefinierte Farbe. |
| [getSlateBlue()](#getSlateBlue--) | Liefert eine systemdefinierte Farbe. |
| [getSlateGray()](#getSlateGray--) | Liefert eine systemdefinierte Farbe. |
| [getSnow()](#getSnow--) | Liefert eine systemdefinierte Farbe. |
| [getSpringGreen()](#getSpringGreen--) | Liefert eine systemdefinierte Farbe. |
| [getSteelBlue()](#getSteelBlue--) | Liefert eine systemdefinierte Farbe. |
| [getTan()](#getTan--) | Liefert eine systemdefinierte Farbe. |
| [getTeal()](#getTeal--) | Liefert eine systemdefinierte Farbe. |
| [getThistle()](#getThistle--) | Liefert eine systemdefinierte Farbe. |
| [getTomato()](#getTomato--) | Liefert eine systemdefinierte Farbe. |
| [getTransparent()](#getTransparent--) | Liefert eine systemdefinierte Farbe. |
| [getTurquoise()](#getTurquoise--) | Liefert eine systemdefinierte Farbe. |
| [getViolet()](#getViolet--) | Liefert eine systemdefinierte Farbe. |
| [getWheat()](#getWheat--) | Liefert eine systemdefinierte Farbe. |
| [getWhite()](#getWhite--) | Liefert eine systemdefinierte Farbe. |
| [getWhiteSmoke()](#getWhiteSmoke--) | Liefert eine systemdefinierte Farbe. |
| [getYellow()](#getYellow--) | Liefert eine systemdefinierte Farbe. |
| [getYellowGreen()](#getYellowGreen--) | Liefert eine systemdefinierte Farbe. |
| [hashCode()](#hashCode--) | Gibt einen Hash‑Code für diese  com.aspose.psd.Color  Struktur zurück. |
| [isEmpty()](#isEmpty--) | Liefert einen Wert, der angibt, ob diese  com.aspose.psd.Color  Struktur nicht initialisiert ist. |
| [isEquals(Color obj1, Color obj2)](#isEquals-com.aspose.psd.Color-com.aspose.psd.Color-) |  |
| [isKnownColor()](#isKnownColor--) | Liefert einen Wert, der angibt, ob diese  com.aspose.psd.Color  Struktur eine vordefinierte Farbe ist. |
| [isNamedColor()](#isNamedColor--) | Liefert einen Wert, der angibt, ob diese  com.aspose.psd.Color  Struktur eine benannte Farbe oder ein Mitglied der  Aspose.Imaging.KnownColor  Aufzählung ist. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Equality(Color left, Color right)](#op-Equality-com.aspose.psd.Color-com.aspose.psd.Color-) | Prüft, ob zwei angegebene  com.aspose.psd.Color  Strukturen gleichwertig sind. |
| [op_Inequality(Color left, Color right)](#op-Inequality-com.aspose.psd.Color-com.aspose.psd.Color-) | Prüft, ob zwei angegebene  com.aspose.psd.Color  Strukturen unterschiedlich sind. |
| [toArgb()](#toArgb--) | Liefert den 32‑Bit‑ARGB‑Wert dieser  com.aspose.psd.Color  Struktur. |
| [toCmyk(Color pixel)](#toCmyk-com.aspose.psd.Color-) | Die Konvertierung von Color zu CmykColor. |
| [toCmyk(Color[] pixels)](#toCmyk-com.aspose.psd.Color---) | Die Konvertierung von Color zu CMYKColor. |
| [toCmykIcc(Color pixel)](#toCmykIcc-com.aspose.psd.Color-) | Die Konvertierung von Color zu CMYKColor mittels ICC‑Konvertierung mit Standardprofilen. |
| [toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIcc-com.aspose.psd.Color-java.io.InputStream-java.io.InputStream-) | Die Konvertierung von Color zu CMYKColor mittels ICC‑Konvertierung mit Standardprofilen. |
| [toCmykIcc(Color[] pixels)](#toCmykIcc-com.aspose.psd.Color---) | Die Konvertierung von Color zu CMYKColor mittels ICC‑Konvertierung mit Standardprofilen. |
| [toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIcc-com.aspose.psd.Color---java.io.InputStream-java.io.InputStream-) | Die Konvertierung von Color zu CMYKColor mittels ICC-Konvertierung. |
| [toCmykIcc_internalized(Color pixel, System.IO.Stream rgbIccStream, System.IO.Stream cmykIccStream)](#toCmykIcc-internalized-com.aspose.psd.Color-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-) |  |
| [toCmykIcc_internalized(Color[] pixels, System.IO.Stream rgbIccStream, System.IO.Stream cmykIccStream)](#toCmykIcc-internalized-com.aspose.psd.Color---com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-) |  |
| [toKnownColor()](#toKnownColor--) | Ruft den Aspose.Imaging.KnownColor-Wert dieser com.aspose.psd.Color-Struktur ab. |
| [toString()](#toString--) | Konvertiert diese com.aspose.psd.Color-Struktur in eine menschenlesbare Zeichenkette. |
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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(Color that) {#CloneTo-com.aspose.psd.Color-}
```
public void CloneTo(Color that)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| that | [Color](../../com.aspose.psd/color) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Prüft, ob das angegebene Objekt eine  com.aspose.psd.Color  Struktur ist und dieser  com.aspose.psd.Color  Struktur entspricht.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object | Das zu testende Objekt. |

**Returns:**
boolean – true, wenn obj eine com.aspose.psd.Color-Struktur ist, die dieser com.aspose.psd.Color-Struktur entspricht; andernfalls false.
### fromArgb(byte red, byte green, byte blue) {#fromArgb-byte-byte-byte-}
```
public static Color fromArgb(byte red, byte green, byte blue)
```


Erstellt eine com.aspose.psd.Color-Struktur aus den angegebenen 8‑Bit‑Farbwerten (Rot, Grün und Blau). Der Alphawert ist implizit 255 (vollständig undurchsichtig). Obwohl diese Methode einen 32‑Bit‑Wert für jede Farbkomponente zulässt, ist der Wert jeder Komponente auf 8 Bit begrenzt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rot | byte | Der Rot‑Komponentenwert für das neue com.aspose.psd.Color. Gültige Werte liegen zwischen 0 und 255. |
| grün | byte | Der Grün‑Komponentenwert für das neue com.aspose.psd.Color. Gültige Werte liegen zwischen 0 und 255. |
| blau | byte | Der Blau‑Komponentenwert für das neue com.aspose.psd.Color. Gültige Werte liegen zwischen 0 und 255. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  com.aspose.psd.Color  that this method creates.
### fromArgb(byte alpha, byte red, byte green, byte blue) {#fromArgb-byte-byte-byte-byte-}
```
public static Color fromArgb(byte alpha, byte red, byte green, byte blue)
```


Erstellt eine com.aspose.psd.Color-Struktur aus den vier ARGB‑Komponenten (Alpha, Rot, Grün und Blau). Obwohl diese Methode einen 32‑Bit‑Wert für jede Komponente zulässt, ist der Wert jeder Komponente auf 8 Bit begrenzt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Alpha | byte | Die Alpha‑Komponente. Gültige Werte liegen zwischen 0 und 255. |
| rot | byte | Die Rot‑Komponente. Gültige Werte liegen zwischen 0 und 255. |
| grün | byte | Die Grün‑Komponente. Gültige Werte liegen zwischen 0 und 255. |
| blau | byte | Die Blau‑Komponente. Gültige Werte liegen zwischen 0 und 255. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  com.aspose.psd.Color  that this method creates.
### fromArgb(int argb) {#fromArgb-int-}
```
public static Color fromArgb(int argb)
```


Erstellt eine  com.aspose.psd.Color  Struktur aus einem 32‑Bit‑ARGB‑Wert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| argb | int | Ein Wert, der den 32‑Bit‑ARGB‑Wert angibt. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  com.aspose.psd.Color  structure that this method creates.
### fromArgb(int alpha, Color baseColor) {#fromArgb-int-com.aspose.psd.Color-}
```
public static Color fromArgb(int alpha, Color baseColor)
```


Erstellt eine com.aspose.psd.Color-Struktur aus der angegebenen com.aspose.psd.Color-Struktur, jedoch mit dem neu angegebenen Alpha‑Wert. Obwohl diese Methode einen 32‑Bit‑Wert für den Alpha‑Wert zulässt, ist der Wert auf 8 Bit begrenzt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Alpha | int | Der Alpha‑Wert für das neue com.aspose.psd.Color. Gültige Werte liegen zwischen 0 und 255. |
| baseColor | [Color](../../com.aspose.psd/color) | Das com.aspose.psd.Color, aus dem das neue com.aspose.psd.Color erstellt werden soll. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  com.aspose.psd.Color  that this method creates.
### fromArgb(int red, int green, int blue) {#fromArgb-int-int-int-}
```
public static Color fromArgb(int red, int green, int blue)
```


Erstellt eine com.aspose.psd.Color-Struktur aus den angegebenen 8‑Bit‑Farbwerten (Rot, Grün und Blau). Der Alphawert ist implizit 255 (vollständig undurchsichtig). Obwohl diese Methode einen 32‑Bit‑Wert für jede Farbkomponente zulässt, ist der Wert jeder Komponente auf 8 Bit begrenzt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rot | int | Der Rot‑Komponentenwert für das neue com.aspose.psd.Color. Gültige Werte liegen zwischen 0 und 255. |
| grün | int | Der Grün‑Komponentenwert für das neue com.aspose.psd.Color. Gültige Werte liegen zwischen 0 und 255. |
| blau | int | Der Blau‑Komponentenwert für das neue com.aspose.psd.Color. Gültige Werte liegen zwischen 0 und 255. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  com.aspose.psd.Color  that this method creates.
### fromArgb(int alpha, int red, int green, int blue) {#fromArgb-int-int-int-int-}
```
public static Color fromArgb(int alpha, int red, int green, int blue)
```


Erstellt eine com.aspose.psd.Color-Struktur aus den vier ARGB‑Komponenten (Alpha, Rot, Grün und Blau). Obwohl diese Methode einen 32‑Bit‑Wert für jede Komponente zulässt, ist der Wert jeder Komponente auf 8 Bit begrenzt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Alpha | int | Die Alpha‑Komponente. Gültige Werte liegen zwischen 0 und 255. |
| rot | int | Die Rot‑Komponente. Gültige Werte liegen zwischen 0 und 255. |
| grün | int | Die Grün‑Komponente. Gültige Werte liegen zwischen 0 und 255. |
| blau | int | Die Blau‑Komponente. Gültige Werte liegen zwischen 0 und 255. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  com.aspose.psd.Color  that this method creates.
### fromKnownColor(int color) {#fromKnownColor-int-}
```
public static Color fromKnownColor(int color)
```


Erstellt eine  com.aspose.psd.Color  Struktur aus der angegebenen vordefinierten Farbe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Farbe | int | Ein Element der Aspose.Imaging.KnownColor‑Aufzählung. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  com.aspose.psd.Color  that this method creates.
### fromName(String name) {#fromName-java.lang.String-}
```
public static Color fromName(String name)
```


Erstellt eine  com.aspose.psd.Color  Struktur aus dem angegebenen Namen einer vordefinierten Farbe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Name | java.lang.String | Eine Zeichenkette, die den Namen einer vordefinierten Farbe enthält. Gültige Namen entsprechen den Namen der Elemente der Aspose.Imaging.KnownColor‑Aufzählung. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  com.aspose.psd.Color  that this method creates.
### getA() {#getA--}
```
public byte getA()
```


Liefert den Alpha‑Komponentenwert dieser  com.aspose.psd.Color  Struktur.

**Returns:**
byte – Der Alpha‑Komponentenwert dieses com.aspose.psd.Color.
### getAliceBlue() {#getAliceBlue--}
```
public static Color getAliceBlue()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getAntiqueWhite() {#getAntiqueWhite--}
```
public static Color getAntiqueWhite()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getAqua() {#getAqua--}
```
public static Color getAqua()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getAquamarine() {#getAquamarine--}
```
public static Color getAquamarine()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getAzure() {#getAzure--}
```
public static Color getAzure()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getB() {#getB--}
```
public byte getB()
```


Liefert den Blau‑Komponentenwert dieser  com.aspose.psd.Color  Struktur.

**Returns:**
byte – Der Blau‑Komponentenwert dieses com.aspose.psd.Color.
### getBeige() {#getBeige--}
```
public static Color getBeige()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getBisque() {#getBisque--}
```
public static Color getBisque()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getBlack() {#getBlack--}
```
public static Color getBlack()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getBlanchedAlmond() {#getBlanchedAlmond--}
```
public static Color getBlanchedAlmond()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getBlue() {#getBlue--}
```
public static Color getBlue()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getBlueViolet() {#getBlueViolet--}
```
public static Color getBlueViolet()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getBrightness() {#getBrightness--}
```
public float getBrightness()
```


Liefert den Helligkeitswert des Farbton‑Sättigungs‑Helligkeits‑Modells (HSB) für diese  com.aspose.psd.Color  Struktur.

**Returns:**
float - Die Helligkeit dieses com.aspose.psd.Color. Die Helligkeit reicht von 0.0 bis 1.0, wobei 0.0 Schwarz und 1.0 Weiß darstellt.
### getBrown() {#getBrown--}
```
public static Color getBrown()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getBurlyWood() {#getBurlyWood--}
```
public static Color getBurlyWood()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getCadetBlue() {#getCadetBlue--}
```
public static Color getCadetBlue()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getChartreuse() {#getChartreuse--}
```
public static Color getChartreuse()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getChocolate() {#getChocolate--}
```
public static Color getChocolate()
```


Liefert eine systemdefinierte Farbe.

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


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getCornflowerBlue() {#getCornflowerBlue--}
```
public static Color getCornflowerBlue()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getCornsilk() {#getCornsilk--}
```
public static Color getCornsilk()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getCrimson() {#getCrimson--}
```
public static Color getCrimson()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getCyan() {#getCyan--}
```
public static Color getCyan()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkBlue() {#getDarkBlue--}
```
public static Color getDarkBlue()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkCyan() {#getDarkCyan--}
```
public static Color getDarkCyan()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkGoldenrod() {#getDarkGoldenrod--}
```
public static Color getDarkGoldenrod()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkGray() {#getDarkGray--}
```
public static Color getDarkGray()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkGreen() {#getDarkGreen--}
```
public static Color getDarkGreen()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkKhaki() {#getDarkKhaki--}
```
public static Color getDarkKhaki()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkMagenta() {#getDarkMagenta--}
```
public static Color getDarkMagenta()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkOliveGreen() {#getDarkOliveGreen--}
```
public static Color getDarkOliveGreen()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkOrange() {#getDarkOrange--}
```
public static Color getDarkOrange()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkOrchid() {#getDarkOrchid--}
```
public static Color getDarkOrchid()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkRed() {#getDarkRed--}
```
public static Color getDarkRed()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkSalmon() {#getDarkSalmon--}
```
public static Color getDarkSalmon()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkSeaGreen() {#getDarkSeaGreen--}
```
public static Color getDarkSeaGreen()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkSlateBlue() {#getDarkSlateBlue--}
```
public static Color getDarkSlateBlue()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkSlateGray() {#getDarkSlateGray--}
```
public static Color getDarkSlateGray()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkTurquoise() {#getDarkTurquoise--}
```
public static Color getDarkTurquoise()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkViolet() {#getDarkViolet--}
```
public static Color getDarkViolet()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDeepPink() {#getDeepPink--}
```
public static Color getDeepPink()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDeepSkyBlue() {#getDeepSkyBlue--}
```
public static Color getDeepSkyBlue()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDimGray() {#getDimGray--}
```
public static Color getDimGray()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDodgerBlue() {#getDodgerBlue--}
```
public static Color getDodgerBlue()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getEmpty() {#getEmpty--}
```
public static Color getEmpty()
```


Liefert ein leeres  Color .

**Returns:**
[Color](../../com.aspose.psd/color) - The empty  Color .
### getFirebrick() {#getFirebrick--}
```
public static Color getFirebrick()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getFloralWhite() {#getFloralWhite--}
```
public static Color getFloralWhite()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getForestGreen() {#getForestGreen--}
```
public static Color getForestGreen()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getFuchsia() {#getFuchsia--}
```
public static Color getFuchsia()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getG() {#getG--}
```
public byte getG()
```


Liefert den Grün‑Komponentenwert dieser  com.aspose.psd.Color  Struktur.

**Returns:**
byte - Der Grünkomponentenwert dieses com.aspose.psd.Color.
### getGainsboro() {#getGainsboro--}
```
public static Color getGainsboro()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getGhostWhite() {#getGhostWhite--}
```
public static Color getGhostWhite()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getGold() {#getGold--}
```
public static Color getGold()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getGoldenrod() {#getGoldenrod--}
```
public static Color getGoldenrod()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getGray() {#getGray--}
```
public static Color getGray()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  structure representing a system-defined color.
### getGreen() {#getGreen--}
```
public static Color getGreen()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getGreenYellow() {#getGreenYellow--}
```
public static Color getGreenYellow()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getHoneydew() {#getHoneydew--}
```
public static Color getHoneydew()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getHotPink() {#getHotPink--}
```
public static Color getHotPink()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getHue() {#getHue--}
```
public float getHue()
```


Liefert den Farbtonwert des Farbton‑Sättigungs‑Helligkeits‑Modells (HSB) in Grad für diese  com.aspose.psd.Color  Struktur.

**Returns:**
float - Der Farbton in Grad dieses com.aspose.psd.Color. Der Farbton wird in Grad gemessen und reicht von 0.0 bis 360.0 im HSB-Farbraum.
### getIndianRed() {#getIndianRed--}
```
public static Color getIndianRed()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getIndigo() {#getIndigo--}
```
public static Color getIndigo()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getIvory() {#getIvory--}
```
public static Color getIvory()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getKhaki() {#getKhaki--}
```
public static Color getKhaki()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLavender() {#getLavender--}
```
public static Color getLavender()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLavenderBlush() {#getLavenderBlush--}
```
public static Color getLavenderBlush()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLawnGreen() {#getLawnGreen--}
```
public static Color getLawnGreen()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLemonChiffon() {#getLemonChiffon--}
```
public static Color getLemonChiffon()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightBlue() {#getLightBlue--}
```
public static Color getLightBlue()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightCoral() {#getLightCoral--}
```
public static Color getLightCoral()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightCyan() {#getLightCyan--}
```
public static Color getLightCyan()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightGoldenrodYellow() {#getLightGoldenrodYellow--}
```
public static Color getLightGoldenrodYellow()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightGray() {#getLightGray--}
```
public static Color getLightGray()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightGreen() {#getLightGreen--}
```
public static Color getLightGreen()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightPink() {#getLightPink--}
```
public static Color getLightPink()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightSalmon() {#getLightSalmon--}
```
public static Color getLightSalmon()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightSeaGreen() {#getLightSeaGreen--}
```
public static Color getLightSeaGreen()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightSkyBlue() {#getLightSkyBlue--}
```
public static Color getLightSkyBlue()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightSlateGray() {#getLightSlateGray--}
```
public static Color getLightSlateGray()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightSteelBlue() {#getLightSteelBlue--}
```
public static Color getLightSteelBlue()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightYellow() {#getLightYellow--}
```
public static Color getLightYellow()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLime() {#getLime--}
```
public static Color getLime()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLimeGreen() {#getLimeGreen--}
```
public static Color getLimeGreen()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLinen() {#getLinen--}
```
public static Color getLinen()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMagenta() {#getMagenta--}
```
public static Color getMagenta()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMaroon() {#getMaroon--}
```
public static Color getMaroon()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMediumAquamarine() {#getMediumAquamarine--}
```
public static Color getMediumAquamarine()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMediumBlue() {#getMediumBlue--}
```
public static Color getMediumBlue()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMediumOrchid() {#getMediumOrchid--}
```
public static Color getMediumOrchid()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMediumPurple() {#getMediumPurple--}
```
public static Color getMediumPurple()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMediumSeaGreen() {#getMediumSeaGreen--}
```
public static Color getMediumSeaGreen()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMediumSlateBlue() {#getMediumSlateBlue--}
```
public static Color getMediumSlateBlue()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMediumSpringGreen() {#getMediumSpringGreen--}
```
public static Color getMediumSpringGreen()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMediumTurquoise() {#getMediumTurquoise--}
```
public static Color getMediumTurquoise()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMediumVioletRed() {#getMediumVioletRed--}
```
public static Color getMediumVioletRed()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMidnightBlue() {#getMidnightBlue--}
```
public static Color getMidnightBlue()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMintCream() {#getMintCream--}
```
public static Color getMintCream()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMistyRose() {#getMistyRose--}
```
public static Color getMistyRose()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMoccasin() {#getMoccasin--}
```
public static Color getMoccasin()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getName() {#getName--}
```
public String getName()
```


Liefert den Namen dieser  com.aspose.psd.Color .

**Returns:**
java.lang.String - Der Name dieses com.aspose.psd.Color.
### getNavajoWhite() {#getNavajoWhite--}
```
public static Color getNavajoWhite()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getNavy() {#getNavy--}
```
public static Color getNavy()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getOldLace() {#getOldLace--}
```
public static Color getOldLace()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getOlive() {#getOlive--}
```
public static Color getOlive()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getOliveDrab() {#getOliveDrab--}
```
public static Color getOliveDrab()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getOrange() {#getOrange--}
```
public static Color getOrange()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getOrangeRed() {#getOrangeRed--}
```
public static Color getOrangeRed()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getOrchid() {#getOrchid--}
```
public static Color getOrchid()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPaleGoldenrod() {#getPaleGoldenrod--}
```
public static Color getPaleGoldenrod()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPaleGreen() {#getPaleGreen--}
```
public static Color getPaleGreen()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPaleTurquoise() {#getPaleTurquoise--}
```
public static Color getPaleTurquoise()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPaleVioletRed() {#getPaleVioletRed--}
```
public static Color getPaleVioletRed()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPapayaWhip() {#getPapayaWhip--}
```
public static Color getPapayaWhip()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPeachPuff() {#getPeachPuff--}
```
public static Color getPeachPuff()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPeru() {#getPeru--}
```
public static Color getPeru()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPink() {#getPink--}
```
public static Color getPink()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPlum() {#getPlum--}
```
public static Color getPlum()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPowderBlue() {#getPowderBlue--}
```
public static Color getPowderBlue()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPurple() {#getPurple--}
```
public static Color getPurple()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getR() {#getR--}
```
public byte getR()
```


Liefert den Rot‑Komponentenwert dieser  com.aspose.psd.Color  Struktur.

**Returns:**
byte - Der Rotkomponentenwert dieses com.aspose.psd.Color.
### getRed() {#getRed--}
```
public static Color getRed()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getRosyBrown() {#getRosyBrown--}
```
public static Color getRosyBrown()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getRoyalBlue() {#getRoyalBlue--}
```
public static Color getRoyalBlue()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSaddleBrown() {#getSaddleBrown--}
```
public static Color getSaddleBrown()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSalmon() {#getSalmon--}
```
public static Color getSalmon()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSandyBrown() {#getSandyBrown--}
```
public static Color getSandyBrown()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSaturation() {#getSaturation--}
```
public float getSaturation()
```


Liefert den Sättigungswert des Farbton‑Sättigungs‑Helligkeits‑Modells (HSB) für diese  com.aspose.psd.Color  Struktur.

**Returns:**
float - Die Sättigung dieses com.aspose.psd.Color. Die Sättigung reicht von 0.0 bis 1.0, wobei 0.0 Graustufen und 1.0 die höchste Sättigung bedeutet.
### getSeaGreen() {#getSeaGreen--}
```
public static Color getSeaGreen()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSeaShell() {#getSeaShell--}
```
public static Color getSeaShell()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSienna() {#getSienna--}
```
public static Color getSienna()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSilver() {#getSilver--}
```
public static Color getSilver()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSkyBlue() {#getSkyBlue--}
```
public static Color getSkyBlue()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSlateBlue() {#getSlateBlue--}
```
public static Color getSlateBlue()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSlateGray() {#getSlateGray--}
```
public static Color getSlateGray()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSnow() {#getSnow--}
```
public static Color getSnow()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSpringGreen() {#getSpringGreen--}
```
public static Color getSpringGreen()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSteelBlue() {#getSteelBlue--}
```
public static Color getSteelBlue()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getTan() {#getTan--}
```
public static Color getTan()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getTeal() {#getTeal--}
```
public static Color getTeal()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getThistle() {#getThistle--}
```
public static Color getThistle()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getTomato() {#getTomato--}
```
public static Color getTomato()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getTransparent() {#getTransparent--}
```
public static Color getTransparent()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getTurquoise() {#getTurquoise--}
```
public static Color getTurquoise()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getViolet() {#getViolet--}
```
public static Color getViolet()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getWheat() {#getWheat--}
```
public static Color getWheat()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getWhite() {#getWhite--}
```
public static Color getWhite()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getWhiteSmoke() {#getWhiteSmoke--}
```
public static Color getWhiteSmoke()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getYellow() {#getYellow--}
```
public static Color getYellow()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getYellowGreen() {#getYellowGreen--}
```
public static Color getYellowGreen()
```


Liefert eine systemdefinierte Farbe.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Gibt einen Hash‑Code für diese  com.aspose.psd.Color  Struktur zurück.

**Returns:**
int - Ein ganzzahliger Wert, der den Hashcode für dieses com.aspose.psd.Color angibt.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Liefert einen Wert, der angibt, ob diese  com.aspose.psd.Color  Struktur nicht initialisiert ist.

**Returns:**
boolean - Diese Eigenschaft gibt true zurück, wenn diese Farbe nicht initialisiert ist; andernfalls false.
### isEquals(Color obj1, Color obj2) {#isEquals-com.aspose.psd.Color-com.aspose.psd.Color-}
```
public static boolean isEquals(Color obj1, Color obj2)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj1 | [Color](../../com.aspose.psd/color) |  |
| obj2 | [Color](../../com.aspose.psd/color) |  |

**Returns:**
boolean
### isKnownColor() {#isKnownColor--}
```
public boolean isKnownColor()
```


Gibt einen Wert zurück, der angibt, ob diese com.aspose.psd.Color-Struktur eine vordefinierte Farbe ist. Vordefinierte Farben werden durch die Elemente der Aspose.Imaging.KnownColor‑Aufzählung dargestellt.

**Returns:**
boolean - True, wenn dieses com.aspose.psd.Color aus einer vordefinierten Farbe erstellt wurde, indem entweder die Methode Aspose.Imaging.Color.FromName(String) oder die Methode Aspose.Imaging.Color.FromKnownColor(Aspose.Imaging.KnownColor) verwendet wurde; andernfalls false.
### isNamedColor() {#isNamedColor--}
```
public boolean isNamedColor()
```


Liefert einen Wert, der angibt, ob diese  com.aspose.psd.Color  Struktur eine benannte Farbe oder ein Mitglied der  Aspose.Imaging.KnownColor  Aufzählung ist.

**Returns:**
boolean - True, wenn dieses com.aspose.psd.Color erstellt wurde, indem entweder die Methode Aspose.Imaging.Color.FromName(String) oder die Methode Aspose.Imaging.Color.FromKnownColor(Aspose.Imaging.KnownColor) verwendet wurde; andernfalls false.
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


Prüft, ob zwei angegebene  com.aspose.psd.Color  Strukturen gleichwertig sind.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| left | [Color](../../com.aspose.psd/color) | Das com.aspose.psd.Color, das links vom Gleichheitsoperator steht. |
| right | [Color](../../com.aspose.psd/color) | Das com.aspose.psd.Color, das rechts vom Gleichheitsoperator steht. |

**Returns:**
boolean - True, wenn die beiden com.aspose.psd.Color-Strukturen gleich sind; andernfalls false.
### op_Inequality(Color left, Color right) {#op-Inequality-com.aspose.psd.Color-com.aspose.psd.Color-}
```
public static boolean op_Inequality(Color left, Color right)
```


Prüft, ob zwei angegebene  com.aspose.psd.Color  Strukturen unterschiedlich sind.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| left | [Color](../../com.aspose.psd/color) | Das com.aspose.psd.Color, das links vom Ungleichheitsoperator steht. |
| right | [Color](../../com.aspose.psd/color) | Das com.aspose.psd.Color, das rechts vom Ungleichheitsoperator steht. |

**Returns:**
boolean - True, wenn die beiden com.aspose.psd.Color-Strukturen unterschiedlich sind; andernfalls false.
### toArgb() {#toArgb--}
```
public int toArgb()
```


Liefert den 32‑Bit‑ARGB‑Wert dieser  com.aspose.psd.Color  Struktur.

**Returns:**
int - Der 32‑Bit‑ARGB‑Wert dieses com.aspose.psd.Color.
### toCmyk(Color pixel) {#toCmyk-com.aspose.psd.Color-}
```
public static CmykColor toCmyk(Color pixel)
```


Die Konvertierung von Color zu CmykColor. Diese Methode ist veraltet. Bitte verwenden Sie die effektivere CmykColorHelper.toCmyk(Color).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.psd/color) | Das Pixel vom Typ Color im RGB-Format. |

**Returns:**
[CmykColor](../../com.aspose.psd/cmykcolor) - The  CmykColor .
### toCmyk(Color[] pixels) {#toCmyk-com.aspose.psd.Color---}
```
public static CmykColor[] toCmyk(Color[] pixels)
```


Die Konvertierung von Color zu CMYKColor. Diese Methode ist veraltet. Bitte verwenden Sie die effektivere CmykColorHelper.toCmyk(Color[]).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.psd/color) | Die Pixel vom Typ Color im RGB-Format. |

**Returns:**
com.aspose.psd.CmykColor[] - Die Aspose:Imaging:CmykColor[].
### toCmykIcc(Color pixel) {#toCmykIcc-com.aspose.psd.Color-}
```
public static CmykColor toCmykIcc(Color pixel)
```


Die Konvertierung von Color zu CMYKColor mittels ICC-Konvertierung mit Standardprofilen. Diese Methode ist veraltet. Bitte verwenden Sie die effektivere CmykColorHelper.toCmykIcc(Color).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.psd/color) | Das Pixel vom Typ Color im RGB-Format. |

**Returns:**
[CmykColor](../../com.aspose.psd/cmykcolor) - The  CmykColor .
### toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIcc-com.aspose.psd.Color-java.io.InputStream-java.io.InputStream-}
```
public static CmykColor toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream)
```


Die Konvertierung von Color zu CMYKColor mittels ICC-Konvertierung mit Standardprofilen. Diese Methode ist veraltet. Bitte verwenden Sie die effektivere CmykColorHelper.toCmykIcc(Color, InputStream, InputStream).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.psd/color) | Das Pixel vom Typ Color im RGB-Format. |
| rgbIccStream | java.io.InputStream | Der Stream, der das ICC-RGB-Profil enthält. |
| cmykIccStream | java.io.InputStream | Der Stream, der das ICC-CMYK-Profil enthält. |

**Returns:**
[CmykColor](../../com.aspose.psd/cmykcolor) - The  CmykColor[] .
### toCmykIcc(Color[] pixels) {#toCmykIcc-com.aspose.psd.Color---}
```
public static CmykColor[] toCmykIcc(Color[] pixels)
```


Die Konvertierung von Color zu CMYKColor mittels ICC-Konvertierung mit Standardprofilen. Diese Methode ist veraltet. Bitte verwenden Sie die effektivere  CmykColorHelper.toCmykIcc(Color[]) .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.psd/color) | Die Pixel vom Typ Color im RGB-Format. |

**Returns:**
com.aspose.psd.CmykColor[] - Das  CmykColor[] .
### toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIcc-com.aspose.psd.Color---java.io.InputStream-java.io.InputStream-}
```
public static CmykColor[] toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)
```


Die Konvertierung von Color zu CMYKColor mittels ICC-Konvertierung. Diese Methode ist veraltet. Bitte verwenden Sie die effektivere  CmykColorHelper.toCmykIcc(Color[], InputStream, InputStream) .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.psd/color) | Die Pixel vom Typ Color im RGB-Format. |
| rgbIccStream | java.io.InputStream | Der Stream, der das ICC-RGB-Profil enthält. |
| cmykIccStream | java.io.InputStream | Der Stream, der das ICC-CMYK-Profil enthält. |

**Returns:**
com.aspose.psd.CmykColor[] - Das  CmykColor[] .
### toCmykIcc_internalized(Color pixel, System.IO.Stream rgbIccStream, System.IO.Stream cmykIccStream) {#toCmykIcc-internalized-com.aspose.psd.Color-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-}
```
public static CmykColor toCmykIcc_internalized(Color pixel, System.IO.Stream rgbIccStream, System.IO.Stream cmykIccStream)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
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
| Parameter | Typ | Beschreibung |
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


Ruft den Aspose.Imaging.KnownColor-Wert dieser com.aspose.psd.Color-Struktur ab.

**Returns:**
int - Ein Element der  Aspose.Imaging.KnownColor  Aufzählung, falls das  com.aspose.psd.Color  aus einer vordefinierten Farbe mittels der  Aspose.Imaging.Color.FromName(String)  Methode oder der  Aspose.Imaging.Color.FromKnownColor(Aspose.Imaging.KnownColor)  Methode erstellt wird; andernfalls 0.
### toString() {#toString--}
```
public String toString()
```


Konvertiert diese com.aspose.psd.Color-Struktur in eine menschenlesbare Zeichenkette.

**Returns:**
java.lang.String - Eine Zeichenkette, die den Namen dieses  com.aspose.psd.Color  darstellt, falls das  com.aspose.psd.Color  aus einer vordefinierten Farbe mittels der  Aspose.Imaging.Color.FromName(String)  Methode oder der  Aspose.Imaging.Color.FromKnownColor(Aspose.Imaging.KnownColor)  Methode erstellt wird; andernfalls eine Zeichenkette, die aus den Namen der ARGB‑Komponenten und deren Werten besteht.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

