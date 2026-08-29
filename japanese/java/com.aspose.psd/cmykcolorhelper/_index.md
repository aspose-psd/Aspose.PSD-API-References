---
title: "CmykColorHelper"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "CMYK カラーを符号付き 32 ビット整数値として扱うヘルパーメソッド。"
type: docs
weight: 18
url: /ja/java/com.aspose.psd/cmykcolorhelper/
---

**Inheritance:**
java.lang.Object
```
public final class CmykColorHelper
```

CMYK カラーを符号付き 32 ビット整数値として扱うためのヘルパーメソッドです。com.aspose.psd.CmykColor 構造体と同様の API を提供します。CMYK カラーが構造体の内部フィールドではなく Int32 として表現されるため、より軽量です。可能な限り、非推奨となった com.aspose.psd.CmykColor 構造体の代わりに、このクラスの静的メソッドを使用してください。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fromComponents(int cyan, int magenta, int yellow, int black)](#fromComponents-int-int-int-int-) | 32 ビットのシアン、マゼンタ、イエロー、ブラック値から CMYK を作成します。 |
| [getC(int cmyk)](#getC-int-) | シアン成分の値を取得します。 |
| [getClass()](#getClass--) |  |
| [getK(int cmyk)](#getK-int-) | ブラック成分の値を取得します。 |
| [getM(int cmyk)](#getM-int-) | マゼンタ成分の値を取得します。 |
| [getY(int cmyk)](#getY-int-) | 黄色コンポーネントの値を取得します。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toArgb(int cmykPixel)](#toArgb-int-) | CMYK カラーから ARGB カラーへの変換です。 |
| [toArgb(int[] cmykPixels)](#toArgb-int---) | CMYK カラーから ARGB カラーへの変換です。 |
| [toArgb32(int[] cmykPixels)](#toArgb32-int---) | CMYK カラーから ARGB カラーへの変換です。 |
| [toArgbIcc(int cmykPixel)](#toArgbIcc-int-) | デフォルトプロファイルを使用した Icc 変換により、CMYK カラーから ARGB カラーへの変換です。 |
| [toArgbIcc(int cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream)](#toArgbIcc-int-java.io.InputStream-java.io.InputStream-) | カスタムプロファイルを使用した Icc 変換により、CMYK カラーから ARGB カラーへの変換です。 |
| [toArgbIcc(int[] cmykPixels)](#toArgbIcc-int---) | デフォルトプロファイルを使用した Icc 変換により、CMYK カラーから ARGB カラーへの変換です。 |
| [toArgbIcc(int[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream)](#toArgbIcc-int---java.io.InputStream-java.io.InputStream-) | カスタムプロファイルを使用した Icc 変換により、CMYK カラーから ARGB カラーへの変換です。 |
| [toCmyk(Color pixel)](#toCmyk-com.aspose.psd.Color-) | ARGB カラーから CMYK カラーへの変換です。 |
| [toCmyk(Color[] pixels)](#toCmyk-com.aspose.psd.Color---) | ARGB カラーから CMYK カラーへの変換です。 |
| [toCmyk(int argbPixel)](#toCmyk-int-) | ARGB カラーから CMYK カラーへの変換です。 |
| [toCmyk(int[] argbPixels)](#toCmyk-int---) | ARGB カラーから CMYK カラーへの変換です。 |
| [toCmykBytes(int[] argbPixels, int startIndex, int length)](#toCmykBytes-int---int-int-) | RGB を CMYK に変換します。 |
| [toCmykIcc(Color pixel)](#toCmykIcc-com.aspose.psd.Color-) | デフォルトプロファイルを使用した Icc 変換により、ARGB カラーから CMYK カラーへの変換です。 |
| [toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIcc-com.aspose.psd.Color-java.io.InputStream-java.io.InputStream-) | カスタムプロファイルを使用した Icc 変換により、ARGB カラーから CMYK カラーへの変換です。 |
| [toCmykIcc(Color[] pixels)](#toCmykIcc-com.aspose.psd.Color---) | デフォルトプロファイルを使用した Icc 変換により、ARGB カラーから CMYK カラーへの変換です。 |
| [toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIcc-com.aspose.psd.Color---java.io.InputStream-java.io.InputStream-) | カスタムプロファイルを使用した Icc 変換により、ARGB カラーから CMYK カラーへの変換です。 |
| [toCmykIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIccBytes-int---int-int-java.io.InputStream-java.io.InputStream-) | カスタム ICC プロファイルを使用して RGB を CMYK に変換します。 |
| [toCmykIccBytes_internalized(int[] pixels, int startIndex, int length, System.IO.Stream rgbIccStream, System.IO.Stream cmykIccStream)](#toCmykIccBytes-internalized-int---int-int-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fromComponents(int cyan, int magenta, int yellow, int black) {#fromComponents-int-int-int-int-}
```
public static int fromComponents(int cyan, int magenta, int yellow, int black)
```


32 ビットのシアン、マゼンタ、イエロー、ブラック値から CMYK を作成します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| シアン | int | シアン成分です。有効な値は 0 から 255 です。 |
| マゼンタ | int | マゼンタ成分です。有効な値は 0 から 255 です。 |
| 黄色 | int | 黄色成分です。有効な値は 0 から 255 です。 |
| 黒 | int | 黒成分です。有効な値は 0 から 255 です。 |

**Returns:**
int - 32 ビット整数値として表現された CMYK カラーです。
### getC(int cmyk) {#getC-int-}
```
public static int getC(int cmyk)
```


シアン成分の値を取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| cmyk | int | 32 ビット整数値として表現された CMYK カラーです。 |

**Returns:**
int - シアン成分の値です。
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getK(int cmyk) {#getK-int-}
```
public static int getK(int cmyk)
```


ブラック成分の値を取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| cmyk | int | 32 ビット整数値として表現された CMYK カラーです。 |

**Returns:**
int - 黒成分の値です。
### getM(int cmyk) {#getM-int-}
```
public static int getM(int cmyk)
```


マゼンタ成分の値を取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| cmyk | int | 32 ビット整数値として表現された CMYK カラーです。 |

**Returns:**
int - マゼンタ成分の値です。
### getY(int cmyk) {#getY-int-}
```
public static int getY(int cmyk)
```


黄色コンポーネントの値を取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| cmyk | int | 32 ビット整数値として表現された CMYK カラーです。 |

**Returns:**
int - 黄色成分の値。
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### toArgb(int cmykPixel) {#toArgb-int-}
```
public static Color toArgb(int cmykPixel)
```


CMYK カラーから ARGB カラーへの変換です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| cmykPixel | int | 32 ビット整数値として表現された CMYK カラーです。 |

**Returns:**
[Color](../../com.aspose.psd/color) - The ARGB color.
### toArgb(int[] cmykPixels) {#toArgb-int---}
```
public static Color[] toArgb(int[] cmykPixels)
```


CMYK カラーから ARGB カラーへの変換です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| cmykPixels | int[] | CMYKカラーは32ビット整数値として表現されます。 |

**Returns:**
com.aspose.psd.Color[] - ARGBカラー。
### toArgb32(int[] cmykPixels) {#toArgb32-int---}
```
public static int[] toArgb32(int[] cmykPixels)
```


CMYK カラーから ARGB カラーへの変換です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| cmykPixels | int[] | CMYKカラーは32ビット整数値として表現されます。 |

**Returns:**
int[] - ARGBカラーは32ビット整数値として表現されます。
### toArgbIcc(int cmykPixel) {#toArgbIcc-int-}
```
public static Color toArgbIcc(int cmykPixel)
```


デフォルトプロファイルを使用した Icc 変換により、CMYK カラーから ARGB カラーへの変換です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| cmykPixel | int | 32 ビット整数値として表現された CMYK カラーです。 |

**Returns:**
[Color](../../com.aspose.psd/color) - The ARGB color.
### toArgbIcc(int cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream) {#toArgbIcc-int-java.io.InputStream-java.io.InputStream-}
```
public static Color toArgbIcc(int cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream)
```


カスタムプロファイルを使用した Icc 変換により、CMYK カラーから ARGB カラーへの変換です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| cmykPixel | int | 32 ビット整数値として表現された CMYK カラーです。 |
| cmykIccStream | java.io.InputStream | CMYK Iccプロファイルを含むストリーム。 |
| rgbIccStream | java.io.InputStream | RGB Iccプロファイルを含むストリーム。 |

**Returns:**
[Color](../../com.aspose.psd/color) - The ARGB color.
### toArgbIcc(int[] cmykPixels) {#toArgbIcc-int---}
```
public static Color[] toArgbIcc(int[] cmykPixels)
```


デフォルトプロファイルを使用した Icc 変換により、CMYK カラーから ARGB カラーへの変換です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| cmykPixels | int[] | CMYKピクセルは32ビット整数値として表現されます。 |

**Returns:**
com.aspose.psd.Color[] - ARGBカラー。
### toArgbIcc(int[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream) {#toArgbIcc-int---java.io.InputStream-java.io.InputStream-}
```
public static Color[] toArgbIcc(int[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream)
```


カスタムプロファイルを使用した Icc 変換により、CMYK カラーから ARGB カラーへの変換です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| cmykPixels | int[] | CMYKカラーは32ビット整数値として表現されます。 |
| cmykIccStream | java.io.InputStream | CMYK Iccプロファイルを含むストリーム。 |
| rgbIccStream | java.io.InputStream | RGB Iccプロファイルを含むストリーム。 |

**Returns:**
com.aspose.psd.Color[] - ARGBカラー。
### toCmyk(Color pixel) {#toCmyk-com.aspose.psd.Color-}
```
public static int toCmyk(Color pixel)
```


ARGB カラーから CMYK カラーへの変換です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.psd/color) | ARGBカラー。 |

**Returns:**
int - 32 ビット整数値として表現された CMYK カラーです。
### toCmyk(Color[] pixels) {#toCmyk-com.aspose.psd.Color---}
```
public static int[] toCmyk(Color[] pixels)
```


ARGB カラーから CMYK カラーへの変換です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.psd/color) | ARGBカラー。 |

**Returns:**
int[] - CMYKカラーは32ビット整数値として表現されます。
### toCmyk(int argbPixel) {#toCmyk-int-}
```
public static int toCmyk(int argbPixel)
```


ARGB カラーから CMYK カラーへの変換です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| argbPixel | int | ARGBカラーは32ビット整数値として表現されます。 |

**Returns:**
int - 32 ビット整数値として表現された CMYK カラーです。
### toCmyk(int[] argbPixels) {#toCmyk-int---}
```
public static int[] toCmyk(int[] argbPixels)
```


ARGB カラーから CMYK カラーへの変換です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| argbPixels | int[] | ARGBカラーは32ビット整数値として表現されます。 |

**Returns:**
int[] - CMYKカラーは32ビット整数値として表現されます。
### toCmykBytes(int[] argbPixels, int startIndex, int length) {#toCmykBytes-int---int-int-}
```
public static byte[] toCmykBytes(int[] argbPixels, int startIndex, int length)
```


RGB を CMYK に変換します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| argbPixels | int[] | RGBカラーは32ビット整数値として表現されます。 |
| startIndex | int | RGBカラーの開始インデックス。 |
| length | int | 変換するRGBピクセルの数。 |

**Returns:**
byte[] - CMYKカラーはバイト配列として表現されます。
### toCmykIcc(Color pixel) {#toCmykIcc-com.aspose.psd.Color-}
```
public static int toCmykIcc(Color pixel)
```


デフォルトプロファイルを使用した Icc 変換により、ARGB カラーから CMYK カラーへの変換です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.psd/color) | ARGBカラー。 |

**Returns:**
int - 32 ビット整数値として表現された CMYK カラーです。
### toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIcc-com.aspose.psd.Color-java.io.InputStream-java.io.InputStream-}
```
public static int toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream)
```


カスタムプロファイルを使用した Icc 変換により、ARGB カラーから CMYK カラーへの変換です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.psd/color) | ARGBカラー。 |
| rgbIccStream | java.io.InputStream | RGB Iccプロファイルを含むストリーム。 |
| cmykIccStream | java.io.InputStream | CMYK Iccプロファイルを含むストリーム。 |

**Returns:**
int - 32 ビット整数値として表現された CMYK カラーです。
### toCmykIcc(Color[] pixels) {#toCmykIcc-com.aspose.psd.Color---}
```
public static int[] toCmykIcc(Color[] pixels)
```


デフォルトプロファイルを使用した Icc 変換により、ARGB カラーから CMYK カラーへの変換です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.psd/color) | ARGBカラー。 |

**Returns:**
int[] - CMYKカラーは32ビット整数値として表現されます。
### toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIcc-com.aspose.psd.Color---java.io.InputStream-java.io.InputStream-}
```
public static int[] toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)
```


カスタムプロファイルを使用した Icc 変換により、ARGB カラーから CMYK カラーへの変換です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.psd/color) | ARGBカラー。 |
| rgbIccStream | java.io.InputStream | RGB Iccプロファイルを含むストリーム。 |
| cmykIccStream | java.io.InputStream | CMYK Iccプロファイルを含むストリーム。 |

**Returns:**
int[] - CMYKカラーは32ビット整数値として表現されます。
### toCmykIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIccBytes-int---int-int-java.io.InputStream-java.io.InputStream-}
```
public static byte[] toCmykIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream)
```


カスタム ICC プロファイルを使用して RGB を CMYK に変換します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ピクセル | int[] | RGBカラーは32ビット整数値として表現されます。 |
| startIndex | int | RGBカラーの開始インデックス。 |
| length | int | 変換するRGBピクセルの数。 |
| rgbIccStream | java.io.InputStream | RGBプロファイルストリーム。 |
| cmykIccStream | java.io.InputStream | CMYKプロファイルストリーム。 |

**Returns:**
byte[] - CMYKカラーはバイト配列として表現されます。
### toCmykIccBytes_internalized(int[] pixels, int startIndex, int length, System.IO.Stream rgbIccStream, System.IO.Stream cmykIccStream) {#toCmykIccBytes-internalized-int---int-int-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-}
```
public static byte[] toCmykIccBytes_internalized(int[] pixels, int startIndex, int length, System.IO.Stream rgbIccStream, System.IO.Stream cmykIccStream)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ピクセル | int[] |  |
| startIndex | int |  |
| length | int |  |
| rgbIccStream | com.aspose.ms.System.IO.Stream |  |
| cmykIccStream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
byte[]
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
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

