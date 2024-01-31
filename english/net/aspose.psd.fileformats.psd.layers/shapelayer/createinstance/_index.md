---
title: ShapeLayer.CreateInstance
second_title: Aspose.PSD for .NET API Reference
description: ShapeLayer method. Creates a new instance of the ShapeLayer class
type: docs
weight: 20
url: /net/aspose.psd.fileformats.psd.layers/shapelayer/createinstance/
---
{{< psd/tize >}}
## ShapeLayer.CreateInstance method

Creates a new instance of the [`ShapeLayer`](../) class.

```csharp
public static ShapeLayer CreateInstance()
```

### Return Value

Returns the new instance of the [`ShapeLayer`](../) class.

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


