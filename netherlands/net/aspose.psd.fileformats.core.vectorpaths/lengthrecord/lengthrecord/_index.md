---
title: LengthRecord.LengthRecord
second_title: Aspose.PSD voor .NET API-referentie
description: LengthRecord constructeur. Initialiseert een nieuw exemplaar van hetLengthRecord klasse.
type: docs
weight: 10
url: /nl/net/aspose.psd.fileformats.core.vectorpaths/lengthrecord/lengthrecord/
---
## LengthRecord(byte[]) {#constructor_1}

Initialiseert een nieuw exemplaar van het[`LengthRecord`](../) klasse.

```csharp
public LengthRecord(byte[] data)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| data | Byte[] | De recordgegevens. |

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| !:PsdImageArgumentException | Onjuiste gegevens voor het maken van LengthRecord |

### Zie ook

* class [LengthRecord](../)
* naamruimte [Aspose.PSD.FileFormats.Core.VectorPaths](../../lengthrecord/)
* montage [Aspose.PSD](../../../)

---

## LengthRecord() {#constructor}

Initialiseert een nieuw exemplaar van het[`LengthRecord`](../) klasse.

```csharp
public LengthRecord()
```

### Voorbeelden

Het volgende codevoorbeeld demonstreert de ondersteuning van nieuwe LengthRecord-eigenschappen, PathOperations (booleaanse bewerkingen), ShapeIndex en BezierKnotRecordsCount.

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

    // Hier veranderen we de manier van combineren tussen vormen.
    lengthRecord0.PathOperations = PathOperations.ExcludeOverlappingShapes;
    lengthRecord1.PathOperations = PathOperations.IntersectShapeAreas;
    lengthRecord2.PathOperations = PathOperations.SubtractFrontShape;

    im.Save(outputFilePath);
}
```

### Zie ook

* class [LengthRecord](../)
* naamruimte [Aspose.PSD.FileFormats.Core.VectorPaths](../../lengthrecord/)
* montage [Aspose.PSD](../../../)


