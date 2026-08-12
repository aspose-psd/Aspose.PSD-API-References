---
title: "ShapeLayer.Path"
second_title: "Aspose.PSD voor .NET API-referentie"
description: "ShapeLayer eigenschap. Haalt de verzameling paden op die aanwezig zijn in een Shape‑laag"
type: docs
weight: 40
url: /nl/net/aspose.psd.fileformats.psd.layers/shapelayer/path/
---
{{< psd/tize >}}
## ShapeLayer.Path property

Haalt de verzameling paden op die aanwezig zijn in een vormlaag.

```csharp
public IPath Path { get; }
```

## Voorbeelden

De volgende code toont ondersteuning voor de ShapeLayer-laag.

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

    // Bronbestand bevat 2 figuren. Verwijder de tweede.
    pathShapesDest.RemoveAt(1);

    layerPath.SetItems(pathShapesDest.ToArray());

    shapeLayer.Update();

    image.Save(outFile);
}
```

### Zie ook

* interface [IPath](../../../aspose.psd.fileformats.psd.layers.layerresources/ipath/)
* class [ShapeLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


