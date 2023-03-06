---
title: LengthRecord.LengthRecord
second_title: Aspose.PSD för .NET API-referens
description: LengthRecord byggare. Initierar en ny instans avLengthRecord class.
type: docs
weight: 10
url: /sv/net/aspose.psd.fileformats.core.vectorpaths/lengthrecord/lengthrecord/
---
## LengthRecord(byte[]) {#constructor_1}

Initierar en ny instans av[`LengthRecord`](../) class.

```csharp
public LengthRecord(byte[] data)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | Byte[] | Rekorddata. |

### Undantag

| undantag | skick |
| --- | --- |
| !:PsdImageArgumentException | Felaktiga data för att skapa LengthRecord |

### Se även

* class [LengthRecord](../)
* namnutrymme [Aspose.PSD.FileFormats.Core.VectorPaths](../../lengthrecord/)
* hopsättning [Aspose.PSD](../../../)

---

## LengthRecord() {#constructor}

Initierar en ny instans av[`LengthRecord`](../) class.

```csharp
public LengthRecord()
```

### Exempel

Följande kodexempel visar stöd för nya LengthRecord-egenskaper, PathOperations (booleska operationer), ShapeIndex och BezierKnotRecordsCount.

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

    // Här ändrar vi sättet att kombinera mellan former.
    lengthRecord0.PathOperations = PathOperations.ExcludeOverlappingShapes;
    lengthRecord1.PathOperations = PathOperations.IntersectShapeAreas;
    lengthRecord2.PathOperations = PathOperations.SubtractFrontShape;

    im.Save(outputFilePath);
}
```

### Se även

* class [LengthRecord](../)
* namnutrymme [Aspose.PSD.FileFormats.Core.VectorPaths](../../lengthrecord/)
* hopsättning [Aspose.PSD](../../../)


