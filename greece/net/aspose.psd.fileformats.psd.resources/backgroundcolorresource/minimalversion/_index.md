---
title: "BackgroundColorResource.MinimalVersion"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Ιδιότητα BackgroundColorResource. Λαμβάνει την ελάχιστη απαιτούμενη έκδοση PSD"
type: docs
weight: 40
url: /el/net/aspose.psd.fileformats.psd.resources/backgroundcolorresource/minimalversion/
---
{{< psd/tize >}}
## BackgroundColorResource.MinimalVersion property

Λαμβάνει την ελάχιστη απαιτούμενη έκδοση PSD.

```csharp
public override int MinimalVersion { get; }
```

### Property Value

Η ελάχιστη έκδοση PSD.

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


