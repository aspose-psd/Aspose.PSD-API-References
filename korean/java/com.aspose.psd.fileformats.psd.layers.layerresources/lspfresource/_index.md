---
title: "LspfResource"
second_title: "Java용 Aspose.PSD API 참조"
description: "레이어 보호 설정"
type: docs
weight: 57
url: /ko/java/com.aspose.psd.fileformats.psd.layers.layerresources/lspfresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource)
```
public class LspfResource extends LayerResource
```

레이어 보호 설정
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [LspfResource(byte[] data)](#LspfResource-byte---) | [LspfResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/lspfresource) 클래스의 새 인스턴스를 초기화합니다. |
| [LspfResource(boolean isTransparencyProtected, boolean isCompositeProtected, boolean isPositionProtected)](#LspfResource-boolean-boolean-boolean-) | [LspfResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/lspfresource) 클래스의 새 인스턴스를 초기화합니다. |
| [LspfResource()](#LspfResource--) | [LspfResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/lspfresource) 클래스의 새 인스턴스를 초기화합니다. |
## 필드

| 필드 | 설명 |
| --- | --- |
| [PsbHeaderVersion_internalized](#PsbHeaderVersion-internalized) | PSB 헤더 버전입니다. |
| [PsbResourceSignature](#PsbResourceSignature) | PSB 전용 리소스 서명입니다. |
| [PsdHeaderVersion_internalized](#PsdHeaderVersion-internalized) | PSD 헤더 버전입니다. |
| [ResourceSignature](#ResourceSignature) | 공통 리소스 서명입니다. |
| [TypeToolKey](#TypeToolKey) | 타입 툴 정보 키 1819504742 |
| [ventureLicense_internalized](#ventureLicense-internalized) | 벤처 라이선스. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [checkAndSetIfResourceIsPsbSpecific_internalized(int key)](#checkAndSetIfResourceIsPsbSpecific-internalized-int-) | 리소스가 PSB 전용인지 확인하고 설정합니다. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getHeader_internalized()](#getHeader-internalized--) | 헤더를 가져오거나 설정합니다. |
| [getKey()](#getKey--) | 레이어 리소스 키를 가져옵니다. |
| [getLength()](#getLength--) | 레이어 리소스 길이를 바이트 단위로 가져옵니다. |
| [getLockType()](#getLockType--) | 잠금의 유형을 가져오거나 설정합니다. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | 접두사 길이를 가져옵니다. |
| [getPsdVersion()](#getPsdVersion--) | 레이어 리소스에 필요한 최소 PSD 버전을 가져옵니다. |
| [getSignature()](#getSignature--) | 레이어 리소스 서명을 가져옵니다. |
| [hashCode()](#hashCode--) |  |
| [isCompositeProtected()](#isCompositeProtected--) | 이 인스턴스가 복합 보호되는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [isPositionProtected()](#isPositionProtected--) | 이 인스턴스가 위치 보호되는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | 리소스가 PSB 전용인지 여부를 결정합니다. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | 이 인스턴스가 리소스 PSB 전용인지 여부를 나타내는 값을 가져옵니다. |
| [isTransparencyProtected()](#isTransparencyProtected--) | 이 인스턴스가 투명도 보호되는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | 지정된 스트림 컨테이너에 리소스를 저장합니다. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | 사용자 정의 리소스 헤더를 저장합니다. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | 헤더 서명, 식별자 및 길이를 저장합니다. |
| [setCompositeProtected(boolean value)](#setCompositeProtected-boolean-) | 이 인스턴스가 복합 보호되는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | 헤더를 가져오거나 설정합니다. |
| [setLockType(int value)](#setLockType-int-) | 잠금의 유형을 가져오거나 설정합니다. |
| [setPositionProtected(boolean value)](#setPositionProtected-boolean-) | 이 인스턴스가 위치 보호되는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [setTransparencyProtected(boolean value)](#setTransparencyProtected-boolean-) | 이 인스턴스가 투명도 보호되는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [toString()](#toString--) | 이 인스턴스를 나타내는 문자열을 반환합니다. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LspfResource(byte[] data) {#LspfResource-byte---}
```
public LspfResource(byte[] data)
```


[LspfResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/lspfresource) 클래스의 새 인스턴스를 초기화합니다. 사용자 지정 또는 알 수 없는 값과 함께

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 데이터 | byte[] | 리소스 데이터. |

### LspfResource(boolean isTransparencyProtected, boolean isCompositeProtected, boolean isPositionProtected) {#LspfResource-boolean-boolean-boolean-}
```
public LspfResource(boolean isTransparencyProtected, boolean isCompositeProtected, boolean isPositionProtected)
```


[LspfResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/lspfresource) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| isTransparencyProtected | boolean | true 로 설정된 경우 [is transparency protected]. |
| isCompositeProtected | boolean | true 로 설정된 경우 [is composite protected]. |
| isPositionProtected | boolean | true 로 설정된 경우 [is position protected]. |

### LspfResource() {#LspfResource--}
```
public LspfResource()
```


[LspfResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/lspfresource) 클래스의 새 인스턴스를 초기화합니다.

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


타입 툴 정보 키 1819504742

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
### getLockType() {#getLockType--}
```
public final int getLockType()
```


잠금의 유형을 가져오거나 설정합니다.

값: 잠금의 유형.

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
### isCompositeProtected() {#isCompositeProtected--}
```
public final boolean isCompositeProtected()
```


이 인스턴스가 복합 보호되는지 여부를 나타내는 값을 가져오거나 설정합니다.

값: 이 인스턴스가 복합 보호되는 경우 true; 그렇지 않으면 false.

**Returns:**
boolean
### isPositionProtected() {#isPositionProtected--}
```
public final boolean isPositionProtected()
```


이 인스턴스가 위치 보호되는지 여부를 나타내는 값을 가져오거나 설정합니다.

값: 이 인스턴스가 위치 보호되는 경우 true; 그렇지 않으면 false.

**Returns:**
boolean
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
### isTransparencyProtected() {#isTransparencyProtected--}
```
public final boolean isTransparencyProtected()
```


이 인스턴스가 투명도 보호되는지 여부를 나타내는 값을 가져오거나 설정합니다.

값: 이 인스턴스가 투명도 보호되는 경우 true; 그렇지 않으면 false.

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

### setCompositeProtected(boolean value) {#setCompositeProtected-boolean-}
```
public final void setCompositeProtected(boolean value)
```


이 인스턴스가 복합 보호되는지 여부를 나타내는 값을 가져오거나 설정합니다.

값: 이 인스턴스가 복합 보호되는 경우 true; 그렇지 않으면 false.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

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

### setLockType(int value) {#setLockType-int-}
```
public final void setLockType(int value)
```


잠금의 유형을 가져오거나 설정합니다.

값: 잠금의 유형.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setPositionProtected(boolean value) {#setPositionProtected-boolean-}
```
public final void setPositionProtected(boolean value)
```


이 인스턴스가 위치 보호되는지 여부를 나타내는 값을 가져오거나 설정합니다.

값: 이 인스턴스가 위치 보호되는 경우 true; 그렇지 않으면 false.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setTransparencyProtected(boolean value) {#setTransparencyProtected-boolean-}
```
public final void setTransparencyProtected(boolean value)
```


이 인스턴스가 투명도 보호되는지 여부를 나타내는 값을 가져오거나 설정합니다.

값: 이 인스턴스가 투명도 보호되는 경우 true; 그렇지 않으면 false.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

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

