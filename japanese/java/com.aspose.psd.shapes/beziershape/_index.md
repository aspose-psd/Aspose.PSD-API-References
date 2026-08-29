---
title: "BezierShape"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "ベジェスプラインを表します。"
type: docs
weight: 11
url: /ja/java/com.aspose.psd.shapes/beziershape/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.ObjectWithBounds](../../com.aspose.psd/objectwithbounds), [com.aspose.psd.Shape](../../com.aspose.psd/shape), [com.aspose.psd.shapes.PolygonShape](../../com.aspose.psd.shapes/polygonshape)
```
public final class BezierShape extends PolygonShape
```

ベジェスプラインを表します。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [BezierShape()](#BezierShape--) | BezierShape クラスの新しいインスタンスを初期化します。 |
| [BezierShape(PointF[] points)](#BezierShape-com.aspose.psd.PointF---) | BezierShape クラスの新しいインスタンスを初期化します。 |
| [BezierShape(PointF[] points, boolean isClosed)](#BezierShape-com.aspose.psd.PointF---boolean-) | BezierShape クラスの新しいインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBounds()](#getBounds--) | オブジェクトの境界を取得します。 |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.psd.Matrix-) | オブジェクトの境界を取得します。 |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-) | オブジェクトの境界を取得します。 |
| [getCenter()](#getCenter--) | 形状の中心を取得します。 |
| [getClass()](#getClass--) |  |
| [getEndPoint()](#getEndPoint--) | 終了シェイプ点を取得します。 |
| [getPoints()](#getPoints--) | 曲線のポイントを取得または設定します。 |
| [getSegments()](#getSegments--) | 形状のセグメントを取得します。 |
| [getStartPoint()](#getStartPoint--) | 開始シェイプ点を取得します。 |
| [hasSegments()](#hasSegments--) | 形状にセグメントがあるかどうかを示す値を取得します。 |
| [hashCode()](#hashCode--) |  |
| [isClosed()](#isClosed--) | 形状が閉じているかどうかを示す値を取得または設定します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [reverse()](#reverse--) | このシェイプの点の順序を逆にします。 |
| [setClosed(boolean value)](#setClosed-boolean-) | 形状が閉じているかどうかを示す値を取得または設定します。 |
| [setPoints(PointF[] value)](#setPoints-com.aspose.psd.PointF---) | 曲線のポイントを取得または設定します。 |
| [toString()](#toString--) |  |
| [transform(Matrix transform)](#transform-com.aspose.psd.Matrix-) | 指定された変換をシェイプに適用します。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BezierShape() {#BezierShape--}
```
public BezierShape()
```


BezierShape クラスの新しいインスタンスを初期化します。

### BezierShape(PointF[] points) {#BezierShape-com.aspose.psd.PointF---}
```
public BezierShape(PointF[] points)
```


BezierShape クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | ポイント配列です。 |

### BezierShape(PointF[] points, boolean isClosed) {#BezierShape-com.aspose.psd.PointF---boolean-}
```
public BezierShape(PointF[] points, boolean isClosed)
```


BezierShape クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | ポイント配列です。 |
| isClosed | boolean | true に設定すると、ベジエスプラインが閉じます。 |

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
### getBounds() {#getBounds--}
```
public RectangleF getBounds()
```


オブジェクトの境界を取得します。

値: オブジェクトの境界です。

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef)
### getBounds(Matrix matrix) {#getBounds-com.aspose.psd.Matrix-}
```
public RectangleF getBounds(Matrix matrix)
```


オブジェクトの境界を取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | 境界が計算される前に適用する行列。 |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The estimated object's bounds.
### getBounds(Matrix matrix, Pen pen) {#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-}
```
public RectangleF getBounds(Matrix matrix, Pen pen)
```


オブジェクトの境界を取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | 境界が計算される前に適用する行列。 |
| pen | [Pen](../../com.aspose.psd/pen) | オブジェクトに使用するペン。これによりオブジェクトの境界サイズが影響を受ける可能性があります。 |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The estimated object's bounds.
### getCenter() {#getCenter--}
```
public PointF getCenter()
```


形状の中心を取得します。

値: 形状の中心です。

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEndPoint() {#getEndPoint--}
```
public PointF getEndPoint()
```


終了シェイプ点を取得します。

値: 終端シェイプポイント。

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getPoints() {#getPoints--}
```
public PointF[] getPoints()
```


曲線のポイントを取得または設定します。

値: 曲線ポイント。

**Returns:**
com.aspose.psd.PointF[]
### getSegments() {#getSegments--}
```
public ShapeSegment[] getSegments()
```


形状のセグメントを取得します。

値: シェイプセグメント。

**Returns:**
com.aspose.psd.ShapeSegment[]
### getStartPoint() {#getStartPoint--}
```
public PointF getStartPoint()
```


開始シェイプ点を取得します。

値: 開始シェイプポイント。

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### hasSegments() {#hasSegments--}
```
public boolean hasSegments()
```


形状にセグメントがあるかどうかを示す値を取得します。

値: 形状にセグメントがある場合は True、そうでない場合は false。

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isClosed() {#isClosed--}
```
public boolean isClosed()
```


形状が閉じているかどうかを示す値を取得または設定します。

値: shape が閉じている場合は  true 、それ以外の場合は  false 。

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




### reverse() {#reverse--}
```
public void reverse()
```


このシェイプの点の順序を逆にします。

### setClosed(boolean value) {#setClosed-boolean-}
```
public void setClosed(boolean value)
```


形状が閉じているかどうかを示す値を取得または設定します。

値: shape が閉じている場合は  true 、それ以外の場合は  false 。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setPoints(PointF[] value) {#setPoints-com.aspose.psd.PointF---}
```
public void setPoints(PointF[] value)
```


曲線のポイントを取得または設定します。

値: 曲線ポイント。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.psd/pointf) |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### transform(Matrix transform) {#transform-com.aspose.psd.Matrix-}
```
public void transform(Matrix transform)
```


指定された変換をシェイプに適用します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| transform | [Matrix](../../com.aspose.psd/matrix) | 適用する変換。 |

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

