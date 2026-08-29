---
title: "DropShadowEffect.IsVisible"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Свойство DropShadowEffect. Возвращает или задает значение, указывающее, видим ли данный экземпляр"
type: docs
weight: 60
url: /ru/net/aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/isvisible/
---
{{< psd/tize >}}
## DropShadowEffect.IsVisible property

Получает или задает значение, указывающее, видим ли этот экземпляр.

```csharp
public bool IsVisible { get; set; }
```

### Property Value

`true` если этот экземпляр видим; иначе `false`.

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


