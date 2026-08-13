---
title: "BorderInformationResource.DataSize"
second_title: "Aspose.PSD for .NET API Referansı"
description: "BorderInformationResource özelliği. Kaynak veri boyutunu bayt cinsinden alır"
type: docs
weight: 20
url: /tr/net/aspose.psd.fileformats.psd.resources/borderinformationresource/datasize/
---
{{< psd/tize >}}
## BorderInformationResource.DataSize property

Kaynak veri boyutunu bayt olarak alır.

```csharp
public override int DataSize { get; }
```

### Property Value

Kaynak veri boyutu.

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


