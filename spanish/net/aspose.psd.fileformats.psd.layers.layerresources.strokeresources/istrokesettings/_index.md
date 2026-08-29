---
title: "Interfaz IStrokeSettings"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources.IStrokeSettings interface. Configuración de trazo de formas"
type: docs
weight: 3390
url: /es/net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/istrokesettings/
---
{{< psd/tize >}}
## IStrokeSettings interface

Configuración de trazo de formas.

```csharp
public interface IStrokeSettings
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Enabled](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/istrokesettings/enabled/) { get; set; } | El trazo está habilitado. |
| [Fill](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/istrokesettings/fill/) { get; set; } | Obtiene o establece la configuración de relleno del trazo. |
| [LineAlignment](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/istrokesettings/linealignment/) { get; set; } | Obtiene o establece la alineación de línea del estilo de trazo. |
| [LineCap](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/istrokesettings/linecap/) { get; set; } | Tipo de extremo de línea del trazo. |
| [LineDashSet](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/istrokesettings/linedashset/) { get; set; } | Obtiene o establece la matriz de guiones de línea. |
| [LineJoin](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/istrokesettings/linejoin/) { get; set; } | Tipo de unión de línea del trazo. |
| [Size](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/istrokesettings/size/) { get; set; } | Ancho de línea del trazo. |

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

* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/)
* assembly [Aspose.PSD](../../)


