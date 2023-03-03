---
title: Class LevlResource
second_title: .NET API 참조용 Aspose.PSD
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LevlResource 수업. 클래스 레벨 리소스. 노출 조정 리소스 Layer
type: docs
weight: 2640
url: /ko/net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/
---
## LevlResource class

클래스 레벨 리소스. 노출 조정 리소스 Layer

```csharp
public class LevlResource : AdjustmentLayerResource
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [LevlResource](levlresource/#constructor)() | 의 새 인스턴스를 초기화합니다.`LevlResource` 클래스. |
| [LevlResource](levlresource/#constructor_1)(byte[]) | 의 새 인스턴스를 초기화합니다.`LevlResource` class. GrayScale, Duotone, RGB, CMYK, Lab 색상 모드에서 지원 2바이트 - 버전(=2) 29 * 10바이트 - 5개의 짧은 정수가 있는 레벨 레코드 세트 4바이트 - Lvls 헤더(인덱스 292에서 시작) 2바이트 - 버전(=3) 2바이트 - 총 레벨 카운트 record 10 * (총 카운트 - 29) Lvls 리소스의 제로 엔딩은 4도 접어야 함 |

## 속성

| 이름 | 설명 |
| --- | --- |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/key/) { get; } | 레이어 리소스 키를 가져옵니다. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/length/) { get; } | 레이어 리소스 길이를 바이트 단위로 가져옵니다. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/psdversion/) { get; } | psd 버전을 가져옵니다. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/signature/) { get; } | 서명을 받습니다. |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/version/) { get; } | 버전을 가져옵니다. 기본값은 2 입니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| [GetChannel](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/getchannel/)(int) | 채널을 가져옵니다. |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/save/)(StreamContainer, int) | 리소스를 지정된 스트림 컨테이너에 저장합니다. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | 반환String 이 instance. 를 나타냅니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/typetoolkey/) | 유형 도구 정보 키입니다. |

### 또한보십시오

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* 네임스페이스 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* 집회 [Aspose.PSD](../../)


