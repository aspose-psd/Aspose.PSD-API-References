---
title: "TiffExifIfd"
second_title: "Java용 Aspose.PSD API 참조"
description: "TIFF Exif 이미지 파일 디렉터리 클래스."
type: docs
weight: 11
url: /ko/java/com.aspose.psd.fileformats.tiff/tiffexififd/
---

**Inheritance:**
java.lang.Object
```
public class TiffExifIfd
```

TIFF Exif 이미지 파일 디렉터리 클래스.

Exif IFD에 대한 포인터를 캡슐화합니다. Interoperability, Exif IFD는 TIFF에 지정된 IFD와 동일한 구조를 가집니다. 그러나 일반적으로 TIFF와 달리 이미지 데이터를 포함하지 않습니다. 자세한 내용은 http://www.exiv2.org/tags.html 및 http://www.awaresystems.be/imaging/tiff/tifftags/exififd.html을 참조하십시오.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [TiffExifIfd()](#TiffExifIfd--) | 새로운 TiffExifIfd 클래스의 인스턴스를 초기화합니다. |
| [TiffExifIfd(long ifdOffset)](#TiffExifIfd-long-) | 새로운 TiffExifIfd 클래스의 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getOffset()](#getOffset--) | EXIF IFD에 대한 포인터를 가져오거나 설정합니다. |
| [hasValue()](#hasValue--) | 이 인스턴스에 값이 있는지 여부를 나타내는 값을 가져옵니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setOffset(long value)](#setOffset-long-) | EXIF IFD에 대한 포인터를 가져오거나 설정합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TiffExifIfd() {#TiffExifIfd--}
```
public TiffExifIfd()
```


새로운 TiffExifIfd 클래스의 인스턴스를 초기화합니다.

### TiffExifIfd(long ifdOffset) {#TiffExifIfd-long-}
```
public TiffExifIfd(long ifdOffset)
```


새로운 TiffExifIfd 클래스의 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | ifdOffset | long | Exif IFD에 대한 포인터입니다. |

Interoperability, Exif IFD는 TIFF에 지정된 IFD와 동일한 구조를 가집니다. 그러나 일반적으로 TIFF와 달리 이미지 데이터를 포함하지 않습니다. |

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
### getOffset() {#getOffset--}
```
public long getOffset()
```


EXIF IFD에 대한 포인터를 가져오거나 설정합니다.

**Returns:**
long - EXIF IFD에 대한 포인터.
### hasValue() {#hasValue--}
```
public boolean hasValue()
```


이 인스턴스에 값이 있는지 여부를 나타내는 값을 가져옵니다.

**Returns:**
boolean - 이 인스턴스에 값이 있으면 true; 그렇지 않으면 false.
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




### setOffset(long value) {#setOffset-long-}
```
public void setOffset(long value)
```


EXIF IFD에 대한 포인터를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | long | EXIF IFD에 대한 포인터. |

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

