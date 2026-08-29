---
title: "XmpGuid"
second_title: "Java용 Aspose.PSD API 참조"
description: "XMP 전역 고유 식별자를 나타냅니다."
type: docs
weight: 14
url: /ko/java/com.aspose.psd.xmp.types.derived/xmpguid/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.types.XmpTypeBase](../../com.aspose.psd.xmp.types/xmptypebase)
```
public final class XmpGuid extends XmpTypeBase
```

XMP 전역 고유 식별자를 나타냅니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [XmpGuid(String value)](#XmpGuid-java.lang.String-) | XmpGuid 클래스의 새 인스턴스를 초기화합니다. |
| [XmpGuid(UUID guid)](#XmpGuid-java.util.UUID-) | XmpGuid 클래스의 새 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getPrefix()](#getPrefix--) | uuid와 같은 접두사를 가져오거나 설정합니다. |
| [getValue()](#getValue--) | 값을 가져오거나 설정합니다. |
| [getValue_internalized()](#getValue-internalized--) |  |
| [getXmpRepresentation()](#getXmpRepresentation--) | XMP 형식의 문자열 포함 값을 가져옵니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setPrefix(String value)](#setPrefix-java.lang.String-) | uuid와 같은 접두사를 가져오거나 설정합니다. |
| [setValue(UUID value)](#setValue-java.util.UUID-) | 값을 가져오거나 설정합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpGuid(String value) {#XmpGuid-java.lang.String-}
```
public XmpGuid(String value)
```


XmpGuid 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String | 값. |

### XmpGuid(UUID guid) {#XmpGuid-java.util.UUID-}
```
public XmpGuid(UUID guid)
```


XmpGuid 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| guid | java.util.UUID | 고유 식별자. |

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
### getPrefix() {#getPrefix--}
```
public String getPrefix()
```


uuid와 같은 접두사를 가져오거나 설정합니다.

값: uuid와 같은 접두사.

**Returns:**
java.lang.String
### getValue() {#getValue--}
```
public UUID getValue()
```


값을 가져오거나 설정합니다.

값: 해당 값입니다.

**Returns:**
java.util.UUID
### getValue_internalized() {#getValue-internalized--}
```
public System.Guid getValue_internalized()
```




**Returns:**
com.aspose.ms.System.Guid
### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


XMP 형식의 문자열 포함 값을 가져옵니다.

**Returns:**
java.lang.String - XMP 형식의 문자열 포함 값을 반환합니다.
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




### setPrefix(String value) {#setPrefix-java.lang.String-}
```
public void setPrefix(String value)
```


uuid와 같은 접두사를 가져오거나 설정합니다.

값: uuid와 같은 접두사.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setValue(UUID value) {#setValue-java.util.UUID-}
```
public void setValue(UUID value)
```


값을 가져오거나 설정합니다.

값: 해당 값입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.util.UUID |  |

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

