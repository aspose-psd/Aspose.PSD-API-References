---
title: "VstkResource.StrokeStyleLineAlignment"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "VstkResource प्रॉपर्टी। स्ट्रोक स्टाइल लाइन अलाइनमेंट प्राप्त करता है या सेट करता है"
type: docs
weight: 80
url: /hi/net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestylelinealignment/
---
{{< psd/tize >}}
## VstkResource.StrokeStyleLineAlignment property

स्ट्रोक शैली की लाइन संरेखण प्राप्त करता या सेट करता है।

```csharp
public StrokePosition StrokeStyleLineAlignment { get; set; }
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

* enum [StrokePosition](../../../aspose.psd.fileformats.psd.layers.layereffects/strokeposition/)
* class [VstkResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources](../../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/)
* assembly [Aspose.PSD](../../../)


