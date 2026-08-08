---
title: "SolidGradient"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "グラデーション塗りつぶし効果設定。"
type: docs
weight: 13
url: /ja/java/com.aspose.psd.fileformats.psd.layers.gradient/solidgradient/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.gradient.BaseGradient](../../com.aspose.psd.fileformats.psd.layers.gradient/basegradient)
```
public class SolidGradient extends BaseGradient
```

グラデーション塗りつぶし効果設定。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [SolidGradient()](#SolidGradient--) | 新しいインスタンスを初期化します [SolidGradient](../../com.aspose.psd.fileformats.psd.layers.gradient/solidgradient) クラス。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [addColorPoint()](#addColorPoint--) | カラー点を追加します。 |
| [addTransparencyPoint()](#addTransparencyPoint--) | カラー点を追加します。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [generateLfx2ResourceNodes()](#generateLfx2ResourceNodes--) | LFX2 リソースノードを生成します。 |
| [getClass()](#getClass--) |  |
| [getColorPoints()](#getColorPoints--) | カラー点を取得または設定します。 |
| [getGradientMode()](#getGradientMode--) | このグラデーションのモードを取得します。 |
| [getGradientName()](#getGradientName--) | グラデーションの名前を取得または設定します。 |
| [getInterpolation()](#getInterpolation--) | Interpolation を取得または設定します。 |
| [getTransparencyPoints()](#getTransparencyPoints--) | 透過点を取得または設定します。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeColorPoint(IGradientColorPoint point)](#removeColorPoint-com.aspose.psd.fileformats.psd.layers.IGradientColorPoint-) | カラー点を削除します。 |
| [removeTransparencyPoint(IGradientTransparencyPoint point)](#removeTransparencyPoint-com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint-) | 透過点を削除します。 |
| [setColorPoints(IGradientColorPoint[] value)](#setColorPoints-com.aspose.psd.fileformats.psd.layers.IGradientColorPoint---) | カラー点を取得または設定します。 |
| [setGradientName(String value)](#setGradientName-java.lang.String-) | グラデーションの名前を取得または設定します。 |
| [setInterpolation(short value)](#setInterpolation-short-) | Interpolation を取得または設定します。 |
| [setTransparencyPoints(IGradientTransparencyPoint[] value)](#setTransparencyPoints-com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint---) | 透過点を取得または設定します。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SolidGradient() {#SolidGradient--}
```
public SolidGradient()
```


新しいインスタンスを初期化します [SolidGradient](../../com.aspose.psd.fileformats.psd.layers.gradient/solidgradient) クラス。

### addColorPoint() {#addColorPoint--}
```
public final GradientColorPoint addColorPoint()
```


カラー点を追加します。

**Returns:**
[GradientColorPoint](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientcolorpoint) - Created color point
### addTransparencyPoint() {#addTransparencyPoint--}
```
public final GradientTransparencyPoint addTransparencyPoint()
```


カラー点を追加します。

**Returns:**
[GradientTransparencyPoint](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradienttransparencypoint) - Created transparency point
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
### generateLfx2ResourceNodes() {#generateLfx2ResourceNodes--}
```
public static System.Collections.Generic.List<OSTypeStructure> generateLfx2ResourceNodes()
```


LFX2 リソースノードを生成します。

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> - 生成されたリスト [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorPoints() {#getColorPoints--}
```
public final IGradientColorPoint[] getColorPoints()
```


カラー点を取得または設定します。

値: カラー点です。

**Returns:**
com.aspose.psd.fileformats.psd.layers.IGradientColorPoint[]
### getGradientMode() {#getGradientMode--}
```
public int getGradientMode()
```


このグラデーションのモードを取得します。'Gradient Type' を 'Solid/Noise' (0/1) に決定します。

**Returns:**
int
### getGradientName() {#getGradientName--}
```
public final String getGradientName()
```


グラデーションの名前を取得または設定します。

値: グラデーションの名前です。

**Returns:**
java.lang.String
### getInterpolation() {#getInterpolation--}
```
public final short getInterpolation()
```


Interpolation を取得または設定します。 「Gradient Type」=「Solid」のとき、スムーズさを決定します。 値の範囲: 0-4096。

**Returns:**
short
### getTransparencyPoints() {#getTransparencyPoints--}
```
public final IGradientTransparencyPoint[] getTransparencyPoints()
```


透過点を取得または設定します。

値: 透過点です。

**Returns:**
com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint[]
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




### removeColorPoint(IGradientColorPoint point) {#removeColorPoint-com.aspose.psd.fileformats.psd.layers.IGradientColorPoint-}
```
public final void removeColorPoint(IGradientColorPoint point)
```


カラー点を削除します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| point | [IGradientColorPoint](../../com.aspose.psd.fileformats.psd.layers/igradientcolorpoint) | ポイントです。 |

### removeTransparencyPoint(IGradientTransparencyPoint point) {#removeTransparencyPoint-com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint-}
```
public final void removeTransparencyPoint(IGradientTransparencyPoint point)
```


透過点を削除します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| point | [IGradientTransparencyPoint](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint) | ポイントです。 |

### setColorPoints(IGradientColorPoint[] value) {#setColorPoints-com.aspose.psd.fileformats.psd.layers.IGradientColorPoint---}
```
public final void setColorPoints(IGradientColorPoint[] value)
```


カラー点を取得または設定します。

値: カラー点です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IGradientColorPoint\[\]](../../com.aspose.psd.fileformats.psd.layers/igradientcolorpoint) |  |

### setGradientName(String value) {#setGradientName-java.lang.String-}
```
public final void setGradientName(String value)
```


グラデーションの名前を取得または設定します。

値: グラデーションの名前です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setInterpolation(short value) {#setInterpolation-short-}
```
public final void setInterpolation(short value)
```


Interpolation を取得または設定します。 「Gradient Type」=「Solid」のとき、スムーズさを決定します。 値の範囲: 0-4096。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | short |  |

### setTransparencyPoints(IGradientTransparencyPoint[] value) {#setTransparencyPoints-com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint---}
```
public final void setTransparencyPoints(IGradientTransparencyPoint[] value)
```


透過点を取得または設定します。

値: 透過点です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IGradientTransparencyPoint\[\]](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint) |  |

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

