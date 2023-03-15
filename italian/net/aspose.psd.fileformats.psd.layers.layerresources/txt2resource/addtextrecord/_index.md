---
title: Txt2Resource.AddTextRecord
second_title: Aspose.PSD per riferimento API .NET
description: Txt2Resource metodo. Aggiunge il record di testo alla risorsa e restituisce lid del record di testo.
type: docs
weight: 70
url: /it/net/aspose.psd.fileformats.psd.layers.layerresources/txt2resource/addtextrecord/
---
## Txt2Resource.AddTextRecord method

Aggiunge il record di testo alla risorsa e restituisce l'id del record di testo.

```csharp
public int AddTextRecord(string text, RectangleF bounds)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| text | String | Il testo del record. |
| bounds | RectangleF | I limiti. |

### Valore di ritorno

Restituisce l'ID del record di testo per la risorsa

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [PsdImageException](../../../aspose.psd.coreexceptions.imageformats/psdimageexception/) | Versione della risorsa Txt2 sconosciuta. |

### Esempi

Il codice seguente illustra il supporto del supporto delle nuove proprietà ITextStyle.

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

// Controlla i valori
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

### Guarda anche

* struct [RectangleF](../../../aspose.psd/rectanglef/)
* class [Txt2Resource](../)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../txt2resource/)
* assemblea [Aspose.PSD](../../../)


