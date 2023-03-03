---
title: LengthRecord.LengthRecord
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: LengthRecord नर्मत. क एक नय उदहरण प्ररंभ करत हैLengthRecord वर्ग.
type: docs
weight: 10
url: /hi/net/aspose.psd.fileformats.core.vectorpaths/lengthrecord/lengthrecord/
---
## LengthRecord(byte[]) {#constructor_1}

का एक नया उदाहरण प्रारंभ करता है[`LengthRecord`](../) वर्ग.

```csharp
public LengthRecord(byte[] data)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| data | Byte[] | रिकॉर्ड डेटा। |

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| !:PsdImageArgumentException | लेंथ रिकॉर्ड बनाने के लिए गलत डेटा |

### यह सभी देखें

* class [LengthRecord](../)
* नाम स्थान [Aspose.PSD.FileFormats.Core.VectorPaths](../../lengthrecord/)
* सभा [Aspose.PSD](../../../)

---

## LengthRecord() {#constructor}

का एक नया उदाहरण प्रारंभ करता है[`LengthRecord`](../) वर्ग.

```csharp
public LengthRecord()
```

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

* class [LengthRecord](../)
* नाम स्थान [Aspose.PSD.FileFormats.Core.VectorPaths](../../lengthrecord/)
* सभा [Aspose.PSD](../../../)


