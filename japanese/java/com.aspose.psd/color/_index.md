---
title: "カラー"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "ピクセルの色。"
type: docs
weight: 19
url: /ja/java/com.aspose.psd/color/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class Color extends Struct<Color>
```

ピクセルの色。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [Color()](#Color--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(Color that)](#CloneTo-com.aspose.psd.Color-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | 指定されたオブジェクトが com.aspose.psd.Color 構造体であり、この com.aspose.psd.Color 構造体と等価かどうかをテストします。 |
| [fromArgb(byte red, byte green, byte blue)](#fromArgb-byte-byte-byte-) | 指定された8ビットカラー値（赤、緑、青）から  com.aspose.psd.Color  構造体を作成します。 |
| [fromArgb(byte alpha, byte red, byte green, byte blue)](#fromArgb-byte-byte-byte-byte-) | 4つのARGBコンポーネント（アルファ、赤、緑、青）の値から  com.aspose.psd.Color  構造体を作成します。 |
| [fromArgb(int argb)](#fromArgb-int-) | 32ビットARGB値から  com.aspose.psd.Color  構造体を作成します。 |
| [fromArgb(int alpha, Color baseColor)](#fromArgb-int-com.aspose.psd.Color-) | 指定された  com.aspose.psd.Color  構造体から、新しい指定されたアルファ値を使用して  com.aspose.psd.Color  構造体を作成します。 |
| [fromArgb(int red, int green, int blue)](#fromArgb-int-int-int-) | 指定された8ビットカラー値（赤、緑、青）から  com.aspose.psd.Color  構造体を作成します。 |
| [fromArgb(int alpha, int red, int green, int blue)](#fromArgb-int-int-int-int-) | 4つのARGBコンポーネント（アルファ、赤、緑、青）の値から  com.aspose.psd.Color  構造体を作成します。 |
| [fromKnownColor(int color)](#fromKnownColor-int-) | 指定された既定のカラーから  com.aspose.psd.Color  構造体を作成します。 |
| [fromName(String name)](#fromName-java.lang.String-) | 指定された既定のカラー名から  com.aspose.psd.Color  構造体を作成します。 |
| [getA()](#getA--) | この  com.aspose.psd.Color  構造体のアルファコンポーネント値を取得します。 |
| [getAliceBlue()](#getAliceBlue--) | システム定義のカラーを取得します。 |
| [getAntiqueWhite()](#getAntiqueWhite--) | システム定義のカラーを取得します。 |
| [getAqua()](#getAqua--) | システム定義のカラーを取得します。 |
| [getAquamarine()](#getAquamarine--) | システム定義のカラーを取得します。 |
| [getAzure()](#getAzure--) | システム定義のカラーを取得します。 |
| [getB()](#getB--) | この  com.aspose.psd.Color  構造体の青コンポーネント値を取得します。 |
| [getBeige()](#getBeige--) | システム定義のカラーを取得します。 |
| [getBisque()](#getBisque--) | システム定義のカラーを取得します。 |
| [getBlack()](#getBlack--) | システム定義のカラーを取得します。 |
| [getBlanchedAlmond()](#getBlanchedAlmond--) | システム定義のカラーを取得します。 |
| [getBlue()](#getBlue--) | システム定義のカラーを取得します。 |
| [getBlueViolet()](#getBlueViolet--) | システム定義のカラーを取得します。 |
| [getBrightness()](#getBrightness--) | この  com.aspose.psd.Color  構造体の色相・彩度・明度（HSB）明度値を取得します。 |
| [getBrown()](#getBrown--) | システム定義のカラーを取得します。 |
| [getBurlyWood()](#getBurlyWood--) | システム定義のカラーを取得します。 |
| [getCadetBlue()](#getCadetBlue--) | システム定義のカラーを取得します。 |
| [getChartreuse()](#getChartreuse--) | システム定義のカラーを取得します。 |
| [getChocolate()](#getChocolate--) | システム定義のカラーを取得します。 |
| [getClass()](#getClass--) |  |
| [getCoral()](#getCoral--) | システム定義のカラーを取得します。 |
| [getCornflowerBlue()](#getCornflowerBlue--) | システム定義のカラーを取得します。 |
| [getCornsilk()](#getCornsilk--) | システム定義のカラーを取得します。 |
| [getCrimson()](#getCrimson--) | システム定義のカラーを取得します。 |
| [getCyan()](#getCyan--) | システム定義のカラーを取得します。 |
| [getDarkBlue()](#getDarkBlue--) | システム定義のカラーを取得します。 |
| [getDarkCyan()](#getDarkCyan--) | システム定義のカラーを取得します。 |
| [getDarkGoldenrod()](#getDarkGoldenrod--) | システム定義のカラーを取得します。 |
| [getDarkGray()](#getDarkGray--) | システム定義のカラーを取得します。 |
| [getDarkGreen()](#getDarkGreen--) | システム定義のカラーを取得します。 |
| [getDarkKhaki()](#getDarkKhaki--) | システム定義のカラーを取得します。 |
| [getDarkMagenta()](#getDarkMagenta--) | システム定義のカラーを取得します。 |
| [getDarkOliveGreen()](#getDarkOliveGreen--) | システム定義のカラーを取得します。 |
| [getDarkOrange()](#getDarkOrange--) | システム定義のカラーを取得します。 |
| [getDarkOrchid()](#getDarkOrchid--) | システム定義のカラーを取得します。 |
| [getDarkRed()](#getDarkRed--) | システム定義のカラーを取得します。 |
| [getDarkSalmon()](#getDarkSalmon--) | システム定義のカラーを取得します。 |
| [getDarkSeaGreen()](#getDarkSeaGreen--) | システム定義のカラーを取得します。 |
| [getDarkSlateBlue()](#getDarkSlateBlue--) | システム定義のカラーを取得します。 |
| [getDarkSlateGray()](#getDarkSlateGray--) | システム定義のカラーを取得します。 |
| [getDarkTurquoise()](#getDarkTurquoise--) | システム定義のカラーを取得します。 |
| [getDarkViolet()](#getDarkViolet--) | システム定義のカラーを取得します。 |
| [getDeepPink()](#getDeepPink--) | システム定義のカラーを取得します。 |
| [getDeepSkyBlue()](#getDeepSkyBlue--) | システム定義のカラーを取得します。 |
| [getDimGray()](#getDimGray--) | システム定義のカラーを取得します。 |
| [getDodgerBlue()](#getDodgerBlue--) | システム定義のカラーを取得します。 |
| [getEmpty()](#getEmpty--) | 空の  Color  を取得します。 |
| [getFirebrick()](#getFirebrick--) | システム定義のカラーを取得します。 |
| [getFloralWhite()](#getFloralWhite--) | システム定義のカラーを取得します。 |
| [getForestGreen()](#getForestGreen--) | システム定義のカラーを取得します。 |
| [getFuchsia()](#getFuchsia--) | システム定義のカラーを取得します。 |
| [getG()](#getG--) | この  com.aspose.psd.Color  構造体の緑コンポーネント値を取得します。 |
| [getGainsboro()](#getGainsboro--) | システム定義のカラーを取得します。 |
| [getGhostWhite()](#getGhostWhite--) | システム定義のカラーを取得します。 |
| [getGold()](#getGold--) | システム定義のカラーを取得します。 |
| [getGoldenrod()](#getGoldenrod--) | システム定義のカラーを取得します。 |
| [getGray()](#getGray--) | システム定義のカラーを取得します。 |
| [getGreen()](#getGreen--) | システム定義のカラーを取得します。 |
| [getGreenYellow()](#getGreenYellow--) | システム定義のカラーを取得します。 |
| [getHoneydew()](#getHoneydew--) | システム定義のカラーを取得します。 |
| [getHotPink()](#getHotPink--) | システム定義のカラーを取得します。 |
| [getHue()](#getHue--) | この  com.aspose.psd.Color  構造体の色相・彩度・明度（HSB）色相値（度）を取得します。 |
| [getIndianRed()](#getIndianRed--) | システム定義のカラーを取得します。 |
| [getIndigo()](#getIndigo--) | システム定義のカラーを取得します。 |
| [getIvory()](#getIvory--) | システム定義のカラーを取得します。 |
| [getKhaki()](#getKhaki--) | システム定義のカラーを取得します。 |
| [getLavender()](#getLavender--) | システム定義のカラーを取得します。 |
| [getLavenderBlush()](#getLavenderBlush--) | システム定義のカラーを取得します。 |
| [getLawnGreen()](#getLawnGreen--) | システム定義のカラーを取得します。 |
| [getLemonChiffon()](#getLemonChiffon--) | システム定義のカラーを取得します。 |
| [getLightBlue()](#getLightBlue--) | システム定義のカラーを取得します。 |
| [getLightCoral()](#getLightCoral--) | システム定義のカラーを取得します。 |
| [getLightCyan()](#getLightCyan--) | システム定義のカラーを取得します。 |
| [getLightGoldenrodYellow()](#getLightGoldenrodYellow--) | システム定義のカラーを取得します。 |
| [getLightGray()](#getLightGray--) | システム定義のカラーを取得します。 |
| [getLightGreen()](#getLightGreen--) | システム定義のカラーを取得します。 |
| [getLightPink()](#getLightPink--) | システム定義のカラーを取得します。 |
| [getLightSalmon()](#getLightSalmon--) | システム定義のカラーを取得します。 |
| [getLightSeaGreen()](#getLightSeaGreen--) | システム定義のカラーを取得します。 |
| [getLightSkyBlue()](#getLightSkyBlue--) | システム定義のカラーを取得します。 |
| [getLightSlateGray()](#getLightSlateGray--) | システム定義のカラーを取得します。 |
| [getLightSteelBlue()](#getLightSteelBlue--) | システム定義のカラーを取得します。 |
| [getLightYellow()](#getLightYellow--) | システム定義のカラーを取得します。 |
| [getLime()](#getLime--) | システム定義のカラーを取得します。 |
| [getLimeGreen()](#getLimeGreen--) | システム定義のカラーを取得します。 |
| [getLinen()](#getLinen--) | システム定義のカラーを取得します。 |
| [getMagenta()](#getMagenta--) | システム定義のカラーを取得します。 |
| [getMaroon()](#getMaroon--) | システム定義のカラーを取得します。 |
| [getMediumAquamarine()](#getMediumAquamarine--) | システム定義のカラーを取得します。 |
| [getMediumBlue()](#getMediumBlue--) | システム定義のカラーを取得します。 |
| [getMediumOrchid()](#getMediumOrchid--) | システム定義のカラーを取得します。 |
| [getMediumPurple()](#getMediumPurple--) | システム定義のカラーを取得します。 |
| [getMediumSeaGreen()](#getMediumSeaGreen--) | システム定義のカラーを取得します。 |
| [getMediumSlateBlue()](#getMediumSlateBlue--) | システム定義のカラーを取得します。 |
| [getMediumSpringGreen()](#getMediumSpringGreen--) | システム定義のカラーを取得します。 |
| [getMediumTurquoise()](#getMediumTurquoise--) | システム定義のカラーを取得します。 |
| [getMediumVioletRed()](#getMediumVioletRed--) | システム定義のカラーを取得します。 |
| [getMidnightBlue()](#getMidnightBlue--) | システム定義のカラーを取得します。 |
| [getMintCream()](#getMintCream--) | システム定義のカラーを取得します。 |
| [getMistyRose()](#getMistyRose--) | システム定義のカラーを取得します。 |
| [getMoccasin()](#getMoccasin--) | システム定義のカラーを取得します。 |
| [getName()](#getName--) | この  com.aspose.psd.Color  の名前を取得します。 |
| [getNavajoWhite()](#getNavajoWhite--) | システム定義のカラーを取得します。 |
| [getNavy()](#getNavy--) | システム定義のカラーを取得します。 |
| [getOldLace()](#getOldLace--) | システム定義のカラーを取得します。 |
| [getOlive()](#getOlive--) | システム定義のカラーを取得します。 |
| [getOliveDrab()](#getOliveDrab--) | システム定義のカラーを取得します。 |
| [getOrange()](#getOrange--) | システム定義のカラーを取得します。 |
| [getOrangeRed()](#getOrangeRed--) | システム定義のカラーを取得します。 |
| [getOrchid()](#getOrchid--) | システム定義のカラーを取得します。 |
| [getPaleGoldenrod()](#getPaleGoldenrod--) | システム定義のカラーを取得します。 |
| [getPaleGreen()](#getPaleGreen--) | システム定義のカラーを取得します。 |
| [getPaleTurquoise()](#getPaleTurquoise--) | システム定義のカラーを取得します。 |
| [getPaleVioletRed()](#getPaleVioletRed--) | システム定義のカラーを取得します。 |
| [getPapayaWhip()](#getPapayaWhip--) | システム定義のカラーを取得します。 |
| [getPeachPuff()](#getPeachPuff--) | システム定義のカラーを取得します。 |
| [getPeru()](#getPeru--) | システム定義のカラーを取得します。 |
| [getPink()](#getPink--) | システム定義のカラーを取得します。 |
| [getPlum()](#getPlum--) | システム定義のカラーを取得します。 |
| [getPowderBlue()](#getPowderBlue--) | システム定義のカラーを取得します。 |
| [getPurple()](#getPurple--) | システム定義のカラーを取得します。 |
| [getR()](#getR--) | この  com.aspose.psd.Color  構造体の赤コンポーネント値を取得します。 |
| [getRed()](#getRed--) | システム定義のカラーを取得します。 |
| [getRosyBrown()](#getRosyBrown--) | システム定義のカラーを取得します。 |
| [getRoyalBlue()](#getRoyalBlue--) | システム定義のカラーを取得します。 |
| [getSaddleBrown()](#getSaddleBrown--) | システム定義のカラーを取得します。 |
| [getSalmon()](#getSalmon--) | システム定義のカラーを取得します。 |
| [getSandyBrown()](#getSandyBrown--) | システム定義のカラーを取得します。 |
| [getSaturation()](#getSaturation--) | この  com.aspose.psd.Color  構造体の色相・彩度・明度（HSB）彩度値を取得します。 |
| [getSeaGreen()](#getSeaGreen--) | システム定義のカラーを取得します。 |
| [getSeaShell()](#getSeaShell--) | システム定義のカラーを取得します。 |
| [getSienna()](#getSienna--) | システム定義のカラーを取得します。 |
| [getSilver()](#getSilver--) | システム定義のカラーを取得します。 |
| [getSkyBlue()](#getSkyBlue--) | システム定義のカラーを取得します。 |
| [getSlateBlue()](#getSlateBlue--) | システム定義のカラーを取得します。 |
| [getSlateGray()](#getSlateGray--) | システム定義のカラーを取得します。 |
| [getSnow()](#getSnow--) | システム定義のカラーを取得します。 |
| [getSpringGreen()](#getSpringGreen--) | システム定義のカラーを取得します。 |
| [getSteelBlue()](#getSteelBlue--) | システム定義のカラーを取得します。 |
| [getTan()](#getTan--) | システム定義のカラーを取得します。 |
| [getTeal()](#getTeal--) | システム定義のカラーを取得します。 |
| [getThistle()](#getThistle--) | システム定義のカラーを取得します。 |
| [getTomato()](#getTomato--) | システム定義のカラーを取得します。 |
| [getTransparent()](#getTransparent--) | システム定義のカラーを取得します。 |
| [getTurquoise()](#getTurquoise--) | システム定義のカラーを取得します。 |
| [getViolet()](#getViolet--) | システム定義のカラーを取得します。 |
| [getWheat()](#getWheat--) | システム定義のカラーを取得します。 |
| [getWhite()](#getWhite--) | システム定義のカラーを取得します。 |
| [getWhiteSmoke()](#getWhiteSmoke--) | システム定義のカラーを取得します。 |
| [getYellow()](#getYellow--) | システム定義のカラーを取得します。 |
| [getYellowGreen()](#getYellowGreen--) | システム定義のカラーを取得します。 |
| [hashCode()](#hashCode--) | この  com.aspose.psd.Color  構造体のハッシュコードを返します。 |
| [isEmpty()](#isEmpty--) | この  com.aspose.psd.Color  構造体が未初期化かどうかを示す値を取得します。 |
| [isEquals(Color obj1, Color obj2)](#isEquals-com.aspose.psd.Color-com.aspose.psd.Color-) |  |
| [isKnownColor()](#isKnownColor--) | この  com.aspose.psd.Color  構造体が既定のカラーかどうかを示す値を取得します。 |
| [isNamedColor()](#isNamedColor--) | この  com.aspose.psd.Color  構造体が名前付きカラーか、または  Aspose.Imaging.KnownColor  列挙体のメンバーかどうかを示す値を取得します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Equality(Color left, Color right)](#op-Equality-com.aspose.psd.Color-com.aspose.psd.Color-) | 指定された2つの  com.aspose.psd.Color  構造体が等価かどうかをテストします。 |
| [op_Inequality(Color left, Color right)](#op-Inequality-com.aspose.psd.Color-com.aspose.psd.Color-) | 指定された2つの  com.aspose.psd.Color  構造体が異なるかどうかをテストします。 |
| [toArgb()](#toArgb--) | この  com.aspose.psd.Color  構造体の32ビットARGB値を取得します。 |
| [toCmyk(Color pixel)](#toCmyk-com.aspose.psd.Color-) | Color から CmykColor への変換です。 |
| [toCmyk(Color[] pixels)](#toCmyk-com.aspose.psd.Color---) | Color から CMYKColor への変換です。 |
| [toCmykIcc(Color pixel)](#toCmykIcc-com.aspose.psd.Color-) | デフォルトプロファイルを使用した ICC 変換による Color から CMYKColor への変換です。 |
| [toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIcc-com.aspose.psd.Color-java.io.InputStream-java.io.InputStream-) | デフォルトプロファイルを使用した ICC 変換による Color から CMYKColor への変換です。 |
| [toCmykIcc(Color[] pixels)](#toCmykIcc-com.aspose.psd.Color---) | デフォルトプロファイルを使用した ICC 変換による Color から CMYKColor への変換です。 |
| [toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIcc-com.aspose.psd.Color---java.io.InputStream-java.io.InputStream-) | ICC 変換による Color から CMYKColor への変換です。 |
| [toCmykIcc_internalized(Color pixel, System.IO.Stream rgbIccStream, System.IO.Stream cmykIccStream)](#toCmykIcc-internalized-com.aspose.psd.Color-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-) |  |
| [toCmykIcc_internalized(Color[] pixels, System.IO.Stream rgbIccStream, System.IO.Stream cmykIccStream)](#toCmykIcc-internalized-com.aspose.psd.Color---com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-) |  |
| [toKnownColor()](#toKnownColor--) | この com.aspose.psd.Color 構造体の Aspose.Imaging.KnownColor 値を取得します。 |
| [toString()](#toString--) | この com.aspose.psd.Color 構造体を人間が読みやすい文字列に変換します。 |
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
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(Color that) {#CloneTo-com.aspose.psd.Color-}
```
public void CloneTo(Color that)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| that | [Color](../../com.aspose.psd/color) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


指定されたオブジェクトが com.aspose.psd.Color 構造体であり、この com.aspose.psd.Color 構造体と等価かどうかをテストします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| obj | java.lang.Object | テスト対象のオブジェクトです。 |

**Returns:**
boolean - obj がこの com.aspose.psd.Color 構造体と等価な com.aspose.psd.Color 構造体である場合は true、そうでない場合は false。
### fromArgb(byte red, byte green, byte blue) {#fromArgb-byte-byte-byte-}
```
public static Color fromArgb(byte red, byte green, byte blue)
```


指定された 8 ビットのカラー値（赤、緑、青）から com.aspose.psd.Color 構造体を作成します。アルファ値は暗黙的に 255（完全に不透明）です。このメソッドは各カラーコンポーネントに 32 ビット値の指定を許可しますが、各コンポーネントの値は 8 ビットに制限されます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 赤 | byte | 新しい com.aspose.psd.Color の赤コンポーネント値です。有効な値は 0 から 255 です。 |
| 緑 | byte | 新しい com.aspose.psd.Color の緑コンポーネント値です。有効な値は 0 から 255 です。 |
| 青 | byte | 新しい com.aspose.psd.Color の青コンポーネント値です。有効な値は 0 から 255 です。 |

**Returns:**
[Color](../../com.aspose.psd/color) - The  com.aspose.psd.Color  that this method creates.
### fromArgb(byte alpha, byte red, byte green, byte blue) {#fromArgb-byte-byte-byte-byte-}
```
public static Color fromArgb(byte alpha, byte red, byte green, byte blue)
```


4 つの ARGB コンポーネント（アルファ、赤、緑、青）の値から com.aspose.psd.Color 構造体を作成します。このメソッドは各コンポーネントに 32 ビット値の指定を許可しますが、各コンポーネントの値は 8 ビットに制限されます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| アルファ | byte | アルファコンポーネントです。有効な値は 0 から 255 です。 |
| 赤 | byte | 赤コンポーネントです。有効な値は 0 から 255 です。 |
| 緑 | byte | 緑コンポーネントです。有効な値は 0 から 255 です。 |
| 青 | byte | 青コンポーネントです。有効な値は 0 から 255 です。 |

**Returns:**
[Color](../../com.aspose.psd/color) - The  com.aspose.psd.Color  that this method creates.
### fromArgb(int argb) {#fromArgb-int-}
```
public static Color fromArgb(int argb)
```


32ビットARGB値から  com.aspose.psd.Color  構造体を作成します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| argb | int | 32 ビット ARGB 値を指定する値です。 |

**Returns:**
[Color](../../com.aspose.psd/color) - The  com.aspose.psd.Color  structure that this method creates.
### fromArgb(int alpha, Color baseColor) {#fromArgb-int-com.aspose.psd.Color-}
```
public static Color fromArgb(int alpha, Color baseColor)
```


指定された com.aspose.psd.Color 構造体から新しいアルファ値を指定して com.aspose.psd.Color 構造体を作成します。このメソッドはアルファ値に 32 ビット値の指定を許可しますが、値は 8 ビットに制限されます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| アルファ | int | 新しい com.aspose.psd.Color のアルファ値です。有効な値は 0 から 255 です。 |
| baseColor | [Color](../../com.aspose.psd/color) | 新しい com.aspose.psd.Color を作成する元となる com.aspose.psd.Color です。 |

**Returns:**
[Color](../../com.aspose.psd/color) - The  com.aspose.psd.Color  that this method creates.
### fromArgb(int red, int green, int blue) {#fromArgb-int-int-int-}
```
public static Color fromArgb(int red, int green, int blue)
```


指定された 8 ビットのカラー値（赤、緑、青）から com.aspose.psd.Color 構造体を作成します。アルファ値は暗黙的に 255（完全に不透明）です。このメソッドは各カラーコンポーネントに 32 ビット値の指定を許可しますが、各コンポーネントの値は 8 ビットに制限されます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 赤 | int | 新しい com.aspose.psd.Color の赤コンポーネント値です。有効な値は 0 から 255 です。 |
| 緑 | int | 新しい com.aspose.psd.Color の緑コンポーネント値です。有効な値は 0 から 255 です。 |
| 青 | int | 新しい com.aspose.psd.Color の青コンポーネント値です。有効な値は 0 から 255 です。 |

**Returns:**
[Color](../../com.aspose.psd/color) - The  com.aspose.psd.Color  that this method creates.
### fromArgb(int alpha, int red, int green, int blue) {#fromArgb-int-int-int-int-}
```
public static Color fromArgb(int alpha, int red, int green, int blue)
```


4 つの ARGB コンポーネント（アルファ、赤、緑、青）の値から com.aspose.psd.Color 構造体を作成します。このメソッドは各コンポーネントに 32 ビット値の指定を許可しますが、各コンポーネントの値は 8 ビットに制限されます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| アルファ | int | アルファコンポーネントです。有効な値は 0 から 255 です。 |
| 赤 | int | 赤コンポーネントです。有効な値は 0 から 255 です。 |
| 緑 | int | 緑コンポーネントです。有効な値は 0 から 255 です。 |
| 青 | int | 青コンポーネントです。有効な値は 0 から 255 です。 |

**Returns:**
[Color](../../com.aspose.psd/color) - The  com.aspose.psd.Color  that this method creates.
### fromKnownColor(int color) {#fromKnownColor-int-}
```
public static Color fromKnownColor(int color)
```


指定された既定のカラーから  com.aspose.psd.Color  構造体を作成します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| カラー | int | Aspose.Imaging.KnownColor 列挙体の要素です。 |

**Returns:**
[Color](../../com.aspose.psd/color) - The  com.aspose.psd.Color  that this method creates.
### fromName(String name) {#fromName-java.lang.String-}
```
public static Color fromName(String name)
```


指定された既定のカラー名から  com.aspose.psd.Color  構造体を作成します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 名前 | java.lang.String | 事前定義されたカラーの名前を表す文字列です。有効な名前は Aspose.Imaging.KnownColor 列挙体の要素名と同じです。 |

**Returns:**
[Color](../../com.aspose.psd/color) - The  com.aspose.psd.Color  that this method creates.
### getA() {#getA--}
```
public byte getA()
```


この  com.aspose.psd.Color  構造体のアルファコンポーネント値を取得します。

**Returns:**
byte - この com.aspose.psd.Color のアルファコンポーネント値です。
### getAliceBlue() {#getAliceBlue--}
```
public static Color getAliceBlue()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getAntiqueWhite() {#getAntiqueWhite--}
```
public static Color getAntiqueWhite()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getAqua() {#getAqua--}
```
public static Color getAqua()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getAquamarine() {#getAquamarine--}
```
public static Color getAquamarine()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getAzure() {#getAzure--}
```
public static Color getAzure()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getB() {#getB--}
```
public byte getB()
```


この  com.aspose.psd.Color  構造体の青コンポーネント値を取得します。

**Returns:**
byte - この com.aspose.psd.Color の青色成分の値です。
### getBeige() {#getBeige--}
```
public static Color getBeige()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getBisque() {#getBisque--}
```
public static Color getBisque()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getBlack() {#getBlack--}
```
public static Color getBlack()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getBlanchedAlmond() {#getBlanchedAlmond--}
```
public static Color getBlanchedAlmond()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getBlue() {#getBlue--}
```
public static Color getBlue()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getBlueViolet() {#getBlueViolet--}
```
public static Color getBlueViolet()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getBrightness() {#getBrightness--}
```
public float getBrightness()
```


この  com.aspose.psd.Color  構造体の色相・彩度・明度（HSB）明度値を取得します。

**Returns:**
float - この com.aspose.psd.Color の明度です。明度は 0.0 から 1.0 の範囲で、0.0 は黒、1.0 は白を表します。
### getBrown() {#getBrown--}
```
public static Color getBrown()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getBurlyWood() {#getBurlyWood--}
```
public static Color getBurlyWood()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getCadetBlue() {#getCadetBlue--}
```
public static Color getCadetBlue()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getChartreuse() {#getChartreuse--}
```
public static Color getChartreuse()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getChocolate() {#getChocolate--}
```
public static Color getChocolate()
```


システム定義のカラーを取得します。

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


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getCornflowerBlue() {#getCornflowerBlue--}
```
public static Color getCornflowerBlue()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getCornsilk() {#getCornsilk--}
```
public static Color getCornsilk()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getCrimson() {#getCrimson--}
```
public static Color getCrimson()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getCyan() {#getCyan--}
```
public static Color getCyan()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkBlue() {#getDarkBlue--}
```
public static Color getDarkBlue()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkCyan() {#getDarkCyan--}
```
public static Color getDarkCyan()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkGoldenrod() {#getDarkGoldenrod--}
```
public static Color getDarkGoldenrod()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkGray() {#getDarkGray--}
```
public static Color getDarkGray()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkGreen() {#getDarkGreen--}
```
public static Color getDarkGreen()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkKhaki() {#getDarkKhaki--}
```
public static Color getDarkKhaki()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkMagenta() {#getDarkMagenta--}
```
public static Color getDarkMagenta()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkOliveGreen() {#getDarkOliveGreen--}
```
public static Color getDarkOliveGreen()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkOrange() {#getDarkOrange--}
```
public static Color getDarkOrange()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkOrchid() {#getDarkOrchid--}
```
public static Color getDarkOrchid()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkRed() {#getDarkRed--}
```
public static Color getDarkRed()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkSalmon() {#getDarkSalmon--}
```
public static Color getDarkSalmon()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkSeaGreen() {#getDarkSeaGreen--}
```
public static Color getDarkSeaGreen()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkSlateBlue() {#getDarkSlateBlue--}
```
public static Color getDarkSlateBlue()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkSlateGray() {#getDarkSlateGray--}
```
public static Color getDarkSlateGray()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkTurquoise() {#getDarkTurquoise--}
```
public static Color getDarkTurquoise()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDarkViolet() {#getDarkViolet--}
```
public static Color getDarkViolet()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDeepPink() {#getDeepPink--}
```
public static Color getDeepPink()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDeepSkyBlue() {#getDeepSkyBlue--}
```
public static Color getDeepSkyBlue()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDimGray() {#getDimGray--}
```
public static Color getDimGray()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getDodgerBlue() {#getDodgerBlue--}
```
public static Color getDodgerBlue()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getEmpty() {#getEmpty--}
```
public static Color getEmpty()
```


空の  Color  を取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - The empty  Color .
### getFirebrick() {#getFirebrick--}
```
public static Color getFirebrick()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getFloralWhite() {#getFloralWhite--}
```
public static Color getFloralWhite()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getForestGreen() {#getForestGreen--}
```
public static Color getForestGreen()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getFuchsia() {#getFuchsia--}
```
public static Color getFuchsia()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getG() {#getG--}
```
public byte getG()
```


この  com.aspose.psd.Color  構造体の緑コンポーネント値を取得します。

**Returns:**
byte - この com.aspose.psd.Color の緑色成分の値です。
### getGainsboro() {#getGainsboro--}
```
public static Color getGainsboro()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getGhostWhite() {#getGhostWhite--}
```
public static Color getGhostWhite()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getGold() {#getGold--}
```
public static Color getGold()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getGoldenrod() {#getGoldenrod--}
```
public static Color getGoldenrod()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getGray() {#getGray--}
```
public static Color getGray()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  structure representing a system-defined color.
### getGreen() {#getGreen--}
```
public static Color getGreen()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getGreenYellow() {#getGreenYellow--}
```
public static Color getGreenYellow()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getHoneydew() {#getHoneydew--}
```
public static Color getHoneydew()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getHotPink() {#getHotPink--}
```
public static Color getHotPink()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getHue() {#getHue--}
```
public float getHue()
```


この  com.aspose.psd.Color  構造体の色相・彩度・明度（HSB）色相値（度）を取得します。

**Returns:**
float - この com.aspose.psd.Color の色相（度）です。色相は度で測定され、HSB カラースペースで 0.0 から 360.0 の範囲です。
### getIndianRed() {#getIndianRed--}
```
public static Color getIndianRed()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getIndigo() {#getIndigo--}
```
public static Color getIndigo()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getIvory() {#getIvory--}
```
public static Color getIvory()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getKhaki() {#getKhaki--}
```
public static Color getKhaki()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLavender() {#getLavender--}
```
public static Color getLavender()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLavenderBlush() {#getLavenderBlush--}
```
public static Color getLavenderBlush()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLawnGreen() {#getLawnGreen--}
```
public static Color getLawnGreen()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLemonChiffon() {#getLemonChiffon--}
```
public static Color getLemonChiffon()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightBlue() {#getLightBlue--}
```
public static Color getLightBlue()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightCoral() {#getLightCoral--}
```
public static Color getLightCoral()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightCyan() {#getLightCyan--}
```
public static Color getLightCyan()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightGoldenrodYellow() {#getLightGoldenrodYellow--}
```
public static Color getLightGoldenrodYellow()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightGray() {#getLightGray--}
```
public static Color getLightGray()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightGreen() {#getLightGreen--}
```
public static Color getLightGreen()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightPink() {#getLightPink--}
```
public static Color getLightPink()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightSalmon() {#getLightSalmon--}
```
public static Color getLightSalmon()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightSeaGreen() {#getLightSeaGreen--}
```
public static Color getLightSeaGreen()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightSkyBlue() {#getLightSkyBlue--}
```
public static Color getLightSkyBlue()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightSlateGray() {#getLightSlateGray--}
```
public static Color getLightSlateGray()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightSteelBlue() {#getLightSteelBlue--}
```
public static Color getLightSteelBlue()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLightYellow() {#getLightYellow--}
```
public static Color getLightYellow()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLime() {#getLime--}
```
public static Color getLime()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLimeGreen() {#getLimeGreen--}
```
public static Color getLimeGreen()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getLinen() {#getLinen--}
```
public static Color getLinen()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMagenta() {#getMagenta--}
```
public static Color getMagenta()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMaroon() {#getMaroon--}
```
public static Color getMaroon()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMediumAquamarine() {#getMediumAquamarine--}
```
public static Color getMediumAquamarine()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMediumBlue() {#getMediumBlue--}
```
public static Color getMediumBlue()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMediumOrchid() {#getMediumOrchid--}
```
public static Color getMediumOrchid()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMediumPurple() {#getMediumPurple--}
```
public static Color getMediumPurple()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMediumSeaGreen() {#getMediumSeaGreen--}
```
public static Color getMediumSeaGreen()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMediumSlateBlue() {#getMediumSlateBlue--}
```
public static Color getMediumSlateBlue()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMediumSpringGreen() {#getMediumSpringGreen--}
```
public static Color getMediumSpringGreen()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMediumTurquoise() {#getMediumTurquoise--}
```
public static Color getMediumTurquoise()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMediumVioletRed() {#getMediumVioletRed--}
```
public static Color getMediumVioletRed()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMidnightBlue() {#getMidnightBlue--}
```
public static Color getMidnightBlue()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMintCream() {#getMintCream--}
```
public static Color getMintCream()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMistyRose() {#getMistyRose--}
```
public static Color getMistyRose()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getMoccasin() {#getMoccasin--}
```
public static Color getMoccasin()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getName() {#getName--}
```
public String getName()
```


この  com.aspose.psd.Color  の名前を取得します。

**Returns:**
java.lang.String - この com.aspose.psd.Color の名前です。
### getNavajoWhite() {#getNavajoWhite--}
```
public static Color getNavajoWhite()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getNavy() {#getNavy--}
```
public static Color getNavy()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getOldLace() {#getOldLace--}
```
public static Color getOldLace()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getOlive() {#getOlive--}
```
public static Color getOlive()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getOliveDrab() {#getOliveDrab--}
```
public static Color getOliveDrab()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getOrange() {#getOrange--}
```
public static Color getOrange()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getOrangeRed() {#getOrangeRed--}
```
public static Color getOrangeRed()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getOrchid() {#getOrchid--}
```
public static Color getOrchid()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPaleGoldenrod() {#getPaleGoldenrod--}
```
public static Color getPaleGoldenrod()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPaleGreen() {#getPaleGreen--}
```
public static Color getPaleGreen()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPaleTurquoise() {#getPaleTurquoise--}
```
public static Color getPaleTurquoise()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPaleVioletRed() {#getPaleVioletRed--}
```
public static Color getPaleVioletRed()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPapayaWhip() {#getPapayaWhip--}
```
public static Color getPapayaWhip()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPeachPuff() {#getPeachPuff--}
```
public static Color getPeachPuff()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPeru() {#getPeru--}
```
public static Color getPeru()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPink() {#getPink--}
```
public static Color getPink()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPlum() {#getPlum--}
```
public static Color getPlum()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPowderBlue() {#getPowderBlue--}
```
public static Color getPowderBlue()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getPurple() {#getPurple--}
```
public static Color getPurple()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getR() {#getR--}
```
public byte getR()
```


この  com.aspose.psd.Color  構造体の赤コンポーネント値を取得します。

**Returns:**
byte - この com.aspose.psd.Color の赤色成分の値です。
### getRed() {#getRed--}
```
public static Color getRed()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getRosyBrown() {#getRosyBrown--}
```
public static Color getRosyBrown()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getRoyalBlue() {#getRoyalBlue--}
```
public static Color getRoyalBlue()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSaddleBrown() {#getSaddleBrown--}
```
public static Color getSaddleBrown()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSalmon() {#getSalmon--}
```
public static Color getSalmon()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSandyBrown() {#getSandyBrown--}
```
public static Color getSandyBrown()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSaturation() {#getSaturation--}
```
public float getSaturation()
```


この  com.aspose.psd.Color  構造体の色相・彩度・明度（HSB）彩度値を取得します。

**Returns:**
float - この com.aspose.psd.Color の彩度です。彩度は 0.0 から 1.0 の範囲で、0.0 はグレースケール、1.0 は最も彩度が高い状態を表します。
### getSeaGreen() {#getSeaGreen--}
```
public static Color getSeaGreen()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSeaShell() {#getSeaShell--}
```
public static Color getSeaShell()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSienna() {#getSienna--}
```
public static Color getSienna()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSilver() {#getSilver--}
```
public static Color getSilver()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSkyBlue() {#getSkyBlue--}
```
public static Color getSkyBlue()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSlateBlue() {#getSlateBlue--}
```
public static Color getSlateBlue()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSlateGray() {#getSlateGray--}
```
public static Color getSlateGray()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSnow() {#getSnow--}
```
public static Color getSnow()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSpringGreen() {#getSpringGreen--}
```
public static Color getSpringGreen()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getSteelBlue() {#getSteelBlue--}
```
public static Color getSteelBlue()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getTan() {#getTan--}
```
public static Color getTan()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getTeal() {#getTeal--}
```
public static Color getTeal()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getThistle() {#getThistle--}
```
public static Color getThistle()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getTomato() {#getTomato--}
```
public static Color getTomato()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getTransparent() {#getTransparent--}
```
public static Color getTransparent()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getTurquoise() {#getTurquoise--}
```
public static Color getTurquoise()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getViolet() {#getViolet--}
```
public static Color getViolet()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getWheat() {#getWheat--}
```
public static Color getWheat()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getWhite() {#getWhite--}
```
public static Color getWhite()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getWhiteSmoke() {#getWhiteSmoke--}
```
public static Color getWhiteSmoke()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getYellow() {#getYellow--}
```
public static Color getYellow()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### getYellowGreen() {#getYellowGreen--}
```
public static Color getYellowGreen()
```


システム定義のカラーを取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  representing a system-defined color.
### hashCode() {#hashCode--}
```
public int hashCode()
```


この  com.aspose.psd.Color  構造体のハッシュコードを返します。

**Returns:**
int - この com.aspose.psd.Color のハッシュコードを指定する整数値です。
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


この  com.aspose.psd.Color  構造体が未初期化かどうかを示す値を取得します。

**Returns:**
boolean - このプロパティは、色が未初期化の場合は true を返し、そうでない場合は false を返します。
### isEquals(Color obj1, Color obj2) {#isEquals-com.aspose.psd.Color-com.aspose.psd.Color-}
```
public static boolean isEquals(Color obj1, Color obj2)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| obj1 | [Color](../../com.aspose.psd/color) |  |
| obj2 | [Color](../../com.aspose.psd/color) |  |

**Returns:**
boolean
### isKnownColor() {#isKnownColor--}
```
public boolean isKnownColor()
```


この com.aspose.psd.Color 構造体がプリセットカラーかどうかを示す値を取得します。プリセットカラーは Aspose.Imaging.KnownColor 列挙体の要素で表されます。

**Returns:**
boolean - この com.aspose.psd.Color が、Aspose.Imaging.Color.FromName(String) メソッドまたは Aspose.Imaging.Color.FromKnownColor(Aspose.Imaging.KnownColor) メソッドのいずれかを使用してプリセットカラーから作成された場合は true、そうでない場合は false です。
### isNamedColor() {#isNamedColor--}
```
public boolean isNamedColor()
```


この  com.aspose.psd.Color  構造体が名前付きカラーか、または  Aspose.Imaging.KnownColor  列挙体のメンバーかどうかを示す値を取得します。

**Returns:**
boolean - この com.aspose.psd.Color が、Aspose.Imaging.Color.FromName(String) メソッドまたは Aspose.Imaging.Color.FromKnownColor(Aspose.Imaging.KnownColor) メソッドのいずれかを使用して作成された場合は true、そうでない場合は false です。
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


指定された2つの  com.aspose.psd.Color  構造体が等価かどうかをテストします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| left | [Color](../../com.aspose.psd/color) | 等価演算子の左側にある com.aspose.psd.Color。 |
| right | [Color](../../com.aspose.psd/color) | 等価演算子の右側にある com.aspose.psd.Color。 |

**Returns:**
boolean - 2 つの com.aspose.psd.Color 構造体が等しい場合は true、そうでない場合は false です。
### op_Inequality(Color left, Color right) {#op-Inequality-com.aspose.psd.Color-com.aspose.psd.Color-}
```
public static boolean op_Inequality(Color left, Color right)
```


指定された2つの  com.aspose.psd.Color  構造体が異なるかどうかをテストします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| left | [Color](../../com.aspose.psd/color) | 不等価演算子の左側にある com.aspose.psd.Color。 |
| right | [Color](../../com.aspose.psd/color) | 不等価演算子の右側にある com.aspose.psd.Color。 |

**Returns:**
boolean - 2 つの com.aspose.psd.Color 構造体が異なる場合は true、そうでない場合は false です。
### toArgb() {#toArgb--}
```
public int toArgb()
```


この  com.aspose.psd.Color  構造体の32ビットARGB値を取得します。

**Returns:**
int - この com.aspose.psd.Color の 32 ビット ARGB 値です。
### toCmyk(Color pixel) {#toCmyk-com.aspose.psd.Color-}
```
public static CmykColor toCmyk(Color pixel)
```


Color から CmykColor への変換。このメソッドは非推奨です。より効果的な CmykColorHelper.toCmyk(Color) を使用してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.psd/color) | RGB 形式の Color タイプのピクセルです。 |

**Returns:**
[CmykColor](../../com.aspose.psd/cmykcolor) - The  CmykColor .
### toCmyk(Color[] pixels) {#toCmyk-com.aspose.psd.Color---}
```
public static CmykColor[] toCmyk(Color[] pixels)
```


Color から CMYKColor への変換。このメソッドは非推奨です。より効果的な CmykColorHelper.toCmyk(Color[]) を使用してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.psd/color) | RGB 形式の Color タイプのピクセル群です。 |

**Returns:**
com.aspose.psd.CmykColor[] - Aspose:Imaging:CmykColor[] です。
### toCmykIcc(Color pixel) {#toCmykIcc-com.aspose.psd.Color-}
```
public static CmykColor toCmykIcc(Color pixel)
```


デフォルトプロファイルを使用した ICC 変換により Color から CMYKColor への変換。このメソッドは非推奨です。より効果的な CmykColorHelper.toCmykIcc(Color) を使用してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.psd/color) | RGB 形式の Color タイプのピクセルです。 |

**Returns:**
[CmykColor](../../com.aspose.psd/cmykcolor) - The  CmykColor .
### toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIcc-com.aspose.psd.Color-java.io.InputStream-java.io.InputStream-}
```
public static CmykColor toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream)
```


icc 変換とデフォルトプロファイルを使用した Color から CMYKColor への変換です。このメソッドは非推奨です。より効果的な CmykColorHelper.toCmykIcc(Color, InputStream, InputStream) を使用してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.psd/color) | RGB 形式の Color タイプのピクセルです。 |
| rgbIccStream | java.io.InputStream | icc rgb プロファイルを含むストリームです。 |
| cmykIccStream | java.io.InputStream | icc cmyk プロファイルを含むストリームです。 |

**Returns:**
[CmykColor](../../com.aspose.psd/cmykcolor) - The  CmykColor[] .
### toCmykIcc(Color[] pixels) {#toCmykIcc-com.aspose.psd.Color---}
```
public static CmykColor[] toCmykIcc(Color[] pixels)
```


icc 変換とデフォルトプロファイルを使用した Color から CMYKColor への変換です。このメソッドは非推奨です。より効果的な CmykColorHelper.toCmykIcc(Color[]) を使用してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.psd/color) | RGB 形式の Color タイプのピクセル群です。 |

**Returns:**
com.aspose.psd.CmykColor[] - CmykColor[] です。
### toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIcc-com.aspose.psd.Color---java.io.InputStream-java.io.InputStream-}
```
public static CmykColor[] toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)
```


icc 変換を使用した Color から CMYKColor への変換です。このメソッドは非推奨です。より効果的な CmykColorHelper.toCmykIcc(Color[], InputStream, InputStream) を使用してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.psd/color) | RGB 形式の Color タイプのピクセル群です。 |
| rgbIccStream | java.io.InputStream | icc rgb プロファイルを含むストリームです。 |
| cmykIccStream | java.io.InputStream | icc cmyk プロファイルを含むストリームです。 |

**Returns:**
com.aspose.psd.CmykColor[] - CmykColor[] です。
### toCmykIcc_internalized(Color pixel, System.IO.Stream rgbIccStream, System.IO.Stream cmykIccStream) {#toCmykIcc-internalized-com.aspose.psd.Color-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-}
```
public static CmykColor toCmykIcc_internalized(Color pixel, System.IO.Stream rgbIccStream, System.IO.Stream cmykIccStream)
```




**Parameters:**
| パラメーター | 型 | 説明 |
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
| パラメーター | 型 | 説明 |
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


この com.aspose.psd.Color 構造体の Aspose.Imaging.KnownColor 値を取得します。

**Returns:**
int - 事前定義された色から com.aspose.psd.Color を作成する際に Aspose.Imaging.Color.FromName(String) メソッドまたは Aspose.Imaging.Color.FromKnownColor(Aspose.Imaging.KnownColor) メソッドのいずれかを使用した場合の Aspose.Imaging.KnownColor 列挙体の要素。それ以外の場合は 0。
### toString() {#toString--}
```
public String toString()
```


この com.aspose.psd.Color 構造体を人間が読みやすい文字列に変換します。

**Returns:**
java.lang.String - 事前定義された色から com.aspose.psd.Color を作成する際に Aspose.Imaging.Color.FromName(String) メソッドまたは Aspose.Imaging.Color.FromKnownColor(Aspose.Imaging.KnownColor) メソッドのいずれかを使用した場合の、この com.aspose.psd.Color の名前を表す文字列。それ以外の場合は、ARGB コンポーネント名とその値からなる文字列です。
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

