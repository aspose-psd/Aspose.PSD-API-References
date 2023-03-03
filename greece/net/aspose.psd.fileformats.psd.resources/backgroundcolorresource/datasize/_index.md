---
title: BackgroundColorResource.DataSize
second_title: Aspose.PSD για Αναφορά API .NET
description: BackgroundColorResource ιδιοκτησία. Λαμβάνει το μέγεθος δεδομένων πόρων σε byte.
type: docs
weight: 30
url: /el/net/aspose.psd.fileformats.psd.resources/backgroundcolorresource/datasize/
---
## BackgroundColorResource.DataSize property

Λαμβάνει το μέγεθος δεδομένων πόρων σε byte.

```csharp
public override int DataSize { get; }
```

### Αξία περιουσίας

Το μέγεθος δεδομένων πόρων.

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


