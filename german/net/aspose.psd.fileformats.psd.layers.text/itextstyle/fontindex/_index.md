---
title: "ITextStyle.FontIndex"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "ITextStyle-Eigenschaft. Gibt den Schriftartindex zurück"
type: docs
weight: 110
url: /de/net/aspose.psd.fileformats.psd.layers.text/itextstyle/fontindex/
---
{{< psd/tize >}}
## ITextStyle.FontIndex property

Liest den Schriftindex.

```csharp
public int FontIndex { get; }
```

### Property Value

Die Schriftart.

## Beispiele

Der folgende Code zeigt, wie Aspose.PSD die Eigenschaften der Inline-Formatierung der Textebene abruft.

```csharp
[C#]

string sourceFile = "inline_formatting.psd";
List<ITextPortion> regularText = new List<ITextPortion>();
List<ITextPortion> boldText = new List<ITextPortion>();
List<ITextPortion> italicText = new List<ITextPortion>();

// Laden Sie ein vorhandenes Bild in eine Instanz der Klasse PsdImage.
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

        // Ermittelt Schriftarten, die in der Textebene enthalten sind
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

### Siehe auch

* interface [ITextStyle](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Text](../../../aspose.psd.fileformats.psd.layers.text/)
* assembly [Aspose.PSD](../../../)


