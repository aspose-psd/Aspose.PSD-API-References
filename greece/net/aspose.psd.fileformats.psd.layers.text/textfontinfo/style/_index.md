---
title: "TextFontInfo.Style"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Ιδιότητα TextFontInfo. Λαμβάνει το στυλ γραμματοσειράς που προέρχεται από το όνομα υποοικογένειας"
type: docs
weight: 50
url: /el/net/aspose.psd.fileformats.psd.layers.text/textfontinfo/style/
---
{{< psd/tize >}}
## TextFontInfo.Style property

Λαμβάνει το στυλ γραμματοσειράς που προέρχεται από το όνομα υποοικογένειας

```csharp
public FontStyle Style { get; }
```

### Property Value

Στυλ γραμματοσειράς που προέρχεται από το όνομα υποοικογένειας

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

* enum [FontStyle](../../../aspose.psd/fontstyle/)
* class [TextFontInfo](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Text](../../../aspose.psd.fileformats.psd.layers.text/)
* assembly [Aspose.PSD](../../../)


