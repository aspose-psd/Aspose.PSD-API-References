---
title: "ShapeLayer.CreateInstance"
second_title: "Aspose.PSD för .NET API‑referens"
description: "ShapeLayer-metod. Skapar en ny instans av ShapeLayer-klassen."
type: docs
weight: 20
url: /sv/net/aspose.psd.fileformats.psd.layers/shapelayer/createinstance/
---
{{< psd/tize >}}
## ShapeLayer.CreateInstance method

Skapar en ny instans av [`ShapeLayer`](../)-klassen.

```csharp
public static ShapeLayer CreateInstance()
```

### Returvärde

Returnerar den nya instansen av [`ShapeLayer`](../)-klassen.

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


