---
title: "클래스 InnerShadowEffect"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerEffects.InnerShadowEffect 클래스. 내부 그림자 레이어 효과"
type: docs
weight: 2350
url: /ko/net/aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/
---
{{< psd/tize >}}
## InnerShadowEffect class

내부 섀도우 레이어 효과

```csharp
public class InnerShadowEffect : IShadowEffect
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [Angle](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/angle/) { get; set; } | 각도를 도 단위로 가져오거나 설정합니다. |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/blendmode/) { get; set; } | 블렌드 모드를 가져오거나 설정합니다. |
| [Color](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/color/) { get; set; } | 색상을 가져오거나 설정합니다. |
| [Distance](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/distance/) { get; set; } | 거리를 픽셀 단위로 가져오거나 설정합니다. |
| [EffectType](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/effecttype/) { get; } | 효과 유형을 가져옵니다. |
| [IsVisible](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/isvisible/) { get; set; } | 이 인스턴스가 표시되는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [Noise](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/noise/) { get; set; } | 노이즈를 가져오거나 설정합니다. |
| [Opacity](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/opacity/) { get; set; } | 불투명도를 가져오거나 설정합니다. |
| [Size](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/size/) { get; set; } | 블러 값을 픽셀 단위로 가져오거나 설정합니다. |
| [Spread](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/spread/) { get; set; } | 퍼짐(차단)을 백분율로 가져오거나 설정합니다. |
| [UseGlobalLight](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/usegloballight/) { get; set; } | 값을 가져오거나 설정하여 [use this angle in all of the layer effects] 여부를 나타냅니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [GetEffectBounds](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/geteffectbounds/)(Rectangle, int) | 입력 레이어 픽셀 경계를 기반으로 효과 픽셀의 경계를 계산하고 가져옵니다. |

## 예제

다음 코드는 내부 그림자 레이어 효과의 설정을 변경하는 방법을 보여줍니다.

```csharp
[C#]

string sourceFile = "example.psd";
string outputFile = "sample_out.psd";

// 기존 이미지를 PsdImage 클래스의 인스턴스로 로드합니다.
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

### 또 보기

* interface [IShadowEffect](../ishadoweffect/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../)


