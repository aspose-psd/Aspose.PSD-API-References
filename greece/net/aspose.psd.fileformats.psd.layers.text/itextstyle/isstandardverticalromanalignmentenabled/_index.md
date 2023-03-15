---
title: ITextStyle.IsStandardVerticalRomanAlignmentEnabled
second_title: Aspose.PSD για Αναφορά API .NET
description: ITextStyle ιδιοκτησία. Λαμβάνει ή ορίζει την τυπική κάθετη ρωμαϊκή στοίχιση. Αυτό με βάση την τιμή πόρου BaselineDirection ισχύει μόνο όταν ο προσανατολισμός κειμένου είναιVertical .
type: docs
weight: 170
url: /el/net/aspose.psd.fileformats.psd.layers.text/itextstyle/isstandardverticalromanalignmentenabled/
---
## ITextStyle.IsStandardVerticalRomanAlignmentEnabled property

Λαμβάνει ή ορίζει την τυπική κάθετη ρωμαϊκή στοίχιση. Αυτό με βάση την τιμή πόρου BaselineDirection ισχύει μόνο όταν ο προσανατολισμός κειμένου είναιVertical .

```csharp
public bool IsStandardVerticalRomanAlignmentEnabled { get; set; }
```

### Παραδείγματα

Ο ακόλουθος κώδικας δείχνει την υποστήριξη της νέας ιδιότητας IsStandardVerticalRomanAlignmentEnabled.

```csharp
[C#]

// Ο ακόλουθος κώδικας δείχνει τη δυνατότητα επεξεργασίας της νέας ιδιότητας IsStandardVerticalRomanAlignmentEnabled.
// Αυτό δεν επηρεάζει την απόδοση αυτή τη στιγμή, αλλά σας επιτρέπει μόνο να επεξεργαστείτε την τιμή της ιδιότητας.

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
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd.Layers.Text](../../itextstyle/)
* συνέλευση [Aspose.PSD](../../../)


