---
title: TextFontInfo.Style
second_title: Aspose.PSD για Αναφορά API .NET
description: TextFontInfo ιδιοκτησία. Παίρνει ανάλυση του στυλ γραμματοσειράς από την υποοικογένεια name
type: docs
weight: 50
url: /el/net/aspose.psd.fileformats.psd.layers.text/textfontinfo/style/
---
## TextFontInfo.Style property

Παίρνει ανάλυση του στυλ γραμματοσειράς από την υποοικογένεια name

```csharp
public FontStyle Style { get; }
```

### Αξία περιουσίας

Το στυλ γραμματοσειράς αναλύθηκε από την υποοικογένεια name

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

* enum [FontStyle](../../../aspose.psd/fontstyle/)
* class [TextFontInfo](../)
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd.Layers.Text](../../textfontinfo/)
* συνέλευση [Aspose.PSD](../../../)


