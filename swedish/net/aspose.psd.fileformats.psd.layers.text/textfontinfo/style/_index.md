---
title: "TextFontInfo.Style"
second_title: "Aspose.PSD för .NET API‑referens"
description: "TextFontInfo-egenskap. Hämtar typsnittsstil som tolkas från underfamiljenamnet"
type: docs
weight: 50
url: /sv/net/aspose.psd.fileformats.psd.layers.text/textfontinfo/style/
---
{{< psd/tize >}}
## TextFontInfo.Style property

Hämtar teckensnittsstil som tolkas från underfamiljens namn

```csharp
public FontStyle Style { get; }
```

### Property Value

Typsnittsstil tolkad från underfamiljenamnet

## Exempel

Följande kod visar hur Aspose.PSD hämtar egenskaper för inlineformatering av Text Layer.

```csharp
[C#]

string sourceFile = "inline_formatting.psd";
List<ITextPortion> regularText = new List<ITextPortion>();
List<ITextPortion> boldText = new List<ITextPortion>();
List<ITextPortion> italicText = new List<ITextPortion>();

// Läs in en befintlig bild i en instans av klassen PsdImage
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

        // hämtar teckensnitt som finns i textlager
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
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Text](../../../aspose.psd.fileformats.psd.layers.text/)
* assembly [Aspose.PSD](../../../)


