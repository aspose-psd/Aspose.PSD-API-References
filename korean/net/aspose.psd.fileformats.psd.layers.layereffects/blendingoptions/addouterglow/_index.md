---
title: BlendingOptions.AddOuterGlow
second_title: .NET API 참조용 Aspose.PSD
description: BlendingOptions 방법. 외부 광선 효과를 추가합니다.
type: docs
weight: 60
url: /ko/net/aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addouterglow/
---
## BlendingOptions.AddOuterGlow method

외부 광선 효과를 추가합니다.

```csharp
public OuterGlowEffect AddOuterGlow()
```

### 반환 값

생성됨[`OuterGlowEffect`](../../outergloweffect/) object

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

* class [OuterGlowEffect](../../outergloweffect/)
* class [BlendingOptions](../)
* 네임스페이스 [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../blendingoptions/)
* 집회 [Aspose.PSD](../../../)


