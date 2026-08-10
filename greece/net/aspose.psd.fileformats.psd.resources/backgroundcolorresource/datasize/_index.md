---
title: "BackgroundColorResource.DataSize"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Ιδιότητα BackgroundColorResource. Λαμβάνει το μέγεθος δεδομένων του πόρου σε byte"
type: docs
weight: 30
url: /el/net/aspose.psd.fileformats.psd.resources/backgroundcolorresource/datasize/
---
{{< psd/tize >}}
## BackgroundColorResource.DataSize property

Λαμβάνει το μέγεθος δεδομένων του πόρου σε byte.

```csharp
public override int DataSize { get; }
```

### Property Value

Το μέγεθος δεδομένων του πόρου.

## Παραδείγματα

Το παρακάτω παράδειγμα δείχνει την υποστήριξη του πόρου BackgroundColorResource.

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
* namespace [Aspose.PSD.FileFormats.Psd.Resources](../../../aspose.psd.fileformats.psd.resources/)
* assembly [Aspose.PSD](../../../)


