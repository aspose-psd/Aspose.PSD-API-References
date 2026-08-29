---
title: "GradientFillSettings.InterpolationMethod"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Propriété GradientFillSettings. Obtient ou définit la méthode d'interpolation du dégradé"
type: docs
weight: 90
url: /fr/net/aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/interpolationmethod/
---
{{< psd/tize >}}
## GradientFillSettings.InterpolationMethod property

Obtient ou définit la méthode d'interpolation du dégradé.

```csharp
public InterpolationMethod InterpolationMethod { get; set; }
```

## Exemples

Le code suivant démontre la prise en charge du rendu de dégradé avec la méthode Smooth.

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
    // Lire
    var effect = image.Layers[1].BlendingOptions.Effects[0] as GradientOverlayEffect;
    var gradientSettings = effect.Settings;
    AssertAreEqual(srcMethod, gradientSettings.InterpolationMethod);

    // Modifier
    gradientSettings.InterpolationMethod = newMethod;

    image.Save(outputFile);
    image.Save(outputFilePng, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}

// Vérifier les données enregistrées
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

### Voir aussi

* enum [InterpolationMethod](../../interpolationmethod/)
* class [GradientFillSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../../aspose.psd.fileformats.psd.layers.fillsettings/)
* assembly [Aspose.PSD](../../../)


