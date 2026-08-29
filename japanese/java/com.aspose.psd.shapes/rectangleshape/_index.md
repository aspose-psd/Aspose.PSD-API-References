---
title: "RectangleShape"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "矩形形状を表します。"
type: docs
weight: 17
url: /ja/java/com.aspose.psd.shapes/rectangleshape/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.ObjectWithBounds](../../com.aspose.psd/objectwithbounds), [com.aspose.psd.Shape](../../com.aspose.psd/shape), [com.aspose.psd.shapes.RectangleProjectedShape](../../com.aspose.psd.shapes/rectangleprojectedshape)
```
public class RectangleShape extends RectangleProjectedShape
```

矩形形状を表します。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [RectangleShape()](#RectangleShape--) | RectangleShape クラスの新しいインスタンスを初期化します。 |
| [RectangleShape(RectangleF rectangle)](#RectangleShape-com.aspose.psd.RectangleF-) | RectangleShape クラスの新しいインスタンスを初期化します。 |
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
| [hasSegments()](#hasSegments--) | 形状にセグメントがあるかどうかを示す値を取得します。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [transform(Matrix transform)](#transform-com.aspose.psd.Matrix-) | 指定された変換をシェイプに適用します。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RectangleShape() {#RectangleShape--}
```
public RectangleShape()
```


RectangleShape クラスの新しいインスタンスを初期化します。

### RectangleShape(RectangleF rectangle) {#RectangleShape-com.aspose.psd.RectangleF-}
```
public RectangleShape(RectangleF rectangle)
```


RectangleShape クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.psd/rectanglef) | 矩形です。 |

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

