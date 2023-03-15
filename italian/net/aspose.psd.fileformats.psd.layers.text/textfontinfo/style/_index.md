---
title: TextFontInfo.Style
second_title: Aspose.PSD per riferimento API .NET
description: TextFontInfo proprietà. Ottiene lo stile del carattere analizzato dal nome della sottofamiglia
type: docs
weight: 50
url: /it/net/aspose.psd.fileformats.psd.layers.text/textfontinfo/style/
---
## TextFontInfo.Style property

Ottiene lo stile del carattere analizzato dal nome della sottofamiglia

```csharp
public FontStyle Style { get; }
```

### Valore della proprietà

Stile carattere analizzato dal nome della sottofamiglia

### Esempi

Il codice seguente mostra come Aspose.PSD ottiene le proprietà della formattazione in linea del livello di testo.

```csharp
[C#]

string sourceFile = "inline_formatting.psd";
List<ITextPortion> regularText = new List<ITextPortion>();
List<ITextPortion> boldText = new List<ITextPortion>();
List<ITextPortion> italicText = new List<ITextPortion>();

// Carica un'immagine esistente in un'istanza della classe PsdImage
using (var psdImage = (PsdImage)Image.Load(sourceFile))
{

    var layers = psdImage.Layers;
    for (int index = 0; index < layers.Length; index++)
    {
        var layer = layers[index];
        if (!(layer is TextLayer))
        {
            continue;
        }

        var textLayer = (TextLayer)layer;

        // ottiene i caratteri che contengono nel livello di testo
        var fonts = textLayer.GetFonts();
        var textPortions = textLayer.TextData.Items;

        foreach (var textPortion in textPortions)
        {
            TextFontInfo font = fonts[textPortion.Style.FontIndex];
            if (font != null)
            {
                switch (font.Style)
                {
                    case FontStyle.Regular:
                        regularText.Add(textPortion);
                        break;
                    case FontStyle.Bold:
                        boldText.Add(textPortion);
                        break;
                    case FontStyle.Italic:
                        italicText.Add(textPortion);
                        break;
                    default:
                        throw new ArgumentOutOfRangeException();
                }
            }
        }
    }
}
```

### Guarda anche

* enum [FontStyle](../../../aspose.psd/fontstyle/)
* class [TextFontInfo](../)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Layers.Text](../../textfontinfo/)
* assemblea [Aspose.PSD](../../../)


