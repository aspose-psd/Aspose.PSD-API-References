---
title: "Classe VectorPath"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Classe Aspose.PSD.FileFormats.Psd.Layers.LayerResources.VectorPath. La classe qui contient les chemins vectoriels"
type: docs
weight: 3730
url: /fr/net/aspose.psd.fileformats.psd.layers.layerresources/vectorpath/
---
{{< psd/tize >}}
## VectorPath class

La classe qui contient les chemins vectoriels.

```csharp
public class VectorPath : IPath
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [VectorPath](vectorpath/)() | Initialise une nouvelle instance de la classe `VectorPath`. |

## Propriétés

| Nom | Description |
| --- | --- |
| [IsDisabled](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpath/isdisabled/) { get; set; } | Obtient ou définit une valeur indiquant si cette instance est désactivée. |
| [IsFillStartsWithAllPixels](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpath/isfillstartswithallpixels/) { get; set; } | Obtient ou définit une valeur indiquant si le remplissage commence avec tous les pixels. |
| [IsInverted](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpath/isinverted/) { get; set; } | Obtient ou définit une valeur indiquant si cette instance est inversée. |
| [IsNotLinked](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpath/isnotlinked/) { get; set; } | Obtient ou définit une valeur indiquant si cette instance n'est pas liée. |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpath/version/) { get; set; } | Obtient ou définit la version. |

## Méthodes

| Nom | Description |
| --- | --- |
| [GetItems](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpath/getitems/)() | Obtient le tableau de formes dans un chemin. |
| [SetItems](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpath/setitems/)(IPathShape[]) | Définit le tableau de formes dans un chemin. |

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

* interface [IPath](../ipath/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


