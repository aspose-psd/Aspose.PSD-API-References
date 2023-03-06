---
title: BorderInformationResource.Unit
second_title: Aspose.PSD for .NET API Referansı
description: BorderInformationResource mülk. Sınır birimlerini alır veya ayarlar.
type: docs
weight: 40
url: /tr/net/aspose.psd.fileformats.psd.resources/borderinformationresource/unit/
---
## BorderInformationResource.Unit property

Sınır birimlerini alır veya ayarlar.

```csharp
public PhysicalUnit Unit { get; set; }
```

### Örnekler

Aşağıdaki örnek, BorderInformationResource kaynağının desteğini göstermektedir.

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

    // BorderInformationResource'u güncelle
    borderInfoResource.Width = 0.1;
    borderInfoResource.Unit = PhysicalUnit.Inches;

    image.Save(outputFilePath);
}
```

### Ayrıca bakınız

* enum [PhysicalUnit](../../../aspose.psd.fileformats.psd.resources.resolutionenums/physicalunit/)
* class [BorderInformationResource](../)
* ad alanı [Aspose.PSD.FileFormats.Psd.Resources](../../borderinformationresource/)
* toplantı [Aspose.PSD](../../../)


