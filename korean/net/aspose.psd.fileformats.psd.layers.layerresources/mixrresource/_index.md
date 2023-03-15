---
title: Class MixrResource
second_title: .NET API 참조용 Aspose.PSD
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.MixrResource 수업. 클래스 MixrResource. 채널 믹서 조정의 리소스 Layer
type: docs
weight: 2820
url: /ko/net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/
---
## MixrResource class

클래스 MixrResource. 채널 믹서 조정의 리소스 Layer

```csharp
public sealed class MixrResource : AdjustmentLayerResource
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [MixrResource](mixrresource/#constructor)() | 의 새 인스턴스를 초기화합니다.`MixrResource` class. PSD 형식 사양에는 다음 설명이 포함됩니다. 4 * 2바이트 색상과 2바이트 상수. |
| [MixrResource](mixrresource/#constructor_1)(byte[]) | 의 새 인스턴스를 초기화합니다.`MixrResource` class. PSD 형식 사양에는 다음 설명이 포함됩니다. 4 * 2바이트 색상과 2바이트 상수. |

## 속성

| 이름 | 설명 |
| --- | --- |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/key/) { get; } | 레이어 리소스 키를 가져옵니다. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/length/) { get; } | 레이어 리소스 길이를 바이트 단위로 가져옵니다. |
| [Monochrome](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/monochrome/) { get; set; } | 이 여부를 나타내는 값을 가져오거나 설정합니다.`MixrResource` 단색입니다. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/psdversion/) { get; } | psd 버전을 가져옵니다. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/signature/) { get; } | 서명을 받습니다. |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/version/) { get; set; } | 버전을 가져오거나 설정합니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| [GetChannelInfo](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/getchannelinfo/)(int) | 채널 정보 raw data 를 가져옵니다. |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/save/)(StreamContainer, int) | 리소스를 지정된 스트림 컨테이너에 저장합니다. |
| [SetChannelInfo](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/setchannelinfo/)(int, byte[]) | 채널 정보를 설정합니다. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | 반환String 이 instance. 를 나타냅니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/typetoolkey/) | 유형 도구 정보 키입니다. |

### 또한보십시오

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* 네임스페이스 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* 집회 [Aspose.PSD](../../)


