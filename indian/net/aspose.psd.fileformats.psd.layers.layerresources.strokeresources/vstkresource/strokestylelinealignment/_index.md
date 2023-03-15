---
title: VstkResource.StrokeStyleLineAlignment
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: VstkResource संपत्त. स्ट्रक स्टइल लइन संरेखण प्रप्त य सेट करत है
type: docs
weight: 100
url: /hi/net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestylelinealignment/
---
## VstkResource.StrokeStyleLineAlignment property

स्ट्रोक स्टाइल लाइन संरेखण प्राप्त या सेट करता है।

```csharp
public StrokePosition StrokeStyleLineAlignment { get; set; }
```

### उदाहरण

निम्न कोड VstkResource संसाधन के समर्थन को प्रदर्शित करता है।

```csharp
[C#]

string srcFile = "StrokeShapeTest1.psd";
string dstFile = "StrokeShapeTest2.psd";

using (PsdImage image = (PsdImage)Image.Load(srcFile))
{
    Layer layer = image.Layers[1];
    foreach (LayerResource resource in layer.Resources)
    {
        if (resource is VstkResource)
        {
            VstkResource vstkResource = (VstkResource)resource;
            vstkResource.StrokeStyleLineAlignment = StrokePosition.Outside;
            vstkResource.StrokeStyleLineWidth = 20;
        }
    }

    image.Save(dstFile);
}
```

### यह सभी देखें

* enum [StrokePosition](../../../aspose.psd.fileformats.psd.layers.layereffects/strokeposition/)
* class [VstkResource](../)
* नाम स्थान [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources](../../vstkresource/)
* सभा [Aspose.PSD](../../../)


