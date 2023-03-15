---
title: TextLayer.GetFonts
second_title: Aspose.PSD för .NET API-referens
description: TextLayer metod. Hämtar teckensnittsuppsättningen för textlagret.
type: docs
weight: 80
url: /sv/net/aspose.psd.fileformats.psd.layers/textlayer/getfonts/
---
## TextLayer.GetFonts method

Hämtar teckensnittsuppsättningen för textlagret.

```csharp
public TextFontInfo[] GetFonts()
```

### Returvärde

Teckensnittsuppsättningen för textlagret.

### Exempel

Följande kod visar hur Aspose.PSD får egenskaper för inline-formatering av Text Layer.

```csharp
[C#]

string sourceFile = "inline_formatting.psd";
List<ITextPortion> regularText = new List<ITextPortion>();
List<ITextPortion> boldText = new List<ITextPortion>();
List<ITextPortion> italicText = new List<ITextPortion>();

// Ladda en befintlig bild i en instans av klassen PsdImage
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

        // får typsnitt som innehåller i textlager
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

### Se även

* class [TextFontInfo](../../../aspose.psd.fileformats.psd.layers.text/textfontinfo/)
* class [TextLayer](../)
* namnutrymme [Aspose.PSD.FileFormats.Psd.Layers](../../textlayer/)
* hopsättning [Aspose.PSD](../../../)


