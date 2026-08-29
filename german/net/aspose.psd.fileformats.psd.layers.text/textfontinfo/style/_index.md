---
title: "TextFontInfo.Style"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "TextFontInfo-Eigenschaft. Gibt den Schriftstil zurück, der aus dem Subfamiliennamen geparst wurde."
type: docs
weight: 50
url: /de/net/aspose.psd.fileformats.psd.layers.text/textfontinfo/style/
---
{{< psd/tize >}}
## TextFontInfo.Style property

Ruft den Schriftstil ab, der aus dem Subfamiliennamen geparst wurde

```csharp
public FontStyle Style { get; }
```

### Property Value

Schriftstil, aus dem Subfamiliennamen geparst

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

* enum [FontStyle](../../../aspose.psd/fontstyle/)
* class [TextFontInfo](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Text](../../../aspose.psd.fileformats.psd.layers.text/)
* assembly [Aspose.PSD](../../../)


