---
title: IGradientFillSettings
second_title: Справочник по Aspose.PSD для .NET API
description: Базовый интерфейс для настроек заливки
type: docs
weight: 1950
url: /ru/net/aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/
---
## IGradientFillSettings interface

Базовый интерфейс для настроек заливки

```csharp
public interface IGradientFillSettings : IFillSettings
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [AlignWithLayer](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/alignwithlayer) { get; set; } | Получает или задает значение, указывающее, следует ли [выравнивать со слоем]. |
| [Angle](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/angle) { get; set; } | Получает или задает угол. |
| [Color](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/color) { get; set; } | Получает или задает цвет. |
| [ColorPoints](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/colorpoints) { get; set; } | Получает точки цвета. |
| [Dither](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/dither) { get; set; } | Получает или задает значение, указывающее, является ли это[`IGradientFillSettings`](../igradientfillsettings)дизерингом. |
| [GradientName](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/gradientname) { get; set; } | Получает или задает имя градиента. |
| [GradientType](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/gradienttype) { get; set; } | Получает или задает тип градиента. |
| [HorizontalOffset](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/horizontaloffset) { get; set; } | Получает или задает смещение по горизонтали. |
| [Reverse](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/reverse) { get; set; } | Получает или задает значение, указывающее, является ли это[`IGradientFillSettings`](../igradientfillsettings)обратным. |
| [Scale](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/scale) { get; set; } | Получает или задает масштаб. |
| [TransparencyPoints](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/transparencypoints) { get; set; } | Получает очки прозрачности. |
| [VerticalOffset](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/verticaloffset) { get; set; } | Получает или задает вертикальное смещение. |

### Примеры

Следующий пример демонстрирует поддержку Gradient FillLayer и параметры редактирования IGradientFillSettings..

```csharp
[C#]

string sourceFileName = "ComplexGradientFillLayer.psd";
string outputFile = "ComplexGradientFillLayer_output.psd";
var im = (PsdImage)Image.Load(sourceFileName);
using (im)
{
    foreach (var layer in im.Layers)
    {
        if (layer is FillLayer)
        {
            var fillLayer = (FillLayer)layer;
            if (fillLayer.FillSettings.FillType != FillType.Gradient)
            {
                throw new Exception("Wrong Fill Layer");
            }
            var settings = (IGradientFillSettings)fillLayer.FillSettings;
            if (
             Math.Abs(settings.Angle - 45) > 0.25 ||
             settings.Dither != true ||
             settings.AlignWithLayer != false ||
             settings.Reverse != false ||
             Math.Abs(settings.HorizontalOffset - (-39)) > 0.25 ||
             Math.Abs(settings.VerticalOffset - (-5)) > 0.25 ||
             settings.TransparencyPoints.Length != 3 ||
             settings.ColorPoints.Length != 2 ||
             Math.Abs(100.0 - settings.TransparencyPoints[0].Opacity) > 0.25 ||
             settings.TransparencyPoints[0].Location != 0 ||
             settings.TransparencyPoints[0].MedianPointLocation != 50 ||
             settings.ColorPoints[0].Color != Color.FromArgb(203, 64, 140) ||
             settings.ColorPoints[0].Location != 0 ||
             settings.ColorPoints[0].MedianPointLocation != 50)
            {
                throw new Exception("Gradient Fill was not read correctly");
            }
            settings.Angle = 0.0;
            settings.Dither = false;
            settings.AlignWithLayer = true;
            settings.Reverse = true;
            settings.HorizontalOffset = 25;
            settings.VerticalOffset = -15;
            var colorPoints = new List<IGradientColorPoint>(settings.ColorPoints);
            var transparencyPoints = new List<IGradientTransparencyPoint>(settings.TransparencyPoints);
            colorPoints.Add(new GradientColorPoint()
            {
                Color = Color.Violet,
                Location = 4096,
                MedianPointLocation = 75
            });
            colorPoints[1].Location = 3000;
            transparencyPoints.Add(new GradientTransparencyPoint()
            {
                Opacity = 80.0,
                Location = 4096,
                MedianPointLocation = 25
            });
            transparencyPoints[2].Location = 3000;
            settings.ColorPoints = colorPoints.ToArray();
            settings.TransparencyPoints = transparencyPoints.ToArray();
            fillLayer.Update();
            im.Save(outputFile, new PsdOptions(im));
            break;
        }
    }
}
```

### Смотрите также

* interface [IFillSettings](../ifillsettings)
* пространство имен [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../aspose.psd.fileformats.psd.layers.fillsettings)
* сборка [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
