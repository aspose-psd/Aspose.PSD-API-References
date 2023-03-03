---
title: Enum LineCapType
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources.LineCapType एनुम. लइन कैप प्रकर
type: docs
weight: 3040
url: /hi/net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/linecaptype/
---
## LineCapType enumeration

लाइन कैप प्रकार।

```csharp
public enum LineCapType : short
```

### मान

| नाम | कीमत | विवरण |
| --- | --- | --- |
| RoundCap | `0` | राउंड कैप टाइप. |
| SquareCap | `1` | स्क्वायर कैप प्रकार। |
| ButtCap | `2` | बट कैप प्रकार। |

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

* नाम स्थान [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/)
* सभा [Aspose.PSD](../../)


