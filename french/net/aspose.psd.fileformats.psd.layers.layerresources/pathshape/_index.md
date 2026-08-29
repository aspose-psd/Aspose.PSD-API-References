---
title: "Classe PathShape"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Classe Aspose.PSD.FileFormats.Psd.Layers.LayerResources.PathShape. La figure à partir des nœuds de la courbe de Bézier"
type: docs
weight: 3210
url: /fr/net/aspose.psd.fileformats.psd.layers.layerresources/pathshape/
---
{{< psd/tize >}}
## PathShape class

La figure des nœuds de la courbe de Bézier.

```csharp
public class PathShape : IPathShape
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [PathShape](pathshape/#constructor)() | Initialise une nouvelle instance de la classe `PathShape`. |
| [PathShape](pathshape/#constructor_1)(LengthRecord, BezierKnotRecord[]) | Initialise une nouvelle instance de la classe `PathShape`. |

## Propriétés

| Nom | Description |
| --- | --- |
| [IsClosed](../../aspose.psd.fileformats.psd.layers.layerresources/pathshape/isclosed/) { get; set; } | Obtient ou définit une valeur indiquant si cette instance est fermée. |
| [PathOperations](../../aspose.psd.fileformats.psd.layers.layerresources/pathshape/pathoperations/) { get; set; } | Obtient ou définit les opérations de chemin (opérations booléennes). |
| [ShapeIndex](../../aspose.psd.fileformats.psd.layers.layerresources/pathshape/shapeindex/) { get; set; } | Obtient ou définit l'index de la forme de chemin actuelle dans le calque. |

## Méthodes

| Nom | Description |
| --- | --- |
| [GetItems](../../aspose.psd.fileformats.psd.layers.layerresources/pathshape/getitems/)() | Obtient le tableau des nœuds de Bézier. |
| [SetItems](../../aspose.psd.fileformats.psd.layers.layerresources/pathshape/setitems/)(BezierKnotRecord[]) | Assigne le tableau des nœuds de Bézier. |
| [ToVectorPathRecords](../../aspose.psd.fileformats.psd.layers.layerresources/pathshape/tovectorpathrecords/)() | Crée les enregistrements [`VectorPathRecord`](../../aspose.psd.fileformats.core.vectorpaths/vectorpathrecord/) basés sur cette instance. |

## Exemples

Le code suivant montre les objets de chemin provenant des ressources vsms ou vmsk pour ShapeLayer.

```csharp
[C#]

string srcFile = "ShapeLayerTest.psd";
string outFile = "ShapeLayerTest-out.psd";

using (PsdImage image = (PsdImage)Image.Load(
    srcFile,
    new PsdLoadOptions { LoadEffectsResource = true }))
{
    Layer shapeLayer = image.Layers[1];
    VectorPathDataResource vectorPathDataResource = (VectorPathDataResource)shapeLayer.Resources[1];

    bool isFillStartsWithAllPixels;
    List<IPathShape> shapes = GetShapesFromResource(vectorPathDataResource, out isFillStartsWithAllPixels);

    // Supprimer une forme
    shapes.RemoveAt(1);

    // Enregistrer les données modifiées dans la ressource
    List<VectorPathRecord> path = new List<VectorPathRecord>();
    path.Add(new PathFillRuleRecord(null));
    path.Add(new InitialFillRuleRecord(isFillStartsWithAllPixels));

    for (ushort i = 0; i < shapes.Count; i++)
    {
        PathShape shape = (PathShape)shapes[i];
        shape.ShapeIndex = i;
        path.AddRange(shape.ToVectorPathRecords());
    }

    vectorPathDataResource.Paths = path.ToArray();

    image.Save(outFile);
}

// Vérifier les valeurs modifiées dans le fichier enregistré
using (PsdImage image = (PsdImage)Image.Load(
    outFile,
    new PsdLoadOptions { LoadEffectsResource = true }))
{
    Layer shapeLayer = image.Layers[1];
    VectorPathDataResource vectorPathDataResource = (VectorPathDataResource)shapeLayer.Resources[1];

    bool isFillStartsWithAllPixels;
    List<IPathShape> shapes = GetShapesFromResource(vectorPathDataResource, out isFillStartsWithAllPixels);

    // Le fichier enregistré doit contenir 1 forme
    AssertAreEqual(1, shapes.Count);
}

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception(message ?? "Objects are not equal.");
    }
}

List<IPathShape> GetShapesFromResource(
    VectorPathDataResource vectorPathDataResource,
    out bool isFillStartsWithAllPixels)
{
    List<IPathShape> shapes = new List<IPathShape>();
    LengthRecord lengthRecord = null;
    isFillStartsWithAllPixels = false;
    List<BezierKnotRecord> bezierKnotRecords = new List<BezierKnotRecord>();

    foreach (var pathRecord in vectorPathDataResource.Paths)
    {
        if (pathRecord is LengthRecord)
        {
            if (bezierKnotRecords.Count > 0)
            {
                shapes.Add(new PathShape(lengthRecord, bezierKnotRecords.ToArray()));
                lengthRecord = null;
                bezierKnotRecords.Clear();
            }

            lengthRecord = (LengthRecord)pathRecord;
        }
        else if (pathRecord is BezierKnotRecord)
        {
            bezierKnotRecords.Add((BezierKnotRecord)pathRecord);
        }
        else if (pathRecord is InitialFillRuleRecord)
        {
            InitialFillRuleRecord initialFillRuleRecord = (InitialFillRuleRecord)pathRecord;
            isFillStartsWithAllPixels = initialFillRuleRecord.IsFillStartsWithAllPixels;
        }
    }

    if (bezierKnotRecords.Count > 0)
    {
        shapes.Add(new PathShape(lengthRecord, bezierKnotRecords.ToArray()));
        lengthRecord = null;
        bezierKnotRecords.Clear();
    }

    return shapes;
}
```

### Voir aussi

* interface [IPathShape](../ipathshape/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


