---
title: Class PhflResource
second_title: .NET API 참조용 Aspose.PSD
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.PhflResource 수업. 클래스 PhflResource. 노출 조정 리소스 Layer 2 버전  3  또는   2  12 XYZ 색상에 대해 각각 4바이트버전 3에서만 10 2바이트 색상 공간 다음에 4  2바이트 색상 구성 요소버전 2에서만 4 밀도 1 광도 유지
type: docs
weight: 2890
url: /ko/net/aspose.psd.fileformats.psd.layers.layerresources/phflresource/
---
## PhflResource class

클래스 PhflResource. 노출 조정 리소스 Layer 2 버전( = 3 ) 또는 ( = 2 ) 12 XYZ 색상에 대해 각각 4바이트(버전 3에서만) 10 2바이트 색상 공간 다음에 4 * 2바이트 색상 구성 요소(버전 2에서만) 4 밀도 1 광도 유지

```csharp
public abstract class PhflResource : AdjustmentLayerResource
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [Density](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/density/) { get; set; } | 밀도를 가져오거나 설정합니다. |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/key/) { get; } | 레이어 리소스 키를 가져옵니다. |
| abstract [Length](../../aspose.psd.fileformats.psd.layers/layerresource/length/) { get; } | 레이어 리소스 길이를 바이트 단위로 가져옵니다. |
| [PreserveLuminosity](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/preserveluminosity/) { get; set; } | [광도 유지]. 여부를 나타내는 값을 가져오거나 설정합니다. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/psdversion/) { get; } | psd 버전을 가져옵니다. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/signature/) { get; } | 서명을 받습니다. |
| abstract [Version](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/version/) { get; } | 버전을 가져옵니다. 기본값은 2 또는 3 입니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| abstract [GetRgbColor](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/getrgbcolor/)() | RGB의 색상을 가져옵니다. |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/save/)(StreamContainer, int) | 리소스를 지정된 스트림 컨테이너에 저장합니다. |
| abstract [SetRgbColor](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/setrgbcolor/)(Color) | RGB 색상을 설정합니다. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | 반환String 이 instance. 를 나타냅니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/typetoolkey/) | 유형 도구 정보 키입니다. |

### 또한보십시오

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* 네임스페이스 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* 집회 [Aspose.PSD](../../)


