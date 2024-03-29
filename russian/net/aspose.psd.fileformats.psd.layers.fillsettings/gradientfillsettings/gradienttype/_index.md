---
title: GradientFillSettings.GradientType
second_title: Справочник по Aspose.PSD для .NET API
description: GradientFillSettings свойство. Получает или задает тип градиента.
type: docs
weight: 90
url: /ru/net/aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/gradienttype/
---
## GradientFillSettings.GradientType property

Получает или задает тип градиента.

```csharp
public GradientType GradientType { get; set; }
```

### Стоимость имущества

Тип градиента.

### Примеры

Следующий код сохраняет изображения с другим типом градиента и показывает, как Aspose.PSD рисует градиент.

```csharp
[C#]

string fileName = "FillLayerGradient.psd";
string sourceFile = fileName;
GradientType[] gradientTypes = new[]
{
    GradientType.Linear, GradientType.Radial, GradientType.Angle, GradientType.Reflected, GradientType.Diamond
};
using (var image = Image.Load(sourceFile))
{
    PsdImage psdImage = (PsdImage)image;
    FillLayer fillLayer = (FillLayer)psdImage.Layers[0];
    GradientFillSettings fillSettings = (GradientFillSettings)fillLayer.FillSettings;
    foreach (var gradientType in gradientTypes)
    {
        fillSettings.GradientType = gradientType;
        fillLayer.Update();

        string resultFile = fileName + "_" + gradientType.ToString() + ".png";
        resultFile = resultFile;
        psdImage.Save(resultFile, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
    }
}
```

### Смотрите также

* enum [GradientType](../../gradienttype/)
* class [GradientFillSettings](../)
* пространство имен [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../gradientfillsettings/)
* сборка [Aspose.PSD](../../../)


