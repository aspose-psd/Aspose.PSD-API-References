---
title: "WarpSettings.RenderQuality"
second_title: "Справочник API Aspose.PSD для .NET"
description: "WarpSettings свойство. Получает или задает значение качества рендеринга искажения между скоростью и качеством"
type: docs
weight: 50
url: /ru/net/aspose.psd.fileformats.psd.layers.warp/warpsettings/renderquality/
---
{{< psd/tize >}}
## WarpSettings.RenderQuality property

Получает или задает значение качества рендеринга искажения — между скоростью и качеством

```csharp
public RenderQuality RenderQuality { get; set; }
```

## Примеры

Следующий код демонстрирует свойство WarpSettings.RenderQuality для настройки деформации искажения.

```csharp
[C#]

string sourceFile = "Warping.psd";
List<string> outputFiles = new List<string>();

PsdLoadOptions loadOptions = new PsdLoadOptions() { LoadEffectsResource = true, AllowWarpRepaint = true };

RenderQuality[] qualityValues = { RenderQuality.Turbo, RenderQuality.Fast, RenderQuality.Normal, RenderQuality.Excellent };

for (int i = 0; i < 4; i++)
{
    using (var psdImage = (PsdImage)Image.Load(sourceFile, loadOptions))
    {
        // Он получает WarpSettings из Smart Layer
        WarpSettings warpSettings = ((SmartObjectLayer)psdImage.Layers[1]).WarpSettings;

        // Он задает размер области обработки искажения
        warpSettings.RenderQuality = qualityValues[i];
        ((SmartObjectLayer)psdImage.Layers[1]).WarpSettings = warpSettings;

        string outputFile = "export" + qualityValues[i].ToString() + ".png";
        outputFiles.Add(outputFile);

        // Здесь не должно быть ошибок
        psdImage.Save(outputFile, new PngOptions { ColorType = PngColorType.TruecolorWithAlpha });
    }
}
```

### См. также

* enum [RenderQuality](../../renderquality/)
* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)


