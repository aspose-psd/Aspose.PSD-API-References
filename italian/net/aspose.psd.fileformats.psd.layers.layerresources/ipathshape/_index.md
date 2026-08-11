---
title: "Interfaccia IPathShape"
second_title: "Riferimento API Aspose.PSD per .NET"
description: "Interfaccia Aspose.PSD.FileFormats.Psd.Layers.LayerResources.IPathShape. La forma dai nodi della curva di Bézier"
type: docs
weight: 2810
url: /it/net/aspose.psd.fileformats.psd.layers.layerresources/ipathshape/
---
{{< psd/tize >}}
## IPathShape interface

La forma dai nodi della curva di Bézier.

```csharp
public interface IPathShape
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [IsClosed](../../aspose.psd.fileformats.psd.layers.layerresources/ipathshape/isclosed/) { get; set; } | Ottiene o imposta la proprietà che determina se la forma è chiusa. |
| [PathOperations](../../aspose.psd.fileformats.psd.layers.layerresources/ipathshape/pathoperations/) { get; set; } | Le operazioni per la combinazione delle forme di percorso (operazioni booleane). |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [GetItems](../../aspose.psd.fileformats.psd.layers.layerresources/ipathshape/getitems/)() | Ottiene l'array dei nodi Bézier. |
| [SetItems](../../aspose.psd.fileformats.psd.layers.layerresources/ipathshape/setitems/)(BezierKnotRecord[]) | Assegna un array di nodi Bexier. |

## Esempi

Il codice seguente dimostra gli oggetti percorso dalle risorse vsms o vmsk per ShapeLayer.

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

    // Rimuovi una forma
    shapes.RemoveAt(1);

    // Salva i dati modificati nella risorsa
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

// Verifica i valori modificati nel file salvato
using (PsdImage image = (PsdImage)Image.Load(
    outFile,
    new PsdLoadOptions { LoadEffectsResource = true }))
{
    Layer shapeLayer = image.Layers[1];
    VectorPathDataResource vectorPathDataResource = (VectorPathDataResource)shapeLayer.Resources[1];

    bool isFillStartsWithAllPixels;
    List<IPathShape> shapes = GetShapesFromResource(vectorPathDataResource, out isFillStartsWithAllPixels);

    // Il file salvato dovrebbe contenere 1 forma
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

### Vedi anche

* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


