---
title: "Txt2Resource.AddTextRecord"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Méthode Txt2Resource. Ajoute l'enregistrement texte à la ressource et renvoie l'identifiant de l'enregistrement texte"
type: docs
weight: 40
url: /fr/net/aspose.psd.fileformats.psd.layers.layerresources/txt2resource/addtextrecord/
---
{{< psd/tize >}}
## Txt2Resource.AddTextRecord method

Ajoute l'enregistrement texte à la Ressource et renvoie l'identifiant de l'enregistrement texte.

```csharp
public int AddTextRecord(string text, RectangleF bounds)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| texte | String | Le texte de l'enregistrement. |
| limites | RectangleF | Les limites. |

### Valeur de retour

Renvoie l'Id de l'enregistrement texte pour la ressource

### Exceptions

| exception | condition |
| --- | --- |
| [PsdImageException](../../../aspose.psd.coreexceptions.imageformats/psdimageexception/) | Version inconnue de Txt2 Resource. |

## Exemples

Le code suivant démontre la prise en charge de la prise en charge des nouvelles propriétés ITextStyle.

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

### Voir aussi

* struct [RectangleF](../../../aspose.psd/rectanglef/)
* class [Txt2Resource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


