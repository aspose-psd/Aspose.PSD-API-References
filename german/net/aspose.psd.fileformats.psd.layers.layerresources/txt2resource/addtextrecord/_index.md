---
title: Txt2Resource.AddTextRecord
second_title: Aspose.PSD für .NET-API-Referenz
description: Txt2Resource methode. Fügt den Textdatensatz zur Ressource hinzu und gibt die ID des Textdatensatzes zurück.
type: docs
weight: 70
url: /de/net/aspose.psd.fileformats.psd.layers.layerresources/txt2resource/addtextrecord/
---
## Txt2Resource.AddTextRecord method

Fügt den Textdatensatz zur Ressource hinzu und gibt die ID des Textdatensatzes zurück.

```csharp
public int AddTextRecord(string text, RectangleF bounds)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | String | Der Datensatztext. |
| bounds | RectangleF | Die Grenzen. |

### Rückgabewert

Gibt die ID des Textdatensatzes für resource zurück

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [PsdImageException](../../../aspose.psd.coreexceptions.imageformats/psdimageexception/) | Unbekannte Version der Txt2-Ressource. |

### Beispiele

Der folgende Code demonstriert die Unterstützung der Unterstützung neuer ITextStyle-Eigenschaften.

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

// Werte prüfen
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

### Siehe auch

* struct [RectangleF](../../../aspose.psd/rectanglef/)
* class [Txt2Resource](../)
* namensraum [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../txt2resource/)
* Montage [Aspose.PSD](../../../)


