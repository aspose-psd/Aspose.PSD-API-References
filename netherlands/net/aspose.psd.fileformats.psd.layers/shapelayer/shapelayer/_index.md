---
title: "ShapeLayer.ShapeLayer"
second_title: "Aspose.PSD voor .NET API-referentie"
description: "ShapeLayer constructor. Initialiseert een nieuw exemplaar van de ShapeLayer‑klasse. Alle bronnen worden in hun standaardstatus aangemaakt"
type: docs
weight: 10
url: /nl/net/aspose.psd.fileformats.psd.layers/shapelayer/shapelayer/
---
{{< psd/tize >}}
## ShapeLayer constructor

Initialiseert een nieuw exemplaar van de [`ShapeLayer`](../) klasse. Alle bronnen worden in hun standaardstatus aangemaakt.

```csharp
public ShapeLayer()
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

* class [ShapeLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


