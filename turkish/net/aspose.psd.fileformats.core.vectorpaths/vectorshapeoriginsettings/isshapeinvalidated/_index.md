---
title: "VectorShapeOriginSettings.IsShapeInvalidated"
second_title: "Aspose.PSD for .NET API Referansı"
description: "VectorShapeOriginSettings özelliği. Şeklin geçersiz olup olmadığını gösteren bir değeri alır veya ayarlar"
type: docs
weight: 80
url: /tr/net/aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isshapeinvalidated/
---
{{< psd/tize >}}
## VectorShapeOriginSettings.IsShapeInvalidated property

Şeklin geçersiz olup olmadığını gösteren bir değeri alır veya ayarlar.

```csharp
public bool IsShapeInvalidated { get; set; }
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

* class [VectorShapeOriginSettings](../)
* namespace [Aspose.PSD.FileFormats.Core.VectorPaths](../../../aspose.psd.fileformats.core.vectorpaths/)
* assembly [Aspose.PSD](../../../)


