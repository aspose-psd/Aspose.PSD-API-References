---
title: "TypeToolInfoResource"
second_title: "Java용 Aspose.PSD API 참조"
description: "타입 도구 정보."
type: docs
weight: 79
url: /ko/java/com.aspose.psd.fileformats.psd.layers.layerresources/typetoolinforesource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource)
```
public class TypeToolInfoResource extends LayerResource
```

타입 도구 정보입니다. PSD 버전이 6.0 미만인 경우.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [TypeToolInfoResource()](#TypeToolInfoResource--) | 새로운 [TypeToolInfoResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/typetoolinforesource) 클래스 인스턴스를 초기화합니다. |
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
| [getAComponent()](#getAComponent--) | 구성 요소를 가져오거나 설정합니다. |
| [getBComponent()](#getBComponent--) | b 구성 요소를 가져오거나 설정합니다. |
| [getCharacterCount()](#getCharacterCount--) | 문자 수를 가져오거나 설정합니다. |
| [getClass()](#getClass--) |  |
| [getColorSpaceValue()](#getColorSpaceValue--) | 색 공간 값을 가져오거나 설정합니다. |
| [getFontVersion()](#getFontVersion--) | 글꼴 버전을 가져오거나 설정합니다. |
| [getFonts()](#getFonts--) | 폰트를 가져오거나 설정합니다. |
| [getFontsCount()](#getFontsCount--) | 폰트 수를 가져옵니다. |
| [getGComponent()](#getGComponent--) | g 구성 요소를 가져오거나 설정합니다. |
| [getHeader_internalized()](#getHeader-internalized--) | 헤더를 가져오거나 설정합니다. |
| [getHorizontalPlacement()](#getHorizontalPlacement--) | 수평 배치를 가져오거나 설정합니다. |
| [getKey()](#getKey--) | 레이어 리소스 키를 가져옵니다. |
| [getLength()](#getLength--) | 레이어 리소스 길이를 바이트 단위로 가져옵니다. |
| [getLineCount()](#getLineCount--) | 라인 수를 가져옵니다. |
| [getLines()](#getLines--) | 라인을 가져오거나 설정합니다. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | 접두사 길이를 가져옵니다. |
| [getPsdVersion()](#getPsdVersion--) | 레이어 리소스에 필요한 최소 PSD 버전을 가져옵니다. |
| [getRComponent()](#getRComponent--) | r 구성 요소를 가져오거나 설정합니다. |
| [getScaleFactor()](#getScaleFactor--) | 스케일 팩터를 가져오거나 설정합니다. |
| [getSelectionEnd()](#getSelectionEnd--) | 선택 끝을 가져오거나 설정합니다. |
| [getSelectionStart()](#getSelectionStart--) | 선택 시작을 가져오거나 설정합니다. |
| [getSignature()](#getSignature--) | 레이어 리소스 서명을 가져옵니다. |
| [getStyles()](#getStyles--) | 폰트 스타일을 가져오거나 설정합니다. |
| [getStylesCount()](#getStylesCount--) | 스타일 수를 가져옵니다. |
| [getTransformMatrix()](#getTransformMatrix--) | 변환 행렬을 가져오거나 설정합니다. |
| [getTypeValue()](#getTypeValue--) | 타입 값을 가져오거나 설정합니다. |
| [getVersion()](#getVersion--) | 버전을 가져오거나 설정합니다. |
| [getVerticalPlacement()](#getVerticalPlacement--) | 수직 배치를 가져오거나 설정합니다. |
| [hashCode()](#hashCode--) |  |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | 리소스가 PSB 전용인지 여부를 결정합니다. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | 이 인스턴스가 리소스 PSB 전용인지 여부를 나타내는 값을 가져옵니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | 지정된 스트림 컨테이너를 저장합니다. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | 사용자 정의 리소스 헤더를 저장합니다. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | 헤더 서명, 식별자 및 길이를 저장합니다. |
| [setAComponent(short value)](#setAComponent-short-) | 구성 요소를 가져오거나 설정합니다. |
| [setBComponent(short value)](#setBComponent-short-) | b 구성 요소를 가져오거나 설정합니다. |
| [setCharacterCount(int value)](#setCharacterCount-int-) | 문자 수를 가져오거나 설정합니다. |
| [setColorDataRaw_internalized(byte[] value)](#setColorDataRaw-internalized-byte---) | 색 데이터 원시값을 가져오거나 설정합니다. |
| [setColorSpaceValue(short value)](#setColorSpaceValue-short-) | 색 공간 값을 가져오거나 설정합니다. |
| [setFontVersion(short value)](#setFontVersion-short-) | 글꼴 버전을 가져오거나 설정합니다. |
| [setFonts(TypeToolFontInfo[] value)](#setFonts-com.aspose.psd.fileformats.psd.layers.layerresources.TypeToolFontInfo---) | 폰트를 가져오거나 설정합니다. |
| [setGComponent(short value)](#setGComponent-short-) | g 구성 요소를 가져오거나 설정합니다. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | 헤더를 가져오거나 설정합니다. |
| [setHorizontalPlacement(int value)](#setHorizontalPlacement-int-) | 수평 배치를 가져오거나 설정합니다. |
| [setLines(TypeToolLineInfo[] value)](#setLines-com.aspose.psd.fileformats.psd.layers.layerresources.TypeToolLineInfo---) | 라인을 가져오거나 설정합니다. |
| [setRComponent(short value)](#setRComponent-short-) | r 구성 요소를 가져오거나 설정합니다. |
| [setScaleFactor(int value)](#setScaleFactor-int-) | 스케일 팩터를 가져오거나 설정합니다. |
| [setSelectionEnd(int value)](#setSelectionEnd-int-) | 선택 끝을 가져오거나 설정합니다. |
| [setSelectionStart(int value)](#setSelectionStart-int-) | 선택 시작을 가져오거나 설정합니다. |
| [setStyles(TypeToolStyleInfo[] value)](#setStyles-com.aspose.psd.fileformats.psd.layers.layerresources.TypeToolStyleInfo---) | 폰트 스타일을 가져오거나 설정합니다. |
| [setTransformMatrix(double[] value)](#setTransformMatrix-double---) | 변환 행렬을 가져오거나 설정합니다. |
| [setTypeValue(short value)](#setTypeValue-short-) | 타입 값을 가져오거나 설정합니다. |
| [setVersion(short value)](#setVersion-short-) | 버전을 가져오거나 설정합니다. |
| [setVerticalPlacement(int value)](#setVerticalPlacement-int-) | 수직 배치를 가져오거나 설정합니다. |
| [toString()](#toString--) | 이 인스턴스를 나타내는 문자열을 반환합니다. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TypeToolInfoResource() {#TypeToolInfoResource--}
```
public TypeToolInfoResource()
```


새로운 [TypeToolInfoResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/typetoolinforesource) 클래스 인스턴스를 초기화합니다.

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
### getAComponent() {#getAComponent--}
```
public final short getAComponent()
```


구성 요소를 가져오거나 설정합니다.

값: 구성 요소.

**Returns:**
short
### getBComponent() {#getBComponent--}
```
public final short getBComponent()
```


b 구성 요소를 가져오거나 설정합니다.

값: b 구성 요소.

**Returns:**
short
### getCharacterCount() {#getCharacterCount--}
```
public final int getCharacterCount()
```


문자 수를 가져오거나 설정합니다.

값: 문자 수.

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorSpaceValue() {#getColorSpaceValue--}
```
public final short getColorSpaceValue()
```


색 공간 값을 가져오거나 설정합니다.

값: 색 공간 값.

**Returns:**
short
### getFontVersion() {#getFontVersion--}
```
public final short getFontVersion()
```


글꼴 버전을 가져오거나 설정합니다.

값: 글꼴 버전.

**Returns:**
short
### getFonts() {#getFonts--}
```
public final TypeToolFontInfo[] getFonts()
```


폰트를 가져오거나 설정합니다.

값: 글꼴.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.TypeToolFontInfo[]
### getFontsCount() {#getFontsCount--}
```
public final short getFontsCount()
```


폰트 수를 가져옵니다.

**Returns:**
short
### getGComponent() {#getGComponent--}
```
public final short getGComponent()
```


g 구성 요소를 가져오거나 설정합니다.

값: g 구성 요소.

**Returns:**
short
### getHeader_internalized() {#getHeader-internalized--}
```
public final PsdHeader getHeader_internalized()
```


헤더를 가져오거나 설정합니다.

값: 헤더.

**Returns:**
com.aspose.internal.fileformats.psd.sections.PsdHeader
### getHorizontalPlacement() {#getHorizontalPlacement--}
```
public final int getHorizontalPlacement()
```


수평 배치를 가져오거나 설정합니다.

값: 수평 배치.

**Returns:**
int
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
### getLineCount() {#getLineCount--}
```
public final short getLineCount()
```


라인 수를 가져옵니다.

값: 라인 수.

**Returns:**
short
### getLines() {#getLines--}
```
public final TypeToolLineInfo[] getLines()
```


라인을 가져오거나 설정합니다.

값: 라인.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.TypeToolLineInfo[]
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
### getRComponent() {#getRComponent--}
```
public final short getRComponent()
```


r 구성 요소를 가져오거나 설정합니다.

값: r 구성 요소.

**Returns:**
short
### getScaleFactor() {#getScaleFactor--}
```
public final int getScaleFactor()
```


스케일 팩터를 가져오거나 설정합니다.

값: 스케일 팩터.

**Returns:**
int
### getSelectionEnd() {#getSelectionEnd--}
```
public final int getSelectionEnd()
```


선택 끝을 가져오거나 설정합니다.

값: 선택 끝.

**Returns:**
int
### getSelectionStart() {#getSelectionStart--}
```
public final int getSelectionStart()
```


선택 시작을 가져오거나 설정합니다.

값: 선택 시작.

**Returns:**
int
### getSignature() {#getSignature--}
```
public int getSignature()
```


레이어 리소스 서명을 가져옵니다.

**Returns:**
int
### getStyles() {#getStyles--}
```
public final TypeToolStyleInfo[] getStyles()
```


폰트 스타일을 가져오거나 설정합니다.

값: 글꼴 스타일.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.TypeToolStyleInfo[]
### getStylesCount() {#getStylesCount--}
```
public final short getStylesCount()
```


스타일 수를 가져옵니다.

**Returns:**
short
### getTransformMatrix() {#getTransformMatrix--}
```
public final double[] getTransformMatrix()
```


변환 행렬을 가져오거나 설정합니다.

값: 변환 행렬.

**Returns:**
double[]
### getTypeValue() {#getTypeValue--}
```
public final short getTypeValue()
```


타입 값을 가져오거나 설정합니다.

값: 유형 값.

**Returns:**
short
### getVersion() {#getVersion--}
```
public final short getVersion()
```


버전을 가져오거나 설정합니다.

값: 버전.

**Returns:**
short
### getVerticalPlacement() {#getVerticalPlacement--}
```
public final int getVerticalPlacement()
```


수직 배치를 가져오거나 설정합니다.

값: 수직 배치.

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


지정된 스트림 컨테이너를 저장합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | 스트림 컨테이너입니다. |
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

### setAComponent(short value) {#setAComponent-short-}
```
public final void setAComponent(short value)
```


구성 요소를 가져오거나 설정합니다.

값: 구성 요소.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | short |  |

### setBComponent(short value) {#setBComponent-short-}
```
public final void setBComponent(short value)
```


b 구성 요소를 가져오거나 설정합니다.

값: b 구성 요소.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | short |  |

### setCharacterCount(int value) {#setCharacterCount-int-}
```
public final void setCharacterCount(int value)
```


문자 수를 가져오거나 설정합니다.

값: 문자 수.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setColorDataRaw_internalized(byte[] value) {#setColorDataRaw-internalized-byte---}
```
public final void setColorDataRaw_internalized(byte[] value)
```


색 데이터 원시값을 가져오거나 설정합니다.

값: 색 데이터 원시.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | byte[] |  |

### setColorSpaceValue(short value) {#setColorSpaceValue-short-}
```
public final void setColorSpaceValue(short value)
```


색 공간 값을 가져오거나 설정합니다.

값: 색 공간 값.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | short |  |

### setFontVersion(short value) {#setFontVersion-short-}
```
public final void setFontVersion(short value)
```


글꼴 버전을 가져오거나 설정합니다.

값: 글꼴 버전.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | short |  |

### setFonts(TypeToolFontInfo[] value) {#setFonts-com.aspose.psd.fileformats.psd.layers.layerresources.TypeToolFontInfo---}
```
public final void setFonts(TypeToolFontInfo[] value)
```


폰트를 가져오거나 설정합니다.

값: 글꼴.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [TypeToolFontInfo\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/typetoolfontinfo) |  |

### setGComponent(short value) {#setGComponent-short-}
```
public final void setGComponent(short value)
```


g 구성 요소를 가져오거나 설정합니다.

값: g 구성 요소.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | short |  |

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

### setHorizontalPlacement(int value) {#setHorizontalPlacement-int-}
```
public final void setHorizontalPlacement(int value)
```


수평 배치를 가져오거나 설정합니다.

값: 수평 배치.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setLines(TypeToolLineInfo[] value) {#setLines-com.aspose.psd.fileformats.psd.layers.layerresources.TypeToolLineInfo---}
```
public final void setLines(TypeToolLineInfo[] value)
```


라인을 가져오거나 설정합니다.

값: 라인.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [TypeToolLineInfo\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/typetoollineinfo) |  |

### setRComponent(short value) {#setRComponent-short-}
```
public final void setRComponent(short value)
```


r 구성 요소를 가져오거나 설정합니다.

값: r 구성 요소.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | short |  |

### setScaleFactor(int value) {#setScaleFactor-int-}
```
public final void setScaleFactor(int value)
```


스케일 팩터를 가져오거나 설정합니다.

값: 스케일 팩터.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setSelectionEnd(int value) {#setSelectionEnd-int-}
```
public final void setSelectionEnd(int value)
```


선택 끝을 가져오거나 설정합니다.

값: 선택 끝.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setSelectionStart(int value) {#setSelectionStart-int-}
```
public final void setSelectionStart(int value)
```


선택 시작을 가져오거나 설정합니다.

값: 선택 시작.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setStyles(TypeToolStyleInfo[] value) {#setStyles-com.aspose.psd.fileformats.psd.layers.layerresources.TypeToolStyleInfo---}
```
public final void setStyles(TypeToolStyleInfo[] value)
```


폰트 스타일을 가져오거나 설정합니다.

값: 글꼴 스타일.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [TypeToolStyleInfo\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/typetoolstyleinfo) |  |

### setTransformMatrix(double[] value) {#setTransformMatrix-double---}
```
public final void setTransformMatrix(double[] value)
```


변환 행렬을 가져오거나 설정합니다.

값: 변환 행렬.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double[] |  |

### setTypeValue(short value) {#setTypeValue-short-}
```
public final void setTypeValue(short value)
```


타입 값을 가져오거나 설정합니다.

값: 유형 값.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | short |  |

### setVersion(short value) {#setVersion-short-}
```
public final void setVersion(short value)
```


버전을 가져오거나 설정합니다.

값: 버전.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | short |  |

### setVerticalPlacement(int value) {#setVerticalPlacement-int-}
```
public final void setVerticalPlacement(int value)
```


수직 배치를 가져오거나 설정합니다.

값: 수직 배치.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

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

