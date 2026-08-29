---
title: "OuterGlowEffect.FillColor"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "OuterGlowEffect 속성. 색상을 가져오거나 설정합니다."
type: docs
weight: 30
url: /ko/net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/fillcolor/
---
{{< psd/tize >}}
## OuterGlowEffect.FillColor property

색상을 가져오거나 설정합니다.

```csharp
public IFillSettings FillColor { get; set; }
```

### Property Value

색상.

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

* interface [IFillSettings](../../../aspose.psd.fileformats.psd.layers.fillsettings/ifillsettings/)
* class [OuterGlowEffect](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../../)


