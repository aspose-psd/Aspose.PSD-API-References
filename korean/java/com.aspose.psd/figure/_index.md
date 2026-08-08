---
title: "도형"
second_title: "Java용 Aspose.PSD API 참조"
description: "도형."
type: docs
weight: 42
url: /ko/java/com.aspose.psd/figure/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.ObjectWithBounds](../../com.aspose.psd/objectwithbounds)
```
public class Figure extends ObjectWithBounds
```

도형. 모양을 위한 컨테이너입니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [Figure()](#Figure--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [addShape(Shape shape)](#addShape-com.aspose.psd.Shape-) | 도형에 모양을 추가합니다. |
| [addShapes(Shape[] shapes)](#addShapes-com.aspose.psd.Shape---) | 도형에 여러 모양을 추가합니다. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBounds()](#getBounds--) | 객체의 경계를 가져오거나 설정합니다. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.psd.Matrix-) | 객체의 경계를 가져옵니다. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-) | 객체의 경계를 가져옵니다. |
| [getClass()](#getClass--) |  |
| [getSegments()](#getSegments--) | 전체 도형 세그먼트를 가져옵니다. |
| [getShapes()](#getShapes--) | 도형의 모양을 가져옵니다. |
| [hashCode()](#hashCode--) |  |
| [isClosed()](#isClosed--) | 이 도형이 닫혔는지 여부를 나타내는 값을 가져옵니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeShape(Shape shape)](#removeShape-com.aspose.psd.Shape-) | 도형에서 모양을 제거합니다. |
| [removeShapes(Shape[] shapes)](#removeShapes-com.aspose.psd.Shape---) | 도형에서 여러 모양을 제거합니다. |
| [reverse()](#reverse--) | 이 도형의 모양 순서와 모양 포인트 순서를 반전시킵니다. |
| [setClosed(boolean value)](#setClosed-boolean-) | 이 도형이 닫혔는지 여부를 나타내는 값을 설정합니다. |
| [toString()](#toString--) |  |
| [transform(Matrix transform)](#transform-com.aspose.psd.Matrix-) | 지정된 변환을 모양에 적용합니다. |
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


도형에 모양을 추가합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.psd/shape) | 추가할 모양입니다. |

### addShapes(Shape[] shapes) {#addShapes-com.aspose.psd.Shape---}
```
public void addShapes(Shape[] shapes)
```


도형에 여러 모양을 추가합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| shapes | [Shape\[\]](../../com.aspose.psd/shape) | 추가할 모양들입니다. |

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


객체의 경계를 가져오거나 설정합니다.

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The object's bounds.
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


전체 도형 세그먼트를 가져옵니다.

**Returns:**
com.aspose.psd.ShapeSegment[] - 도형 세그먼트입니다.
### getShapes() {#getShapes--}
```
public Shape[] getShapes()
```


도형의 모양을 가져옵니다.

**Returns:**
com.aspose.psd.Shape[] - 도형 모양들입니다.
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


이 도형이 닫혔는지 여부를 나타내는 값을 가져옵니다. 닫힌 도형은 첫 번째와 마지막 도형의 모양이 연속적인 경우에만 차이를 만듭니다. 이러한 경우 첫 번째 모양의 첫 번째 점이 마지막 모양의 마지막 점에서 직선으로 연결됩니다.

**Returns:**
boolean - 이 도형이 닫혔으면 True; 그렇지 않으면 false.
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


도형에서 모양을 제거합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.psd/shape) | 제거할 모양입니다. |

### removeShapes(Shape[] shapes) {#removeShapes-com.aspose.psd.Shape---}
```
public void removeShapes(Shape[] shapes)
```


도형에서 여러 모양을 제거합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| shapes | [Shape\[\]](../../com.aspose.psd/shape) | 제거할 도형 범위. |

### reverse() {#reverse--}
```
public void reverse()
```


이 도형의 모양 순서와 모양 포인트 순서를 반전시킵니다.

### setClosed(boolean value) {#setClosed-boolean-}
```
public void setClosed(boolean value)
```


이 도형이 닫혀 있는지 여부를 나타내는 값을 설정합니다. 닫힌 도형은 첫 번째와 마지막 도형의 모양이 연속적인 경우에만 차이가 있습니다. 이러한 경우 첫 번째 모양의 첫 번째 점이 마지막 모양의 마지막 점과 직선으로 연결됩니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean | 이 도형이 닫혀 있으면 true; 그렇지 않으면 false. |

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

