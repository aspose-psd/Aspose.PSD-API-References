---
title: "LengthRecord.LengthRecord"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "LengthRecord-Konstruktor. Initialisiert eine neue Instanz der LengthRecord-Klasse"
type: docs
weight: 10
url: /de/net/aspose.psd.fileformats.core.vectorpaths/lengthrecord/lengthrecord/
---
{{< psd/tize >}}
## LengthRecord(byte[]) {#constructor_1}

Initialisiert eine neue Instanz der [`LengthRecord`](../)-Klasse.

```csharp
public LengthRecord(byte[] data)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Daten | Byte[] | Die Datensatzdaten. |

### Siehe auch

* class [LengthRecord](../)
* namespace [Aspose.PSD.FileFormats.Core.VectorPaths](../../../aspose.psd.fileformats.core.vectorpaths/)
* assembly [Aspose.PSD](../../../)

---

## LengthRecord() {#constructor}

Initialisiert eine neue Instanz der [`LengthRecord`](../)-Klasse.

```csharp
public LengthRecord()
```

## Beispiele

Das folgende Codebeispiel demonstriert die Unterstützung neuer LengthRecord‑Eigenschaften, PathOperations (boolesche Operationen), ShapeIndex und BezierKnotRecordsCount.

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

    // Hier ändern wir die Art und Weise, Formen zu kombinieren.
    lengthRecord0.PathOperations = PathOperations.ExcludeOverlappingShapes;
    lengthRecord1.PathOperations = PathOperations.IntersectShapeAreas;
    lengthRecord2.PathOperations = PathOperations.SubtractFrontShape;

    im.Save(outputFilePath);
}
```

### Siehe auch

* class [LengthRecord](../)
* namespace [Aspose.PSD.FileFormats.Core.VectorPaths](../../../aspose.psd.fileformats.core.vectorpaths/)
* assembly [Aspose.PSD](../../../)


