---
title: Enum PathOperations
second_title: Aspose.PSD για Αναφορά API .NET
description: Aspose.PSD.FileFormats.Core.VectorPaths.PathOperations αρίθμηση. Οι πράξεις για τα σχήματα διαδρομής που συνδυάζονται πράξεις Boolean.
type: docs
weight: 1390
url: /el/net/aspose.psd.fileformats.core.vectorpaths/pathoperations/
---
## PathOperations enumeration

Οι πράξεις για τα σχήματα διαδρομής που συνδυάζονται (πράξεις Boolean).

```csharp
public enum PathOperations
```

### Αξίες

| Ονομα | αξία | Περιγραφή |
| --- | --- | --- |
| ExcludeOverlappingShapes | `0` | Εξαίρεση επικαλυπτόμενων σχημάτων (λειτουργία XOR). |
| CombineShapes | `1` | Συνδυάστε σχήματα (λειτουργία Ή). Αυτή είναι η προεπιλεγμένη τιμή στο Photoshop. |
| SubtractFrontShape | `2` | Αφαίρεση μπροστινού σχήματος (ΟΧΙ λειτουργία). |
| IntersectShapeAreas | `3` | Περιοχές τομής σχήματος (ΚΑΙ λειτουργία). |

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

* χώρος ονομάτων [Aspose.PSD.FileFormats.Core.VectorPaths](../../aspose.psd.fileformats.core.vectorpaths/)
* συνέλευση [Aspose.PSD](../../)


