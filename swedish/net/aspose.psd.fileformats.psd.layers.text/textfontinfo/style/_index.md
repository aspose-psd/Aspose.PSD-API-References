---
title: TextFontInfo.Style
second_title: Aspose.PSD för .NET API-referens
description: TextFontInfo fast egendom. Får teckensnittsstil tolkad från underfamilj name
type: docs
weight: 50
url: /sv/net/aspose.psd.fileformats.psd.layers.text/textfontinfo/style/
---
## TextFontInfo.Style property

Får teckensnittsstil tolkad från underfamilj name

```csharp
public FontStyle Style { get; }
```

### Fastighetsvärde

Teckensnittsstil tolkad från underfamiljens namn

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

* enum [FontStyle](../../../aspose.psd/fontstyle/)
* class [TextFontInfo](../)
* namnutrymme [Aspose.PSD.FileFormats.Psd.Layers.Text](../../textfontinfo/)
* hopsättning [Aspose.PSD](../../../)


