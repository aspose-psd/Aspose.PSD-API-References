---
title: VogkResource.Key
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: VogkResource संपत्त. परत संसधन कुंज प्रप्त करत है.
type: docs
weight: 20
url: /hi/net/aspose.psd.fileformats.psd.layers.layerresources/vogkresource/key/
---
## VogkResource.Key property

परत संसाधन कुंजी प्राप्त करता है.

```csharp
public override int Key { get; }
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

* class [VogkResource](../)
* नाम स्थान [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../vogkresource/)
* सभा [Aspose.PSD](../../../)


