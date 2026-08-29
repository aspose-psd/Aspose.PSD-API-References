---
title: "NoiseGradient.ExpansionCount"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Propriété NoiseGradient. Obtient ou définit le nombre d'expansions   2 pour Photoshop 6.0"
type: docs
weight: 30
url: /fr/net/aspose.psd.fileformats.psd.layers.gradient/noisegradient/expansioncount/
---
{{< psd/tize >}}
## NoiseGradient.ExpansionCount property

Obtient ou définit le nombre d'expansion ( = 2 pour Photoshop 6.0).

```csharp
public short ExpansionCount { get; set; }
```

## Exemples

Le code suivant démontre la prise en charge du calque de carte de dégradé.

```csharp
[C#]

string sourceFile = "gradient_map_src.psd";
string outputFile = "gradient_map_src_output.psd";

using (PsdImage im = (PsdImage)Image.Load(sourceFile))
{
    // Ajouter un calque d'ajustement de carte de dégradé.
    GradientMapLayer layer = im.AddGradientMapAdjustmentLayer();
    layer.GradientSettings.Reverse = true;
    layer.Update();

    im.Save(outputFile);
}

// Vérifier les modifications enregistrées
using (PsdImage im = (PsdImage)Image.Load(outputFile))
{
    GradientMapLayer gradientMapLayer = im.Layers[1] as GradientMapLayer;
    var gradientSettings = gradientMapLayer.GradientSettings;
    SolidGradient solidGradient = (SolidGradient)gradientSettings.Gradient;

    AssertAreEqual((short)4096, solidGradient.Interpolation);
    AssertAreEqual(true, gradientSettings.Reverse);
    AssertAreEqual(false, gradientSettings.Dither);
    AssertAreEqual("Custom", solidGradient.GradientName);
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

* class [NoiseGradient](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Gradient](../../../aspose.psd.fileformats.psd.layers.gradient/)
* assembly [Aspose.PSD](../../../)


