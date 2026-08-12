---
title: "IGradientFillSettings.Scale"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Свойство IGradientFillSettings. Возвращает или задает нормализованную шкалу градиента в процентах"
type: docs
weight: 90
url: /ru/net/aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/scale/
---
{{< psd/tize >}}
## IGradientFillSettings.Scale property

Получает или задает **нормализованный** масштаб градиента (в процентах).

```csharp
public int Scale { get; set; }
```

### Property Value

Масштаб.

## Примеры

В следующем примере демонстрируется, как использовать свойство Scale для масштабирования FillLayer с градиентом.

```csharp
[C#]

string sourceFileName = "FillLayerGradient.psd";
string output = "scaledImage.png";

using (var image = (PsdImage)Image.Load(sourceFileName))
{
    // получение FillLayer
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

    // обновление значения масштаба
    settings.Scale = 200;
    fillLayer.Update(); // Updates pixels data

    image.Save(output, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### См. также

* interface [IGradientFillSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../../aspose.psd.fileformats.psd.layers.fillsettings/)
* assembly [Aspose.PSD](../../../)


