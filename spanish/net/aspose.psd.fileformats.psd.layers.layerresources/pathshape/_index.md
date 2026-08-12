---
title: "Clase PathShape"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Clase Aspose.PSD.FileFormats.Psd.Layers.LayerResources.PathShape. La figura de los nudos de la curva Bézier"
type: docs
weight: 3210
url: /es/net/aspose.psd.fileformats.psd.layers.layerresources/pathshape/
---
{{< psd/tize >}}
## PathShape class

La figura de los nudos de la curva Bézier.

```csharp
public class PathShape : IPathShape
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [PathShape](pathshape/#constructor)() | Inicializa una nueva instancia de la clase `PathShape`. |
| [PathShape](pathshape/#constructor_1)(LengthRecord, BezierKnotRecord[]) | Inicializa una nueva instancia de la clase `PathShape`. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [IsClosed](../../aspose.psd.fileformats.psd.layers.layerresources/pathshape/isclosed/) { get; set; } | Obtiene o establece un valor que indica si esta instancia está cerrada. |
| [PathOperations](../../aspose.psd.fileformats.psd.layers.layerresources/pathshape/pathoperations/) { get; set; } | Obtiene o establece las operaciones de ruta (operaciones booleanas). |
| [ShapeIndex](../../aspose.psd.fileformats.psd.layers.layerresources/pathshape/shapeindex/) { get; set; } | Obtiene o establece el índice de la forma de ruta actual en la capa. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [GetItems](../../aspose.psd.fileformats.psd.layers.layerresources/pathshape/getitems/)() | Obtiene una matriz de nudos Bézier. |
| [SetItems](../../aspose.psd.fileformats.psd.layers.layerresources/pathshape/setitems/)(BezierKnotRecord[]) | Asigna una matriz de nudos Bézier. |
| [ToVectorPathRecords](../../aspose.psd.fileformats.psd.layers.layerresources/pathshape/tovectorpathrecords/)() | Crea los registros [`VectorPathRecord`](../../aspose.psd.fileformats.core.vectorpaths/vectorpathrecord/) basados en esta instancia. |

## Ejemplos

El siguiente código demuestra objetos de ruta de los recursos vsms o vmsk para ShapeLayer.

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

    // Eliminar una forma
    shapes.RemoveAt(1);

    // Guardar datos modificados en el recurso
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

// Verificar los valores modificados en el archivo guardado
using (PsdImage image = (PsdImage)Image.Load(
    outFile,
    new PsdLoadOptions { LoadEffectsResource = true }))
{
    Layer shapeLayer = image.Layers[1];
    VectorPathDataResource vectorPathDataResource = (VectorPathDataResource)shapeLayer.Resources[1];

    bool isFillStartsWithAllPixels;
    List<IPathShape> shapes = GetShapesFromResource(vectorPathDataResource, out isFillStartsWithAllPixels);

    // El archivo guardado debe tener 1 forma
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

### Ver también

* interface [IPathShape](../ipathshape/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


