---
title: OuterGlowEffect.BlendMode
second_title: Справочник по Aspose.PSD для .NET API
description: OuterGlowEffect свойство. Получает или задает режим наложения.
type: docs
weight: 10
url: /ru/net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/blendmode/
---
## OuterGlowEffect.BlendMode property

Получает или задает режим наложения.

```csharp
public BlendMode BlendMode { get; set; }
```

### Стоимость имущества

Режим наложения.

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

* enum [BlendMode](../../../aspose.psd.fileformats.core.blending/blendmode/)
* class [OuterGlowEffect](../)
* пространство имен [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../outergloweffect/)
* сборка [Aspose.PSD](../../../)


