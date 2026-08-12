---
title: "ShapeLayer.ShapeLayer"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Constructor ShapeLayer. Inicializa una nueva instancia de la clase ShapeLayer. Todos los recursos se crean en su estado predeterminado"
type: docs
weight: 10
url: /es/net/aspose.psd.fileformats.psd.layers/shapelayer/shapelayer/
---
{{< psd/tize >}}
## ShapeLayer constructor

Inicializa una nueva instancia de la clase [`ShapeLayer`](../). Todos los recursos se crean en su estado predeterminado.

```csharp
public ShapeLayer()
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

* class [ShapeLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


