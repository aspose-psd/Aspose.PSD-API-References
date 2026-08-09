---
title: "PatternOverlayEffect.EffectType"
second_title: "Aspose.PSD for .NET API 参考"
description: "PatternOverlayEffect 属性。获取效果类型"
type: docs
weight: 20
url: /zh/net/aspose.psd.fileformats.psd.layers.layereffects/patternoverlayeffect/effecttype/
---
{{< psd/tize >}}
## PatternOverlayEffect.EffectType property

获取效果类型

```csharp
public LayerEffectsTypes EffectType { get; }
```

## 示例

以下代码演示了对 ILayerEffect.EffectType 属性的支持。

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
            // 已捕获
            psdImage.Save(outputWith, new PngOptions());
        }
    }
}
```

### 另请参阅

* enum [LayerEffectsTypes](../../layereffectstypes/)
* class [PatternOverlayEffect](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../../)


