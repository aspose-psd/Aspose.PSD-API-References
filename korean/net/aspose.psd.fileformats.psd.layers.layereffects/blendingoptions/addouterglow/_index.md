---
title: "BlendingOptions.AddOuterGlow"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "BlendingOptions 메서드. 외부 글로우 효과를 추가합니다"
type: docs
weight: 70
url: /ko/net/aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addouterglow/
---
{{< psd/tize >}}
## BlendingOptions.AddOuterGlow method

외부 글로우 효과를 추가합니다.

```csharp
public OuterGlowEffect AddOuterGlow()
```

### 반환 값

생성된 [`OuterGlowEffect`](../../outergloweffect/) 객체

## 예제

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

### 또 보기

* class [OuterGlowEffect](../../outergloweffect/)
* class [BlendingOptions](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../../)


