---
title: "एनम PathOperations"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.FileFormats.Core.VectorPaths.PathOperations एनम। पाथ आकारों को बूलियन ऑपरेशनों के साथ संयोजित करने के लिए ऑपरेशन्स"
type: docs
weight: 1400
url: /hi/net/aspose.psd.fileformats.core.vectorpaths/pathoperations/
---
{{< psd/tize >}}
## PathOperations enumeration

पाथ शैप्स को संयोजित करने के लिए ऑपरेशन्स (बूलियन ऑपरेशन्स)।

```csharp
public enum PathOperations
```

### मान

| नाम | मान | विवरण |
| --- | --- | --- |
| ExcludeOverlappingShapes | `0` | ओवरलैपिंग आकारों को बाहर करें (XOR ऑपरेशन)। |
| CombineShapes | `1` | आकारों को संयोजित करें (OR ऑपरेशन)। यह Photoshop में डिफ़ॉल्ट मान है। |
| SubtractFrontShape | `2` | सामने के आकार को घटाएँ (NOT ऑपरेशन)। |
| IntersectShapeAreas | `3` | आकार क्षेत्रों का प्रतिच्छेदन करें (AND ऑपरेशन)। |

## उदाहरण

निम्नलिखित कोड उदाहरण नई LengthRecord गुणों, PathOperations (बूलियन ऑपरेशन्स), ShapeIndex और BezierKnotRecordsCount के समर्थन को दर्शाता है।

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

    // यहाँ हम आकारों के बीच संयोजन के तरीके को बदल रहे हैं।
    lengthRecord0.PathOperations = PathOperations.ExcludeOverlappingShapes;
    lengthRecord1.PathOperations = PathOperations.IntersectShapeAreas;
    lengthRecord2.PathOperations = PathOperations.SubtractFrontShape;

    im.Save(outputFilePath);
}
```

### देखें भी

* namespace [Aspose.PSD.FileFormats.Core.VectorPaths](../../aspose.psd.fileformats.core.vectorpaths/)
* assembly [Aspose.PSD](../../)


