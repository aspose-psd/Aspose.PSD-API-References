---
title: "GlobalLayerMaskInfo"
second_title: "Java용 Aspose.PSD API 참조"
description: "전역 레이어 마스크 섹션."
type: docs
weight: 15
url: /ko/java/com.aspose.psd.fileformats.psd.layers/globallayermaskinfo/
---

**Inheritance:**
java.lang.Object
```
public final class GlobalLayerMaskInfo
```

전역 레이어 마스크 섹션.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [GlobalLayerMaskInfo()](#GlobalLayerMaskInfo--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlphaMask()](#getAlphaMask--) | 알파 마스크를 가져오거나 설정합니다. |
| [getBlueMask()](#getBlueMask--) | 파란색 마스크를 가져오거나 설정합니다. |
| [getClass()](#getClass--) |  |
| [getGreenMask()](#getGreenMask--) | 녹색 마스크를 가져오거나 설정합니다. |
| [getKind()](#getKind--) | 종류를 가져오거나 설정합니다. |
| [getLength()](#getLength--) | 전역 레이어 마스크 섹션의 길이를 바이트 단위로 가져옵니다. |
| [getOpacity()](#getOpacity--) | 전역 레이어 불투명도를 가져오거나 설정합니다. |
| [getOverlayColorSpace()](#getOverlayColorSpace--) | 오버레이 색 공간을 가져오거나 설정합니다 (문서화되지 않은 값). |
| [getRedMask()](#getRedMask--) | 빨간색 마스크를 가져오거나 설정합니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save_internalized(StreamContainer streamContainer)](#save-internalized-com.aspose.psd.StreamContainer-) | 지정된 스트림 컨테이너에 데이터를 저장합니다. |
| [setAlphaMask(short value)](#setAlphaMask-short-) | 알파 마스크를 가져오거나 설정합니다. |
| [setBlueMask(short value)](#setBlueMask-short-) | 파란색 마스크를 가져오거나 설정합니다. |
| [setGreenMask(short value)](#setGreenMask-short-) | 녹색 마스크를 가져오거나 설정합니다. |
| [setKind(byte value)](#setKind-byte-) | 종류를 가져오거나 설정합니다. |
| [setOpacity(short value)](#setOpacity-short-) | 전역 레이어 불투명도를 가져오거나 설정합니다. |
| [setOverlayColorSpace(short value)](#setOverlayColorSpace-short-) | 오버레이 색 공간을 가져오거나 설정합니다 (문서화되지 않은 값). |
| [setRedMask(short value)](#setRedMask-short-) | 빨간색 마스크를 가져오거나 설정합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GlobalLayerMaskInfo() {#GlobalLayerMaskInfo--}
```
public GlobalLayerMaskInfo()
```


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
### getAlphaMask() {#getAlphaMask--}
```
public final short getAlphaMask()
```


알파 마스크를 가져오거나 설정합니다.

값: 알파 마스크.

**Returns:**
short
### getBlueMask() {#getBlueMask--}
```
public final short getBlueMask()
```


파란색 마스크를 가져오거나 설정합니다.

값: 파란색 마스크.

**Returns:**
short
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getGreenMask() {#getGreenMask--}
```
public final short getGreenMask()
```


녹색 마스크를 가져오거나 설정합니다.

값: 녹색 마스크.

**Returns:**
short
### getKind() {#getKind--}
```
public final byte getKind()
```


종류를 가져오거나 설정합니다. 0 = 선택된 색상--즉, 반전; 1 = 색상 보호; 128 = 레이어당 저장된 값을 사용합니다. 이 값이 기본값입니다. 다른 값은 베타 버전과의 호환성을 위해 제공됩니다.

값: 종류.

**Returns:**
byte
### getLength() {#getLength--}
```
public final long getLength()
```


전역 레이어 마스크 섹션의 길이를 바이트 단위로 가져옵니다.

**Returns:**
long
### getOpacity() {#getOpacity--}
```
public final short getOpacity()
```


전역 레이어 불투명도를 가져오거나 설정합니다. 0 = 투명, 100 = 불투명.

값: 전역 레이어 불투명도.

**Returns:**
short
### getOverlayColorSpace() {#getOverlayColorSpace--}
```
public final short getOverlayColorSpace()
```


오버레이 색 공간을 가져오거나 설정합니다 (문서화되지 않은 값).

값: 오버레이 색 공간.

**Returns:**
short
### getRedMask() {#getRedMask--}
```
public final short getRedMask()
```


빨간색 마스크를 가져오거나 설정합니다.

값: 빨간색 마스크.

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




### save_internalized(StreamContainer streamContainer) {#save-internalized-com.aspose.psd.StreamContainer-}
```
public final void save_internalized(StreamContainer streamContainer)
```


지정된 스트림 컨테이너에 데이터를 저장합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | 저장할 스트림 컨테이너. |

### setAlphaMask(short value) {#setAlphaMask-short-}
```
public final void setAlphaMask(short value)
```


알파 마스크를 가져오거나 설정합니다.

값: 알파 마스크.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | short |  |

### setBlueMask(short value) {#setBlueMask-short-}
```
public final void setBlueMask(short value)
```


파란색 마스크를 가져오거나 설정합니다.

값: 파란색 마스크.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | short |  |

### setGreenMask(short value) {#setGreenMask-short-}
```
public final void setGreenMask(short value)
```


녹색 마스크를 가져오거나 설정합니다.

값: 녹색 마스크.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | short |  |

### setKind(byte value) {#setKind-byte-}
```
public final void setKind(byte value)
```


종류를 가져오거나 설정합니다. 0 = 선택된 색상--즉, 반전; 1 = 색상 보호; 128 = 레이어당 저장된 값을 사용합니다. 이 값이 기본값입니다. 다른 값은 베타 버전과의 호환성을 위해 제공됩니다.

값: 종류.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | byte |  |

### setOpacity(short value) {#setOpacity-short-}
```
public final void setOpacity(short value)
```


전역 레이어 불투명도를 가져오거나 설정합니다. 0 = 투명, 100 = 불투명.

값: 전역 레이어 불투명도.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | short |  |

### setOverlayColorSpace(short value) {#setOverlayColorSpace-short-}
```
public final void setOverlayColorSpace(short value)
```


오버레이 색 공간을 가져오거나 설정합니다 (문서화되지 않은 값).

값: 오버레이 색 공간.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | short |  |

### setRedMask(short value) {#setRedMask-short-}
```
public final void setRedMask(short value)
```


빨간색 마스크를 가져오거나 설정합니다.

값: 빨간색 마스크.

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

