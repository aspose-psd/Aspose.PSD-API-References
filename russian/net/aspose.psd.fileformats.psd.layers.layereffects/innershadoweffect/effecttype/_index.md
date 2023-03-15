---
title: InnerShadowEffect.EffectType
second_title: Справочник по Aspose.PSD для .NET API
description: InnerShadowEffect свойство. Получает тип эффекта
type: docs
weight: 50
url: /ru/net/aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/effecttype/
---
## InnerShadowEffect.EffectType property

Получает тип эффекта

```csharp
public LayerEffectsTypes EffectType { get; }
```

### Примеры

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
            // он поймал
            psdImage.Save(outputWith, new PngOptions());
        }
    }
}
```

### Смотрите также

* enum [LayerEffectsTypes](../../../aspose.psd.fileformats.psd.layers.layerresources.lfx2resources/layereffectstypes/)
* class [InnerShadowEffect](../)
* пространство имен [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../innershadoweffect/)
* сборка [Aspose.PSD](../../../)


