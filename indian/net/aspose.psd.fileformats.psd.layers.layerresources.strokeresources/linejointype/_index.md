---
title: "Enum LineJoinType"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources.LineJoinType enum. लाइन जॉइन प्रकार"
type: docs
weight: 3410
url: /hi/net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/linejointype/
---
{{< psd/tize >}}
## LineJoinType enumeration

लाइन जॉइन प्रकार।

```csharp
public enum LineJoinType : short
```

### मान

| नाम | मान | विवरण |
| --- | --- | --- |
| BevelJoin | `0` | बिवेल जॉइन प्रकार। |
| RoundJoin | `1` | Rounnd जॉइन प्रकार। |
| MiterJoin | `2` | माइटर जॉइन प्रकार। |

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

* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/)
* assembly [Aspose.PSD](../../)


