---
title: LengthRecord.LengthRecord
second_title: Aspose.PSD για Αναφορά API .NET
description: LengthRecord κατασκευαστής. Αρχικοποιεί μια νέα παρουσία τουLengthRecord τάξη.
type: docs
weight: 10
url: /el/net/aspose.psd.fileformats.core.vectorpaths/lengthrecord/lengthrecord/
---
## LengthRecord(byte[]) {#constructor_1}

Αρχικοποιεί μια νέα παρουσία του[`LengthRecord`](../) τάξη.

```csharp
public LengthRecord(byte[] data)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| data | Byte[] | Τα δεδομένα εγγραφής. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| !:PsdImageArgumentException | Εσφαλμένα δεδομένα για τη δημιουργία LengthRecord |

### Δείτε επίσης

* class [LengthRecord](../)
* χώρος ονομάτων [Aspose.PSD.FileFormats.Core.VectorPaths](../../lengthrecord/)
* συνέλευση [Aspose.PSD](../../../)

---

## LengthRecord() {#constructor}

Αρχικοποιεί μια νέα παρουσία του[`LengthRecord`](../) τάξη.

```csharp
public LengthRecord()
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


