---
title: "ColorOverlayEffect.EffectType"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "ColorOverlayEffect property. 효과 유형을 가져옵니다"
type: docs
weight: 30
url: /ko/net/aspose.psd.fileformats.psd.layers.layereffects/coloroverlayeffect/effecttype/
---
{{< psd/tize >}}
## ColorOverlayEffect.EffectType property

효과 유형을 가져옵니다.

```csharp
public LayerEffectsTypes EffectType { get; }
```

## 예제

다음 코드는 ILayerEffect.EffectType 속성 지원을 보여줍니다.

```csharp
[C#]

string inputFile = "input.psd";
string outputWithout = "outputWithout.png";
string outputWith = "outputWith.png";

using (PsdImage psdImage = (PsdImage)Image.Load(inputFile, new LoadOptions()))
{
    psdImage.Save(outputWithout, new PngOptions());

    Layer workLayer = psdImage.Layers[1];

    DropShadowEffect dropShadowEffect = workLayer.BlendingOptions.AddDropShadow();
    dropShadowEffect.Distance = 0;
    dropShadowEffect.Size = 8;
    dropShadowEffect.Opacity = 20;

    foreach (ILayerEffect iEffect in workLayer.BlendingOptions.Effects)
    {
        if (iEffect.EffectType == LayerEffectsTypes.DropShadow)
        {
            // 포착되었습니다
            psdImage.Save(outputWith, new PngOptions());
        }
    }
}
```

### 또 보기

* enum [LayerEffectsTypes](../../layereffectstypes/)
* class [ColorOverlayEffect](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../../)


