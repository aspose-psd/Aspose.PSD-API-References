---
title: "클래스 MixrResource"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.MixrResource 클래스. MixrResource 클래스. 채널 믹서 조정 레이어의 리소스입니다."
type: docs
weight: 3160
url: /ko/net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/
---
{{< psd/tize >}}
## MixrResource class

MixrResource 클래스. 채널 믹서 조정 레이어의 리소스

```csharp
public sealed class MixrResource : AdjustmentLayerResource
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [MixrResource](mixrresource/#constructor)() | `MixrResource` 클래스의 새 인스턴스를 초기화합니다. PSD 형식 사양에는 다음 설명이 포함됩니다: 2 버전 (= 1) 2 모노크롬 20 RGB 또는 CMYK 색상과 믹서 설정을 위한 상수가 있습니다. 색상 4 * 2 바이트와 상수 2 바이트. |
| [MixrResource](mixrresource/#constructor_1)(byte[]) | `MixrResource` 클래스의 새 인스턴스를 초기화합니다. PSD 형식 사양에는 다음 설명이 포함됩니다: 2 버전 (= 1) 2 모노크롬 20 RGB 또는 CMYK 색상과 믹서 설정을 위한 상수가 있습니다. 색상 4 * 2 바이트와 상수 2 바이트. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | 레이어 리소스 키를 가져옵니다. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/length/) { get; } | 레이어 리소스 길이를 바이트 단위로 가져옵니다. |
| [Monochrome](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/monochrome/) { get; set; } | `MixrResource`가 모노크롬인지 여부를 나타내는 값을 가져오거나 설정합니다. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | 레이어 리소스에 필요한 최소 PSD 버전을 가져옵니다. 0은 제한이 없음을 나타냅니다. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | 서명을 가져옵니다. |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/version/) { get; set; } | 버전을 가져오거나 설정합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [GetChannelInfo](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/getchannelinfo/)(int) | 채널 정보 원시 데이터를 가져옵니다 |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/save/)(StreamContainer, int) | 리소스를 지정된 스트림 컨테이너에 저장합니다. |
| [SetChannelInfo](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/setchannelinfo/)(int, byte[]) | 채널 정보를 설정합니다. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | 이 인스턴스를 나타내는 문자열을 반환합니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/typetoolkey/) | 타입 툴 정보 키. |

### 또 보기

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


