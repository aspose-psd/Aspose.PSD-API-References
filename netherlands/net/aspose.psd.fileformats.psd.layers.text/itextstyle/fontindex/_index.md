---
title: ITextStyle.FontIndex
second_title: Aspose.PSD voor .NET API-referentie
description: ITextStyle eigendom. Haalt de lettertypeindex op.
type: docs
weight: 110
url: /nl/net/aspose.psd.fileformats.psd.layers.text/itextstyle/fontindex/
---
## ITextStyle.FontIndex property

Haalt de lettertype-index op.

```csharp
public int FontIndex { get; }
```

### Eigendoms-waarde

Het lettertype.

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

* interface [ITextStyle](../)
* naamruimte [Aspose.PSD.FileFormats.Psd.Layers.Text](../../itextstyle/)
* montage [Aspose.PSD](../../../)


