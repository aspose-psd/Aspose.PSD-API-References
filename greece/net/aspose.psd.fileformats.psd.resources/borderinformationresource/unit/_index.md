---
title: BorderInformationResource.Unit
second_title: Aspose.PSD για Αναφορά API .NET
description: BorderInformationResource ιδιοκτησία. Λαμβάνει ή ορίζει τις μονάδες συνόρων.
type: docs
weight: 40
url: /el/net/aspose.psd.fileformats.psd.resources/borderinformationresource/unit/
---
## BorderInformationResource.Unit property

Λαμβάνει ή ορίζει τις μονάδες συνόρων.

```csharp
public PhysicalUnit Unit { get; set; }
```

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

* enum [PhysicalUnit](../../../aspose.psd.fileformats.psd.resources.resolutionenums/physicalunit/)
* class [BorderInformationResource](../)
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd.Resources](../../borderinformationresource/)
* συνέλευση [Aspose.PSD](../../../)


