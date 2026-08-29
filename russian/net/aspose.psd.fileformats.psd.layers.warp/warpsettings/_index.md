---
title: "Класс WarpSettings"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Класс Aspose.PSD.FileFormats.Psd.Layers.Warp.WarpSettings. Параметры слоя с искажением"
type: docs
weight: 4010
url: /ru/net/aspose.psd.fileformats.psd.layers.warp/warpsettings/
---
{{< psd/tize >}}
## WarpSettings class

Параметры слоя с искажением.

```csharp
public class WarpSettings
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [WarpSettings](warpsettings/#constructor_1)(PlacedResource) | Инициализирует новый экземпляр класса `WarpSettings`. |
| [WarpSettings](warpsettings/#constructor)(OSTypeStructure[], Rectangle) | Инициализирует новый экземпляр класса `WarpSettings`. |
| [WarpSettings](warpsettings/#constructor_2)(PointF[], Rectangle) | Инициализирует новый экземпляр класса `WarpSettings`. |
| [WarpSettings](warpsettings/#constructor_3)(PointF[], Rectangle, WarpStyles) | Инициализирует новый экземпляр класса `WarpSettings`. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Bounds](../../aspose.psd.fileformats.psd.layers.warp/warpsettings/bounds/) { get; } | Получает или задает границы изображения искажения |
| [GridSize](../../aspose.psd.fileformats.psd.layers.warp/warpsettings/gridsize/) { get; set; } | Получает или задает размер сетки искажения. По умолчанию 1. |
| [MeshPoints](../../aspose.psd.fileformats.psd.layers.warp/warpsettings/meshpoints/) { get; set; } | Точки сетки Photoshop |
| [RenderQuality](../../aspose.psd.fileformats.psd.layers.warp/warpsettings/renderquality/) { get; set; } | Получает или задает значение качества рендеринга искажения — между скоростью и качеством |
| [Rotate](../../aspose.psd.fileformats.psd.layers.warp/warpsettings/rotate/) { get; set; } | Получает или задает значение поворота |
| [Style](../../aspose.psd.fileformats.psd.layers.warp/warpsettings/style/) { get; set; } | Получает или задает стиль искажения |
| [Value](../../aspose.psd.fileformats.psd.layers.warp/warpsettings/value/) { get; set; } | Получает или задает значение искажения |

## Примеры

Следующий код демонстрирует, как управлять WarpSettings для выполнения трансформации искажения на SmartObjectLayer и TexLayer.

```csharp
[C#]

string sourceFile = "smart_without_warp.psd";

var opt = new PsdLoadOptions()
{
    LoadEffectsResource = true,
    AllowWarpRepaint = true
};

string[] outputImageFile = new string[4];
string[] outputPsdFile = new string[4];

for (int caseIndex = 0; caseIndex < outputImageFile.Length; caseIndex++)
{
    outputImageFile[caseIndex] = "export_" + caseIndex + ".png";
    outputPsdFile[caseIndex] = "export_" + caseIndex + ".psd";

    using (PsdImage img = (PsdImage)Image.Load(sourceFile, opt))
    {
        foreach (Layer layer in img.Layers)
        {
            if (layer is SmartObjectLayer)
            {
                var smartLayer = (SmartObjectLayer)layer;
                smartLayer.WarpSettings = GetWarpSettingsByIndex(smartLayer.WarpSettings, caseIndex);
            }

            if (layer is TextLayer)
            {
                var textLayer = (TextLayer)layer;

                if (caseIndex != 3)
                {
                    textLayer.WarpSettings = GetWarpSettingsByIndex(textLayer.WarpSettings, caseIndex);
                }
            }
        }

        img.Save(outputPsdFile[caseIndex], new PsdOptions());
    }

    using (PsdImage img = (PsdImage)Image.Load(outputPsdFile[caseIndex], opt))
    {
        img.Save(outputImageFile[caseIndex],
            new PngOptions() { CompressionLevel = 9, ColorType = PngColorType.TruecolorWithAlpha });
    }
}

WarpSettings GetWarpSettingsByIndex(WarpSettings warpParams, int caseIndex)
{
    switch (caseIndex)
    {
        case 0:
            warpParams.Style = WarpStyles.Rise;
            warpParams.Rotate = WarpRotates.Horizontal;
            warpParams.Value = 20;
            break;
        case 1:
            warpParams.Style = WarpStyles.Rise;
            warpParams.Rotate = WarpRotates.Vertical;
            warpParams.Value = 10;
            break;
        case 2:
            warpParams.Style = WarpStyles.Flag;
            warpParams.Rotate = WarpRotates.Horizontal;
            warpParams.Value = 30;
            break;
        case 3:
            warpParams.Style = WarpStyles.Custom;
            warpParams.MeshPoints[2].Y += 70;
            break;
    }

    return warpParams;
}
```

### См. также

* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../)


