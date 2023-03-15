---
title: VstkResource.StrokeStyleLineWidth
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: VstkResource संपत्त. स्ट्रक लइन क चड़ई प्रप्त य सेट करत है
type: docs
weight: 160
url: /hi/net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestylelinewidth/
---
## VstkResource.StrokeStyleLineWidth property

स्ट्रोक लाइन की चौड़ाई प्राप्त या सेट करता है।

```csharp
public double StrokeStyleLineWidth { get; set; }
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

* class [VstkResource](../)
* नाम स्थान [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources](../../vstkresource/)
* सभा [Aspose.PSD](../../../)


