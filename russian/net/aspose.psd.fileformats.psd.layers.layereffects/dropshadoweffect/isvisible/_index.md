---
title: DropShadowEffect.IsVisible
second_title: Справочник по Aspose.PSD для .NET API
description: DropShadowEffect свойство. Получает или задает значение указывающее виден ли этот экземпляр.
type: docs
weight: 60
url: /ru/net/aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/isvisible/
---
## DropShadowEffect.IsVisible property

Получает или задает значение, указывающее, виден ли этот экземпляр.

```csharp
public bool IsVisible { get; set; }
```

### Стоимость имущества

`истинный` если этот экземпляр виден; в противном случае,`ЛОЖЬ` .

### Примеры

Следующий код демонстрирует использование свойства Opacity DropShadowEffect.

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

    // Пример с непрозрачностью = 20
    dropShadowEffect.Opacity = 20;
    psdImage.Save(outputImage20, new PngOptions());

    // Пример с непрозрачностью = 200
    dropShadowEffect.Opacity = 200;
    psdImage.Save(outputImage200, new PngOptions());
}
```

### Смотрите также

* class [DropShadowEffect](../)
* пространство имен [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../dropshadoweffect/)
* сборка [Aspose.PSD](../../../)


