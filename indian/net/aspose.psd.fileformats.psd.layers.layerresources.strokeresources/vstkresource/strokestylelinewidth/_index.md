---
title: "VstkResource.StrokeStyleLineWidth"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "VstkResource प्रॉपर्टी। स्ट्रोक लाइन चौड़ाई प्राप्त करता है या सेट करता है"
type: docs
weight: 140
url: /hi/net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestylelinewidth/
---
{{< psd/tize >}}
## VstkResource.StrokeStyleLineWidth property

स्ट्रोक लाइन की चौड़ाई प्राप्त करता या सेट करता है।

```csharp
public double StrokeStyleLineWidth { get; set; }
```

## उदाहरण

निम्नलिखित कोड VstkResource संसाधन के समर्थन को दर्शाता है।

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

### देखें भी

* class [VstkResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources](../../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/)
* assembly [Aspose.PSD](../../../)


