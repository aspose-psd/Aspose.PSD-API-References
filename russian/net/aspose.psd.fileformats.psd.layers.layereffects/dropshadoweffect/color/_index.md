---
title: "DropShadowEffect.Color"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Свойство DropShadowEffect. Возвращает или задает цвет"
type: docs
weight: 30
url: /ru/net/aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/color/
---
{{< psd/tize >}}
## DropShadowEffect.Color property

Получает или задает цвет.

```csharp
public Color Color { get; set; }
```

### Property Value

Цвет.

## Примеры

Следующий код демонстрирует использование свойства Opacity у DropShadowEffect.

```csharp
[C#]

string inputFile = "input.psd";
string outputImage20 = "outputImage20.png";
string outputImage200 = "outputImage200.png";

using (PsdImage psdImage = (PsdImage)Image.Load(inputFile, new LoadOptions()))
{
    Layer workLayer = psdImage.Layers[1];

    DropShadowEffect dropShadowEffect = workLayer.BlendingOptions.AddDropShadow();
    dropShadowEffect.Distance = 0;
    dropShadowEffect.Size = 8;

    // Пример с Opacity = 20
    dropShadowEffect.Opacity = 20;
    psdImage.Save(outputImage20, new PngOptions());

    // Пример с Opacity = 200
    dropShadowEffect.Opacity = 200;
    psdImage.Save(outputImage200, new PngOptions());
}
```

### См. также

* struct [Color](../../../aspose.psd/color/)
* class [DropShadowEffect](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../../)


