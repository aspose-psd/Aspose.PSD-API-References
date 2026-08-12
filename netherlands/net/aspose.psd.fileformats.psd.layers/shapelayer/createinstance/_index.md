---
title: "ShapeLayer.CreateInstance"
second_title: "Aspose.PSD voor .NET API-referentie"
description: "ShapeLayer methode. Maakt een nieuw exemplaar van de ShapeLayer-klasse"
type: docs
weight: 20
url: /nl/net/aspose.psd.fileformats.psd.layers/shapelayer/createinstance/
---
{{< psd/tize >}}
## ShapeLayer.CreateInstance method

Maakt een nieuw exemplaar van de [`ShapeLayer`](../) klasse.

```csharp
public static ShapeLayer CreateInstance()
```

### Retourwaarde

Retourneert het nieuwe exemplaar van de [`ShapeLayer`](../) klasse.

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


