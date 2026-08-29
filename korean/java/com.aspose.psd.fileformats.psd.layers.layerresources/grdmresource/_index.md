---
title: "GrdmResource"
second_title: "Java용 Aspose.PSD API 참조"
description: "클래스 GrdmResource."
type: docs
weight: 35
url: /ko/java/com.aspose.psd.fileformats.psd.layers.layerresources/grdmresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.AdjustmentLayerResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource)
```
public class GrdmResource extends AdjustmentLayerResource
```

클래스 GrdmResource. Gradient-Map 레이어에 대한 정보를 포함합니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [GrdmResource()](#GrdmResource--) |  |
| [GrdmResource(int psdVersion)](#GrdmResource-int-) | 새 인스턴스를 초기화합니다 [GrdmResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/grdmresource) 클래스. |
## 필드

| 필드 | 설명 |
| --- | --- |
| [DefaultScale_internalized](#DefaultScale-internalized) | 기본 스케일. |
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
| [getColorModel()](#getColorModel--) | 색상 모델. |
| [getColorPoints()](#getColorPoints--) | 색상 포인트를 가져오거나 설정합니다. |
| [getData()](#getData--) | 데이터를 가져오거나 설정합니다. |
| [getDither()](#getDither--) | 그라디언트가 디더링되었는지 여부. |
| [getExpansionCount()](#getExpansionCount--) | 확장 수 ( = Photoshop 6.0에서는 2). |
| [getGradientLength_internalized()](#getGradientLength-internalized--) | 길이(= Photoshop 6.0에서는 32) 무엇을 담당하는지에 대한 정보가 없습니다. |
| [getGradientMode()](#getGradientMode--) | 이 그라디언트의 모드는 'Gradient Type' = 'Solid/Noise' (0/1) 를 결정합니다. |
| [getGradientName()](#getGradientName--) | 그라디언트 이름: 유니코드 문자열, 패딩됨. |
| [getHeader_internalized()](#getHeader-internalized--) | 헤더를 가져오거나 설정합니다. |
| [getInterpolation()](#getInterpolation--) | 보간. |
| [getInterpolationMethod()](#getInterpolationMethod--) | 그라디언트에 대한 보간 방법을 가져오거나 설정합니다. |
| [getKey()](#getKey--) | 레이어 리소스 키를 가져옵니다. |
| [getLength()](#getLength--) | 레이어 리소스 길이를 바이트 단위로 가져옵니다. |
| [getMaximumColor()](#getMaximumColor--) | PixelDataFormat.Rgba64Bpp 형식의 최대 색상. |
| [getMinimumColor()](#getMinimumColor--) | PixelDataFormat.Rgba64Bpp 형식의 최소 색상. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | 접두사 길이를 가져옵니다. |
| [getPsdVersion()](#getPsdVersion--) | 이 리소스에 필요한 최소 PSD 버전을 가져옵니다. |
| [getReverse()](#getReverse--) | 그라디언트가 반전되었습니까. |
| [getRndNumberSeed()](#getRndNumberSeed--) | 노이즈 그라디언트의 색상을 생성하는 데 사용되는 난수 시드. |
| [getRoughness()](#getRoughness--) | 거칠기 계수 'Gradient type' = 'Noise'인 경우, 'Roughness'를 (0 - 2048)으로 할당할 수 있습니다. |
| [getShowTransparency()](#getShowTransparency--) | 투명도 표시 플래그 'Gradient type' = 'Noise'인 경우, 'Add transparency'를 true로 설정할 수 있습니다. |
| [getSignature()](#getSignature--) | 레이어 리소스 서명을 가져옵니다. |
| [getTransparencyPoints()](#getTransparencyPoints--) | 투명도 포인트를 가져오거나 설정합니다. |
| [getUseVectorColor()](#getUseVectorColor--) | 벡터 색상을 사용하기 위한 플래그. |
| [hashCode()](#hashCode--) |  |
| [initGradientLength_internalized(short value)](#initGradientLength-internalized-short-) | 그라디언트의 길이를 초기화합니다. |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | 리소스가 PSB 전용인지 여부를 결정합니다. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | 이 인스턴스가 리소스 PSB 전용인지 여부를 나타내는 값을 가져옵니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | 리소스 데이터를 지정된 스트림 컨테이너에 저장합니다. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | 사용자 정의 리소스 헤더를 저장합니다. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | 헤더 서명, 식별자 및 길이를 저장합니다. |
| [setColorModel(short value)](#setColorModel-short-) | 색상 모델. |
| [setColorPoints(IGradientColorPoint[] value)](#setColorPoints-com.aspose.psd.fileformats.psd.layers.IGradientColorPoint---) | 색상 포인트를 가져오거나 설정합니다. |
| [setDither(boolean value)](#setDither-boolean-) | 그라디언트가 디더링되었는지 여부. |
| [setExpansionCount(short value)](#setExpansionCount-short-) | 확장 수 ( = Photoshop 6.0에서는 2). |
| [setGradientMode(int value)](#setGradientMode-int-) | 이 그라디언트의 모드는 'Gradient Type' = 'Solid/Noise' (0/1) 를 결정합니다. |
| [setGradientName(String value)](#setGradientName-java.lang.String-) | 그라디언트 이름: 유니코드 문자열, 패딩됨. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | 헤더를 가져오거나 설정합니다. |
| [setInterpolation(short value)](#setInterpolation-short-) | 보간. |
| [setInterpolationMethod(long value)](#setInterpolationMethod-long-) | 그라디언트에 대한 보간 방법을 가져오거나 설정합니다. |
| [setMaximumColor(RawColor value)](#setMaximumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | PixelDataFormat.Rgba64Bpp 형식의 최대 색상. |
| [setMinimumColor(RawColor value)](#setMinimumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | PixelDataFormat.Rgba64Bpp 형식의 최소 색상. |
| [setReverse(boolean value)](#setReverse-boolean-) | 그라디언트가 반전되었습니까. |
| [setRndNumberSeed(int value)](#setRndNumberSeed-int-) | 노이즈 그라디언트의 색상을 생성하는 데 사용되는 난수 시드. |
| [setRoughness(int value)](#setRoughness-int-) | 거칠기 계수 'Gradient type' = 'Noise'인 경우, 'Roughness'를 (0 - 2048)으로 할당할 수 있습니다. |
| [setShowTransparency(short value)](#setShowTransparency-short-) | 투명도 표시 플래그 'Gradient type' = 'Noise'인 경우, 'Add transparency'를 true로 설정할 수 있습니다. |
| [setTransparencyPoints(IGradientTransparencyPoint[] value)](#setTransparencyPoints-com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint---) | 투명도 포인트를 가져오거나 설정합니다. |
| [setUseVectorColor(short value)](#setUseVectorColor-short-) | 벡터 색상을 사용하기 위한 플래그. |
| [toString()](#toString--) | 이 인스턴스를 나타내는 문자열을 반환합니다. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GrdmResource() {#GrdmResource--}
```
public GrdmResource()
```


### GrdmResource(int psdVersion) {#GrdmResource-int-}
```
public GrdmResource(int psdVersion)
```


새 인스턴스를 초기화합니다 [GrdmResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/grdmresource) 클래스.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| psdVersion | int | 리소스의 PSD 버전입니다. |

### DefaultScale_internalized {#DefaultScale-internalized}
```
public static final int DefaultScale_internalized
```


기본 스케일.

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
### getColorModel() {#getColorModel--}
```
public final short getColorModel()
```


컬러 모델. 'Gradient type' = 'Noise'인 경우, 'Color Model'을 RGB/SHB/LAB (3/4/6)으로 할당할 수 있습니다.

**Returns:**
short
### getColorPoints() {#getColorPoints--}
```
public final IGradientColorPoint[] getColorPoints()
```


색상 포인트를 가져오거나 설정합니다.

값: 색상 포인트.

**Returns:**
com.aspose.psd.fileformats.psd.layers.IGradientColorPoint[]
### getData() {#getData--}
```
public final byte[] getData()
```


데이터를 가져오거나 설정합니다.

값: 데이터.

**Returns:**
byte[]
### getDither() {#getDither--}
```
public final boolean getDither()
```


그라디언트가 디더링되었는지 여부.

**Returns:**
boolean
### getExpansionCount() {#getExpansionCount--}
```
public final short getExpansionCount()
```


확장 수 ( = Photoshop 6.0에서는 2).

**Returns:**
short
### getGradientLength_internalized() {#getGradientLength-internalized--}
```
public final short getGradientLength_internalized()
```


길이(= Photoshop 6.0에서는 32) 무엇을 담당하는지에 대한 정보가 없습니다.

**Returns:**
short
### getGradientMode() {#getGradientMode--}
```
public final int getGradientMode()
```


이 그라디언트의 모드는 'Gradient Type' = 'Solid/Noise' (0/1) 를 결정합니다.

**Returns:**
int
### getGradientName() {#getGradientName--}
```
public final String getGradientName()
```


그라디언트 이름: 유니코드 문자열, 패딩됨.

**Returns:**
java.lang.String
### getHeader_internalized() {#getHeader-internalized--}
```
public final PsdHeader getHeader_internalized()
```


헤더를 가져오거나 설정합니다.

값: 헤더.

**Returns:**
com.aspose.internal.fileformats.psd.sections.PsdHeader
### getInterpolation() {#getInterpolation--}
```
public final short getInterpolation()
```


보간. 'Gradient Type' = 'Solid' (GradientMode = 0)인 경우, 부드러움을 결정합니다.

**Returns:**
short
### getInterpolationMethod() {#getInterpolationMethod--}
```
public final long getInterpolationMethod()
```


그라디언트에 대한 보간 방법을 가져오거나 설정합니다.

**Returns:**
long
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
### getMaximumColor() {#getMaximumColor--}
```
public final RawColor getMaximumColor()
```


PixelDataFormat.Rgba64Bpp 형식의 최대 색상. 색상은 ARGB 채널을 가지며, 각 채널은 16비트입니다.

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor)
### getMinimumColor() {#getMinimumColor--}
```
public final RawColor getMinimumColor()
```


PixelDataFormat.Rgba64Bpp 형식의 최소 색상. 색상은 ARGB 채널을 가지며, 각 채널은 16비트입니다.

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor)
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


이 리소스에 필요한 최소 PSD 버전을 가져옵니다. 보간 방법이 명시적으로 저장될 때 버전 3이 필요합니다.

**Returns:**
int
### getReverse() {#getReverse--}
```
public final boolean getReverse()
```


그라디언트가 반전되었습니까.

**Returns:**
boolean
### getRndNumberSeed() {#getRndNumberSeed--}
```
public final int getRndNumberSeed()
```


노이즈 그라디언트의 색상을 생성하는 데 사용되는 난수 시드.

**Returns:**
int
### getRoughness() {#getRoughness--}
```
public final int getRoughness()
```


거칠기 계수 'Gradient type' = 'Noise'인 경우, 'Roughness'를 (0 - 2048)으로 할당할 수 있습니다.

**Returns:**
int
### getShowTransparency() {#getShowTransparency--}
```
public final short getShowTransparency()
```


투명도 표시 플래그 'Gradient type' = 'Noise'인 경우, 'Add transparency'를 true로 설정할 수 있습니다.

**Returns:**
short
### getSignature() {#getSignature--}
```
public int getSignature()
```


레이어 리소스 서명을 가져옵니다.

**Returns:**
int
### getTransparencyPoints() {#getTransparencyPoints--}
```
public final IGradientTransparencyPoint[] getTransparencyPoints()
```


투명도 포인트를 가져오거나 설정합니다.

값: 투명도 포인트.

**Returns:**
com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint[]
### getUseVectorColor() {#getUseVectorColor--}
```
public final short getUseVectorColor()
```


벡터 색상을 사용하기 위한 플래그.

**Returns:**
short
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### initGradientLength_internalized(short value) {#initGradientLength-internalized-short-}
```
public final void initGradientLength_internalized(short value)
```


그라디언트의 길이를 초기화합니다. GradientLength는 읽기 전용이므로 한 번만 할당할 수 있습니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | short | 값. |

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


리소스 데이터를 지정된 스트림 컨테이너에 저장합니다.

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

### setColorModel(short value) {#setColorModel-short-}
```
public final void setColorModel(short value)
```


컬러 모델. 'Gradient type' = 'Noise'인 경우, 'Color Model'을 RGB/SHB/LAB (3/4/6)으로 할당할 수 있습니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | short |  |

### setColorPoints(IGradientColorPoint[] value) {#setColorPoints-com.aspose.psd.fileformats.psd.layers.IGradientColorPoint---}
```
public final void setColorPoints(IGradientColorPoint[] value)
```


색상 포인트를 가져오거나 설정합니다.

값: 색상 포인트.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [IGradientColorPoint\[\]](../../com.aspose.psd.fileformats.psd.layers/igradientcolorpoint) |  |

### setDither(boolean value) {#setDither-boolean-}
```
public final void setDither(boolean value)
```


그라디언트가 디더링되었는지 여부.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setExpansionCount(short value) {#setExpansionCount-short-}
```
public final void setExpansionCount(short value)
```


확장 수 ( = Photoshop 6.0에서는 2).

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | short |  |

### setGradientMode(int value) {#setGradientMode-int-}
```
public final void setGradientMode(int value)
```


이 그라디언트의 모드는 'Gradient Type' = 'Solid/Noise' (0/1) 를 결정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setGradientName(String value) {#setGradientName-java.lang.String-}
```
public final void setGradientName(String value)
```


그라디언트 이름: 유니코드 문자열, 패딩됨.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

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

### setInterpolation(short value) {#setInterpolation-short-}
```
public final void setInterpolation(short value)
```


보간. 'Gradient Type' = 'Solid' (GradientMode = 0)인 경우, 부드러움을 결정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | short |  |

### setInterpolationMethod(long value) {#setInterpolationMethod-long-}
```
public final void setInterpolationMethod(long value)
```


그라디언트에 대한 보간 방법을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | long |  |

### setMaximumColor(RawColor value) {#setMaximumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public final void setMaximumColor(RawColor value)
```


PixelDataFormat.Rgba64Bpp 형식의 최대 색상. 색상은 ARGB 채널을 가지며, 각 채널은 16비트입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) |  |

### setMinimumColor(RawColor value) {#setMinimumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public final void setMinimumColor(RawColor value)
```


PixelDataFormat.Rgba64Bpp 형식의 최소 색상. 색상은 ARGB 채널을 가지며, 각 채널은 16비트입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) |  |

### setReverse(boolean value) {#setReverse-boolean-}
```
public final void setReverse(boolean value)
```


그라디언트가 반전되었습니까.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setRndNumberSeed(int value) {#setRndNumberSeed-int-}
```
public final void setRndNumberSeed(int value)
```


노이즈 그라디언트의 색상을 생성하는 데 사용되는 난수 시드.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setRoughness(int value) {#setRoughness-int-}
```
public final void setRoughness(int value)
```


거칠기 계수 'Gradient type' = 'Noise'인 경우, 'Roughness'를 (0 - 2048)으로 할당할 수 있습니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setShowTransparency(short value) {#setShowTransparency-short-}
```
public final void setShowTransparency(short value)
```


투명도 표시 플래그 'Gradient type' = 'Noise'인 경우, 'Add transparency'를 true로 설정할 수 있습니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | short |  |

### setTransparencyPoints(IGradientTransparencyPoint[] value) {#setTransparencyPoints-com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint---}
```
public final void setTransparencyPoints(IGradientTransparencyPoint[] value)
```


투명도 포인트를 가져오거나 설정합니다.

값: 투명도 포인트.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [IGradientTransparencyPoint\[\]](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint) |  |

### setUseVectorColor(short value) {#setUseVectorColor-short-}
```
public final void setUseVectorColor(short value)
```


벡터 색상을 사용하기 위한 플래그.

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

