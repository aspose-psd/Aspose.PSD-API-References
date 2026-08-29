---
title: "Класс ColorFillSettings"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Класс Aspose.PSD.FileFormats.Psd.Layers.FillSettings.ColorFillSettings. Настройки эффекта заливки цветом"
type: docs
weight: 2040
url: /ru/net/aspose.psd.fileformats.psd.layers.fillsettings/colorfillsettings/
---
{{< psd/tize >}}
## ColorFillSettings class

Настройки эффекта заливки цветом

```csharp
public class ColorFillSettings : BaseFillSettings, IColorFillSettings
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [ColorFillSettings](colorfillsettings/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Color](../../aspose.psd.fileformats.psd.layers.fillsettings/colorfillsettings/color/) { get; set; } | Получает или задает цвет. |
| override [FillType](../../aspose.psd.fileformats.psd.layers.fillsettings/colorfillsettings/filltype/) { get; } | Тип заливки |

## Примеры

Следующий код демонстрирует поддержку слоя эффекта штриха с типом заливки — Color.

```csharp
[C#]

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new FormatException(message ?? "Objects are not equal.");
    }
}

var sourceFileName = "Stroke.psd";
var exportPath = "StrokeColorChanged.psd";

var loadOptions = new PsdLoadOptions()
{
    LoadEffectsResource = true
};

using (var im = (PsdImage)Image.Load(sourceFileName, loadOptions))
{
    var colorStroke = (StrokeEffect)im.Layers[1].BlendingOptions.Effects[0];

    AssertAreEqual(BlendMode.Normal, colorStroke.BlendMode);
    AssertAreEqual((byte)255, colorStroke.Opacity);
    AssertAreEqual(true, colorStroke.IsVisible);

    var fillSettings = (ColorFillSettings)colorStroke.FillSettings;
    AssertAreEqual(Color.Black, fillSettings.Color);
    AssertAreEqual(FillType.Color, fillSettings.FillType);

    fillSettings.Color = Color.Yellow;

    colorStroke.Opacity = 127;
    colorStroke.BlendMode = BlendMode.Color;
    im.Save(exportPath);
}

// Тестовый файл после редактирования
using (var im = (PsdImage)Image.Load(exportPath, loadOptions))
{
    var colorStroke = (StrokeEffect)im.Layers[1].BlendingOptions.Effects[0];

    AssertAreEqual(BlendMode.Color, colorStroke.BlendMode);
    AssertAreEqual((byte)127, colorStroke.Opacity);
    AssertAreEqual(true, colorStroke.IsVisible);

    var fillSettings = (ColorFillSettings)colorStroke.FillSettings;
    AssertAreEqual(Color.Yellow, fillSettings.Color);
    AssertAreEqual(FillType.Color, fillSettings.FillType);
}
```

### См. также

* class [BaseFillSettings](../basefillsettings/)
* interface [IColorFillSettings](../icolorfillsettings/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../aspose.psd.fileformats.psd.layers.fillsettings/)
* assembly [Aspose.PSD](../../)


