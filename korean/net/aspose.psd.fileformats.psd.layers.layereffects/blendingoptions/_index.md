---
title: Class BlendingOptions
second_title: .NET API 참조용 Aspose.PSD
description: Aspose.PSD.FileFormats.Psd.Layers.LayerEffects.BlendingOptions 수업. 혼합 옵션. Layer effects 에 대한 API를 제공하는 Lfx2Resource의 래퍼입니다.
type: docs
weight: 2100
url: /ko/net/aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/
---
## BlendingOptions class

혼합 옵션. Layer effects 에 대한 API를 제공하는 Lfx2Resource의 래퍼입니다.

```csharp
public class BlendingOptions
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [Effects](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/effects/) { get; } | 효과를 얻습니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| [AddColorOverlay](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addcoloroverlay/)() | 색상 오버레이를 추가합니다. |
| [AddDropShadow](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/adddropshadow/)() | 그림자 효과를 추가합니다. |
| [AddGradientOverlay](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addgradientoverlay/)() | 그라디언트 오버레이를 추가합니다. |
| [AddInnerShadow](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addinnershadow/)() | 내부 그림자 효과를 추가합니다. |
| [AddOuterGlow](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addouterglow/)() | 외부 광선 효과를 추가합니다. |
| [AddPatternOverlay](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addpatternoverlay/)() | 패턴 오버레이를 추가합니다. |
| [AddStroke](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addstroke/)(FillType) | 스트로크 효과를 추가합니다. |

### 예

다음 코드는 내부 그림자 레이어 효과의 설정을 변경하는 방법을 보여줍니다.

```csharp
[C#]

string sourceFile = "example.psd";
string outputFile = "sample_out.psd";

// 기존 이미지를 PsdImage 클래스의 인스턴스로 로드
var loadOptions = new PsdLoadOptions();
loadOptions.LoadEffectsResource = true;
using (var image = (PsdImage)Image.Load(sourceFile, loadOptions))
{
    var layer = image.Layers[image.Layers.Length - 1];
    var shadowEffect = (IShadowEffect)layer.BlendingOptions.Effects[0];

    shadowEffect.Color = Color.Green;
    shadowEffect.Opacity = 128;
    shadowEffect.Distance = 1;
    shadowEffect.UseGlobalLight = false;
    shadowEffect.Size = 2;
    shadowEffect.Angle = 45;
    shadowEffect.Spread = 50;
    shadowEffect.Noise = 5;

    image.Save(outputFile, new PsdOptions(image));
}
```

### 또한보십시오

* 네임스페이스 [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../aspose.psd.fileformats.psd.layers.layereffects/)
* 집회 [Aspose.PSD](../../)


