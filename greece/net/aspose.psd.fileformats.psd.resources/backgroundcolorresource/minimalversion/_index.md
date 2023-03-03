---
title: BackgroundColorResource.MinimalVersion
second_title: Aspose.PSD για Αναφορά API .NET
description: BackgroundColorResource ιδιοκτησία. Αποκτά την ελάχιστη απαιτούμενη έκδοση PSD.
type: docs
weight: 40
url: /el/net/aspose.psd.fileformats.psd.resources/backgroundcolorresource/minimalversion/
---
## BackgroundColorResource.MinimalVersion property

Αποκτά την ελάχιστη απαιτούμενη έκδοση PSD.

```csharp
public override int MinimalVersion { get; }
```

### Αξία περιουσίας

Η minimal έκδοση PSD.

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

* class [BackgroundColorResource](../)
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd.Resources](../../backgroundcolorresource/)
* συνέλευση [Aspose.PSD](../../../)


