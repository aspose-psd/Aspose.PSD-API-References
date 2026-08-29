---
title: "XmpTrailerPi"
second_title: "Java용 Aspose.PSD API 참조"
description: "XMP 트레일러 처리 지시문을 나타냅니다."
type: docs
weight: 22
url: /ko/java/com.aspose.psd.xmp/xmptrailerpi/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.xmp.IXmlValue](../../com.aspose.psd.xmp/ixmlvalue), com.aspose.ms.System.IEquatable
```
public final class XmpTrailerPi implements IXmlValue, System.IEquatable<XmpTrailerPi>
```

XMP 트레일러 처리 지시문을 나타냅니다.

end="w" 또는 end="r" 부분은 패킷 스캔 프로세서에 의해 XMP를 제자리에서 수정할 수 있는지 여부를 판단하는 데 사용됩니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [XmpTrailerPi(boolean isWritable)](#XmpTrailerPi-boolean-) | XmpTrailerPi 클래스의 새 인스턴스를 초기화합니다. |
| [XmpTrailerPi()](#XmpTrailerPi--) | XmpTrailerPi 클래스의 새 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [deepClone_internalized()](#deepClone-internalized--) | 이 인스턴스를 복제합니다. |
| [equals(Object obj)](#equals-java.lang.Object-) | 지정된 System.Object가 이 인스턴스와 같은지 여부를 결정합니다. |
| [getClass()](#getClass--) |  |
| [getXmlValue()](#getXmlValue--) | xmp 값을 XML 표현으로 변환합니다. |
| [hashCode()](#hashCode--) | 이 인스턴스에 대한 해시 코드를 반환합니다. |
| [isEquals(XmpTrailerPi other)](#isEquals-com.aspose.psd.xmp.XmpTrailerPi-) | 현재 객체가 동일한 유형의 다른 객체와 같은지 여부를 나타냅니다. |
| [isWritable()](#isWritable--) | 이 인스턴스가 쓰기 가능한지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setWritable(boolean value)](#setWritable-boolean-) | 이 인스턴스가 쓰기 가능한지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpTrailerPi(boolean isWritable) {#XmpTrailerPi-boolean-}
```
public XmpTrailerPi(boolean isWritable)
```


XmpTrailerPi 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| isWritable | boolean | 트레일러가 쓰기 가능한지 여부를 나타냅니다. |

### XmpTrailerPi() {#XmpTrailerPi--}
```
public XmpTrailerPi()
```


XmpTrailerPi 클래스의 새 인스턴스를 초기화합니다.

### deepClone_internalized() {#deepClone-internalized--}
```
public final XmpTrailerPi deepClone_internalized()
```


이 인스턴스를 복제합니다.

**Returns:**
[XmpTrailerPi](../../com.aspose.psd.xmp/xmptrailerpi) - The cloned object
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
### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


xmp 값을 XML 표현으로 변환합니다.

**Returns:**
java.lang.String - XMP의 XML 표현을 반환합니다.
### hashCode() {#hashCode--}
```
public int hashCode()
```


이 인스턴스에 대한 해시 코드를 반환합니다.

**Returns:**
int - 이 인스턴스에 대한 해시 코드이며, 해시 알고리즘 및 해시 테이블과 같은 데이터 구조에 사용하기에 적합합니다.
### isEquals(XmpTrailerPi other) {#isEquals-com.aspose.psd.xmp.XmpTrailerPi-}
```
public boolean isEquals(XmpTrailerPi other)
```


현재 객체가 동일한 유형의 다른 객체와 같은지 여부를 나타냅니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| other | [XmpTrailerPi](../../com.aspose.psd.xmp/xmptrailerpi) | 이 객체와 비교할 객체. |

**Returns:**
boolean - 현재 객체가 other 매개변수와 같으면 true; 그렇지 않으면 false.
### isWritable() {#isWritable--}
```
public boolean isWritable()
```


이 인스턴스가 쓰기 가능한지 여부를 나타내는 값을 가져오거나 설정합니다.

값: 이 인스턴스가 쓰기 가능한 경우 true; 그렇지 않으면 false.

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




### setWritable(boolean value) {#setWritable-boolean-}
```
public void setWritable(boolean value)
```


이 인스턴스가 쓰기 가능한지 여부를 나타내는 값을 가져오거나 설정합니다.

값: 이 인스턴스가 쓰기 가능한 경우 true; 그렇지 않으면 false.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

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

