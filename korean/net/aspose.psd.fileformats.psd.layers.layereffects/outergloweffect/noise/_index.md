---
title: "OuterGlowEffect.Noise"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "OuterGlowEffect 속성. 노이즈를 가져오거나 설정합니다."
type: docs
weight: 90
url: /ko/net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/noise/
---
{{< psd/tize >}}
## OuterGlowEffect.Noise property

노이즈를 가져오거나 설정합니다.

```csharp
public int Noise { get; set; }
```

### Property Value

노이즈입니다.

### 예외

| 예외 | 조건 |
| --- | --- |
| [PsdImageArgumentException](../../../aspose.psd.coreexceptions.imageformats/psdimageargumentexception/) | 노이즈는 0에서 100 사이의 백분율로 지정해야 합니다. |

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

* class [OuterGlowEffect](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../../)


