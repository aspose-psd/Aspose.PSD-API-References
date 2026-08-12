---
title: "ShapeLayer.ShapeLayer"
second_title: "Aspose.PSD för .NET API‑referens"
description: "ShapeLayer konstruktor. Initierar en ny instans av ShapeLayer-klassen. Alla resurser skapas i deras standardläge."
type: docs
weight: 10
url: /sv/net/aspose.psd.fileformats.psd.layers/shapelayer/shapelayer/
---
{{< psd/tize >}}
## ShapeLayer constructor

Initierar en ny instans av [`ShapeLayer`](../)-klassen. Alla resurser skapas i deras standardläge.

```csharp
public ShapeLayer()
```

## Exempel

Följande kod visar stöd för ShapeLayer-lagret.

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

    // Källfilen innehåller 2 figurer. Ta bort den andra.
    pathShapesDest.RemoveAt(1);

    layerPath.SetItems(pathShapesDest.ToArray());

    shapeLayer.Update();

    image.Save(outFile);
}
```

### Se även

* class [ShapeLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


