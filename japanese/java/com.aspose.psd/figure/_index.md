---
title: "図形"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "図です。"
type: docs
weight: 42
url: /ja/java/com.aspose.psd/figure/
---

**Inheritance:**
java.lang.Object、[com.aspose.psd.ObjectWithBounds](../../com.aspose.psd/objectwithbounds)
```
public class Figure extends ObjectWithBounds
```

図形です。シェイプのコンテナです。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [Figure()](#Figure--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [addShape(Shape shape)](#addShape-com.aspose.psd.Shape-) | 図形にシェイプを追加します。 |
| [addShapes(Shape[] shapes)](#addShapes-com.aspose.psd.Shape---) | 図形にシェイプの範囲を追加します。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBounds()](#getBounds--) | オブジェクトの境界を取得または設定します。 |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.psd.Matrix-) | オブジェクトの境界を取得します。 |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-) | オブジェクトの境界を取得します。 |
| [getClass()](#getClass--) |  |
| [getSegments()](#getSegments--) | 図形全体のセグメントを取得します。 |
| [getShapes()](#getShapes--) | 図形のシェイプを取得します。 |
| [hashCode()](#hashCode--) |  |
| [isClosed()](#isClosed--) | この図形が閉じているかどうかを示す値を取得します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeShape(Shape shape)](#removeShape-com.aspose.psd.Shape-) | 図形からシェイプを削除します。 |
| [removeShapes(Shape[] shapes)](#removeShapes-com.aspose.psd.Shape---) | 図形からシェイプの範囲を削除します。 |
| [reverse()](#reverse--) | この図形のシェイプ順序とシェイプのポイント順序を逆にします。 |
| [setClosed(boolean value)](#setClosed-boolean-) | この図形が閉じているかどうかを示す値を設定します。 |
| [toString()](#toString--) |  |
| [transform(Matrix transform)](#transform-com.aspose.psd.Matrix-) | 指定された変換をシェイプに適用します。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Figure() {#Figure--}
```
public Figure()
```


### addShape(Shape shape) {#addShape-com.aspose.psd.Shape-}
```
public void addShape(Shape shape)
```


図形にシェイプを追加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.psd/shape) | 追加するシェイプ。 |

### addShapes(Shape[] shapes) {#addShapes-com.aspose.psd.Shape---}
```
public void addShapes(Shape[] shapes)
```


図形にシェイプの範囲を追加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| shapes | [Shape\[\]](../../com.aspose.psd/shape) | 追加するシェイプ群。 |

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


オブジェクトの境界を取得または設定します。

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The object's bounds.
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getSegments() {#getSegments--}
```
public ShapeSegment[] getSegments()
```


図形全体のセグメントを取得します。

**Returns:**
com.aspose.psd.ShapeSegment[] - 図形のセグメントです。
### getShapes() {#getShapes--}
```
public Shape[] getShapes()
```


図形のシェイプを取得します。

**Returns:**
com.aspose.psd.Shape[] - 図形のシェイプです。
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


この図形が閉じているかどうかを示す値を取得します。閉じた図形は、最初のシェイプと最後のシェイプが連続したシェイプである場合にのみ違いが生じます。その場合、最初のシェイプの最初のポイントは、最後のシェイプの最後のポイントから直線で接続されます。

**Returns:**
boolean - この図形が閉じている場合は True、そうでない場合は false。
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeShape(Shape shape) {#removeShape-com.aspose.psd.Shape-}
```
public void removeShape(Shape shape)
```


図形からシェイプを削除します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.psd/shape) | 削除するシェイプ。 |

### removeShapes(Shape[] shapes) {#removeShapes-com.aspose.psd.Shape---}
```
public void removeShapes(Shape[] shapes)
```


図形からシェイプの範囲を削除します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| shapes | [Shape\[\]](../../com.aspose.psd/shape) | 削除するシェイプの範囲。 |

### reverse() {#reverse--}
```
public void reverse()
```


この図形のシェイプ順序とシェイプのポイント順序を逆にします。

### setClosed(boolean value) {#setClosed-boolean-}
```
public void setClosed(boolean value)
```


この図形が閉じているかどうかを示す値を設定します。閉じた図形は、最初と最後の図形のシェイプが連続したシェイプである場合にのみ違いが生じます。そのような場合、最初のシェイプの最初の点は、最後のシェイプの最後の点から直線で接続されます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean | この図形が閉じている場合は true、そうでない場合は false。 |

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

