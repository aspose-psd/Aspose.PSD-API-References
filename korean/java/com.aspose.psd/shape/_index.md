---
title: "Shape"
second_title: "Java용 Aspose.PSD API 참조"
description: "모양입니다."
type: docs
weight: 96
url: /ko/java/com.aspose.psd/shape/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.ObjectWithBounds](../../com.aspose.psd/objectwithbounds)
```
public abstract class Shape extends ObjectWithBounds
```

형상. 특정 규칙을 사용하여 연결된 연속적인 점 집합입니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [Shape()](#Shape--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBounds()](#getBounds--) | 객체의 경계를 가져옵니다. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.psd.Matrix-) | 객체의 경계를 가져옵니다. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-) | 객체의 경계를 가져옵니다. |
| [getCenter()](#getCenter--) | 형상의 중심을 가져옵니다. |
| [getClass()](#getClass--) |  |
| [getSegments()](#getSegments--) | 형상 세그먼트를 가져옵니다. |
| [hasSegments()](#hasSegments--) | 형상에 세그먼트가 있는지 여부를 나타내는 값을 가져옵니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [transform(Matrix transform)](#transform-com.aspose.psd.Matrix-) | 지정된 변환을 모양에 적용합니다. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Shape() {#Shape--}
```
public Shape()
```


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
public abstract RectangleF getBounds()
```


객체의 경계를 가져옵니다.

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The object's bounds.
### getBounds(Matrix matrix) {#getBounds-com.aspose.psd.Matrix-}
```
public abstract RectangleF getBounds(Matrix matrix)
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
public abstract RectangleF getBounds(Matrix matrix, Pen pen)
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
public abstract PointF getCenter()
```


형상의 중심을 가져옵니다.

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The shape's center.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getSegments() {#getSegments--}
```
public abstract ShapeSegment[] getSegments()
```


형상 세그먼트를 가져옵니다.

**Returns:**
com.aspose.psd.ShapeSegment[] - 형상 세그먼트.
### hasSegments() {#hasSegments--}
```
public abstract boolean hasSegments()
```


형상에 세그먼트가 있는지 여부를 나타내는 값을 가져옵니다.

**Returns:**
boolean -  True  if 형상에 세그먼트가 있습니다; otherwise,  false .
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
public abstract void transform(Matrix transform)
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

