---
title: "Απαρίθμηση PathOperations"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Aspose.PSD.FileFormats.Core.VectorPaths.PathOperations απαρίθμηση. Οι λειτουργίες για τα σχήματα διαδρομής που συνδυάζουν Boolean λειτουργίες"
type: docs
weight: 1400
url: /el/net/aspose.psd.fileformats.core.vectorpaths/pathoperations/
---
{{< psd/tize >}}
## PathOperations enumeration

Οι λειτουργίες για τον συνδυασμό των σχημάτων διαδρομής (Boolean operations).

```csharp
public enum PathOperations
```

### Τιμές

| Όνομα | Τιμή | Περιγραφή |
| --- | --- | --- |
| ExcludeOverlappingShapes | `0` | Εξαίρεση επικαλυπτόμενων σχημάτων (λειτουργία XOR). |
| CombineShapes | `1` | Συνδυάστε σχήματα (λειτουργία OR). Αυτή είναι η προεπιλεγμένη τιμή στο Photoshop. |
| SubtractFrontShape | `2` | Αφαίρεση μπροστινού σχήματος (λειτουργία NOT). |
| IntersectShapeAreas | `3` | Διατομή περιοχών σχήματος (λειτουργία AND). |

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

* namespace [Aspose.PSD.FileFormats.Core.VectorPaths](../../aspose.psd.fileformats.core.vectorpaths/)
* assembly [Aspose.PSD](../../)


