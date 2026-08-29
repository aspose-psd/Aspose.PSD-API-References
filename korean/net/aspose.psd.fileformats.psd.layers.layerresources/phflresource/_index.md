---
title: "클래스 PhflResource"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.PhflResource 클래스. 클래스 PhflResource. 노출 조정 레이어 2의 리소스 버전 3 또는 2. XYZ 색상당 12 4바이트씩. 버전 3에서는 색상 전용 10 2바이트 색상 공간 뒤에 4 2바이트 색상 구성 요소가 옵니다. 버전 2에서는 색상 전용 4. 밀도 1. 밝기 보존"
type: docs
weight: 3240
url: /ko/net/aspose.psd.fileformats.psd.layers.layerresources/phflresource/
---
{{< psd/tize >}}
## PhflResource class

PhflResource 클래스. 노출 조정 레이어 2 리소스. 버전( = 3) 또는 ( = 2) 12: 버전 3에서는 XYZ 색상당 4바이트, 10: 버전 2에서는 색상 공간 2바이트에 이어 4 * 2바이트 색상 구성 요소, 4: 밀도, 1: 밝기 보존.

```csharp
public abstract class PhflResource : AdjustmentLayerResource
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [Density](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/density/) { get; set; } | 밀도를 가져오거나 설정합니다. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | 레이어 리소스 키를 가져옵니다. |
| abstract [Length](../../aspose.psd.fileformats.psd.layers/layerresource/length/) { get; } | 레이어 리소스 길이를 바이트 단위로 가져옵니다. |
| [PreserveLuminosity](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/preserveluminosity/) { get; set; } | 광도 보존 여부를 나타내는 값을 가져오거나 설정합니다. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | 레이어 리소스에 필요한 최소 PSD 버전을 가져옵니다. 0은 제한이 없음을 나타냅니다. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | 서명을 가져옵니다. |
| abstract [Version](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/version/) { get; } | 버전을 가져옵니다. 기본값은 2 또는 3입니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| abstract [GetRgbColor](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/getrgbcolor/)() | RGB 색상을 가져옵니다. |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/save/)(StreamContainer, int) | 리소스를 지정된 스트림 컨테이너에 저장합니다. |
| abstract [SetRgbColor](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/setrgbcolor/)(Color) | RGB 색상을 설정합니다. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | 이 인스턴스를 나타내는 문자열을 반환합니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/typetoolkey/) | 타입 툴 정보 키. |

### 또 보기

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


