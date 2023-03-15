---
title: OuterGlowEffect.Size
second_title: Справочник по Aspose.PSD для .NET API
description: OuterGlowEffect свойство. Получает значение размытия в пикселях.
type: docs
weight: 120
url: /ru/net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/size/
---
## OuterGlowEffect.Size property

Получает значение размытия в пикселях.

```csharp
public int Size { get; }
```

### Стоимость имущества

Размер.

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


