---
title: "DropShadowEffect.Angle"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Свойство DropShadowEffect. Возвращает или задает угол в градусах"
type: docs
weight: 10
url: /ru/net/aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/angle/
---
{{< psd/tize >}}
## DropShadowEffect.Angle property

Получает или задает угол в градусах.

```csharp
public int Angle { get; set; }
```

### Property Value

Угол.

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

* class [DropShadowEffect](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../../)


