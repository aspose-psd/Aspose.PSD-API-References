---
title: LengthRecord.ShapeIndex
second_title: Aspose.PSD για Αναφορά API .NET
description: LengthRecord ιδιοκτησία. Λαμβάνει ή ορίζει το δείκτη του τρέχοντος σχήματος διαδρομής σε επίπεδο.
type: docs
weight: 70
url: /el/net/aspose.psd.fileformats.core.vectorpaths/lengthrecord/shapeindex/
---
## LengthRecord.ShapeIndex property

Λαμβάνει ή ορίζει το δείκτη του τρέχοντος σχήματος διαδρομής σε επίπεδο.

```csharp
public ushort ShapeIndex { get; set; }
```

### Παραδείγματα

Το ακόλουθο παράδειγμα κώδικα δείχνει την υποστήριξη νέων ιδιοτήτων LengthRecord, PathOperations (λειτουργίες boolean), ShapeIndex και BezierKnotRecordsCount.

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

    // Εδώ αλλάζουμε τον τρόπο για το συνδυασμό μεταξύ σχημάτων.
    lengthRecord0.PathOperations = PathOperations.ExcludeOverlappingShapes;
    lengthRecord1.PathOperations = PathOperations.IntersectShapeAreas;
    lengthRecord2.PathOperations = PathOperations.SubtractFrontShape;

    im.Save(outputFilePath);
}
```

### Δείτε επίσης

* class [LengthRecord](../)
* χώρος ονομάτων [Aspose.PSD.FileFormats.Core.VectorPaths](../../lengthrecord/)
* συνέλευση [Aspose.PSD](../../../)


