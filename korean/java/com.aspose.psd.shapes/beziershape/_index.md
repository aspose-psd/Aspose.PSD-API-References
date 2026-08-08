---
title: "BezierShape"
second_title: "Java용 Aspose.PSD API 참조"
description: "베지어 스플라인을 나타냅니다."
type: docs
weight: 11
url: /ko/java/com.aspose.psd.shapes/beziershape/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.ObjectWithBounds](../../com.aspose.psd/objectwithbounds), [com.aspose.psd.Shape](../../com.aspose.psd/shape), [com.aspose.psd.shapes.PolygonShape](../../com.aspose.psd.shapes/polygonshape)
```
public final class BezierShape extends PolygonShape
```

베지어 스플라인을 나타냅니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [BezierShape()](#BezierShape--) | BezierShape 클래스의 새 인스턴스를 초기화합니다. |
| [BezierShape(PointF[] points)](#BezierShape-com.aspose.psd.PointF---) | BezierShape 클래스의 새 인스턴스를 초기화합니다. |
| [BezierShape(PointF[] points, boolean isClosed)](#BezierShape-com.aspose.psd.PointF---boolean-) | BezierShape 클래스의 새 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBounds()](#getBounds--) | 객체의 경계를 가져옵니다. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.psd.Matrix-) | 객체의 경계를 가져옵니다. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-) | 객체의 경계를 가져옵니다. |
| [getCenter()](#getCenter--) | 형상의 중심을 가져옵니다. |
| [getClass()](#getClass--) |  |
| [getEndPoint()](#getEndPoint--) | 끝 형태 점을 가져옵니다. |
| [getPoints()](#getPoints--) | 곡선 점을 가져오거나 설정합니다. |
| [getSegments()](#getSegments--) | 형상 세그먼트를 가져옵니다. |
| [getStartPoint()](#getStartPoint--) | 시작 형태 점을 가져옵니다. |
| [hasSegments()](#hasSegments--) | 형상에 세그먼트가 있는지 여부를 나타내는 값을 가져옵니다. |
| [hashCode()](#hashCode--) |  |
| [isClosed()](#isClosed--) | 형태가 닫혔는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [reverse()](#reverse--) | 이 형태의 점 순서를 반전시킵니다. |
| [setClosed(boolean value)](#setClosed-boolean-) | 형태가 닫혔는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [setPoints(PointF[] value)](#setPoints-com.aspose.psd.PointF---) | 곡선 점을 가져오거나 설정합니다. |
| [toString()](#toString--) |  |
| [transform(Matrix transform)](#transform-com.aspose.psd.Matrix-) | 지정된 변환을 모양에 적용합니다. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BezierShape() {#BezierShape--}
```
public BezierShape()
```


BezierShape 클래스의 새 인스턴스를 초기화합니다.

### BezierShape(PointF[] points) {#BezierShape-com.aspose.psd.PointF---}
```
public BezierShape(PointF[] points)
```


BezierShape 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | 점 배열입니다. |

### BezierShape(PointF[] points, boolean isClosed) {#BezierShape-com.aspose.psd.PointF---boolean-}
```
public BezierShape(PointF[] points, boolean isClosed)
```


BezierShape 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | 점 배열입니다. |
| isClosed | boolean | true 로 설정하면 베지어 스플라인이 닫힙니다. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBounds() {#getBounds--}
```
public RectangleF getBounds()
```


객체의 경계를 가져옵니다.

값: 객체의 경계입니다.

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef)
### getBounds(Matrix matrix) {#getBounds-com.aspose.psd.Matrix-}
```
public RectangleF getBounds(Matrix matrix)
```


객체의 경계를 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | 경계가 계산되기 전에 적용할 행렬입니다. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The estimated object's bounds.
### getBounds(Matrix matrix, Pen pen) {#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-}
```
public RectangleF getBounds(Matrix matrix, Pen pen)
```


객체의 경계를 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | 경계가 계산되기 전에 적용할 행렬입니다. |
| pen | [Pen](../../com.aspose.psd/pen) | 객체에 사용할 펜입니다. 이는 객체의 경계 크기에 영향을 줄 수 있습니다. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The estimated object's bounds.
### getCenter() {#getCenter--}
```
public PointF getCenter()
```


형상의 중심을 가져옵니다.

값: 형태의 중심입니다.

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


끝 형태 점을 가져옵니다.

값: 끝 모양 점.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getPoints() {#getPoints--}
```
public PointF[] getPoints()
```


곡선 점을 가져오거나 설정합니다.

값: 곡선 점들.

**Returns:**
com.aspose.psd.PointF[]
### getSegments() {#getSegments--}
```
public ShapeSegment[] getSegments()
```


형상 세그먼트를 가져옵니다.

값: 모양 세그먼트.

**Returns:**
com.aspose.psd.ShapeSegment[]
### getStartPoint() {#getStartPoint--}
```
public PointF getStartPoint()
```


시작 형태 점을 가져옵니다.

값: 시작 모양 점.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### hasSegments() {#hasSegments--}
```
public boolean hasSegments()
```


형상에 세그먼트가 있는지 여부를 나타내는 값을 가져옵니다.

값:  True  , 그렇지 않으면  false  .

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


형태가 닫혔는지 여부를 나타내는 값을 가져오거나 설정합니다.

값: shape가 닫혀 있으면 true, 그렇지 않으면 false.

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


이 형태의 점 순서를 반전시킵니다.

### setClosed(boolean value) {#setClosed-boolean-}
```
public void setClosed(boolean value)
```


형태가 닫혔는지 여부를 나타내는 값을 가져오거나 설정합니다.

값: shape가 닫혀 있으면 true, 그렇지 않으면 false.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setPoints(PointF[] value) {#setPoints-com.aspose.psd.PointF---}
```
public void setPoints(PointF[] value)
```


곡선 점을 가져오거나 설정합니다.

값: 곡선 점들.

**Parameters:**
| 매개변수 | 형식 | 설명 |
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


지정된 변환을 모양에 적용합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| transform | [Matrix](../../com.aspose.psd/matrix) | 적용할 변환. |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

