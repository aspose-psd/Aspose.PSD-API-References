---
title: "Interfaz IPath"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Interfaz Aspose.PSD.FileFormats.Psd.Layers.LayerResources.IPath. La interfaz describe el conjunto de rutas que están presentes en una capa de forma"
type: docs
weight: 2800
url: /es/net/aspose.psd.fileformats.psd.layers.layerresources/ipath/
---
{{< psd/tize >}}
## IPath interface

La interfaz describe el conjunto de Paths que están presentes en una capa Shape.

```csharp
public interface IPath
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [IsDisabled](../../aspose.psd.fileformats.psd.layers.layerresources/ipath/isdisabled/) { get; set; } | La ruta está deshabilitada. |
| [IsInverted](../../aspose.psd.fileformats.psd.layers.layerresources/ipath/isinverted/) { get; set; } | La ruta está invertida. |
| [IsNotLinked](../../aspose.psd.fileformats.psd.layers.layerresources/ipath/isnotlinked/) { get; set; } | La ruta no está vinculada. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [GetItems](../../aspose.psd.fileformats.psd.layers.layerresources/ipath/getitems/)() | Obtiene el arreglo de Shapes en una Path. |
| [SetItems](../../aspose.psd.fileformats.psd.layers.layerresources/ipath/setitems/)(IPathShape[]) | Establece el arreglo de Shapes en una Path. |

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

* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


