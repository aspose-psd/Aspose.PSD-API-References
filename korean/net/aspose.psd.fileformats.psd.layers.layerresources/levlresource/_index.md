---
title: "클래스 LevlResource"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LevlResource 클래스. LevlResource 클래스. 노출 조정 레이어의 리소스"
type: docs
weight: 2950
url: /ko/net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/
---
{{< psd/tize >}}
## LevlResource class

클래스 LevlResource. 노출 조정 레이어의 리소스

```csharp
public class LevlResource : AdjustmentLayerResource
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [LevlResource](levlresource/#constructor)() | `LevlResource` 클래스의 새 인스턴스를 초기화합니다. |
| [LevlResource](levlresource/#constructor_1)(byte[]) | `LevlResource` 클래스의 새 인스턴스를 초기화합니다. GrayScale, Duotone, RGB, CMYK, Lab 색상 모드에서 지원됩니다. 2 바이트 - 버전 (=2) 29 * 10 바이트 - 5개의 short 정수로 구성된 레벨 레코드 집합 4 바이트 - Lvls 헤더 (인덱스 292에서 시작) 2 바이트 - 버전 (=3) 2 바이트 - 전체 레벨 레코드 수 10 * (전체 수 - 29) Lvls 리소스의 0 종료는 네 배로 접어야 합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | 레이어 리소스 키를 가져옵니다. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/length/) { get; } | 레이어 리소스 길이를 바이트 단위로 가져옵니다. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | 레이어 리소스에 필요한 최소 PSD 버전을 가져옵니다. 0은 제한이 없음을 나타냅니다. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | 서명을 가져옵니다. |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/version/) { get; } | 버전을 가져옵니다. 기본값은 2입니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [GetChannel](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/getchannel/)(int) | 채널을 가져옵니다. |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/save/)(StreamContainer, int) | 리소스를 지정된 스트림 컨테이너에 저장합니다. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | 이 인스턴스를 나타내는 문자열을 반환합니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/typetoolkey/) | 타입 툴 정보 키. |

### 또 보기

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


