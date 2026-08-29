---
title: "ShapeLayer.Path"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "ShapeLayer-Eigenschaft. Gibt die Menge der Pfade zurück, die in einer Shape-Ebene vorhanden sind."
type: docs
weight: 40
url: /de/net/aspose.psd.fileformats.psd.layers/shapelayer/path/
---
{{< psd/tize >}}
## ShapeLayer.Path property

Ruft die Menge der Pfade ab, die in einem Shape layer vorhanden sind.

```csharp
public IPath Path { get; }
```

## Beispiele

Der folgende Code zeigt die Unterstützung für die ShapeLayer-Ebene.

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

    // Die Quelldatei enthält 2 Figuren. Entfernen Sie die zweite.
    pathShapesDest.RemoveAt(1);

    layerPath.SetItems(pathShapesDest.ToArray());

    shapeLayer.Update();

    image.Save(outFile);
}
```

### Siehe auch

* interface [IPath](../../../aspose.psd.fileformats.psd.layers.layerresources/ipath/)
* class [ShapeLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


