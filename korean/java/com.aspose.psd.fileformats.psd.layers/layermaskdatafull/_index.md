---
title: "LayerMaskDataFull"
second_title: "Java용 Aspose.PSD API 참조"
description: "LayerMaskDataFull 클래스를 정의하며, 레이어가 레이어 마스크와 벡터 마스크를 모두 가지고 있을 때 PSD 파일 레이어의 마스크 데이터에 대한 정보를 포함합니다."
type: docs
weight: 22
url: /ko/java/com.aspose.psd.fileformats.psd.layers/layermaskdatafull/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata)
```
public final class LayerMaskDataFull extends LayerMaskData
```

LayerMaskDataFull 클래스를 정의하며, 레이어에 레이어 마스크와 벡터 마스크가 모두 있을 때 PSD 파일 레이어의 마스크 데이터에 대한 정보를 포함합니다. 그렇지 않은 경우에는 [LayerMaskDataShort](../../com.aspose.psd.fileformats.psd.layers/layermaskdatashort) 이 사용됩니다. ImageData는 래스터 마스크와 래스터화된 벡터 마스크가 결합된 것을 포함합니다. ImageData 바이트 길이는 MaskRectangle.Width \* MaskRectangle.Height 속성과 같아야 합니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [LayerMaskDataFull()](#LayerMaskDataFull--) | 새로운 [LayerMaskDataFull](../../com.aspose.psd.fileformats.psd.layers/layermaskdatafull) 클래스의 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [deepClone_internalized()](#deepClone-internalized--) | 이 인스턴스를 복제합니다. |
| [deepClone_internalized(LayerMaskData mask)](#deepClone-internalized-com.aspose.psd.fileformats.psd.layers.LayerMaskData-) | 레이어 마스크를 복제합니다. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackgroundColor()](#getBackgroundColor--) | 배경 색상을 가져오거나 설정합니다. |
| [getBottom()](#getBottom--) | 하단 레이어 마스크 위치를 가져오거나 설정합니다. |
| [getClass()](#getClass--) |  |
| [getDataSize()](#getDataSize--) | 레이어 마스크 데이터의 크기를 가져옵니다. |
| [getDefaultColor()](#getDefaultColor--) | 기본 색상을 가져오거나 설정합니다. |
| [getEnclosingBottom()](#getEnclosingBottom--) | PSD 이미지 레이어에서 포함된 하단 래스터 마스크 위치를 가져오거나 설정합니다. |
| [getEnclosingLeft()](#getEnclosingLeft--) | PSD 파일 레이어에서 포함된 왼쪽 래스터 마스크 위치를 가져오거나 설정합니다. |
| [getEnclosingRight()](#getEnclosingRight--) | PSD 파일 레이어에서 포함된 오른쪽 래스터 마스크 위치를 가져오거나 설정합니다. |
| [getEnclosingTop()](#getEnclosingTop--) | PSD 이미지 레이어에서 포함된 래스터 마스크의 상단 위치를 가져오거나 설정합니다. |
| [getFlags()](#getFlags--) | 레이어 마스크 플래그를 가져오거나 설정합니다. |
| [getHeight_internalized()](#getHeight-internalized--) | 마스크 높이를 가져옵니다. |
| [getImageData()](#getImageData--) | PSD 파일에서 레이어 마스크 데이터(벡터 마스크가 있는 경우 결합/최종 마스크)를 가져오거나 설정합니다. |
| [getLeft()](#getLeft--) | 왼쪽 레이어 마스크 위치를 가져오거나 설정합니다. |
| [getMaskRectangle()](#getMaskRectangle--) | PSD 파일에서 레이어 마스크의 mask  Rectangle을 가져오거나 설정합니다. |
| [getRealFlags()](#getRealFlags--) | 사용자/래스터 마스크에 사용되는 레이어 마스크 플래그를 가져오거나 설정합니다. |
| [getRight()](#getRight--) | 오른쪽 레이어 마스크 위치를 가져오거나 설정합니다. |
| [getTop()](#getTop--) | 위쪽 레이어 마스크 위치를 가져오거나 설정합니다. |
| [getUserMaskData()](#getUserMaskData--) | PSD 파일의 레이어에 대한 사용자(래스터) 마스크 데이터를 가져오거나 설정합니다. |
| [getUserMaskRectangle()](#getUserMaskRectangle--) | PSD 이미지 레이어에서 사용자 마스크(포함) 사각형을 가져오거나 설정합니다. |
| [getWidth_internalized()](#getWidth-internalized--) | 마스크 너비를 가져옵니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save_internalized(StreamContainer streamContainer)](#save-internalized-com.aspose.psd.StreamContainer-) | 지정된  StreamContainer에 [LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata)를 저장합니다. |
| [setBackgroundColor(byte value)](#setBackgroundColor-byte-) | 배경 색상을 가져오거나 설정합니다. |
| [setBottom(int value)](#setBottom-int-) | 하단 레이어 마스크 위치를 가져오거나 설정합니다. |
| [setDefaultColor(byte value)](#setDefaultColor-byte-) | 기본 색상을 가져오거나 설정합니다. |
| [setEnclosingBottom(int value)](#setEnclosingBottom-int-) | PSD 이미지 레이어에서 포함된 하단 래스터 마스크 위치를 가져오거나 설정합니다. |
| [setEnclosingLeft(int value)](#setEnclosingLeft-int-) | PSD 파일 레이어에서 포함된 왼쪽 래스터 마스크 위치를 가져오거나 설정합니다. |
| [setEnclosingRight(int value)](#setEnclosingRight-int-) | PSD 파일 레이어에서 포함된 오른쪽 래스터 마스크 위치를 가져오거나 설정합니다. |
| [setEnclosingTop(int value)](#setEnclosingTop-int-) | PSD 이미지 레이어에서 포함된 래스터 마스크의 상단 위치를 가져오거나 설정합니다. |
| [setFlags(byte value)](#setFlags-byte-) | 레이어 마스크 플래그를 가져오거나 설정합니다. |
| [setImageData(byte[] value)](#setImageData-byte---) | PSD 파일에서 레이어 마스크 데이터(벡터 마스크가 있는 경우 결합/최종 마스크)를 가져오거나 설정합니다. |
| [setLeft(int value)](#setLeft-int-) | 왼쪽 레이어 마스크 위치를 가져오거나 설정합니다. |
| [setMaskRectangle(Rectangle value)](#setMaskRectangle-com.aspose.psd.Rectangle-) | PSD 파일에서 레이어 마스크의 mask  Rectangle을 가져오거나 설정합니다. |
| [setRealFlags(byte value)](#setRealFlags-byte-) | 사용자/래스터 마스크에 사용되는 레이어 마스크 플래그를 가져오거나 설정합니다. |
| [setRight(int value)](#setRight-int-) | 오른쪽 레이어 마스크 위치를 가져오거나 설정합니다. |
| [setTop(int value)](#setTop-int-) | 위쪽 레이어 마스크 위치를 가져오거나 설정합니다. |
| [setUserMaskData(byte[] value)](#setUserMaskData-byte---) | PSD 파일의 레이어에 대한 사용자(래스터) 마스크 데이터를 가져오거나 설정합니다. |
| [setUserMaskRectangle(Rectangle value)](#setUserMaskRectangle-com.aspose.psd.Rectangle-) | PSD 이미지 레이어에서 사용자 마스크(포함) 사각형을 가져오거나 설정합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LayerMaskDataFull() {#LayerMaskDataFull--}
```
public LayerMaskDataFull()
```


새로운 [LayerMaskDataFull](../../com.aspose.psd.fileformats.psd.layers/layermaskdatafull) 클래스의 인스턴스를 초기화합니다.

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
### getBackgroundColor() {#getBackgroundColor--}
```
public final byte getBackgroundColor()
```


배경 색상을 가져오거나 설정합니다.

값: 배경 색상.

**Returns:**
byte
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
### getEnclosingBottom() {#getEnclosingBottom--}
```
public final int getEnclosingBottom()
```


PSD 이미지 레이어에서 포함된 하단 래스터 마스크 위치를 가져오거나 설정합니다.

값: 아래쪽 레이어 마스크 위치.

**Returns:**
int
### getEnclosingLeft() {#getEnclosingLeft--}
```
public final int getEnclosingLeft()
```


PSD 파일 레이어에서 포함된 왼쪽 래스터 마스크 위치를 가져오거나 설정합니다.

값: 왼쪽 레이어 마스크 위치.

**Returns:**
int
### getEnclosingRight() {#getEnclosingRight--}
```
public final int getEnclosingRight()
```


PSD 파일 레이어에서 포함된 오른쪽 래스터 마스크 위치를 가져오거나 설정합니다.

값: 오른쪽 레이어 마스크 위치.

**Returns:**
int
### getEnclosingTop() {#getEnclosingTop--}
```
public final int getEnclosingTop()
```


PSD 이미지 레이어에서 포함된 래스터 마스크의 상단 위치를 가져오거나 설정합니다.

값: 위쪽 레이어 마스크 위치.

**Returns:**
int
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
### getRealFlags() {#getRealFlags--}
```
public final byte getRealFlags()
```


사용자/래스터 마스크에 사용되는 레이어 마스크 플래그를 가져오거나 설정합니다. 벡터 마스크의 경우 Flags 속성이 사용됩니다.

값: 실제 레이어 마스크 플래그.

**Returns:**
byte
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
### getUserMaskData() {#getUserMaskData--}
```
public final byte[] getUserMaskData()
```


PSD 파일의 레이어에 대한 사용자(래스터) 마스크 데이터를 가져오거나 설정합니다. (MaskData 속성에 래스터화된 벡터 마스크가 있습니다.)

값: PSD 이미지의 레이어 이미지 데이터.

**Returns:**
byte[]
### getUserMaskRectangle() {#getUserMaskRectangle--}
```
public final Rectangle getUserMaskRectangle()
```


PSD 이미지 레이어에서 사용자 마스크(포함) 사각형을 가져오거나 설정합니다.

값: 사용자 마스크 사각형.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
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

### setBackgroundColor(byte value) {#setBackgroundColor-byte-}
```
public final void setBackgroundColor(byte value)
```


배경 색상을 가져오거나 설정합니다.

값: 배경 색상.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | byte |  |

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

### setEnclosingBottom(int value) {#setEnclosingBottom-int-}
```
public final void setEnclosingBottom(int value)
```


PSD 이미지 레이어에서 포함된 하단 래스터 마스크 위치를 가져오거나 설정합니다.

값: 아래쪽 레이어 마스크 위치.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setEnclosingLeft(int value) {#setEnclosingLeft-int-}
```
public final void setEnclosingLeft(int value)
```


PSD 파일 레이어에서 포함된 왼쪽 래스터 마스크 위치를 가져오거나 설정합니다.

값: 왼쪽 레이어 마스크 위치.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setEnclosingRight(int value) {#setEnclosingRight-int-}
```
public final void setEnclosingRight(int value)
```


PSD 파일 레이어에서 포함된 오른쪽 래스터 마스크 위치를 가져오거나 설정합니다.

값: 오른쪽 레이어 마스크 위치.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setEnclosingTop(int value) {#setEnclosingTop-int-}
```
public final void setEnclosingTop(int value)
```


PSD 이미지 레이어에서 포함된 래스터 마스크의 상단 위치를 가져오거나 설정합니다.

값: 위쪽 레이어 마스크 위치.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

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

### setRealFlags(byte value) {#setRealFlags-byte-}
```
public final void setRealFlags(byte value)
```


사용자/래스터 마스크에 사용되는 레이어 마스크 플래그를 가져오거나 설정합니다. 벡터 마스크의 경우 Flags 속성이 사용됩니다.

값: 실제 레이어 마스크 플래그.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | byte |  |

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

### setUserMaskData(byte[] value) {#setUserMaskData-byte---}
```
public final void setUserMaskData(byte[] value)
```


PSD 파일의 레이어에 대한 사용자(래스터) 마스크 데이터를 가져오거나 설정합니다. (MaskData 속성에 래스터화된 벡터 마스크가 있습니다.)

값: PSD 이미지의 레이어 이미지 데이터.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | byte[] |  |

### setUserMaskRectangle(Rectangle value) {#setUserMaskRectangle-com.aspose.psd.Rectangle-}
```
public final void setUserMaskRectangle(Rectangle value)
```


PSD 이미지 레이어에서 사용자 마스크(포함) 사각형을 가져오거나 설정합니다.

값: 사용자 마스크 사각형.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

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

