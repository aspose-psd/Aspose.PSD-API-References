---
title: "Color"
second_title: "Java용 Aspose.PSD API 참조"
description: "픽셀의 색상."
type: docs
weight: 19
url: /ko/java/com.aspose.psd/color/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class Color extends Struct<Color>
```

픽셀의 색상.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [Color()](#Color--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(Color that)](#CloneTo-com.aspose.psd.Color-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | 지정된 객체가 com.aspose.psd.Color 구조체인지 및 이 com.aspose.psd.Color 구조체와 동등한지 테스트합니다. |
| [fromArgb(byte red, byte green, byte blue)](#fromArgb-byte-byte-byte-) | 지정된 8비트 색상 값(빨강, 초록 및 파랑)으로부터  com.aspose.psd.Color  구조를 생성합니다. |
| [fromArgb(byte alpha, byte red, byte green, byte blue)](#fromArgb-byte-byte-byte-byte-) | 네 개의 ARGB 구성 요소(알파, 빨강, 초록 및 파랑) 값을 사용하여  com.aspose.psd.Color  구조를 생성합니다. |
| [fromArgb(int argb)](#fromArgb-int-) | 32비트 ARGB 값을 사용하여  com.aspose.psd.Color  구조를 생성합니다. |
| [fromArgb(int alpha, Color baseColor)](#fromArgb-int-com.aspose.psd.Color-) | 지정된  com.aspose.psd.Color  구조를 기반으로 하되, 새로 지정된 알파 값을 사용하여  com.aspose.psd.Color  구조를 생성합니다. |
| [fromArgb(int red, int green, int blue)](#fromArgb-int-int-int-) | 지정된 8비트 색상 값(빨강, 초록 및 파랑)으로부터  com.aspose.psd.Color  구조를 생성합니다. |
| [fromArgb(int alpha, int red, int green, int blue)](#fromArgb-int-int-int-int-) | 네 개의 ARGB 구성 요소(알파, 빨강, 초록 및 파랑) 값을 사용하여  com.aspose.psd.Color  구조를 생성합니다. |
| [fromKnownColor(int color)](#fromKnownColor-int-) | 지정된 사전 정의된 색상으로부터  com.aspose.psd.Color  구조를 생성합니다. |
| [fromName(String name)](#fromName-java.lang.String-) | 지정된 사전 정의된 색상의 이름으로부터  com.aspose.psd.Color  구조를 생성합니다. |
| [getA()](#getA--) | 이  com.aspose.psd.Color  구조의 알파 구성 요소 값을 가져옵니다. |
| [getAliceBlue()](#getAliceBlue--) | 시스템 정의 색상을 가져옵니다. |
| [getAntiqueWhite()](#getAntiqueWhite--) | 시스템 정의 색상을 가져옵니다. |
| [getAqua()](#getAqua--) | 시스템 정의 색상을 가져옵니다. |
| [getAquamarine()](#getAquamarine--) | 시스템 정의 색상을 가져옵니다. |
| [getAzure()](#getAzure--) | 시스템 정의 색상을 가져옵니다. |
| [getB()](#getB--) | 이  com.aspose.psd.Color  구조의 파랑 구성 요소 값을 가져옵니다. |
| [getBeige()](#getBeige--) | 시스템 정의 색상을 가져옵니다. |
| [getBisque()](#getBisque--) | 시스템 정의 색상을 가져옵니다. |
| [getBlack()](#getBlack--) | 시스템 정의 색상을 가져옵니다. |
| [getBlanchedAlmond()](#getBlanchedAlmond--) | 시스템 정의 색상을 가져옵니다. |
| [getBlue()](#getBlue--) | 시스템 정의 색상을 가져옵니다. |
| [getBlueViolet()](#getBlueViolet--) | 시스템 정의 색상을 가져옵니다. |
| [getBrightness()](#getBrightness--) | 이  com.aspose.psd.Color  구조에 대한 색조-채도-밝기(HSB) 밝기 값을 가져옵니다. |
| [getBrown()](#getBrown--) | 시스템 정의 색상을 가져옵니다. |
| [getBurlyWood()](#getBurlyWood--) | 시스템 정의 색상을 가져옵니다. |
| [getCadetBlue()](#getCadetBlue--) | 시스템 정의 색상을 가져옵니다. |
| [getChartreuse()](#getChartreuse--) | 시스템 정의 색상을 가져옵니다. |
| [getChocolate()](#getChocolate--) | 시스템 정의 색상을 가져옵니다. |
| [getClass()](#getClass--) |  |
| [getCoral()](#getCoral--) | 시스템 정의 색상을 가져옵니다. |
| [getCornflowerBlue()](#getCornflowerBlue--) | 시스템 정의 색상을 가져옵니다. |
| [getCornsilk()](#getCornsilk--) | 시스템 정의 색상을 가져옵니다. |
| [getCrimson()](#getCrimson--) | 시스템 정의 색상을 가져옵니다. |
| [getCyan()](#getCyan--) | 시스템 정의 색상을 가져옵니다. |
| [getDarkBlue()](#getDarkBlue--) | 시스템 정의 색상을 가져옵니다. |
| [getDarkCyan()](#getDarkCyan--) | 시스템 정의 색상을 가져옵니다. |
| [getDarkGoldenrod()](#getDarkGoldenrod--) | 시스템 정의 색상을 가져옵니다. |
| [getDarkGray()](#getDarkGray--) | 시스템 정의 색상을 가져옵니다. |
| [getDarkGreen()](#getDarkGreen--) | 시스템 정의 색상을 가져옵니다. |
| [getDarkKhaki()](#getDarkKhaki--) | 시스템 정의 색상을 가져옵니다. |
| [getDarkMagenta()](#getDarkMagenta--) | 시스템 정의 색상을 가져옵니다. |
| [getDarkOliveGreen()](#getDarkOliveGreen--) | 시스템 정의 색상을 가져옵니다. |
| [getDarkOrange()](#getDarkOrange--) | 시스템 정의 색상을 가져옵니다. |
| [getDarkOrchid()](#getDarkOrchid--) | 시스템 정의 색상을 가져옵니다. |
| [getDarkRed()](#getDarkRed--) | 시스템 정의 색상을 가져옵니다. |
| [getDarkSalmon()](#getDarkSalmon--) | 시스템 정의 색상을 가져옵니다. |
| [getDarkSeaGreen()](#getDarkSeaGreen--) | 시스템 정의 색상을 가져옵니다. |
| [getDarkSlateBlue()](#getDarkSlateBlue--) | 시스템 정의 색상을 가져옵니다. |
| [getDarkSlateGray()](#getDarkSlateGray--) | 시스템 정의 색상을 가져옵니다. |
| [getDarkTurquoise()](#getDarkTurquoise--) | 시스템 정의 색상을 가져옵니다. |
| [getDarkViolet()](#getDarkViolet--) | 시스템 정의 색상을 가져옵니다. |
| [getDeepPink()](#getDeepPink--) | 시스템 정의 색상을 가져옵니다. |
| [getDeepSkyBlue()](#getDeepSkyBlue--) | 시스템 정의 색상을 가져옵니다. |
| [getDimGray()](#getDimGray--) | 시스템 정의 색상을 가져옵니다. |
| [getDodgerBlue()](#getDodgerBlue--) | 시스템 정의 색상을 가져옵니다. |
| [getEmpty()](#getEmpty--) | 빈  Color  을 가져옵니다. |
| [getFirebrick()](#getFirebrick--) | 시스템 정의 색상을 가져옵니다. |
| [getFloralWhite()](#getFloralWhite--) | 시스템 정의 색상을 가져옵니다. |
| [getForestGreen()](#getForestGreen--) | 시스템 정의 색상을 가져옵니다. |
| [getFuchsia()](#getFuchsia--) | 시스템 정의 색상을 가져옵니다. |
| [getG()](#getG--) | 이  com.aspose.psd.Color  구조의 초록 구성 요소 값을 가져옵니다. |
| [getGainsboro()](#getGainsboro--) | 시스템 정의 색상을 가져옵니다. |
| [getGhostWhite()](#getGhostWhite--) | 시스템 정의 색상을 가져옵니다. |
| [getGold()](#getGold--) | 시스템 정의 색상을 가져옵니다. |
| [getGoldenrod()](#getGoldenrod--) | 시스템 정의 색상을 가져옵니다. |
| [getGray()](#getGray--) | 시스템 정의 색상을 가져옵니다. |
| [getGreen()](#getGreen--) | 시스템 정의 색상을 가져옵니다. |
| [getGreenYellow()](#getGreenYellow--) | 시스템 정의 색상을 가져옵니다. |
| [getHoneydew()](#getHoneydew--) | 시스템 정의 색상을 가져옵니다. |
| [getHotPink()](#getHotPink--) | 시스템 정의 색상을 가져옵니다. |
| [getHue()](#getHue--) | 이  com.aspose.psd.Color  구조에 대한 색조-채도-밝기(HSB) 색조 값을 도(degrees) 단위로 가져옵니다. |
| [getIndianRed()](#getIndianRed--) | 시스템 정의 색상을 가져옵니다. |
| [getIndigo()](#getIndigo--) | 시스템 정의 색상을 가져옵니다. |
| [getIvory()](#getIvory--) | 시스템 정의 색상을 가져옵니다. |
| [getKhaki()](#getKhaki--) | 시스템 정의 색상을 가져옵니다. |
| [getLavender()](#getLavender--) | 시스템 정의 색상을 가져옵니다. |
| [getLavenderBlush()](#getLavenderBlush--) | 시스템 정의 색상을 가져옵니다. |
| [getLawnGreen()](#getLawnGreen--) | 시스템 정의 색상을 가져옵니다. |
| [getLemonChiffon()](#getLemonChiffon--) | 시스템 정의 색상을 가져옵니다. |
| [getLightBlue()](#getLightBlue--) | 시스템 정의 색상을 가져옵니다. |
| [getLightCoral()](#getLightCoral--) | 시스템 정의 색상을 가져옵니다. |
| [getLightCyan()](#getLightCyan--) | 시스템 정의 색상을 가져옵니다. |
| [getLightGoldenrodYellow()](#getLightGoldenrodYellow--) | 시스템 정의 색상을 가져옵니다. |
| [getLightGray()](#getLightGray--) | 시스템 정의 색상을 가져옵니다. |
| [getLightGreen()](#getLightGreen--) | 시스템 정의 색상을 가져옵니다. |
| [getLightPink()](#getLightPink--) | 시스템 정의 색상을 가져옵니다. |
| [getLightSalmon()](#getLightSalmon--) | 시스템 정의 색상을 가져옵니다. |
| [getLightSeaGreen()](#getLightSeaGreen--) | 시스템 정의 색상을 가져옵니다. |
| [getLightSkyBlue()](#getLightSkyBlue--) | 시스템 정의 색상을 가져옵니다. |
| [getLightSlateGray()](#getLightSlateGray--) | 시스템 정의 색상을 가져옵니다. |
| [getLightSteelBlue()](#getLightSteelBlue--) | 시스템 정의 색상을 가져옵니다. |
| [getLightYellow()](#getLightYellow--) | 시스템 정의 색상을 가져옵니다. |
| [getLime()](#getLime--) | 시스템 정의 색상을 가져옵니다. |
| [getLimeGreen()](#getLimeGreen--) | 시스템 정의 색상을 가져옵니다. |
| [getLinen()](#getLinen--) | 시스템 정의 색상을 가져옵니다. |
| [getMagenta()](#getMagenta--) | 시스템 정의 색상을 가져옵니다. |
| [getMaroon()](#getMaroon--) | 시스템 정의 색상을 가져옵니다. |
| [getMediumAquamarine()](#getMediumAquamarine--) | 시스템 정의 색상을 가져옵니다. |
| [getMediumBlue()](#getMediumBlue--) | 시스템 정의 색상을 가져옵니다. |
| [getMediumOrchid()](#getMediumOrchid--) | 시스템 정의 색상을 가져옵니다. |
| [getMediumPurple()](#getMediumPurple--) | 시스템 정의 색상을 가져옵니다. |
| [getMediumSeaGreen()](#getMediumSeaGreen--) | 시스템 정의 색상을 가져옵니다. |
| [getMediumSlateBlue()](#getMediumSlateBlue--) | 시스템 정의 색상을 가져옵니다. |
| [getMediumSpringGreen()](#getMediumSpringGreen--) | 시스템 정의 색상을 가져옵니다. |
| [getMediumTurquoise()](#getMediumTurquoise--) | 시스템 정의 색상을 가져옵니다. |
| [getMediumVioletRed()](#getMediumVioletRed--) | 시스템 정의 색상을 가져옵니다. |
| [getMidnightBlue()](#getMidnightBlue--) | 시스템 정의 색상을 가져옵니다. |
| [getMintCream()](#getMintCream--) | 시스템 정의 색상을 가져옵니다. |
| [getMistyRose()](#getMistyRose--) | 시스템 정의 색상을 가져옵니다. |
| [getMoccasin()](#getMoccasin--) | 시스템 정의 색상을 가져옵니다. |
| [getName()](#getName--) | 이  com.aspose.psd.Color  의 이름을 가져옵니다. |
| [getNavajoWhite()](#getNavajoWhite--) | 시스템 정의 색상을 가져옵니다. |
| [getNavy()](#getNavy--) | 시스템 정의 색상을 가져옵니다. |
| [getOldLace()](#getOldLace--) | 시스템 정의 색상을 가져옵니다. |
| [getOlive()](#getOlive--) | 시스템 정의 색상을 가져옵니다. |
| [getOliveDrab()](#getOliveDrab--) | 시스템 정의 색상을 가져옵니다. |
| [getOrange()](#getOrange--) | 시스템 정의 색상을 가져옵니다. |
| [getOrangeRed()](#getOrangeRed--) | 시스템 정의 색상을 가져옵니다. |
| [getOrchid()](#getOrchid--) | 시스템 정의 색상을 가져옵니다. |
| [getPaleGoldenrod()](#getPaleGoldenrod--) | 시스템 정의 색상을 가져옵니다. |
| [getPaleGreen()](#getPaleGreen--) | 시스템 정의 색상을 가져옵니다. |
| [getPaleTurquoise()](#getPaleTurquoise--) | 시스템 정의 색상을 가져옵니다. |
| [getPaleVioletRed()](#getPaleVioletRed--) | 시스템 정의 색상을 가져옵니다. |
| [getPapayaWhip()](#getPapayaWhip--) | 시스템 정의 색상을 가져옵니다. |
| [getPeachPuff()](#getPeachPuff--) | 시스템 정의 색상을 가져옵니다. |
| [getPeru()](#getPeru--) | 시스템 정의 색상을 가져옵니다. |
| [getPink()](#getPink--) | 시스템 정의 색상을 가져옵니다. |
| [getPlum()](#getPlum--) | 시스템 정의 색상을 가져옵니다. |
| [getPowderBlue()](#getPowderBlue--) | 시스템 정의 색상을 가져옵니다. |
| [getPurple()](#getPurple--) | 시스템 정의 색상을 가져옵니다. |
| [getR()](#getR--) | 이  com.aspose.psd.Color  구조의 빨강 구성 요소 값을 가져옵니다. |
| [getRed()](#getRed--) | 시스템 정의 색상을 가져옵니다. |
| [getRosyBrown()](#getRosyBrown--) | 시스템 정의 색상을 가져옵니다. |
| [getRoyalBlue()](#getRoyalBlue--) | 시스템 정의 색상을 가져옵니다. |
| [getSaddleBrown()](#getSaddleBrown--) | 시스템 정의 색상을 가져옵니다. |
| [getSalmon()](#getSalmon--) | 시스템 정의 색상을 가져옵니다. |
| [getSandyBrown()](#getSandyBrown--) | 시스템 정의 색상을 가져옵니다. |
| [getSaturation()](#getSaturation--) | 이  com.aspose.psd.Color  구조에 대한 색조-채도-밝기(HSB) 채도 값을 가져옵니다. |
| [getSeaGreen()](#getSeaGreen--) | 시스템 정의 색상을 가져옵니다. |
| [getSeaShell()](#getSeaShell--) | 시스템 정의 색상을 가져옵니다. |
| [getSienna()](#getSienna--) | 시스템 정의 색상을 가져옵니다. |
| [getSilver()](#getSilver--) | 시스템 정의 색상을 가져옵니다. |
| [getSkyBlue()](#getSkyBlue--) | 시스템 정의 색상을 가져옵니다. |
| [getSlateBlue()](#getSlateBlue--) | 시스템 정의 색상을 가져옵니다. |
| [getSlateGray()](#getSlateGray--) | 시스템 정의 색상을 가져옵니다. |
| [getSnow()](#getSnow--) | 시스템 정의 색상을 가져옵니다. |
| [getSpringGreen()](#getSpringGreen--) | 시스템 정의 색상을 가져옵니다. |
| [getSteelBlue()](#getSteelBlue--) | 시스템 정의 색상을 가져옵니다. |
| [getTan()](#getTan--) | 시스템 정의 색상을 가져옵니다. |
| [getTeal()](#getTeal--) | 시스템 정의 색상을 가져옵니다. |
| [getThistle()](#getThistle--) | 시스템 정의 색상을 가져옵니다. |
| [getTomato()](#getTomato--) | 시스템 정의 색상을 가져옵니다. |
| [getTransparent()](#getTransparent--) | 시스템 정의 색상을 가져옵니다. |
| [getTurquoise()](#getTurquoise--) | 시스템 정의 색상을 가져옵니다. |
| [getViolet()](#getViolet--) | 시스템 정의 색상을 가져옵니다. |
| [getWheat()](#getWheat--) | 시스템 정의 색상을 가져옵니다. |
| [getWhite()](#getWhite--) | 시스템 정의 색상을 가져옵니다. |
| [getWhiteSmoke()](#getWhiteSmoke--) | 시스템 정의 색상을 가져옵니다. |
| [getYellow()](#getYellow--) | 시스템 정의 색상을 가져옵니다. |
| [getYellowGreen()](#getYellowGreen--) | 시스템 정의 색상을 가져옵니다. |
| [hashCode()](#hashCode--) | 이  com.aspose.psd.Color  구조의 해시 코드를 반환합니다. |
| [isEmpty()](#isEmpty--) | 이  com.aspose.psd.Color  구조가 초기화되지 않았는지 여부를 나타내는 값을 가져옵니다. |
| [isEquals(Color obj1, Color obj2)](#isEquals-com.aspose.psd.Color-com.aspose.psd.Color-) |  |
| [isKnownColor()](#isKnownColor--) | 이  com.aspose.psd.Color  구조가 사전 정의된 색상인지 여부를 나타내는 값을 가져옵니다. |
| [isNamedColor()](#isNamedColor--) | 이  com.aspose.psd.Color  구조가 명명된 색상인지 또는 Aspose.Imaging.KnownColor 열거형의 멤버인지 여부를 나타내는 값을 가져옵니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Equality(Color left, Color right)](#op-Equality-com.aspose.psd.Color-com.aspose.psd.Color-) | 두 지정된  com.aspose.psd.Color  구조가 동등한지 테스트합니다. |
| [op_Inequality(Color left, Color right)](#op-Inequality-com.aspose.psd.Color-com.aspose.psd.Color-) | 두 지정된  com.aspose.psd.Color  구조가 다른지 테스트합니다. |
| [toArgb()](#toArgb--) | 이  com.aspose.psd.Color  구조의 32비트 ARGB 값을 가져옵니다. |
| [toCmyk(Color pixel)](#toCmyk-com.aspose.psd.Color-) | Color에서 CmykColor로의 변환입니다. |
| [toCmyk(Color[] pixels)](#toCmyk-com.aspose.psd.Color---) | Color에서 CMYKColor로의 변환입니다. |
| [toCmykIcc(Color pixel)](#toCmykIcc-com.aspose.psd.Color-) | 기본 프로파일을 사용한 icc 변환으로 Color에서 CMYKColor로의 변환입니다. |
| [toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIcc-com.aspose.psd.Color-java.io.InputStream-java.io.InputStream-) | 기본 프로파일을 사용한 icc 변환으로 Color에서 CMYKColor로의 변환입니다. |
| [toCmykIcc(Color[] pixels)](#toCmykIcc-com.aspose.psd.Color---) | 기본 프로파일을 사용한 icc 변환으로 Color에서 CMYKColor로의 변환입니다. |
| [toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIcc-com.aspose.psd.Color---java.io.InputStream-java.io.InputStream-) | icc 변환을 사용한 Color에서 CMYKColor로의 변환입니다. |
| [toCmykIcc_internalized(Color pixel, System.IO.Stream rgbIccStream, System.IO.Stream cmykIccStream)](#toCmykIcc-internalized-com.aspose.psd.Color-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-) |  |
| [toCmykIcc_internalized(Color[] pixels, System.IO.Stream rgbIccStream, System.IO.Stream cmykIccStream)](#toCmykIcc-internalized-com.aspose.psd.Color---com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-) |  |
| [toKnownColor()](#toKnownColor--) | 이 com.aspose.psd.Color 구조체의 Aspose.Imaging.KnownColor 값을 가져옵니다. |
| [toString()](#toString--) | 이 com.aspose.psd.Color 구조체를 사람이 읽을 수 있는 문자열로 변환합니다. |
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
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(Color that) {#CloneTo-com.aspose.psd.Color-}
```
public void CloneTo(Color that)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| that | [Color](../../com.aspose.psd/color) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


지정된 객체가 com.aspose.psd.Color 구조체인지 및 이 com.aspose.psd.Color 구조체와 동등한지 테스트합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | java.lang.Object | 테스트할 객체입니다. |

**Returns:**
boolean - obj가 이 com.aspose.psd.Color 구조체와 동등한 com.aspose.psd.Color 구조체인 경우 true; 그렇지 않으면 false.
### fromArgb(byte red, byte green, byte blue) {#fromArgb-byte-byte-byte-}
```
public static Color fromArgb(byte red, byte green, byte blue)
```


지정된 8비트 색상 값(빨강, 초록, 파랑)으로 com.aspose.psd.Color 구조체를 생성합니다. 알파 값은 암시적으로 255(완전 불투명)입니다. 이 메서드는 각 색상 구성 요소에 대해 32비트 값을 전달할 수 있지만, 각 구성 요소의 값은 8비트로 제한됩니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 빨간색 | byte | 새 com.aspose.psd.Color의 빨간색 구성 요소 값입니다. 유효한 값은 0부터 255까지입니다. |
| 녹색 | byte | 새 com.aspose.psd.Color의 초록색 구성 요소 값입니다. 유효한 값은 0부터 255까지입니다. |
| 파란색 | byte | 새 com.aspose.psd.Color의 파란색 구성 요소 값입니다. 유효한 값은 0부터 255까지입니다. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  com.aspose.psd.Color  that this method creates.
### fromArgb(byte alpha, byte red, byte green, byte blue) {#fromArgb-byte-byte-byte-byte-}
```
public static Color fromArgb(byte alpha, byte red, byte green, byte blue)
```


네 개의 ARGB 구성 요소(알파, 빨강, 초록, 파랑) 값으로 com.aspose.psd.Color 구조체를 생성합니다. 이 메서드는 각 구성 요소에 대해 32비트 값을 전달할 수 있지만, 각 구성 요소의 값은 8비트로 제한됩니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 알파 | byte | 알파 구성 요소입니다. 유효한 값은 0부터 255까지입니다. |
| 빨간색 | byte | 빨간색 구성 요소입니다. 유효한 값은 0부터 255까지입니다. |
| 녹색 | byte | 초록색 구성 요소입니다. 유효한 값은 0부터 255까지입니다. |
| 파란색 | byte | 파란색 구성 요소입니다. 유효한 값은 0부터 255까지입니다. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  com.aspose.psd.Color  that this method creates.
### fromArgb(int argb) {#fromArgb-int-}
```
public static Color fromArgb(int argb)
```


32비트 ARGB 값을 사용하여  com.aspose.psd.Color  구조를 생성합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| argb | int | 32비트 ARGB 값을 지정하는 값입니다. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  com.aspose.psd.Color  structure that this method creates.
### fromArgb(int alpha, Color baseColor) {#fromArgb-int-com.aspose.psd.Color-}
```
public static Color fromArgb(int alpha, Color baseColor)
```


지정된 com.aspose.psd.Color 구조체에서 새로운 알파 값을 지정하여 com.aspose.psd.Color 구조체를 생성합니다. 이 메서드는 알파 값에 대해 32비트 값을 전달할 수 있지만, 값은 8비트로 제한됩니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 알파 | int | 새 com.aspose.psd.Color의 알파 값입니다. 유효한 값은 0부터 255까지입니다. |
| baseColor | [Color](../../com.aspose.psd/color) | 새 com.aspose.psd.Color를 생성할 기준이 되는 com.aspose.psd.Color입니다. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  com.aspose.psd.Color  that this method creates.
### fromArgb(int red, int green, int blue) {#fromArgb-int-int-int-}
```
public static Color fromArgb(int red, int green, int blue)
```


지정된 8비트 색상 값(빨강, 초록, 파랑)으로 com.aspose.psd.Color 구조체를 생성합니다. 알파 값은 암시적으로 255(완전 불투명)입니다. 이 메서드는 각 색상 구성 요소에 대해 32비트 값을 전달할 수 있지만, 각 구성 요소의 값은 8비트로 제한됩니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 빨간색 | int | 새 com.aspose.psd.Color의 빨간색 구성 요소 값입니다. 유효한 값은 0부터 255까지입니다. |
| 녹색 | int | 새 com.aspose.psd.Color의 초록색 구성 요소 값입니다. 유효한 값은 0부터 255까지입니다. |
| 파란색 | int | 새 com.aspose.psd.Color의 파란색 구성 요소 값입니다. 유효한 값은 0부터 255까지입니다. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  com.aspose.psd.Color  that this method creates.
### fromArgb(int alpha, int red, int green, int blue) {#fromArgb-int-int-int-int-}
```
public static Color fromArgb(int alpha, int red, int green, int blue)
```


네 개의 ARGB 구성 요소(알파, 빨강, 초록, 파랑) 값으로 com.aspose.psd.Color 구조체를 생성합니다. 이 메서드는 각 구성 요소에 대해 32비트 값을 전달할 수 있지만, 각 구성 요소의 값은 8비트로 제한됩니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 알파 | int | 알파 구성 요소입니다. 유효한 값은 0부터 255까지입니다. |
| 빨간색 | int | 빨간색 구성 요소입니다. 유효한 값은 0부터 255까지입니다. |
| 녹색 | int | 초록색 구성 요소입니다. 유효한 값은 0부터 255까지입니다. |
| 파란색 | int | 파란색 구성 요소입니다. 유효한 값은 0부터 255까지입니다. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  com.aspose.psd.Color  that this method creates.
### fromKnownColor(int color) {#fromKnownColor-int-}
```
public static Color fromKnownColor(int color)
```


지정된 사전 정의된 색상으로부터  com.aspose.psd.Color  구조를 생성합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 색상 | int | Aspose.Imaging.KnownColor 열거형의 요소입니다. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  com.aspose.psd.Color  that this method creates.
### fromName(String name) {#fromName-java.lang.String-}
```
public static Color fromName(String name)
```


지정된 사전 정의된 색상의 이름으로부터  com.aspose.psd.Color  구조를 생성합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 이름 | java.lang.String | 미리 정의된 색상의 이름인 문자열입니다. 유효한 이름은 Aspose.Imaging.KnownColor 열거형 요소들의 이름과 동일합니다. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  com.aspose.psd.Color  that this method creates.
### getA() {#getA--}
```
public byte getA()
```


이  com.aspose.psd.Color  구조의 알파 구성 요소 값을 가져옵니다.

**Returns:**
byte - 이 com.aspose.psd.Color의 알파 구성 요소 값입니다.
### getAliceBlue() {#getAliceBlue--}
```
public static Color getAliceBlue()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getAntiqueWhite() {#getAntiqueWhite--}
```
public static Color getAntiqueWhite()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getAqua() {#getAqua--}
```
public static Color getAqua()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getAquamarine() {#getAquamarine--}
```
public static Color getAquamarine()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getAzure() {#getAzure--}
```
public static Color getAzure()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getB() {#getB--}
```
public byte getB()
```


이  com.aspose.psd.Color  구조의 파랑 구성 요소 값을 가져옵니다.

**Returns:**
byte - 이 com.aspose.psd.Color의 파란색 구성 요소 값.
### getBeige() {#getBeige--}
```
public static Color getBeige()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getBisque() {#getBisque--}
```
public static Color getBisque()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getBlack() {#getBlack--}
```
public static Color getBlack()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getBlanchedAlmond() {#getBlanchedAlmond--}
```
public static Color getBlanchedAlmond()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getBlue() {#getBlue--}
```
public static Color getBlue()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getBlueViolet() {#getBlueViolet--}
```
public static Color getBlueViolet()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getBrightness() {#getBrightness--}
```
public float getBrightness()
```


이  com.aspose.psd.Color  구조에 대한 색조-채도-밝기(HSB) 밝기 값을 가져옵니다.

**Returns:**
float - 이 com.aspose.psd.Color의 밝기. 밝기는 0.0부터 1.0까지이며, 0.0은 검은색을, 1.0은 흰색을 나타냅니다.
### getBrown() {#getBrown--}
```
public static Color getBrown()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getBurlyWood() {#getBurlyWood--}
```
public static Color getBurlyWood()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getCadetBlue() {#getCadetBlue--}
```
public static Color getCadetBlue()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getChartreuse() {#getChartreuse--}
```
public static Color getChartreuse()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getChocolate() {#getChocolate--}
```
public static Color getChocolate()
```


시스템 정의 색상을 가져옵니다.

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


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getCornflowerBlue() {#getCornflowerBlue--}
```
public static Color getCornflowerBlue()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getCornsilk() {#getCornsilk--}
```
public static Color getCornsilk()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getCrimson() {#getCrimson--}
```
public static Color getCrimson()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getCyan() {#getCyan--}
```
public static Color getCyan()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkBlue() {#getDarkBlue--}
```
public static Color getDarkBlue()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkCyan() {#getDarkCyan--}
```
public static Color getDarkCyan()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkGoldenrod() {#getDarkGoldenrod--}
```
public static Color getDarkGoldenrod()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkGray() {#getDarkGray--}
```
public static Color getDarkGray()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkGreen() {#getDarkGreen--}
```
public static Color getDarkGreen()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkKhaki() {#getDarkKhaki--}
```
public static Color getDarkKhaki()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkMagenta() {#getDarkMagenta--}
```
public static Color getDarkMagenta()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkOliveGreen() {#getDarkOliveGreen--}
```
public static Color getDarkOliveGreen()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkOrange() {#getDarkOrange--}
```
public static Color getDarkOrange()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkOrchid() {#getDarkOrchid--}
```
public static Color getDarkOrchid()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkRed() {#getDarkRed--}
```
public static Color getDarkRed()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkSalmon() {#getDarkSalmon--}
```
public static Color getDarkSalmon()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkSeaGreen() {#getDarkSeaGreen--}
```
public static Color getDarkSeaGreen()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkSlateBlue() {#getDarkSlateBlue--}
```
public static Color getDarkSlateBlue()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkSlateGray() {#getDarkSlateGray--}
```
public static Color getDarkSlateGray()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkTurquoise() {#getDarkTurquoise--}
```
public static Color getDarkTurquoise()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkViolet() {#getDarkViolet--}
```
public static Color getDarkViolet()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDeepPink() {#getDeepPink--}
```
public static Color getDeepPink()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDeepSkyBlue() {#getDeepSkyBlue--}
```
public static Color getDeepSkyBlue()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDimGray() {#getDimGray--}
```
public static Color getDimGray()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDodgerBlue() {#getDodgerBlue--}
```
public static Color getDodgerBlue()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getEmpty() {#getEmpty--}
```
public static Color getEmpty()
```


빈  Color  을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - The empty  Color .
### getFirebrick() {#getFirebrick--}
```
public static Color getFirebrick()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getFloralWhite() {#getFloralWhite--}
```
public static Color getFloralWhite()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getForestGreen() {#getForestGreen--}
```
public static Color getForestGreen()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getFuchsia() {#getFuchsia--}
```
public static Color getFuchsia()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getG() {#getG--}
```
public byte getG()
```


이  com.aspose.psd.Color  구조의 초록 구성 요소 값을 가져옵니다.

**Returns:**
byte - 이 com.aspose.psd.Color의 녹색 구성 요소 값.
### getGainsboro() {#getGainsboro--}
```
public static Color getGainsboro()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getGhostWhite() {#getGhostWhite--}
```
public static Color getGhostWhite()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getGold() {#getGold--}
```
public static Color getGold()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getGoldenrod() {#getGoldenrod--}
```
public static Color getGoldenrod()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getGray() {#getGray--}
```
public static Color getGray()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  structure representing a system-defined color.
### getGreen() {#getGreen--}
```
public static Color getGreen()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getGreenYellow() {#getGreenYellow--}
```
public static Color getGreenYellow()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getHoneydew() {#getHoneydew--}
```
public static Color getHoneydew()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getHotPink() {#getHotPink--}
```
public static Color getHotPink()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getHue() {#getHue--}
```
public float getHue()
```


이  com.aspose.psd.Color  구조에 대한 색조-채도-밝기(HSB) 색조 값을 도(degrees) 단위로 가져옵니다.

**Returns:**
float - 이 com.aspose.psd.Color의 색조(도 단위). 색조는 HSB 색 공간에서 0.0부터 360.0까지도로 측정됩니다.
### getIndianRed() {#getIndianRed--}
```
public static Color getIndianRed()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getIndigo() {#getIndigo--}
```
public static Color getIndigo()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getIvory() {#getIvory--}
```
public static Color getIvory()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getKhaki() {#getKhaki--}
```
public static Color getKhaki()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLavender() {#getLavender--}
```
public static Color getLavender()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLavenderBlush() {#getLavenderBlush--}
```
public static Color getLavenderBlush()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLawnGreen() {#getLawnGreen--}
```
public static Color getLawnGreen()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLemonChiffon() {#getLemonChiffon--}
```
public static Color getLemonChiffon()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightBlue() {#getLightBlue--}
```
public static Color getLightBlue()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightCoral() {#getLightCoral--}
```
public static Color getLightCoral()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightCyan() {#getLightCyan--}
```
public static Color getLightCyan()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightGoldenrodYellow() {#getLightGoldenrodYellow--}
```
public static Color getLightGoldenrodYellow()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightGray() {#getLightGray--}
```
public static Color getLightGray()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightGreen() {#getLightGreen--}
```
public static Color getLightGreen()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightPink() {#getLightPink--}
```
public static Color getLightPink()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightSalmon() {#getLightSalmon--}
```
public static Color getLightSalmon()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightSeaGreen() {#getLightSeaGreen--}
```
public static Color getLightSeaGreen()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightSkyBlue() {#getLightSkyBlue--}
```
public static Color getLightSkyBlue()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightSlateGray() {#getLightSlateGray--}
```
public static Color getLightSlateGray()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightSteelBlue() {#getLightSteelBlue--}
```
public static Color getLightSteelBlue()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightYellow() {#getLightYellow--}
```
public static Color getLightYellow()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLime() {#getLime--}
```
public static Color getLime()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLimeGreen() {#getLimeGreen--}
```
public static Color getLimeGreen()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLinen() {#getLinen--}
```
public static Color getLinen()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMagenta() {#getMagenta--}
```
public static Color getMagenta()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMaroon() {#getMaroon--}
```
public static Color getMaroon()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMediumAquamarine() {#getMediumAquamarine--}
```
public static Color getMediumAquamarine()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMediumBlue() {#getMediumBlue--}
```
public static Color getMediumBlue()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMediumOrchid() {#getMediumOrchid--}
```
public static Color getMediumOrchid()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMediumPurple() {#getMediumPurple--}
```
public static Color getMediumPurple()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMediumSeaGreen() {#getMediumSeaGreen--}
```
public static Color getMediumSeaGreen()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMediumSlateBlue() {#getMediumSlateBlue--}
```
public static Color getMediumSlateBlue()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMediumSpringGreen() {#getMediumSpringGreen--}
```
public static Color getMediumSpringGreen()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMediumTurquoise() {#getMediumTurquoise--}
```
public static Color getMediumTurquoise()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMediumVioletRed() {#getMediumVioletRed--}
```
public static Color getMediumVioletRed()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMidnightBlue() {#getMidnightBlue--}
```
public static Color getMidnightBlue()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMintCream() {#getMintCream--}
```
public static Color getMintCream()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMistyRose() {#getMistyRose--}
```
public static Color getMistyRose()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMoccasin() {#getMoccasin--}
```
public static Color getMoccasin()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getName() {#getName--}
```
public String getName()
```


이  com.aspose.psd.Color  의 이름을 가져옵니다.

**Returns:**
java.lang.String - 이 com.aspose.psd.Color의 이름.
### getNavajoWhite() {#getNavajoWhite--}
```
public static Color getNavajoWhite()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getNavy() {#getNavy--}
```
public static Color getNavy()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getOldLace() {#getOldLace--}
```
public static Color getOldLace()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getOlive() {#getOlive--}
```
public static Color getOlive()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getOliveDrab() {#getOliveDrab--}
```
public static Color getOliveDrab()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getOrange() {#getOrange--}
```
public static Color getOrange()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getOrangeRed() {#getOrangeRed--}
```
public static Color getOrangeRed()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getOrchid() {#getOrchid--}
```
public static Color getOrchid()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPaleGoldenrod() {#getPaleGoldenrod--}
```
public static Color getPaleGoldenrod()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPaleGreen() {#getPaleGreen--}
```
public static Color getPaleGreen()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPaleTurquoise() {#getPaleTurquoise--}
```
public static Color getPaleTurquoise()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPaleVioletRed() {#getPaleVioletRed--}
```
public static Color getPaleVioletRed()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPapayaWhip() {#getPapayaWhip--}
```
public static Color getPapayaWhip()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPeachPuff() {#getPeachPuff--}
```
public static Color getPeachPuff()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPeru() {#getPeru--}
```
public static Color getPeru()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPink() {#getPink--}
```
public static Color getPink()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPlum() {#getPlum--}
```
public static Color getPlum()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPowderBlue() {#getPowderBlue--}
```
public static Color getPowderBlue()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPurple() {#getPurple--}
```
public static Color getPurple()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getR() {#getR--}
```
public byte getR()
```


이  com.aspose.psd.Color  구조의 빨강 구성 요소 값을 가져옵니다.

**Returns:**
byte - 이 com.aspose.psd.Color의 빨간색 구성 요소 값.
### getRed() {#getRed--}
```
public static Color getRed()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getRosyBrown() {#getRosyBrown--}
```
public static Color getRosyBrown()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getRoyalBlue() {#getRoyalBlue--}
```
public static Color getRoyalBlue()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSaddleBrown() {#getSaddleBrown--}
```
public static Color getSaddleBrown()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSalmon() {#getSalmon--}
```
public static Color getSalmon()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSandyBrown() {#getSandyBrown--}
```
public static Color getSandyBrown()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSaturation() {#getSaturation--}
```
public float getSaturation()
```


이  com.aspose.psd.Color  구조에 대한 색조-채도-밝기(HSB) 채도 값을 가져옵니다.

**Returns:**
float - 이 com.aspose.psd.Color의 채도. 채도는 0.0부터 1.0까지이며, 0.0은 회색조, 1.0은 가장 포화된 상태를 나타냅니다.
### getSeaGreen() {#getSeaGreen--}
```
public static Color getSeaGreen()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSeaShell() {#getSeaShell--}
```
public static Color getSeaShell()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSienna() {#getSienna--}
```
public static Color getSienna()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSilver() {#getSilver--}
```
public static Color getSilver()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSkyBlue() {#getSkyBlue--}
```
public static Color getSkyBlue()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSlateBlue() {#getSlateBlue--}
```
public static Color getSlateBlue()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSlateGray() {#getSlateGray--}
```
public static Color getSlateGray()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSnow() {#getSnow--}
```
public static Color getSnow()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSpringGreen() {#getSpringGreen--}
```
public static Color getSpringGreen()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSteelBlue() {#getSteelBlue--}
```
public static Color getSteelBlue()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getTan() {#getTan--}
```
public static Color getTan()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getTeal() {#getTeal--}
```
public static Color getTeal()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getThistle() {#getThistle--}
```
public static Color getThistle()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getTomato() {#getTomato--}
```
public static Color getTomato()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getTransparent() {#getTransparent--}
```
public static Color getTransparent()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getTurquoise() {#getTurquoise--}
```
public static Color getTurquoise()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getViolet() {#getViolet--}
```
public static Color getViolet()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getWheat() {#getWheat--}
```
public static Color getWheat()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getWhite() {#getWhite--}
```
public static Color getWhite()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getWhiteSmoke() {#getWhiteSmoke--}
```
public static Color getWhiteSmoke()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getYellow() {#getYellow--}
```
public static Color getYellow()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getYellowGreen() {#getYellowGreen--}
```
public static Color getYellowGreen()
```


시스템 정의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### hashCode() {#hashCode--}
```
public int hashCode()
```


이  com.aspose.psd.Color  구조의 해시 코드를 반환합니다.

**Returns:**
int - 이 com.aspose.psd.Color에 대한 해시 코드를 지정하는 정수 값.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


이  com.aspose.psd.Color  구조가 초기화되지 않았는지 여부를 나타내는 값을 가져옵니다.

**Returns:**
boolean - 이 속성은 색상이 초기화되지 않은 경우 true를 반환하고, 그렇지 않으면 false를 반환합니다.
### isEquals(Color obj1, Color obj2) {#isEquals-com.aspose.psd.Color-com.aspose.psd.Color-}
```
public static boolean isEquals(Color obj1, Color obj2)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj1 | [Color](../../com.aspose.psd/color) |  |
| obj2 | [Color](../../com.aspose.psd/color) |  |

**Returns:**
boolean
### isKnownColor() {#isKnownColor--}
```
public boolean isKnownColor()
```


이 com.aspose.psd.Color 구조가 사전 정의된 색상인지 여부를 나타내는 값을 가져옵니다. 사전 정의된 색상은 Aspose.Imaging.KnownColor 열거형의 요소로 표현됩니다.

**Returns:**
boolean - 이 com.aspose.psd.Color가 사전 정의된 색상에서 Aspose.Imaging.Color.FromName(String) 메서드 또는 Aspose.Imaging.Color.FromKnownColor(Aspose.Imaging.KnownColor) 메서드를 사용하여 생성된 경우 true이며, 그렇지 않으면 false입니다.
### isNamedColor() {#isNamedColor--}
```
public boolean isNamedColor()
```


이  com.aspose.psd.Color  구조가 명명된 색상인지 또는 Aspose.Imaging.KnownColor 열거형의 멤버인지 여부를 나타내는 값을 가져옵니다.

**Returns:**
boolean - 이 com.aspose.psd.Color가 Aspose.Imaging.Color.FromName(String) 메서드 또는 Aspose.Imaging.Color.FromKnownColor(Aspose.Imaging.KnownColor) 메서드를 사용하여 생성된 경우 true이며, 그렇지 않으면 false입니다.
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


두 지정된  com.aspose.psd.Color  구조가 동등한지 테스트합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| left | [Color](../../com.aspose.psd/color) | 동등 연산자 왼쪽에 있는 com.aspose.psd.Color. |
| right | [Color](../../com.aspose.psd/color) | 동등 연산자 오른쪽에 있는 com.aspose.psd.Color. |

**Returns:**
boolean - 두 com.aspose.psd.Color 구조가 동일한 경우 true이며, 그렇지 않으면 false입니다.
### op_Inequality(Color left, Color right) {#op-Inequality-com.aspose.psd.Color-com.aspose.psd.Color-}
```
public static boolean op_Inequality(Color left, Color right)
```


두 지정된  com.aspose.psd.Color  구조가 다른지 테스트합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| left | [Color](../../com.aspose.psd/color) | 부등 연산자 왼쪽에 있는 com.aspose.psd.Color. |
| right | [Color](../../com.aspose.psd/color) | 부등 연산자 오른쪽에 있는 com.aspose.psd.Color. |

**Returns:**
boolean - 두 com.aspose.psd.Color 구조가 다른 경우 true이며, 그렇지 않으면 false입니다.
### toArgb() {#toArgb--}
```
public int toArgb()
```


이  com.aspose.psd.Color  구조의 32비트 ARGB 값을 가져옵니다.

**Returns:**
int - 이 com.aspose.psd.Color의 32비트 ARGB 값.
### toCmyk(Color pixel) {#toCmyk-com.aspose.psd.Color-}
```
public static CmykColor toCmyk(Color pixel)
```


Color를 CmykColor로 변환합니다. 이 메서드는 사용 중단되었습니다. 보다 효율적인 CmykColorHelper.toCmyk(Color) 를 사용하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.psd/color) | RGB 형식의 Color 타입 픽셀. |

**Returns:**
[CmykColor](../../com.aspose.psd/cmykcolor) - The  CmykColor .
### toCmyk(Color[] pixels) {#toCmyk-com.aspose.psd.Color---}
```
public static CmykColor[] toCmyk(Color[] pixels)
```


Color를 CMYKColor로 변환합니다. 이 메서드는 사용 중단되었습니다. 보다 효율적인 CmykColorHelper.toCmyk(Color[]) 를 사용하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.psd/color) | RGB 형식의 Color 타입 픽셀들. |

**Returns:**
com.aspose.psd.CmykColor[] - Aspose:Imaging:CmykColor[].
### toCmykIcc(Color pixel) {#toCmykIcc-com.aspose.psd.Color-}
```
public static CmykColor toCmykIcc(Color pixel)
```


기본 프로파일을 사용한 icc 변환으로 Color를 CMYKColor로 변환합니다. 이 메서드는 사용 중단되었습니다. 보다 효율적인 CmykColorHelper.toCmykIcc(Color) 를 사용하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.psd/color) | RGB 형식의 Color 타입 픽셀. |

**Returns:**
[CmykColor](../../com.aspose.psd/cmykcolor) - The  CmykColor .
### toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIcc-com.aspose.psd.Color-java.io.InputStream-java.io.InputStream-}
```
public static CmykColor toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream)
```


Color에서 CMYKColor로 icc 변환을 기본 프로파일을 사용하여 수행합니다. 이 메서드는 더 이상 사용되지 않습니다. 보다 효율적인 CmykColorHelper.toCmykIcc(Color, InputStream, InputStream)를 사용하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.psd/color) | RGB 형식의 Color 타입 픽셀. |
| rgbIccStream | java.io.InputStream | icc rgb 프로파일을 포함하는 스트림입니다. |
| cmykIccStream | java.io.InputStream | icc cmyk 프로파일을 포함하는 스트림입니다. |

**Returns:**
[CmykColor](../../com.aspose.psd/cmykcolor) - The  CmykColor[] .
### toCmykIcc(Color[] pixels) {#toCmykIcc-com.aspose.psd.Color---}
```
public static CmykColor[] toCmykIcc(Color[] pixels)
```


Color에서 CMYKColor로 icc 변환을 기본 프로파일을 사용하여 수행합니다. 이 메서드는 더 이상 사용되지 않습니다. 보다 효율적인 CmykColorHelper.toCmykIcc(Color[])를 사용하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.psd/color) | RGB 형식의 Color 타입 픽셀들. |

**Returns:**
com.aspose.psd.CmykColor[] - CmykColor[] 입니다.
### toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIcc-com.aspose.psd.Color---java.io.InputStream-java.io.InputStream-}
```
public static CmykColor[] toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)
```


icc 변환을 사용하여 Color를 CMYKColor로 변환합니다. 이 메서드는 더 이상 사용되지 않습니다. 보다 효율적인 CmykColorHelper.toCmykIcc(Color[], InputStream, InputStream)를 사용하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.psd/color) | RGB 형식의 Color 타입 픽셀들. |
| rgbIccStream | java.io.InputStream | icc rgb 프로파일을 포함하는 스트림입니다. |
| cmykIccStream | java.io.InputStream | icc cmyk 프로파일을 포함하는 스트림입니다. |

**Returns:**
com.aspose.psd.CmykColor[] - CmykColor[] 입니다.
### toCmykIcc_internalized(Color pixel, System.IO.Stream rgbIccStream, System.IO.Stream cmykIccStream) {#toCmykIcc-internalized-com.aspose.psd.Color-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-}
```
public static CmykColor toCmykIcc_internalized(Color pixel, System.IO.Stream rgbIccStream, System.IO.Stream cmykIccStream)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
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
| 매개변수 | 형식 | 설명 |
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


이 com.aspose.psd.Color 구조체의 Aspose.Imaging.KnownColor 값을 가져옵니다.

**Returns:**
int - com.aspose.psd.Color가 사전 정의된 색상으로 Aspose.Imaging.Color.FromName(String) 메서드 또는 Aspose.Imaging.Color.FromKnownColor(Aspose.Imaging.KnownColor) 메서드를 사용하여 생성된 경우 Aspose.Imaging.KnownColor 열거형의 요소이며, 그렇지 않은 경우 0입니다.
### toString() {#toString--}
```
public String toString()
```


이 com.aspose.psd.Color 구조체를 사람이 읽을 수 있는 문자열로 변환합니다.

**Returns:**
java.lang.String - com.aspose.psd.Color가 사전 정의된 색상으로 Aspose.Imaging.Color.FromName(String) 메서드 또는 Aspose.Imaging.Color.FromKnownColor(Aspose.Imaging.KnownColor) 메서드를 사용하여 생성된 경우 해당 com.aspose.psd.Color의 이름을 나타내는 문자열이며, 그렇지 않은 경우 ARGB 구성 요소 이름과 그 값으로 구성된 문자열입니다.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

