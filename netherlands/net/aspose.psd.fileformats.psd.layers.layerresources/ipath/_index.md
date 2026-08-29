---
title: "Interface IPath"
second_title: "Aspose.PSD voor .NET API-referentie"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.IPath interface. Interface beschrijft de set paden die aanwezig zijn in een vormlaag"
type: docs
weight: 2800
url: /nl/net/aspose.psd.fileformats.psd.layers.layerresources/ipath/
---
{{< psd/tize >}}
## IPath interface

Interface beschrijft de set paden die aanwezig zijn in een vormlaag.

```csharp
public interface IPath
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [IsDisabled](../../aspose.psd.fileformats.psd.layers.layerresources/ipath/isdisabled/) { get; set; } | Is pad uitgeschakeld. |
| [IsInverted](../../aspose.psd.fileformats.psd.layers.layerresources/ipath/isinverted/) { get; set; } | Is pad omgekeerd. |
| [IsNotLinked](../../aspose.psd.fileformats.psd.layers.layerresources/ipath/isnotlinked/) { get; set; } | Is pad niet gekoppeld. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [GetItems](../../aspose.psd.fileformats.psd.layers.layerresources/ipath/getitems/)() | Haalt array van Vormen in een Pad op. |
| [SetItems](../../aspose.psd.fileformats.psd.layers.layerresources/ipath/setitems/)(IPathShape[]) | Stelt array van Vormen in een Pad in. |

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

* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


