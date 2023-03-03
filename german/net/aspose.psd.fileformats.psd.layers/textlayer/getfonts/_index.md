---
title: TextLayer.GetFonts
second_title: Aspose.PSD für .NET-API-Referenz
description: TextLayer methode. Ruft den Schriftsatz der Textebene ab.
type: docs
weight: 80
url: /de/net/aspose.psd.fileformats.psd.layers/textlayer/getfonts/
---
## TextLayer.GetFonts method

Ruft den Schriftsatz der Textebene ab.

```csharp
public TextFontInfo[] GetFonts()
```

### Rückgabewert

Der Schriftsatz der Textebene.

### Beispiele

Der folgende Code zeigt, wie Aspose.PSD Eigenschaften der Inline-Formatierung der Textebene erhält.

```csharp
[C#]

string sourceFile = "inline_formatting.psd";
List<ITextPortion> regularText = new List<ITextPortion>();
List<ITextPortion> boldText = new List<ITextPortion>();
List<ITextPortion> italicText = new List<ITextPortion>();

// Ein vorhandenes Bild in eine Instanz der PsdImage-Klasse laden
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

        // Ruft Schriftarten ab, die in der Textebene enthalten sind
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

* class [TextFontInfo](../../../aspose.psd.fileformats.psd.layers.text/textfontinfo/)
* class [TextLayer](../)
* namensraum [Aspose.PSD.FileFormats.Psd.Layers](../../textlayer/)
* Montage [Aspose.PSD](../../../)


