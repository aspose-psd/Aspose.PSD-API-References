---
title: IText.TextOrientation
second_title: Aspose.PSD για Αναφορά API .NET
description: IText ιδιοκτησία. Λαμβάνει ή ορίζει τον προσανατολισμό του κειμένου.
type: docs
weight: 30
url: /el/net/aspose.psd.fileformats.psd.layers.text/itext/textorientation/
---
## IText.TextOrientation property

Λαμβάνει ή ορίζει τον προσανατολισμό του κειμένου.

```csharp
public TextOrientation TextOrientation { get; set; }
```

### Αξία περιουσίας

Ο προσανατολισμός του κειμένου.

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

* enum [TextOrientation](../../../aspose.psd.fileformats.psd/textorientation/)
* interface [IText](../)
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd.Layers.Text](../../itext/)
* συνέλευση [Aspose.PSD](../../../)


