---
title: "Time"
second_title: "Java용 Aspose.PSD API 참조"
description: "시간 값을 초 단위로 나타냅니다."
type: docs
weight: 13
url: /ko/java/com.aspose.psd.xmp.schemas.xmpdm/time/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.types.XmpTypeBase](../../com.aspose.psd.xmp.types/xmptypebase)
```
public final class Time extends XmpTypeBase
```

시간 값을 초 단위로 나타냅니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [Time(Rational scale, int value)](#Time-com.aspose.psd.xmp.types.derived.Rational-int-) | Time 클래스의 새 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getScale()](#getScale--) | 시간 값의 스케일을 가져오거나 설정합니다. |
| [getValue()](#getValue--) | 지정된 스케일에서 시간 값을 가져오거나 설정합니다. |
| [getXmpRepresentation()](#getXmpRepresentation--) | XMP 형식의 문자열 포함 값을 가져옵니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setScale(Rational value)](#setScale-com.aspose.psd.xmp.types.derived.Rational-) | 시간 값의 스케일을 가져오거나 설정합니다. |
| [setValue(int value)](#setValue-int-) | 지정된 스케일에서 시간 값을 가져오거나 설정합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Time(Rational scale, int value) {#Time-com.aspose.psd.xmp.types.derived.Rational-int-}
```
public Time(Rational scale, int value)
```


Time 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| scale | [Rational](../../com.aspose.psd.xmp.types.derived/rational) | 스케일. |
| 값 | int | 값. |

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
### getScale() {#getScale--}
```
public Rational getScale()
```


시간 값의 스케일을 가져오거나 설정합니다.

NTSC의 경우 1001/30000을 사용하거나 덜 정확한 100/2997을 사용합니다. PAL의 경우 1/25를 사용합니다. 값: 시간 값의 스케일.

**Returns:**
[Rational](../../com.aspose.psd.xmp.types.derived/rational)
### getValue() {#getValue--}
```
public int getValue()
```


지정된 스케일에서 시간 값을 가져오거나 설정합니다.

값: 지정된 스케일의 시간 값.

**Returns:**
int
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




### setScale(Rational value) {#setScale-com.aspose.psd.xmp.types.derived.Rational-}
```
public void setScale(Rational value)
```


시간 값의 스케일을 가져오거나 설정합니다.

NTSC의 경우 1001/30000을 사용하거나 덜 정확한 100/2997을 사용합니다. PAL의 경우 1/25를 사용합니다. 값: 시간 값의 스케일.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Rational](../../com.aspose.psd.xmp.types.derived/rational) |  |

### setValue(int value) {#setValue-int-}
```
public void setValue(int value)
```


지정된 스케일에서 시간 값을 가져오거나 설정합니다.

값: 지정된 스케일의 시간 값.

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

