---
title: IGradientFillSettings.Scale
second_title: Справочник по Aspose.PSD для .NET API
description: IGradientFillSettings свойство. Получает или задает масштаб.
type: docs
weight: 100
url: /ru/net/aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/scale/
---
## IGradientFillSettings.Scale property

Получает или задает масштаб.

```csharp
public int Scale { get; set; }
```

### Стоимость имущества

Масштаб.

### Примеры

В следующем примере показано, как использовать свойство Scale для масштабирования FillLayer с градиентом.

```csharp
[C#]

string sourceFileName = "FillLayerGradient.psd";
string output = "scaledImage.png";

using (var image = (PsdImage)Image.Load(sourceFileName))
{
    // получаем слой-заливку
    FillLayer fillLayer = null;
    foreach (var layer in image.Layers)
    {
        fillLayer = layer as FillLayer;
        if (fillLayer != null)
        {
            break;
        }
    }

    var settings = fillLayer.FillSettings as IGradientFillSettings;

    // обновить значение шкалы
    settings.Scale = 200;
    fillLayer.Update(); // Обновляет данные пикселей

    image.Save(output, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### Смотрите также

* interface [IGradientFillSettings](../)
* пространство имен [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../igradientfillsettings/)
* сборка [Aspose.PSD](../../../)


