---
title: "Timecode"
second_title: "Java용 Aspose.PSD API 참조"
description: "비디오에서 타임코드 값을 나타냅니다."
type: docs
weight: 15
url: /ko/java/com.aspose.psd.xmp.schemas.xmpdm/timecode/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.types.XmpTypeBase](../../com.aspose.psd.xmp.types/xmptypebase)

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public final class Timecode extends XmpTypeBase implements System.IEquatable<Timecode>
```

비디오에서 타임코드 값을 나타냅니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [Timecode(TimeFormat format, String timeValue)](#Timecode-com.aspose.psd.xmp.schemas.xmpdm.TimeFormat-java.lang.String-) | Timecode 클래스의 새 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | 지정된 System.Object가 이 인스턴스와 같은지 여부를 결정합니다. |
| [getClass()](#getClass--) |  |
| [getFormat()](#getFormat--) | TimeValue에서 사용되는 형식을 가져오거나 설정합니다. |
| [getTimeValue()](#getTimeValue--) | 지정된 형식으로 시간 값을 가져오거나 설정합니다. |
| [getXmpRepresentation()](#getXmpRepresentation--) | XMP 형식으로 포함된 문자열 값을 반환합니다. |
| [hashCode()](#hashCode--) | 이 인스턴스에 대한 해시 코드를 반환합니다. |
| [isEquals(Timecode other)](#isEquals-com.aspose.psd.xmp.schemas.xmpdm.Timecode-) | 현재 객체가 동일한 유형의 다른 객체와 같은지 여부를 나타냅니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFormat(TimeFormat value)](#setFormat-com.aspose.psd.xmp.schemas.xmpdm.TimeFormat-) | TimeValue에서 사용되는 형식을 가져오거나 설정합니다. |
| [setTimeValue(String value)](#setTimeValue-java.lang.String-) | 지정된 형식으로 시간 값을 가져오거나 설정합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Timecode(TimeFormat format, String timeValue) {#Timecode-com.aspose.psd.xmp.schemas.xmpdm.TimeFormat-java.lang.String-}
```
public Timecode(TimeFormat format, String timeValue)
```


Timecode 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| format | [TimeFormat](../../com.aspose.psd.xmp.schemas.xmpdm/timeformat) | 시간 형식. |
| timeValue | java.lang.String | 시간 값. |

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
### getFormat() {#getFormat--}
```
public TimeFormat getFormat()
```


TimeValue에서 사용되는 형식을 가져오거나 설정합니다.

Value: TimeValue에서 사용되는 형식.

**Returns:**
[TimeFormat](../../com.aspose.psd.xmp.schemas.xmpdm/timeformat)
### getTimeValue() {#getTimeValue--}
```
public String getTimeValue()
```


지정된 형식으로 시간 값을 가져오거나 설정합니다.

Value: 지정된 형식의 시간 값.

**Returns:**
java.lang.String
### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


XMP 형식으로 포함된 문자열 값을 반환합니다.

**Returns:**
java.lang.String - XMP 형식의 문자열 포함 값을 반환합니다.
### hashCode() {#hashCode--}
```
public int hashCode()
```


이 인스턴스에 대한 해시 코드를 반환합니다.

**Returns:**
int - 이 인스턴스에 대한 해시 코드이며, 해시 알고리즘 및 해시 테이블과 같은 데이터 구조에 사용하기에 적합합니다.
### isEquals(Timecode other) {#isEquals-com.aspose.psd.xmp.schemas.xmpdm.Timecode-}
```
public boolean isEquals(Timecode other)
```


현재 객체가 동일한 유형의 다른 객체와 같은지 여부를 나타냅니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| other | [Timecode](../../com.aspose.psd.xmp.schemas.xmpdm/timecode) | 이 객체와 비교할 객체. |

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




### setFormat(TimeFormat value) {#setFormat-com.aspose.psd.xmp.schemas.xmpdm.TimeFormat-}
```
public void setFormat(TimeFormat value)
```


TimeValue에서 사용되는 형식을 가져오거나 설정합니다.

Value: TimeValue에서 사용되는 형식.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [TimeFormat](../../com.aspose.psd.xmp.schemas.xmpdm/timeformat) |  |

### setTimeValue(String value) {#setTimeValue-java.lang.String-}
```
public void setTimeValue(String value)
```


지정된 형식으로 시간 값을 가져오거나 설정합니다.

Value: 지정된 형식의 시간 값.

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

