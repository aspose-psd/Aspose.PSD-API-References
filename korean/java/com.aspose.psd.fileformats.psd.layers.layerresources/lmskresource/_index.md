---
title: "LmskResource"
second_title: "Java용 Aspose.PSD API 참조"
description: "LMsk 리소스."
type: docs
weight: 50
url: /ko/java/com.aspose.psd.fileformats.psd.layers.layerresources/lmskresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource)
```
public class LmskResource extends LayerResource
```

LMsk 리소스.

--------------------

이 리소스에는 색 공간 ID가 포함되어 있으며, 이는 특정 색 공간 유형을 나타내고 4개의 색 구성 요소를 가집니다. ID에 따라 색 구성 요소의 의미가 다릅니다. 색 공간 유형이 네 값을 필요로 하지 않을 경우, 추가 구성 요소는 정의되지 않으며 항상 0으로 기록됩니다. 색 공간 유형별 색 구성 요소: RGB - 처음 세 구성 요소는 빨강, 초록, 파랑입니다. HSB - 처음 세 구성 요소는 색조, 채도, 밝기입니다. CMYK - 네 구성 요소는 시안, 마젠타, 옐로우, 검정입니다. Lab - 처음 세 구성 요소는 밝기, a 색차, b 색차입니다. Grayscale - 첫 번째 구성 요소는 회색 값이며, 0...10000 범위입니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [LmskResource()](#LmskResource--) | 새 인스턴스를 초기화합니다 [LmskResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/lmskresource) 클래스. |
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
| [create_internalized(byte[] data)](#create-internalized-byte---) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getColorComponent1()](#getColorComponent1--) | 색 구성 요소 1을 가져옵니다. |
| [getColorComponent2()](#getColorComponent2--) | 색 구성 요소 2를 가져옵니다. |
| [getColorComponent3()](#getColorComponent3--) | 색 구성 요소 3을 가져옵니다. |
| [getColorComponent4()](#getColorComponent4--) | 색 구성 요소 4를 가져옵니다. |
| [getColorSpace()](#getColorSpace--) | 색 공간을 가져옵니다. |
| [getFlag()](#getFlag--) | 플래그를 가져옵니다. |
| [getHeader_internalized()](#getHeader-internalized--) | 헤더를 가져오거나 설정합니다. |
| [getKey()](#getKey--) | 레이어 리소스 키를 가져옵니다. |
| [getLength()](#getLength--) | 레이어 리소스 길이를 바이트 단위로 가져옵니다. |
| [getOpacity()](#getOpacity--) | 불투명도를 가져옵니다. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | 접두사 길이를 가져옵니다. |
| [getPsdVersion()](#getPsdVersion--) | 레이어 리소스에 필요한 최소 PSD 버전을 가져옵니다. |
| [getSignature()](#getSignature--) | 레이어 리소스 서명을 가져옵니다. |
| [hashCode()](#hashCode--) |  |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | 리소스가 PSB 전용인지 여부를 결정합니다. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | 이 인스턴스가 리소스 PSB 전용인지 여부를 나타내는 값을 가져옵니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | 지정된 스트림 컨테이너에 리소스를 저장합니다. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | 사용자 정의 리소스 헤더를 저장합니다. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | 헤더 서명, 식별자 및 길이를 저장합니다. |
| [setColorComponent1(int value)](#setColorComponent1-int-) | 색 구성 요소 1을 가져옵니다. |
| [setColorComponent2(int value)](#setColorComponent2-int-) | 색 구성 요소 2를 가져옵니다. |
| [setColorComponent3(int value)](#setColorComponent3-int-) | 색 구성 요소 3을 가져옵니다. |
| [setColorComponent4(int value)](#setColorComponent4-int-) | 색 구성 요소 4를 가져옵니다. |
| [setColorSpace(int value)](#setColorSpace-int-) | 색 공간을 가져옵니다. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | 헤더를 가져오거나 설정합니다. |
| [setOpacity(short value)](#setOpacity-short-) | 불투명도를 가져옵니다. |
| [toString()](#toString--) | 이 인스턴스를 나타내는 문자열을 반환합니다. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LmskResource() {#LmskResource--}
```
public LmskResource()
```


새 인스턴스를 초기화합니다 [LmskResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/lmskresource) 클래스.

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

### create_internalized(byte[] data) {#create-internalized-byte---}
```
public static LmskResource create_internalized(byte[] data)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 데이터 | byte[] |  |

**Returns:**
[LmskResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/lmskresource)
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
### getColorComponent1() {#getColorComponent1--}
```
public final int getColorComponent1()
```


색 구성 요소 1을 가져옵니다.

값: 색 구성 요소 1.

**Returns:**
int
### getColorComponent2() {#getColorComponent2--}
```
public final int getColorComponent2()
```


색 구성 요소 2를 가져옵니다.

값: 색 구성 요소 2.

**Returns:**
int
### getColorComponent3() {#getColorComponent3--}
```
public final int getColorComponent3()
```


색 구성 요소 3을 가져옵니다.

값: 색 구성 요소 3.

**Returns:**
int
### getColorComponent4() {#getColorComponent4--}
```
public final int getColorComponent4()
```


색 구성 요소 4를 가져옵니다.

값: 색 구성 요소 4.

**Returns:**
int
### getColorSpace() {#getColorSpace--}
```
public final int getColorSpace()
```


색 공간을 가져옵니다.

값: 색 공간입니다.

**Returns:**
int
### getFlag() {#getFlag--}
```
public final byte getFlag()
```


플래그를 가져옵니다.

값: 플래그.

**Returns:**
byte
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
### getOpacity() {#getOpacity--}
```
public final short getOpacity()
```


불투명도를 가져옵니다.

값: 불투명도.

**Returns:**
short
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
### getPsdVersion() {#getPsdVersion--}
```
public int getPsdVersion()
```


레이어 리소스에 필요한 최소 PSD 버전을 가져옵니다. 0은 제한이 없음을 나타냅니다.

**Returns:**
int
### getSignature() {#getSignature--}
```
public int getSignature()
```


레이어 리소스 서명을 가져옵니다.

**Returns:**
int
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

### setColorComponent1(int value) {#setColorComponent1-int-}
```
public final void setColorComponent1(int value)
```


색 구성 요소 1을 가져옵니다.

값: 색 구성 요소 1.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setColorComponent2(int value) {#setColorComponent2-int-}
```
public final void setColorComponent2(int value)
```


색 구성 요소 2를 가져옵니다.

값: 색 구성 요소 2.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setColorComponent3(int value) {#setColorComponent3-int-}
```
public final void setColorComponent3(int value)
```


색 구성 요소 3을 가져옵니다.

값: 색 구성 요소 3.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setColorComponent4(int value) {#setColorComponent4-int-}
```
public final void setColorComponent4(int value)
```


색 구성 요소 4를 가져옵니다.

값: 색 구성 요소 4.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setColorSpace(int value) {#setColorSpace-int-}
```
public final void setColorSpace(int value)
```


색 공간을 가져옵니다.

값: 색 공간입니다.

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

### setOpacity(short value) {#setOpacity-short-}
```
public final void setOpacity(short value)
```


불투명도를 가져옵니다.

값: 불투명도.

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

