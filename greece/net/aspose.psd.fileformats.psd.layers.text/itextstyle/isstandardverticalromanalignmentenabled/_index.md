---
title: "ITextStyle.IsStandardVerticalRomanAlignmentEnabled"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "ITextStyle property. Λαμβάνει ή ορίζει την τυπική κάθετη Ρωμαϊκή στοίχιση. Αυτό βασίζεται στην τιμή του πόρου BaselineDirection και εφαρμόζεται μόνο όταν ο προσανατολισμός κειμένου είναι Κάθετος."
type: docs
weight: 170
url: /el/net/aspose.psd.fileformats.psd.layers.text/itextstyle/isstandardverticalromanalignmentenabled/
---
{{< psd/tize >}}
## ITextStyle.IsStandardVerticalRomanAlignmentEnabled property

Λαμβάνει ή ορίζει την τυπική κατακόρυφη ρωμαϊκή στοίχιση. Αυτό βασίζεται στην τιμή πόρου BaselineDirection και εφαρμόζεται μόνο όταν ο προσανατολισμός κειμένου είναι Κατακόρυφος.

```csharp
public bool IsStandardVerticalRomanAlignmentEnabled { get; set; }
```

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει την υποστήριξη της νέας ιδιότητας IsStandardVerticalRomanAlignmentEnabled.

```csharp
[C#]

// Ο παρακάτω κώδικας δείχνει τη δυνατότητα επεξεργασίας της νέας ιδιότητας IsStandardVerticalRomanAlignmentEnabled.
// Αυτό δεν επηρεάζει την απόδοση αυτή τη στιγμή, αλλά επιτρέπει μόνο την επεξεργασία της τιμής της ιδιότητας.

string src = "1346test.psd";
string output = "out_1346test.psd";

using (var image = (PsdImage)Image.Load(src))
{
    var textLayer = image.Layers[1] as TextLayer;
    var textPortion = textLayer.TextData.Items[0];
    if (textPortion.Style.IsStandardVerticalRomanAlignmentEnabled)
    {
        // Σωστή ανάγνωση
    }
    else
    {
        throw new Exception("Incorrect reading of IsStandardVerticalRomanAlignmentEnabled property value");
    }

    textPortion.Style.IsStandardVerticalRomanAlignmentEnabled = false;
    textLayer.TextData.UpdateLayerData();

    image.Save(output);
}

using (var image = (PsdImage)Image.Load(output))
{
    var textLayer = image.Layers[1] as TextLayer;
    var textPortion = textLayer.TextData.Items[0];
    if (!textPortion.Style.IsStandardVerticalRomanAlignmentEnabled)
    {
        // Σωστή ανάγνωση
    }
    else
    {
        throw new Exception("Incorrect reading of IsStandardVerticalRomanAlignmentEnabled property value");
    }
}
```

### Δείτε επίσης

* interface [ITextStyle](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Text](../../../aspose.psd.fileformats.psd.layers.text/)
* assembly [Aspose.PSD](../../../)


