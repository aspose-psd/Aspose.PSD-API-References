---
title: BorderInformationResource.MinimalVersion
second_title: Aspose.PSD untuk Referensi .NET API
description: BorderInformationResource Properti. Mendapatkan versi PSD minimal yang diperlukan.
type: docs
weight: 30
url: /id/net/aspose.psd.fileformats.psd.resources/borderinformationresource/minimalversion/
---
## BorderInformationResource.MinimalVersion property

Mendapatkan versi PSD minimal yang diperlukan.

```csharp
public override int MinimalVersion { get; }
```

### Nilai properti

Versi PSD minimal.

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


