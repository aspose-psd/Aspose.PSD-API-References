---
title: OuterGlowEffect.Jitter
second_title: Справочник по Aspose.PSD для .NET API
description: OuterGlowEffect свойство. Получает или задает шум.
type: docs
weight: 80
url: /ru/net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/jitter/
---
## OuterGlowEffect.Jitter property

Получает или задает шум.

```csharp
public int Jitter { get; set; }
```

### Стоимость имущества

Шум.

### Исключения

| исключение | условие |
| --- | --- |
| [PsdImageArgumentException](../../../aspose.psd.coreexceptions.imageformats/psdimageargumentexception/) | Шум должен быть указан в процентах в диапазоне от 0 до 100 |

### Примеры

Следующий код демонстрирует поддержку OuterGlowEffect.

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

### Смотрите также

* class [OuterGlowEffect](../)
* пространство имен [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../outergloweffect/)
* сборка [Aspose.PSD](../../../)


