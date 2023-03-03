---
title: VogkResource.PsdVersion
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: VogkResource संपत्त. परत संसधन के लए आवश्यक न्यूनतम PSD संस्करण प्रप्त करत है 0 कई प्रतबंध नहं दर्शत है
type: docs
weight: 40
url: /hi/net/aspose.psd.fileformats.psd.layers.layerresources/vogkresource/psdversion/
---
## VogkResource.PsdVersion property

परत संसाधन के लिए आवश्यक न्यूनतम PSD संस्करण प्राप्त करता है। 0 कोई प्रतिबंध नहीं दर्शाता है।

```csharp
public override int PsdVersion { get; }
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


