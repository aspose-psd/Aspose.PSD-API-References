---
title: "클래스 ImageAttributes"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.ImageAttributes 클래스. ImageAttributes 객체는 렌더링 중 비트맵 및 메타파일 색상이 어떻게 조작되는지에 대한 정보를 포함합니다. ImageAttributes 객체는 색상조정 행렬, 그레이스케일조정 행렬, 감마 보정 값, 컬러맵 테이블 및 컬러 임계값 등을 포함한 여러 색상조정 설정을 유지합니다. 렌더링 중 색상은 보정, 어둡게, 밝게, 제거될 수 있습니다. 이러한 조작을 적용하려면 ImageAttributes 객체를 초기화하고 해당 ImageAttributes 객체의 경로와 Image의 경로를 함께 DrawImage 메서드에 전달합니다."
type: docs
weight: 5080
url: /ko/net/aspose.psd/imageattributes/
---
{{< psd/tize >}}
## ImageAttributes class

`ImageAttributes` 객체는 렌더링 중 비트맵 및 메타파일 색상이 어떻게 조작되는지에 대한 정보를 포함합니다. `ImageAttributes` 객체는 색상-조정 행렬, 그레이스케일-조정 행렬, 감마-보정 값, 컬러-맵 테이블 및 컬러-임계값 등을 포함한 여러 색상-조정 설정을 유지합니다. 렌더링 중 색상은 보정, 어둡게, 밝게, 제거될 수 있습니다. 이러한 조작을 적용하려면 `ImageAttributes` 객체를 초기화하고 해당 `ImageAttributes` 객체의 경로(및 [`Image`](../image/)의 경로)를 DrawImage 메서드에 전달합니다.

```csharp
public sealed class ImageAttributes
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [ImageAttributes](imageattributes/)() | 기본 생성자입니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [ClearBrushRemapTable](../../aspose.psd/imageattributes/clearbrushremaptable/)() | `ImageAttributes` 객체의 브러시 색상-재매핑 테이블을 지웁니다. |
| [ClearColorKey](../../aspose.psd/imageattributes/clearcolorkey/#clearcolorkey)() | 기본 카테고리의 색상 키(투명도 범위)를 지웁니다. |
| [ClearColorKey](../../aspose.psd/imageattributes/clearcolorkey/#clearcolorkey_1)(ColorAdjustType) | 지정된 카테고리의 색상 키(투명도 범위)를 지웁니다. |
| [ClearColorMatrix](../../aspose.psd/imageattributes/clearcolormatrix/#clearcolormatrix)() | 기본 카테고리의 색상-조정 행렬을 지웁니다. |
| [ClearColorMatrix](../../aspose.psd/imageattributes/clearcolormatrix/#clearcolormatrix_1)(ColorAdjustType) | 지정된 카테고리의 색상-조정 행렬을 지웁니다. |
| [ClearGamma](../../aspose.psd/imageattributes/cleargamma/#cleargamma)() | 기본 카테고리의 감마 보정을 비활성화합니다. |
| [ClearGamma](../../aspose.psd/imageattributes/cleargamma/#cleargamma_1)(ColorAdjustType) | 지정된 카테고리의 감마 보정을 비활성화합니다. |
| [ClearNoOp](../../aspose.psd/imageattributes/clearnoop/#clearnoop)() | 기본 카테고리의 NoOp 설정을 지웁니다. |
| [ClearNoOp](../../aspose.psd/imageattributes/clearnoop/#clearnoop_1)(ColorAdjustType) | 지정된 카테고리의 NoOp 설정을 지웁니다. |
| [ClearOutputChannel](../../aspose.psd/imageattributes/clearoutputchannel/#clearoutputchannel)() | 기본 카테고리의 CMYK(시안-마젠타-옐로-블랙) 출력 채널 설정을 지웁니다. |
| [ClearOutputChannel](../../aspose.psd/imageattributes/clearoutputchannel/#clearoutputchannel_1)(ColorAdjustType) | 지정된 카테고리의 (시안-마젠타-옐로-블랙) 출력 채널 설정을 지웁니다. |
| [ClearOutputChannelColorProfile](../../aspose.psd/imageattributes/clearoutputchannelcolorprofile/#clearoutputchannelcolorprofile)() | 기본 카테고리의 출력 채널 색상 프로파일 설정을 지웁니다. |
| [ClearOutputChannelColorProfile](../../aspose.psd/imageattributes/clearoutputchannelcolorprofile/#clearoutputchannelcolorprofile_1)(ColorAdjustType) | 지정된 카테고리의 출력 채널 색상 프로파일 설정을 지웁니다. |
| [ClearRemapTable](../../aspose.psd/imageattributes/clearremaptable/#clearremaptable)() | 기본 카테고리의 색상-재매핑 테이블을 지웁니다. |
| [ClearRemapTable](../../aspose.psd/imageattributes/clearremaptable/#clearremaptable_1)(ColorAdjustType) | 지정된 카테고리의 색상-재매핑 테이블을 지웁니다. |
| [ClearThreshold](../../aspose.psd/imageattributes/clearthreshold/#clearthreshold)() | 기본 카테고리의 임계값을 지웁니다. |
| [ClearThreshold](../../aspose.psd/imageattributes/clearthreshold/#clearthreshold_1)(ColorAdjustType) | 지정된 카테고리의 임계값을 지웁니다. |
| [SetBrushRemapTable](../../aspose.psd/imageattributes/setbrushremaptable/)(ColorMap[]) | 브러시 카테고리의 색상-재매핑 테이블을 설정합니다. |
| [SetColorKey](../../aspose.psd/imageattributes/setcolorkey/#setcolorkey)(Color, Color) | 기본 카테고리의 색 키를 설정합니다. |
| [SetColorKey](../../aspose.psd/imageattributes/setcolorkey/#setcolorkey_1)(Color, Color, ColorAdjustType) | 지정된 카테고리의 색 키(투명도 범위)를 설정합니다. |
| [SetColorMatrices](../../aspose.psd/imageattributes/setcolormatrices/#setcolormatrices)(ColorMatrix, ColorMatrix) | 기본 카테고리의 색 보정 행렬 및 그레이스케일 보정 행렬을 설정합니다. |
| [SetColorMatrices](../../aspose.psd/imageattributes/setcolormatrices/#setcolormatrices_1)(ColorMatrix, ColorMatrix, ColorMatrixFlag) | 기본 카테고리의 색 보정 행렬 및 그레이스케일 보정 행렬을 설정합니다. |
| [SetColorMatrices](../../aspose.psd/imageattributes/setcolormatrices/#setcolormatrices_2)(ColorMatrix, ColorMatrix, ColorMatrixFlag, ColorAdjustType) | 지정된 카테고리의 색 보정 행렬 및 그레이스케일 보정 행렬을 설정합니다. |
| [SetColorMatrix](../../aspose.psd/imageattributes/setcolormatrix/#setcolormatrix)(ColorMatrix) | 기본 카테고리의 색 보정 행렬을 설정합니다. |
| [SetColorMatrix](../../aspose.psd/imageattributes/setcolormatrix/#setcolormatrix_1)(ColorMatrix, ColorMatrixFlag) | 기본 카테고리의 색 보정 행렬을 설정합니다. |
| [SetColorMatrix](../../aspose.psd/imageattributes/setcolormatrix/#setcolormatrix_2)(ColorMatrix, ColorMatrixFlag, ColorAdjustType) | 지정된 카테고리의 색 보정 행렬을 설정합니다. |
| [SetGamma](../../aspose.psd/imageattributes/setgamma/#setgamma)(float) | 기본 카테고리의 감마 값을 설정합니다. |
| [SetGamma](../../aspose.psd/imageattributes/setgamma/#setgamma_1)(float, ColorAdjustType) | 지정된 카테고리의 감마 값을 설정합니다. |
| [SetNoOp](../../aspose.psd/imageattributes/setnoop/#setnoop)() | 기본 카테고리의 색 보정을 끕니다. |
| [SetNoOp](../../aspose.psd/imageattributes/setnoop/#setnoop_1)(ColorAdjustType) | 지정된 카테고리의 색 보정을 끕니다. |
| [SetOutputChannel](../../aspose.psd/imageattributes/setoutputchannel/#setoutputchannel)(ColorChannelFlag) | 기본 카테고리의 CMYK(시안-마젠타-옐로-블랙) 출력 채널을 설정합니다. |
| [SetOutputChannel](../../aspose.psd/imageattributes/setoutputchannel/#setoutputchannel_1)(ColorChannelFlag, ColorAdjustType) | 지정된 카테고리의 CMYK(시안-마젠타-옐로-블랙) 출력 채널을 설정합니다. |
| [SetOutputChannelColorProfile](../../aspose.psd/imageattributes/setoutputchannelcolorprofile/#setoutputchannelcolorprofile)(string) | 기본 카테고리의 출력 채널 색 프로파일 파일을 설정합니다. |
| [SetOutputChannelColorProfile](../../aspose.psd/imageattributes/setoutputchannelcolorprofile/#setoutputchannelcolorprofile_1)(string, ColorAdjustType) | 지정된 카테고리의 출력 채널 색 프로파일 파일을 설정합니다. |
| [SetRemapTable](../../aspose.psd/imageattributes/setremaptable/#setremaptable)(ColorMap[]) | 기본 카테고리의 색 재매핑 테이블을 설정합니다. |
| [SetRemapTable](../../aspose.psd/imageattributes/setremaptable/#setremaptable_1)(ColorMap[], ColorAdjustType) | 지정된 카테고리의 색 재매핑 테이블을 설정합니다. |
| [SetThreshold](../../aspose.psd/imageattributes/setthreshold/#setthreshold)(float) | 기본 카테고리의 임계값(투명도 범위)을 설정합니다. |
| [SetThreshold](../../aspose.psd/imageattributes/setthreshold/#setthreshold_1)(float, ColorAdjustType) | 지정된 카테고리의 임계값(투명도 범위)을 설정합니다. |
| [SetWrapMode](../../aspose.psd/imageattributes/setwrapmode/#setwrapmode)(WrapMode) | 텍스처를 도형 전체 또는 도형 경계에 타일링하는 방식을 결정하는 랩 모드를 설정합니다. 텍스처가 도형보다 작을 경우, 텍스처가 도형을 채우도록 타일링됩니다. |
| [SetWrapMode](../../aspose.psd/imageattributes/setwrapmode/#setwrapmode_1)(WrapMode, Color) | 텍스처를 도형 전체 또는 도형 경계에 타일링하는 방식을 결정하는 랩 모드와 색상을 설정합니다. 텍스처가 도형보다 작을 경우, 텍스처가 도형을 채우도록 타일링됩니다. |
| [SetWrapMode](../../aspose.psd/imageattributes/setwrapmode/#setwrapmode_2)(WrapMode, Color, bool) | 텍스처를 도형 전체 또는 도형 경계에 타일링하는 방식을 결정하는 랩 모드와 색상을 설정합니다. 텍스처가 도형보다 작을 경우, 텍스처가 도형을 채우도록 타일링됩니다. |

### 또 보기

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


