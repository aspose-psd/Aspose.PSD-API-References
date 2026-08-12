---
title: "WarpSettings.ProcessingArea"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Свойство WarpSettings. Получает или задает значение размера области обработки. Значение по умолчанию 10. Диапазон 240"
type: docs
weight: 40
url: /ru/net/aspose.psd.fileformats.psd.layers.warp/warpsettings/processingarea/
---
{{< psd/tize >}}
## WarpSettings.ProcessingArea property

Получает или задает значение размера области обработки. Значение по умолчанию — 10. Диапазон: [2;40]

```csharp
public int ProcessingArea { get; set; }
```

## Примеры

В следующем коде демонстрируется свойство WarpSettings.ProcessingArea для настройки деформации искажения.

```csharp
[C#]

string sourceFile = "Warping.psd";
List<string> outputFiles = new List<string>();

PsdLoadOptions loadOptions = new PsdLoadOptions() { LoadEffectsResource = true, AllowWarpRepaint = true };

int[] areaValues = { 5, 10, 25, 40 };

for (int i = 0; i < 4; i++)
{
    using (var psdImage = (PsdImage)Image.Load(sourceFile, loadOptions))
    {
        // Он получает WarpSettings из Smart Layer
        WarpSettings warpSettings = ((SmartObjectLayer)psdImage.Layers[1]).WarpSettings;

        // Он задает размер области обработки искажения
        warpSettings.ProcessingArea = areaValues[i];
        ((SmartObjectLayer)psdImage.Layers[1]).WarpSettings = warpSettings;

        string outputFile = "export" + areaValues[i] + ".png";
        outputFiles.Add(outputFile);

        // Здесь не должно быть ошибок
        psdImage.Save(outputFile, new PngOptions { ColorType = PngColorType.TruecolorWithAlpha });
    }
}
```

### См. также

* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)


