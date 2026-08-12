---
title: "Перечисление InterpolationMethod"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Перечисление Aspose.PSD.FileFormats.Psd.Layers.FillSettings.InterpolationMethod. Упакованные значения fourCC для метода интерполяции градиента Photoshop. Ключ дескриптора gradientsInterpolationMethod"
type: docs
weight: 2160
url: /ru/net/aspose.psd.fileformats.psd.layers.fillsettings/interpolationmethod/
---
{{< psd/tize >}}
## InterpolationMethod enumeration

Упакованные значения fourCC для метода интерполяции градиента Photoshop. Ключ дескриптора: "gradientsInterpolationMethod"

```csharp
public enum InterpolationMethod : uint
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| Classic | `1197698163` | 'Gcls' — Classic (устаревшее значение по умолчанию, когда ключ отсутствует). |
| Perceptual | `1348825699` | 'Perc' — Perceptual. |
| Linear | `1282306592` | 'Lnr ' — Linear (обратите внимание на пробел в конце). |
| Smooth | `1399680879` | 'Smoo' — Smooth. |
| Stripes | `1195986291` | 'GIMs' — Stripes. |

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

* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../aspose.psd.fileformats.psd.layers.fillsettings/)
* assembly [Aspose.PSD](../../)


