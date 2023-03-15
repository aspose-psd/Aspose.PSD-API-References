---
title: OuterGlowEffect.Size
second_title: .NET API 참조용 Aspose.PSD
description: OuterGlowEffect 재산. 블러 값을 픽셀 단위로 가져옵니다.
type: docs
weight: 120
url: /ko/net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/size/
---
## OuterGlowEffect.Size property

블러 값을 픽셀 단위로 가져옵니다.

```csharp
public int Size { get; }
```

### 자산 가치

크기.

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

* class [OuterGlowEffect](../)
* 네임스페이스 [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../outergloweffect/)
* 집회 [Aspose.PSD](../../../)


