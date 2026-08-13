---
title: "BorderInformationResource.MinimalVersion"
second_title: "Aspose.PSD for .NET API Referansı"
description: "BorderInformationResource özelliği. Gerekli minimum PSD sürümünü alır"
type: docs
weight: 30
url: /tr/net/aspose.psd.fileformats.psd.resources/borderinformationresource/minimalversion/
---
{{< psd/tize >}}
## BorderInformationResource.MinimalVersion property

Gerekli minimum PSD sürümünü alır.

```csharp
public override int MinimalVersion { get; }
```

### Property Value

Minimum PSD sürümü.

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


