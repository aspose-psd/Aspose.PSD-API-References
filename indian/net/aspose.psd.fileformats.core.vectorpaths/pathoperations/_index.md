---
title: Enum PathOperations
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: Aspose.PSD.FileFormats.Core.VectorPaths.PathOperations एनुम. पथ आकृतयं के संयजन के लए संचलन बूलयन संचलन
type: docs
weight: 1390
url: /hi/net/aspose.psd.fileformats.core.vectorpaths/pathoperations/
---
## PathOperations enumeration

पथ आकृतियों के संयोजन के लिए संचालन (बूलियन संचालन)।

```csharp
public enum PathOperations
```

### मान

| नाम | कीमत | विवरण |
| --- | --- | --- |
| ExcludeOverlappingShapes | `0` | ओवरलैपिंग आकृतियों को बाहर करें (XOR ऑपरेशन)। |
| CombineShapes | `1` | आकृतियों को संयोजित करें (या संक्रिया)। यह फोटोशॉप में डिफ़ॉल्ट मान है। |
| SubtractFrontShape | `2` | फ्रंट शेप घटाएं (ऑपरेशन नहीं) . |
| IntersectShapeAreas | `3` | प्रतिच्छेद आकार क्षेत्र (और संचालन). |

### उदाहरण

निम्न कोड उदाहरण नई लेंथरेकॉर्ड गुणों, पाथऑपरेशन (बूलियन ऑपरेशंस), शेपइंडेक्स और बेज़ियर नॉट रिकॉर्ड्सकाउंट के समर्थन को प्रदर्शित करता है।

```csharp
[C#]

string sourceFilePath = "PathOperationsShape.psd";
string outputFilePath = "out_PathOperationsShape.psd";

using (var im = (PsdImage)Image.Load(sourceFilePath))
{
    VsmsResource resource = null;
    foreach (var layerResource in im.Layers[1].Resources)
    {
        if (layerResource is VsmsResource)
        {
            resource = (VsmsResource)layerResource;
            break;
        }
    }

    LengthRecord lengthRecord0 = (LengthRecord)resource.Paths[2];
    LengthRecord lengthRecord1 = (LengthRecord)resource.Paths[7];
    LengthRecord lengthRecord2 = (LengthRecord)resource.Paths[11];

    // यहां हम आकृतियों के बीच संयोजन करने का तरीका बदलते हैं।
    lengthRecord0.PathOperations = PathOperations.ExcludeOverlappingShapes;
    lengthRecord1.PathOperations = PathOperations.IntersectShapeAreas;
    lengthRecord2.PathOperations = PathOperations.SubtractFrontShape;

    im.Save(outputFilePath);
}
```

### यह सभी देखें

* नाम स्थान [Aspose.PSD.FileFormats.Core.VectorPaths](../../aspose.psd.fileformats.core.vectorpaths/)
* सभा [Aspose.PSD](../../)


