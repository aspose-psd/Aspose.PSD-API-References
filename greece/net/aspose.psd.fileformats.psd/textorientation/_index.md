---
title: Enum TextOrientation
second_title: Aspose.PSD για Αναφορά API .NET
description: Aspose.PSD.FileFormats.Psd.TextOrientation αρίθμηση. Απαρίθμηση για λειτουργία προσανατολισμού κειμένου.
type: docs
weight: 4010
url: /el/net/aspose.psd.fileformats.psd/textorientation/
---
## TextOrientation enumeration

Απαρίθμηση για λειτουργία προσανατολισμού κειμένου.

```csharp
public enum TextOrientation
```

### Αξίες

| Ονομα | αξία | Περιγραφή |
| --- | --- | --- |
| Horizontal | `0` | Ο οριζόντιος προσανατολισμός κειμένου. |
| Vertical | `2` | Ο κατακόρυφος προσανατολισμός κειμένου. |

### Παραδείγματα

Ο παρακάτω κώδικας δείχνει τη δυνατότητα επεξεργασίας της νέας ιδιότητας TextOrientation. Αυτό δεν επηρεάζει την απόδοση αυτή τη στιγμή, αλλά σας επιτρέπει μόνο να επεξεργαστείτε την τιμή της ιδιότητας.

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

* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* συνέλευση [Aspose.PSD](../../)


