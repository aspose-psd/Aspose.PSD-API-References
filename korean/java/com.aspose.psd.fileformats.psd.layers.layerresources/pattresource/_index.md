---
title: "PattResource"
second_title: "Java용 Aspose.PSD API 참조"
description: "PattResource 클래스."
type: docs
weight: 66
url: /ko/java/com.aspose.psd.fileformats.psd.layers.layerresources/pattresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource)
```
public class PattResource extends LayerResource
```

클래스 PattResource. 패턴 데이터를 포함하는 리소스
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [PattResource()](#PattResource--) | 새로운 [PattResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresource) 클래스 인스턴스를 초기화합니다. |
| [PattResource(int key, PattResourceData[] patterns)](#PattResource-int-com.aspose.psd.fileformats.psd.layers.layerresources.PattResourceData---) | 새로운 [PattResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresource) 클래스 인스턴스를 초기화합니다. |
## 필드

| 필드 | 설명 |
| --- | --- |
| [PsbHeaderVersion_internalized](#PsbHeaderVersion-internalized) | PSB 헤더 버전입니다. |
| [PsbResourceSignature](#PsbResourceSignature) | PSB 전용 리소스 서명입니다. |
| [PsdHeaderVersion_internalized](#PsdHeaderVersion-internalized) | PSD 헤더 버전입니다. |
| [ResourceSignature](#ResourceSignature) | 공통 리소스 서명입니다. |
| [TypeToolKey](#TypeToolKey) | 'Patt' 유형 툴 정보 키 (8비트용)입니다. |
| [TypeToolKey2](#TypeToolKey2) | 'Pat2' 유형 툴 정보 키 (16비트용)입니다. |
| [TypeToolKey3](#TypeToolKey3) | 'Pat3' 유형 툴 정보 키 (32비트용)입니다. |
| [ventureLicense_internalized](#ventureLicense-internalized) | 벤처 라이선스. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [addNewPattResourceData_internalized(PattResource resource)](#addNewPattResourceData-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.PattResource-) | Patt 리소스를 기본 데이터로 업데이트합니다. |
| [checkAndSetIfResourceIsPsbSpecific_internalized(int key)](#checkAndSetIfResourceIsPsbSpecific-internalized-int-) | 리소스가 PSB 전용인지 확인하고 설정합니다. |
| [createDefaultNotEmptyResource_internalized(int bitDepth)](#createDefaultNotEmptyResource-internalized-int-) | 비어 있지 않은 기본 리소스를 생성합니다. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getHeader_internalized()](#getHeader-internalized--) | 헤더를 가져오거나 설정합니다. |
| [getKey()](#getKey--) | 레이어 리소스 키를 가져옵니다. |
| [getLength()](#getLength--) | 레이어 리소스 길이를 바이트 단위로 가져옵니다. |
| [getPatterns()](#getPatterns--) | 패턴 데이터를 가져오거나 설정합니다; |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | 접두사 길이를 가져옵니다. |
| [getPsdVersion()](#getPsdVersion--) | 레이어 리소스에 필요한 최소 PSD 버전을 가져옵니다. |
| [getSignature()](#getSignature--) | 레이어 리소스 서명을 가져옵니다. |
| [hashCode()](#hashCode--) |  |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | 리소스가 PSB 전용인지 여부를 결정합니다. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | 이 인스턴스가 리소스 PSB 전용인지 여부를 나타내는 값을 가져옵니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | 리소스 블록 데이터를 저장합니다. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | 사용자 정의 리소스 헤더를 저장합니다. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | 헤더 서명, 식별자 및 길이를 저장합니다. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | 헤더를 가져오거나 설정합니다. |
| [setPatterns(PattResourceData[] value)](#setPatterns-com.aspose.psd.fileformats.psd.layers.layerresources.PattResourceData---) | 패턴 데이터를 가져오거나 설정합니다; |
| [toString()](#toString--) | 이 인스턴스를 나타내는 문자열을 반환합니다. |
| [updateOrAddPattern_internalized(IPatternFillSettings patternSettings)](#updateOrAddPattern-internalized-com.aspose.psd.fileformats.psd.layers.fillsettings.IPatternFillSettings-) | 패턴 데이터 항목을 검색하고 새 값으로 업데이트합니다. 그렇지 않으면 새 항목을 배열 끝에 추가합니다. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PattResource() {#PattResource--}
```
public PattResource()
```


새로운 [PattResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresource) 클래스 인스턴스를 초기화합니다.

### PattResource(int key, PattResourceData[] patterns) {#PattResource-int-com.aspose.psd.fileformats.psd.layers.layerresources.PattResourceData---}
```
public PattResource(int key, PattResourceData[] patterns)
```


새로운 [PattResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresource) 클래스 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 키 | int | 리소스 유형 키입니다. |
| patterns | [PattResourceData\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata) | 패턴 데이터입니다. |

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


'Patt' 유형 툴 정보 키 (8비트용)입니다.

### TypeToolKey2 {#TypeToolKey2}
```
public static final int TypeToolKey2
```


'Pat2' 유형 툴 정보 키 (16비트용)입니다.

### TypeToolKey3 {#TypeToolKey3}
```
public static final int TypeToolKey3
```


'Pat3' 유형 툴 정보 키 (32비트용)입니다.

### ventureLicense_internalized {#ventureLicense-internalized}
```
public Object ventureLicense_internalized
```


벤처 라이선스.

### addNewPattResourceData_internalized(PattResource resource) {#addNewPattResourceData-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.PattResource-}
```
public static void addNewPattResourceData_internalized(PattResource resource)
```


Patt 리소스를 기본 데이터로 업데이트합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| resource | [PattResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresource) | 리소스. |

### checkAndSetIfResourceIsPsbSpecific_internalized(int key) {#checkAndSetIfResourceIsPsbSpecific-internalized-int-}
```
public final void checkAndSetIfResourceIsPsbSpecific_internalized(int key)
```


리소스가 PSB 전용인지 확인하고 설정합니다. 현재 일부 리소스는 인식되지 않지만, 저장 시 동작이 변경되는 PSB 전용 리소스 전체 목록이 있습니다. 따라서 최소한 UnknownResource에서 이를 확인해야 합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 키 | int | 키. |

### createDefaultNotEmptyResource_internalized(int bitDepth) {#createDefaultNotEmptyResource-internalized-int-}
```
public static PattResource createDefaultNotEmptyResource_internalized(int bitDepth)
```


비어 있지 않은 기본 리소스를 생성합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| bitDepth | int |  |

**Returns:**
[PattResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresource) - Created [PattResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresource)
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
### getPatterns() {#getPatterns--}
```
public final PattResourceData[] getPatterns()
```


패턴 데이터를 가져오거나 설정합니다;

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.PattResourceData[]
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


리소스 블록 데이터를 저장합니다.

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

### setPatterns(PattResourceData[] value) {#setPatterns-com.aspose.psd.fileformats.psd.layers.layerresources.PattResourceData---}
```
public final void setPatterns(PattResourceData[] value)
```


패턴 데이터를 가져오거나 설정합니다;

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [PattResourceData\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata) |  |

### toString() {#toString--}
```
public String toString()
```


이 인스턴스를 나타내는 문자열을 반환합니다.

**Returns:**
java.lang.String - 이 인스턴스를 나타내는 문자열.
### updateOrAddPattern_internalized(IPatternFillSettings patternSettings) {#updateOrAddPattern-internalized-com.aspose.psd.fileformats.psd.layers.fillsettings.IPatternFillSettings-}
```
public final void updateOrAddPattern_internalized(IPatternFillSettings patternSettings)
```


패턴 데이터 항목을 검색하고 새 값으로 업데이트합니다. 그렇지 않으면 새 항목을 배열 끝에 추가합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| patternSettings | [IPatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/ipatternfillsettings) | 패턴 항목을 업데이트하기 위한 패턴 설정 객체입니다. |

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

