---
title: "VogkResource.Length"
second_title: "Aspose.PSD for .NET API Referansı"
description: "VogkResource özelliği. Katman kaynağı uzunluğunu bayt cinsinden alır"
type: docs
weight: 20
url: /tr/net/aspose.psd.fileformats.psd.layers.layerresources/vogkresource/length/
---
{{< psd/tize >}}
## VogkResource.Length property

Katman kaynağı uzunluğunu bayt cinsinden alır.

```csharp
public override int Length { get; }
```

## Örnekler

Aşağıdaki örnek, VogkResource kaynağının desteğini gösterir.

```csharp
[C#]

VogkResource GetVogkResource(PsdImage image)
{
    var layer = image.Layers[1];

    VogkResource resource = null;
    var resources = layer.Resources;
    for (int i = 0; i < resources.Length; i++)
    {
        if (resources[i] is VogkResource)
        {
            resource = (VogkResource)resources[i];
            break;
        }
    }

    if (resource == null)
    {
        throw new Exception("VogkResourcenot found.");
    }

    return resource;
}

string sourceFilePath = "VectorOriginationDataResource.psd";
string outputFilePath = "out_VectorOriginationDataResource_.psd";

using (var psdImage = (PsdImage)Image.Load(sourceFilePath))
{
    var resource = GetVogkResource(psdImage);

    // Okuma
    if (resource.ShapeOriginSettings.Length != 1 ||
        !resource.ShapeOriginSettings[0].IsShapeInvalidated ||
        resource.ShapeOriginSettings[0].OriginIndex != 0)
    {
        throw new Exception("VogkResource were read wrong.");
    }

    // Düzenleme
    resource.ShapeOriginSettings = new[]
    {
        resource.ShapeOriginSettings[0],
        new VectorShapeOriginSettings(true, 1)
    };

    psdImage.Save(outputFilePath);
}
```

### Ayrıca Bakınız

* class [VogkResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


