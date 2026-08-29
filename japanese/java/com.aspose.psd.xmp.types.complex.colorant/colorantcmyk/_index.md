---
title: "ColorantCmyk"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "CMYK カラーネントを表します。"
type: docs
weight: 13
url: /ja/java/com.aspose.psd.xmp.types.complex.colorant/colorantcmyk/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.types.XmpTypeBase](../../com.aspose.psd.xmp.types/xmptypebase), [com.aspose.psd.xmp.types.complex.ComplexTypeBase](../../com.aspose.psd.xmp.types.complex/complextypebase), [com.aspose.psd.xmp.types.complex.colorant.ColorantBase](../../com.aspose.psd.xmp.types.complex.colorant/colorantbase)
```
public final class ColorantCmyk extends ColorantBase
```

CMYK カラーネントを表します。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [ColorantCmyk()](#ColorantCmyk--) | ColorantCmyk クラスの新しいインスタンスを初期化します。 |
| [ColorantCmyk(float black, float cyan, float magenta, float yellow)](#ColorantCmyk-float-float-float-float-) | ColorantCmyk クラスの新しいインスタンスを初期化します。 |
## フィールド

| フィールド | 説明 |
| --- | --- |
| [ColorValueMax](#ColorValueMax) | CMYK カラントの最大色値。 |
| [ColorValueMin](#ColorValueMin) | CMYK カラントの最小色値。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [add(String key, Object value)](#add-java.lang.String-java.lang.Object-) | 指定されたキーを追加します。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlack()](#getBlack--) | 黒コンポーネントの値を取得または設定します。 |
| [getClass()](#getClass--) |  |
| [getColorType()](#getColorType--) | 色のタイプを取得または設定します。 |
| [getCyan()](#getCyan--) | シアンコンポーネントの値を取得または設定します。 |
| [getMagenta()](#getMagenta--) | マゼンタコンポーネントの値を取得または設定します。 |
| [getMode()](#getMode--) | ColorMode を取得します。 |
| [getNamespaceUri()](#getNamespaceUri--) | デフォルトの名前空間 URI を取得します。 |
| [getPrefix()](#getPrefix--) | プレフィックスを取得します。 |
| [getSwatchName()](#getSwatchName--) | スウォッチの名前を取得または設定します。 |
| [getXmpRepresentation()](#getXmpRepresentation--) | XMP 形式で含まれる文字列値を取得します。 |
| [getYellow()](#getYellow--) | 黄色コンポーネントの値を取得または設定します。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBlack(float value)](#setBlack-float-) | 黒コンポーネントの値を取得または設定します。 |
| [setColorType(int value)](#setColorType-int-) | 色のタイプを取得または設定します。 |
| [setCyan(float value)](#setCyan-float-) | シアンコンポーネントの値を取得または設定します。 |
| [setMagenta(float value)](#setMagenta-float-) | マゼンタコンポーネントの値を取得または設定します。 |
| [setSwatchName(String value)](#setSwatchName-java.lang.String-) | スウォッチの名前を取得または設定します。 |
| [setYellow(float value)](#setYellow-float-) | 黄色コンポーネントの値を取得または設定します。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ColorantCmyk() {#ColorantCmyk--}
```
public ColorantCmyk()
```


ColorantCmyk クラスの新しいインスタンスを初期化します。

### ColorantCmyk(float black, float cyan, float magenta, float yellow) {#ColorantCmyk-float-float-float-float-}
```
public ColorantCmyk(float black, float cyan, float magenta, float yellow)
```


ColorantCmyk クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 黒 | float | 黒コンポーネントの値。 |
| シアン | float | シアン色コンポーネントの値。 |
| マゼンタ | float | マゼンタコンポーネントの値。 |
| 黄色 | float | 黄色コンポーネントの値。 |

### ColorValueMax {#ColorValueMax}
```
public static final float ColorValueMax
```


CMYK カラントの最大色値。

### ColorValueMin {#ColorValueMin}
```
public static final float ColorValueMin
```


CMYK カラントの最小色値。

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
### getBlack() {#getBlack--}
```
public float getBlack()
```


黒コンポーネントの値を取得または設定します。

値: 黒コンポーネントの値。

**Returns:**
float
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
### getCyan() {#getCyan--}
```
public float getCyan()
```


シアンコンポーネントの値を取得または設定します。

値: シアンコンポーネントの値。

**Returns:**
float
### getMagenta() {#getMagenta--}
```
public float getMagenta()
```


マゼンタコンポーネントの値を取得または設定します。

値: マゼンタコンポーネントの値。

**Returns:**
float
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
### getYellow() {#getYellow--}
```
public float getYellow()
```


黄色コンポーネントの値を取得または設定します。

値: 黄色コンポーネントの値。

**Returns:**
float
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




### setBlack(float value) {#setBlack-float-}
```
public void setBlack(float value)
```


黒コンポーネントの値を取得または設定します。

値: 黒コンポーネントの値。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | float |  |

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

### setCyan(float value) {#setCyan-float-}
```
public void setCyan(float value)
```


シアンコンポーネントの値を取得または設定します。

値: シアンコンポーネントの値。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | float |  |

### setMagenta(float value) {#setMagenta-float-}
```
public void setMagenta(float value)
```


マゼンタコンポーネントの値を取得または設定します。

値: マゼンタコンポーネントの値。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | float |  |

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

### setYellow(float value) {#setYellow-float-}
```
public void setYellow(float value)
```


黄色コンポーネントの値を取得または設定します。

値: 黄色コンポーネントの値。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | float |  |

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

