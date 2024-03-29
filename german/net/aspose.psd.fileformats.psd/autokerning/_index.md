---
title: Enum AutoKerning
second_title: Aspose.PSD für .NET-API-Referenz
description: Aspose.PSD.FileFormats.Psd.AutoKerning opsomming. Der automatische KerningModus von Photoshop Abstand zwischen Symbolen.
type: docs
weight: 1600
url: /de/net/aspose.psd.fileformats.psd/autokerning/
---
## AutoKerning enumeration

Der automatische Kerning-Modus von Photoshop (Abstand zwischen Symbolen).

```csharp
public enum AutoKerning
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Manual | `0` | Manueller Kerning-Wert. |
| Metric | `1` | Metrics Kerning verwendet Kerning-Paare, die in den meisten Schriftarten (von ihren Designern) enthalten sind. |
| Optical | `2` | Optisches Kerning passt den Abstand zwischen benachbarten Zeichen basierend auf ihren Formen an. |

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

* namensraum [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* Montage [Aspose.PSD](../../)


