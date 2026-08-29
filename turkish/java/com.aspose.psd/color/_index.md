---
title: "Renk"
second_title: "Java için Aspose.PSD API Referansı"
description: "Pikselin rengi."
type: docs
weight: 19
url: /tr/java/com.aspose.psd/color/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class Color extends Struct<Color>
```

Pikselin rengi.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Color()](#Color--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(Color that)](#CloneTo-com.aspose.psd.Color-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Belirtilen nesnenin bir com.aspose.psd.Color yapısı olup olmadığını ve bu com.aspose.psd.Color yapısına eşit olup olmadığını test eder. |
| [fromArgb(byte red, byte green, byte blue)](#fromArgb-byte-byte-byte-) | Belirtilen 8 bit renk değerlerinden (kırmızı, yeşil ve mavi) bir com.aspose.psd.Color yapısı oluşturur. |
| [fromArgb(byte alpha, byte red, byte green, byte blue)](#fromArgb-byte-byte-byte-byte-) | Dört ARGB bileşeninin (alfa, kırmızı, yeşil ve mavi) değerlerinden bir com.aspose.psd.Color yapısı oluşturur. |
| [fromArgb(int argb)](#fromArgb-int-) | 32 bit ARGB değerinden bir com.aspose.psd.Color yapısı oluşturur. |
| [fromArgb(int alpha, Color baseColor)](#fromArgb-int-com.aspose.psd.Color-) | Belirtilen com.aspose.psd.Color yapısından, ancak yeni belirtilen alfa değeriyle bir com.aspose.psd.Color yapısı oluşturur. |
| [fromArgb(int red, int green, int blue)](#fromArgb-int-int-int-) | Belirtilen 8 bit renk değerlerinden (kırmızı, yeşil ve mavi) bir com.aspose.psd.Color yapısı oluşturur. |
| [fromArgb(int alpha, int red, int green, int blue)](#fromArgb-int-int-int-int-) | Dört ARGB bileşeninin (alfa, kırmızı, yeşil ve mavi) değerlerinden bir com.aspose.psd.Color yapısı oluşturur. |
| [fromKnownColor(int color)](#fromKnownColor-int-) | Belirtilen önceden tanımlı renkten bir com.aspose.psd.Color yapısı oluşturur. |
| [fromName(String name)](#fromName-java.lang.String-) | Belirtilen önceden tanımlı renk adından bir com.aspose.psd.Color yapısı oluşturur. |
| [getA()](#getA--) | Bu com.aspose.psd.Color yapısının alfa bileşen değerini alır. |
| [getAliceBlue()](#getAliceBlue--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getAntiqueWhite()](#getAntiqueWhite--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getAqua()](#getAqua--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getAquamarine()](#getAquamarine--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getAzure()](#getAzure--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getB()](#getB--) | Bu  com.aspose.psd.Color  yapısının mavi bileşen değerini alır. |
| [getBeige()](#getBeige--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getBisque()](#getBisque--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getBlack()](#getBlack--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getBlanchedAlmond()](#getBlanchedAlmond--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getBlue()](#getBlue--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getBlueViolet()](#getBlueViolet--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getBrightness()](#getBrightness--) | Bu  com.aspose.psd.Color  yapısı için hue-saturation-brightness (HSB) parlaklık değerini alır. |
| [getBrown()](#getBrown--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getBurlyWood()](#getBurlyWood--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getCadetBlue()](#getCadetBlue--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getChartreuse()](#getChartreuse--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getChocolate()](#getChocolate--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getClass()](#getClass--) |  |
| [getCoral()](#getCoral--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getCornflowerBlue()](#getCornflowerBlue--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getCornsilk()](#getCornsilk--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getCrimson()](#getCrimson--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getCyan()](#getCyan--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getDarkBlue()](#getDarkBlue--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getDarkCyan()](#getDarkCyan--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getDarkGoldenrod()](#getDarkGoldenrod--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getDarkGray()](#getDarkGray--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getDarkGreen()](#getDarkGreen--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getDarkKhaki()](#getDarkKhaki--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getDarkMagenta()](#getDarkMagenta--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getDarkOliveGreen()](#getDarkOliveGreen--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getDarkOrange()](#getDarkOrange--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getDarkOrchid()](#getDarkOrchid--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getDarkRed()](#getDarkRed--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getDarkSalmon()](#getDarkSalmon--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getDarkSeaGreen()](#getDarkSeaGreen--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getDarkSlateBlue()](#getDarkSlateBlue--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getDarkSlateGray()](#getDarkSlateGray--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getDarkTurquoise()](#getDarkTurquoise--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getDarkViolet()](#getDarkViolet--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getDeepPink()](#getDeepPink--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getDeepSkyBlue()](#getDeepSkyBlue--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getDimGray()](#getDimGray--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getDodgerBlue()](#getDodgerBlue--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getEmpty()](#getEmpty--) | Boş bir  Color  alır. |
| [getFirebrick()](#getFirebrick--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getFloralWhite()](#getFloralWhite--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getForestGreen()](#getForestGreen--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getFuchsia()](#getFuchsia--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getG()](#getG--) | Bu  com.aspose.psd.Color  yapısının yeşil bileşen değerini alır. |
| [getGainsboro()](#getGainsboro--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getGhostWhite()](#getGhostWhite--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getGold()](#getGold--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getGoldenrod()](#getGoldenrod--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getGray()](#getGray--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getGreen()](#getGreen--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getGreenYellow()](#getGreenYellow--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getHoneydew()](#getHoneydew--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getHotPink()](#getHotPink--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getHue()](#getHue--) | Bu  com.aspose.psd.Color  yapısı için hue-saturation-brightness (HSB) ton değerini, derece cinsinden alır. |
| [getIndianRed()](#getIndianRed--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getIndigo()](#getIndigo--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getIvory()](#getIvory--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getKhaki()](#getKhaki--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getLavender()](#getLavender--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getLavenderBlush()](#getLavenderBlush--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getLawnGreen()](#getLawnGreen--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getLemonChiffon()](#getLemonChiffon--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getLightBlue()](#getLightBlue--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getLightCoral()](#getLightCoral--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getLightCyan()](#getLightCyan--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getLightGoldenrodYellow()](#getLightGoldenrodYellow--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getLightGray()](#getLightGray--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getLightGreen()](#getLightGreen--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getLightPink()](#getLightPink--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getLightSalmon()](#getLightSalmon--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getLightSeaGreen()](#getLightSeaGreen--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getLightSkyBlue()](#getLightSkyBlue--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getLightSlateGray()](#getLightSlateGray--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getLightSteelBlue()](#getLightSteelBlue--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getLightYellow()](#getLightYellow--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getLime()](#getLime--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getLimeGreen()](#getLimeGreen--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getLinen()](#getLinen--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getMagenta()](#getMagenta--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getMaroon()](#getMaroon--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getMediumAquamarine()](#getMediumAquamarine--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getMediumBlue()](#getMediumBlue--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getMediumOrchid()](#getMediumOrchid--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getMediumPurple()](#getMediumPurple--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getMediumSeaGreen()](#getMediumSeaGreen--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getMediumSlateBlue()](#getMediumSlateBlue--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getMediumSpringGreen()](#getMediumSpringGreen--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getMediumTurquoise()](#getMediumTurquoise--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getMediumVioletRed()](#getMediumVioletRed--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getMidnightBlue()](#getMidnightBlue--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getMintCream()](#getMintCream--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getMistyRose()](#getMistyRose--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getMoccasin()](#getMoccasin--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getName()](#getName--) | Bu  com.aspose.psd.Color  adını alır. |
| [getNavajoWhite()](#getNavajoWhite--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getNavy()](#getNavy--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getOldLace()](#getOldLace--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getOlive()](#getOlive--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getOliveDrab()](#getOliveDrab--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getOrange()](#getOrange--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getOrangeRed()](#getOrangeRed--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getOrchid()](#getOrchid--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getPaleGoldenrod()](#getPaleGoldenrod--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getPaleGreen()](#getPaleGreen--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getPaleTurquoise()](#getPaleTurquoise--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getPaleVioletRed()](#getPaleVioletRed--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getPapayaWhip()](#getPapayaWhip--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getPeachPuff()](#getPeachPuff--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getPeru()](#getPeru--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getPink()](#getPink--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getPlum()](#getPlum--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getPowderBlue()](#getPowderBlue--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getPurple()](#getPurple--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getR()](#getR--) | Bu  com.aspose.psd.Color  yapısının kırmızı bileşen değerini alır. |
| [getRed()](#getRed--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getRosyBrown()](#getRosyBrown--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getRoyalBlue()](#getRoyalBlue--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getSaddleBrown()](#getSaddleBrown--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getSalmon()](#getSalmon--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getSandyBrown()](#getSandyBrown--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getSaturation()](#getSaturation--) | Bu  com.aspose.psd.Color  yapısı için hue-saturation-brightness (HSB) doygunluk değerini alır. |
| [getSeaGreen()](#getSeaGreen--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getSeaShell()](#getSeaShell--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getSienna()](#getSienna--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getSilver()](#getSilver--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getSkyBlue()](#getSkyBlue--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getSlateBlue()](#getSlateBlue--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getSlateGray()](#getSlateGray--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getSnow()](#getSnow--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getSpringGreen()](#getSpringGreen--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getSteelBlue()](#getSteelBlue--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getTan()](#getTan--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getTeal()](#getTeal--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getThistle()](#getThistle--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getTomato()](#getTomato--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getTransparent()](#getTransparent--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getTurquoise()](#getTurquoise--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getViolet()](#getViolet--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getWheat()](#getWheat--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getWhite()](#getWhite--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getWhiteSmoke()](#getWhiteSmoke--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getYellow()](#getYellow--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [getYellowGreen()](#getYellowGreen--) | Sistem tarafından tanımlanmış bir rengi alır. |
| [hashCode()](#hashCode--) | Bu  com.aspose.psd.Color  yapısı için bir karma kod (hash code) döndürür. |
| [isEmpty()](#isEmpty--) | Bu  com.aspose.psd.Color  yapısının başlatılmamış olup olmadığını gösteren bir değer alır. |
| [isEquals(Color obj1, Color obj2)](#isEquals-com.aspose.psd.Color-com.aspose.psd.Color-) |  |
| [isKnownColor()](#isKnownColor--) | Bu  com.aspose.psd.Color  yapısının önceden tanımlı bir renk olup olmadığını gösteren bir değer alır. |
| [isNamedColor()](#isNamedColor--) | Bu  com.aspose.psd.Color  yapısının adlandırılmış bir renk mi yoksa  Aspose.Imaging.KnownColor  enumarasyonunun bir üyesi mi olduğunu gösteren bir değer alır. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Equality(Color left, Color right)](#op-Equality-com.aspose.psd.Color-com.aspose.psd.Color-) | Belirtilen iki  com.aspose.psd.Color  yapısının eşdeğer olup olmadığını test eder. |
| [op_Inequality(Color left, Color right)](#op-Inequality-com.aspose.psd.Color-com.aspose.psd.Color-) | Belirtilen iki  com.aspose.psd.Color  yapısının farklı olup olmadığını test eder. |
| [toArgb()](#toArgb--) | Bu  com.aspose.psd.Color  yapısının 32-bit ARGB değerini alır. |
| [toCmyk(Color pixel)](#toCmyk-com.aspose.psd.Color-) | Color'dan CmykColor'a dönüşüm. |
| [toCmyk(Color[] pixels)](#toCmyk-com.aspose.psd.Color---) | Color'dan CMYKColor'a dönüşüm. |
| [toCmykIcc(Color pixel)](#toCmykIcc-com.aspose.psd.Color-) | Color'dan CMYKColor'a, varsayılan profillerle icc dönüşümü kullanılarak dönüşüm. |
| [toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIcc-com.aspose.psd.Color-java.io.InputStream-java.io.InputStream-) | Color'dan CMYKColor'a, varsayılan profillerle icc dönüşümü kullanılarak dönüşüm. |
| [toCmykIcc(Color[] pixels)](#toCmykIcc-com.aspose.psd.Color---) | Color'dan CMYKColor'a, varsayılan profillerle icc dönüşümü kullanılarak dönüşüm. |
| [toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIcc-com.aspose.psd.Color---java.io.InputStream-java.io.InputStream-) | Color'dan CMYKColor'a icc dönüşümü kullanılarak dönüşüm. |
| [toCmykIcc_internalized(Color pixel, System.IO.Stream rgbIccStream, System.IO.Stream cmykIccStream)](#toCmykIcc-internalized-com.aspose.psd.Color-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-) |  |
| [toCmykIcc_internalized(Color[] pixels, System.IO.Stream rgbIccStream, System.IO.Stream cmykIccStream)](#toCmykIcc-internalized-com.aspose.psd.Color---com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-) |  |
| [toKnownColor()](#toKnownColor--) | Bu  com.aspose.psd.Color  yapısının  Aspose.Imaging.KnownColor  değerini alır. |
| [toString()](#toString--) | Bu  com.aspose.psd.Color  yapısını insan tarafından okunabilir bir dizeye dönüştürür. |
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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(Color that) {#CloneTo-com.aspose.psd.Color-}
```
public void CloneTo(Color that)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| that | [Color](../../com.aspose.psd/color) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Belirtilen nesnenin bir com.aspose.psd.Color yapısı olup olmadığını ve bu com.aspose.psd.Color yapısına eşit olup olmadığını test eder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | Test edilecek nesne. |

**Returns:**
boolean - Eğer  obj  bu  com.aspose.psd.Color  yapısına eşdeğer bir  com.aspose.psd.Color  yapısı ise True; aksi takdirde false.
### fromArgb(byte red, byte green, byte blue) {#fromArgb-byte-byte-byte-}
```
public static Color fromArgb(byte red, byte green, byte blue)
```


Belirtilen 8-bit renk değerlerinden (kırmızı, yeşil ve mavi) bir  com.aspose.psd.Color  yapısı oluşturur. Alfa değeri örtülü olarak 255'tir (tamamen opak). Bu yöntem her renk bileşeni için 32-bit değer geçilmesine izin verse de, her bileşenin değeri 8 bit ile sınırlıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| kırmızı | byte | Yeni  com.aspose.psd.Color  için kırmızı bileşen değeri. Geçerli değerler 0 ile 255 arasındadır. |
| yeşil | byte | Yeni  com.aspose.psd.Color  için yeşil bileşen değeri. Geçerli değerler 0 ile 255 arasındadır. |
| mavi | byte | Yeni  com.aspose.psd.Color  için mavi bileşen değeri. Geçerli değerler 0 ile 255 arasındadır. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  com.aspose.psd.Color  that this method creates.
### fromArgb(byte alpha, byte red, byte green, byte blue) {#fromArgb-byte-byte-byte-byte-}
```
public static Color fromArgb(byte alpha, byte red, byte green, byte blue)
```


Dört ARGB bileşen (alfa, kırmızı, yeşil ve mavi) değerlerinden bir  com.aspose.psd.Color  yapısı oluşturur. Bu yöntem her bileşen için 32 bitlik bir değer geçirmeye izin verse de, her bileşenin değeri 8 bit ile sınırlıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| alfa | byte | Alfa bileşeni. Geçerli değerler 0 ile 255 arasındadır. |
| kırmızı | byte | Kırmızı bileşeni. Geçerli değerler 0 ile 255 arasındadır. |
| yeşil | byte | Yeşil bileşeni. Geçerli değerler 0 ile 255 arasındadır. |
| mavi | byte | Mavi bileşeni. Geçerli değerler 0 ile 255 arasındadır. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  com.aspose.psd.Color  that this method creates.
### fromArgb(int argb) {#fromArgb-int-}
```
public static Color fromArgb(int argb)
```


32 bit ARGB değerinden bir com.aspose.psd.Color yapısı oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| argb | int | 32 bitlik ARGB değerini belirten bir değer. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  com.aspose.psd.Color  structure that this method creates.
### fromArgb(int alpha, Color baseColor) {#fromArgb-int-com.aspose.psd.Color-}
```
public static Color fromArgb(int alpha, Color baseColor)
```


Belirtilen  com.aspose.psd.Color  yapısından bir  com.aspose.psd.Color  yapısı oluşturur, ancak yeni belirtilen alfa değeriyle. Bu yöntem alfa değeri için 32 bitlik bir değer geçirmeye izin verse de, değer 8 bit ile sınırlıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| alfa | int | Yeni  com.aspose.psd.Color  için alfa değeri. Geçerli değerler 0 ile 255 arasındadır. |
| baseColor | [Color](../../com.aspose.psd/color) | Yeni  com.aspose.psd.Color  oluşturmak için kullanılacak  com.aspose.psd.Color . |

**Returns:**
[Color](../../com.aspose.psd/color) - The  com.aspose.psd.Color  that this method creates.
### fromArgb(int red, int green, int blue) {#fromArgb-int-int-int-}
```
public static Color fromArgb(int red, int green, int blue)
```


Belirtilen 8-bit renk değerlerinden (kırmızı, yeşil ve mavi) bir  com.aspose.psd.Color  yapısı oluşturur. Alfa değeri örtülü olarak 255'tir (tamamen opak). Bu yöntem her renk bileşeni için 32-bit değer geçilmesine izin verse de, her bileşenin değeri 8 bit ile sınırlıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| kırmızı | int | Yeni  com.aspose.psd.Color  için kırmızı bileşen değeri. Geçerli değerler 0 ile 255 arasındadır. |
| yeşil | int | Yeni  com.aspose.psd.Color  için yeşil bileşen değeri. Geçerli değerler 0 ile 255 arasındadır. |
| mavi | int | Yeni  com.aspose.psd.Color  için mavi bileşen değeri. Geçerli değerler 0 ile 255 arasındadır. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  com.aspose.psd.Color  that this method creates.
### fromArgb(int alpha, int red, int green, int blue) {#fromArgb-int-int-int-int-}
```
public static Color fromArgb(int alpha, int red, int green, int blue)
```


Dört ARGB bileşen (alfa, kırmızı, yeşil ve mavi) değerlerinden bir  com.aspose.psd.Color  yapısı oluşturur. Bu yöntem her bileşen için 32 bitlik bir değer geçirmeye izin verse de, her bileşenin değeri 8 bit ile sınırlıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| alfa | int | Alfa bileşeni. Geçerli değerler 0 ile 255 arasındadır. |
| kırmızı | int | Kırmızı bileşeni. Geçerli değerler 0 ile 255 arasındadır. |
| yeşil | int | Yeşil bileşeni. Geçerli değerler 0 ile 255 arasındadır. |
| mavi | int | Mavi bileşeni. Geçerli değerler 0 ile 255 arasındadır. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  com.aspose.psd.Color  that this method creates.
### fromKnownColor(int color) {#fromKnownColor-int-}
```
public static Color fromKnownColor(int color)
```


Belirtilen önceden tanımlı renkten bir com.aspose.psd.Color yapısı oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| renk | int | Aspose.Imaging.KnownColor  enumarasyonunun bir öğesi. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  com.aspose.psd.Color  that this method creates.
### fromName(String name) {#fromName-java.lang.String-}
```
public static Color fromName(String name)
```


Belirtilen önceden tanımlı renk adından bir com.aspose.psd.Color yapısı oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ad | java.lang.String | Önceden tanımlı bir rengin adı olan bir dize. Geçerli adlar, Aspose.Imaging.KnownColor  enumarasyonundaki öğelerin adlarıyla aynıdır. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  com.aspose.psd.Color  that this method creates.
### getA() {#getA--}
```
public byte getA()
```


Bu com.aspose.psd.Color yapısının alfa bileşen değerini alır.

**Returns:**
byte - Bu  com.aspose.psd.Color  nesnesinin alfa bileşen değeri.
### getAliceBlue() {#getAliceBlue--}
```
public static Color getAliceBlue()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getAntiqueWhite() {#getAntiqueWhite--}
```
public static Color getAntiqueWhite()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getAqua() {#getAqua--}
```
public static Color getAqua()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getAquamarine() {#getAquamarine--}
```
public static Color getAquamarine()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getAzure() {#getAzure--}
```
public static Color getAzure()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getB() {#getB--}
```
public byte getB()
```


Bu  com.aspose.psd.Color  yapısının mavi bileşen değerini alır.

**Returns:**
byte - Bu  com.aspose.psd.Color  nesnesinin mavi bileşen değeri.
### getBeige() {#getBeige--}
```
public static Color getBeige()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getBisque() {#getBisque--}
```
public static Color getBisque()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getBlack() {#getBlack--}
```
public static Color getBlack()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getBlanchedAlmond() {#getBlanchedAlmond--}
```
public static Color getBlanchedAlmond()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getBlue() {#getBlue--}
```
public static Color getBlue()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getBlueViolet() {#getBlueViolet--}
```
public static Color getBlueViolet()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getBrightness() {#getBrightness--}
```
public float getBrightness()
```


Bu  com.aspose.psd.Color  yapısı için hue-saturation-brightness (HSB) parlaklık değerini alır.

**Returns:**
float - Bu  com.aspose.psd.Color  nesnesinin parlaklığı. Parlaklık 0.0 ile 1.0 arasında değişir; 0.0 siyahı, 1.0 beyazı temsil eder.
### getBrown() {#getBrown--}
```
public static Color getBrown()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getBurlyWood() {#getBurlyWood--}
```
public static Color getBurlyWood()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getCadetBlue() {#getCadetBlue--}
```
public static Color getCadetBlue()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getChartreuse() {#getChartreuse--}
```
public static Color getChartreuse()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getChocolate() {#getChocolate--}
```
public static Color getChocolate()
```


Sistem tarafından tanımlanmış bir rengi alır.

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


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getCornflowerBlue() {#getCornflowerBlue--}
```
public static Color getCornflowerBlue()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getCornsilk() {#getCornsilk--}
```
public static Color getCornsilk()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getCrimson() {#getCrimson--}
```
public static Color getCrimson()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getCyan() {#getCyan--}
```
public static Color getCyan()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkBlue() {#getDarkBlue--}
```
public static Color getDarkBlue()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkCyan() {#getDarkCyan--}
```
public static Color getDarkCyan()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkGoldenrod() {#getDarkGoldenrod--}
```
public static Color getDarkGoldenrod()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkGray() {#getDarkGray--}
```
public static Color getDarkGray()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkGreen() {#getDarkGreen--}
```
public static Color getDarkGreen()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkKhaki() {#getDarkKhaki--}
```
public static Color getDarkKhaki()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkMagenta() {#getDarkMagenta--}
```
public static Color getDarkMagenta()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkOliveGreen() {#getDarkOliveGreen--}
```
public static Color getDarkOliveGreen()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkOrange() {#getDarkOrange--}
```
public static Color getDarkOrange()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkOrchid() {#getDarkOrchid--}
```
public static Color getDarkOrchid()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkRed() {#getDarkRed--}
```
public static Color getDarkRed()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkSalmon() {#getDarkSalmon--}
```
public static Color getDarkSalmon()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkSeaGreen() {#getDarkSeaGreen--}
```
public static Color getDarkSeaGreen()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkSlateBlue() {#getDarkSlateBlue--}
```
public static Color getDarkSlateBlue()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkSlateGray() {#getDarkSlateGray--}
```
public static Color getDarkSlateGray()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkTurquoise() {#getDarkTurquoise--}
```
public static Color getDarkTurquoise()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkViolet() {#getDarkViolet--}
```
public static Color getDarkViolet()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDeepPink() {#getDeepPink--}
```
public static Color getDeepPink()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDeepSkyBlue() {#getDeepSkyBlue--}
```
public static Color getDeepSkyBlue()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDimGray() {#getDimGray--}
```
public static Color getDimGray()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDodgerBlue() {#getDodgerBlue--}
```
public static Color getDodgerBlue()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getEmpty() {#getEmpty--}
```
public static Color getEmpty()
```


Boş bir  Color  alır.

**Returns:**
[Color](../../com.aspose.psd/color) - The empty  Color .
### getFirebrick() {#getFirebrick--}
```
public static Color getFirebrick()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getFloralWhite() {#getFloralWhite--}
```
public static Color getFloralWhite()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getForestGreen() {#getForestGreen--}
```
public static Color getForestGreen()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getFuchsia() {#getFuchsia--}
```
public static Color getFuchsia()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getG() {#getG--}
```
public byte getG()
```


Bu  com.aspose.psd.Color  yapısının yeşil bileşen değerini alır.

**Returns:**
byte - Bu  com.aspose.psd.Color  nesnesinin yeşil bileşen değeri.
### getGainsboro() {#getGainsboro--}
```
public static Color getGainsboro()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getGhostWhite() {#getGhostWhite--}
```
public static Color getGhostWhite()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getGold() {#getGold--}
```
public static Color getGold()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getGoldenrod() {#getGoldenrod--}
```
public static Color getGoldenrod()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getGray() {#getGray--}
```
public static Color getGray()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  structure representing a system-defined color.
### getGreen() {#getGreen--}
```
public static Color getGreen()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getGreenYellow() {#getGreenYellow--}
```
public static Color getGreenYellow()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getHoneydew() {#getHoneydew--}
```
public static Color getHoneydew()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getHotPink() {#getHotPink--}
```
public static Color getHotPink()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getHue() {#getHue--}
```
public float getHue()
```


Bu  com.aspose.psd.Color  yapısı için hue-saturation-brightness (HSB) ton değerini, derece cinsinden alır.

**Returns:**
float - Bu  com.aspose.psd.Color  nesnesinin derece cinsinden renk tonu. Renk tonu HSB renk uzayında 0.0 ile 360.0 derece arasında ölçülür.
### getIndianRed() {#getIndianRed--}
```
public static Color getIndianRed()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getIndigo() {#getIndigo--}
```
public static Color getIndigo()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getIvory() {#getIvory--}
```
public static Color getIvory()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getKhaki() {#getKhaki--}
```
public static Color getKhaki()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLavender() {#getLavender--}
```
public static Color getLavender()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLavenderBlush() {#getLavenderBlush--}
```
public static Color getLavenderBlush()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLawnGreen() {#getLawnGreen--}
```
public static Color getLawnGreen()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLemonChiffon() {#getLemonChiffon--}
```
public static Color getLemonChiffon()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightBlue() {#getLightBlue--}
```
public static Color getLightBlue()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightCoral() {#getLightCoral--}
```
public static Color getLightCoral()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightCyan() {#getLightCyan--}
```
public static Color getLightCyan()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightGoldenrodYellow() {#getLightGoldenrodYellow--}
```
public static Color getLightGoldenrodYellow()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightGray() {#getLightGray--}
```
public static Color getLightGray()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightGreen() {#getLightGreen--}
```
public static Color getLightGreen()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightPink() {#getLightPink--}
```
public static Color getLightPink()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightSalmon() {#getLightSalmon--}
```
public static Color getLightSalmon()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightSeaGreen() {#getLightSeaGreen--}
```
public static Color getLightSeaGreen()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightSkyBlue() {#getLightSkyBlue--}
```
public static Color getLightSkyBlue()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightSlateGray() {#getLightSlateGray--}
```
public static Color getLightSlateGray()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightSteelBlue() {#getLightSteelBlue--}
```
public static Color getLightSteelBlue()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightYellow() {#getLightYellow--}
```
public static Color getLightYellow()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLime() {#getLime--}
```
public static Color getLime()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLimeGreen() {#getLimeGreen--}
```
public static Color getLimeGreen()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLinen() {#getLinen--}
```
public static Color getLinen()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMagenta() {#getMagenta--}
```
public static Color getMagenta()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMaroon() {#getMaroon--}
```
public static Color getMaroon()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMediumAquamarine() {#getMediumAquamarine--}
```
public static Color getMediumAquamarine()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMediumBlue() {#getMediumBlue--}
```
public static Color getMediumBlue()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMediumOrchid() {#getMediumOrchid--}
```
public static Color getMediumOrchid()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMediumPurple() {#getMediumPurple--}
```
public static Color getMediumPurple()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMediumSeaGreen() {#getMediumSeaGreen--}
```
public static Color getMediumSeaGreen()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMediumSlateBlue() {#getMediumSlateBlue--}
```
public static Color getMediumSlateBlue()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMediumSpringGreen() {#getMediumSpringGreen--}
```
public static Color getMediumSpringGreen()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMediumTurquoise() {#getMediumTurquoise--}
```
public static Color getMediumTurquoise()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMediumVioletRed() {#getMediumVioletRed--}
```
public static Color getMediumVioletRed()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMidnightBlue() {#getMidnightBlue--}
```
public static Color getMidnightBlue()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMintCream() {#getMintCream--}
```
public static Color getMintCream()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMistyRose() {#getMistyRose--}
```
public static Color getMistyRose()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMoccasin() {#getMoccasin--}
```
public static Color getMoccasin()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getName() {#getName--}
```
public String getName()
```


Bu  com.aspose.psd.Color  adını alır.

**Returns:**
java.lang.String - Bu  com.aspose.psd.Color  nesnesinin adı.
### getNavajoWhite() {#getNavajoWhite--}
```
public static Color getNavajoWhite()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getNavy() {#getNavy--}
```
public static Color getNavy()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getOldLace() {#getOldLace--}
```
public static Color getOldLace()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getOlive() {#getOlive--}
```
public static Color getOlive()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getOliveDrab() {#getOliveDrab--}
```
public static Color getOliveDrab()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getOrange() {#getOrange--}
```
public static Color getOrange()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getOrangeRed() {#getOrangeRed--}
```
public static Color getOrangeRed()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getOrchid() {#getOrchid--}
```
public static Color getOrchid()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPaleGoldenrod() {#getPaleGoldenrod--}
```
public static Color getPaleGoldenrod()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPaleGreen() {#getPaleGreen--}
```
public static Color getPaleGreen()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPaleTurquoise() {#getPaleTurquoise--}
```
public static Color getPaleTurquoise()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPaleVioletRed() {#getPaleVioletRed--}
```
public static Color getPaleVioletRed()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPapayaWhip() {#getPapayaWhip--}
```
public static Color getPapayaWhip()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPeachPuff() {#getPeachPuff--}
```
public static Color getPeachPuff()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPeru() {#getPeru--}
```
public static Color getPeru()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPink() {#getPink--}
```
public static Color getPink()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPlum() {#getPlum--}
```
public static Color getPlum()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPowderBlue() {#getPowderBlue--}
```
public static Color getPowderBlue()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPurple() {#getPurple--}
```
public static Color getPurple()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getR() {#getR--}
```
public byte getR()
```


Bu  com.aspose.psd.Color  yapısının kırmızı bileşen değerini alır.

**Returns:**
byte - Bu  com.aspose.psd.Color  nesnesinin kırmızı bileşen değeri.
### getRed() {#getRed--}
```
public static Color getRed()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getRosyBrown() {#getRosyBrown--}
```
public static Color getRosyBrown()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getRoyalBlue() {#getRoyalBlue--}
```
public static Color getRoyalBlue()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSaddleBrown() {#getSaddleBrown--}
```
public static Color getSaddleBrown()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSalmon() {#getSalmon--}
```
public static Color getSalmon()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSandyBrown() {#getSandyBrown--}
```
public static Color getSandyBrown()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSaturation() {#getSaturation--}
```
public float getSaturation()
```


Bu  com.aspose.psd.Color  yapısı için hue-saturation-brightness (HSB) doygunluk değerini alır.

**Returns:**
float - Bu  com.aspose.psd.Color  nesnesinin doygunluğu. Doygunluk 0.0 ile 1.0 arasında değişir; 0.0 gri tonlamayı, 1.0 ise en yüksek doygunluğu temsil eder.
### getSeaGreen() {#getSeaGreen--}
```
public static Color getSeaGreen()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSeaShell() {#getSeaShell--}
```
public static Color getSeaShell()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSienna() {#getSienna--}
```
public static Color getSienna()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSilver() {#getSilver--}
```
public static Color getSilver()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSkyBlue() {#getSkyBlue--}
```
public static Color getSkyBlue()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSlateBlue() {#getSlateBlue--}
```
public static Color getSlateBlue()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSlateGray() {#getSlateGray--}
```
public static Color getSlateGray()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSnow() {#getSnow--}
```
public static Color getSnow()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSpringGreen() {#getSpringGreen--}
```
public static Color getSpringGreen()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSteelBlue() {#getSteelBlue--}
```
public static Color getSteelBlue()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getTan() {#getTan--}
```
public static Color getTan()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getTeal() {#getTeal--}
```
public static Color getTeal()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getThistle() {#getThistle--}
```
public static Color getThistle()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getTomato() {#getTomato--}
```
public static Color getTomato()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getTransparent() {#getTransparent--}
```
public static Color getTransparent()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getTurquoise() {#getTurquoise--}
```
public static Color getTurquoise()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getViolet() {#getViolet--}
```
public static Color getViolet()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getWheat() {#getWheat--}
```
public static Color getWheat()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getWhite() {#getWhite--}
```
public static Color getWhite()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getWhiteSmoke() {#getWhiteSmoke--}
```
public static Color getWhiteSmoke()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getYellow() {#getYellow--}
```
public static Color getYellow()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getYellowGreen() {#getYellowGreen--}
```
public static Color getYellowGreen()
```


Sistem tarafından tanımlanmış bir rengi alır.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Bu  com.aspose.psd.Color  yapısı için bir karma kod (hash code) döndürür.

**Returns:**
int - Bu  com.aspose.psd.Color  nesnesinin karma kodunu belirten bir tamsayı değeri.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Bu  com.aspose.psd.Color  yapısının başlatılmamış olup olmadığını gösteren bir değer alır.

**Returns:**
boolean - Bu özellik, bu renk başlatılmamışsa true döndürür; aksi takdirde false.
### isEquals(Color obj1, Color obj2) {#isEquals-com.aspose.psd.Color-com.aspose.psd.Color-}
```
public static boolean isEquals(Color obj1, Color obj2)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj1 | [Color](../../com.aspose.psd/color) |  |
| obj2 | [Color](../../com.aspose.psd/color) |  |

**Returns:**
boolean
### isKnownColor() {#isKnownColor--}
```
public boolean isKnownColor()
```


Bu  com.aspose.psd.Color  yapısının önceden tanımlı bir renk olup olmadığını gösteren bir değer alır. Önceden tanımlı renkler,  Aspose.Imaging.KnownColor  enumarasyonunun öğeleriyle temsil edilir.

**Returns:**
boolean - Bu  com.aspose.psd.Color  önceden tanımlı bir renkten,  Aspose.Imaging.Color.FromName(String)  yöntemi veya  Aspose.Imaging.Color.FromKnownColor(Aspose.Imaging.KnownColor)  yöntemi kullanılarak oluşturulduysa true; aksi takdirde false.
### isNamedColor() {#isNamedColor--}
```
public boolean isNamedColor()
```


Bu  com.aspose.psd.Color  yapısının adlandırılmış bir renk mi yoksa  Aspose.Imaging.KnownColor  enumarasyonunun bir üyesi mi olduğunu gösteren bir değer alır.

**Returns:**
boolean - Bu  com.aspose.psd.Color  Aspose.Imaging.Color.FromName(String)  yöntemi veya  Aspose.Imaging.Color.FromKnownColor(Aspose.Imaging.KnownColor)  yöntemi kullanılarak oluşturulduysa true; aksi takdirde false.
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


Belirtilen iki  com.aspose.psd.Color  yapısının eşdeğer olup olmadığını test eder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| left | [Color](../../com.aspose.psd/color) | Eşitlik operatörünün solundaki  com.aspose.psd.Color . |
| right | [Color](../../com.aspose.psd/color) | Eşitlik operatörünün sağındaki  com.aspose.psd.Color . |

**Returns:**
boolean - İki  com.aspose.psd.Color  yapısı eşitse true; aksi takdirde false.
### op_Inequality(Color left, Color right) {#op-Inequality-com.aspose.psd.Color-com.aspose.psd.Color-}
```
public static boolean op_Inequality(Color left, Color right)
```


Belirtilen iki  com.aspose.psd.Color  yapısının farklı olup olmadığını test eder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| left | [Color](../../com.aspose.psd/color) | Eşitsizlik operatörünün solundaki  com.aspose.psd.Color . |
| right | [Color](../../com.aspose.psd/color) | Eşitsizlik operatörünün sağındaki  com.aspose.psd.Color . |

**Returns:**
boolean - İki  com.aspose.psd.Color  yapısı farklıysa true; aksi takdirde false.
### toArgb() {#toArgb--}
```
public int toArgb()
```


Bu  com.aspose.psd.Color  yapısının 32-bit ARGB değerini alır.

**Returns:**
int - Bu  com.aspose.psd.Color  nesnesinin 32-bit ARGB değeri.
### toCmyk(Color pixel) {#toCmyk-com.aspose.psd.Color-}
```
public static CmykColor toCmyk(Color pixel)
```


Color'dan CmykColor'a dönüşüm. Bu yöntem kullanımdan kaldırıldı. Lütfen daha etkili  CmykColorHelper.toCmyk(Color)  yöntemini kullanın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.psd/color) | RGB formatında Color tipindeki piksel. |

**Returns:**
[CmykColor](../../com.aspose.psd/cmykcolor) - The  CmykColor .
### toCmyk(Color[] pixels) {#toCmyk-com.aspose.psd.Color---}
```
public static CmykColor[] toCmyk(Color[] pixels)
```


Color'dan CMYKColor'a dönüşüm. Bu yöntem kullanımdan kaldırıldı. Lütfen daha etkili  CmykColorHelper.toCmyk(Color[])  yöntemini kullanın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.psd/color) | RGB formatında Color tipindeki pikseller. |

**Returns:**
com.aspose.psd.CmykColor[] -  Aspose:Imaging:CmykColor[] .
### toCmykIcc(Color pixel) {#toCmykIcc-com.aspose.psd.Color-}
```
public static CmykColor toCmykIcc(Color pixel)
```


Color'dan CMYKColor'a, varsayılan profillerle icc dönüşümü kullanarak dönüşüm. Bu yöntem kullanımdan kaldırıldı. Lütfen daha etkili  CmykColorHelper.toCmykIcc(Color)  yöntemini kullanın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.psd/color) | RGB formatında Color tipindeki piksel. |

**Returns:**
[CmykColor](../../com.aspose.psd/cmykcolor) - The  CmykColor .
### toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIcc-com.aspose.psd.Color-java.io.InputStream-java.io.InputStream-}
```
public static CmykColor toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream)
```


Color'dan CMYKColor'a, varsayılan profillerle icc dönüşümü kullanarak dönüşüm. Bu yöntem kullanımdan kaldırıldı. Lütfen daha etkili  CmykColorHelper.toCmykIcc(Color, InputStream, InputStream)  yöntemini kullanın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.psd/color) | RGB formatında Color tipindeki piksel. |
| rgbIccStream | java.io.InputStream | icc rgb profilini içeren akış. |
| cmykIccStream | java.io.InputStream | icc cmyk profilini içeren akış. |

**Returns:**
[CmykColor](../../com.aspose.psd/cmykcolor) - The  CmykColor[] .
### toCmykIcc(Color[] pixels) {#toCmykIcc-com.aspose.psd.Color---}
```
public static CmykColor[] toCmykIcc(Color[] pixels)
```


Color'dan CMYKColor'a, varsayılan profillerle icc dönüşümü kullanarak dönüşüm. Bu yöntem kullanımdan kaldırıldı. Lütfen daha etkili  CmykColorHelper.toCmykIcc(Color[])  yöntemini kullanın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.psd/color) | RGB formatında Color tipindeki pikseller. |

**Returns:**
com.aspose.psd.CmykColor[] -  CmykColor[] .
### toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIcc-com.aspose.psd.Color---java.io.InputStream-java.io.InputStream-}
```
public static CmykColor[] toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)
```


Color'dan CMYKColor'a icc dönüşümü kullanarak dönüşüm. Bu yöntem kullanımdan kaldırıldı. Lütfen daha etkili  CmykColorHelper.toCmykIcc(Color[], InputStream, InputStream)  yöntemini kullanın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.psd/color) | RGB formatında Color tipindeki pikseller. |
| rgbIccStream | java.io.InputStream | icc rgb profilini içeren akış. |
| cmykIccStream | java.io.InputStream | icc cmyk profilini içeren akış. |

**Returns:**
com.aspose.psd.CmykColor[] -  CmykColor[] .
### toCmykIcc_internalized(Color pixel, System.IO.Stream rgbIccStream, System.IO.Stream cmykIccStream) {#toCmykIcc-internalized-com.aspose.psd.Color-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-}
```
public static CmykColor toCmykIcc_internalized(Color pixel, System.IO.Stream rgbIccStream, System.IO.Stream cmykIccStream)
```




**Parameters:**
| Parametre | Tür | Açıklama |
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
| Parametre | Tür | Açıklama |
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


Bu  com.aspose.psd.Color  yapısının  Aspose.Imaging.KnownColor  değerini alır.

**Returns:**
int -  Aspose.Imaging.KnownColor  enumarasyonunun bir öğesi, eğer  com.aspose.psd.Color  önceden tanımlı bir renkten  Aspose.Imaging.Color.FromName(String)  yöntemi veya  Aspose.Imaging.Color.FromKnownColor(Aspose.Imaging.KnownColor)  yöntemi kullanılarak oluşturulmuşsa; aksi takdirde 0.
### toString() {#toString--}
```
public String toString()
```


Bu  com.aspose.psd.Color  yapısını insan tarafından okunabilir bir dizeye dönüştürür.

**Returns:**
java.lang.String - Bu com.aspose.psd.Color'ın adı olan bir dizedir, eğer com.aspose.psd.Color önceden tanımlı bir renkten Aspose.Imaging.Color.FromName(String) yöntemi ya da Aspose.Imaging.Color.FromKnownColor(Aspose.Imaging.KnownColor) yöntemi kullanılarak oluşturulmuşsa; aksi takdirde, ARGB bileşen adları ve değerlerinden oluşan bir dizedir.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

