---
title: PatternOverlayEffect.EffectType
second_title: .NET API 참조용 Aspose.PSD
description: PatternOverlayEffect 재산. 효과 유형 가져오기 type
type: docs
weight: 20
url: /ko/net/aspose.psd.fileformats.psd.layers.layereffects/patternoverlayeffect/effecttype/
---
## PatternOverlayEffect.EffectType property

효과 유형 가져오기 type

```csharp
public LayerEffectsTypes EffectType { get; }
```

### 예

다음 코드는 ILayerEffect.EffectType 속성의 지원을 보여줍니다.

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
            // 걸렸다
            psdImage.Save(outputWith, new PngOptions());
        }
    }
}
```

### 또한보십시오

* enum [LayerEffectsTypes](../../../aspose.psd.fileformats.psd.layers.layerresources.lfx2resources/layereffectstypes/)
* class [PatternOverlayEffect](../)
* 네임스페이스 [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../patternoverlayeffect/)
* 집회 [Aspose.PSD](../../../)


