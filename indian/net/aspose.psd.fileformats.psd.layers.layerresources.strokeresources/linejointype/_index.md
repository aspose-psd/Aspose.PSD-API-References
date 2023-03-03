---
title: Enum LineJoinType
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources.LineJoinType एनुम. लइन ज्वइन प्रकर
type: docs
weight: 3050
url: /hi/net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/linejointype/
---
## LineJoinType enumeration

लाइन ज्वाइन प्रकार।

```csharp
public enum LineJoinType : short
```

### मान

| नाम | कीमत | विवरण |
| --- | --- | --- |
| BevelJoin | `0` | बेवेल ज्वाइन टाइप. |
| RoundJoin | `1` | राउंड जॉइन टाइप. |
| MiterJoin | `2` | मिटर प्रकार से जुड़ें। |

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


