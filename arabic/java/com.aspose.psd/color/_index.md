---
title: "اللون"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "لون البكسل."
type: docs
weight: 19
url: /ar/java/com.aspose.psd/color/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class Color extends Struct<Color>
```

لون البكسل.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [Color()](#Color--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(Color that)](#CloneTo-com.aspose.psd.Color-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | يفحص ما إذا كان الكائن المحدد هو بنية  com.aspose.psd.Color  ومكافئ لهذه البنية  com.aspose.psd.Color . |
| [fromArgb(byte red, byte green, byte blue)](#fromArgb-byte-byte-byte-) | ينشئ بنية  com.aspose.psd.Color  من قيم اللون ذات 8 بت المحددة (أحمر، أخضر، وأزرق). |
| [fromArgb(byte alpha, byte red, byte green, byte blue)](#fromArgb-byte-byte-byte-byte-) | ينشئ بنية  com.aspose.psd.Color  من القيم الأربعة لمكوّن ARGB (ألفا، أحمر، أخضر، وأزرق). |
| [fromArgb(int argb)](#fromArgb-int-) | ينشئ بنية  com.aspose.psd.Color  من قيمة ARGB ذات 32 بت. |
| [fromArgb(int alpha, Color baseColor)](#fromArgb-int-com.aspose.psd.Color-) | ينشئ بنية  com.aspose.psd.Color  من بنية  com.aspose.psd.Color  المحددة، ولكن مع قيمة ألفا الجديدة المحددة. |
| [fromArgb(int red, int green, int blue)](#fromArgb-int-int-int-) | ينشئ بنية  com.aspose.psd.Color  من قيم اللون ذات 8 بت المحددة (أحمر، أخضر، وأزرق). |
| [fromArgb(int alpha, int red, int green, int blue)](#fromArgb-int-int-int-int-) | ينشئ بنية  com.aspose.psd.Color  من القيم الأربعة لمكوّن ARGB (ألفا، أحمر، أخضر، وأزرق). |
| [fromKnownColor(int color)](#fromKnownColor-int-) | ينشئ بنية  com.aspose.psd.Color  من اللون المحدد مسبقًا. |
| [fromName(String name)](#fromName-java.lang.String-) | ينشئ بنية  com.aspose.psd.Color  من الاسم المحدد للون مسبقًا. |
| [getA()](#getA--) | يحصل على قيمة مكوّن الألفا لهذه بنية  com.aspose.psd.Color . |
| [getAliceBlue()](#getAliceBlue--) | يحصل على لون معرف من النظام. |
| [getAntiqueWhite()](#getAntiqueWhite--) | يحصل على لون معرف من النظام. |
| [getAqua()](#getAqua--) | يحصل على لون معرف من النظام. |
| [getAquamarine()](#getAquamarine--) | يحصل على لون معرف من النظام. |
| [getAzure()](#getAzure--) | يحصل على لون معرف من النظام. |
| [getB()](#getB--) | يحصل على قيمة المكوّن الأزرق لهذا  com.aspose.psd.Color  الهيكل. |
| [getBeige()](#getBeige--) | يحصل على لون معرف من النظام. |
| [getBisque()](#getBisque--) | يحصل على لون معرف من النظام. |
| [getBlack()](#getBlack--) | يحصل على لون معرف من النظام. |
| [getBlanchedAlmond()](#getBlanchedAlmond--) | يحصل على لون معرف من النظام. |
| [getBlue()](#getBlue--) | يحصل على لون معرف من النظام. |
| [getBlueViolet()](#getBlueViolet--) | يحصل على لون معرف من النظام. |
| [getBrightness()](#getBrightness--) | يحصل على قيمة السطوع في نظام اللون (HSB) لهذا  com.aspose.psd.Color  الهيكل. |
| [getBrown()](#getBrown--) | يحصل على لون معرف من النظام. |
| [getBurlyWood()](#getBurlyWood--) | يحصل على لون معرف من النظام. |
| [getCadetBlue()](#getCadetBlue--) | يحصل على لون معرف من النظام. |
| [getChartreuse()](#getChartreuse--) | يحصل على لون معرف من النظام. |
| [getChocolate()](#getChocolate--) | يحصل على لون معرف من النظام. |
| [getClass()](#getClass--) |  |
| [getCoral()](#getCoral--) | يحصل على لون معرف من النظام. |
| [getCornflowerBlue()](#getCornflowerBlue--) | يحصل على لون معرف من النظام. |
| [getCornsilk()](#getCornsilk--) | يحصل على لون معرف من النظام. |
| [getCrimson()](#getCrimson--) | يحصل على لون معرف من النظام. |
| [getCyan()](#getCyan--) | يحصل على لون معرف من النظام. |
| [getDarkBlue()](#getDarkBlue--) | يحصل على لون معرف من النظام. |
| [getDarkCyan()](#getDarkCyan--) | يحصل على لون معرف من النظام. |
| [getDarkGoldenrod()](#getDarkGoldenrod--) | يحصل على لون معرف من النظام. |
| [getDarkGray()](#getDarkGray--) | يحصل على لون معرف من النظام. |
| [getDarkGreen()](#getDarkGreen--) | يحصل على لون معرف من النظام. |
| [getDarkKhaki()](#getDarkKhaki--) | يحصل على لون معرف من النظام. |
| [getDarkMagenta()](#getDarkMagenta--) | يحصل على لون معرف من النظام. |
| [getDarkOliveGreen()](#getDarkOliveGreen--) | يحصل على لون معرف من النظام. |
| [getDarkOrange()](#getDarkOrange--) | يحصل على لون معرف من النظام. |
| [getDarkOrchid()](#getDarkOrchid--) | يحصل على لون معرف من النظام. |
| [getDarkRed()](#getDarkRed--) | يحصل على لون معرف من النظام. |
| [getDarkSalmon()](#getDarkSalmon--) | يحصل على لون معرف من النظام. |
| [getDarkSeaGreen()](#getDarkSeaGreen--) | يحصل على لون معرف من النظام. |
| [getDarkSlateBlue()](#getDarkSlateBlue--) | يحصل على لون معرف من النظام. |
| [getDarkSlateGray()](#getDarkSlateGray--) | يحصل على لون معرف من النظام. |
| [getDarkTurquoise()](#getDarkTurquoise--) | يحصل على لون معرف من النظام. |
| [getDarkViolet()](#getDarkViolet--) | يحصل على لون معرف من النظام. |
| [getDeepPink()](#getDeepPink--) | يحصل على لون معرف من النظام. |
| [getDeepSkyBlue()](#getDeepSkyBlue--) | يحصل على لون معرف من النظام. |
| [getDimGray()](#getDimGray--) | يحصل على لون معرف من النظام. |
| [getDodgerBlue()](#getDodgerBlue--) | يحصل على لون معرف من النظام. |
| [getEmpty()](#getEmpty--) | يحصل على لون فارغ  Color . |
| [getFirebrick()](#getFirebrick--) | يحصل على لون معرف من النظام. |
| [getFloralWhite()](#getFloralWhite--) | يحصل على لون معرف من النظام. |
| [getForestGreen()](#getForestGreen--) | يحصل على لون معرف من النظام. |
| [getFuchsia()](#getFuchsia--) | يحصل على لون معرف من النظام. |
| [getG()](#getG--) | يحصل على قيمة المكوّن الأخضر لهذا  com.aspose.psd.Color  الهيكل. |
| [getGainsboro()](#getGainsboro--) | يحصل على لون معرف من النظام. |
| [getGhostWhite()](#getGhostWhite--) | يحصل على لون معرف من النظام. |
| [getGold()](#getGold--) | يحصل على لون معرف من النظام. |
| [getGoldenrod()](#getGoldenrod--) | يحصل على لون معرف من النظام. |
| [getGray()](#getGray--) | يحصل على لون معرف من النظام. |
| [getGreen()](#getGreen--) | يحصل على لون معرف من النظام. |
| [getGreenYellow()](#getGreenYellow--) | يحصل على لون معرف من النظام. |
| [getHoneydew()](#getHoneydew--) | يحصل على لون معرف من النظام. |
| [getHotPink()](#getHotPink--) | يحصل على لون معرف من النظام. |
| [getHue()](#getHue--) | يحصل على قيمة درجة اللون (HSB) بالدرجات لهذا  com.aspose.psd.Color  الهيكل. |
| [getIndianRed()](#getIndianRed--) | يحصل على لون معرف من النظام. |
| [getIndigo()](#getIndigo--) | يحصل على لون معرف من النظام. |
| [getIvory()](#getIvory--) | يحصل على لون معرف من النظام. |
| [getKhaki()](#getKhaki--) | يحصل على لون معرف من النظام. |
| [getLavender()](#getLavender--) | يحصل على لون معرف من النظام. |
| [getLavenderBlush()](#getLavenderBlush--) | يحصل على لون معرف من النظام. |
| [getLawnGreen()](#getLawnGreen--) | يحصل على لون معرف من النظام. |
| [getLemonChiffon()](#getLemonChiffon--) | يحصل على لون معرف من النظام. |
| [getLightBlue()](#getLightBlue--) | يحصل على لون معرف من النظام. |
| [getLightCoral()](#getLightCoral--) | يحصل على لون معرف من النظام. |
| [getLightCyan()](#getLightCyan--) | يحصل على لون معرف من النظام. |
| [getLightGoldenrodYellow()](#getLightGoldenrodYellow--) | يحصل على لون معرف من النظام. |
| [getLightGray()](#getLightGray--) | يحصل على لون معرف من النظام. |
| [getLightGreen()](#getLightGreen--) | يحصل على لون معرف من النظام. |
| [getLightPink()](#getLightPink--) | يحصل على لون معرف من النظام. |
| [getLightSalmon()](#getLightSalmon--) | يحصل على لون معرف من النظام. |
| [getLightSeaGreen()](#getLightSeaGreen--) | يحصل على لون معرف من النظام. |
| [getLightSkyBlue()](#getLightSkyBlue--) | يحصل على لون معرف من النظام. |
| [getLightSlateGray()](#getLightSlateGray--) | يحصل على لون معرف من النظام. |
| [getLightSteelBlue()](#getLightSteelBlue--) | يحصل على لون معرف من النظام. |
| [getLightYellow()](#getLightYellow--) | يحصل على لون معرف من النظام. |
| [getLime()](#getLime--) | يحصل على لون معرف من النظام. |
| [getLimeGreen()](#getLimeGreen--) | يحصل على لون معرف من النظام. |
| [getLinen()](#getLinen--) | يحصل على لون معرف من النظام. |
| [getMagenta()](#getMagenta--) | يحصل على لون معرف من النظام. |
| [getMaroon()](#getMaroon--) | يحصل على لون معرف من النظام. |
| [getMediumAquamarine()](#getMediumAquamarine--) | يحصل على لون معرف من النظام. |
| [getMediumBlue()](#getMediumBlue--) | يحصل على لون معرف من النظام. |
| [getMediumOrchid()](#getMediumOrchid--) | يحصل على لون معرف من النظام. |
| [getMediumPurple()](#getMediumPurple--) | يحصل على لون معرف من النظام. |
| [getMediumSeaGreen()](#getMediumSeaGreen--) | يحصل على لون معرف من النظام. |
| [getMediumSlateBlue()](#getMediumSlateBlue--) | يحصل على لون معرف من النظام. |
| [getMediumSpringGreen()](#getMediumSpringGreen--) | يحصل على لون معرف من النظام. |
| [getMediumTurquoise()](#getMediumTurquoise--) | يحصل على لون معرف من النظام. |
| [getMediumVioletRed()](#getMediumVioletRed--) | يحصل على لون معرف من النظام. |
| [getMidnightBlue()](#getMidnightBlue--) | يحصل على لون معرف من النظام. |
| [getMintCream()](#getMintCream--) | يحصل على لون معرف من النظام. |
| [getMistyRose()](#getMistyRose--) | يحصل على لون معرف من النظام. |
| [getMoccasin()](#getMoccasin--) | يحصل على لون معرف من النظام. |
| [getName()](#getName--) | يحصل على اسم هذا  com.aspose.psd.Color . |
| [getNavajoWhite()](#getNavajoWhite--) | يحصل على لون معرف من النظام. |
| [getNavy()](#getNavy--) | يحصل على لون معرف من النظام. |
| [getOldLace()](#getOldLace--) | يحصل على لون معرف من النظام. |
| [getOlive()](#getOlive--) | يحصل على لون معرف من النظام. |
| [getOliveDrab()](#getOliveDrab--) | يحصل على لون معرف من النظام. |
| [getOrange()](#getOrange--) | يحصل على لون معرف من النظام. |
| [getOrangeRed()](#getOrangeRed--) | يحصل على لون معرف من النظام. |
| [getOrchid()](#getOrchid--) | يحصل على لون معرف من النظام. |
| [getPaleGoldenrod()](#getPaleGoldenrod--) | يحصل على لون معرف من النظام. |
| [getPaleGreen()](#getPaleGreen--) | يحصل على لون معرف من النظام. |
| [getPaleTurquoise()](#getPaleTurquoise--) | يحصل على لون معرف من النظام. |
| [getPaleVioletRed()](#getPaleVioletRed--) | يحصل على لون معرف من النظام. |
| [getPapayaWhip()](#getPapayaWhip--) | يحصل على لون معرف من النظام. |
| [getPeachPuff()](#getPeachPuff--) | يحصل على لون معرف من النظام. |
| [getPeru()](#getPeru--) | يحصل على لون معرف من النظام. |
| [getPink()](#getPink--) | يحصل على لون معرف من النظام. |
| [getPlum()](#getPlum--) | يحصل على لون معرف من النظام. |
| [getPowderBlue()](#getPowderBlue--) | يحصل على لون معرف من النظام. |
| [getPurple()](#getPurple--) | يحصل على لون معرف من النظام. |
| [getR()](#getR--) | يحصل على قيمة المكوّن الأحمر لهذا  com.aspose.psd.Color  الهيكل. |
| [getRed()](#getRed--) | يحصل على لون معرف من النظام. |
| [getRosyBrown()](#getRosyBrown--) | يحصل على لون معرف من النظام. |
| [getRoyalBlue()](#getRoyalBlue--) | يحصل على لون معرف من النظام. |
| [getSaddleBrown()](#getSaddleBrown--) | يحصل على لون معرف من النظام. |
| [getSalmon()](#getSalmon--) | يحصل على لون معرف من النظام. |
| [getSandyBrown()](#getSandyBrown--) | يحصل على لون معرف من النظام. |
| [getSaturation()](#getSaturation--) | يحصل على قيمة التشبع في نظام اللون (HSB) لهذا  com.aspose.psd.Color  الهيكل. |
| [getSeaGreen()](#getSeaGreen--) | يحصل على لون معرف من النظام. |
| [getSeaShell()](#getSeaShell--) | يحصل على لون معرف من النظام. |
| [getSienna()](#getSienna--) | يحصل على لون معرف من النظام. |
| [getSilver()](#getSilver--) | يحصل على لون معرف من النظام. |
| [getSkyBlue()](#getSkyBlue--) | يحصل على لون معرف من النظام. |
| [getSlateBlue()](#getSlateBlue--) | يحصل على لون معرف من النظام. |
| [getSlateGray()](#getSlateGray--) | يحصل على لون معرف من النظام. |
| [getSnow()](#getSnow--) | يحصل على لون معرف من النظام. |
| [getSpringGreen()](#getSpringGreen--) | يحصل على لون معرف من النظام. |
| [getSteelBlue()](#getSteelBlue--) | يحصل على لون معرف من النظام. |
| [getTan()](#getTan--) | يحصل على لون معرف من النظام. |
| [getTeal()](#getTeal--) | يحصل على لون معرف من النظام. |
| [getThistle()](#getThistle--) | يحصل على لون معرف من النظام. |
| [getTomato()](#getTomato--) | يحصل على لون معرف من النظام. |
| [getTransparent()](#getTransparent--) | يحصل على لون معرف من النظام. |
| [getTurquoise()](#getTurquoise--) | يحصل على لون معرف من النظام. |
| [getViolet()](#getViolet--) | يحصل على لون معرف من النظام. |
| [getWheat()](#getWheat--) | يحصل على لون معرف من النظام. |
| [getWhite()](#getWhite--) | يحصل على لون معرف من النظام. |
| [getWhiteSmoke()](#getWhiteSmoke--) | يحصل على لون معرف من النظام. |
| [getYellow()](#getYellow--) | يحصل على لون معرف من النظام. |
| [getYellowGreen()](#getYellowGreen--) | يحصل على لون معرف من النظام. |
| [hashCode()](#hashCode--) | يعيد رمز تجزئة لهذا  com.aspose.psd.Color  الهيكل. |
| [isEmpty()](#isEmpty--) | يحصل على قيمة تشير إلى ما إذا كان هذا  com.aspose.psd.Color  الهيكل غير مهيأ. |
| [isEquals(Color obj1, Color obj2)](#isEquals-com.aspose.psd.Color-com.aspose.psd.Color-) |  |
| [isKnownColor()](#isKnownColor--) | يحصل على قيمة تشير إلى ما إذا كان هذا  com.aspose.psd.Color  الهيكل لونًا مسبق التعريف. |
| [isNamedColor()](#isNamedColor--) | يحصل على قيمة تشير إلى ما إذا كان هذا  com.aspose.psd.Color  الهيكل لونًا مسمى أو عضوًا في تعداد  Aspose.Imaging.KnownColor . |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Equality(Color left, Color right)](#op-Equality-com.aspose.psd.Color-com.aspose.psd.Color-) | يفحص ما إذا كان هيكلا  com.aspose.psd.Color  المحددين متكافئين. |
| [op_Inequality(Color left, Color right)](#op-Inequality-com.aspose.psd.Color-com.aspose.psd.Color-) | يفحص ما إذا كان هيكلا  com.aspose.psd.Color  المحددين مختلفين. |
| [toArgb()](#toArgb--) | يحصل على قيمة ARGB 32‑بت لهذا  com.aspose.psd.Color  الهيكل. |
| [toCmyk(Color pixel)](#toCmyk-com.aspose.psd.Color-) | التحويل من Color إلى CmykColor. |
| [toCmyk(Color[] pixels)](#toCmyk-com.aspose.psd.Color---) | التحويل من Color إلى CMYKColor. |
| [toCmykIcc(Color pixel)](#toCmykIcc-com.aspose.psd.Color-) | التحويل من Color إلى CMYKColor باستخدام تحويل icc مع ملفات التعريف الافتراضية. |
| [toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIcc-com.aspose.psd.Color-java.io.InputStream-java.io.InputStream-) | التحويل من Color إلى CMYKColor باستخدام تحويل icc مع ملفات التعريف الافتراضية. |
| [toCmykIcc(Color[] pixels)](#toCmykIcc-com.aspose.psd.Color---) | التحويل من Color إلى CMYKColor باستخدام تحويل icc مع ملفات التعريف الافتراضية. |
| [toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIcc-com.aspose.psd.Color---java.io.InputStream-java.io.InputStream-) | التحويل من Color إلى CMYKColor باستخدام تحويل icc. |
| [toCmykIcc_internalized(Color pixel, System.IO.Stream rgbIccStream, System.IO.Stream cmykIccStream)](#toCmykIcc-internalized-com.aspose.psd.Color-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-) |  |
| [toCmykIcc_internalized(Color[] pixels, System.IO.Stream rgbIccStream, System.IO.Stream cmykIccStream)](#toCmykIcc-internalized-com.aspose.psd.Color---com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-) |  |
| [toKnownColor()](#toKnownColor--) | يحصل على قيمة  Aspose.Imaging.KnownColor  لهذا  com.aspose.psd.Color  الهيكل. |
| [toString()](#toString--) | يحوّل هذا  com.aspose.psd.Color  الهيكل إلى سلسلة قابلة للقراءة من قبل الإنسان. |
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
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(Color that) {#CloneTo-com.aspose.psd.Color-}
```
public void CloneTo(Color that)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| that | [Color](../../com.aspose.psd/color) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


يفحص ما إذا كان الكائن المحدد هو بنية  com.aspose.psd.Color  ومكافئ لهذه البنية  com.aspose.psd.Color .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | الكائن للاختبار. |

**Returns:**
منطقي - صحيح إذا كان  obj  هو هيكل  com.aspose.psd.Color  مكافئ لهذا  com.aspose.psd.Color  الهيكل؛ وإلا، خطأ.
### fromArgb(byte red, byte green, byte blue) {#fromArgb-byte-byte-byte-}
```
public static Color fromArgb(byte red, byte green, byte blue)
```


ينشئ هيكل  com.aspose.psd.Color  من قيم اللون 8‑بت المحددة (الأحمر، الأخضر، والأزرق). قيمة ألفا هي ضمنيًا 255 (معتمة بالكامل). على الرغم من أن هذه الطريقة تسمح بتمرير قيمة 32‑بت لكل مكوّن لون، فإن قيمة كل مكوّن محدودة بـ 8‑بت.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| أحمر | byte | قيمة المكوّن الأحمر للـ  com.aspose.psd.Color  الجديد. القيم الصالحة هي من 0 إلى 255. |
| أخضر | byte | قيمة مكوّن اللون الأخضر للـ com.aspose.psd.Color الجديد. القيم الصالحة هي من 0 إلى 255. |
| أزرق | byte | قيمة مكوّن اللون الأزرق للـ com.aspose.psd.Color الجديد. القيم الصالحة هي من 0 إلى 255. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  com.aspose.psd.Color  that this method creates.
### fromArgb(byte alpha, byte red, byte green, byte blue) {#fromArgb-byte-byte-byte-byte-}
```
public static Color fromArgb(byte alpha, byte red, byte green, byte blue)
```


ينشئ بنية com.aspose.psd.Color من القيم الأربعة لمكوّنات ARGB (ألفا، أحمر، أخضر، وأزرق). على الرغم من أن هذه الطريقة تسمح بتمرير قيمة 32-بت لكل مكوّن، فإن قيمة كل مكوّن محدودة بـ 8 بت.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| ألفا | byte | مكوّن الألفا. القيم الصالحة هي من 0 إلى 255. |
| أحمر | byte | مكوّن الأحمر. القيم الصالحة هي من 0 إلى 255. |
| أخضر | byte | مكوّن الأخضر. القيم الصالحة هي من 0 إلى 255. |
| أزرق | byte | مكوّن الأزرق. القيم الصالحة هي من 0 إلى 255. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  com.aspose.psd.Color  that this method creates.
### fromArgb(int argb) {#fromArgb-int-}
```
public static Color fromArgb(int argb)
```


ينشئ بنية  com.aspose.psd.Color  من قيمة ARGB ذات 32 بت.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| argb | int | قيمة تحدد قيمة ARGB ذات 32-بت. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  com.aspose.psd.Color  structure that this method creates.
### fromArgb(int alpha, Color baseColor) {#fromArgb-int-com.aspose.psd.Color-}
```
public static Color fromArgb(int alpha, Color baseColor)
```


ينشئ بنية com.aspose.psd.Color من بنية com.aspose.psd.Color المحددة، ولكن مع قيمة ألفا الجديدة المحددة. على الرغم من أن هذه الطريقة تسمح بتمرير قيمة 32-بت لقيمة الألفا، فإن القيمة محدودة بـ 8 بت.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| ألفا | int | قيمة الألفا للـ com.aspose.psd.Color الجديد. القيم الصالحة هي من 0 إلى 255. |
| baseColor | [Color](../../com.aspose.psd/color) | الـ com.aspose.psd.Color الذي يُنشأ منه الـ com.aspose.psd.Color الجديد. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  com.aspose.psd.Color  that this method creates.
### fromArgb(int red, int green, int blue) {#fromArgb-int-int-int-}
```
public static Color fromArgb(int red, int green, int blue)
```


ينشئ هيكل  com.aspose.psd.Color  من قيم اللون 8‑بت المحددة (الأحمر، الأخضر، والأزرق). قيمة ألفا هي ضمنيًا 255 (معتمة بالكامل). على الرغم من أن هذه الطريقة تسمح بتمرير قيمة 32‑بت لكل مكوّن لون، فإن قيمة كل مكوّن محدودة بـ 8‑بت.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| أحمر | int | قيمة المكوّن الأحمر للـ  com.aspose.psd.Color  الجديد. القيم الصالحة هي من 0 إلى 255. |
| أخضر | int | قيمة مكوّن اللون الأخضر للـ com.aspose.psd.Color الجديد. القيم الصالحة هي من 0 إلى 255. |
| أزرق | int | قيمة مكوّن اللون الأزرق للـ com.aspose.psd.Color الجديد. القيم الصالحة هي من 0 إلى 255. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  com.aspose.psd.Color  that this method creates.
### fromArgb(int alpha, int red, int green, int blue) {#fromArgb-int-int-int-int-}
```
public static Color fromArgb(int alpha, int red, int green, int blue)
```


ينشئ بنية com.aspose.psd.Color من القيم الأربعة لمكوّنات ARGB (ألفا، أحمر، أخضر، وأزرق). على الرغم من أن هذه الطريقة تسمح بتمرير قيمة 32-بت لكل مكوّن، فإن قيمة كل مكوّن محدودة بـ 8 بت.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| ألفا | int | مكوّن الألفا. القيم الصالحة هي من 0 إلى 255. |
| أحمر | int | مكوّن الأحمر. القيم الصالحة هي من 0 إلى 255. |
| أخضر | int | مكوّن الأخضر. القيم الصالحة هي من 0 إلى 255. |
| أزرق | int | مكوّن الأزرق. القيم الصالحة هي من 0 إلى 255. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  com.aspose.psd.Color  that this method creates.
### fromKnownColor(int color) {#fromKnownColor-int-}
```
public static Color fromKnownColor(int color)
```


ينشئ بنية  com.aspose.psd.Color  من اللون المحدد مسبقًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| لون | int | عنصر من تعداد Aspose.Imaging.KnownColor. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  com.aspose.psd.Color  that this method creates.
### fromName(String name) {#fromName-java.lang.String-}
```
public static Color fromName(String name)
```


ينشئ بنية  com.aspose.psd.Color  من الاسم المحدد للون مسبقًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الاسم | java.lang.String | سلسلة تمثل اسم لون مُعرّف مسبقًا. الأسماء الصالحة هي نفسها أسماء عناصر تعداد Aspose.Imaging.KnownColor. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  com.aspose.psd.Color  that this method creates.
### getA() {#getA--}
```
public byte getA()
```


يحصل على قيمة مكوّن الألفا لهذه بنية  com.aspose.psd.Color .

**Returns:**
byte - قيمة مكوّن الألفا لهذا com.aspose.psd.Color.
### getAliceBlue() {#getAliceBlue--}
```
public static Color getAliceBlue()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getAntiqueWhite() {#getAntiqueWhite--}
```
public static Color getAntiqueWhite()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getAqua() {#getAqua--}
```
public static Color getAqua()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getAquamarine() {#getAquamarine--}
```
public static Color getAquamarine()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getAzure() {#getAzure--}
```
public static Color getAzure()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getB() {#getB--}
```
public byte getB()
```


يحصل على قيمة المكوّن الأزرق لهذا  com.aspose.psd.Color  الهيكل.

**Returns:**
byte - قيمة مكوّن الأزرق لهذا com.aspose.psd.Color.
### getBeige() {#getBeige--}
```
public static Color getBeige()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getBisque() {#getBisque--}
```
public static Color getBisque()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getBlack() {#getBlack--}
```
public static Color getBlack()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getBlanchedAlmond() {#getBlanchedAlmond--}
```
public static Color getBlanchedAlmond()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getBlue() {#getBlue--}
```
public static Color getBlue()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getBlueViolet() {#getBlueViolet--}
```
public static Color getBlueViolet()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getBrightness() {#getBrightness--}
```
public float getBrightness()
```


يحصل على قيمة السطوع في نظام اللون (HSB) لهذا  com.aspose.psd.Color  الهيكل.

**Returns:**
float - سطوع هذا com.aspose.psd.Color. يتراوح السطوع من 0.0 إلى 1.0، حيث 0.0 يمثل الأسود و1.0 يمثل الأبيض.
### getBrown() {#getBrown--}
```
public static Color getBrown()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getBurlyWood() {#getBurlyWood--}
```
public static Color getBurlyWood()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getCadetBlue() {#getCadetBlue--}
```
public static Color getCadetBlue()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getChartreuse() {#getChartreuse--}
```
public static Color getChartreuse()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getChocolate() {#getChocolate--}
```
public static Color getChocolate()
```


يحصل على لون معرف من النظام.

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


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getCornflowerBlue() {#getCornflowerBlue--}
```
public static Color getCornflowerBlue()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getCornsilk() {#getCornsilk--}
```
public static Color getCornsilk()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getCrimson() {#getCrimson--}
```
public static Color getCrimson()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getCyan() {#getCyan--}
```
public static Color getCyan()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkBlue() {#getDarkBlue--}
```
public static Color getDarkBlue()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkCyan() {#getDarkCyan--}
```
public static Color getDarkCyan()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkGoldenrod() {#getDarkGoldenrod--}
```
public static Color getDarkGoldenrod()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkGray() {#getDarkGray--}
```
public static Color getDarkGray()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkGreen() {#getDarkGreen--}
```
public static Color getDarkGreen()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkKhaki() {#getDarkKhaki--}
```
public static Color getDarkKhaki()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkMagenta() {#getDarkMagenta--}
```
public static Color getDarkMagenta()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkOliveGreen() {#getDarkOliveGreen--}
```
public static Color getDarkOliveGreen()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkOrange() {#getDarkOrange--}
```
public static Color getDarkOrange()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkOrchid() {#getDarkOrchid--}
```
public static Color getDarkOrchid()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkRed() {#getDarkRed--}
```
public static Color getDarkRed()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkSalmon() {#getDarkSalmon--}
```
public static Color getDarkSalmon()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkSeaGreen() {#getDarkSeaGreen--}
```
public static Color getDarkSeaGreen()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkSlateBlue() {#getDarkSlateBlue--}
```
public static Color getDarkSlateBlue()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkSlateGray() {#getDarkSlateGray--}
```
public static Color getDarkSlateGray()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkTurquoise() {#getDarkTurquoise--}
```
public static Color getDarkTurquoise()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkViolet() {#getDarkViolet--}
```
public static Color getDarkViolet()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDeepPink() {#getDeepPink--}
```
public static Color getDeepPink()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDeepSkyBlue() {#getDeepSkyBlue--}
```
public static Color getDeepSkyBlue()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDimGray() {#getDimGray--}
```
public static Color getDimGray()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDodgerBlue() {#getDodgerBlue--}
```
public static Color getDodgerBlue()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getEmpty() {#getEmpty--}
```
public static Color getEmpty()
```


يحصل على لون فارغ  Color .

**Returns:**
[Color](../../com.aspose.psd/color) - The empty  Color .
### getFirebrick() {#getFirebrick--}
```
public static Color getFirebrick()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getFloralWhite() {#getFloralWhite--}
```
public static Color getFloralWhite()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getForestGreen() {#getForestGreen--}
```
public static Color getForestGreen()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getFuchsia() {#getFuchsia--}
```
public static Color getFuchsia()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getG() {#getG--}
```
public byte getG()
```


يحصل على قيمة المكوّن الأخضر لهذا  com.aspose.psd.Color  الهيكل.

**Returns:**
byte - قيمة مكوّن الأخضر لهذا com.aspose.psd.Color.
### getGainsboro() {#getGainsboro--}
```
public static Color getGainsboro()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getGhostWhite() {#getGhostWhite--}
```
public static Color getGhostWhite()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getGold() {#getGold--}
```
public static Color getGold()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getGoldenrod() {#getGoldenrod--}
```
public static Color getGoldenrod()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getGray() {#getGray--}
```
public static Color getGray()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  structure representing a system-defined color.
### getGreen() {#getGreen--}
```
public static Color getGreen()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getGreenYellow() {#getGreenYellow--}
```
public static Color getGreenYellow()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getHoneydew() {#getHoneydew--}
```
public static Color getHoneydew()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getHotPink() {#getHotPink--}
```
public static Color getHotPink()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getHue() {#getHue--}
```
public float getHue()
```


يحصل على قيمة درجة اللون (HSB) بالدرجات لهذا  com.aspose.psd.Color  الهيكل.

**Returns:**
float - درجة اللون (Hue) لهذا com.aspose.psd.Color بالدرجات. يتم قياس اللون بالدرجات، ويتراوح من 0.0 إلى 360.0 في مساحة اللون HSB.
### getIndianRed() {#getIndianRed--}
```
public static Color getIndianRed()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getIndigo() {#getIndigo--}
```
public static Color getIndigo()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getIvory() {#getIvory--}
```
public static Color getIvory()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getKhaki() {#getKhaki--}
```
public static Color getKhaki()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLavender() {#getLavender--}
```
public static Color getLavender()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLavenderBlush() {#getLavenderBlush--}
```
public static Color getLavenderBlush()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLawnGreen() {#getLawnGreen--}
```
public static Color getLawnGreen()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLemonChiffon() {#getLemonChiffon--}
```
public static Color getLemonChiffon()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightBlue() {#getLightBlue--}
```
public static Color getLightBlue()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightCoral() {#getLightCoral--}
```
public static Color getLightCoral()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightCyan() {#getLightCyan--}
```
public static Color getLightCyan()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightGoldenrodYellow() {#getLightGoldenrodYellow--}
```
public static Color getLightGoldenrodYellow()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightGray() {#getLightGray--}
```
public static Color getLightGray()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightGreen() {#getLightGreen--}
```
public static Color getLightGreen()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightPink() {#getLightPink--}
```
public static Color getLightPink()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightSalmon() {#getLightSalmon--}
```
public static Color getLightSalmon()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightSeaGreen() {#getLightSeaGreen--}
```
public static Color getLightSeaGreen()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightSkyBlue() {#getLightSkyBlue--}
```
public static Color getLightSkyBlue()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightSlateGray() {#getLightSlateGray--}
```
public static Color getLightSlateGray()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightSteelBlue() {#getLightSteelBlue--}
```
public static Color getLightSteelBlue()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightYellow() {#getLightYellow--}
```
public static Color getLightYellow()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLime() {#getLime--}
```
public static Color getLime()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLimeGreen() {#getLimeGreen--}
```
public static Color getLimeGreen()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLinen() {#getLinen--}
```
public static Color getLinen()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMagenta() {#getMagenta--}
```
public static Color getMagenta()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMaroon() {#getMaroon--}
```
public static Color getMaroon()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMediumAquamarine() {#getMediumAquamarine--}
```
public static Color getMediumAquamarine()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMediumBlue() {#getMediumBlue--}
```
public static Color getMediumBlue()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMediumOrchid() {#getMediumOrchid--}
```
public static Color getMediumOrchid()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMediumPurple() {#getMediumPurple--}
```
public static Color getMediumPurple()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMediumSeaGreen() {#getMediumSeaGreen--}
```
public static Color getMediumSeaGreen()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMediumSlateBlue() {#getMediumSlateBlue--}
```
public static Color getMediumSlateBlue()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMediumSpringGreen() {#getMediumSpringGreen--}
```
public static Color getMediumSpringGreen()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMediumTurquoise() {#getMediumTurquoise--}
```
public static Color getMediumTurquoise()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMediumVioletRed() {#getMediumVioletRed--}
```
public static Color getMediumVioletRed()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMidnightBlue() {#getMidnightBlue--}
```
public static Color getMidnightBlue()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMintCream() {#getMintCream--}
```
public static Color getMintCream()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMistyRose() {#getMistyRose--}
```
public static Color getMistyRose()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMoccasin() {#getMoccasin--}
```
public static Color getMoccasin()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getName() {#getName--}
```
public String getName()
```


يحصل على اسم هذا  com.aspose.psd.Color .

**Returns:**
java.lang.String - اسم هذا com.aspose.psd.Color.
### getNavajoWhite() {#getNavajoWhite--}
```
public static Color getNavajoWhite()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getNavy() {#getNavy--}
```
public static Color getNavy()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getOldLace() {#getOldLace--}
```
public static Color getOldLace()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getOlive() {#getOlive--}
```
public static Color getOlive()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getOliveDrab() {#getOliveDrab--}
```
public static Color getOliveDrab()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getOrange() {#getOrange--}
```
public static Color getOrange()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getOrangeRed() {#getOrangeRed--}
```
public static Color getOrangeRed()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getOrchid() {#getOrchid--}
```
public static Color getOrchid()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPaleGoldenrod() {#getPaleGoldenrod--}
```
public static Color getPaleGoldenrod()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPaleGreen() {#getPaleGreen--}
```
public static Color getPaleGreen()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPaleTurquoise() {#getPaleTurquoise--}
```
public static Color getPaleTurquoise()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPaleVioletRed() {#getPaleVioletRed--}
```
public static Color getPaleVioletRed()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPapayaWhip() {#getPapayaWhip--}
```
public static Color getPapayaWhip()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPeachPuff() {#getPeachPuff--}
```
public static Color getPeachPuff()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPeru() {#getPeru--}
```
public static Color getPeru()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPink() {#getPink--}
```
public static Color getPink()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPlum() {#getPlum--}
```
public static Color getPlum()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPowderBlue() {#getPowderBlue--}
```
public static Color getPowderBlue()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPurple() {#getPurple--}
```
public static Color getPurple()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getR() {#getR--}
```
public byte getR()
```


يحصل على قيمة المكوّن الأحمر لهذا  com.aspose.psd.Color  الهيكل.

**Returns:**
byte - قيمة مكوّن الأحمر لهذا com.aspose.psd.Color.
### getRed() {#getRed--}
```
public static Color getRed()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getRosyBrown() {#getRosyBrown--}
```
public static Color getRosyBrown()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getRoyalBlue() {#getRoyalBlue--}
```
public static Color getRoyalBlue()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSaddleBrown() {#getSaddleBrown--}
```
public static Color getSaddleBrown()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSalmon() {#getSalmon--}
```
public static Color getSalmon()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSandyBrown() {#getSandyBrown--}
```
public static Color getSandyBrown()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSaturation() {#getSaturation--}
```
public float getSaturation()
```


يحصل على قيمة التشبع في نظام اللون (HSB) لهذا  com.aspose.psd.Color  الهيكل.

**Returns:**
float - تشبع هذا com.aspose.psd.Color. يتراوح التشبع من 0.0 إلى 1.0، حيث 0.0 هو تدرج الرمادي و1.0 هو أعلى تشبع.
### getSeaGreen() {#getSeaGreen--}
```
public static Color getSeaGreen()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSeaShell() {#getSeaShell--}
```
public static Color getSeaShell()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSienna() {#getSienna--}
```
public static Color getSienna()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSilver() {#getSilver--}
```
public static Color getSilver()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSkyBlue() {#getSkyBlue--}
```
public static Color getSkyBlue()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSlateBlue() {#getSlateBlue--}
```
public static Color getSlateBlue()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSlateGray() {#getSlateGray--}
```
public static Color getSlateGray()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSnow() {#getSnow--}
```
public static Color getSnow()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSpringGreen() {#getSpringGreen--}
```
public static Color getSpringGreen()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSteelBlue() {#getSteelBlue--}
```
public static Color getSteelBlue()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getTan() {#getTan--}
```
public static Color getTan()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getTeal() {#getTeal--}
```
public static Color getTeal()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getThistle() {#getThistle--}
```
public static Color getThistle()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getTomato() {#getTomato--}
```
public static Color getTomato()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getTransparent() {#getTransparent--}
```
public static Color getTransparent()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getTurquoise() {#getTurquoise--}
```
public static Color getTurquoise()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getViolet() {#getViolet--}
```
public static Color getViolet()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getWheat() {#getWheat--}
```
public static Color getWheat()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getWhite() {#getWhite--}
```
public static Color getWhite()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getWhiteSmoke() {#getWhiteSmoke--}
```
public static Color getWhiteSmoke()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getYellow() {#getYellow--}
```
public static Color getYellow()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getYellowGreen() {#getYellowGreen--}
```
public static Color getYellowGreen()
```


يحصل على لون معرف من النظام.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### hashCode() {#hashCode--}
```
public int hashCode()
```


يعيد رمز تجزئة لهذا  com.aspose.psd.Color  الهيكل.

**Returns:**
int - قيمة عددية تحدد رمز التجزئة لهذا com.aspose.psd.Color.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


يحصل على قيمة تشير إلى ما إذا كان هذا  com.aspose.psd.Color  الهيكل غير مهيأ.

**Returns:**
boolean - تُعيد هذه الخاصية true إذا كان هذا اللون غير مبدئ؛ وإلا false.
### isEquals(Color obj1, Color obj2) {#isEquals-com.aspose.psd.Color-com.aspose.psd.Color-}
```
public static boolean isEquals(Color obj1, Color obj2)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| obj1 | [Color](../../com.aspose.psd/color) |  |
| obj2 | [Color](../../com.aspose.psd/color) |  |

**Returns:**
boolean
### isKnownColor() {#isKnownColor--}
```
public boolean isKnownColor()
```


يحصل على قيمة تشير إلى ما إذا كان هيكل  com.aspose.psd.Color  هذا لونًا مسبقًا. تمثل الألوان المسبقة العناصر في تعداد  Aspose.Imaging.KnownColor .

**Returns:**
boolean - True إذا تم إنشاء  com.aspose.psd.Color  هذا من لون مسبق باستخدام إما طريقة  Aspose.Imaging.Color.FromName(String)  أو طريقة  Aspose.Imaging.Color.FromKnownColor(Aspose.Imaging.KnownColor) ; وإلا false.
### isNamedColor() {#isNamedColor--}
```
public boolean isNamedColor()
```


يحصل على قيمة تشير إلى ما إذا كان هذا  com.aspose.psd.Color  الهيكل لونًا مسمى أو عضوًا في تعداد  Aspose.Imaging.KnownColor .

**Returns:**
boolean - True إذا تم إنشاء  com.aspose.psd.Color  هذا باستخدام إما طريقة  Aspose.Imaging.Color.FromName(String)  أو طريقة  Aspose.Imaging.Color.FromKnownColor(Aspose.Imaging.KnownColor) ; وإلا false.
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


يفحص ما إذا كان هيكلا  com.aspose.psd.Color  المحددين متكافئين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| left | [Color](../../com.aspose.psd/color) | الـ  com.aspose.psd.Color  الموجود إلى يسار عامل المساواة. |
| right | [Color](../../com.aspose.psd/color) | الـ  com.aspose.psd.Color  الموجود إلى يمين عامل المساواة. |

**Returns:**
boolean - True إذا كان هياكل  com.aspose.psd.Color  الاثنين متساويين؛ وإلا false.
### op_Inequality(Color left, Color right) {#op-Inequality-com.aspose.psd.Color-com.aspose.psd.Color-}
```
public static boolean op_Inequality(Color left, Color right)
```


يفحص ما إذا كان هيكلا  com.aspose.psd.Color  المحددين مختلفين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| left | [Color](../../com.aspose.psd/color) | الـ  com.aspose.psd.Color  الموجود إلى يسار عامل عدم المساواة. |
| right | [Color](../../com.aspose.psd/color) | الـ  com.aspose.psd.Color  الموجود إلى يمين عامل عدم المساواة. |

**Returns:**
boolean - True إذا كانت هياكل  com.aspose.psd.Color  الاثنين مختلفة؛ وإلا false.
### toArgb() {#toArgb--}
```
public int toArgb()
```


يحصل على قيمة ARGB 32‑بت لهذا  com.aspose.psd.Color  الهيكل.

**Returns:**
int - قيمة ARGB ذات 32 بت لهذا  com.aspose.psd.Color .
### toCmyk(Color pixel) {#toCmyk-com.aspose.psd.Color-}
```
public static CmykColor toCmyk(Color pixel)
```


التحويل من Color إلى CmykColor. هذه الطريقة مهجورة. يرجى استخدام  CmykColorHelper.toCmyk(Color)  الأكثر فعالية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.psd/color) | البكسل من نوع Color بصيغة RGB. |

**Returns:**
[CmykColor](../../com.aspose.psd/cmykcolor) - The  CmykColor .
### toCmyk(Color[] pixels) {#toCmyk-com.aspose.psd.Color---}
```
public static CmykColor[] toCmyk(Color[] pixels)
```


التحويل من Color إلى CMYKColor. هذه الطريقة مهجورة. يرجى استخدام  CmykColorHelper.toCmyk(Color[])  الأكثر فعالية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.psd/color) | البكسلات من نوع Color بصيغة RGB. |

**Returns:**
com.aspose.psd.CmykColor[] - الـ Aspose:Imaging:CmykColor[] .
### toCmykIcc(Color pixel) {#toCmykIcc-com.aspose.psd.Color-}
```
public static CmykColor toCmykIcc(Color pixel)
```


التحويل من Color إلى CMYKColor باستخدام تحويل icc مع ملفات تعريف افتراضية. هذه الطريقة مهجورة. يرجى استخدام  CmykColorHelper.toCmykIcc(Color)  الأكثر فعالية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.psd/color) | البكسل من نوع Color بصيغة RGB. |

**Returns:**
[CmykColor](../../com.aspose.psd/cmykcolor) - The  CmykColor .
### toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIcc-com.aspose.psd.Color-java.io.InputStream-java.io.InputStream-}
```
public static CmykColor toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream)
```


التحويل من Color إلى CMYKColor باستخدام تحويل icc مع ملفات تعريف افتراضية. هذه الطريقة مهجورة. يرجى استخدام  CmykColorHelper.toCmykIcc(Color, InputStream, InputStream)  الأكثر فعالية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.psd/color) | البكسل من نوع Color بصيغة RGB. |
| rgbIccStream | java.io.InputStream | الدفق الذي يحتوي على ملف تعريف icc rgb. |
| cmykIccStream | java.io.InputStream | الدفق الذي يحتوي على ملف تعريف icc cmyk. |

**Returns:**
[CmykColor](../../com.aspose.psd/cmykcolor) - The  CmykColor[] .
### toCmykIcc(Color[] pixels) {#toCmykIcc-com.aspose.psd.Color---}
```
public static CmykColor[] toCmykIcc(Color[] pixels)
```


التحويل من Color إلى CMYKColor باستخدام تحويل icc مع ملفات تعريف افتراضية. هذه الطريقة مهجورة. يرجى استخدام  CmykColorHelper.toCmykIcc(Color[])  الأكثر فعالية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.psd/color) | البكسلات من نوع Color بصيغة RGB. |

**Returns:**
com.aspose.psd.CmykColor[] - الـ CmykColor[] .
### toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIcc-com.aspose.psd.Color---java.io.InputStream-java.io.InputStream-}
```
public static CmykColor[] toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)
```


التحويل من Color إلى CMYKColor باستخدام تحويل icc. هذه الطريقة مهجورة. يرجى استخدام  CmykColorHelper.toCmykIcc(Color[], InputStream, InputStream)  الأكثر فعالية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.psd/color) | البكسلات من نوع Color بصيغة RGB. |
| rgbIccStream | java.io.InputStream | الدفق الذي يحتوي على ملف تعريف icc rgb. |
| cmykIccStream | java.io.InputStream | الدفق الذي يحتوي على ملف تعريف icc cmyk. |

**Returns:**
com.aspose.psd.CmykColor[] - الـ CmykColor[] .
### toCmykIcc_internalized(Color pixel, System.IO.Stream rgbIccStream, System.IO.Stream cmykIccStream) {#toCmykIcc-internalized-com.aspose.psd.Color-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-}
```
public static CmykColor toCmykIcc_internalized(Color pixel, System.IO.Stream rgbIccStream, System.IO.Stream cmykIccStream)
```




**Parameters:**
| معامل | نوع | الوصف |
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
| معامل | نوع | الوصف |
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


يحصل على قيمة  Aspose.Imaging.KnownColor  لهذا  com.aspose.psd.Color  الهيكل.

**Returns:**
int - عنصر من تعداد  Aspose.Imaging.KnownColor ، إذا تم إنشاء  com.aspose.psd.Color  من لون مسبق باستخدام إما طريقة  Aspose.Imaging.Color.FromName(String)  أو طريقة  Aspose.Imaging.Color.FromKnownColor(Aspose.Imaging.KnownColor) ; وإلا 0.
### toString() {#toString--}
```
public String toString()
```


يحوّل هذا  com.aspose.psd.Color  الهيكل إلى سلسلة قابلة للقراءة من قبل الإنسان.

**Returns:**
java.lang.String - سلسلة تمثل اسم هذا com.aspose.psd.Color، إذا تم إنشاء com.aspose.psd.Color من لون مسبق التعريف باستخدام إما طريقة Aspose.Imaging.Color.FromName(String) أو طريقة Aspose.Imaging.Color.FromKnownColor(Aspose.Imaging.KnownColor)؛ وإلا، تكون سلسلة تتكون من أسماء مكونات ARGB وقيمها.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

