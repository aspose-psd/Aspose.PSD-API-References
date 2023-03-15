---
title: BorderInformationResource.MinimalVersion
second_title: Aspose.PSD για Αναφορά API .NET
description: BorderInformationResource ιδιοκτησία. Αποκτά την ελάχιστη απαιτούμενη έκδοση PSD.
type: docs
weight: 30
url: /el/net/aspose.psd.fileformats.psd.resources/borderinformationresource/minimalversion/
---
## BorderInformationResource.MinimalVersion property

Αποκτά την ελάχιστη απαιτούμενη έκδοση PSD.

```csharp
public override int MinimalVersion { get; }
```

### Αξία περιουσίας

Η minimal έκδοση PSD.

### Παραδείγματα

Το ακόλουθο παράδειγμα δείχνει την υποστήριξη του πόρου BorderInformationResource.

```csharp
[C#]

string sourceFilePath = "input.psd";
string outputFilePath = "output.psd";

using (var image = (PsdImage)Image.Load(sourceFilePath))
{
    ResourceBlock[] imageResources = image.ImageResources;
    BorderInformationResource borderInfoResource = null;
    foreach (var imageResource in imageResources)
    {
        if (imageResource is BorderInformationResource)
        {
            borderInfoResource = (BorderInformationResource)imageResource;
            break;
        }
    }

    // ενημέρωση BorderInformationResource
    borderInfoResource.Width = 0.1;
    borderInfoResource.Unit = PhysicalUnit.Inches;

    image.Save(outputFilePath);
}
```

### Δείτε επίσης

* class [BorderInformationResource](../)
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd.Resources](../../borderinformationresource/)
* συνέλευση [Aspose.PSD](../../../)


