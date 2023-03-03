---
title: VectorShapeOriginSettings.OriginIndex
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: VectorShapeOriginSettings संपत्त. ओरजन शेप इंडेक्स क प्रप्त य सेट करत है
type: docs
weight: 120
url: /hi/net/aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/originindex/
---
## VectorShapeOriginSettings.OriginIndex property

ओरिजिन शेप इंडेक्स को प्राप्त या सेट करता है।

```csharp
public int OriginIndex { get; set; }
```

### उदाहरण

निम्न उदाहरण VogkResource संसाधन के समर्थन को प्रदर्शित करता है।

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

    // अध्ययन
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

### यह सभी देखें

* class [VectorShapeOriginSettings](../)
* नाम स्थान [Aspose.PSD.FileFormats.Core.VectorPaths](../../vectorshapeoriginsettings/)
* सभा [Aspose.PSD](../../../)


