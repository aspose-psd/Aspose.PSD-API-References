---
title: "IGradientFillSettings.InterpolationMethod"
second_title: "Riferimento API Aspose.PSD per .NET"
description: "IGradientFillSettings proprietà. Ottiene o imposta il metodo di interpolazione per il gradiente"
type: docs
weight: 70
url: /it/net/aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/interpolationmethod/
---
{{< psd/tize >}}
## IGradientFillSettings.InterpolationMethod property

Ottiene o imposta il metodo di interpolazione per il gradiente.

```csharp
public InterpolationMethod InterpolationMethod { get; set; }
```

## Esempi

Il codice seguente dimostra il supporto del rendering del gradiente con il metodo Smooth.

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
    // Leggi
    var effect = image.Layers[1].BlendingOptions.Effects[0] as GradientOverlayEffect;
    var gradientSettings = effect.Settings;
    AssertAreEqual(srcMethod, gradientSettings.InterpolationMethod);

    // Modifica
    gradientSettings.InterpolationMethod = newMethod;

    image.Save(outputFile);
    image.Save(outputFilePng, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}

// Verifica i dati salvati
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

### Vedi anche

* enum [InterpolationMethod](../../interpolationmethod/)
* interface [IGradientFillSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../../aspose.psd.fileformats.psd.layers.fillsettings/)
* assembly [Aspose.PSD](../../../)


