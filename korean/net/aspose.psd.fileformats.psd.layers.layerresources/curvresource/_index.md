---
title: Class CurvResource
second_title: .NET API 참조용 Aspose.PSD
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.CurvResource 수업. 클래스 CurvResource. 곡선 조정 Layer 1바이트  곡선을 사용하는 경우 0 map 의 픽셀을 사용하는 경우 1 0인 경우 2바이트  짧습니다. 기본값은 1 4바이트  정수입니다. 마지막 바이트만 비트 단위로 사용됩니다. 첫 번째 비트는 1 채널용 네 번째 비트는 4 채널용 for example 2 bytes  short points count 4 bytes  count of point  point of curve 2 short 첫 번째 위치 두 번째 height 4 bytes  word Crv  2 bytes  Curves 4바이트  int의 짧은 기본값은 4입니다. 기본값은 1 4바이트  포인트 카운트 4바이트  포인트 카운트  곡선 2의 포인트 short 첫 번째 위치 두 번째 height 04바이트  1인 경우 four 에 대한 접기로 이어짐 then 2바이트  짧습니다. 기본값은 1 4바이트  정수입니다. 마지막 바이트만 사용됩니다. 하나의 채널은 하나의 비트입니다. 첫 번째 비트는 1개 채널용이고 네 번째 비트는 4개 채널용입니다. 예를 들어 example 256  변경된 채널 수  0  255 4바이트 범위의 채널 순서 값  단어 Crv 2바이트  짧습니다. 기본값은 map 의 픽셀에 대해 3입니다. 4바이트  int 채널 수 2  256바이트  채널 인덱스의 경우 short 2 256은 0  255 범위의 채널 값입니다.
type: docs
weight: 2400
url: /ko/net/aspose.psd.fileformats.psd.layers.layerresources/curvresource/
---
## CurvResource class

클래스 CurvResource. 곡선 조정 Layer 1바이트 - 곡선을 사용하는 경우 0, map 의 픽셀을 사용하는 경우 1, 0인 경우: 2바이트 - 짧습니다. 기본값은 1 4바이트 - 정수입니다. 마지막 바이트만 비트 단위로 사용됩니다. 첫 번째 비트는 1 채널용, 네 번째 비트는 4 채널용 for example 2 bytes - short points count 4 bytes * count of point - point of curve 2 short: 첫 번째 위치, 두 번째 height 4 bytes - word "Crv " 2 bytes - Curves 4바이트 - int의 짧은 기본값은 4입니다. 기본값은 1 4바이트 - 포인트 카운트 4바이트 * 포인트 카운트 - 곡선 2의 포인트 short: 첫 번째 위치, 두 번째 height 0-4바이트 - 1인 경우 four 에 대한 접기로 이어짐 then: 2바이트 - 짧습니다. 기본값은 1 4바이트 - 정수입니다. 마지막 바이트만 사용됩니다. 하나의 채널은 하나의 비트입니다. 첫 번째 비트는 1개 채널용이고 네 번째 비트는 4개 채널용입니다. 예를 들어 example 256 * 변경된 채널 수 - 0 - 255 4바이트 범위의 채널 순서 값 - 단어 "Crv" 2바이트 - 짧습니다. 기본값은 map 의 픽셀에 대해 3입니다. 4바이트 - int 채널 수 (2 + 256)바이트 - 채널 인덱스의 경우 short 2, 256은 0 - 255 범위의 채널 값입니다.

```csharp
public class CurvResource : AdjustmentLayerResource
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [CurvResource](curvresource/#constructor)(byte[]) | 의 새 인스턴스를 초기화합니다.`CurvResource` 클래스. |
| [CurvResource](curvresource/#constructor_1)(int) | 의 새 인스턴스를 초기화합니다.`CurvResource` 클래스. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [IsDataStoredDiscretely](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/isdatastoreddiscretely/) { get; set; } | 이 인스턴스가 개별적으로 저장된 데이터인지 여부를 나타내는 값을 가져오거나 설정합니다. |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/key/) { get; } | 레이어 리소스 키를 가져옵니다. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/length/) { get; } | 레이어 리소스 길이를 바이트 단위로 가져옵니다. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/psdversion/) { get; } | psd 버전을 가져옵니다. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/signature/) { get; } | 서명을 받습니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| [GetActiveManager](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/getactivemanager/)() | 활성 관리자를 가져옵니다. |
| [GetChannelData](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/getchanneldata/)(int) | 채널 데이터를 가져옵니다. |
| [GetCurveManager](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/getcurvemanager/)() | 곡선 관리자를 가져옵니다. |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/save/)(StreamContainer, int) | 리소스를 지정된 스트림 컨테이너에 저장합니다. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | 반환String 이 instance. 를 나타냅니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/typetoolkey/) | 유형 도구 정보 키입니다. |

### 또한보십시오

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* 네임스페이스 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* 집회 [Aspose.PSD](../../)


