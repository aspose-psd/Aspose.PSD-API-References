---
title: "BorderInformationResource.Unit"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Properti BorderInformationResource. Mendapatkan atau mengatur satuan batas"
type: docs
weight: 40
url: /id/net/aspose.psd.fileformats.psd.resources/borderinformationresource/unit/
---
{{< psd/tize >}}
## BorderInformationResource.Unit property

Mendapatkan atau mengatur unit batas.

```csharp
public PhysicalUnit Unit { get; set; }
```

## Contoh

Contoh berikut menunjukkan dukungan sumber daya BorderInformationResource.

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

    // perbarui BorderInformationResource
    borderInfoResource.Width = 0.1;
    borderInfoResource.Unit = PhysicalUnit.Inches;

    image.Save(outputFilePath);
}
```

### Lihat Juga

* enum [PhysicalUnit](../../../aspose.psd.fileformats.psd.resources.resolutionenums/physicalunit/)
* class [BorderInformationResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Resources](../../../aspose.psd.fileformats.psd.resources/)
* assembly [Aspose.PSD](../../../)


