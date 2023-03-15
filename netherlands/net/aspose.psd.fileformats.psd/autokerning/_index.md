---
title: Enum AutoKerning
second_title: Aspose.PSD voor .NET API-referentie
description: Aspose.PSD.FileFormats.Psd.AutoKerning opsomming. De automatische afspatiëringsmodus van Photoshop afstand tussen symbolen.
type: docs
weight: 1600
url: /nl/net/aspose.psd.fileformats.psd/autokerning/
---
## AutoKerning enumeration

De automatische afspatiëringsmodus van Photoshop (afstand tussen symbolen).

```csharp
public enum AutoKerning
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| Manual | `0` | Handmatige spatiëringswaarde. |
| Metric | `1` | Metrics spatiëring maakt gebruik van kernparen, die zijn opgenomen in de meeste lettertypen (van hun ontwerpers). |
| Optical | `2` | Optische spatiëring past de spatiëring tussen aangrenzende tekens aan op basis van hun vorm. |

### Voorbeelden

De volgende code demonstreert de ondersteuning van de ondersteuning van nieuwe ITextStyle-eigenschappen.

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

// Controleer waarden
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

### Zie ook

* naamruimte [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* montage [Aspose.PSD](../../)


