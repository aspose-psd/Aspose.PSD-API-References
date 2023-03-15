---
title: OuterGlowEffect.BlendMode
second_title: .NET API 참조용 Aspose.PSD
description: OuterGlowEffect 재산. 혼합 모드를 가져오거나 설정합니다.
type: docs
weight: 10
url: /ko/net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/blendmode/
---
## OuterGlowEffect.BlendMode property

혼합 모드를 가져오거나 설정합니다.

```csharp
public BlendMode BlendMode { get; set; }
```

### 자산 가치

혼합 모드입니다.

### 예

다음 코드는 OuterGlowEffect 지원을 보여줍니다.

```csharp
[C#]

string src = "GreenLayer.psd";
string outputPng = "output261.png";

using (var image = (PsdImage)Image.Load(src))
{
    OuterGlowEffect effect = image.Layers[1].BlendingOptions.AddOuterGlow();
    effect.Range = 10;
    effect.Spread = 10;
    ((IColorFillSettings)effect.FillColor).Color = Color.Red;
    effect.Opacity = 128;
    effect.BlendMode = BlendMode.Normal;

    image.Save(outputPng, new PngOptions());
}
```

### 또한보십시오

* enum [BlendMode](../../../aspose.psd.fileformats.core.blending/blendmode/)
* class [OuterGlowEffect](../)
* 네임스페이스 [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../outergloweffect/)
* 집회 [Aspose.PSD](../../../)


