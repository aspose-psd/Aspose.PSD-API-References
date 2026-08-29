---
title: "Απαρίθμηση LeadingType"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Απαρίθμηση Aspose.PSD.FileFormats.Psd.LeadingType. Τύπος leading του Photoshop, τύπος απόστασης μεταξύ γραμμών"
type: docs
weight: 4030
url: /el/net/aspose.psd.fileformats.psd/leadingtype/
---
{{< psd/tize >}}
## LeadingType enumeration

Τύπος leading του Photoshop (τύπος απόστασης μεταξύ γραμμών).

```csharp
public enum LeadingType
```

### Τιμές

| Όνομα | Τιμή | Περιγραφή |
| --- | --- | --- |
| BottomToBottom | `0` | Το leading από κάτω προς κάτω. |
| TopToTop | `1` | Το leading από πάνω προς πάνω. |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει την υποστήριξη των λειτουργιών leading από κάτω προς κάτω και από πάνω προς πάνω από τις ρυθμίσεις παραγράφου.

```csharp
[C#]

string input = "leadingMode.psd";
string output = "output_leadingMode.png";

using (var psdImage = (PsdImage)Image.Load(input, new PsdLoadOptions()))
{
    IText text1 = ((TextLayer)psdImage.Layers[1]).TextData;
    foreach (var textPortion in text1.Items)
    {
        textPortion.Paragraph.LeadingType = LeadingType.TopToTop; // Change LeadingType value   
    }
    text1.Items[8].Text = "TopToTop";
    text1.Items[8].Style.FillColor = Color.ForestGreen;
    text1.UpdateLayerData();

    IText text2 = ((TextLayer)psdImage.Layers[2]).TextData;
    foreach (var textPortion in text2.Items)
    {
        textPortion.Paragraph.LeadingType = LeadingType.BottomToBottom; // Change LeadingType value   
    }
    text2.Items[8].Text = "BottomToBottom";
    text2.Items[8].Style.FillColor = Color.ForestGreen;
    text2.UpdateLayerData();

    psdImage.Save(output, new PngOptions());
}
```

### Δείτε επίσης

* namespace [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../)


