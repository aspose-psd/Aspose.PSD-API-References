---
title: "클래스 CurvResource"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.CurvResource 클래스. CurvResource 클래스. 곡선 조정 레이어의 리소스 1 바이트 - 곡선을 사용할 경우 0, 맵에 픽셀을 사용할 경우 1, 0이면 2 바이트 short. 기본값은 1 4 바이트 int. 비트별로 마지막 바이트만 사용. 첫 번째 비트는 1채널, 네 번째 비트는 4채널 예시 2 바이트 short 포인트 수 4 바이트 포인트 수 곡선의 포인트 2 short 첫 번째 위치 두 번째 높이 4 바이트 word Crv 2 바이트 short 기본값은 곡선의 경우 4 4 바이트 int 기본값은 1 4 바이트 포인트 수 4 바이트 포인트 수 곡선의 포인트 2 short 첫 번째 위치 두 번째 높이 04 바이트 네 배로 접어야 함, 1이면 2 바이트 short 기본값은 1 4 바이트 int 마지막 바이트만 사용. 하나의 채널은 하나의 비트에 해당. 첫 번째 비트는 1채널, 네 번째 비트는 4채널 예시 256 변경된 채널 수 0~255 범위의 채널 순서값 4 바이트 word Crv 2 바이트 short 기본값은 맵의 픽셀 경우 3 4 바이트 int 채널 수 2 256 바이트 short 채널 인덱스용 2, 256은 0~255 범위의 채널 순서값"
type: docs
weight: 2660
url: /ko/net/aspose.psd.fileformats.psd.layers.layerresources/curvresource/
---
{{< psd/tize >}}
## CurvResource class

CurvResource 클래스. Curves Adjustment Layer의 리소스 1 바이트 - 곡선을 사용할 경우 0, 픽셀 맵을 사용할 경우 1. 0인 경우: 2 바이트 - short. 기본값은 1. 4 바이트 - int. 비트별로 마지막 바이트만 사용. 첫 번째 비트는 1채널, 네 번째 비트는 4채널을 나타냅니다. 예시: 2 바이트 - short 포인트 수. 4 바이트 * 포인트 수 - 곡선 포인트. 2 short: 첫 번째 위치, 두 번째 높이. 4 바이트 - word "Crv " 2 바이트 - short, 기본값은 Curves의 경우 4. 4 바이트 - int, 기본값은 1. 4 바이트 - 포인트 수. 4 바이트 * 포인트 수 - 곡선 포인트. 2 short: 첫 번째 위치, 두 번째 높이. 0-4 바이트 - 네 개가 접히도록. 1인 경우: 2 바이트 - short, 기본값은 1. 4 바이트 - int, 마지막 바이트만 사용. 하나의 채널은 한 비트에 해당합니다. 첫 번째 비트는 1채널, 네 번째 비트는 4채널을 나타냅니다. 예시: 256 * 변경된 채널 수 - 0~255 범위의 정렬된 채널 값. 4 바이트 - word "Crv " 2 바이트 - short, 기본값은 픽셀 맵의 경우 3. 4 바이트 - int 채널 수 (2 + 256) 바이트 - short, 채널 인덱스용 2 바이트, 256은 0~255 범위의 정렬된 채널 값.

```csharp
public class CurvResource : AdjustmentLayerResource
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [CurvResource](curvresource/#constructor)(byte[]) | `CurvResource` 클래스의 새 인스턴스를 초기화합니다. |
| [CurvResource](curvresource/#constructor_1)(int) | `CurvResource` 클래스의 새 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [IsDataStoredDiscretely](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/isdatastoreddiscretely/) { get; set; } | 이 인스턴스가 이산 데이터로 저장되는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | 레이어 리소스 키를 가져옵니다. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/length/) { get; } | 레이어 리소스 길이를 바이트 단위로 가져옵니다. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | 레이어 리소스에 필요한 최소 PSD 버전을 가져옵니다. 0은 제한이 없음을 나타냅니다. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | 서명을 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [GetActiveManager](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/getactivemanager/)() | 활성 관리자를 가져옵니다. |
| [GetChannelData](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/getchanneldata/)(int) | 채널 데이터를 가져옵니다. |
| [GetCurveManager](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/getcurvemanager/)() | 곡선 관리자를 가져옵니다. |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/save/)(StreamContainer, int) | 리소스를 지정된 스트림 컨테이너에 저장합니다. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | 이 인스턴스를 나타내는 문자열을 반환합니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/typetoolkey/) | 타입 툴 정보 키. |

### 또 보기

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


