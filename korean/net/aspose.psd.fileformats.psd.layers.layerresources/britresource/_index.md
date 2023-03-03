---
title: Class BritResource
second_title: .NET API 참조용 Aspose.PSD
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.BritResource 수업. 클래스 BritResource. 밝기/대비 조정 레이어 리소스
type: docs
weight: 2340
url: /ko/net/aspose.psd.fileformats.psd.layers.layerresources/britresource/
---
## BritResource class

클래스 BritResource. 밝기/대비 조정 레이어 리소스

```csharp
public class BritResource : AdjustmentLayerResource
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [BritResource](britresource/#constructor)() | 의 새 인스턴스를 초기화합니다.`BritResource` 클래스. |
| [BritResource](britresource/#constructor_1)(byte[]) | 의 새 인스턴스를 초기화합니다.`BritResource`class. PSD 형식 사양에는 다음 설명이 포함되어 있습니다. 2 Brightness 2 Contrast 2 밝기 및 대비의 평균값 1 Lab color only CgEd가 있는 최신 PSD(CS5 이상)에서는 사용되지 않습니다. CgEd는 정보 properties 를 저장합니다. |
| [BritResource](britresource/#constructor_2)(short, short, short, bool) | 의 새 인스턴스를 초기화합니다.`BritResource` 클래스. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Brightness](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/brightness/) { get; set; } | 밝기를 가져오거나 설정합니다. |
| [Contrast](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/contrast/) { get; set; } | 대비를 가져오거나 설정합니다. |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/key/) { get; } | 레이어 리소스 키를 가져옵니다. |
| [LabColor](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/labcolor/) { get; set; } | [실험실 색상]. 여부를 나타내는 값을 가져오거나 설정합니다. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/length/) { get; } | 레이어 리소스 길이를 바이트 단위로 가져옵니다. |
| [MeanValueForBrightnessAndContrast](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/meanvalueforbrightnessandcontrast/) { get; set; } | 밝기와 대비의 평균값을 가져오거나 설정합니다. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/psdversion/) { get; } | psd 버전을 가져옵니다. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/signature/) { get; } | 서명을 받습니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/save/)(StreamContainer, int) | 리소스를 지정된 스트림 컨테이너에 저장합니다. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | 반환String 이 instance. 를 나타냅니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/typetoolkey/) | 유형 도구 정보 키입니다. |

### 또한보십시오

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* 네임스페이스 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* 집회 [Aspose.PSD](../../)


