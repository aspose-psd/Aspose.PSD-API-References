---
title: "LengthRecord.BezierKnotRecordsCount"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "LengthRecord प्रॉपर्टी। बेज़ियर नॉट रिकॉर्ड्स की गिनती प्राप्त करता या सेट करता है"
type: docs
weight: 20
url: /hi/net/aspose.psd.fileformats.core.vectorpaths/lengthrecord/bezierknotrecordscount/
---
{{< psd/tize >}}
## LengthRecord.BezierKnotRecordsCount property

bezier knot records count प्राप्त करता है या सेट करता है।

```csharp
public int BezierKnotRecordsCount { get; set; }
```

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

* class [LengthRecord](../)
* namespace [Aspose.PSD.FileFormats.Core.VectorPaths](../../../aspose.psd.fileformats.core.vectorpaths/)
* assembly [Aspose.PSD](../../../)


