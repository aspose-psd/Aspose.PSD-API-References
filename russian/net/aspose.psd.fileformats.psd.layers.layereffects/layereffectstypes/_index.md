---
title: "Перечисление LayerEffectsTypes"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerEffects.LayerEffectsTypes перечисление. Эффекты смешивания слоёв"
type: docs
weight: 2360
url: /ru/net/aspose.psd.fileformats.psd.layers.layereffects/layereffectstypes/
---
{{< psd/tize >}}
## LayerEffectsTypes enumeration

Эффекты наложения слоёв.

```csharp
public enum LayerEffectsTypes
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| DropShadow | `0` | Тень. |
| OuterGlow | `1` | Внешнее свечение. |
| PatternOverlay | `2` | Наложение узора. |
| GradientOverlay | `3` | Наложение градиента. |
| ColorOverlay | `4` | Наложение цвета. |
| Satin | `5` | Тип атласного эффекта. |
| InnerGlow | `6` | Внутреннее свечение. |
| InnerShadow | `7` | Внутренняя тень. |
| Stroke | `8` | Обводка. |
| BevelEmboss | `9` | Фаска. |

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

* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../)


