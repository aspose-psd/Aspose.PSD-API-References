---
title: "ITextStyle.FontIndex"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "ITextStyle property. Λαμβάνει τον δείκτη γραμματοσειράς"
type: docs
weight: 110
url: /el/net/aspose.psd.fileformats.psd.layers.text/itextstyle/fontindex/
---
{{< psd/tize >}}
## ITextStyle.FontIndex property

Λαμβάνει τον δείκτη της γραμματοσειράς.

```csharp
public int FontIndex { get; }
```

### Property Value

Η γραμματοσειρά.

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς το Aspose.PSD λαμβάνει τις ιδιότητες της ενσωματωμένης μορφοποίησης του Text Layer.

```csharp
[C#]

string sourceFile = "inline_formatting.psd";
List<ITextPortion> regularText = new List<ITextPortion>();
List<ITextPortion> boldText = new List<ITextPortion>();
List<ITextPortion> italicText = new List<ITextPortion>();

// Φορτώστε μια υπάρχουσα εικόνα σε μια παρουσία της κλάσης PsdImage
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

        // λαμβάνει τις γραμματοσειρές που περιέχονται στο text layer
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

### Δείτε επίσης

* interface [ITextStyle](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Text](../../../aspose.psd.fileformats.psd.layers.text/)
* assembly [Aspose.PSD](../../../)


