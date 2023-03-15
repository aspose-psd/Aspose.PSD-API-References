---
title: Interface IPatternFillSettings
second_title: Справочник по Aspose.PSD для .NET API
description: Aspose.PSD.FileFormats.Psd.Layers.FillSettings.IPatternFillSettings интерфейс. Интерфейс для настройки заливки узором
type: docs
weight: 2030
url: /ru/net/aspose.psd.fileformats.psd.layers.fillsettings/ipatternfillsettings/
---
## IPatternFillSettings interface

Интерфейс для настройки заливки узором

```csharp
public interface IPatternFillSettings : IFillSettings
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [HorizontalOffset](../../aspose.psd.fileformats.psd.layers.fillsettings/ipatternfillsettings/horizontaloffset/) { get; set; } | Получает или задает смещение по горизонтали. |
| [Linked](../../aspose.psd.fileformats.psd.layers.fillsettings/ipatternfillsettings/linked/) { get; set; } | Получает или задает значение, указывающее, является ли это`IPatternFillSettings`связан. |
| [PatternData](../../aspose.psd.fileformats.psd.layers.fillsettings/ipatternfillsettings/patterndata/) { get; set; } | Получает или устанавливает данные шаблона. |
| [PatternHeight](../../aspose.psd.fileformats.psd.layers.fillsettings/ipatternfillsettings/patternheight/) { get; set; } | Получает или задает высоту шаблона. |
| [PatternId](../../aspose.psd.fileformats.psd.layers.fillsettings/ipatternfillsettings/patternid/) { get; set; } | Получает или задает идентификатор шаблона. |
| [PatternName](../../aspose.psd.fileformats.psd.layers.fillsettings/ipatternfillsettings/patternname/) { get; set; } | Получает или задает имя шаблона. |
| [PatternWidth](../../aspose.psd.fileformats.psd.layers.fillsettings/ipatternfillsettings/patternwidth/) { get; set; } | Получает или задает ширину шаблона. |
| [PointType](../../aspose.psd.fileformats.psd.layers.fillsettings/ipatternfillsettings/pointtype/) { get; set; } | Получает или задает тип точки. |
| [Scale](../../aspose.psd.fileformats.psd.layers.fillsettings/ipatternfillsettings/scale/) { get; set; } | Получает или задает масштаб. |
| [VerticalOffset](../../aspose.psd.fileformats.psd.layers.fillsettings/ipatternfillsettings/verticaloffset/) { get; set; } | Получает или задает вертикальное смещение. |

### Примеры

Следующий код сохраняет изображения со слоем заливки шаблона и демонстрирует, как Aspose.PSD отображает шаблон.

```csharp
[C#]

string sourceFile = "sample.psd";
string outputFile = "sample_out.psd";
string outputPngFile = "sample_out.png";

// Загружаем существующее изображение в экземпляр класса PsdImage
using (var image = (PsdImage)Image.Load(sourceFile))
{
    foreach (var layer in image.Layers)
    {
        if (layer is FillLayer)
        {
            var fillLayer = (FillLayer)layer;
            var settings = (IPatternFillSettings)fillLayer.FillSettings;
            settings.HorizontalOffset = -5;
            settings.VerticalOffset = 12;
            settings.Scale = 300;
            settings.Linked = true;
            settings.PatternData = new int[]
                                       {
                                           Color.Black.ToArgb(), Color.Red.ToArgb(),
                                           Color.Green.ToArgb(), Color.Blue.ToArgb(),
                                           Color.White.ToArgb(), Color.AliceBlue.ToArgb(),
                                           Color.Violet.ToArgb(), Color.Chocolate.ToArgb(),
                                           Color.IndianRed.ToArgb(), Color.DarkOliveGreen.ToArgb(),
                                           Color.CadetBlue.ToArgb(), Color.YellowGreen.ToArgb(),
                                           Color.Black.ToArgb(), Color.Azure.ToArgb(),
                                           Color.ForestGreen.ToArgb(), Color.Sienna.ToArgb(),
                                       };

            settings.PatternHeight = 4;
            settings.PatternWidth = 4;

            settings.PatternName = "$$$/Presets/Patterns/ColorfulSquare=Colorful Square New\0";
            settings.PatternId = Guid.NewGuid().ToString() + "\0";

            fillLayer.Update();
            break;
        }
    }

    image.Save(outputFile, new PsdOptions(image));
    image.Save(outputPngFile, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### Смотрите также

* interface [IFillSettings](../ifillsettings/)
* пространство имен [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../aspose.psd.fileformats.psd.layers.fillsettings/)
* сборка [Aspose.PSD](../../)


