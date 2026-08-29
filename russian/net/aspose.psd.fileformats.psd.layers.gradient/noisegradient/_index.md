---
title: "Класс NoiseGradient"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Aspose.PSD.FileFormats.Psd.Layers.Gradient.NoiseGradient класс. Класс определения шумового градиента"
type: docs
weight: 2220
url: /ru/net/aspose.psd.fileformats.psd.layers.gradient/noisegradient/
---
{{< psd/tize >}}
## NoiseGradient class

Класс определения шумового градиента.

```csharp
public class NoiseGradient : BaseGradient
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [NoiseGradient](noisegradient/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [ColorModel](../../aspose.psd.fileformats.psd.layers.gradient/noisegradient/colormodel/) { get; set; } | Получает или задает модель цвета — RGB/HSB/LAB (3/4/6). |
| [ExpansionCount](../../aspose.psd.fileformats.psd.layers.gradient/noisegradient/expansioncount/) { get; set; } | Получает или задает количество расширений ( = 2 для Photoshop 6.0). |
| override [GradientMode](../../aspose.psd.fileformats.psd.layers.gradient/noisegradient/gradientmode/) { get; } | Получает режим для этого градиента. Определяет 'Gradient Type' = 'Solid/Noise' (0/1). |
| [GradientName](../../aspose.psd.fileformats.psd.layers.gradient/basegradient/gradientname/) { get; set; } | Получает или задает имя градиента. |
| [MaximumColor](../../aspose.psd.fileformats.psd.layers.gradient/noisegradient/maximumcolor/) { get; set; } | Получает или задает максимальный цвет PixelDataFormat. |
| [MinimumColor](../../aspose.psd.fileformats.psd.layers.gradient/noisegradient/minimumcolor/) { get; set; } | Получает или задает минимальный цвет PixelDataFormat. |
| [RndNumberSeed](../../aspose.psd.fileformats.psd.layers.gradient/noisegradient/rndnumberseed/) { get; set; } | Получает или задает seed случайного числа, используемый для генерации цветов для градиента Noise. |
| [Roughness](../../aspose.psd.fileformats.psd.layers.gradient/noisegradient/roughness/) { get; set; } | Получает или задает коэффициент шероховатости. |
| [ShowTransparency](../../aspose.psd.fileformats.psd.layers.gradient/noisegradient/showtransparency/) { get; set; } | Получает или задает флаг отображения прозрачности. |
| [UseVectorColor](../../aspose.psd.fileformats.psd.layers.gradient/noisegradient/usevectorcolor/) { get; set; } | Получает или задает флаг использования векторного цвета. |

## Примеры

Продемонстрировано чтение и изменение настроек шума и сплошного градиента в эффектах заливки штрихов.

```csharp
[C#]

string inputFile = "StrokeNoise.psd";
string outputFile = "output.psd";

var loadOptions = new PsdLoadOptions() { LoadEffectsResource = true };

using (PsdImage image = (PsdImage)Image.Load(inputFile, loadOptions))
{
    var gradientStroke = (StrokeEffect)image.Layers[0].BlendingOptions.Effects[0];
    GradientFillSettings gradientFillSettings = gradientStroke.FillSettings as GradientFillSettings;

    // Проверьте общие свойства настроек градиентной заливки
    AssertIsNotNull(gradientFillSettings);
    AssertAreEqual(true, gradientFillSettings.AlignWithLayer);
    AssertAreEqual(true, gradientFillSettings.Dither);
    AssertAreEqual(true, gradientFillSettings.Reverse);
    AssertAreEqual(116.0, gradientFillSettings.Angle);
    AssertAreEqual(122, gradientFillSettings.Scale);
    AssertAreEqual(GradientType.Angle, gradientFillSettings.GradientType);

    // Проверьте свойства градиента Noise
    NoiseGradient noiseGradient = gradientFillSettings.Gradient as NoiseGradient;
    AssertIsNotNull(noiseGradient);
    AssertAreEqual(GradientKind.Noise, noiseGradient.GradientMode);
    AssertAreEqual(2107422935, noiseGradient.RndNumberSeed);
    AssertAreEqual(false, noiseGradient.ShowTransparency);
    AssertAreEqual(false, noiseGradient.UseVectorColor);
    AssertAreEqual(2048, noiseGradient.Roughness);
    AssertAreEqual(NoiseColorModel.RGB, noiseGradient.ColorModel);
    AssertAreEqual((long)0, noiseGradient.MinimumColor.GetAsLong());
    AssertAreEqual(28147819798528050, noiseGradient.MaximumColor.GetAsLong());

    // Изменить настройки градиента
    gradientFillSettings.AlignWithLayer = false;
    gradientFillSettings.Dither = false;
    gradientFillSettings.Reverse = false;
    gradientFillSettings.Angle = 30;
    gradientFillSettings.Scale = 80;
    gradientFillSettings.GradientType = GradientType.Linear;

    var solidGradient = new SolidGradient();
    solidGradient.Interpolation = 2048;
    solidGradient.ColorPoints[0].RawColor.Components[0].Value = 255; // A
    solidGradient.ColorPoints[0].RawColor.Components[1].Value = 255; // R 
    solidGradient.ColorPoints[0].RawColor.Components[2].Value = 0;   // G
    solidGradient.ColorPoints[0].RawColor.Components[3].Value = 0;   // B
    solidGradient.TransparencyPoints[1].Opacity = 50;
    gradientFillSettings.Gradient = solidGradient;

    image.Save(outputFile);
}

// Проверить сохранённые изменения
using (PsdImage image = (PsdImage)Image.Load(outputFile, loadOptions))
{
    var gradientStroke = (StrokeEffect)image.Layers[0].BlendingOptions.Effects[0];
    GradientFillSettings gradientFillSettings = gradientStroke.FillSettings as GradientFillSettings;

    // Проверьте общие свойства настроек градиентной заливки
    AssertIsNotNull(gradientFillSettings);
    AssertAreEqual(false, gradientFillSettings.AlignWithLayer);
    AssertAreEqual(false, gradientFillSettings.Dither);
    AssertAreEqual(false, gradientFillSettings.Reverse);
    AssertAreEqual(30.0, gradientFillSettings.Angle);
    AssertAreEqual(80, gradientFillSettings.Scale);
    AssertAreEqual(GradientType.Linear, gradientFillSettings.GradientType);

    SolidGradient solidGradient = gradientFillSettings.Gradient as SolidGradient;
    AssertIsNotNull(solidGradient);
    AssertAreEqual((short)2048, solidGradient.Interpolation);
    AssertAreEqual(
        (ulong)255,
        solidGradient.ColorPoints[0].RawColor.Components[0].Value);
    AssertAreEqual(
        (ulong)255,
        solidGradient.ColorPoints[0].RawColor.Components[1].Value);
    AssertAreEqual(
        (ulong)0,
        solidGradient.ColorPoints[0].RawColor.Components[2].Value);
    AssertAreEqual(
        (ulong)0,
        solidGradient.ColorPoints[0].RawColor.Components[3].Value);
    AssertAreEqual(50.0, solidGradient.TransparencyPoints[1].Opacity);
}

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception(message ?? "Objects are not equal.");
    }
}

void AssertIsNotNull(object actual)
{
    if (actual == null)
    {
        throw new Exception("Object is null.");
    }
}
```

### См. также

* class [BaseGradient](../basegradient/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Gradient](../../aspose.psd.fileformats.psd.layers.gradient/)
* assembly [Aspose.PSD](../../)


