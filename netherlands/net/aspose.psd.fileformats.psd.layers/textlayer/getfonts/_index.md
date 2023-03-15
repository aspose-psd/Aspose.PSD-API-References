---
title: TextLayer.GetFonts
second_title: Aspose.PSD voor .NET API-referentie
description: TextLayer methode. Haalt de fontset van de tekstlaag op.
type: docs
weight: 80
url: /nl/net/aspose.psd.fileformats.psd.layers/textlayer/getfonts/
---
## TextLayer.GetFonts method

Haalt de fontset van de tekstlaag op.

```csharp
public TextFontInfo[] GetFonts()
```

### Winstwaarde

De fontset van de tekstlaag.

### Voorbeelden

De volgende code laat zien hoe Aspose.PSD eigenschappen van inline opmaak van tekstlaag verkrijgt.

```csharp
[C#]

string sourceFile = "inline_formatting.psd";
List<ITextPortion> regularText = new List<ITextPortion>();
List<ITextPortion> boldText = new List<ITextPortion>();
List<ITextPortion> italicText = new List<ITextPortion>();

// Laad een bestaande afbeelding in een instantie van de PsdImage-klasse
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

        // haalt lettertypen op die zich in de tekstlaag bevinden
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

### Zie ook

* class [TextFontInfo](../../../aspose.psd.fileformats.psd.layers.text/textfontinfo/)
* class [TextLayer](../)
* naamruimte [Aspose.PSD.FileFormats.Psd.Layers](../../textlayer/)
* montage [Aspose.PSD](../../../)


