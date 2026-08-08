---
title: "PattResourceData"
second_title: "Java용 Aspose.PSD API 참조"
description: "패턴 데이터를 저장하기 위한 클래스입니다."
type: docs
weight: 67
url: /ko/java/com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata/
---

**Inheritance:**
java.lang.Object
```
public final class PattResourceData
```

패턴 데이터를 저장하기 위한 클래스입니다. [PattResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresource) 리소스.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [PattResourceData()](#PattResourceData--) | 새로운 [PattResourceData](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata) 클래스 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [createNewInstance_internalized()](#createNewInstance-internalized--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getChannelsCompressionMode_internalized()](#getChannelsCompressionMode-internalized--) | 패턴\u2019s 채널에서 얻은 압축 방법 코드를 반환합니다. |
| [getClass()](#getClass--) |  |
| [getDefaultPattern_internalized()](#getDefaultPattern-internalized--) | 기본 패턴 데이터를 생성합니다. |
| [getHeight()](#getHeight--) | 높이를 가져옵니다. |
| [getImageMode()](#getImageMode--) | 이미지 모드를 가져옵니다. |
| [getLength()](#getLength--) | 패턴의 길이를 가져옵니다. |
| [getName()](#getName--) | 이름을 가져오거나 설정합니다. |
| [getPatternData()](#getPatternData--) | 패턴 데이터를 가져옵니다. |
| [getPatternDataArrayList_internalized()](#getPatternDataArrayList-internalized--) | 메모리 배열 리스트입니다. |
| [getPatternId()](#getPatternId--) | 패턴 식별자를 가져오거나 설정합니다. |
| [getVersion()](#getVersion--) | 버전을 가져옵니다. |
| [getWidth()](#getWidth--) | 너비를 가져옵니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer)](#save-com.aspose.psd.StreamContainer-) | 패턴 데이터를 저장합니다. |
| [setHeight_internalized(short value)](#setHeight-internalized-short-) | 높이를 가져옵니다. |
| [setImageMode_internalized(short value)](#setImageMode-internalized-short-) | 이미지 모드를 가져옵니다. |
| [setIndexColorTable_internalized(byte[] value)](#setIndexColorTable-internalized-byte---) | 인덱스 색상 테이블을 가져오거나 설정합니다. |
| [setName(String value)](#setName-java.lang.String-) | 이름을 가져오거나 설정합니다. |
| [setPattern(int[] pixels, Rectangle bounds)](#setPattern-int---com.aspose.psd.Rectangle-) | 패턴 픽셀 버퍼와 목표 크기를 설정하고, Width ([.getWidth](../../null/\#getWidth)/[.setWidth(short)](../../null/\#setWidth-short-)) / Height ([.getHeight](../../null/\#getHeight)/[.setHeight(short)](../../null/\#setHeight-short-))를 업데이트하며, 기본 압축 모드(0)를 사용하여 저장을 위한 데이터를 저장합니다. |
| [setPatternDataArrayList_internalized(VirtualMemoryArrayList value)](#setPatternDataArrayList-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.VirtualMemoryArrayList-) | 메모리 배열 리스트입니다. |
| [setPatternId(String value)](#setPatternId-java.lang.String-) | 패턴 식별자를 가져오거나 설정합니다. |
| [setPattern_internalized(int[] pixels, Rectangle bounds, byte compressionMode)](#setPattern-internalized-int---com.aspose.psd.Rectangle-byte-) | 패턴 픽셀 버퍼와 목표 크기를 설정하고, Width ([.getWidth](../../null/\#getWidth)/[.setWidth(short)](../../null/\#setWidth-short-)) / Height ([.getHeight](../../null/\#getHeight)/[.setHeight(short)](../../null/\#setHeight-short-))를 업데이트하며, 지정된 압축 모드를 사용하여 저장을 위한 데이터를 저장합니다. |
| [setVersion_internalized(int value)](#setVersion-internalized-int-) | 버전을 가져옵니다. |
| [setWidth_internalized(short value)](#setWidth-internalized-short-) | 너비를 가져옵니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PattResourceData() {#PattResourceData--}
```
public PattResourceData()
```


새로운 [PattResourceData](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata) 클래스 인스턴스를 초기화합니다.

### createNewInstance_internalized() {#createNewInstance-internalized--}
```
public static PattResourceData createNewInstance_internalized()
```




**Returns:**
[PattResourceData](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata)
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
### getChannelsCompressionMode_internalized() {#getChannelsCompressionMode-internalized--}
```
public final byte getChannelsCompressionMode_internalized()
```


패턴\u2019s 채널에서 얻은 압축 방법 코드를 반환합니다.

**Returns:**
byte - 압축 코드: 0 \\u2014 원시/압축되지 않음; >= 1 \\u2014 zip.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDefaultPattern_internalized() {#getDefaultPattern-internalized--}
```
public static PixelsData getDefaultPattern_internalized()
```


기본 패턴 데이터를 생성합니다.

**Returns:**
[PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata) - The default pattern data.
### getHeight() {#getHeight--}
```
public final short getHeight()
```


높이를 가져옵니다.

값: 높이.

**Returns:**
short
### getImageMode() {#getImageMode--}
```
public final short getImageMode()
```


이미지 모드를 가져옵니다.

Value: 이미지 모드.

**Returns:**
short
### getLength() {#getLength--}
```
public final int getLength()
```


패턴의 길이를 가져옵니다.

Value: 패턴의 길이.

**Returns:**
int
### getName() {#getName--}
```
public final String getName()
```


이름을 가져오거나 설정합니다.

Value: 이름.

**Returns:**
java.lang.String
### getPatternData() {#getPatternData--}
```
public final int[] getPatternData()
```


패턴 데이터를 가져옵니다.

값: 패턴 데이터.

**Returns:**
int[]
### getPatternDataArrayList_internalized() {#getPatternDataArrayList-internalized--}
```
public final VirtualMemoryArrayList getPatternDataArrayList_internalized()
```


메모리 배열 리스트입니다.

**Returns:**
com.aspose.internal.fileformats.psd.layers.layerresources.VirtualMemoryArrayList
### getPatternId() {#getPatternId--}
```
public final String getPatternId()
```


패턴 식별자를 가져오거나 설정합니다.

값: 패턴 식별자.

**Returns:**
java.lang.String
### getVersion() {#getVersion--}
```
public final int getVersion()
```


버전을 가져옵니다.

값: 버전.

**Returns:**
int
### getWidth() {#getWidth--}
```
public final short getWidth()
```


너비를 가져옵니다.

값: 너비.

**Returns:**
short
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




### save(StreamContainer streamContainer) {#save-com.aspose.psd.StreamContainer-}
```
public final void save(StreamContainer streamContainer)
```


패턴 데이터를 저장합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | 저장할 스트림 컨테이너. |

### setHeight_internalized(short value) {#setHeight-internalized-short-}
```
public final void setHeight_internalized(short value)
```


높이를 가져옵니다.

값: 높이.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | short |  |

### setImageMode_internalized(short value) {#setImageMode-internalized-short-}
```
public final void setImageMode_internalized(short value)
```


이미지 모드를 가져옵니다.

Value: 이미지 모드.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | short |  |

### setIndexColorTable_internalized(byte[] value) {#setIndexColorTable-internalized-byte---}
```
public final void setIndexColorTable_internalized(byte[] value)
```


인덱스 색상 테이블을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | byte[] |  |

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


이름을 가져오거나 설정합니다.

Value: 이름.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setPattern(int[] pixels, Rectangle bounds) {#setPattern-int---com.aspose.psd.Rectangle-}
```
public final void setPattern(int[] pixels, Rectangle bounds)
```


패턴 픽셀 버퍼와 목표 크기를 설정하고, Width ([.getWidth](../../null/\#getWidth)/[.setWidth(short)](../../null/\#setWidth-short-)) / Height ([.getHeight](../../null/\#getHeight)/[.setHeight(short)](../../null/\#setHeight-short-))를 업데이트하며, 기본 압축 모드(0)를 사용하여 저장을 위한 데이터를 저장합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 픽셀 | int[] | 0xAARRGGBB 형식의 32비트 픽셀. |
| bounds | [Rectangle](../../com.aspose.psd/rectangle) | 패턴의 픽셀 경계. |

### setPatternDataArrayList_internalized(VirtualMemoryArrayList value) {#setPatternDataArrayList-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.VirtualMemoryArrayList-}
```
public final void setPatternDataArrayList_internalized(VirtualMemoryArrayList value)
```


메모리 배열 리스트입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | com.aspose.internal.fileformats.psd.layers.layerresources.VirtualMemoryArrayList |  |

### setPatternId(String value) {#setPatternId-java.lang.String-}
```
public final void setPatternId(String value)
```


패턴 식별자를 가져오거나 설정합니다.

값: 패턴 식별자.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setPattern_internalized(int[] pixels, Rectangle bounds, byte compressionMode) {#setPattern-internalized-int---com.aspose.psd.Rectangle-byte-}
```
public final void setPattern_internalized(int[] pixels, Rectangle bounds, byte compressionMode)
```


패턴 픽셀 버퍼와 목표 크기를 설정하고, Width ([.getWidth](../../null/\#getWidth)/[.setWidth(short)](../../null/\#setWidth-short-)) / Height ([.getHeight](../../null/\#getHeight)/[.setHeight(short)](../../null/\#setHeight-short-))를 업데이트하며, 지정된 압축 모드를 사용하여 저장을 위한 데이터를 저장합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 픽셀 | int[] | 0xAARRGGBB 형식의 32비트 픽셀. |
| bounds | [Rectangle](../../com.aspose.psd/rectangle) | 패턴의 픽셀 경계. |
| compressionMode | byte | psd 파일 저장 시 패턴 데이터 압축을 정의하는 데 사용되는 압축 모드. |

### setVersion_internalized(int value) {#setVersion-internalized-int-}
```
public final void setVersion_internalized(int value)
```


버전을 가져옵니다.

값: 버전.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setWidth_internalized(short value) {#setWidth-internalized-short-}
```
public final void setWidth_internalized(short value)
```


너비를 가져옵니다.

값: 너비.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | short |  |

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

