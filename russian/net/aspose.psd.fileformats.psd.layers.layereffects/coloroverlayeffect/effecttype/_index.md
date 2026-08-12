---
title: "ColorOverlayEffect.EffectType"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Свойство ColorOverlayEffect. Получает тип эффекта."
type: docs
weight: 30
url: /ru/net/aspose.psd.fileformats.psd.layers.layereffects/coloroverlayeffect/effecttype/
---
{{< psd/tize >}}
## ColorOverlayEffect.EffectType property

Получает тип эффекта.

```csharp
public LayerEffectsTypes EffectType { get; }
```

## Примеры

Следующий код демонстрирует поддержку свойства ILayerEffect.EffectType.

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
            // это поймано
            psdImage.Save(outputWith, new PngOptions());
        }
    }
}
```

### См. также

* enum [LayerEffectsTypes](../../layereffectstypes/)
* class [ColorOverlayEffect](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../../)


