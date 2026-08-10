---
title: "BorderInformationResource.Unit"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "BorderInformationResource ιδιότητα. Λαμβάνει και ορίζει τις μονάδες του περιγράμματος"
type: docs
weight: 40
url: /el/net/aspose.psd.fileformats.psd.resources/borderinformationresource/unit/
---
{{< psd/tize >}}
## BorderInformationResource.Unit property

Λαμβάνει ή ορίζει τις μονάδες περιγράμματος.

```csharp
public PhysicalUnit Unit { get; set; }
```

## Παραδείγματα

Το παρακάτω παράδειγμα δείχνει την υποστήριξη του πόρου BorderInformationResource.

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
* namespace [Aspose.PSD.FileFormats.Psd.Resources](../../../aspose.psd.fileformats.psd.resources/)
* assembly [Aspose.PSD](../../../)


