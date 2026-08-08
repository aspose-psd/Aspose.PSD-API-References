---
title: "TiffDataType"
second_title: "Java용 Aspose.PSD API 참조"
description: "tiff 데이터 유형."
type: docs
weight: 10
url: /ko/java/com.aspose.psd.fileformats.tiff/tiffdatatype/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Comparable
```
public abstract class TiffDataType implements Comparable<TiffDataType>
```

tiff 데이터 유형.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [compareTo(TiffDataType obj)](#compareTo-com.aspose.psd.fileformats.tiff.TiffDataType-) | 현재 인스턴스를 동일한 유형의 다른 객체와 비교하고, 현재 인스턴스가 정렬 순서에서 다른 객체보다 앞선, 뒤에 있거나 같은 위치에 있는지를 나타내는 정수를 반환합니다. |
| [deepClone()](#deepClone--) | 이 인스턴스의 깊은 복제를 수행합니다. |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [getAlignedDataSize()](#getAlignedDataSize--) | 태그 데이터를 저장하기에 12바이트가 충분하지 않은 경우를 대비하여 추가 데이터 크기(바이트)를 가져옵니다. |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | 요소의 개수를 가져옵니다. |
| [getDataSize()](#getDataSize--) | 태그 데이터를 저장하기에 12바이트가 충분하지 않은 경우를 대비하여 추가 데이터 크기(바이트)를 가져옵니다. |
| [getId()](#getId--) | 태그 ID의 정수 표현을 가져옵니다. |
| [getTagId()](#getTagId--) | 태그 ID를 가져옵니다. |
| [getTagType()](#getTagType--) | 태그 유형을 가져옵니다. |
| [getValue()](#getValue--) | 이 데이터 형식이 포함하는 값을 가져옵니다. |
| [hashCode()](#hashCode--) |  |
| [isPrivate_internalized()](#isPrivate-internalized--) | 태그가 비공개인지 여부를 나타내는 값을 가져옵니다. |
| [isValid()](#isValid--) | 태그 데이터가 유효한지 여부를 나타내는 값을 가져옵니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [readTag(TiffStreamReader dataStream, long position)](#readTag-com.aspose.psd.fileformats.tiff.filemanagement.TiffStreamReader-long-) | 태그 데이터를 읽습니다. |
| [setValue(Object value)](#setValue-java.lang.Object-) | 이 데이터 형식이 포함하는 값을 설정합니다. |
| [toString()](#toString--) | 이 인스턴스를 나타내는  System.String  을 반환합니다. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.psd.fileformats.tiff.filemanagement.TiffStreamWriter-) | 추가 태그 데이터를 씁니다. |
| [writeTag(TiffStreamWriter dataStream, long additionalDataOffset)](#writeTag-com.aspose.psd.fileformats.tiff.filemanagement.TiffStreamWriter-long-) | 태그 데이터를 씁니다. |
### compareTo(TiffDataType obj) {#compareTo-com.aspose.psd.fileformats.tiff.TiffDataType-}
```
public int compareTo(TiffDataType obj)
```


현재 인스턴스를 동일한 유형의 다른 객체와 비교하고, 현재 인스턴스가 정렬 순서에서 다른 객체보다 앞선, 뒤에 있거나 같은 위치에 있는지를 나타내는 정수를 반환합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | [TiffDataType](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | 이 인스턴스와 비교할 객체입니다. |

**Returns:**
int - 비교되는 객체들의 상대 순서를 나타내는 32비트 부호 있는 정수입니다. 반환 값은 다음과 같은 의미를 가집니다: 값 의미 0보다 작음 이 인스턴스는 obj보다 작습니다. 0 이 인스턴스는 obj와 같습니다. 0보다 큼 이 인스턴스는 obj보다 큽니다.
### deepClone() {#deepClone--}
```
public TiffDataType deepClone()
```


이 인스턴스의 깊은 복제를 수행합니다.

**Returns:**
[TiffDataType](../../com.aspose.psd.fileformats.tiff/tiffdatatype) - A deep clone of the current instance.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### getAlignedDataSize() {#getAlignedDataSize--}
```
public long getAlignedDataSize()
```


태그 데이터를 저장하기에 12바이트가 충분하지 않은 경우를 대비하여 추가 데이터 크기(바이트)를 가져옵니다.

**Returns:**
long - 추가 데이터 크기(바이트)입니다.

이는 워드 경계에 맞춰 정렬된 데이터 바이트 수입니다.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCount() {#getCount--}
```
public abstract long getCount()
```


요소의 개수를 가져옵니다.

**Returns:**
long - 요소 개수입니다.
### getDataSize() {#getDataSize--}
```
public abstract long getDataSize()
```


태그 데이터를 저장하기에 12바이트가 충분하지 않은 경우를 대비하여 추가 데이터 크기(바이트)를 가져옵니다.

**Returns:**
long - 추가 데이터 크기(바이트)입니다.

이는 정확한 바이트 수입니다.
### getId() {#getId--}
```
public int getId()
```


태그 ID의 정수 표현을 가져옵니다.

**Returns:**
int - 태그 ID 정수 표현입니다
### getTagId() {#getTagId--}
```
public int getTagId()
```


태그 ID를 가져옵니다.

**Returns:**
int - 태그 ID입니다.
### getTagType() {#getTagType--}
```
public abstract int getTagType()
```


태그 유형을 가져옵니다.

**Returns:**
int - 태그 유형입니다.
### getValue() {#getValue--}
```
public abstract Object getValue()
```


이 데이터 형식이 포함하는 값을 가져옵니다.

**Returns:**
java.lang.Object - 값입니다.
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### isPrivate_internalized() {#isPrivate-internalized--}
```
public boolean isPrivate_internalized()
```


태그가 비공개인지 여부를 나타내는 값을 가져옵니다. 비공개 TIFF 태그는 태그 ID가 32768보다 큰 태그입니다.

**Returns:**
boolean -  true  if tag data is valid; otherwise,  false .
### isValid() {#isValid--}
```
public boolean isValid()
```


태그 데이터가 유효한지 여부를 나타내는 값을 가져옵니다. 유효한 태그는 보존될 수 있는 데이터를 포함합니다. 무효한 태그는 저장할 수 없습니다.

**Returns:**
boolean -  true  if tag data is valid; otherwise,  false .
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### readTag(TiffStreamReader dataStream, long position) {#readTag-com.aspose.psd.fileformats.tiff.filemanagement.TiffStreamReader-long-}
```
public static TiffDataType readTag(TiffStreamReader dataStream, long position)
```


태그 데이터를 읽습니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| dataStream | [TiffStreamReader](../../com.aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader) | 데이터 스트림. |
| position | long | 태그 위치입니다. |

**Returns:**
[TiffDataType](../../com.aspose.psd.fileformats.tiff/tiffdatatype) - The read tag.
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```


이 데이터 형식이 포함하는 값을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.Object | 값. |

### toString() {#toString--}
```
public String toString()
```


이 인스턴스를 나타내는  System.String  을 반환합니다.

**Returns:**
java.lang.String - 이 인스턴스를 나타내는 System.String.
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

### writeAdditionalData(TiffStreamWriter dataStream) {#writeAdditionalData-com.aspose.psd.fileformats.tiff.filemanagement.TiffStreamWriter-}
```
public abstract long writeAdditionalData(TiffStreamWriter dataStream)
```


추가 태그 데이터를 씁니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| dataStream | [TiffStreamWriter](../../com.aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter) | 데이터 스트림. |

**Returns:**
long - 실제로 기록된 바이트 수입니다.
### writeTag(TiffStreamWriter dataStream, long additionalDataOffset) {#writeTag-com.aspose.psd.fileformats.tiff.filemanagement.TiffStreamWriter-long-}
```
public void writeTag(TiffStreamWriter dataStream, long additionalDataOffset)
```


태그 데이터를 씁니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| dataStream | [TiffStreamWriter](../../com.aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter) | 데이터 스트림. |
| additionalDataOffset | long | 추가 데이터를 기록할 오프셋입니다. |

