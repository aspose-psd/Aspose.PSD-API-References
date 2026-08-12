---
title: "Klasse PathShape"
second_title: "Aspose.PSD voor .NET API-referentie"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.PathShape klasse. De figuur van de knopen van de Bézier-curve"
type: docs
weight: 3210
url: /nl/net/aspose.psd.fileformats.psd.layers.layerresources/pathshape/
---
{{< psd/tize >}}
## PathShape class

De figuur van de knopen van de Bézier-curve.

```csharp
public class PathShape : IPathShape
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [PathShape](pathshape/#constructor)() | Initialiseert een nieuw exemplaar van de `PathShape` klasse. |
| [PathShape](pathshape/#constructor_1)(LengthRecord, BezierKnotRecord[]) | Initialiseert een nieuw exemplaar van de `PathShape` klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [IsClosed](../../aspose.psd.fileformats.psd.layers.layerresources/pathshape/isclosed/) { get; set; } | Haalt op of stelt een waarde in die aangeeft of dit exemplaar gesloten is. |
| [PathOperations](../../aspose.psd.fileformats.psd.layers.layerresources/pathshape/pathoperations/) { get; set; } | Haalt op of stelt de padbewerkingen (Boolean-bewerkingen) in. |
| [ShapeIndex](../../aspose.psd.fileformats.psd.layers.layerresources/pathshape/shapeindex/) { get; set; } | Haalt op of stelt de index van de huidige padvorm in de laag in. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [GetItems](../../aspose.psd.fileformats.psd.layers.layerresources/pathshape/getitems/)() | Haalt array van Bézier-knopen op. |
| [SetItems](../../aspose.psd.fileformats.psd.layers.layerresources/pathshape/setitems/)(BezierKnotRecord[]) | Wijst array van Bézier-knopen toe. |
| [ToVectorPathRecords](../../aspose.psd.fileformats.psd.layers.layerresources/pathshape/tovectorpathrecords/)() | Maakt de [`VectorPathRecord`](../../aspose.psd.fileformats.core.vectorpaths/vectorpathrecord/) records aan op basis van dit exemplaar. |

## Voorbeelden

De volgende code demonstreert padobjecten van vsms- of vmsk-resources voor ShapeLayer.

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

    // Verwijder één vorm
    shapes.RemoveAt(1);

    // Sla gewijzigde gegevens op in resource
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

// Controleer gewijzigde waarden in opgeslagen bestand
using (PsdImage image = (PsdImage)Image.Load(
    outFile,
    new PsdLoadOptions { LoadEffectsResource = true }))
{
    Layer shapeLayer = image.Layers[1];
    VectorPathDataResource vectorPathDataResource = (VectorPathDataResource)shapeLayer.Resources[1];

    bool isFillStartsWithAllPixels;
    List<IPathShape> shapes = GetShapesFromResource(vectorPathDataResource, out isFillStartsWithAllPixels);

    // Opgeslagen bestand moet 1 vorm bevatten
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

### Zie ook

* interface [IPathShape](../ipathshape/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


