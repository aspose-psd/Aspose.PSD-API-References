---
title: "FilterEffectMaskData"
second_title: "Java용 Aspose.PSD API 참조"
description: "필터 마스크 데이터 클래스."
type: docs
weight: 31
url: /ko/java/com.aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/
---

**Inheritance:**
java.lang.Object
```
public final class FilterEffectMaskData
```

필터 마스크 데이터 클래스.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [FilterEffectMaskData(String guid, Rectangle rectangle, int pixelsDepth, int maxChannels, ChannelInformation[] channels, ChannelInformation userMask, Rectangle maskRectangle, ChannelInformation sheetMask)](#FilterEffectMaskData-java.lang.String-com.aspose.psd.Rectangle-int-int-com.aspose.psd.fileformats.psd.layers.ChannelInformation---com.aspose.psd.fileformats.psd.layers.ChannelInformation-com.aspose.psd.Rectangle-com.aspose.psd.fileformats.psd.layers.ChannelInformation-) | 새 인스턴스를 초기화합니다. [FilterEffectMaskData](../../com.aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata) 클래스. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getChannels()](#getChannels--) | 채널을 가져옵니다. |
| [getClass()](#getClass--) |  |
| [getGUID()](#getGUID--) | GUID를 가져옵니다. |
| [getLength()](#getLength--) | 필터 마스크 데이터 길이를 바이트 단위로 가져옵니다. |
| [getMaskRectangle()](#getMaskRectangle--) | 시트 마스크 사각형을 가져옵니다. |
| [getMaxChannels()](#getMaxChannels--) | 채널 수의 최대값을 가져옵니다. |
| [getPixelsDepth()](#getPixelsDepth--) | 픽셀 깊이를 가져옵니다. |
| [getRectangle()](#getRectangle--) | 채널 사각형을 가져옵니다. |
| [getSheetMask()](#getSheetMask--) | 시트 마스크를 가져옵니다. |
| [getUserMask()](#getUserMask--) | 사용자 마스크를 가져옵니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [saveData(StreamContainer streamContainer)](#saveData-com.aspose.psd.StreamContainer-) | 지정된 스트림 컨테이너에 리소스를 저장합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FilterEffectMaskData(String guid, Rectangle rectangle, int pixelsDepth, int maxChannels, ChannelInformation[] channels, ChannelInformation userMask, Rectangle maskRectangle, ChannelInformation sheetMask) {#FilterEffectMaskData-java.lang.String-com.aspose.psd.Rectangle-int-int-com.aspose.psd.fileformats.psd.layers.ChannelInformation---com.aspose.psd.fileformats.psd.layers.ChannelInformation-com.aspose.psd.Rectangle-com.aspose.psd.fileformats.psd.layers.ChannelInformation-}
```
public FilterEffectMaskData(String guid, Rectangle rectangle, int pixelsDepth, int maxChannels, ChannelInformation[] channels, ChannelInformation userMask, Rectangle maskRectangle, ChannelInformation sheetMask)
```


새 인스턴스를 초기화합니다. [FilterEffectMaskData](../../com.aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata) 클래스.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| guid | java.lang.String | 리소스 GUID. |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | 채널 사각형. |
| pixelsDepth | int | 픽셀 깊이. |
| maxChannels | int | 최대 채널 값. |
| channels | [ChannelInformation\[\]](../../com.aspose.psd.fileformats.psd.layers/channelinformation) | 채널. |
| userMask | [ChannelInformation](../../com.aspose.psd.fileformats.psd.layers/channelinformation) | 사용자 마스크. |
| maskRectangle | [Rectangle](../../com.aspose.psd/rectangle) | 시트 마스크 사각형. |
| sheetMask | [ChannelInformation](../../com.aspose.psd.fileformats.psd.layers/channelinformation) | 시트 마스크. |

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
### getChannels() {#getChannels--}
```
public final ChannelInformation[] getChannels()
```


채널을 가져옵니다.

**Returns:**
com.aspose.psd.fileformats.psd.layers.ChannelInformation[]
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getGUID() {#getGUID--}
```
public final String getGUID()
```


GUID를 가져옵니다.

**Returns:**
java.lang.String
### getLength() {#getLength--}
```
public final long getLength()
```


필터 마스크 데이터 길이를 바이트 단위로 가져옵니다.

**Returns:**
long
### getMaskRectangle() {#getMaskRectangle--}
```
public final Rectangle getMaskRectangle()
```


시트 마스크 사각형을 가져옵니다.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getMaxChannels() {#getMaxChannels--}
```
public final int getMaxChannels()
```


채널 수의 최대값을 가져옵니다.

**Returns:**
int
### getPixelsDepth() {#getPixelsDepth--}
```
public final int getPixelsDepth()
```


픽셀 깊이를 가져옵니다.

**Returns:**
int
### getRectangle() {#getRectangle--}
```
public final Rectangle getRectangle()
```


채널 사각형을 가져옵니다.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getSheetMask() {#getSheetMask--}
```
public final ChannelInformation getSheetMask()
```


시트 마스크를 가져옵니다.

**Returns:**
[ChannelInformation](../../com.aspose.psd.fileformats.psd.layers/channelinformation)
### getUserMask() {#getUserMask--}
```
public final ChannelInformation getUserMask()
```


사용자 마스크를 가져옵니다.

**Returns:**
[ChannelInformation](../../com.aspose.psd.fileformats.psd.layers/channelinformation)
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




### saveData(StreamContainer streamContainer) {#saveData-com.aspose.psd.StreamContainer-}
```
public final void saveData(StreamContainer streamContainer)
```


지정된 스트림 컨테이너에 리소스를 저장합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | 저장할 스트림 컨테이너. |

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

