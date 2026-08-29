---
title: "ResourceEvent"
second_title: "Java용 Aspose.PSD API 참조"
description: "그려진 객체의 차원을 포함합니다."
type: docs
weight: 10
url: /ko/java/com.aspose.psd.xmp.types.complex.resourceevent/resourceevent/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.types.XmpTypeBase](../../com.aspose.psd.xmp.types/xmptypebase), [com.aspose.psd.xmp.types.complex.ComplexTypeBase](../../com.aspose.psd.xmp.types.complex/complextypebase)
```
public final class ResourceEvent extends ComplexTypeBase
```

그려진 객체의 차원을 포함합니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [ResourceEvent()](#ResourceEvent--) | 새 인스턴스를 초기화합니다  ResourceEvent  클래스의. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [add(String key, Object value)](#add-java.lang.String-java.lang.Object-) | 지정된 키를 추가합니다. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAction()](#getAction--) | 동작을 가져옵니다. |
| [getActionDate()](#getActionDate--) | 동작 날짜를 가져오거나 설정합니다. |
| [getChanged()](#getChanged--) | 이전 이벤트 기록 이후 변경된 리소스 부분들의 세미콜론 구분 목록을 가져옵니다. |
| [getClass()](#getClass--) |  |
| [getInstanceId()](#getInstanceId--) | xmpMM:InstanceId의 값을 가져옵니다. |
| [getNamespaceUri()](#getNamespaceUri--) | 기본 네임스페이스 URI를 가져옵니다. |
| [getParameters()](#getParameters--) | 동작에 대한 추가 설명을 가져오거나 설정합니다. |
| [getPrefix()](#getPrefix--) | 접두사를 가져옵니다. |
| [getSofwareAgentName()](#getSofwareAgentName--) | 소프트웨어 에이전트 이름을 가져오거나 설정합니다. |
| [getXmpRepresentation()](#getXmpRepresentation--) | XMP 형식의 문자열 포함 값을 가져옵니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAction(String value)](#setAction-java.lang.String-) | 동작을 설정합니다. |
| [setActionDate(Date value)](#setActionDate-java.util.Date-) | 동작 날짜를 가져오거나 설정합니다. |
| [setChanged(String value)](#setChanged-java.lang.String-) | 이전 이벤트 기록 이후 변경된 리소스 부분들의 세미콜론 구분 목록을 설정합니다. |
| [setInstanceId(UUID value)](#setInstanceId-java.util.UUID-) | xmpMM:InstanceId의 값을 가져오거나 설정합니다. |
| [setParameters(String value)](#setParameters-java.lang.String-) | 동작에 대한 추가 설명을 가져오거나 설정합니다. |
| [setSofwareAgentName(String value)](#setSofwareAgentName-java.lang.String-) | 소프트웨어 에이전트 이름을 가져오거나 설정합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ResourceEvent() {#ResourceEvent--}
```
public ResourceEvent()
```


새 인스턴스를 초기화합니다  ResourceEvent  클래스의.

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
### getAction() {#getAction--}
```
public String getAction()
```


동작을 가져옵니다.

정의된 값은: converted, copied, created, cropped, edited, filtered, formatted, version\_updated, printed, published, managed, produced, resized, saved. 새 값은 과거 시제 동사여야 합니다.

**Returns:**
java.lang.String - 동작.
### getActionDate() {#getActionDate--}
```
public Date getActionDate()
```


동작 날짜를 가져오거나 설정합니다.

**Returns:**
java.util.Date - 작업 날짜.
### getChanged() {#getChanged--}
```
public String getChanged()
```


이전 이벤트 기록 이후 변경된 리소스 부분들의 세미콜론 구분 목록을 가져옵니다.

**Returns:**
java.lang.String - 세미콜론으로 구분된 리소스의 부분 목록으로, 이전 이벤트 기록 이후 변경된 부분을 나타냅니다.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getInstanceId() {#getInstanceId--}
```
public UUID getInstanceId()
```


xmpMM:InstanceId의 값을 가져옵니다.

**Returns:**
java.util.UUID - xmpMM:InstanceId의 값.
### getNamespaceUri() {#getNamespaceUri--}
```
public String getNamespaceUri()
```


기본 네임스페이스 URI를 가져옵니다.

**Returns:**
java.lang.String - 기본 네임스페이스 URI.
### getParameters() {#getParameters--}
```
public String getParameters()
```


동작에 대한 추가 설명을 가져오거나 설정합니다.

Value: 작업에 대한 추가 설명.

**Returns:**
java.lang.String
### getPrefix() {#getPrefix--}
```
public String getPrefix()
```


접두사를 가져옵니다.

**Returns:**
java.lang.String - 접두사.
### getSofwareAgentName() {#getSofwareAgentName--}
```
public String getSofwareAgentName()
```


소프트웨어 에이전트 이름을 가져오거나 설정합니다.

**Returns:**
java.lang.String - 소프트웨어 에이전트 이름.
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




### setAction(String value) {#setAction-java.lang.String-}
```
public void setAction(String value)
```


동작을 설정합니다.

정의된 값은: converted, copied, created, cropped, edited, filtered, formatted, version\_updated, printed, published, managed, produced, resized, saved. 새 값은 과거 시제 동사여야 합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String | 작업. |

### setActionDate(Date value) {#setActionDate-java.util.Date-}
```
public void setActionDate(Date value)
```


동작 날짜를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.util.Date | 작업 날짜. |

### setChanged(String value) {#setChanged-java.lang.String-}
```
public void setChanged(String value)
```


이전 이벤트 기록 이후 변경된 리소스 부분들의 세미콜론 구분 목록을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String | 세미콜론으로 구분된 리소스의 부분 목록으로, 이전 이벤트 기록 이후 변경된 부분을 나타냅니다. |

### setInstanceId(UUID value) {#setInstanceId-java.util.UUID-}
```
public void setInstanceId(UUID value)
```


xmpMM:InstanceId의 값을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.util.UUID | xmpMM:InstanceId의 값. |

### setParameters(String value) {#setParameters-java.lang.String-}
```
public void setParameters(String value)
```


동작에 대한 추가 설명을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String | 작업에 대한 추가 설명. |

### setSofwareAgentName(String value) {#setSofwareAgentName-java.lang.String-}
```
public void setSofwareAgentName(String value)
```


소프트웨어 에이전트 이름을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String | 소프트웨어 에이전트 이름. |

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

