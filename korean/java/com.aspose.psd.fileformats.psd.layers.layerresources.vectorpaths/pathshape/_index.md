---
title: "PathShape"
second_title: "Java용 Aspose.PSD API 참조"
description: "베지어 곡선의 매듭으로부터 만든 도형."
type: docs
weight: 16
url: /ko/java/com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/pathshape/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.IPathShape](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/ipathshape)
```
public class PathShape implements IPathShape
```

베지어 곡선의 매듭으로부터 만든 도형.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [PathShape()](#PathShape--) | 새 인스턴스를 초기화합니다. [PathShape](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/pathshape) 클래스. |
| [PathShape(LengthRecord lengthRecord, BezierKnotRecord[] bezierKnotRecords)](#PathShape-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.LengthRecord-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.BezierKnotRecord---) | 새 인스턴스를 초기화합니다. [PathShape](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/pathshape) 클래스. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getItems()](#getItems--) | Bezier 매듭 배열을 가져옵니다. |
| [getPathOperations()](#getPathOperations--) | 경로 연산(불리언 연산)을 가져오거나 설정합니다. |
| [getShapeIndex()](#getShapeIndex--) | 레이어에서 현재 경로 모양의 인덱스를 가져오거나 설정합니다. |
| [hashCode()](#hashCode--) |  |
| [isClosed()](#isClosed--) | 이 인스턴스가 닫혔는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setClosed(boolean value)](#setClosed-boolean-) | 이 인스턴스가 닫혔는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [setItems(BezierKnotRecord[] bezierPoints)](#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.BezierKnotRecord---) | Bezier 매듭 배열을 할당합니다. |
| [setPathOperations(int value)](#setPathOperations-int-) | 경로 연산(불리언 연산)을 가져오거나 설정합니다. |
| [setShapeIndex(int value)](#setShapeIndex-int-) | 레이어에서 현재 경로 모양의 인덱스를 가져오거나 설정합니다. |
| [toString()](#toString--) |  |
| [toVectorPathRecords()](#toVectorPathRecords--) | 이 인스턴스를 기반으로 VectorPathRecord 레코드를 생성합니다. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PathShape() {#PathShape--}
```
public PathShape()
```


새 인스턴스를 초기화합니다. [PathShape](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/pathshape) 클래스.

### PathShape(LengthRecord lengthRecord, BezierKnotRecord[] bezierKnotRecords) {#PathShape-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.LengthRecord-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.BezierKnotRecord---}
```
public PathShape(LengthRecord lengthRecord, BezierKnotRecord[] bezierKnotRecords)
```


새 인스턴스를 초기화합니다. [PathShape](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/pathshape) 클래스.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| lengthRecord | [LengthRecord](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/lengthrecord) | 길이 레코드. |
| bezierKnotRecords | [BezierKnotRecord\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/bezierknotrecord) | Bezier 매듭 레코드. |

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
### getItems() {#getItems--}
```
public final BezierKnotRecord[] getItems()
```


Bezier 매듭 배열을 가져옵니다.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.BezierKnotRecord[] - BezierKnotRecord 배열
### getPathOperations() {#getPathOperations--}
```
public final int getPathOperations()
```


경로 연산(불리언 연산)을 가져오거나 설정합니다.

**Returns:**
int
### getShapeIndex() {#getShapeIndex--}
```
public final int getShapeIndex()
```


레이어에서 현재 경로 모양의 인덱스를 가져오거나 설정합니다.

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isClosed() {#isClosed--}
```
public final boolean isClosed()
```


이 인스턴스가 닫혔는지 여부를 나타내는 값을 가져오거나 설정합니다.

값: 이 인스턴스가 닫혔으면 true, 그렇지 않으면 false.

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




### setClosed(boolean value) {#setClosed-boolean-}
```
public final void setClosed(boolean value)
```


이 인스턴스가 닫혔는지 여부를 나타내는 값을 가져오거나 설정합니다.

값: 이 인스턴스가 닫혔으면 true, 그렇지 않으면 false.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setItems(BezierKnotRecord[] bezierPoints) {#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.BezierKnotRecord---}
```
public final void setItems(BezierKnotRecord[] bezierPoints)
```


Bezier 매듭 배열을 할당합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| bezierPoints | [BezierKnotRecord\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/bezierknotrecord) | Bezier 매듭 배열 |

### setPathOperations(int value) {#setPathOperations-int-}
```
public final void setPathOperations(int value)
```


경로 연산(불리언 연산)을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setShapeIndex(int value) {#setShapeIndex-int-}
```
public final void setShapeIndex(int value)
```


레이어에서 현재 경로 모양의 인덱스를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### toVectorPathRecords() {#toVectorPathRecords--}
```
public final System.Collections.Generic.IGenericEnumerable<VectorPathRecord> toVectorPathRecords()
```


이 인스턴스를 기반으로 VectorPathRecord 레코드를 생성합니다.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorPathRecord> - 이 인스턴스의 각 포인트에 대해 LengthRecord와 BezierKnotRecord를 각각 반환합니다.
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

