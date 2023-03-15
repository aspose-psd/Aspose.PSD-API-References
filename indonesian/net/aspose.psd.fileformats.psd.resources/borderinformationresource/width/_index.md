---
title: BorderInformationResource.Width
second_title: Aspose.PSD untuk Referensi .NET API
description: BorderInformationResource Properti. Mendapat atau mengatur lebar perbatasan.
type: docs
weight: 50
url: /id/net/aspose.psd.fileformats.psd.resources/borderinformationresource/width/
---
## BorderInformationResource.Width property

Mendapat atau mengatur lebar perbatasan.

```csharp
public double Width { get; set; }
```

### Contoh

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

### Lihat juga

* class [BorderInformationResource](../)
* ruang nama [Aspose.PSD.FileFormats.Psd.Resources](../../borderinformationresource/)
* perakitan [Aspose.PSD](../../../)


