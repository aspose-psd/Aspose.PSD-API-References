---
title: "ComplexTypeBase"
second_title: "Java용 Aspose.PSD API 참조"
description: "XMP 복합 값 유형에 대한 기본 추상화를 나타냅니다."
type: docs
weight: 10
url: /ko/java/com.aspose.psd.xmp.types.complex/complextypebase/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.types.XmpTypeBase](../../com.aspose.psd.xmp.types/xmptypebase)
```
public class ComplexTypeBase extends XmpTypeBase
```

XMP 복합 값 유형에 대한 기본 추상화를 나타냅니다.

자세히 보기: XMP Specification Part 2, Chapter 1.2.2
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [ComplexTypeBase(String prefix, String namespaceUri)](#ComplexTypeBase-java.lang.String-java.lang.String-) | 새로운  ComplexTypeBase  클래스 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [add(String key, Object value)](#add-java.lang.String-java.lang.Object-) | 지정된 키를 추가합니다. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getNamespaceUri()](#getNamespaceUri--) | 기본 네임스페이스 URI를 가져옵니다. |
| [getPrefix()](#getPrefix--) | 접두사를 가져옵니다. |
| [getXmpRepresentation()](#getXmpRepresentation--) | XMP 형식의 문자열 포함 값을 가져옵니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ComplexTypeBase(String prefix, String namespaceUri) {#ComplexTypeBase-java.lang.String-java.lang.String-}
```
public ComplexTypeBase(String prefix, String namespaceUri)
```


새로운  ComplexTypeBase  클래스 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| prefix | java.lang.String | 접두사입니다. |
| namespaceUri | java.lang.String | 네임스페이스 URI입니다. |

### add(String key, Object value) {#add-java.lang.String-java.lang.Object-}
```
public void add(String key, Object value)
```


지정된 키를 추가합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 키 | java.lang.String | 추가된 값과 식별되는 키의 문자열 표현. |
| 값 | java.lang.Object | 추가할 값. |

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
### getNamespaceUri() {#getNamespaceUri--}
```
public String getNamespaceUri()
```


기본 네임스페이스 URI를 가져옵니다.

**Returns:**
java.lang.String - 기본 네임스페이스 URI.
### getPrefix() {#getPrefix--}
```
public String getPrefix()
```


접두사를 가져옵니다.

**Returns:**
java.lang.String - 접두사.
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

