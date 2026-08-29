---
title: "CmykColor"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "ピクセルの CMYK カラーです。"
type: docs
weight: 17
url: /ja/java/com.aspose.psd/cmykcolor/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class CmykColor extends Struct<CmykColor>
```

ピクセルの CMYK カラーです。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [CmykColor()](#CmykColor--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(CmykColor that)](#CloneTo-com.aspose.psd.CmykColor-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [fromParams(int cyan, int magenta, int yellow, int black)](#fromParams-int-int-int-int-) | 32ビットのシアン、マゼンタ、イエロー、ブラックの値から  CmykColor  構造体を作成します。 |
| [getC()](#getC--) | この  com.aspose.psd.Color  構造体のシアン成分の値を取得します。 |
| [getClass()](#getClass--) |  |
| [getEmpty()](#getEmpty--) | 空の値を取得します。 |
| [getK()](#getK--) | この  com.aspose.psd.Color  構造体のブラック成分の値を取得します。 |
| [getM()](#getM--) | この  com.aspose.psd.Color  構造体のマゼンタ成分の値を取得します。 |
| [getY()](#getY--) | この  com.aspose.psd.Color  構造体のイエロー成分の値を取得します。 |
| [hashCode()](#hashCode--) | ハッシュコードを取得します。 |
| [isEmpty()](#isEmpty--) | この  com.aspose.psd.Color  構造体が未初期化かどうかを示す値を取得します。 |
| [isEquals(CmykColor obj1, CmykColor obj2)](#isEquals-com.aspose.psd.CmykColor-com.aspose.psd.CmykColor-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toArgb32(CmykColor[] cmykPixels)](#toArgb32-com.aspose.psd.CmykColor---) | デフォルトプロファイルを使用した ICC 変換により、CMYKColor から 32 ビット ARGB カラーへの変換。 |
| [toCmyk(int argbPixel)](#toCmyk-int-) | 32 ビット ARGB から CMYKColor への変換。 |
| [toCmyk(int[] argbPixels)](#toCmyk-int---) | 32 ビット ARGB カラーから CMYKColor への変換。 |
| [toColor(CmykColor cmykPixel)](#toColor-com.aspose.psd.CmykColor-) | CMYKColor から Color への変換。 |
| [toColor(CmykColor[] cmykPixels)](#toColor-com.aspose.psd.CmykColor---) | デフォルトプロファイルを使用した ICC 変換により、CMYKColor から Color への変換。 |
| [toColorIcc(CmykColor cmykPixel)](#toColorIcc-com.aspose.psd.CmykColor-) | デフォルトプロファイルを使用した ICC 変換により、CMYKColor から Color への変換。 |
| [toColorIcc(CmykColor cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream)](#toColorIcc-com.aspose.psd.CmykColor-java.io.InputStream-java.io.InputStream-) | ICC 変換を使用して、CMYKColor から Color への変換。 |
| [toColorIcc(CmykColor[] cmykPixels)](#toColorIcc-com.aspose.psd.CmykColor---) | デフォルトプロファイルを使用した ICC 変換により、CMYKColor から Color への変換。 |
| [toColorIcc(CmykColor[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream)](#toColorIcc-com.aspose.psd.CmykColor---java.io.InputStream-java.io.InputStream-) | ICC 変換を使用して、CMYKColor から Color への変換。 |
| [toColorIcc_internalized(CmykColor cmykPixel, System.IO.Stream cmykIccStream, System.IO.Stream rgbIccStream)](#toColorIcc-internalized-com.aspose.psd.CmykColor-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-) | ICC 変換を使用して、CMYKColor から Color への変換。 |
| [toColorIcc_internalized(CmykColor[] cmykPixels, System.IO.Stream cmykIccStream, System.IO.Stream rgbIccStream)](#toColorIcc-internalized-com.aspose.psd.CmykColor---com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-) | ICC 変換を使用して、CMYKColor から Color への変換。 |
| [toString()](#toString--) |  |
| [toValue()](#toValue--) | to の値。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CmykColor() {#CmykColor--}
```
public CmykColor()
```


### Clone() {#Clone--}
```
public CmykColor Clone()
```




**Returns:**
[CmykColor](../../com.aspose.psd/cmykcolor)
### CloneTo(T arg0) {#CloneTo-T-}
```
public abstract void CloneTo(T arg0)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(CmykColor that) {#CloneTo-com.aspose.psd.CmykColor-}
```
public void CloneTo(CmykColor that)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| that | [CmykColor](../../com.aspose.psd/cmykcolor) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### fromParams(int cyan, int magenta, int yellow, int black) {#fromParams-int-int-int-int-}
```
public static CmykColor fromParams(int cyan, int magenta, int yellow, int black)
```


32ビットのシアン、マゼンタ、イエロー、ブラックの値から  CmycColor  構造体を作成します。このメソッドは非推奨です。より効果的な CmykColorHelper\#fromComponents(int, int, int, int) を使用してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| シアン | int | シアン成分です。有効な値は 0 から 255 です。 |
| マゼンタ | int | マゼンタ成分です。有効な値は 0 から 255 です。 |
| 黄色 | int | 黄色成分です。有効な値は 0 から 255 です。 |
| 黒 | int | 黒成分です。有効な値は 0 から 255 です。 |

**Returns:**
[CmykColor](../../com.aspose.psd/cmykcolor) - The  CmykColor .
### getC() {#getC--}
```
public byte getC()
```


この  com.aspose.psd.Color  構造体のシアン成分の値を取得します。

**Returns:**
byte - この  com.aspose.psd.Color  のシアン成分の値。
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEmpty() {#getEmpty--}
```
public static CmykColor getEmpty()
```


空の値を取得します。

**Returns:**
[CmykColor](../../com.aspose.psd/cmykcolor)
### getK() {#getK--}
```
public byte getK()
```


この  com.aspose.psd.Color  構造体のブラック成分の値を取得します。

Value: この  com.aspose.psd.Color  のブラック成分の値。

**Returns:**
byte
### getM() {#getM--}
```
public byte getM()
```


この  com.aspose.psd.Color  構造体のマゼンタ成分の値を取得します。

**Returns:**
byte - この  com.aspose.psd.Color  のマゼンタ成分の値。
### getY() {#getY--}
```
public byte getY()
```


この  com.aspose.psd.Color  構造体のイエロー成分の値を取得します。

**Returns:**
byte - この  com.aspose.psd.Color  のイエロー成分の値。
### hashCode() {#hashCode--}
```
public int hashCode()
```


ハッシュコードを取得します。

**Returns:**
int - int。
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


この  com.aspose.psd.Color  構造体が未初期化かどうかを示す値を取得します。

**Returns:**
boolean - このプロパティは、色が未初期化の場合は true を返し、そうでない場合は false を返します。
### isEquals(CmykColor obj1, CmykColor obj2) {#isEquals-com.aspose.psd.CmykColor-com.aspose.psd.CmykColor-}
```
public static boolean isEquals(CmykColor obj1, CmykColor obj2)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| obj1 | [CmykColor](../../com.aspose.psd/cmykcolor) |  |
| obj2 | [CmykColor](../../com.aspose.psd/cmykcolor) |  |

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### toArgb32(CmykColor[] cmykPixels) {#toArgb32-com.aspose.psd.CmykColor---}
```
public static int[] toArgb32(CmykColor[] cmykPixels)
```


デフォルトプロファイルを使用した ICC 変換により、CMYKColor から 32 ビット ARGB カラーへの変換。このメソッドは非推奨です。より効果的な  CmykColorHelper.toArgb32(int[]) を使用してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.psd/cmykcolor) | CMYK 形式の CMYKColor タイプのピクセル。 |

**Returns:**
int[] - 32 ビット ARGB カラーの配列。
### toCmyk(int argbPixel) {#toCmyk-int-}
```
public static CmykColor toCmyk(int argbPixel)
```


32 ビット ARGB から CMYKColor への変換。このメソッドは非推奨です。より効果的な  CmykColorHelper.toCmyk(int) を使用してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| argbPixel | int | 32ビット ARGB フォーマットのピクセル。 |

**Returns:**
[CmykColor](../../com.aspose.psd/cmykcolor) - The  Aspose:Imaging:CmykColor .
### toCmyk(int[] argbPixels) {#toCmyk-int---}
```
public static CmykColor[] toCmyk(int[] argbPixels)
```


32ビット ARGB カラーから CMYKColor への変換。このメソッドは非推奨です。より効果的な CmykColorHelper.toCmyk(int[]) を使用してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| argbPixels | int[] | 32ビット ARGB フォーマットのピクセル。 |

**Returns:**
com.aspose.psd.CmykColor[] - Aspose:Imaging:CmykColor[] です。
### toColor(CmykColor cmykPixel) {#toColor-com.aspose.psd.CmykColor-}
```
public static Color toColor(CmykColor cmykPixel)
```


CMYKColor から Color への変換。このメソッドは非推奨です。より効果的な CmykColorHelper.toArgb(int) を使用してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| cmykPixel | [CmykColor](../../com.aspose.psd/cmykcolor) | CMYK 形式の CMYKColor タイプのピクセル。 |

**Returns:**
[Color](../../com.aspose.psd/color) - The  Aspose.Imaging.Color[] .
### toColor(CmykColor[] cmykPixels) {#toColor-com.aspose.psd.CmykColor---}
```
public static Color[] toColor(CmykColor[] cmykPixels)
```


デフォルトプロファイルを使用した ICC 変換で CMYKColor から Color への変換。このメソッドは非推奨です。より効果的な CmykColorHelper.toArgb(int[]) を使用してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.psd/cmykcolor) | CMYK 形式の CMYKColor タイプのピクセル。 |

**Returns:**
com.aspose.psd.Color[] - ARGB カラーの配列です。
### toColorIcc(CmykColor cmykPixel) {#toColorIcc-com.aspose.psd.CmykColor-}
```
public static Color toColorIcc(CmykColor cmykPixel)
```


デフォルトプロファイルを使用した ICC 変換で CMYKColor から Color への変換。このメソッドは非推奨です。より効果的な CmykColorHelper.toArgbIcc(int) を使用してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| cmykPixel | [CmykColor](../../com.aspose.psd/cmykcolor) | CMYK フォーマットの CMYKColor 型のピクセルです。 |

**Returns:**
[Color](../../com.aspose.psd/color) - The  Color .
### toColorIcc(CmykColor cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream) {#toColorIcc-com.aspose.psd.CmykColor-java.io.InputStream-java.io.InputStream-}
```
public static Color toColorIcc(CmykColor cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream)
```


ICC 変換で CMYKColor から Color への変換。このメソッドは非推奨です。より効果的な CmykColorHelper.toArgbIcc(int, Stream, Stream) を使用してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| cmykPixel | [CmykColor](../../com.aspose.psd/cmykcolor) | CMYK フォーマットの CMYKColor 型のピクセルです。 |
| cmykIccStream | java.io.InputStream | icc cmyk プロファイルを含むストリームです。 |
| rgbIccStream | java.io.InputStream | icc rgb プロファイルを含むストリームです。 |

**Returns:**
[Color](../../com.aspose.psd/color) - The  Color .
### toColorIcc(CmykColor[] cmykPixels) {#toColorIcc-com.aspose.psd.CmykColor---}
```
public static Color[] toColorIcc(CmykColor[] cmykPixels)
```


デフォルトプロファイルを使用した ICC 変換で CMYKColor から Color への変換。このメソッドは非推奨です。より効果的な CmykColorHelper\#toArgbIcc(int[]) を使用してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.psd/cmykcolor) | CMYK 形式の CMYKColor タイプのピクセル。 |

**Returns:**
com.aspose.psd.Color[] - com.aspose.psd.Color[] です。
### toColorIcc(CmykColor[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream) {#toColorIcc-com.aspose.psd.CmykColor---java.io.InputStream-java.io.InputStream-}
```
public static Color[] toColorIcc(CmykColor[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream)
```


ICC 変換で CMYKColor から Color への変換。このメソッドは非推奨です。より効果的な CmykColorHelper.toArgbIcc(int[], InputStream, InputStream) を使用してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.psd/cmykcolor) | CMYK 形式の CMYKColor タイプのピクセル。 |
| cmykIccStream | java.io.InputStream | icc cmyk プロファイルを含むストリームです。 |
| rgbIccStream | java.io.InputStream | icc rgb プロファイルを含むストリームです。 |

**Returns:**
com.aspose.psd.Color[] - Aspose.Imaging.Color[] です。
### toColorIcc_internalized(CmykColor cmykPixel, System.IO.Stream cmykIccStream, System.IO.Stream rgbIccStream) {#toColorIcc-internalized-com.aspose.psd.CmykColor-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-}
```
public static Color toColorIcc_internalized(CmykColor cmykPixel, System.IO.Stream cmykIccStream, System.IO.Stream rgbIccStream)
```


ICC 変換を使用して、CMYKColor から Color への変換。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| cmykPixel | [CmykColor](../../com.aspose.psd/cmykcolor) | CMYK フォーマットの CMYKColor 型のピクセルです。 |
| cmykIccStream | com.aspose.ms.System.IO.Stream | icc cmyk プロファイルを含むストリームです。 |
| rgbIccStream | com.aspose.ms.System.IO.Stream | icc rgb プロファイルを含むストリームです。 |

**Returns:**
[Color](../../com.aspose.psd/color) - The  Color .
### toColorIcc_internalized(CmykColor[] cmykPixels, System.IO.Stream cmykIccStream, System.IO.Stream rgbIccStream) {#toColorIcc-internalized-com.aspose.psd.CmykColor---com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-}
```
public static Color[] toColorIcc_internalized(CmykColor[] cmykPixels, System.IO.Stream cmykIccStream, System.IO.Stream rgbIccStream)
```


ICC 変換を使用して、CMYKColor から Color への変換。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.psd/cmykcolor) | CMYK 形式の CMYKColor タイプのピクセル。 |
| cmykIccStream | com.aspose.ms.System.IO.Stream | icc cmyk プロファイルを含むストリームです。 |
| rgbIccStream | com.aspose.ms.System.IO.Stream | icc rgb プロファイルを含むストリームです。 |

**Returns:**
com.aspose.psd.Color[] - Aspose.Imaging.Color[] です。
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### toValue() {#toValue--}
```
public long toValue()
```


to の値。

**Returns:**
long - long 型です。
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

