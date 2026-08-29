---
title: "GdFlResource"
second_title: "Java용 Aspose.PSD API 참조"
description: "GdFlResource 클래스."
type: docs
weight: 33
url: /ko/java/com.aspose.psd.fileformats.psd.layers.layerresources/gdflresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.FillLayerResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/filllayerresource)
```
public class GdFlResource extends FillLayerResource
```

GdFlResource 클래스. 이 리소스는 클리핑된 요소의 블렌딩에 대한 정보를 포함합니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [GdFlResource()](#GdFlResource--) | 새 인스턴스를 초기화합니다 [.GdFlResource](../../null/\#GdFlResource) 클래스. |
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
| [addUnknownStructure_internalized(OSTypeStructure structure)](#addUnknownStructure-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-) | 알 수 없는 구조를 추가합니다. |
| [checkAndSetIfResourceIsPsbSpecific_internalized(int key)](#checkAndSetIfResourceIsPsbSpecific-internalized-int-) | 리소스가 PSB 전용인지 확인하고 설정합니다. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [generateDefaultControlPoints_internalized()](#generateDefaultControlPoints-internalized--) | 기본 제어점을 생성합니다. |
| [generateDefaultTransparencyPoints_internalized()](#generateDefaultTransparencyPoints-internalized--) | 기본 투명도 점을 생성합니다. |
| [getAlignWithLayer()](#getAlignWithLayer--) | [align with layer] 여부를 가져오거나 설정합니다. |
| [getAngle()](#getAngle--) | 각도 값을 가져오거나 설정합니다. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | RGB의 색상을 가져옵니다. |
| [getColorModel()](#getColorModel--) | 컬러 모델 - RGB/HSB/LAB ("RGBC"/"HSBl"/"LbCl"). |
| [getColorPoints()](#getColorPoints--) | 색상 포인트를 가져옵니다. |
| [getDither()](#getDither--) | 이 [GdFlResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/gdflresource)가 디더링인지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [getGradientInterval()](#getGradientInterval--) | 그라디언트 간격을 가져오거나 설정합니다. |
| [getGradientMode()](#getGradientMode--) | 이 그라디언트의 모드. |
| [getGradientName()](#getGradientName--) | 그라디언트의 이름을 가져오거나 설정합니다. |
| [getGradientType()](#getGradientType--) |  |
| [getHeader_internalized()](#getHeader-internalized--) | 헤더를 가져오거나 설정합니다. |
| [getHorizontalOffset()](#getHorizontalOffset--) | 수평 오프셋 값을 가져오거나 설정합니다. |
| [getInterpolationMethod()](#getInterpolationMethod--) | 그라디언트에 대한 보간 방법을 가져오거나 설정합니다. |
| [getKey()](#getKey--) | 레이어 리소스 키를 가져옵니다. |
| [getLength()](#getLength--) | 레이어 리소스 길이를 바이트 단위로 가져옵니다. |
| [getMaximumColor()](#getMaximumColor--) | PixelDataFormat의 최대 색상. |
| [getMinimumColor()](#getMinimumColor--) | PixelDataFormat의 최소 색상. |
| [getOffset_internalized()](#getOffset-internalized--) | 오프셋을 가져오거나 설정합니다. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | 접두사 길이를 가져옵니다. |
| [getPsdVersion()](#getPsdVersion--) | 레이어 리소스에 필요한 최소 PSD 버전을 가져옵니다. |
| [getReverse()](#getReverse--) | 이 [GdFlResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/gdflresource)가 역방향인지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [getRndNumberSeed()](#getRndNumberSeed--) | 노이즈 그라디언트의 색상을 생성하는 데 사용되는 난수 시드. |
| [getRoughness()](#getRoughness--) | 거칠기 계수. |
| [getScale()](#getScale--) | 스케일을 가져오거나 설정합니다. |
| [getShowTransparency()](#getShowTransparency--) | 투명도를 표시하기 위한 플래그. |
| [getSignature()](#getSignature--) | 레이어 리소스 서명을 가져옵니다. |
| [getTransparencyPoints()](#getTransparencyPoints--) | 투명도 포인트를 가져옵니다. |
| [getUseVectorColor()](#getUseVectorColor--) | 벡터 색상을 사용하기 위한 플래그. |
| [getVerticalOffset()](#getVerticalOffset--) | 수직 오프셋 값을 가져오거나 설정합니다. |
| [hashCode()](#hashCode--) |  |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | 리소스가 PSB 전용인지 여부를 결정합니다. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | 이 인스턴스가 리소스 PSB 전용인지 여부를 나타내는 값을 가져옵니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | 지정된 스트림 컨테이너에 리소스를 저장합니다. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | 사용자 정의 리소스 헤더를 저장합니다. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | 헤더 서명, 식별자 및 길이를 저장합니다. |
| [setAlignWithLayer(boolean value)](#setAlignWithLayer-boolean-) | [align with layer] 여부를 가져오거나 설정합니다. |
| [setAngle(double value)](#setAngle-double-) |  |
| [setColor(Color value)](#setColor-com.aspose.psd.Color-) | RGB의 색상을 가져옵니다. |
| [setColorModel(String value)](#setColorModel-java.lang.String-) | 컬러 모델 - RGB/HSB/LAB ("RGBC"/"HSBl"/"LbCl"). |
| [setColorPoints(IGradientColorPoint[] value)](#setColorPoints-com.aspose.psd.fileformats.psd.layers.IGradientColorPoint---) | 색상 포인트를 가져옵니다. |
| [setDither(boolean value)](#setDither-boolean-) | 이 [GdFlResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/gdflresource)가 디더링인지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [setGradientInterval(double value)](#setGradientInterval-double-) | 그라디언트 간격을 가져오거나 설정합니다. |
| [setGradientMode(String value)](#setGradientMode-java.lang.String-) | 이 그라디언트의 모드. |
| [setGradientName(String value)](#setGradientName-java.lang.String-) | 그라디언트의 이름을 가져오거나 설정합니다. |
| [setGradientType(int value)](#setGradientType-int-) |  |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | 헤더를 가져오거나 설정합니다. |
| [setHorizontalOffset(double value)](#setHorizontalOffset-double-) |  |
| [setInterpolationMethod(long value)](#setInterpolationMethod-long-) | 그라디언트에 대한 보간 방법을 가져오거나 설정합니다. |
| [setMaximumColor(RawColor value)](#setMaximumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | PixelDataFormat의 최대 색상. |
| [setMinimumColor(RawColor value)](#setMinimumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | PixelDataFormat의 최소 색상. |
| [setOffset_internalized(OffsetEntity value)](#setOffset-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.OffsetEntity-) | 오프셋을 가져오거나 설정합니다. |
| [setReverse(boolean value)](#setReverse-boolean-) | 이 [GdFlResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/gdflresource)가 역방향인지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [setRndNumberSeed(int value)](#setRndNumberSeed-int-) | 노이즈 그라디언트의 색상을 생성하는 데 사용되는 난수 시드. |
| [setRoughness(int value)](#setRoughness-int-) | 거칠기 계수. |
| [setScale(double value)](#setScale-double-) | 스케일을 가져오거나 설정합니다. |
| [setShowTransparency(boolean value)](#setShowTransparency-boolean-) | 투명도를 표시하기 위한 플래그. |
| [setTransparencyPoints(IGradientTransparencyPoint[] value)](#setTransparencyPoints-com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint---) | 투명도 포인트를 가져옵니다. |
| [setUseVectorColor(boolean value)](#setUseVectorColor-boolean-) | 벡터 색상을 사용하기 위한 플래그. |
| [setVerticalOffset(double value)](#setVerticalOffset-double-) |  |
| [toString()](#toString--) | 이 인스턴스를 나타내는 문자열을 반환합니다. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GdFlResource() {#GdFlResource--}
```
public GdFlResource()
```


새 인스턴스를 초기화합니다 [.GdFlResource](../../null/\#GdFlResource) 클래스.

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

### addUnknownStructure_internalized(OSTypeStructure structure) {#addUnknownStructure-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-}
```
public void addUnknownStructure_internalized(OSTypeStructure structure)
```


알 수 없는 구조를 추가합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| structure | [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | 구조. |

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
### generateDefaultControlPoints_internalized() {#generateDefaultControlPoints-internalized--}
```
public static IGradientColorPoint[] generateDefaultControlPoints_internalized()
```


기본 제어점을 생성합니다.

**Returns:**
com.aspose.psd.fileformats.psd.layers.IGradientColorPoint[] - 기본 제어 포인트.
### generateDefaultTransparencyPoints_internalized() {#generateDefaultTransparencyPoints-internalized--}
```
public static IGradientTransparencyPoint[] generateDefaultTransparencyPoints_internalized()
```


기본 투명도 점을 생성합니다.

**Returns:**
com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint[] - 기본 투명도 포인트.
### getAlignWithLayer() {#getAlignWithLayer--}
```
public final boolean getAlignWithLayer()
```


[align with layer] 여부를 가져오거나 설정합니다.

값:  true  인 경우 [align with layer]; 그렇지 않으면,  false .

**Returns:**
boolean
### getAngle() {#getAngle--}
```
public double getAngle()
```


각도 값을 가져오거나 설정합니다.

그 각도.

**Returns:**
double
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColor() {#getColor--}
```
public final Color getColor()
```


RGB의 색상을 가져옵니다.

**Returns:**
[Color](../../com.aspose.psd/color) - The RGB Color
### getColorModel() {#getColorModel--}
```
public final String getColorModel()
```


컬러 모델 - RGB/HSB/LAB ("RGBC"/"HSBl"/"LbCl").

**Returns:**
java.lang.String
### getColorPoints() {#getColorPoints--}
```
public final IGradientColorPoint[] getColorPoints()
```


색상 포인트를 가져옵니다.

값: 색상 포인트.

**Returns:**
com.aspose.psd.fileformats.psd.layers.IGradientColorPoint[]
### getDither() {#getDither--}
```
public final boolean getDither()
```


이 [GdFlResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/gdflresource)가 디더링인지 여부를 나타내는 값을 가져오거나 설정합니다.

값: 디더링이면 true, 그렇지 않으면 false.

**Returns:**
boolean
### getGradientInterval() {#getGradientInterval--}
```
public final double getGradientInterval()
```


그라디언트 간격을 가져오거나 설정합니다.

값: 그라디언트 간격.

**Returns:**
double
### getGradientMode() {#getGradientMode--}
```
public final String getGradientMode()
```


이 그라디언트의 모드. 'Gradient Type' = 'Solid/Noise' = \"CstS\"/\"ClNs\"를 결정합니다.

**Returns:**
java.lang.String
### getGradientName() {#getGradientName--}
```
public String getGradientName()
```


그라디언트의 이름을 가져오거나 설정합니다.

값: 그라디언트의 이름.

**Returns:**
java.lang.String
### getGradientType() {#getGradientType--}
```
public int getGradientType()
```




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
### getHorizontalOffset() {#getHorizontalOffset--}
```
public double getHorizontalOffset()
```


수평 오프셋 값을 가져오거나 설정합니다.

수평 오프셋입니다.

**Returns:**
double
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


PixelDataFormat의 최대 색상.

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor)
### getMinimumColor() {#getMinimumColor--}
```
public final RawColor getMinimumColor()
```


PixelDataFormat의 최소 색상.

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor)
### getOffset_internalized() {#getOffset-internalized--}
```
public final OffsetEntity getOffset_internalized()
```


오프셋을 가져오거나 설정합니다.

값: 오프셋.

**Returns:**
com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.OffsetEntity
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
### getReverse() {#getReverse--}
```
public final boolean getReverse()
```


이 [GdFlResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/gdflresource)가 역방향인지 여부를 나타내는 값을 가져오거나 설정합니다.

값: 역방향이면 true, 그렇지 않으면 false.

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


거칠기 계수.

**Returns:**
int
### getScale() {#getScale--}
```
public final double getScale()
```


스케일을 가져오거나 설정합니다.

**Returns:**
double
### getShowTransparency() {#getShowTransparency--}
```
public final boolean getShowTransparency()
```


투명도를 표시하기 위한 플래그.

**Returns:**
boolean
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


투명도 포인트를 가져옵니다.

값: 투명도 포인트.

**Returns:**
com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint[]
### getUseVectorColor() {#getUseVectorColor--}
```
public final boolean getUseVectorColor()
```


벡터 색상을 사용하기 위한 플래그.

**Returns:**
boolean
### getVerticalOffset() {#getVerticalOffset--}
```
public double getVerticalOffset()
```


수직 오프셋 값을 가져오거나 설정합니다.

수직 오프셋입니다.

**Returns:**
double
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

### setAlignWithLayer(boolean value) {#setAlignWithLayer-boolean-}
```
public final void setAlignWithLayer(boolean value)
```


[align with layer] 여부를 가져오거나 설정합니다.

값:  true  인 경우 [align with layer]; 그렇지 않으면,  false .

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setAngle(double value) {#setAngle-double-}
```
public void setAngle(double value)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double |  |

### setColor(Color value) {#setColor-com.aspose.psd.Color-}
```
public final void setColor(Color value)
```


RGB의 색상을 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setColorModel(String value) {#setColorModel-java.lang.String-}
```
public final void setColorModel(String value)
```


컬러 모델 - RGB/HSB/LAB ("RGBC"/"HSBl"/"LbCl").

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setColorPoints(IGradientColorPoint[] value) {#setColorPoints-com.aspose.psd.fileformats.psd.layers.IGradientColorPoint---}
```
public final void setColorPoints(IGradientColorPoint[] value)
```


색상 포인트를 가져옵니다.

값: 색상 포인트.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [IGradientColorPoint\[\]](../../com.aspose.psd.fileformats.psd.layers/igradientcolorpoint) |  |

### setDither(boolean value) {#setDither-boolean-}
```
public final void setDither(boolean value)
```


이 [GdFlResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/gdflresource)가 디더링인지 여부를 나타내는 값을 가져오거나 설정합니다.

값: 디더링이면 true, 그렇지 않으면 false.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setGradientInterval(double value) {#setGradientInterval-double-}
```
public final void setGradientInterval(double value)
```


그라디언트 간격을 가져오거나 설정합니다.

값: 그라디언트 간격.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double |  |

### setGradientMode(String value) {#setGradientMode-java.lang.String-}
```
public final void setGradientMode(String value)
```


이 그라디언트의 모드. 'Gradient Type' = 'Solid/Noise' = \"CstS\"/\"ClNs\"를 결정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setGradientName(String value) {#setGradientName-java.lang.String-}
```
public void setGradientName(String value)
```


그라디언트의 이름을 가져오거나 설정합니다.

값: 그라디언트의 이름.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setGradientType(int value) {#setGradientType-int-}
```
public void setGradientType(int value)
```




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

### setHorizontalOffset(double value) {#setHorizontalOffset-double-}
```
public void setHorizontalOffset(double value)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double |  |

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


PixelDataFormat의 최대 색상.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) |  |

### setMinimumColor(RawColor value) {#setMinimumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public final void setMinimumColor(RawColor value)
```


PixelDataFormat의 최소 색상.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) |  |

### setOffset_internalized(OffsetEntity value) {#setOffset-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.OffsetEntity-}
```
public final void setOffset_internalized(OffsetEntity value)
```


오프셋을 가져오거나 설정합니다.

값: 오프셋.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.OffsetEntity |  |

### setReverse(boolean value) {#setReverse-boolean-}
```
public final void setReverse(boolean value)
```


이 [GdFlResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/gdflresource)가 역방향인지 여부를 나타내는 값을 가져오거나 설정합니다.

값: 역방향이면 true, 그렇지 않으면 false.

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


거칠기 계수.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setScale(double value) {#setScale-double-}
```
public final void setScale(double value)
```


스케일을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double |  |

### setShowTransparency(boolean value) {#setShowTransparency-boolean-}
```
public final void setShowTransparency(boolean value)
```


투명도를 표시하기 위한 플래그.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setTransparencyPoints(IGradientTransparencyPoint[] value) {#setTransparencyPoints-com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint---}
```
public final void setTransparencyPoints(IGradientTransparencyPoint[] value)
```


투명도 포인트를 가져옵니다.

값: 투명도 포인트.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [IGradientTransparencyPoint\[\]](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint) |  |

### setUseVectorColor(boolean value) {#setUseVectorColor-boolean-}
```
public final void setUseVectorColor(boolean value)
```


벡터 색상을 사용하기 위한 플래그.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setVerticalOffset(double value) {#setVerticalOffset-double-}
```
public void setVerticalOffset(double value)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double |  |

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

