---
title: OuterGlowEffect.FillColor
second_title: Справочник по Aspose.PSD для .NET API
description: OuterGlowEffect свойство. Получает или задает цвет.
type: docs
weight: 30
url: /ru/net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/fillcolor/
---
## OuterGlowEffect.FillColor property

Получает или задает цвет.

```csharp
public IFillSettings FillColor { get; set; }
```

### Стоимость имущества

Цвет.

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

* interface [IFillSettings](../../../aspose.psd.fileformats.psd.layers.fillsettings/ifillsettings/)
* class [OuterGlowEffect](../)
* пространство имен [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../outergloweffect/)
* сборка [Aspose.PSD](../../../)


