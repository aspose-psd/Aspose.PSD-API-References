---
title: "BorderInformationResource.Width"
second_title: "Aspose.PSD for .NET API Referansı"
description: "BorderInformationResource özelliği. Kenar genişliğini alır veya ayarlar"
type: docs
weight: 50
url: /tr/net/aspose.psd.fileformats.psd.resources/borderinformationresource/width/
---
{{< psd/tize >}}
## BorderInformationResource.Width property

Kenar genişliğini alır veya ayarlar.

```csharp
public double Width { get; set; }
```

## Örnekler

Aşağıdaki örnek, BorderInformationResource kaynağının desteğini gösterir.

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

    // güncelle BorderInformationResource
    borderInfoResource.Width = 0.1;
    borderInfoResource.Unit = PhysicalUnit.Inches;

    image.Save(outputFilePath);
}
```

### Ayrıca Bakınız

* class [BorderInformationResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Resources](../../../aspose.psd.fileformats.psd.resources/)
* assembly [Aspose.PSD](../../../)


