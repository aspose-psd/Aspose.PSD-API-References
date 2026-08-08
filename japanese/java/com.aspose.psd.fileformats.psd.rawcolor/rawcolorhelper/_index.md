---
title: "RawColorHelper"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "Raw Color Helper クラスは、事前定義されたチャンネルメタデータを使用して RawColor をより速く作成するのに役立ちます"
type: docs
weight: 12
url: /ja/java/com.aspose.psd.fileformats.psd.rawcolor/rawcolorhelper/
---

**Inheritance:**
java.lang.Object
```
public class RawColorHelper
```

Raw Color Helper Class は、事前定義されたチャンネルメタデータを使用して RawColor を迅速に作成するのに役立ちます。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [RawColorHelper()](#RawColorHelper--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [createArgb16BitColor(int a, int r, int g, int b)](#createArgb16BitColor-int-int-int-int-) | チャンネルあたり 16 ビットの ARGB カラーを作成します。 |
| [createArgb8BitColor(byte a, byte r, byte g, byte b)](#createArgb8BitColor-byte-byte-byte-byte-) | チャンネルあたり 8 ビットの ARGB カラーを作成します。 |
| [createArgb8BitColor(Color drawingColor)](#createArgb8BitColor-com.aspose.psd.Color-) | Drawing.Color からチャンネルあたり 8 ビットの ARGB カラーを作成します。 |
| [createCmyk16BitBitColor(int c, int m, int y, int k)](#createCmyk16BitBitColor-int-int-int-int-) | チャンネルあたり 16 ビットの CMYK カラーを作成します。 |
| [createCmyk8BitColor(byte c, byte m, byte y, byte k)](#createCmyk8BitColor-byte-byte-byte-byte-) | 各チャンネル8ビットのCMYKカラーを作成します。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RawColorHelper() {#RawColorHelper--}
```
public RawColorHelper()
```


### createArgb16BitColor(int a, int r, int g, int b) {#createArgb16BitColor-int-int-int-int-}
```
public static RawColor createArgb16BitColor(int a, int r, int g, int b)
```


チャンネルあたり 16 ビットの ARGB カラーを作成します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| a | int | アルファ成分の値 (0-65535)。 |
| r | int | 赤成分の値 (0-65535)。 |
| g | int | 緑成分の値 (0-65535)。 |
|  | b | int | 青成分の値 (0-65535)。 |

--------------------

カラー成分は64ビット整数に次の順序でパックされます: アルファ (ビット 48-63)、赤 (ビット 32-47)、緑 (ビット 16-31)、青 (ビット 0-15)。 |

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) - A new [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) instance representing the ARGB color.
### createArgb8BitColor(byte a, byte r, byte g, byte b) {#createArgb8BitColor-byte-byte-byte-byte-}
```
public static RawColor createArgb8BitColor(byte a, byte r, byte g, byte b)
```


チャンネルあたり 8 ビットの ARGB カラーを作成します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| a | byte | アルファ成分の値 (0-255)。 |
| r | byte | 赤成分の値 (0-255)。 |
| g | byte | 緑成分の値 (0-255)。 |
|  | b | byte | 青成分の値 (0-255)。 |

--------------------

カラー成分は32ビット整数に次の順序でパックされます: アルファ (ビット 24-31)、赤 (ビット 16-23)、緑 (ビット 8-15)、青 (ビット 0-7)。 |

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) - A new [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) instance representing the ARGB color.
### createArgb8BitColor(Color drawingColor) {#createArgb8BitColor-com.aspose.psd.Color-}
```
public static RawColor createArgb8BitColor(Color drawingColor)
```


Drawing.Color からチャンネルあたり 8 ビットの ARGB カラーを作成します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | drawingColor | [Color](../../com.aspose.psd/color) | System.Drawing カラー |

--------------------

カラー成分は32ビット整数に次の順序でパックされます: アルファ (ビット 24-31)、赤 (ビット 16-23)、緑 (ビット 8-15)、青 (ビット 0-7)。 |

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) - A new [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) instance representing the ARGB color.
### createCmyk16BitBitColor(int c, int m, int y, int k) {#createCmyk16BitBitColor-int-int-int-int-}
```
public static RawColor createCmyk16BitBitColor(int c, int m, int y, int k)
```


チャンネルあたり 16 ビットの CMYK カラーを作成します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| c | int | シアン成分の値 (0-65535)。 |
| m | int | マゼンタ成分の値 (0-65535)。 |
| y | int | イエロー成分の値 (0-65535)。 |
|  | k | int | キー (黒) 成分の値 (0-65535)。 |

--------------------

カラー成分は64ビット整数に次の順序でパックされます: シアン (ビット 48-63)、マゼンタ (ビット 32-47)、イエロー (ビット 16-31)、キー/黒 (ビット 0-15)。 |

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) - A new [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) instance representing the CMYK color.
### createCmyk8BitColor(byte c, byte m, byte y, byte k) {#createCmyk8BitColor-byte-byte-byte-byte-}
```
public static RawColor createCmyk8BitColor(byte c, byte m, byte y, byte k)
```


各チャンネル8ビットのCMYKカラーを作成します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| c | byte | シアン成分の値 (0-255)。 |
| m | byte | マゼンタ成分の値 (0-255)。 |
| y | byte | イエロー成分の値 (0-255)。 |
|  | k | byte | キー (黒) 成分の値 (0-255)。 |

--------------------

色成分は 32 ビット整数に次の順序でパックされます: シアン (ビット 24-31)、マゼンタ (ビット 16-23)、イエロー (ビット 8-15)、およびキー/ブラック (ビット 0-7)。 |

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) - A new [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) instance representing the CMYK color.
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
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

