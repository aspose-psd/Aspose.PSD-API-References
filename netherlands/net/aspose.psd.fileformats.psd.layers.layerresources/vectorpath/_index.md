---
title: "Klasse VectorPath"
second_title: "Aspose.PSD voor .NET API-referentie"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.VectorPath klasse. De klasse die vectorpaden bevat"
type: docs
weight: 3730
url: /nl/net/aspose.psd.fileformats.psd.layers.layerresources/vectorpath/
---
{{< psd/tize >}}
## VectorPath class

De klasse die vectorpaden bevat.

```csharp
public class VectorPath : IPath
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [VectorPath](vectorpath/)() | Initialiseert een nieuw exemplaar van de `VectorPath` klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [IsDisabled](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpath/isdisabled/) { get; set; } | Haalt op of stelt een waarde in die aangeeft of dit exemplaar uitgeschakeld is. |
| [IsFillStartsWithAllPixels](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpath/isfillstartswithallpixels/) { get; set; } | Haalt op of stelt een waarde in die aangeeft of de vulling begint met alle pixels. |
| [IsInverted](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpath/isinverted/) { get; set; } | Haalt op of stelt een waarde in die aangeeft of dit exemplaar omgekeerd is. |
| [IsNotLinked](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpath/isnotlinked/) { get; set; } | Haalt op of stelt een waarde in die aangeeft of dit exemplaar niet gekoppeld is. |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpath/version/) { get; set; } | Haalt op of stelt de versie in. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [GetItems](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpath/getitems/)() | Haalt array van Vormen in een Pad op. |
| [SetItems](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpath/setitems/)(IPathShape[]) | Stelt array van Vormen in een Pad in. |

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

* interface [IPath](../ipath/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


