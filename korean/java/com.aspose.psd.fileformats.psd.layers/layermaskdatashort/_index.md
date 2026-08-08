---
title: "LayerMaskDataShort"
second_title: "Java용 Aspose.PSD API 참조"
description: "LayerMaskDataShort 클래스를 정의하며, 레이어가 래스터 마스크 또는 벡터 마스크 중 하나만 가지고 있을 때 PSD 파일 레이어의 마스크 데이터에 대한 정보를 포함합니다."
type: docs
weight: 23
url: /ko/java/com.aspose.psd.fileformats.psd.layers/layermaskdatashort/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata)
```
public final class LayerMaskDataShort extends LayerMaskData
```

LayerMaskDataShort 클래스를 정의하며, 레이어에 래스터 마스크 또는 벡터 마스크만 있고 둘 다는 없을 때 PSD 파일 레이어의 마스크 데이터에 대한 정보를 포함합니다. 그렇지 않은 경우에는 [LayerMaskDataFull](../../com.aspose.psd.fileformats.psd.layers/layermaskdatafull) 이 사용됩니다. 레이어에 래스터 마스크만 있는 경우 ImageData는 래스터 마스크 데이터 바이트를 포함합니다. 레이어에 벡터 마스크만 있는 경우 ImageData는 벡터 마스크가 래스터화(캐시)된 데이터 바이트를 포함합니다. LayerMaskData.ImageData ([LayerMaskData.getImageData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata\#getImageData)/[LayerMaskData.setImageData(byte[])](../../com.aspose.psd.fileformats.psd.layers/layermaskdata\#setImageData-byte---)) 바이트 길이는 LayerMaskData.MaskRectangle의 Width \* Height와 같아야 합니다 ([LayerMaskData.getMaskRectangle](../../com.aspose.psd.fileformats.psd.layers/layermaskdata\#getMaskRectangle)/[LayerMaskData.setMaskRectangle(Rectangle)](../../com.aspose.psd.fileformats.psd.layers/layermaskdata\#setMaskRectangle-Rectangle-)) 속성.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [LayerMaskDataShort()](#LayerMaskDataShort--) | 새로운 [LayerMaskDataShort](../../com.aspose.psd.fileformats.psd.layers/layermaskdatashort) 클래스의 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [create_internalized(PixelsData pixelsData)](#create-internalized-com.aspose.psd.pixelsdatamodels.PixelsData-) |  |
| [deepClone_internalized()](#deepClone-internalized--) | 이 인스턴스를 복제합니다. |
| [deepClone_internalized(LayerMaskData mask)](#deepClone-internalized-com.aspose.psd.fileformats.psd.layers.LayerMaskData-) | 레이어 마스크를 복제합니다. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBottom()](#getBottom--) | 하단 레이어 마스크 위치를 가져오거나 설정합니다. |
| [getClass()](#getClass--) |  |
| [getDataSize()](#getDataSize--) | 레이어 마스크 데이터의 크기를 가져옵니다. |
| [getDefaultColor()](#getDefaultColor--) | 기본 색상을 가져오거나 설정합니다. |
| [getFlags()](#getFlags--) | 레이어 마스크 플래그를 가져오거나 설정합니다. |
| [getHeight_internalized()](#getHeight-internalized--) | 마스크 높이를 가져옵니다. |
| [getImageData()](#getImageData--) | PSD 파일에서 레이어 마스크 데이터(벡터 마스크가 있는 경우 결합/최종 마스크)를 가져오거나 설정합니다. |
| [getLeft()](#getLeft--) | 왼쪽 레이어 마스크 위치를 가져오거나 설정합니다. |
| [getMaskRectangle()](#getMaskRectangle--) | PSD 파일에서 레이어 마스크의 mask  Rectangle을 가져오거나 설정합니다. |
| [getPadding()](#getPadding--) | 레이어 마스크 패딩을 가져오거나 설정합니다. |
| [getRight()](#getRight--) | 오른쪽 레이어 마스크 위치를 가져오거나 설정합니다. |
| [getTop()](#getTop--) | 위쪽 레이어 마스크 위치를 가져오거나 설정합니다. |
| [getWidth_internalized()](#getWidth-internalized--) | 마스크 너비를 가져옵니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save_internalized(StreamContainer streamContainer)](#save-internalized-com.aspose.psd.StreamContainer-) | 지정된  StreamContainer에 [LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata)를 저장합니다. |
| [setBottom(int value)](#setBottom-int-) | 하단 레이어 마스크 위치를 가져오거나 설정합니다. |
| [setDefaultColor(byte value)](#setDefaultColor-byte-) | 기본 색상을 가져오거나 설정합니다. |
| [setFlags(byte value)](#setFlags-byte-) | 레이어 마스크 플래그를 가져오거나 설정합니다. |
| [setImageData(byte[] value)](#setImageData-byte---) | PSD 파일에서 레이어 마스크 데이터(벡터 마스크가 있는 경우 결합/최종 마스크)를 가져오거나 설정합니다. |
| [setLeft(int value)](#setLeft-int-) | 왼쪽 레이어 마스크 위치를 가져오거나 설정합니다. |
| [setMaskRectangle(Rectangle value)](#setMaskRectangle-com.aspose.psd.Rectangle-) | PSD 파일에서 레이어 마스크의 mask  Rectangle을 가져오거나 설정합니다. |
| [setPadding(short value)](#setPadding-short-) | 레이어 마스크 패딩을 가져오거나 설정합니다. |
| [setRight(int value)](#setRight-int-) | 오른쪽 레이어 마스크 위치를 가져오거나 설정합니다. |
| [setTop(int value)](#setTop-int-) | 위쪽 레이어 마스크 위치를 가져오거나 설정합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LayerMaskDataShort() {#LayerMaskDataShort--}
```
public LayerMaskDataShort()
```


새로운 [LayerMaskDataShort](../../com.aspose.psd.fileformats.psd.layers/layermaskdatashort) 클래스의 인스턴스를 초기화합니다.

### create_internalized(PixelsData pixelsData) {#create-internalized-com.aspose.psd.pixelsdatamodels.PixelsData-}
```
public static LayerMaskDataShort create_internalized(PixelsData pixelsData)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pixelsData | [PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata) |  |

**Returns:**
[LayerMaskDataShort](../../com.aspose.psd.fileformats.psd.layers/layermaskdatashort)
### deepClone_internalized() {#deepClone-internalized--}
```
public LayerMaskData deepClone_internalized()
```


이 인스턴스를 복제합니다.

**Returns:**
[LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) - The cloned layer mask.
### deepClone_internalized(LayerMaskData mask) {#deepClone-internalized-com.aspose.psd.fileformats.psd.layers.LayerMaskData-}
```
public static LayerMaskData deepClone_internalized(LayerMaskData mask)
```


레이어 마스크를 복제합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| mask | [LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) | 마스크. |

**Returns:**
[LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) - The cloned layer mask.
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
### getBottom() {#getBottom--}
```
public final int getBottom()
```


하단 레이어 마스크 위치를 가져오거나 설정합니다.

값: 아래쪽 레이어 마스크 위치.

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDataSize() {#getDataSize--}
```
public final int getDataSize()
```


레이어 마스크 데이터의 크기를 가져옵니다.

값: 레이어 마스크 데이터의 크기.

**Returns:**
int
### getDefaultColor() {#getDefaultColor--}
```
public final byte getDefaultColor()
```


기본 색상을 가져오거나 설정합니다.

값: 기본 색상.

**Returns:**
byte
### getFlags() {#getFlags--}
```
public final byte getFlags()
```


레이어 마스크 플래그를 가져오거나 설정합니다.

값: 레이어 마스크 플래그.

**Returns:**
byte
### getHeight_internalized() {#getHeight-internalized--}
```
public final int getHeight_internalized()
```


마스크 높이를 가져옵니다.

값: 높이.

**Returns:**
int
### getImageData() {#getImageData--}
```
public final byte[] getImageData()
```


PSD 파일에서 레이어 마스크 데이터(벡터 마스크가 있는 경우 결합/최종 마스크)를 가져오거나 설정합니다.

값: 이미지 데이터.

**Returns:**
byte[]
### getLeft() {#getLeft--}
```
public final int getLeft()
```


왼쪽 레이어 마스크 위치를 가져오거나 설정합니다.

값: 왼쪽 레이어 마스크 위치.

**Returns:**
int
### getMaskRectangle() {#getMaskRectangle--}
```
public final Rectangle getMaskRectangle()
```


PSD 파일에서 레이어 마스크의 mask  Rectangle을 가져오거나 설정합니다. left, right, top 및 bottom 속성을 받아서  Rectangle을 생성합니다.

값: 마스크 rectangle.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getPadding() {#getPadding--}
```
public final short getPadding()
```


레이어 마스크 패딩을 가져오거나 설정합니다.

값: 레이어 마스크 패딩.

**Returns:**
short
### getRight() {#getRight--}
```
public final int getRight()
```


오른쪽 레이어 마스크 위치를 가져오거나 설정합니다.

값: 오른쪽 레이어 마스크 위치.

**Returns:**
int
### getTop() {#getTop--}
```
public final int getTop()
```


위쪽 레이어 마스크 위치를 가져오거나 설정합니다.

값: 위쪽 레이어 마스크 위치.

**Returns:**
int
### getWidth_internalized() {#getWidth-internalized--}
```
public final int getWidth_internalized()
```


마스크 너비를 가져옵니다.

값: 너비.

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




### save_internalized(StreamContainer streamContainer) {#save-internalized-com.aspose.psd.StreamContainer-}
```
public void save_internalized(StreamContainer streamContainer)
```


지정된  StreamContainer에 [LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata)를 저장합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | 데이터를 저장할 스트림 컨테이너. |

### setBottom(int value) {#setBottom-int-}
```
public final void setBottom(int value)
```


하단 레이어 마스크 위치를 가져오거나 설정합니다.

값: 아래쪽 레이어 마스크 위치.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setDefaultColor(byte value) {#setDefaultColor-byte-}
```
public final void setDefaultColor(byte value)
```


기본 색상을 가져오거나 설정합니다.

값: 기본 색상.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | byte |  |

### setFlags(byte value) {#setFlags-byte-}
```
public final void setFlags(byte value)
```


레이어 마스크 플래그를 가져오거나 설정합니다.

값: 레이어 마스크 플래그.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | byte |  |

### setImageData(byte[] value) {#setImageData-byte---}
```
public final void setImageData(byte[] value)
```


PSD 파일에서 레이어 마스크 데이터(벡터 마스크가 있는 경우 결합/최종 마스크)를 가져오거나 설정합니다.

값: 이미지 데이터.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | byte[] |  |

### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


왼쪽 레이어 마스크 위치를 가져오거나 설정합니다.

값: 왼쪽 레이어 마스크 위치.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setMaskRectangle(Rectangle value) {#setMaskRectangle-com.aspose.psd.Rectangle-}
```
public final void setMaskRectangle(Rectangle value)
```


PSD 파일에서 레이어 마스크의 mask  Rectangle을 가져오거나 설정합니다. left, right, top 및 bottom 속성을 받아서  Rectangle을 생성합니다.

값: 마스크 rectangle.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setPadding(short value) {#setPadding-short-}
```
public final void setPadding(short value)
```


레이어 마스크 패딩을 가져오거나 설정합니다.

값: 레이어 마스크 패딩.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | short |  |

### setRight(int value) {#setRight-int-}
```
public final void setRight(int value)
```


오른쪽 레이어 마스크 위치를 가져오거나 설정합니다.

값: 오른쪽 레이어 마스크 위치.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


위쪽 레이어 마스크 위치를 가져오거나 설정합니다.

값: 위쪽 레이어 마스크 위치.

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

