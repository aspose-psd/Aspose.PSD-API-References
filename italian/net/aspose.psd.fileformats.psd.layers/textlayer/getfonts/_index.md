---
title: TextLayer.GetFonts
second_title: Aspose.PSD per riferimento API .NET
description: TextLayer metodo. Ottiene il set di caratteri del livello di testo.
type: docs
weight: 80
url: /it/net/aspose.psd.fileformats.psd.layers/textlayer/getfonts/
---
## TextLayer.GetFonts method

Ottiene il set di caratteri del livello di testo.

```csharp
public TextFontInfo[] GetFonts()
```

### Valore di ritorno

Il set di caratteri del livello di testo.

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

* class [TextFontInfo](../../../aspose.psd.fileformats.psd.layers.text/textfontinfo/)
* class [TextLayer](../)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Layers](../../textlayer/)
* assemblea [Aspose.PSD](../../../)


