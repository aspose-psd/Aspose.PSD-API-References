---
title: "Thumbnail4Resource"
second_title: "Java용 Aspose.PSD API 참조"
description: "psd 4.0용 썸네일 리소스를 나타냅니다."
type: docs
weight: 34
url: /ko/java/com.aspose.psd.fileformats.psd.resources/thumbnail4resource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.ResourceBlock](../../com.aspose.psd.fileformats.psd/resourceblock), [com.aspose.psd.fileformats.psd.resources.ThumbnailResource](../../com.aspose.psd.fileformats.psd.resources/thumbnailresource)
```
public final class Thumbnail4Resource extends ThumbnailResource
```

psd 4.0용 썸네일 리소스를 나타냅니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [Thumbnail4Resource()](#Thumbnail4Resource--) | [Thumbnail4Resource](../../com.aspose.psd.fileformats.psd.resources/thumbnail4resource) 클래스의 새 인스턴스를 초기화합니다. |
## 필드

| 필드 | 설명 |
| --- | --- |
| [ResouceBlockMeSaSignature](#ResouceBlockMeSaSignature) | ImageReady의 리소스 서명입니다. |
| [ResouceBlockSignature](#ResouceBlockSignature) | 일반 Photoshop 리소스 서명입니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBitsPixel()](#getBitsPixel--) | 비트 픽셀을 가져오거나 설정합니다. |
| [getClass()](#getClass--) |  |
| [getDataSize()](#getDataSize--) | 리소스 데이터 크기를 바이트 단위로 가져옵니다. |
| [getFormat()](#getFormat--) | 썸네일 데이터 형식을 가져오거나 설정합니다. |
| [getHeight()](#getHeight--) | 썸네일의 높이를 픽셀 단위로 가져오거나 설정합니다. |
| [getID()](#getID--) | 리소스의 고유 식별자를 가져오거나 설정합니다. |
| [getJpegOptions()](#getJpegOptions--) | JPEG 옵션을 가져오거나 설정합니다. |
| [getMinimalVersion()](#getMinimalVersion--) | 필요한 최소 psd 버전을 가져옵니다. |
| [getName()](#getName--) | 리소스 이름을 가져오거나 설정합니다. |
| [getPlanesCount()](#getPlanesCount--) | 플레인 수를 가져오거나 설정합니다. |
| [getSignature()](#getSignature--) | 리소스 시그니처를 가져옵니다. |
| [getSize()](#getSize--) | 데이터를 포함한 바이트 단위의 리소스 블록 크기를 가져옵니다. |
| [getSizeAfterCompression()](#getSizeAfterCompression--) | 압축 후 크기를 가져오거나 설정합니다. |
| [getThumbnailArgb32Data()](#getThumbnailArgb32Data--) | 32비트 ARGB 썸네일 데이터를 가져오거나 설정합니다. |
| [getThumbnailData()](#getThumbnailData--) | 썸네일 데이터를 가져오거나 설정합니다. |
| [getTotalSize()](#getTotalSize--) | 전체 데이터 크기를 가져옵니다. |
| [getWidth()](#getWidth--) | 썸네일의 너비를 픽셀 단위로 가져오거나 설정합니다. |
| [getWidthBytes()](#getWidthBytes--) | 행 너비를 바이트 단위로 가져옵니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer stream)](#save-com.aspose.psd.StreamContainer-) | 지정된 스트림에 리소스 블록을 저장합니다. |
| [setBitsPixel(short value)](#setBitsPixel-short-) | 비트 픽셀을 가져오거나 설정합니다. |
| [setFormat(int value)](#setFormat-int-) | 썸네일 데이터 형식을 가져오거나 설정합니다. |
| [setHeight(int value)](#setHeight-int-) | 썸네일의 높이를 픽셀 단위로 가져오거나 설정합니다. |
| [setID(short value)](#setID-short-) | 리소스의 고유 식별자를 가져오거나 설정합니다. |
| [setJpegOptions(JpegOptions value)](#setJpegOptions-com.aspose.psd.imageoptions.JpegOptions-) | JPEG 옵션을 가져오거나 설정합니다. |
| [setLayerAndMaskInfo_internalized(LayerAndMaskInfo value)](#setLayerAndMaskInfo-internalized-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-) | 레이어 및 마스크 정보를 가져오거나 설정합니다. |
| [setName(String value)](#setName-java.lang.String-) | 리소스 이름을 가져오거나 설정합니다. |
| [setPlanesCount(short value)](#setPlanesCount-short-) | 플레인 수를 가져오거나 설정합니다. |
| [setSignature_internalized(int signature)](#setSignature-internalized-int-) |  |
| [setState_internalized(int value)](#setState-internalized-int-) | 리소스 블록 상태를 가져오거나 설정합니다. |
| [setThumbnailArgb32Data(int[] value)](#setThumbnailArgb32Data-int---) | 32비트 ARGB 썸네일 데이터를 가져오거나 설정합니다. |
| [setThumbnailData(Color[] value)](#setThumbnailData-com.aspose.psd.Color---) | 썸네일 데이터를 가져오거나 설정합니다. |
| [setWidth(int value)](#setWidth-int-) | 썸네일의 너비를 픽셀 단위로 가져오거나 설정합니다. |
| [toString()](#toString--) |  |
| [validateValues()](#validateValues--) | 리소스 값을 검증합니다. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Thumbnail4Resource() {#Thumbnail4Resource--}
```
public Thumbnail4Resource()
```


[Thumbnail4Resource](../../com.aspose.psd.fileformats.psd.resources/thumbnail4resource) 클래스의 새 인스턴스를 초기화합니다.

### ResouceBlockMeSaSignature {#ResouceBlockMeSaSignature}
```
public static final int ResouceBlockMeSaSignature
```


ImageReady의 리소스 서명입니다.

### ResouceBlockSignature {#ResouceBlockSignature}
```
public static final int ResouceBlockSignature
```


일반 Photoshop 리소스 서명입니다.

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
### getBitsPixel() {#getBitsPixel--}
```
public final short getBitsPixel()
```


비트 픽셀을 가져오거나 설정합니다.

값: 썸네일 비트 픽셀.

**Returns:**
short
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDataSize() {#getDataSize--}
```
public int getDataSize()
```


리소스 데이터 크기를 바이트 단위로 가져옵니다.

값: 리소스 데이터 크기.

**Returns:**
int
### getFormat() {#getFormat--}
```
public final int getFormat()
```


썸네일 데이터 형식을 가져오거나 설정합니다.

값: 썸네일 데이터 형식.

**Returns:**
int
### getHeight() {#getHeight--}
```
public final int getHeight()
```


썸네일의 높이를 픽셀 단위로 가져오거나 설정합니다.

값: 썸네일 높이.

**Returns:**
int
### getID() {#getID--}
```
public final short getID()
```


리소스의 고유 식별자를 가져오거나 설정합니다.

값: 리소스의 고유 식별자.

**Returns:**
short
### getJpegOptions() {#getJpegOptions--}
```
public final JpegOptions getJpegOptions()
```


JPEG 옵션을 가져오거나 설정합니다. 썸네일 리소스가 JPEG 파일 형식으로만 저장될 때 적합합니다. RAW 형식이 정의된 경우 이 옵션은 영향을 주지 않습니다.

값: JPEG 옵션.

**Returns:**
[JpegOptions](../../com.aspose.psd.imageoptions/jpegoptions)
### getMinimalVersion() {#getMinimalVersion--}
```
public int getMinimalVersion()
```


필요한 최소 psd 버전을 가져옵니다.

값: 최소 psd 버전.

**Returns:**
int
### getName() {#getName--}
```
public final String getName()
```


리소스 이름을 가져오거나 설정합니다. 파스칼 문자열이며, 크기를 짝수로 맞추기 위해 패딩됩니다(널 이름은 0 두 바이트로 구성됩니다).

값: 리소스 이름.

**Returns:**
java.lang.String
### getPlanesCount() {#getPlanesCount--}
```
public final short getPlanesCount()
```


플레인 수를 가져오거나 설정합니다.

값: 썸네일 평면 수.

**Returns:**
short
### getSignature() {#getSignature--}
```
public final int getSignature()
```


리소스 시그니처를 가져옵니다. 항상 '8BIM'이어야 합니다.

값: 리소스 시그니처.

**Returns:**
int
### getSize() {#getSize--}
```
public final int getSize()
```


데이터를 포함한 바이트 단위의 리소스 블록 크기를 가져옵니다.

값: 리소스 블록 크기.

**Returns:**
int
### getSizeAfterCompression() {#getSizeAfterCompression--}
```
public final int getSizeAfterCompression()
```


압축 후 크기를 가져오거나 설정합니다. 일관성 검사를 위해 사용됩니다.

값: 압축 후 크기.

**Returns:**
int
### getThumbnailArgb32Data() {#getThumbnailArgb32Data--}
```
public final int[] getThumbnailArgb32Data()
```


32비트 ARGB 썸네일 데이터를 가져오거나 설정합니다.

값: 32비트 ARGB 썸네일 데이터.

**Returns:**
int[]
### getThumbnailData() {#getThumbnailData--}
```
public final Color[] getThumbnailData()
```


썸네일 데이터를 가져오거나 설정합니다.

값: 썸네일 데이터.

**Returns:**
com.aspose.psd.Color[]
### getTotalSize() {#getTotalSize--}
```
public final int getTotalSize()
```


전체 데이터 크기를 가져옵니다.

값: 전체 데이터 크기.

**Returns:**
int
### getWidth() {#getWidth--}
```
public final int getWidth()
```


썸네일의 너비를 픽셀 단위로 가져오거나 설정합니다.

값: 썸네일 너비.

**Returns:**
int
### getWidthBytes() {#getWidthBytes--}
```
public final int getWidthBytes()
```


행 너비를 바이트 단위로 가져옵니다.

값: 바이트 단위 행 너비.

**Returns:**
int
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




### save(StreamContainer stream) {#save-com.aspose.psd.StreamContainer-}
```
public final void save(StreamContainer stream)
```


지정된 스트림에 리소스 블록을 저장합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | [StreamContainer](../../com.aspose.psd/streamcontainer) | 리소스 블록을 저장할 스트림. |

### setBitsPixel(short value) {#setBitsPixel-short-}
```
public final void setBitsPixel(short value)
```


비트 픽셀을 가져오거나 설정합니다.

값: 썸네일 비트 픽셀.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | short |  |

### setFormat(int value) {#setFormat-int-}
```
public final void setFormat(int value)
```


썸네일 데이터 형식을 가져오거나 설정합니다.

값: 썸네일 데이터 형식.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


썸네일의 높이를 픽셀 단위로 가져오거나 설정합니다.

값: 썸네일 높이.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setID(short value) {#setID-short-}
```
public final void setID(short value)
```


리소스의 고유 식별자를 가져오거나 설정합니다.

값: 리소스의 고유 식별자.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | short |  |

### setJpegOptions(JpegOptions value) {#setJpegOptions-com.aspose.psd.imageoptions.JpegOptions-}
```
public final void setJpegOptions(JpegOptions value)
```


JPEG 옵션을 가져오거나 설정합니다. 썸네일 리소스가 JPEG 파일 형식으로만 저장될 때 적합합니다. RAW 형식이 정의된 경우 이 옵션은 영향을 주지 않습니다.

값: JPEG 옵션.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [JpegOptions](../../com.aspose.psd.imageoptions/jpegoptions) |  |

### setLayerAndMaskInfo_internalized(LayerAndMaskInfo value) {#setLayerAndMaskInfo-internalized-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-}
```
public final void setLayerAndMaskInfo_internalized(LayerAndMaskInfo value)
```


레이어 및 마스크 정보를 가져오거나 설정합니다.

값: 레이어 및 마스크 정보.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo |  |

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


리소스 이름을 가져오거나 설정합니다. 파스칼 문자열이며, 크기를 짝수로 맞추기 위해 패딩됩니다(널 이름은 0 두 바이트로 구성됩니다).

값: 리소스 이름.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setPlanesCount(short value) {#setPlanesCount-short-}
```
public final void setPlanesCount(short value)
```


플레인 수를 가져오거나 설정합니다.

값: 썸네일 평면 수.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | short |  |

### setSignature_internalized(int signature) {#setSignature-internalized-int-}
```
public void setSignature_internalized(int signature)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 시그니처 | int |  |

### setState_internalized(int value) {#setState-internalized-int-}
```
public final void setState_internalized(int value)
```


리소스 블록 상태를 가져오거나 설정합니다.

값: 리소스 블록 상태.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setThumbnailArgb32Data(int[] value) {#setThumbnailArgb32Data-int---}
```
public final void setThumbnailArgb32Data(int[] value)
```


32비트 ARGB 썸네일 데이터를 가져오거나 설정합니다.

값: 32비트 ARGB 썸네일 데이터.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int[] |  |

### setThumbnailData(Color[] value) {#setThumbnailData-com.aspose.psd.Color---}
```
public final void setThumbnailData(Color[] value)
```


썸네일 데이터를 가져오거나 설정합니다.

값: 썸네일 데이터.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Color\[\]](../../com.aspose.psd/color) |  |

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


썸네일의 너비를 픽셀 단위로 가져오거나 설정합니다.

값: 썸네일 너비.

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
### validateValues() {#validateValues--}
```
public void validateValues()
```


리소스 값을 검증합니다.

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

