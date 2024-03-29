---
title: OuterGlowEffect.Intensity
second_title: Справочник по Aspose.PSD для .NET API
description: OuterGlowEffect свойство. Получает или задает угол в градусах.
type: docs
weight: 40
url: /ru/net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/intensity/
---
## OuterGlowEffect.Intensity property

Получает или задает угол в градусах.

```csharp
public int Intensity { get; set; }
```

### Стоимость имущества

Угол.

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


