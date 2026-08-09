---
title: "Énumération InterpolationMethod"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Énumération Aspose.PSD.FileFormats.Psd.Layers.FillSettings.InterpolationMethod. Valeurs fourCC empaquetées pour la méthode d'interpolation de dégradé Photoshop. Clé de descripteur gradientsInterpolationMethod"
type: docs
weight: 2160
url: /fr/net/aspose.psd.fileformats.psd.layers.fillsettings/interpolationmethod/
---
{{< psd/tize >}}
## InterpolationMethod enumeration

Valeurs fourCC empaquetées pour la méthode d'interpolation de dégradé Photoshop. Clé du descripteur : "gradientsInterpolationMethod"

```csharp
public enum InterpolationMethod : uint
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| Classic | `1197698163` | 'Gcls' — Classique (valeur par défaut héritée lorsque la clé est absente). |
| Perceptual | `1348825699` | 'Perc' — Perceptuel. |
| Linear | `1282306592` | 'Lnr ' — Linéaire (notez l'espace final). |
| Smooth | `1399680879` | 'Smoo' — Lisse. |
| Stripes | `1195986291` | 'GIMs' — Bandes. |

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

* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../aspose.psd.fileformats.psd.layers.fillsettings/)
* assembly [Aspose.PSD](../../)


