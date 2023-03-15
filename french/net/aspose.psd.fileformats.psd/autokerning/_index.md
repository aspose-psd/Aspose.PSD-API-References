---
title: Enum AutoKerning
second_title: Référence de l'API Aspose.PSD pour .NET
description: Aspose.PSD.FileFormats.Psd.AutoKerning énumération. Le mode de crénage automatique de Photoshop distance entre les symboles.
type: docs
weight: 1600
url: /fr/net/aspose.psd.fileformats.psd/autokerning/
---
## AutoKerning enumeration

Le mode de crénage automatique de Photoshop (distance entre les symboles).

```csharp
public enum AutoKerning
```

### Valeurs

| Nom | Évaluer | La description |
| --- | --- | --- |
| Manual | `0` | Valeur de crénage manuel. |
| Metric | `1` | Le crénage des métriques utilise des paires de crénage, qui sont incluses avec la plupart des polices (de leurs concepteurs). |
| Optical | `2` | Le crénage optique ajuste l'espacement entre les caractères adjacents en fonction de leurs formes. |

### Exemples

Le code suivant illustre la prise en charge de la prise en charge des nouvelles propriétés ITextStyle.

```csharp
[C#]

void AssertAreEqual(object expected, object actual)
{
    if (!object.Equals(expected, actual))
    {
        throw new FormatException(
            string.Format("Actual value {0} are not equal to expected {1}.", actual, expected));
    }
}

string srcFile = "A.psd";
string outputFile = "output.psd";

using (var psdImage = (PsdImage)Image.Load(srcFile))
{
    var textLayer = (TextLayer)psdImage.Layers[1];
    textLayer.UpdateText("abc");

    psdImage.Save(outputFile);
}

// Vérifier les valeurs
using (var srcImage = (PsdImage)Image.Load(srcFile))
{
    var srcTextLayer = (TextLayer)srcImage.Layers[1];
    var etalonStyle = srcTextLayer.TextData.Items[0].Style;

    using (var outImage = (PsdImage)Image.Load(outputFile))
    {
        var outTextLayer = (TextLayer)outImage.Layers[1];
        var resultStyle = outTextLayer.TextData.Items[0].Style;

        AssertAreEqual(etalonStyle.AutoLeading, resultStyle.AutoLeading);
        AssertAreEqual(etalonStyle.FontIndex, resultStyle.FontIndex);
        AssertAreEqual(etalonStyle.Underline, resultStyle.Underline);
        AssertAreEqual(etalonStyle.Strikethrough, resultStyle.Strikethrough);
        AssertAreEqual(etalonStyle.AutoKerning, resultStyle.AutoKerning);
        AssertAreEqual(etalonStyle.StandardLigatures, resultStyle.StandardLigatures);
        AssertAreEqual(etalonStyle.DiscretionaryLigatures, resultStyle.DiscretionaryLigatures);
        AssertAreEqual(etalonStyle.ContextualAlternates, resultStyle.ContextualAlternates);
        AssertAreEqual(etalonStyle.LanguageIndex, resultStyle.LanguageIndex);
        AssertAreEqual(etalonStyle.VerticalScale, resultStyle.VerticalScale);
        AssertAreEqual(etalonStyle.HorizontalScale, resultStyle.HorizontalScale);
        AssertAreEqual(etalonStyle.Fractions, resultStyle.Fractions);
    }
}
```

### Voir également

* espace de noms [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* Assemblée [Aspose.PSD](../../)


