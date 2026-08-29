---
title: "GradientMapSettings.InterpolationMethod"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Свойство GradientMapSettings. Получает или задает метод интерполяции для градиента"
type: docs
weight: 40
url: /ru/net/aspose.psd.fileformats.psd.layers.fillsettings/gradientmapsettings/interpolationmethod/
---
{{< psd/tize >}}
## GradientMapSettings.InterpolationMethod property

Получает или задаёт метод интерполяции градиента.

```csharp
public InterpolationMethod InterpolationMethod { get; set; }
```

## Примеры

Следующий код демонстрирует поддержку градиентного рендеринга с методом Smooth.

```csharp
[C#]

string sourceFile = "GradientOverlay.psd";
string outputFile = "output_GradientOverlay.psd";
string outputFilePng = "output_GradientOverlay.png";

var srcMethod = InterpolationMethod.Linear;
var newMethod = InterpolationMethod.Smooth;

var opt = new PsdLoadOptions()
{
    LoadEffectsResource = true,
};

using (var image = (PsdImage)Image.Load(sourceFile, opt))
{
    // Читать
    var effect = image.Layers[1].BlendingOptions.Effects[0] as GradientOverlayEffect;
    var gradientSettings = effect.Settings;
    AssertAreEqual(srcMethod, gradientSettings.InterpolationMethod);

    // Изменить
    gradientSettings.InterpolationMethod = newMethod;

    image.Save(outputFile);
    image.Save(outputFilePng, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}

// Проверить сохранённые данные
using (var image = (PsdImage)Image.Load(outputFile, opt))
{
    var effect = image.Layers[1].BlendingOptions.Effects[0] as GradientOverlayEffect;
    var gradientSettings = effect.Settings;

    AssertAreEqual(newMethod, gradientSettings.InterpolationMethod);
}

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception(message ?? "Objects are not equal.");
    }
}
```

### См. также

* enum [InterpolationMethod](../../interpolationmethod/)
* class [GradientMapSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../../aspose.psd.fileformats.psd.layers.fillsettings/)
* assembly [Aspose.PSD](../../../)


