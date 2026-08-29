---
title: "PieShape"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "パイ形状を表します。"
type: docs
weight: 14
url: /ja/java/com.aspose.psd.shapes/pieshape/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.ObjectWithBounds](../../com.aspose.psd/objectwithbounds), [com.aspose.psd.Shape](../../com.aspose.psd/shape), [com.aspose.psd.shapes.RectangleProjectedShape](../../com.aspose.psd.shapes/rectangleprojectedshape), [com.aspose.psd.shapes.RectangleShape](../../com.aspose.psd.shapes/rectangleshape), [com.aspose.psd.shapes.EllipseShape](../../com.aspose.psd.shapes/ellipseshape)
```
public class PieShape extends EllipseShape
```

パイ形状を表します。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [PieShape()](#PieShape--) | PieShape クラスの新しいインスタンスを初期化します。 |
| [PieShape(RectangleF rectangle, float startAngle, float sweepAngle)](#PieShape-com.aspose.psd.RectangleF-float-float-) | PieShape クラスの新しいインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBounds()](#getBounds--) | オブジェクトの境界を取得します。 |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.psd.Matrix-) | オブジェクトの境界を取得します。 |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-) | オブジェクトの境界を取得します。 |
| [getCenter()](#getCenter--) | 形状の中心を取得します。 |
| [getClass()](#getClass--) |  |
| [getLeftBottom()](#getLeftBottom--) | 左下の矩形の点を取得します。 |
| [getLeftTop()](#getLeftTop--) | 左上の矩形の点を取得します。 |
| [getRectangleHeight()](#getRectangleHeight--) | 矩形の高さを取得します。 |
| [getRectangleWidth()](#getRectangleWidth--) | 矩形の幅を取得します。 |
| [getRightBottom()](#getRightBottom--) | 右下の矩形の点を取得します。 |
| [getRightTop()](#getRightTop--) | 右上の矩形の点を取得します。 |
| [getSegments()](#getSegments--) | 形状のセグメントを取得します。 |
| [getStartAngle()](#getStartAngle--) | 開始角度を取得または設定します。 |
| [getSweepAngle()](#getSweepAngle--) | スイープ角度を取得または設定します。 |
| [hasSegments()](#hasSegments--) | 形状にセグメントがあるかどうかを示す値を取得します。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setStartAngle(float value)](#setStartAngle-float-) | 開始角度を取得または設定します。 |
| [setSweepAngle(float value)](#setSweepAngle-float-) | スイープ角度を取得または設定します。 |
| [toString()](#toString--) |  |
| [transform(Matrix transform)](#transform-com.aspose.psd.Matrix-) | 指定された変換をシェイプに適用します。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PieShape() {#PieShape--}
```
public PieShape()
```


PieShape クラスの新しいインスタンスを初期化します。

### PieShape(RectangleF rectangle, float startAngle, float sweepAngle) {#PieShape-com.aspose.psd.RectangleF-float-float-}
```
public PieShape(RectangleF rectangle, float startAngle, float sweepAngle)
```


PieShape クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.psd/rectanglef) | 矩形です。 |
| 開始角度 | float | 開始角度。 |
| 掃引角度 | float | スイープ角度。 |

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
### getLeftBottom() {#getLeftBottom--}
```
public PointF getLeftBottom()
```


左下の矩形の点を取得します。

値: 左下の矩形の点です。

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getLeftTop() {#getLeftTop--}
```
public PointF getLeftTop()
```


左上の矩形の点を取得します。

値: 左上の矩形の点です。

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getRectangleHeight() {#getRectangleHeight--}
```
public double getRectangleHeight()
```


矩形の高さを取得します。

値: 矩形の高さです。

**Returns:**
double
### getRectangleWidth() {#getRectangleWidth--}
```
public double getRectangleWidth()
```


矩形の幅を取得します。

値: 矩形の幅です。

**Returns:**
double
### getRightBottom() {#getRightBottom--}
```
public PointF getRightBottom()
```


右下の矩形の点を取得します。

値: 右下の矩形の点です。

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getRightTop() {#getRightTop--}
```
public PointF getRightTop()
```


右上の矩形の点を取得します。

値: 右上の矩形の点です。

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getSegments() {#getSegments--}
```
public ShapeSegment[] getSegments()
```


形状のセグメントを取得します。

値: シェイプセグメント。

**Returns:**
com.aspose.psd.ShapeSegment[]
### getStartAngle() {#getStartAngle--}
```
public float getStartAngle()
```


開始角度を取得または設定します。

値: 開始角度。

**Returns:**
float
### getSweepAngle() {#getSweepAngle--}
```
public float getSweepAngle()
```


スイープ角度を取得または設定します。

値: スイープ角度。

**Returns:**
float
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
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setStartAngle(float value) {#setStartAngle-float-}
```
public void setStartAngle(float value)
```


開始角度を取得または設定します。

値: 開始角度。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | float |  |

### setSweepAngle(float value) {#setSweepAngle-float-}
```
public void setSweepAngle(float value)
```


スイープ角度を取得または設定します。

値: スイープ角度。

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

