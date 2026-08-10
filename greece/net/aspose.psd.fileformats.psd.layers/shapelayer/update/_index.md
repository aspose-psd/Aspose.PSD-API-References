---
title: "ShapeLayer.Update"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Μέθοδος ShapeLayer. Ενημερώνει τους πόρους από τις ιδιότητες του στρώματος σχήματος"
type: docs
weight: 60
url: /el/net/aspose.psd.fileformats.psd.layers/shapelayer/update/
---
{{< psd/tize >}}
## ShapeLayer.Update method

Ενημερώνει τους πόρους από τις ιδιότητες του στρώματος Shape.

```csharp
public void Update()
```

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει την υποστήριξη για το στρώμα ShapeLayer.

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

    // Το αρχείο πηγής περιέχει 2 σχήματα. Αφαιρέστε το δεύτερο.
    pathShapesDest.RemoveAt(1);

    layerPath.SetItems(pathShapesDest.ToArray());

    shapeLayer.Update();

    image.Save(outFile);
}
```

### Δείτε επίσης

* class [ShapeLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


