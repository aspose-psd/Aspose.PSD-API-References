---
title: BackgroundColorResource.Color
second_title: Aspose.PSD για Αναφορά API .NET
description: BackgroundColorResource ιδιοκτησία. Παίρνει ή ορίζει το χρώμα φόντου.
type: docs
weight: 20
url: /el/net/aspose.psd.fileformats.psd.resources/backgroundcolorresource/color/
---
## BackgroundColorResource.Color property

Παίρνει ή ορίζει το χρώμα φόντου.

```csharp
public Color Color { get; set; }
```

### Παραδείγματα

Το ακόλουθο παράδειγμα δείχνει την υποστήριξη του πόρου BackgroundColorResource.

```csharp
[C#]

string sourceFilePath = "input.psd";
string outputFilePath = "output.psd";

using (var image = (PsdImage)Image.Load(sourceFilePath))
{
    ResourceBlock[] imageResources = image.ImageResources;
    BackgroundColorResource backgroundColorResource = null;
    foreach (var imageResource in imageResources)
    {
        if (imageResource is BackgroundColorResource)
        {
            backgroundColorResource = (BackgroundColorResource)imageResource;
            break;
        }
    }

    // ενημέρωση BackgroundColorResource
    backgroundColorResource.Color = Color.DarkRed;

    image.Save(outputFilePath);
}
```

### Δείτε επίσης

* struct [Color](../../../aspose.psd/color/)
* class [BackgroundColorResource](../)
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd.Resources](../../backgroundcolorresource/)
* συνέλευση [Aspose.PSD](../../../)


