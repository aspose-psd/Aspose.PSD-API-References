---
title: "Απαρίθμηση TextOrientation"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Απαρίθμηση Aspose.PSD.FileFormats.Psd.TextOrientation. Απαρίθμηση για τη λειτουργία προσανατολισμού κειμένου"
type: docs
weight: 4480
url: /el/net/aspose.psd.fileformats.psd/textorientation/
---
{{< psd/tize >}}
## TextOrientation enumeration

Απαρίθμηση για τη λειτουργία προσανατολισμού κειμένου.

```csharp
public enum TextOrientation
```

### Τιμές

| Όνομα | Τιμή | Περιγραφή |
| --- | --- | --- |
| Horizontal | `0` | Ο οριζόντιος προσανατολισμός κειμένου. |
| Vertical | `2` | Ο κάθετος προσανατολισμός κειμένου. |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει τη δυνατότητα επεξεργασίας της νέας ιδιότητας TextOrientation. Αυτό δεν επηρεάζει την απόδοση αυτή τη στιγμή, αλλά επιτρέπει μόνο την επεξεργασία της τιμής της ιδιότητας.

```csharp
[C#]

string src = "1336test.psd";
string output = "out_1336test.psd";

using (var image = (PsdImage)Image.Load(src))
{
    var textLayer = image.Layers[1] as TextLayer;
    if (textLayer.TextData.TextOrientation == TextOrientation.Vertical)
    {
        // Σωστή ανάγνωση
    }
    else
    {
        throw new Exception("Incorrect reading of TextOrientation property value");
    }

    textLayer.TextData.TextOrientation = TextOrientation.Horizontal;
    textLayer.TextData.UpdateLayerData();

    image.Save(output);
}

using (var image = (PsdImage)Image.Load(output))
{
    var textLayer = image.Layers[1] as TextLayer;
    if (textLayer.TextData.TextOrientation == TextOrientation.Horizontal)
    {
        // Σωστή ανάγνωση
    }
    else
    {
        throw new Exception("Incorrect reading of TextOrientation property value");
    }
}
```

### Δείτε επίσης

* namespace [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../)


