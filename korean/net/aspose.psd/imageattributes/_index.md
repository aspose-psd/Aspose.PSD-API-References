---
title: Class ImageAttributes
second_title: .NET API 참조용 Aspose.PSD
description: Aspose.PSD.ImageAttributes 수업. 안ImageAttributes 객체에는 렌더링 중에 비트맵 및 메타파일 색상이 조작되는 방식에 대한 정보가 들어 있습니다. 안ImageAttributes 개체는 색상 조정 매트릭스 그레이스케일 조정 매트릭스 감마 보정 값 색상 맵 테이블 및 색상 임계값을 포함하여 여러 색상 조정 설정을 유지합니다. 렌더링하는 동안 색상을 수정 어둡게 밝게 및 제거할 수 있습니다. 이러한 조작을 적용하려면ImageAttributes대상을 지정하고 해당 경로를 전달합니다.ImageAttributes 개체의 경로와 함께Image  DrawImage 메서드에.
type: docs
weight: 4610
url: /ko/net/aspose.psd/imageattributes/
---
## ImageAttributes class

안`ImageAttributes` 객체에는 렌더링 중에 비트맵 및 메타파일 색상이 조작되는 방식에 대한 정보가 들어 있습니다. 안`ImageAttributes` 개체는 색상 조정 매트릭스, 그레이스케일 조정 매트릭스, 감마 보정 값, 색상 맵 테이블 및 색상 임계값을 포함하여 여러 색상 조정 설정을 유지합니다. 렌더링하는 동안 색상을 수정, 어둡게, 밝게 및 제거할 수 있습니다. 이러한 조작을 적용하려면`ImageAttributes`대상을 지정하고 해당 경로를 전달합니다.`ImageAttributes` 개체(의 경로와 함께[`Image`](../image/) ) DrawImage 메서드에.

```csharp
public sealed class ImageAttributes
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [ImageAttributes](imageattributes/)() | 기본 생성자입니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| [ClearBrushRemapTable](../../aspose.psd/imageattributes/clearbrushremaptable/)() | 이 브러시 색상 재매핑 테이블을 지웁니다.`ImageAttributes` object. |
| [ClearColorKey](../../aspose.psd/imageattributes/clearcolorkey/#clearcolorkey)() | 기본 범주에 대한 색상 키(투명도 범위)를 지웁니다. |
| [ClearColorKey](../../aspose.psd/imageattributes/clearcolorkey/#clearcolorkey_1)(ColorAdjustType) | 지정된 범주에 대한 색상 키(투명도 범위)를 지웁니다. |
| [ClearColorMatrix](../../aspose.psd/imageattributes/clearcolormatrix/#clearcolormatrix)() | 기본 범주에 대한 색상 조정 매트릭스를 지웁니다. |
| [ClearColorMatrix](../../aspose.psd/imageattributes/clearcolormatrix/#clearcolormatrix_1)(ColorAdjustType) | 지정된 범주에 대한 색상 조정 매트릭스를 지웁니다. |
| [ClearGamma](../../aspose.psd/imageattributes/cleargamma/#cleargamma)() | 기본 범주에 대한 감마 보정을 비활성화합니다. |
| [ClearGamma](../../aspose.psd/imageattributes/cleargamma/#cleargamma_1)(ColorAdjustType) | 지정된 범주에 대한 감마 보정을 비활성화합니다. |
| [ClearNoOp](../../aspose.psd/imageattributes/clearnoop/#clearnoop)() | 기본 범주에 대한 NoOp 설정을 지웁니다. |
| [ClearNoOp](../../aspose.psd/imageattributes/clearnoop/#clearnoop_1)(ColorAdjustType) | 지정된 범주에 대한 NoOp 설정을 지웁니다. |
| [ClearOutputChannel](../../aspose.psd/imageattributes/clearoutputchannel/#clearoutputchannel)() | 기본 범주에 대한 CMYK(시안-마젠타-노랑-검정) 출력 채널 설정을 지웁니다. |
| [ClearOutputChannel](../../aspose.psd/imageattributes/clearoutputchannel/#clearoutputchannel_1)(ColorAdjustType) | 지정된 범주에 대한 (시안-마젠타-노랑-검정) 출력 채널 설정을 지웁니다. |
| [ClearOutputChannelColorProfile](../../aspose.psd/imageattributes/clearoutputchannelcolorprofile/#clearoutputchannelcolorprofile)() | 기본 범주에 대한 출력 채널 색상 프로필 설정을 지웁니다. |
| [ClearOutputChannelColorProfile](../../aspose.psd/imageattributes/clearoutputchannelcolorprofile/#clearoutputchannelcolorprofile_1)(ColorAdjustType) | 지정된 범주에 대한 출력 채널 색상 프로파일 설정을 지웁니다. |
| [ClearRemapTable](../../aspose.psd/imageattributes/clearremaptable/#clearremaptable)() | 기본 범주에 대한 색상 재매핑 테이블을 지웁니다. |
| [ClearRemapTable](../../aspose.psd/imageattributes/clearremaptable/#clearremaptable_1)(ColorAdjustType) | 지정된 범주에 대한 색상 재매핑 테이블을 지웁니다. |
| [ClearThreshold](../../aspose.psd/imageattributes/clearthreshold/#clearthreshold)() | 기본 범주에 대한 임계값을 지웁니다. |
| [ClearThreshold](../../aspose.psd/imageattributes/clearthreshold/#clearthreshold_1)(ColorAdjustType) | 지정된 범주에 대한 임계값을 지웁니다. |
| [SetBrushRemapTable](../../aspose.psd/imageattributes/setbrushremaptable/)(ColorMap[]) | 브러시 범주에 대한 색상 재매핑 테이블을 설정합니다. |
| [SetColorKey](../../aspose.psd/imageattributes/setcolorkey/#setcolorkey)(Color, Color) | 기본 범주에 대한 색상 키를 설정합니다. |
| [SetColorKey](../../aspose.psd/imageattributes/setcolorkey/#setcolorkey_1)(Color, Color, ColorAdjustType) | 지정된 범주에 대한 색상 키(투명도 범위)를 설정합니다. |
| [SetColorMatrices](../../aspose.psd/imageattributes/setcolormatrices/#setcolormatrices)(ColorMatrix, ColorMatrix) | 기본 범주에 대한 색상 조정 매트릭스 및 그레이스케일 조정 매트릭스를 설정합니다. |
| [SetColorMatrices](../../aspose.psd/imageattributes/setcolormatrices/#setcolormatrices_1)(ColorMatrix, ColorMatrix, ColorMatrixFlag) | 기본 범주에 대한 색상 조정 매트릭스 및 그레이스케일 조정 매트릭스를 설정합니다. |
| [SetColorMatrices](../../aspose.psd/imageattributes/setcolormatrices/#setcolormatrices_2)(ColorMatrix, ColorMatrix, ColorMatrixFlag, ColorAdjustType) | 지정된 범주에 대한 색상 조정 매트릭스 및 그레이스케일 조정 매트릭스를 설정합니다. |
| [SetColorMatrix](../../aspose.psd/imageattributes/setcolormatrix/#setcolormatrix)(ColorMatrix) | 기본 범주에 대한 색상 조정 매트릭스를 설정합니다. |
| [SetColorMatrix](../../aspose.psd/imageattributes/setcolormatrix/#setcolormatrix_1)(ColorMatrix, ColorMatrixFlag) | 기본 범주에 대한 색상 조정 매트릭스를 설정합니다. |
| [SetColorMatrix](../../aspose.psd/imageattributes/setcolormatrix/#setcolormatrix_2)(ColorMatrix, ColorMatrixFlag, ColorAdjustType) | 지정된 범주에 대한 색상 조정 매트릭스를 설정합니다. |
| [SetGamma](../../aspose.psd/imageattributes/setgamma/#setgamma)(float) | 기본 범주에 대한 감마 값을 설정합니다. |
| [SetGamma](../../aspose.psd/imageattributes/setgamma/#setgamma_1)(float, ColorAdjustType) | 지정된 범주에 대한 감마 값을 설정합니다. |
| [SetNoOp](../../aspose.psd/imageattributes/setnoop/#setnoop)() | 기본 범주에 대한 색상 조정을 끕니다. |
| [SetNoOp](../../aspose.psd/imageattributes/setnoop/#setnoop_1)(ColorAdjustType) | 지정된 범주에 대한 색상 조정을 끕니다. |
| [SetOutputChannel](../../aspose.psd/imageattributes/setoutputchannel/#setoutputchannel)(ColorChannelFlag) | 기본 범주에 대한 CMYK(시안-마젠타-노랑-검정) 출력 채널을 설정합니다. |
| [SetOutputChannel](../../aspose.psd/imageattributes/setoutputchannel/#setoutputchannel_1)(ColorChannelFlag, ColorAdjustType) | 지정된 범주에 대한 CMYK(시안-마젠타-노랑-검정) 출력 채널을 설정합니다. |
| [SetOutputChannelColorProfile](../../aspose.psd/imageattributes/setoutputchannelcolorprofile/#setoutputchannelcolorprofile)(string) | 기본 범주에 대한 출력 채널 색상 프로필 파일을 설정합니다. |
| [SetOutputChannelColorProfile](../../aspose.psd/imageattributes/setoutputchannelcolorprofile/#setoutputchannelcolorprofile_1)(string, ColorAdjustType) | 지정된 범주에 대한 출력 채널 색상 프로필 파일을 설정합니다. |
| [SetRemapTable](../../aspose.psd/imageattributes/setremaptable/#setremaptable)(ColorMap[]) | 기본 범주에 대한 색상 재매핑 테이블을 설정합니다. |
| [SetRemapTable](../../aspose.psd/imageattributes/setremaptable/#setremaptable_1)(ColorMap[], ColorAdjustType) | 지정된 범주에 대한 색상 재매핑 테이블을 설정합니다. |
| [SetThreshold](../../aspose.psd/imageattributes/setthreshold/#setthreshold)(float) | 기본 범주에 대한 임계값(투명도 범위)을 설정합니다. |
| [SetThreshold](../../aspose.psd/imageattributes/setthreshold/#setthreshold_1)(float, ColorAdjustType) | 지정된 범주에 대한 임계값(투명도 범위)을 설정합니다. |
| [SetWrapMode](../../aspose.psd/imageattributes/setwrapmode/#setwrapmode)(WrapMode) | 모양 또는 모양 경계에서 텍스처를 타일링하는 방법을 결정하는 데 사용되는 랩 모드를 설정합니다. 텍스처가 채우고 있는 모양보다 작을 때 텍스처가 채우기 위해 모양을 가로질러 바둑판식으로 배열됩니다. |
| [SetWrapMode](../../aspose.psd/imageattributes/setwrapmode/#setwrapmode_1)(WrapMode, Color) | 모양 또는 모양 경계에서 텍스처를 타일링하는 방법을 결정하는 데 사용되는 랩 모드 및 색상을 설정합니다. 텍스처가 채우고 있는 모양보다 작을 때 텍스처가 채우기 위해 모양을 가로질러 바둑판식으로 배열됩니다. |
| [SetWrapMode](../../aspose.psd/imageattributes/setwrapmode/#setwrapmode_2)(WrapMode, Color, bool) | 모양 또는 모양 경계에서 텍스처를 타일링하는 방법을 결정하는 데 사용되는 랩 모드 및 색상을 설정합니다. 텍스처가 채우고 있는 모양보다 작을 때 텍스처가 채우기 위해 모양을 가로질러 바둑판식으로 배열됩니다. |

### 또한보십시오

* 네임스페이스 [Aspose.PSD](../../aspose.psd/)
* 집회 [Aspose.PSD](../../)


