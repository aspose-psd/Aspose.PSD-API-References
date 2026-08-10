---
title: "एनम LineCapType"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources.LineCapType एनम। लाइन कैप प्रकार"
type: docs
weight: 3400
url: /hi/net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/linecaptype/
---
{{< psd/tize >}}
## LineCapType enumeration

लाइन कैप प्रकार।

```csharp
public enum LineCapType : short
```

### मान

| नाम | मान | विवरण |
| --- | --- | --- |
| RoundCap | `0` | राउंड कैप प्रकार। |
| SquareCap | `1` | स्क्वायर कैप प्रकार। |
| ButtCap | `2` | बट कैप प्रकार। |

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


