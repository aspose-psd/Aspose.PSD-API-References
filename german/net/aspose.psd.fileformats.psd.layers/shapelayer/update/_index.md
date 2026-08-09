---
title: "ShapeLayer.Update"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "ShapeLayer-Methode. Aktualisiert Ressourcen aus den Eigenschaften der Shape-Ebene."
type: docs
weight: 60
url: /de/net/aspose.psd.fileformats.psd.layers/shapelayer/update/
---
{{< psd/tize >}}
## ShapeLayer.Update method

Aktualisiert Ressourcen aus den Eigenschaften der Shape-Ebene.

```csharp
public void Update()
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

* class [ShapeLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


