---
title: "ColorantRgb"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "RGB カラーネントを表します。"
type: docs
weight: 15
url: /ja/java/com.aspose.psd.xmp.types.complex.colorant/colorantrgb/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.types.XmpTypeBase](../../com.aspose.psd.xmp.types/xmptypebase), [com.aspose.psd.xmp.types.complex.ComplexTypeBase](../../com.aspose.psd.xmp.types.complex/complextypebase), [com.aspose.psd.xmp.types.complex.colorant.ColorantBase](../../com.aspose.psd.xmp.types.complex.colorant/colorantbase)
```
public final class ColorantRgb extends ColorantBase
```

RGB カラーネントを表します。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [ColorantRgb()](#ColorantRgb--) | ColorantRgb クラスの新しいインスタンスを初期化します。 |
| [ColorantRgb(byte red, byte green, byte blue)](#ColorantRgb-byte-byte-byte-) | ColorantRgb クラスの新しいインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [add(String key, Object value)](#add-java.lang.String-java.lang.Object-) | 指定されたキーを追加します。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlue()](#getBlue--) | 青コンポーネントの値を取得または設定します。 |
| [getClass()](#getClass--) |  |
| [getColorType()](#getColorType--) | 色のタイプを取得または設定します。 |
| [getGreen()](#getGreen--) | 緑コンポーネントの値を取得または設定します。 |
| [getMode()](#getMode--) | ColorMode を取得します。 |
| [getNamespaceUri()](#getNamespaceUri--) | デフォルトの名前空間 URI を取得します。 |
| [getPrefix()](#getPrefix--) | プレフィックスを取得します。 |
| [getRed()](#getRed--) | 赤コンポーネントの値を取得または設定します。 |
| [getSwatchName()](#getSwatchName--) | スウォッチの名前を取得または設定します。 |
| [getXmpRepresentation()](#getXmpRepresentation--) | XMP 形式で含まれる文字列値を取得します。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBlue(byte value)](#setBlue-byte-) | 青コンポーネントの値を取得または設定します。 |
| [setColorType(int value)](#setColorType-int-) | 色のタイプを取得または設定します。 |
| [setGreen(byte value)](#setGreen-byte-) | 緑コンポーネントの値を取得または設定します。 |
| [setRed(byte value)](#setRed-byte-) | 赤コンポーネントの値を取得または設定します。 |
| [setSwatchName(String value)](#setSwatchName-java.lang.String-) | スウォッチの名前を取得または設定します。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ColorantRgb() {#ColorantRgb--}
```
public ColorantRgb()
```


ColorantRgb クラスの新しいインスタンスを初期化します。

### ColorantRgb(byte red, byte green, byte blue) {#ColorantRgb-byte-byte-byte-}
```
public ColorantRgb(byte red, byte green, byte blue)
```


ColorantRgb クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 赤 | byte | 赤コンポーネントの値。 |
| 緑 | byte | 緑コンポーネントの値。 |
| 青 | byte | 青コンポーネントの値。 |

### add(String key, Object value) {#add-java.lang.String-java.lang.Object-}
```
public void add(String key, Object value)
```


指定されたキーを追加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| キー | java.lang.String | 追加された値で識別されるキーの文字列表現です。 |
| 値 | java.lang.Object | 追加する対象の値。 |

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
### getBlue() {#getBlue--}
```
public byte getBlue()
```


青コンポーネントの値を取得または設定します。

値: 青色成分の値。

**Returns:**
byte
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorType() {#getColorType--}
```
public int getColorType()
```


色のタイプを取得または設定します。

値: 色のタイプ。

**Returns:**
int
### getGreen() {#getGreen--}
```
public byte getGreen()
```


緑コンポーネントの値を取得または設定します。

値: 緑色成分の値。

**Returns:**
byte
### getMode() {#getMode--}
```
public int getMode()
```


ColorMode を取得します。

値: color mode。

**Returns:**
int
### getNamespaceUri() {#getNamespaceUri--}
```
public String getNamespaceUri()
```


デフォルトの名前空間 URI を取得します。

**Returns:**
java.lang.String - デフォルトの名前空間 URI。
### getPrefix() {#getPrefix--}
```
public String getPrefix()
```


プレフィックスを取得します。

**Returns:**
java.lang.String - プレフィックス。
### getRed() {#getRed--}
```
public byte getRed()
```


赤コンポーネントの値を取得または設定します。

値: 赤色成分の値。

**Returns:**
byte
### getSwatchName() {#getSwatchName--}
```
public String getSwatchName()
```


スウォッチの名前を取得または設定します。

値: スウォッチの名前。

**Returns:**
java.lang.String
### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


XMP 形式で含まれる文字列値を取得します。

**Returns:**
java.lang.String - XMP 形式で含まれる文字列値を返します。
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




### setBlue(byte value) {#setBlue-byte-}
```
public void setBlue(byte value)
```


青コンポーネントの値を取得または設定します。

値: 青色成分の値。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | byte |  |

### setColorType(int value) {#setColorType-int-}
```
public void setColorType(int value)
```


色のタイプを取得または設定します。

値: 色のタイプ。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setGreen(byte value) {#setGreen-byte-}
```
public void setGreen(byte value)
```


緑コンポーネントの値を取得または設定します。

値: 緑色成分の値。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | byte |  |

### setRed(byte value) {#setRed-byte-}
```
public void setRed(byte value)
```


赤コンポーネントの値を取得または設定します。

値: 赤色成分の値。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | byte |  |

### setSwatchName(String value) {#setSwatchName-java.lang.String-}
```
public void setSwatchName(String value)
```


スウォッチの名前を取得または設定します。

値: スウォッチの名前。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

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

