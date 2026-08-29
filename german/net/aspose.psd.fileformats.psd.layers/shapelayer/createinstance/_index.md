---
title: "ShapeLayer.CreateInstance"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "ShapeLayer-Methode. Erstellt eine neue Instanz der ShapeLayer-Klasse."
type: docs
weight: 20
url: /de/net/aspose.psd.fileformats.psd.layers/shapelayer/createinstance/
---
{{< psd/tize >}}
## ShapeLayer.CreateInstance method

Erstellt eine neue Instanz der [`ShapeLayer`](../)-Klasse.

```csharp
public static ShapeLayer CreateInstance()
```

### Rückgabewert

Gibt die neue Instanz der [`ShapeLayer`](../)-Klasse zurück.

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

* class [ShapeLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


