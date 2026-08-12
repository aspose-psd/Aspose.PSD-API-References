---
title: "ShapeLayer.Path"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Propiedad ShapeLayer. Obtiene el conjunto de rutas que están presentes en una capa Shape"
type: docs
weight: 40
url: /es/net/aspose.psd.fileformats.psd.layers/shapelayer/path/
---
{{< psd/tize >}}
## ShapeLayer.Path property

Obtiene el conjunto de Paths que están presentes en una capa Shape.

```csharp
public IPath Path { get; }
```

## Ejemplos

El siguiente código muestra el soporte para la capa ShapeLayer.

```csharp
[C#]

string srcFile = "ShapeLayerTest.psd";
string outFile = "ShapeLayerTest-out.psd";

using (PsdImage image = (PsdImage)Image.Load(srcFile, new PsdLoadOptions { LoadEffectsResource = true }))
{
    ShapeLayer shapeLayer = (ShapeLayer)image.Layers[1];
    IPath layerPath = shapeLayer.Path;

    IPathShape[] pathShapeSource = layerPath.GetItems();
    List<IPathShape> pathShapesDest = new List<IPathShape>(pathShapeSource);

    // El archivo fuente contiene 2 figuras. Elimina la segunda.
    pathShapesDest.RemoveAt(1);

    layerPath.SetItems(pathShapesDest.ToArray());

    shapeLayer.Update();

    image.Save(outFile);
}
```

### Ver también

* interface [IPath](../../../aspose.psd.fileformats.psd.layers.layerresources/ipath/)
* class [ShapeLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


