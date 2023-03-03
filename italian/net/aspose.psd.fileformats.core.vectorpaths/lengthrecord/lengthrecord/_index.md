---
title: LengthRecord.LengthRecord
second_title: Aspose.PSD per riferimento API .NET
description: LengthRecord costruttore. Inizializza una nuova istanza diLengthRecord classe.
type: docs
weight: 10
url: /it/net/aspose.psd.fileformats.core.vectorpaths/lengthrecord/lengthrecord/
---
## LengthRecord(byte[]) {#constructor_1}

Inizializza una nuova istanza di[`LengthRecord`](../) classe.

```csharp
public LengthRecord(byte[] data)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| data | Byte[] | I dati della registrazione. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| !:PsdImageArgumentException | Dati errati per la creazione di LengthRecord |

### Guarda anche

* class [LengthRecord](../)
* spazio dei nomi [Aspose.PSD.FileFormats.Core.VectorPaths](../../lengthrecord/)
* assemblea [Aspose.PSD](../../../)

---

## LengthRecord() {#constructor}

Inizializza una nuova istanza di[`LengthRecord`](../) classe.

```csharp
public LengthRecord()
```

### Esempi

L'esempio di codice seguente illustra il supporto delle nuove proprietà LengthRecord, PathOperations (operazioni booleane), ShapeIndex e BezierKnotRecordsCount.

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

    // Qui cambiamo il modo di combinare le forme.
    lengthRecord0.PathOperations = PathOperations.ExcludeOverlappingShapes;
    lengthRecord1.PathOperations = PathOperations.IntersectShapeAreas;
    lengthRecord2.PathOperations = PathOperations.SubtractFrontShape;

    im.Save(outputFilePath);
}
```

### Guarda anche

* class [LengthRecord](../)
* spazio dei nomi [Aspose.PSD.FileFormats.Core.VectorPaths](../../lengthrecord/)
* assemblea [Aspose.PSD](../../../)


