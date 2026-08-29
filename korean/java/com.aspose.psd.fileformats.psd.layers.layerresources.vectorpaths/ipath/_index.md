---
title: "IPath"
second_title: "Java용 Aspose.PSD API 참조"
description: "인터페이스는 Shape 레이어에 존재하는 Path 집합을 설명합니다."
type: docs
weight: 30
url: /ko/java/com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/ipath/
---
```
public interface IPath
```

인터페이스는 Shape 레이어에 존재하는 Path 집합을 설명합니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getItems()](#getItems--) | Path에 있는 Shapes 배열을 가져옵니다. |
| [isDisabled()](#isDisabled--) | 경로가 비활성화되었습니다. |
| [isInverted()](#isInverted--) | 경로가 반전되었습니다. |
| [isNotLinked()](#isNotLinked--) | 경로가 연결되지 않았습니다. |
| [setDisabled(boolean value)](#setDisabled-boolean-) | 경로가 비활성화되었습니다. |
| [setInverted(boolean value)](#setInverted-boolean-) | 경로가 반전되었습니다. |
| [setItems(IPathShape[] shapes)](#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.IPathShape---) | Path에 있는 Shapes 배열을 설정합니다. |
| [setNotLinked(boolean value)](#setNotLinked-boolean-) | 경로가 연결되지 않았습니다. |
### getItems() {#getItems--}
```
public abstract IPathShape[] getItems()
```


Path에 있는 Shapes 배열을 가져옵니다.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.IPathShape[] - IPathShape 배열.
### isDisabled() {#isDisabled--}
```
public abstract boolean isDisabled()
```


경로가 비활성화되었습니다.

**Returns:**
boolean
### isInverted() {#isInverted--}
```
public abstract boolean isInverted()
```


경로가 반전되었습니다.

**Returns:**
boolean
### isNotLinked() {#isNotLinked--}
```
public abstract boolean isNotLinked()
```


경로가 연결되지 않았습니다.

**Returns:**
boolean
### setDisabled(boolean value) {#setDisabled-boolean-}
```
public abstract void setDisabled(boolean value)
```


경로가 비활성화되었습니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setInverted(boolean value) {#setInverted-boolean-}
```
public abstract void setInverted(boolean value)
```


경로가 반전되었습니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setItems(IPathShape[] shapes) {#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.IPathShape---}
```
public abstract void setItems(IPathShape[] shapes)
```


Path에 있는 Shapes 배열을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| shapes | [IPathShape\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/ipathshape) | IPathShape 배열. |

### setNotLinked(boolean value) {#setNotLinked-boolean-}
```
public abstract void setNotLinked(boolean value)
```


경로가 연결되지 않았습니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

