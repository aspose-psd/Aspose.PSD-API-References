---
title: "BorderInformationResource.DataSize"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Properti BorderInformationResource. Mendapatkan ukuran data sumber daya dalam byte"
type: docs
weight: 20
url: /id/net/aspose.psd.fileformats.psd.resources/borderinformationresource/datasize/
---
{{< psd/tize >}}
## BorderInformationResource.DataSize property

Mendapatkan ukuran data sumber daya dalam byte.

```csharp
public override int DataSize { get; }
```

### Property Value

Ukuran data sumber daya.

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

* class [BorderInformationResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Resources](../../../aspose.psd.fileformats.psd.resources/)
* assembly [Aspose.PSD](../../../)


