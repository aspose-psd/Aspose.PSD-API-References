---
title: "XmpDate"
second_title: "Java용 Aspose.PSD API 참조"
description: "XMP 패킷의 Date를 나타냅니다."
type: docs
weight: 11
url: /ko/java/com.aspose.psd.xmp.types.basic/xmpdate/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.types.XmpTypeBase](../../com.aspose.psd.xmp.types/xmptypebase)
```
public final class XmpDate extends XmpTypeBase
```

XMP 패킷의 Date를 나타냅니다.

날짜-시간 값은 날짜 및 시간 형식에 정의된 형식 중 일부를 사용하여 표현됩니다: YYYY YYYY-MM YYYY-MM-DD YYYY-MM-DDThh:mmTZD YYYY-MM-DDThh:mm:ssTZD YYYY-MM-DDThh:mm:ss.sTZD
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [XmpDate(Date dateTime)](#XmpDate-java.util.Date-) | XmpDate 클래스의 새 인스턴스를 초기화합니다. |
| [XmpDate(String dateString)](#XmpDate-java.lang.String-) | XmpDate 클래스의 새 인스턴스를 초기화합니다. |
## 필드

| 필드 | 설명 |
| --- | --- |
| [Iso8601Format](#Iso8601Format) | ISO 8601(라운드트립) 형식 문자열입니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [create_internalized(System.DateTime dateTime)](#create-internalized-com.aspose.ms.System.DateTime-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFormat()](#getFormat--) | 현재 값에 대한 형식 문자열을 가져옵니다. |
| [getValue()](#getValue--) | 날짜 값을 가져오거나 설정합니다. |
| [getValue_internalized()](#getValue-internalized--) |  |
| [getXmpRepresentation()](#getXmpRepresentation--) | XMP 형식으로 포함된 문자열 값을 반환합니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setValue(Date value)](#setValue-java.util.Date-) | 날짜 값을 가져오거나 설정합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpDate(Date dateTime) {#XmpDate-java.util.Date-}
```
public XmpDate(Date dateTime)
```


XmpDate 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| dateTime | java.util.Date | ISO RFC 8601 형식의 하위 집합을 사용하여 표현되는 날짜-시간 값입니다. |

### XmpDate(String dateString) {#XmpDate-java.lang.String-}
```
public XmpDate(String dateString)
```


XmpDate 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| dateString | java.lang.String | 날짜의 문자열 표현입니다. |

### Iso8601Format {#Iso8601Format}
```
public static final String Iso8601Format
```


ISO 8601(라운드트립) 형식 문자열입니다.

자세히 보기: https://en.wikipedia.org/wiki/ISO\_8601.

### create_internalized(System.DateTime dateTime) {#create-internalized-com.aspose.ms.System.DateTime-}
```
public static XmpDate create_internalized(System.DateTime dateTime)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| dateTime | com.aspose.ms.System.DateTime |  |

**Returns:**
[XmpDate](../../com.aspose.psd.xmp.types.basic/xmpdate)
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
### getFormat() {#getFormat--}
```
public String getFormat()
```


현재 값에 대한 형식 문자열을 가져옵니다.

값: 현재 값에 대한 형식 문자열입니다.

**Returns:**
java.lang.String
### getValue() {#getValue--}
```
public Date getValue()
```


날짜 값을 가져오거나 설정합니다.

값: 날짜 값입니다.

**Returns:**
java.util.Date
### getValue_internalized() {#getValue-internalized--}
```
public System.DateTime getValue_internalized()
```




**Returns:**
com.aspose.ms.System.DateTime
### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


XMP 형식으로 포함된 문자열 값을 반환합니다.

**Returns:**
java.lang.String - XMP 형식으로 포함된 문자열 값을 반환합니다.
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




### setValue(Date value) {#setValue-java.util.Date-}
```
public void setValue(Date value)
```


날짜 값을 가져오거나 설정합니다.

값: 날짜 값입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.util.Date |  |

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

