---
title: "BezierSegment"
second_title: "Java용 Aspose.PSD API 참조"
description: "두 개의 제어점을 사용하여 한 점에서 다음 점으로 이동하는 베지어 세그먼트."
type: docs
weight: 10
url: /ko/java/com.aspose.psd.shapesegments/beziersegment/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.ShapeSegment](../../com.aspose.psd/shapesegment), [com.aspose.psd.shapesegments.LineSegment](../../com.aspose.psd.shapesegments/linesegment)
```
public final class BezierSegment extends LineSegment
```

두 개의 제어점을 사용하여 한 점에서 다음 점으로 이동하는 베지어 세그먼트.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [BezierSegment(PointF startPoint, PointF firstControlPoint, PointF secondControlPoint, PointF endPoint)](#BezierSegment-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.PointF-) | BezierSegment 클래스의 새 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getEndPoint()](#getEndPoint--) | 끝점을 가져옵니다. |
| [getFirstControlPoint()](#getFirstControlPoint--) | 베지어 스플라인의 첫 번째 제어점을 가져옵니다. |
| [getSecondControlPoint()](#getSecondControlPoint--) | 베지어 스플라인의 두 번째 제어점을 가져옵니다. |
| [getStartPoint()](#getStartPoint--) | 시작점을 가져옵니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BezierSegment(PointF startPoint, PointF firstControlPoint, PointF secondControlPoint, PointF endPoint) {#BezierSegment-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.PointF-}
```
public BezierSegment(PointF startPoint, PointF firstControlPoint, PointF secondControlPoint, PointF endPoint)
```


BezierSegment 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| startPoint | [PointF](../../com.aspose.psd/pointf) | 시작점. |
| firstControlPoint | [PointF](../../com.aspose.psd/pointf) | 첫 번째 제어점. |
| secondControlPoint | [PointF](../../com.aspose.psd/pointf) | 두 번째 제어점. |
| endPoint | [PointF](../../com.aspose.psd/pointf) | 끝점. |

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


끝점을 가져옵니다.

값: 끝점.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getFirstControlPoint() {#getFirstControlPoint--}
```
public PointF getFirstControlPoint()
```


베지어 스플라인의 첫 번째 제어점을 가져옵니다.

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The first control point.
### getSecondControlPoint() {#getSecondControlPoint--}
```
public PointF getSecondControlPoint()
```


베지어 스플라인의 두 번째 제어점을 가져옵니다.

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The second control point.
### getStartPoint() {#getStartPoint--}
```
public PointF getStartPoint()
```


시작점을 가져옵니다.

값: 시작점.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
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

