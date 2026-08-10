---
title: "VectorShapeOriginSettings.OriginIndex"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "VectorShapeOriginSettings प्रॉपर्टी। मूल आकार इंडेक्स को प्राप्त करता है या सेट करता है"
type: docs
weight: 120
url: /hi/net/aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/originindex/
---
{{< psd/tize >}}
## VectorShapeOriginSettings.OriginIndex property

origin shape index प्राप्त करता है या सेट करता है।

```csharp
public int OriginIndex { get; set; }
```

## उदाहरण

निम्न उदाहरण VogkResource संसाधन के समर्थन को दर्शाता है।

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

    // पढ़ना
    if (resource.ShapeOriginSettings.Length != 1 ||
        !resource.ShapeOriginSettings[0].IsShapeInvalidated ||
        resource.ShapeOriginSettings[0].OriginIndex != 0)
    {
        throw new Exception("VogkResource were read wrong.");
    }

    // संपादन
    resource.ShapeOriginSettings = new[]
    {
        resource.ShapeOriginSettings[0],
        new VectorShapeOriginSettings(true, 1)
    };

    psdImage.Save(outputFilePath);
}
```

### देखें भी

* class [VectorShapeOriginSettings](../)
* namespace [Aspose.PSD.FileFormats.Core.VectorPaths](../../../aspose.psd.fileformats.core.vectorpaths/)
* assembly [Aspose.PSD](../../../)


