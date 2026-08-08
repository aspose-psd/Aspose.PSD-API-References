---
title: "VectorPath"
second_title: "Java용 Aspose.PSD API 참조"
description: "벡터 경로를 포함하는 클래스."
type: docs
weight: 17
url: /ko/java/com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpath/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.IPath](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/ipath)
```
public class VectorPath implements IPath
```

벡터 경로를 포함하는 클래스.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [VectorPath()](#VectorPath--) | VectorPath의 새 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [create_internalized(VectorPathDataResource vectorPathDataResource)](#create-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorPathDataResource-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getItems()](#getItems--) | Path에 있는 Shapes 배열을 가져옵니다. |
| [getVersion()](#getVersion--) | 버전을 가져오거나 설정합니다. |
| [hashCode()](#hashCode--) |  |
| [isDisabled()](#isDisabled--) | 이 인스턴스가 비활성화되었는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [isFillStartsWithAllPixels()](#isFillStartsWithAllPixels--) | 채우기가 모든 픽셀에서 시작되는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [isInverted()](#isInverted--) | 이 인스턴스가 반전되었는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [isNotLinked()](#isNotLinked--) | 이 인스턴스가 연결되지 않았는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDisabled(boolean value)](#setDisabled-boolean-) | 이 인스턴스가 비활성화되었는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [setFillStartsWithAllPixels(boolean value)](#setFillStartsWithAllPixels-boolean-) | 채우기가 모든 픽셀에서 시작되는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [setInverted(boolean value)](#setInverted-boolean-) | 이 인스턴스가 반전되었는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [setItems(IPathShape[] shapes)](#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.IPathShape---) | Path에 있는 Shapes 배열을 설정합니다. |
| [setNotLinked(boolean value)](#setNotLinked-boolean-) | 이 인스턴스가 연결되지 않았는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [setVersion(int value)](#setVersion-int-) | 버전을 가져오거나 설정합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### VectorPath() {#VectorPath--}
```
public VectorPath()
```


VectorPath의 새 인스턴스를 초기화합니다.

### create_internalized(VectorPathDataResource vectorPathDataResource) {#create-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorPathDataResource-}
```
public static VectorPath create_internalized(VectorPathDataResource vectorPathDataResource)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| vectorPathDataResource | [VectorPathDataResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathdataresource) |  |

**Returns:**
[VectorPath](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpath)
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
public final IPathShape[] getItems()
```


Path에 있는 Shapes 배열을 가져옵니다.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.IPathShape[] - IPathShape 배열.
### getVersion() {#getVersion--}
```
public final int getVersion()
```


버전을 가져오거나 설정합니다.

값: 버전.

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isDisabled() {#isDisabled--}
```
public final boolean isDisabled()
```


이 인스턴스가 비활성화되었는지 여부를 나타내는 값을 가져오거나 설정합니다.

값:  true  이 인스턴스가 비활성화된 경우; 그렇지 않으면,  false .

**Returns:**
boolean
### isFillStartsWithAllPixels() {#isFillStartsWithAllPixels--}
```
public final boolean isFillStartsWithAllPixels()
```


채우기가 모든 픽셀에서 시작되는지 여부를 나타내는 값을 가져오거나 설정합니다.

값: 채우기가 모든 픽셀에서 시작됩니다.

**Returns:**
boolean
### isInverted() {#isInverted--}
```
public final boolean isInverted()
```


이 인스턴스가 반전되었는지 여부를 나타내는 값을 가져오거나 설정합니다.

값:  true  이 인스턴스가 반전된 경우; 그렇지 않으면,  false .

**Returns:**
boolean
### isNotLinked() {#isNotLinked--}
```
public final boolean isNotLinked()
```


이 인스턴스가 연결되지 않았는지 여부를 나타내는 값을 가져오거나 설정합니다.

값:  true  이 인스턴스가 연결되지 않은 경우; 그렇지 않으면,  false .

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




### setDisabled(boolean value) {#setDisabled-boolean-}
```
public final void setDisabled(boolean value)
```


이 인스턴스가 비활성화되었는지 여부를 나타내는 값을 가져오거나 설정합니다.

값:  true  이 인스턴스가 비활성화된 경우; 그렇지 않으면,  false .

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setFillStartsWithAllPixels(boolean value) {#setFillStartsWithAllPixels-boolean-}
```
public final void setFillStartsWithAllPixels(boolean value)
```


채우기가 모든 픽셀에서 시작되는지 여부를 나타내는 값을 가져오거나 설정합니다.

값: 채우기가 모든 픽셀에서 시작됩니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setInverted(boolean value) {#setInverted-boolean-}
```
public final void setInverted(boolean value)
```


이 인스턴스가 반전되었는지 여부를 나타내는 값을 가져오거나 설정합니다.

값:  true  이 인스턴스가 반전된 경우; 그렇지 않으면,  false .

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setItems(IPathShape[] shapes) {#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.IPathShape---}
```
public final void setItems(IPathShape[] shapes)
```


Path에 있는 Shapes 배열을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| shapes | [IPathShape\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/ipathshape) | IPathShape 배열. |

### setNotLinked(boolean value) {#setNotLinked-boolean-}
```
public final void setNotLinked(boolean value)
```


이 인스턴스가 연결되지 않았는지 여부를 나타내는 값을 가져오거나 설정합니다.

값:  true  이 인스턴스가 연결되지 않은 경우; 그렇지 않으면,  false .

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setVersion(int value) {#setVersion-int-}
```
public final void setVersion(int value)
```


버전을 가져오거나 설정합니다.

값: 버전.

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

