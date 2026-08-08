---
title: "IPathShape"
second_title: "Java용 Aspose.PSD API 참조"
description: "그 Bezier 곡선의 매듭에서 만든 Shape."
type: docs
weight: 31
url: /ko/java/com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/ipathshape/
---
```
public interface IPathShape
```

그 Bezier 곡선의 매듭에서 만든 Shape.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getItems()](#getItems--) | Bezier 매듭 배열을 가져옵니다. |
| [getPathOperations()](#getPathOperations--) | 경로 형태 결합(불리언 연산)을 위한 연산. |
| [isClosed()](#isClosed--) | Shape가 닫혀 있는지 여부를 결정하는 속성을 가져오거나 설정합니다. |
| [setClosed(boolean value)](#setClosed-boolean-) | Shape가 닫혀 있는지 여부를 결정하는 속성을 가져오거나 설정합니다. |
| [setItems(BezierKnotRecord[] bezierPoints)](#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.BezierKnotRecord---) | Bexier 매듭 배열을 할당합니다. |
| [setPathOperations(int value)](#setPathOperations-int-) | 경로 형태 결합(불리언 연산)을 위한 연산. |
### getItems() {#getItems--}
```
public abstract BezierKnotRecord[] getItems()
```


Bezier 매듭 배열을 가져옵니다.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.BezierKnotRecord[] - BezierKnotRecord 배열.
### getPathOperations() {#getPathOperations--}
```
public abstract int getPathOperations()
```


경로 형태 결합(불리언 연산)을 위한 연산.

**Returns:**
int
### isClosed() {#isClosed--}
```
public abstract boolean isClosed()
```


Shape가 닫혀 있는지 여부를 결정하는 속성을 가져오거나 설정합니다.

**Returns:**
boolean
### setClosed(boolean value) {#setClosed-boolean-}
```
public abstract void setClosed(boolean value)
```


Shape가 닫혀 있는지 여부를 결정하는 속성을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setItems(BezierKnotRecord[] bezierPoints) {#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.BezierKnotRecord---}
```
public abstract void setItems(BezierKnotRecord[] bezierPoints)
```


Bexier 매듭 배열을 할당합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| bezierPoints | [BezierKnotRecord\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/bezierknotrecord) | Bezier 매듭 배열 |

### setPathOperations(int value) {#setPathOperations-int-}
```
public abstract void setPathOperations(int value)
```


경로 형태 결합(불리언 연산)을 위한 연산.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

