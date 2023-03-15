---
title: LengthRecord.LengthRecord
second_title: Référence de l'API Aspose.PSD pour .NET
description: LengthRecord constructeur. Initialise une nouvelle instance duLengthRecord classe.
type: docs
weight: 10
url: /fr/net/aspose.psd.fileformats.core.vectorpaths/lengthrecord/lengthrecord/
---
## LengthRecord(byte[]) {#constructor_1}

Initialise une nouvelle instance du[`LengthRecord`](../) classe.

```csharp
public LengthRecord(byte[] data)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| data | Byte[] | Les données d'enregistrement. |

### Exceptions

| exception | condition |
| --- | --- |
| !:PsdImageArgumentException | Données incorrectes pour la création de LengthRecord |

### Voir également

* class [LengthRecord](../)
* espace de noms [Aspose.PSD.FileFormats.Core.VectorPaths](../../lengthrecord/)
* Assemblée [Aspose.PSD](../../../)

---

## LengthRecord() {#constructor}

Initialise une nouvelle instance du[`LengthRecord`](../) classe.

```csharp
public LengthRecord()
```

### Exemples

L'exemple de code suivant illustre la prise en charge des nouvelles propriétés LengthRecord, PathOperations (opérations booléennes), ShapeIndex et BezierKnotRecordsCount.

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

    // Ici, nous changeons la façon de combiner entre les formes.
    lengthRecord0.PathOperations = PathOperations.ExcludeOverlappingShapes;
    lengthRecord1.PathOperations = PathOperations.IntersectShapeAreas;
    lengthRecord2.PathOperations = PathOperations.SubtractFrontShape;

    im.Save(outputFilePath);
}
```

### Voir également

* class [LengthRecord](../)
* espace de noms [Aspose.PSD.FileFormats.Core.VectorPaths](../../lengthrecord/)
* Assemblée [Aspose.PSD](../../../)


