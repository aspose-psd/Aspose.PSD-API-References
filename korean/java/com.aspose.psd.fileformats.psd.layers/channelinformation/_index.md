---
title: "채널 정보"
second_title: "Java용 Aspose.PSD API 참조"
description: "채널 정보."
type: docs
weight: 13
url: /ko/java/com.aspose.psd.fileformats.psd.layers/channelinformation/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Cloneable
```
public class ChannelInformation implements Cloneable
```

채널 정보.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [ChannelInformation(short compressionMethod, int bitDepth, int psdVersion)](#ChannelInformation-short-int-int-) |  |
## 필드

| 필드 | 설명 |
| --- | --- |
| [FullMaskChannelId_internalized](#FullMaskChannelId-internalized) | 사용자 (래스터) 마스크 채널 ID |
| [ShortMaskChannelId_internalized](#ShortMaskChannelId-internalized) | 짧은 (래스터 또는 벡터) 마스크 채널 ID |
| [TransparencyMaskChannelId_internalized](#TransparencyMaskChannelId-internalized) | 알파 채널 ID |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [compressChannel_internalized(byte[] rawData, Rectangle layerBounds, Rectangle layerMaskBounds)](#compressChannel-internalized-byte---com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-) | 채널 데이터를 압축합니다. |
| [create_internalized(byte[] compressedData, short compressionMethod, int width, int height, PsdHeader header)](#create-internalized-byte---short-int-int-com.aspose.internal.fileformats.psd.sections.PsdHeader-) |  |
| [create_internalized(short compressionMethod, PsdHeader header)](#create-internalized-short-com.aspose.internal.fileformats.psd.sections.PsdHeader-) |  |
| [deepClone_internalized(ChannelInformation[] info)](#deepClone-internalized-com.aspose.psd.fileformats.psd.layers.ChannelInformation---) | 지정된 채널 정보를 복제합니다. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBitDepth_internalized()](#getBitDepth-internalized--) | 채널 비트 깊이를 가져옵니다. |
| [getChannelID()](#getChannelID--) | 채널 ID를 가져오거나 설정합니다. |
| [getClass()](#getClass--) |  |
| [getCompressionMethod()](#getCompressionMethod--) | 압축 방법을 가져오거나 설정합니다. |
| [getData_internalized()](#getData-internalized--) | 채널 데이터를 가져오거나 설정합니다. |
| [getLength()](#getLength--) | 채널 길이를 바이트 단위로 가져옵니다. |
| [getPsdHeaderVersion_internalized()](#getPsdHeaderVersion-internalized--) | PSD 버전을 가져옵니다. |
| [getUncompressedData_internalized()](#getUncompressedData-internalized--) | 압축되지 않은 데이터를 가져옵니다. |
| [hashCode()](#hashCode--) |  |
| [isShortMaskChannel_internalized()](#isShortMaskChannel-internalized--) | 채널이 ShortMask인지 여부를 가져옵니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [saveChannelData_internalized(StreamContainer streamContainer)](#saveChannelData-internalized-com.aspose.psd.StreamContainer-) |  |
| [saveChannelData_internalized(StreamContainer streamContainer, boolean is32BitColor)](#saveChannelData-internalized-com.aspose.psd.StreamContainer-boolean-) | 채널 데이터를 저장합니다. |
| [setChannelID(short value)](#setChannelID-short-) | 채널 ID를 가져오거나 설정합니다. |
| [setCompressedData_internalized(byte[] compressedData, int channelWidth, int channelHeight)](#setCompressedData-internalized-byte---int-int-) | 압축된 데이터를 설정합니다. |
| [setCompressionMethod(short value)](#setCompressionMethod-short-) | 압축 방법을 가져오거나 설정합니다. |
| [setRawData_internalized(byte[] rawData, Size imageSize, Rectangle currentBounds)](#setRawData-internalized-byte---com.aspose.psd.Size-com.aspose.psd.Rectangle-) | 압축된 데이터를 설정합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ChannelInformation(short compressionMethod, int bitDepth, int psdVersion) {#ChannelInformation-short-int-int-}
```
public ChannelInformation(short compressionMethod, int bitDepth, int psdVersion)
```


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| compressionMethod | short |  |
| bitDepth | int |  |
| psdVersion | int |  |

### FullMaskChannelId_internalized {#FullMaskChannelId-internalized}
```
public static final int FullMaskChannelId_internalized
```


사용자 (래스터) 마스크 채널 ID. (레이어에 벡터와 래스터 마스크가 모두 있는 경우).

### ShortMaskChannelId_internalized {#ShortMaskChannelId-internalized}
```
public static final int ShortMaskChannelId_internalized
```


짧은 (래스터 또는 벡터) 마스크 채널 ID. (레이어에 벡터 또는 래스터 마스크 중 하나만 있는 경우).

### TransparencyMaskChannelId_internalized {#TransparencyMaskChannelId-internalized}
```
public static final int TransparencyMaskChannelId_internalized
```


알파 채널 ID

### compressChannel_internalized(byte[] rawData, Rectangle layerBounds, Rectangle layerMaskBounds) {#compressChannel-internalized-byte---com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-}
```
public final void compressChannel_internalized(byte[] rawData, Rectangle layerBounds, Rectangle layerMaskBounds)
```


채널 데이터를 압축합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rawData | byte[] | 압축을 위한 원시 데이터 |
| layerBounds | [Rectangle](../../com.aspose.psd/rectangle) | 레이어의 경계 |
| layerMaskBounds | [Rectangle](../../com.aspose.psd/rectangle) | 레이어 마스크의 경계 |

### create_internalized(byte[] compressedData, short compressionMethod, int width, int height, PsdHeader header) {#create-internalized-byte---short-int-int-com.aspose.internal.fileformats.psd.sections.PsdHeader-}
```
public static ChannelInformation create_internalized(byte[] compressedData, short compressionMethod, int width, int height, PsdHeader header)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| compressedData | byte[] |  |
| compressionMethod | short |  |
| 너비 | int |  |
| 높이 | int |  |
| header | com.aspose.internal.fileformats.psd.sections.PsdHeader |  |

**Returns:**
[ChannelInformation](../../com.aspose.psd.fileformats.psd.layers/channelinformation)
### create_internalized(short compressionMethod, PsdHeader header) {#create-internalized-short-com.aspose.internal.fileformats.psd.sections.PsdHeader-}
```
public static ChannelInformation create_internalized(short compressionMethod, PsdHeader header)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| compressionMethod | short |  |
| header | com.aspose.internal.fileformats.psd.sections.PsdHeader |  |

**Returns:**
[ChannelInformation](../../com.aspose.psd.fileformats.psd.layers/channelinformation)
### deepClone_internalized(ChannelInformation[] info) {#deepClone-internalized-com.aspose.psd.fileformats.psd.layers.ChannelInformation---}
```
public static ChannelInformation[] deepClone_internalized(ChannelInformation[] info)
```


지정된 채널 정보를 복제합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| info | [ChannelInformation\[\]](../../com.aspose.psd.fileformats.psd.layers/channelinformation) | 정보. |

**Returns:**
com.aspose.psd.fileformats.psd.layers.ChannelInformation[] - 복제된 레이어 마스크.
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
### getBitDepth_internalized() {#getBitDepth-internalized--}
```
public final int getBitDepth_internalized()
```


채널 비트 깊이를 가져옵니다.

**Returns:**
int
### getChannelID() {#getChannelID--}
```
public final short getChannelID()
```


채널 ID를 가져오거나 설정합니다.

값: 채널 ID.

**Returns:**
short
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCompressionMethod() {#getCompressionMethod--}
```
public final short getCompressionMethod()
```


압축 방법을 가져오거나 설정합니다.

값: 압축 방법.

**Returns:**
short
### getData_internalized() {#getData-internalized--}
```
public final byte[] getData_internalized()
```


채널 데이터를 가져오거나 설정합니다.

값: 채널 데이터.

**Returns:**
byte[]
### getLength() {#getLength--}
```
public final long getLength()
```


채널 길이를 바이트 단위로 가져옵니다.

값: 길이.

**Returns:**
long
### getPsdHeaderVersion_internalized() {#getPsdHeaderVersion-internalized--}
```
public final int getPsdHeaderVersion_internalized()
```


PSD 버전을 가져옵니다.

**Returns:**
int
### getUncompressedData_internalized() {#getUncompressedData-internalized--}
```
public final byte[] getUncompressedData_internalized()
```


압축되지 않은 데이터를 가져옵니다.

**Returns:**
byte[] -
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isShortMaskChannel_internalized() {#isShortMaskChannel-internalized--}
```
public final boolean isShortMaskChannel_internalized()
```


채널이 ShortMask인지 여부를 가져옵니다.

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




### saveChannelData_internalized(StreamContainer streamContainer) {#saveChannelData-internalized-com.aspose.psd.StreamContainer-}
```
public final void saveChannelData_internalized(StreamContainer streamContainer)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) |  |

### saveChannelData_internalized(StreamContainer streamContainer, boolean is32BitColor) {#saveChannelData-internalized-com.aspose.psd.StreamContainer-boolean-}
```
public final void saveChannelData_internalized(StreamContainer streamContainer, boolean is32BitColor)
```


채널 데이터를 저장합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | 저장할 스트림 컨테이너. |
| is32BitColor | boolean | 색상이 32비트 모드인 경우 true |

### setChannelID(short value) {#setChannelID-short-}
```
public final void setChannelID(short value)
```


채널 ID를 가져오거나 설정합니다.

값: 채널 ID.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | short |  |

### setCompressedData_internalized(byte[] compressedData, int channelWidth, int channelHeight) {#setCompressedData-internalized-byte---int-int-}
```
public final void setCompressedData_internalized(byte[] compressedData, int channelWidth, int channelHeight)
```


압축된 데이터를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| compressedData | byte[] | 압축된 데이터. |
| channelWidth | int | 채널의 너비. |
| channelHeight | int | 채널의 높이. |

### setCompressionMethod(short value) {#setCompressionMethod-short-}
```
public final void setCompressionMethod(short value)
```


압축 방법을 가져오거나 설정합니다.

값: 압축 방법.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | short |  |

### setRawData_internalized(byte[] rawData, Size imageSize, Rectangle currentBounds) {#setRawData-internalized-byte---com.aspose.psd.Size-com.aspose.psd.Rectangle-}
```
public final void setRawData_internalized(byte[] rawData, Size imageSize, Rectangle currentBounds)
```


압축된 데이터를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rawData | byte[] | 원시 데이터. |
| imageSize | [Size](../../com.aspose.psd/size) | 이미지 크기 |
| currentBounds | [Rectangle](../../com.aspose.psd/rectangle) | 현재 channelData의 경계. 이미지가 큰 경우 처리 과정에서 분할되며 currentBounds는 imageBounds와 다릅니다. |

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

