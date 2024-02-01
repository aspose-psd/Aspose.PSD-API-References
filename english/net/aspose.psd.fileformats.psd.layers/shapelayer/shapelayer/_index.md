---
title: ShapeLayer.ShapeLayer
second_title: Aspose.PSD for .NET API Reference
description: ShapeLayer constructor. Initializes a new instance of the ShapeLayer class. All resources are created in their default state
type: docs
weight: 10
url: /net/aspose.psd.fileformats.psd.layers/shapelayer/shapelayer/
---
{{< psd/tize >}}
## ShapeLayer constructor

Initializes a new instance of the [`ShapeLayer`](../) class. All resources are created in their default state.

```csharp
public ShapeLayer()
```

## Examples

The following code shows support for the ShapeLayer layer.

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

    // Source file contains 2 figures. Remove the seconds one.
    pathShapesDest.RemoveAt(1);

    layerPath.SetItems(pathShapesDest.ToArray());

    shapeLayer.Update();

    image.Save(outFile);
}
```

### See Also

* class [ShapeLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


