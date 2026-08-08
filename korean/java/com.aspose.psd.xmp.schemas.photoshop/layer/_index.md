---
title: "레이어"
second_title: "Java용 Aspose.PSD API 참조"
description: "Photoshop 텍스트 레이어를 나타냅니다."
type: docs
weight: 11
url: /ko/java/com.aspose.psd.xmp.schemas.photoshop/layer/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.types.XmpTypeBase](../../com.aspose.psd.xmp.types/xmptypebase)

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public class Layer extends XmpTypeBase implements System.IEquatable<Layer>
```

Photoshop 텍스트 레이어를 나타냅니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [Layer(String layerName, String layerText)](#Layer-java.lang.String-java.lang.String-) | 새로운  Layer  클래스의 인스턴스를 초기화합니다. |
| [Layer()](#Layer--) | 새로운  Layer  클래스의 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | 지정된 System.Object가 이 인스턴스와 같은지 여부를 결정합니다. |
| [getClass()](#getClass--) |  |
| [getName()](#getName--) | 텍스트 레이어의 이름을 가져오거나 설정합니다. |
| [getText()](#getText--) | 레이어의 텍스트 내용을 가져오거나 설정합니다. |
| [getXmpRepresentation()](#getXmpRepresentation--) | XMP 형식으로 포함된 문자열 값을 반환합니다. |
| [hashCode()](#hashCode--) | 이 인스턴스에 대한 해시 코드를 반환합니다. |
| [isEquals(Layer other)](#isEquals-com.aspose.psd.xmp.schemas.photoshop.Layer-) | 현재 객체가 동일한 유형의 다른 객체와 같은지 여부를 나타냅니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setName(String value)](#setName-java.lang.String-) | 텍스트 레이어의 이름을 가져오거나 설정합니다. |
| [setText(String value)](#setText-java.lang.String-) | 레이어의 텍스트 내용을 가져오거나 설정합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Layer(String layerName, String layerText) {#Layer-java.lang.String-java.lang.String-}
```
public Layer(String layerName, String layerText)
```


새로운  Layer  클래스의 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| layerName | java.lang.String | 레이어 이름. |
| layerText | java.lang.String | 레이어 텍스트. |

### Layer() {#Layer--}
```
public Layer()
```


새로운  Layer  클래스의 인스턴스를 초기화합니다.

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


지정된 System.Object가 이 인스턴스와 같은지 여부를 결정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | java.lang.Object | 이 인스턴스와 비교할 System.Object. |

**Returns:**
boolean - 지정된 System.Object가 이 인스턴스와 같으면 true; 그렇지 않으면 false.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getName() {#getName--}
```
public String getName()
```


텍스트 레이어의 이름을 가져오거나 설정합니다.

값: 텍스트 레이어의 이름.

**Returns:**
java.lang.String
### getText() {#getText--}
```
public String getText()
```


레이어의 텍스트 내용을 가져오거나 설정합니다.

값: 레이어의 텍스트 내용.

**Returns:**
java.lang.String
### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


XMP 형식으로 포함된 문자열 값을 반환합니다.

**Returns:**
java.lang.String - XMP 형식으로 포함된 문자열 값을 반환합니다.
### hashCode() {#hashCode--}
```
public int hashCode()
```


이 인스턴스에 대한 해시 코드를 반환합니다.

**Returns:**
int - 이 인스턴스에 대한 해시 코드이며, 해시 알고리즘 및 해시 테이블과 같은 데이터 구조에 사용하기에 적합합니다.
### isEquals(Layer other) {#isEquals-com.aspose.psd.xmp.schemas.photoshop.Layer-}
```
public boolean isEquals(Layer other)
```


현재 객체가 동일한 유형의 다른 객체와 같은지 여부를 나타냅니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| other | [Layer](../../com.aspose.psd.xmp.schemas.photoshop/layer) | 이 객체와 비교할 객체. |

**Returns:**
boolean - 현재 객체가 other 매개변수와 같으면 true; 그렇지 않으면 false.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


텍스트 레이어의 이름을 가져오거나 설정합니다.

값: 텍스트 레이어의 이름.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


레이어의 텍스트 내용을 가져오거나 설정합니다.

값: 레이어의 텍스트 내용.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

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

