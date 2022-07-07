---
title: GradientFillSettings
second_title: Справочник по Aspose.PSD для .NET API
description: Настройки эффекта градиентной заливки.
type: docs
weight: 1900
url: /ru/net/aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/
---
## GradientFillSettings class

Настройки эффекта градиентной заливки.

```csharp
public class GradientFillSettings : BaseFillSettings, IGradientFillSettings
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [GradientFillSettings](gradientfillsettings)() | Инициализирует новый экземпляр класса[`GradientFillSettings`](../gradientfillsettings). |

## Характеристики

| Имя | Описание |
| --- | --- |
| [AlignWithLayer](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/alignwithlayer) { get; set; } | Получает или задает значение, указывающее, следует ли [выравнивать со слоем]. |
| [Angle](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/angle) { get; set; } | Получает или задает угол. |
| [Color](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/color) { get; set; } | Получает или задает цвет. |
| [ColorPoints](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/colorpoints) { get; set; } | Получает или задает точки цвета. |
| [Dither](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/dither) { get; set; } | Получает или задает значение, указывающее, является ли это[`GradientFillSettings`](../gradientfillsettings)дизерингом. |
| override [FillType](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/filltype) { get; } | Тип заполнения |
| [GradientName](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/gradientname) { get; set; } | Получает или задает имя градиента. |
| [GradientType](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/gradienttype) { get; set; } | Получает или задает тип градиента. |
| [HorizontalOffset](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/horizontaloffset) { get; set; } | Получает или задает смещение по горизонтали. |
| [Reverse](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/reverse) { get; set; } | Получает или задает значение, указывающее, является ли это[`GradientFillSettings`](../gradientfillsettings)обратным. |
| [Scale](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/scale) { get; set; } | Получает или задает масштаб. |
| [TransparencyPoints](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/transparencypoints) { get; set; } | Получает или задает точки прозрачности. |
| [VerticalOffset](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/verticaloffset) { get; set; } | Получает или задает вертикальное смещение. |

## Методы

| Имя | Описание |
| --- | --- |
| [AddColorPoint](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/addcolorpoint)() | Добавляет точку цвета. |
| [AddTransparencyPoint](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/addtransparencypoint)() | Добавляет точку цвета. |
| [RemoveColorPoint](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/removecolorpoint)(IGradientColorPoint) | Удаляет точку цвета. |
| [RemoveTransparencyPoint](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/removetransparencypoint)(IGradientTransparencyPoint) | Удаляет точку прозрачности. |
| static [GenerateLfx2ResourceNodes](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/generatelfx2resourcenodes)() | Генерирует узлы ресурсов LFX2. |

### Примеры

Следующий код демонстрирует поддержка слоя с эффектом обводки с типом заливки - Градиент.

```csharp
[C#]

void AssertIsTrue(bool condition, string message)
{
    if (!condition)
    {
        throw new FormatException(message);
    }
}
void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new FormatException(message ?? "Objects are not equal.");
    }
}

string sourceFileName = "Stroke.psd";
string exportPath = "StrokeGradientChanged.psd";

var loadOptions = new PsdLoadOptions()
{
    LoadEffectsResource = true
};

using (var im = (PsdImage)Image.Load(sourceFileName, loadOptions))
{
    var gradientStroke = (StrokeEffect)im.Layers[2].BlendingOptions.Effects[0];

    AssertAreEqual(BlendMode.Normal, gradientStroke.BlendMode);
    AssertAreEqual((byte)255, gradientStroke.Opacity);
    AssertAreEqual(true, gradientStroke.IsVisible);

    var fillSettings = (GradientFillSettings)gradientStroke.FillSettings;
    AssertAreEqual(Color.Black, fillSettings.Color);
    AssertAreEqual(FillType.Gradient, fillSettings.FillType);
    AssertAreEqual(true, fillSettings.AlignWithLayer);
    AssertAreEqual(GradientType.Linear, fillSettings.GradientType);
    AssertIsTrue(Math.Abs(90 - fillSettings.Angle) < 0.001, "Angle is incorrect");
    AssertAreEqual(false, fillSettings.Dither);
    AssertIsTrue(Math.Abs(0 - fillSettings.HorizontalOffset) < 0.001, "Horizontal offset is incorrect");
    AssertIsTrue(Math.Abs(0 - fillSettings.VerticalOffset) < 0.001, "Vertical offset is incorrect");
    AssertAreEqual(false, fillSettings.Reverse);

    // Цветовые точки
    var colorPoints = fillSettings.ColorPoints;
    AssertAreEqual(2, colorPoints.Length);

    AssertAreEqual(Color.Black, colorPoints[0].Color);
    AssertAreEqual(0, colorPoints[0].Location);
    AssertAreEqual(50, colorPoints[0].MedianPointLocation);

    AssertAreEqual(Color.White, colorPoints[1].Color);
    AssertAreEqual(4096, colorPoints[1].Location);
    AssertAreEqual(50, colorPoints[1].MedianPointLocation);

    // Точки прозрачности
    var transparencyPoints = fillSettings.TransparencyPoints;
    AssertAreEqual(2, transparencyPoints.Length);

    AssertAreEqual(0, transparencyPoints[0].Location);
    AssertAreEqual(50, transparencyPoints[0].MedianPointLocation);
    AssertAreEqual(100.00, transparencyPoints[0].Opacity);

    AssertAreEqual(4096, transparencyPoints[1].Location);
    AssertAreEqual(50, transparencyPoints[1].MedianPointLocation);
    AssertAreEqual(100.00, transparencyPoints[1].Opacity);

    // Тестовое редактирование
    fillSettings.Color = Color.Green;

    gradientStroke.Opacity = 127;
    gradientStroke.BlendMode = BlendMode.Color;

    fillSettings.AlignWithLayer = false;
    fillSettings.GradientType = GradientType.Radial;
    fillSettings.Angle = 45;
    fillSettings.Dither = true;
    fillSettings.HorizontalOffset = 15;
    fillSettings.VerticalOffset = 11;
    fillSettings.Reverse = true;

    // Добавляем новую точку цвета
    var colorPoint = fillSettings.AddColorPoint();
    colorPoint.Color = Color.Green;
    colorPoint.Location = 4096;
    colorPoint.MedianPointLocation = 75;

    // Изменить местоположение предыдущей точки
    fillSettings.ColorPoints[1].Location = 1899;

    // Добавляем новую точку прозрачности
    var transparencyPoint = fillSettings.AddTransparencyPoint();
    transparencyPoint.Opacity = 25;
    transparencyPoint.MedianPointLocation = 25;
    transparencyPoint.Location = 4096;

    // Изменить положение предыдущей точки прозрачности
    fillSettings.TransparencyPoints[1].Location = 2411;

    im.Save(exportPath);
}

// Тестовый файл после редактирования
using (var im = (PsdImage)Image.Load(exportPath, loadOptions))
{
    var gradientStroke = (StrokeEffect)im.Layers[2].BlendingOptions.Effects[0];

    AssertAreEqual(BlendMode.Color, gradientStroke.BlendMode);
    AssertAreEqual((byte)127, gradientStroke.Opacity);
    AssertAreEqual(true, gradientStroke.IsVisible);

    var fillSettings = (GradientFillSettings)gradientStroke.FillSettings;
    AssertAreEqual(Color.Green, fillSettings.Color);
    AssertAreEqual(FillType.Gradient, fillSettings.FillType);

    // Проверяем точки цвета
    AssertAreEqual(3, fillSettings.ColorPoints.Length);

    var point = fillSettings.ColorPoints[0];
    AssertAreEqual(50, point.MedianPointLocation);
    AssertAreEqual(Color.Black, point.Color);
    AssertAreEqual(0, point.Location);

    point = fillSettings.ColorPoints[1];
    AssertAreEqual(50, point.MedianPointLocation);
    AssertAreEqual(Color.White, point.Color);
    AssertAreEqual(1899, point.Location);

    point = fillSettings.ColorPoints[2];
    AssertAreEqual(75, point.MedianPointLocation);
    AssertAreEqual(Color.Green, point.Color);
    AssertAreEqual(4096, point.Location);

    // Проверяем прозрачные точки
    AssertAreEqual(3, fillSettings.TransparencyPoints.Length);

    var transparencyPoint = fillSettings.TransparencyPoints[0];
    AssertAreEqual(50, transparencyPoint.MedianPointLocation);
    AssertAreEqual(100.00, transparencyPoint.Opacity);
    AssertAreEqual(0, transparencyPoint.Location);

    transparencyPoint = fillSettings.TransparencyPoints[1];
    AssertAreEqual(50, transparencyPoint.MedianPointLocation);
    AssertAreEqual(100.00, transparencyPoint.Opacity);
    AssertAreEqual(2411, transparencyPoint.Location);

    transparencyPoint = fillSettings.TransparencyPoints[2];
    AssertAreEqual(25, transparencyPoint.MedianPointLocation);
    AssertAreEqual(25.00, transparencyPoint.Opacity);
    AssertAreEqual(4096, transparencyPoint.Location);
}
```

### Смотрите также

* class [BaseFillSettings](../basefillsettings)
* interface [IGradientFillSettings](../igradientfillsettings)
* пространство имен [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../aspose.psd.fileformats.psd.layers.fillsettings)
* сборка [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
