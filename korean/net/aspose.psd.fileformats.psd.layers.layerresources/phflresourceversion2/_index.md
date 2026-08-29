---
title: "클래스 PhflResourceVersion2"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.PhflResourceVersion2 클래스. PhflResource 클래스. 노출 보정 레이어 2 리소스 버전 3 또는 2. 버전 3에서는 XYZ 색상당 각각 12~4 바이트가 사용되며 색상 전용입니다. 버전 3에서는 10 바이트 색상 공간 뒤에 4 바이트가 따라오고, 버전 2에서는 2 바이트 색상 구성 요소 전용입니다. 4 밀도 1, 밝기 보존."
type: docs
weight: 3250
url: /ko/net/aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/
---
{{< psd/tize >}}
## PhflResourceVersion2 class

PhflResource 클래스. 노출 조정 레이어 2 리소스. 버전( = 3) 또는 ( = 2) 12: 버전 3에서는 XYZ 색상당 4바이트, 10: 버전 2에서는 색상 공간 2바이트에 이어 4 * 2바이트 색상 구성 요소, 4: 밀도, 1: 밝기 보존.

```csharp
public class PhflResourceVersion2 : PhflResource
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [PhflResourceVersion2](phflresourceversion2/#constructor)() | `PhflResourceVersion2` 클래스의 새 인스턴스를 초기화합니다. |
| [PhflResourceVersion2](phflresourceversion2/#constructor_1)(byte[]) | `PhflResourceVersion2` 클래스의 새 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [ColorSpace](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/colorspace/) { get; } | 색상 공간을 가져옵니다. |
| [ComponentA](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/componenta/) { get; set; } | 색상의 A 구성 요소를 가져오거나 설정합니다. |
| [ComponentB](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/componentb/) { get; set; } | B 구성 요소를 가져오거나 설정합니다. |
| [ComponentL](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/componentl/) { get; set; } | 색상의 L 구성 요소를 가져오거나 설정합니다. |
| [Density](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/density/) { get; set; } | 밀도를 가져오거나 설정합니다. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | 레이어 리소스 키를 가져옵니다. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/length/) { get; } | 레이어 리소스 길이를 바이트 단위로 가져옵니다. |
| [PreserveLuminosity](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/preserveluminosity/) { get; set; } | 광도 보존 여부를 나타내는 값을 가져오거나 설정합니다. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | 레이어 리소스에 필요한 최소 PSD 버전을 가져옵니다. 0은 제한이 없음을 나타냅니다. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | 서명을 가져옵니다. |
| override [Version](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/version/) { get; } | 버전을 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| override [GetRgbColor](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/getrgbcolor/)() | 색상을 가져옵니다. |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/save/)(StreamContainer, int) | 리소스를 지정된 스트림 컨테이너에 저장합니다. |
| override [SetRgbColor](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/setrgbcolor/)(Color) | RGB 색상을 설정합니다. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | 이 인스턴스를 나타내는 문자열을 반환합니다. |

### 또 보기

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [PhflResource](../phflresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


