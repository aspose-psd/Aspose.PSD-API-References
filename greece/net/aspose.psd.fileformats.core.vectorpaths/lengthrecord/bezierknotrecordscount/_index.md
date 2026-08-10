---
title: "LengthRecord.BezierKnotRecordsCount"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Ιδιότητα LengthRecord. Λαμβάνει ή ορίζει τον αριθμό των εγγραφών κόμβων Bezier"
type: docs
weight: 20
url: /el/net/aspose.psd.fileformats.core.vectorpaths/lengthrecord/bezierknotrecordscount/
---
{{< psd/tize >}}
## LengthRecord.BezierKnotRecordsCount property

Λαμβάνει ή ορίζει τον αριθμό των εγγραφών κόμβων Bezier.

```csharp
public int BezierKnotRecordsCount { get; set; }
```

## Παραδείγματα

Το παρακάτω παράδειγμα κώδικα δείχνει την υποστήριξη των νέων ιδιοτήτων LengthRecord, PathOperations (λογικές λειτουργίες), ShapeIndex και BezierKnotRecordsCount.

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

    // Εδώ αλλάζουμε τον τρόπο συνδυασμού μεταξύ σχημάτων.
    lengthRecord0.PathOperations = PathOperations.ExcludeOverlappingShapes;
    lengthRecord1.PathOperations = PathOperations.IntersectShapeAreas;
    lengthRecord2.PathOperations = PathOperations.SubtractFrontShape;

    im.Save(outputFilePath);
}
```

### Δείτε επίσης

* class [LengthRecord](../)
* namespace [Aspose.PSD.FileFormats.Core.VectorPaths](../../../aspose.psd.fileformats.core.vectorpaths/)
* assembly [Aspose.PSD](../../../)


