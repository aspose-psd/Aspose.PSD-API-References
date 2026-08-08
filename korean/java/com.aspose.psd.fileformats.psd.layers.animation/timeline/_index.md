---
title: "Timeline"
second_title: "Java용 Aspose.PSD API 참조"
description: "시간 라인 옵션 모델."
type: docs
weight: 14
url: /ko/java/com.aspose.psd.fileformats.psd.layers.animation/timeline/
---

**Inheritance:**
java.lang.Object
```
public final class Timeline
```

시간 라인 옵션 모델.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [Timeline()](#Timeline--) | 새로운 [Timeline](../../com.aspose.psd.fileformats.psd.layers.animation/timeline) 클래스 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [applyTo_internalized(PsdImage psdImage)](#applyTo-internalized-com.aspose.psd.fileformats.psd.PsdImage-) | 현재 타임라인 값을 입력 PsdImage에 적용합니다 ([.getPsdImage](../../null/\#getPsdImage)/[.setPsdImage(PsdImage)](../../null/\#setPsdImage-PsdImage-)). |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAFSt()](#getAFSt--) | AFSt 값을 가져오거나 설정합니다. |
| [getActiveFrameIndex()](#getActiveFrameIndex--) | 활성 프레임 인덱스를 가져오거나 설정합니다. |
| [getClass()](#getClass--) |  |
| [getFrame(int frameId)](#getFrame-int-) | ID로 프레임을 가져옵니다. |
| [getFrames()](#getFrames--) | 프레임 목록을 가져옵니다. |
| [getFramesList()](#getFramesList--) | 프레임 목록을 가져옵니다. |
| [getFsID()](#getFsID--) | FsID 값을 가져오거나 설정합니다. |
| [getLoopesCount()](#getLoopesCount--) | 루프 수를 가져오거나 설정합니다. |
| [getPsdImage()](#getPsdImage--) | 이 [Timeline](../../com.aspose.psd.fileformats.psd.layers.animation/timeline)의 PsdImage을 가져오거나 설정합니다 ([.getPsdImage](../../null/\#getPsdImage)/[.setPsdImage(PsdImage)](../../null/\#setPsdImage-PsdImage-)). |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(System.IO.Stream outputStream, ImageOptionsBase options)](#save-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-) | 지정된 저장 옵션에 따라 지정된 형식으로 지정된 스트림에 PsdImage와 Timeline 데이터를 저장합니다. |
| [save(String filePath, ImageOptionsBase options)](#save-java.lang.String-com.aspose.psd.ImageOptionsBase-) | 지정된 저장 옵션에 따라 지정된 형식으로 지정된 파일 위치에 PsdImage와 Timeline 데이터를 저장합니다. |
| [setAFSt(int value)](#setAFSt-int-) | AFSt 값을 가져오거나 설정합니다. |
| [setActiveFrameIndex_internalized(int value)](#setActiveFrameIndex-internalized-int-) | 활성 프레임 인덱스를 가져오거나 설정합니다. |
| [setFrames(Frame[] value)](#setFrames-com.aspose.psd.fileformats.psd.layers.animation.Frame---) | 프레임 목록을 가져옵니다. |
| [setFsID(int value)](#setFsID-int-) | FsID 값을 가져오거나 설정합니다. |
| [setLoopesCount(int value)](#setLoopesCount-int-) | 루프 수를 가져오거나 설정합니다. |
| [setPsdImage(PsdImage value)](#setPsdImage-com.aspose.psd.fileformats.psd.PsdImage-) | 이 [Timeline](../../com.aspose.psd.fileformats.psd.layers.animation/timeline)의 PsdImage을 가져오거나 설정합니다 ([.getPsdImage](../../null/\#getPsdImage)/[.setPsdImage(PsdImage)](../../null/\#setPsdImage-PsdImage-)). |
| [switchActiveFrame(int targetActiveFrameIndex)](#switchActiveFrame-int-) | 활성 프레임을 대상 프레임으로 전환합니다. |
| [toString()](#toString--) |  |
| [updateFrameFromPsdImage_internalized(int frameIndex)](#updateFrameFromPsdImage-internalized-int-) | 현재 타임라인 값을 입력 PsdImage에 적용합니다 ([.getPsdImage](../../null/\#getPsdImage)/[.setPsdImage(PsdImage)](../../null/\#setPsdImage-PsdImage-)). |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Timeline() {#Timeline--}
```
public Timeline()
```


새로운 [Timeline](../../com.aspose.psd.fileformats.psd.layers.animation/timeline) 클래스 인스턴스를 초기화합니다.

### applyTo_internalized(PsdImage psdImage) {#applyTo-internalized-com.aspose.psd.fileformats.psd.PsdImage-}
```
public void applyTo_internalized(PsdImage psdImage)
```


현재 타임라인 값을 입력 PsdImage에 적용합니다 ([.getPsdImage](../../null/\#getPsdImage)/[.setPsdImage(PsdImage)](../../null/\#setPsdImage-PsdImage-)).

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| psdImage | [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) | psd 이미지입니다. |

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
### getAFSt() {#getAFSt--}
```
public int getAFSt()
```


AFSt 값을 가져오거나 설정합니다.

**Returns:**
int
### getActiveFrameIndex() {#getActiveFrameIndex--}
```
public int getActiveFrameIndex()
```


활성 프레임 인덱스를 가져오거나 설정합니다.

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFrame(int frameId) {#getFrame-int-}
```
public Frame getFrame(int frameId)
```


ID로 프레임을 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| frameId | int | 프레임 ID입니다. |

**Returns:**
[Frame](../../com.aspose.psd.fileformats.psd.layers.animation/frame) - Returns the frame item or NULL if not exists.
### getFrames() {#getFrames--}
```
public Frame[] getFrames()
```


프레임 목록을 가져옵니다.

**Returns:**
com.aspose.psd.fileformats.psd.layers.animation.Frame[]
### getFramesList() {#getFramesList--}
```
public System.Collections.Generic.List<Frame> getFramesList()
```


프레임 목록을 가져옵니다.

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.animation.Frame>
### getFsID() {#getFsID--}
```
public int getFsID()
```


FsID 값을 가져오거나 설정합니다.

**Returns:**
int
### getLoopesCount() {#getLoopesCount--}
```
public int getLoopesCount()
```


루프 수를 가져오거나 설정합니다.

**Returns:**
int
### getPsdImage() {#getPsdImage--}
```
public PsdImage getPsdImage()
```


이 [Timeline](../../com.aspose.psd.fileformats.psd.layers.animation/timeline)의 PsdImage을 가져오거나 설정합니다 ([.getPsdImage](../../null/\#getPsdImage)/[.setPsdImage(PsdImage)](../../null/\#setPsdImage-PsdImage-)).

**Returns:**
[PsdImage](../../com.aspose.psd.fileformats.psd/psdimage)
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




### save(System.IO.Stream outputStream, ImageOptionsBase options) {#save-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-}
```
public void save(System.IO.Stream outputStream, ImageOptionsBase options)
```


지정된 저장 옵션에 따라 지정된 형식으로 지정된 스트림에 PsdImage와 Timeline 데이터를 저장합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| outputStream | com.aspose.ms.System.IO.Stream | 출력 스트림입니다. |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | 옵션. |

### save(String filePath, ImageOptionsBase options) {#save-java.lang.String-com.aspose.psd.ImageOptionsBase-}
```
public void save(String filePath, ImageOptionsBase options)
```


지정된 저장 옵션에 따라 지정된 형식으로 지정된 파일 위치에 PsdImage와 Timeline 데이터를 저장합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| filePath | java.lang.String | 파일 경로. |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | 옵션. |

### setAFSt(int value) {#setAFSt-int-}
```
public void setAFSt(int value)
```


AFSt 값을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setActiveFrameIndex_internalized(int value) {#setActiveFrameIndex-internalized-int-}
```
public void setActiveFrameIndex_internalized(int value)
```


활성 프레임 인덱스를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setFrames(Frame[] value) {#setFrames-com.aspose.psd.fileformats.psd.layers.animation.Frame---}
```
public void setFrames(Frame[] value)
```


프레임 목록을 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Frame\[\]](../../com.aspose.psd.fileformats.psd.layers.animation/frame) |  |

### setFsID(int value) {#setFsID-int-}
```
public void setFsID(int value)
```


FsID 값을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setLoopesCount(int value) {#setLoopesCount-int-}
```
public void setLoopesCount(int value)
```


루프 수를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setPsdImage(PsdImage value) {#setPsdImage-com.aspose.psd.fileformats.psd.PsdImage-}
```
public void setPsdImage(PsdImage value)
```


이 [Timeline](../../com.aspose.psd.fileformats.psd.layers.animation/timeline)의 PsdImage을 가져오거나 설정합니다 ([.getPsdImage](../../null/\#getPsdImage)/[.setPsdImage(PsdImage)](../../null/\#setPsdImage-PsdImage-)).

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) |  |

### switchActiveFrame(int targetActiveFrameIndex) {#switchActiveFrame-int-}
```
public void switchActiveFrame(int targetActiveFrameIndex)
```


활성 프레임을 대상 프레임으로 전환합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| targetActiveFrameIndex | int | 대상 프레임 인덱스입니다. |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### updateFrameFromPsdImage_internalized(int frameIndex) {#updateFrameFromPsdImage-internalized-int-}
```
public void updateFrameFromPsdImage_internalized(int frameIndex)
```


현재 타임라인 값을 입력 PsdImage에 적용합니다 ([.getPsdImage](../../null/\#getPsdImage)/[.setPsdImage(PsdImage)](../../null/\#setPsdImage-PsdImage-)).

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| frameIndex | int | 레이어 상태를 업데이트할 프레임 인덱스입니다. |

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

