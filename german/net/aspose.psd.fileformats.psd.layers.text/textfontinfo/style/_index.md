---
title: TextFontInfo.Style
second_title: Aspose.PSD für .NET-API-Referenz
description: TextFontInfo eigendom. Ruft den Schriftstil ab der aus der Unterfamilie name geparst wurde
type: docs
weight: 50
url: /de/net/aspose.psd.fileformats.psd.layers.text/textfontinfo/style/
---
## TextFontInfo.Style property

Ruft den Schriftstil ab, der aus der Unterfamilie name geparst wurde

```csharp
public FontStyle Style { get; }
```

### Eigentumswert

Schriftstil aus Unterfamilie name geparst

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

* enum [FontStyle](../../../aspose.psd/fontstyle/)
* class [TextFontInfo](../)
* namensraum [Aspose.PSD.FileFormats.Psd.Layers.Text](../../textfontinfo/)
* Montage [Aspose.PSD](../../../)


