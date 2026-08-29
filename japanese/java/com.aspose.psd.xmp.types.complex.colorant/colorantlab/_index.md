---
title: "ColorantLab"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "LAB カラーネントを表します。"
type: docs
weight: 14
url: /ja/java/com.aspose.psd.xmp.types.complex.colorant/colorantlab/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.types.XmpTypeBase](../../com.aspose.psd.xmp.types/xmptypebase), [com.aspose.psd.xmp.types.complex.ComplexTypeBase](../../com.aspose.psd.xmp.types.complex/complextypebase), [com.aspose.psd.xmp.types.complex.colorant.ColorantBase](../../com.aspose.psd.xmp.types.complex.colorant/colorantbase)
```
public final class ColorantLab extends ColorantBase
```

LAB カラーネントを表します。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [ColorantLab()](#ColorantLab--) | ColorantLab クラスの新しいインスタンスを初期化します。 |
| [ColorantLab(int a, int b, float l)](#ColorantLab-int-int-float-) | ColorantLab クラスの新しいインスタンスを初期化します。 |
## フィールド

| フィールド | 説明 |
| --- | --- |
| [MaxA](#MaxA) | 最大 A コンポーネント値 |
| [MaxB](#MaxB) | 最大 A コンポーネント値 |
| [MaxL](#MaxL) | 最大 A コンポーネント値 |
| [MinA](#MinA) | 最小 A コンポーネント値 |
| [MinB](#MinB) | 最小 B コンポーネント値 |
| [MinL](#MinL) | 最小 L コンポーネント値 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [add(String key, Object value)](#add-java.lang.String-java.lang.Object-) | 指定されたキーを追加します。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getA()](#getA--) | A component を取得または設定します。 |
| [getB()](#getB--) | B component を取得または設定します。 |
| [getClass()](#getClass--) |  |
| [getColorType()](#getColorType--) | 色のタイプを取得または設定します。 |
| [getL()](#getL--) | L component を取得または設定します。 |
| [getMode()](#getMode--) | ColorMode を取得します。 |
| [getNamespaceUri()](#getNamespaceUri--) | デフォルトの名前空間 URI を取得します。 |
| [getPrefix()](#getPrefix--) | プレフィックスを取得します。 |
| [getSwatchName()](#getSwatchName--) | スウォッチの名前を取得または設定します。 |
| [getXmpRepresentation()](#getXmpRepresentation--) | XMP 形式で含まれる文字列値を取得します。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setA(int value)](#setA-int-) | A component を取得または設定します。 |
| [setB(int value)](#setB-int-) | B component を取得または設定します。 |
| [setColorType(int value)](#setColorType-int-) | 色のタイプを取得または設定します。 |
| [setL(float value)](#setL-float-) | L component を取得または設定します。 |
| [setSwatchName(String value)](#setSwatchName-java.lang.String-) | スウォッチの名前を取得または設定します。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ColorantLab() {#ColorantLab--}
```
public ColorantLab()
```


ColorantLab クラスの新しいインスタンスを初期化します。

### ColorantLab(int a, int b, float l) {#ColorantLab-int-int-float-}
```
public ColorantLab(int a, int b, float l)
```


ColorantLab クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| a | int | A component。 |
| b | int | B component。 |
| l | float | L component。 |

### MaxA {#MaxA}
```
public static final int MaxA
```


最大 A コンポーネント値

### MaxB {#MaxB}
```
public static final int MaxB
```


最大 A コンポーネント値

### MaxL {#MaxL}
```
public static final float MaxL
```


最大 A コンポーネント値

### MinA {#MinA}
```
public static final int MinA
```


最小 A コンポーネント値

### MinB {#MinB}
```
public static final int MinB
```


最小 B コンポーネント値

### MinL {#MinL}
```
public static final float MinL
```


最小 L コンポーネント値

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
### getA() {#getA--}
```
public int getA()
```


A component を取得または設定します。

値: A component。

**Returns:**
int
### getB() {#getB--}
```
public int getB()
```


B component を取得または設定します。

値: B component。

**Returns:**
int
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
### getL() {#getL--}
```
public float getL()
```


L component を取得または設定します。

値: L component。

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




### setA(int value) {#setA-int-}
```
public void setA(int value)
```


A component を取得または設定します。

値: A component。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setB(int value) {#setB-int-}
```
public void setB(int value)
```


B component を取得または設定します。

値: B component。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

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

### setL(float value) {#setL-float-}
```
public void setL(float value)
```


L component を取得または設定します。

値: L component。

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

