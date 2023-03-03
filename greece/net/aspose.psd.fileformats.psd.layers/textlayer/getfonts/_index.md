---
title: TextLayer.GetFonts
second_title: Aspose.PSD για Αναφορά API .NET
description: TextLayer μέθοδος. Λαμβάνει το σύνολο γραμματοσειρών του επιπέδου κειμένου.
type: docs
weight: 80
url: /el/net/aspose.psd.fileformats.psd.layers/textlayer/getfonts/
---
## TextLayer.GetFonts method

Λαμβάνει το σύνολο γραμματοσειρών του επιπέδου κειμένου.

```csharp
public TextFontInfo[] GetFonts()
```

### Επιστρεφόμενη Αξία

Το σύνολο γραμματοσειρών του επιπέδου κειμένου.

### Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς το Aspose.PSD λαμβάνει ιδιότητες ενσωματωμένης μορφοποίησης του επιπέδου κειμένου.

```csharp
[C#]

string sourceFile = "inline_formatting.psd";
List<ITextPortion> regularText = new List<ITextPortion>();
List<ITextPortion> boldText = new List<ITextPortion>();
List<ITextPortion> italicText = new List<ITextPortion>();

// Φόρτωση μιας υπάρχουσας εικόνας σε μια παρουσία της κλάσης PsdImage
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

        // λαμβάνει γραμματοσειρές που περιέχει στο επίπεδο κειμένου
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

* class [TextFontInfo](../../../aspose.psd.fileformats.psd.layers.text/textfontinfo/)
* class [TextLayer](../)
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd.Layers](../../textlayer/)
* συνέλευση [Aspose.PSD](../../../)


