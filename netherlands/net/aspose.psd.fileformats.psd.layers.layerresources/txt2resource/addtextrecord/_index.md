---
title: Txt2Resource.AddTextRecord
second_title: Aspose.PSD voor .NET API-referentie
description: Txt2Resource methode. Voegt het tekstrecord toe aan Resource en retourneert de id van het tekstrecord.
type: docs
weight: 70
url: /nl/net/aspose.psd.fileformats.psd.layers.layerresources/txt2resource/addtextrecord/
---
## Txt2Resource.AddTextRecord method

Voegt het tekstrecord toe aan Resource en retourneert de id van het tekstrecord.

```csharp
public int AddTextRecord(string text, RectangleF bounds)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| text | String | De recordtekst. |
| bounds | RectangleF | De grenzen. |

### Winstwaarde

Retourneert ID van tekstrecord voor resource

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| [PsdImageException](../../../aspose.psd.coreexceptions.imageformats/psdimageexception/) | Onbekende Txt2 Resource-versie. |

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

* struct [RectangleF](../../../aspose.psd/rectanglef/)
* class [Txt2Resource](../)
* naamruimte [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../txt2resource/)
* montage [Aspose.PSD](../../../)


