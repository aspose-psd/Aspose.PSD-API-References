---
title: "PhflResourceVersion3"
second_title: "Java용 Aspose.PSD API 참조"
description: "PhflResource 클래스."
type: docs
weight: 70
url: /ko/java/com.aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.AdjustmentLayerResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.PhflResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/phflresource)
```
public class PhflResourceVersion3 extends PhflResource
```

클래스 PhflResource. Exposure Adjustment Layer 2의 리소스 버전 ( = 3 ) 또는 ( = 2 ) 12 4바이트씩 XYZ 색상(버전 3에만 해당) 10 2바이트 색 공간 뒤에 4 \* 2바이트 색 구성 요소(버전 2에만 해당) 4 밀도 1 밝기 보존
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [PhflResourceVersion3()](#PhflResourceVersion3--) | 새 인스턴스를 초기화합니다 [PhflResourceVersion3](../../com.aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3) 클래스의. |
| [PhflResourceVersion3(byte[] data)](#PhflResourceVersion3-byte---) | 새 인스턴스를 초기화합니다 [PhflResourceVersion3](../../com.aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3) 클래스의. |
## 필드

| 필드 | 설명 |
| --- | --- |
| [PsbHeaderVersion_internalized](#PsbHeaderVersion-internalized) | PSB 헤더 버전입니다. |
| [PsbResourceSignature](#PsbResourceSignature) | PSB 전용 리소스 서명입니다. |
| [PsdHeaderVersion_internalized](#PsdHeaderVersion-internalized) | PSD 헤더 버전입니다. |
| [ResourceSignature](#ResourceSignature) | 공통 리소스 서명입니다. |
| [TypeToolKey](#TypeToolKey) | 타입 도구 정보 키. |
| [ventureLicense_internalized](#ventureLicense-internalized) | 벤처 라이선스. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [checkAndSetIfResourceIsPsbSpecific_internalized(int key)](#checkAndSetIfResourceIsPsbSpecific-internalized-int-) | 리소스가 PSB 전용인지 확인하고 설정합니다. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getColorSpace()](#getColorSpace--) | 색 공간을 가져옵니다. |
| [getColorX()](#getColorX--) | X 색상을 가져오거나 설정합니다. |
| [getColorY()](#getColorY--) | Y 색상을 가져오거나 설정합니다. |
| [getColorZ()](#getColorZ--) | Z 색상을 가져오거나 설정합니다. |
| [getData()](#getData--) | 데이터를 가져오거나 설정합니다. |
| [getDensity()](#getDensity--) | 밀도를 가져오거나 설정합니다. |
| [getHeader_internalized()](#getHeader-internalized--) | 헤더를 가져오거나 설정합니다. |
| [getKey()](#getKey--) | 레이어 리소스 키를 가져옵니다. |
| [getLength()](#getLength--) | 레이어 리소스 길이를 바이트 단위로 가져옵니다. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | 접두사 길이를 가져옵니다. |
| [getPreserveLuminosity()](#getPreserveLuminosity--) | 밝기 보존 여부를 나타내는 값을 가져오거나 설정합니다 [preserve luminosity]. |
| [getPsdVersion()](#getPsdVersion--) | 레이어 리소스에 필요한 최소 PSD 버전을 가져옵니다. |
| [getRgbColor()](#getRgbColor--) | 색상을 가져옵니다. |
| [getSignature()](#getSignature--) | 레이어 리소스 서명을 가져옵니다. |
| [getVersion()](#getVersion--) | 버전을 가져옵니다. |
| [hashCode()](#hashCode--) |  |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | 리소스가 PSB 전용인지 여부를 결정합니다. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | 이 인스턴스가 리소스 PSB 전용인지 여부를 나타내는 값을 가져옵니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | 지정된 스트림 컨테이너에 리소스를 저장합니다. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | 사용자 정의 리소스 헤더를 저장합니다. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | 헤더 서명, 식별자 및 길이를 저장합니다. |
| [setColorSpace(short value)](#setColorSpace-short-) | 색 공간을 가져옵니다. |
| [setColorX(float value)](#setColorX-float-) | X 색상을 가져오거나 설정합니다. |
| [setColorY(float value)](#setColorY-float-) | Y 색상을 가져오거나 설정합니다. |
| [setColorZ(float value)](#setColorZ-float-) | Z 색상을 가져오거나 설정합니다. |
| [setDensity(int value)](#setDensity-int-) | 밀도를 가져오거나 설정합니다. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | 헤더를 가져오거나 설정합니다. |
| [setPreserveLuminosity(boolean value)](#setPreserveLuminosity-boolean-) | 밝기 보존 여부를 나타내는 값을 가져오거나 설정합니다 [preserve luminosity]. |
| [setRgbColor(Color color)](#setRgbColor-com.aspose.psd.Color-) | RGB 색상을 설정합니다. |
| [setVersion(short value)](#setVersion-short-) | 버전을 가져옵니다. |
| [toString()](#toString--) | 이 인스턴스를 나타내는 문자열을 반환합니다. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PhflResourceVersion3() {#PhflResourceVersion3--}
```
public PhflResourceVersion3()
```


새 인스턴스를 초기화합니다 [PhflResourceVersion3](../../com.aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3) 클래스의.

### PhflResourceVersion3(byte[] data) {#PhflResourceVersion3-byte---}
```
public PhflResourceVersion3(byte[] data)
```


새 인스턴스를 초기화합니다 [PhflResourceVersion3](../../com.aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3) 클래스의.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 데이터 | byte[] | 리소스의 데이터입니다. |

### PsbHeaderVersion_internalized {#PsbHeaderVersion-internalized}
```
public static final int PsbHeaderVersion_internalized
```


PSB 헤더 버전입니다.

### PsbResourceSignature {#PsbResourceSignature}
```
public static final int PsbResourceSignature
```


PSB 전용 리소스 서명입니다.

### PsdHeaderVersion_internalized {#PsdHeaderVersion-internalized}
```
public static final int PsdHeaderVersion_internalized
```


PSD 헤더 버전입니다.

### ResourceSignature {#ResourceSignature}
```
public static final int ResourceSignature
```


공통 리소스 서명입니다.

### TypeToolKey {#TypeToolKey}
```
public static final int TypeToolKey
```


타입 도구 정보 키.

### ventureLicense_internalized {#ventureLicense-internalized}
```
public Object ventureLicense_internalized
```


벤처 라이선스.

### checkAndSetIfResourceIsPsbSpecific_internalized(int key) {#checkAndSetIfResourceIsPsbSpecific-internalized-int-}
```
public final void checkAndSetIfResourceIsPsbSpecific_internalized(int key)
```


리소스가 PSB 전용인지 확인하고 설정합니다. 현재 일부 리소스는 인식되지 않지만, 저장 시 동작이 변경되는 PSB 전용 리소스 전체 목록이 있습니다. 따라서 최소한 UnknownResource에서 이를 확인해야 합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 키 | int | 키. |

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
### getColorSpace() {#getColorSpace--}
```
public final short getColorSpace()
```


색 공간을 가져옵니다.

값: 색 공간입니다.

**Returns:**
short
### getColorX() {#getColorX--}
```
public final float getColorX()
```


X 색상을 가져오거나 설정합니다.

값: X 색상.

**Returns:**
float
### getColorY() {#getColorY--}
```
public final float getColorY()
```


Y 색상을 가져오거나 설정합니다.

값: Y 색상.

**Returns:**
float
### getColorZ() {#getColorZ--}
```
public final float getColorZ()
```


Z 색상을 가져오거나 설정합니다.

값: Z 색상.

**Returns:**
float
### getData() {#getData--}
```
public final byte[] getData()
```


데이터를 가져오거나 설정합니다.

값: 데이터.

**Returns:**
byte[]
### getDensity() {#getDensity--}
```
public final int getDensity()
```


밀도를 가져오거나 설정합니다.

값: 밀도.

**Returns:**
int
### getHeader_internalized() {#getHeader-internalized--}
```
public final PsdHeader getHeader_internalized()
```


헤더를 가져오거나 설정합니다.

값: 헤더.

**Returns:**
com.aspose.internal.fileformats.psd.sections.PsdHeader
### getKey() {#getKey--}
```
public final int getKey()
```


레이어 리소스 키를 가져옵니다.

**Returns:**
int
### getLength() {#getLength--}
```
public int getLength()
```


레이어 리소스 길이를 바이트 단위로 가져옵니다.

**Returns:**
int
### getPrefixLength_internalized(int psdVersion) {#getPrefixLength-internalized-int-}
```
public final int getPrefixLength_internalized(int psdVersion)
```


접두사 길이를 가져옵니다. 기본값은 8BIM 리소스의 경우 12이며, 8B64의 경우 16입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| psdVersion | int | PSD 버전. |

**Returns:**
int - 접두사 길이.
### getPreserveLuminosity() {#getPreserveLuminosity--}
```
public final boolean getPreserveLuminosity()
```


밝기 보존 여부를 나타내는 값을 가져오거나 설정합니다 [preserve luminosity].

값:  true  [preserve luminosity]인 경우; 그렇지 않으면,  false .

**Returns:**
boolean
### getPsdVersion() {#getPsdVersion--}
```
public int getPsdVersion()
```


레이어 리소스에 필요한 최소 PSD 버전을 가져옵니다. 0은 제한이 없음을 나타냅니다.

**Returns:**
int
### getRgbColor() {#getRgbColor--}
```
public Color getRgbColor()
```


색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - The RGB color
### getSignature() {#getSignature--}
```
public int getSignature()
```


레이어 리소스 서명을 가져옵니다.

**Returns:**
int
### getVersion() {#getVersion--}
```
public short getVersion()
```


버전을 가져옵니다. 기본값은 2 또는 3입니다.

**Returns:**
short
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isResourcePsbSpecificByKey_internalized(int key) {#isResourcePsbSpecificByKey-internalized-int-}
```
public static boolean isResourcePsbSpecificByKey_internalized(int key)
```


리소스가 PSB 전용인지 여부를 결정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 키 | int | 리소스 키. |

**Returns:**
boolean -  true  리소스가 PSB 전용이면; 그렇지 않으면,  false .
### isResourcePsbSpecific_internalized() {#isResourcePsbSpecific-internalized--}
```
public final boolean isResourcePsbSpecific_internalized()
```


이 인스턴스가 리소스 PSB 전용인지 여부를 나타내는 값을 가져옵니다.

값:  true  이 인스턴스가 리소스 PSB 전용이면; 그렇지 않으면,  false .

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




### save(StreamContainer streamContainer, int psdVersion) {#save-com.aspose.psd.StreamContainer-int-}
```
public void save(StreamContainer streamContainer, int psdVersion)
```


지정된 스트림 컨테이너에 리소스를 저장합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | 저장할 스트림 컨테이너. |
| psdVersion | int | PSD 버전. |

### saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature) {#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-}
```
public final void saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)
```


사용자 정의 리소스 헤더를 저장합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | 스트림 컨테이너입니다. |
| 시그니처 | int | 서명. |

### saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong) {#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-}
```
public final void saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)
```


헤더 서명, 식별자 및 길이를 저장합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | 스트림 컨테이너입니다. |
| 시그니처 | int | 서명. |
| isLengthLong | boolean | 설정된 경우  true  길이가 깁니다. |

### setColorSpace(short value) {#setColorSpace-short-}
```
public void setColorSpace(short value)
```


색 공간을 가져옵니다.

값: 색 공간입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | short |  |

### setColorX(float value) {#setColorX-float-}
```
public final void setColorX(float value)
```


X 색상을 가져오거나 설정합니다.

값: X 색상.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | float |  |

### setColorY(float value) {#setColorY-float-}
```
public final void setColorY(float value)
```


Y 색상을 가져오거나 설정합니다.

값: Y 색상.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | float |  |

### setColorZ(float value) {#setColorZ-float-}
```
public final void setColorZ(float value)
```


Z 색상을 가져오거나 설정합니다.

값: Z 색상.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | float |  |

### setDensity(int value) {#setDensity-int-}
```
public final void setDensity(int value)
```


밀도를 가져오거나 설정합니다.

값: 밀도.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setHeader_internalized(PsdHeader value) {#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-}
```
public final void setHeader_internalized(PsdHeader value)
```


헤더를 가져오거나 설정합니다.

값: 헤더.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | com.aspose.internal.fileformats.psd.sections.PsdHeader |  |

### setPreserveLuminosity(boolean value) {#setPreserveLuminosity-boolean-}
```
public final void setPreserveLuminosity(boolean value)
```


밝기 보존 여부를 나타내는 값을 가져오거나 설정합니다 [preserve luminosity].

값:  true  [preserve luminosity]인 경우; 그렇지 않으면,  false .

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setRgbColor(Color color) {#setRgbColor-com.aspose.psd.Color-}
```
public void setRgbColor(Color color)
```


RGB 색상을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| color | [Color](../../com.aspose.psd/color) | 색상. |

### setVersion(short value) {#setVersion-short-}
```
public void setVersion(short value)
```


버전을 가져옵니다. 기본값은 2 또는 3입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | short |  |

### toString() {#toString--}
```
public String toString()
```


이 인스턴스를 나타내는 문자열을 반환합니다.

**Returns:**
java.lang.String - 이 인스턴스를 나타내는 문자열.
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

