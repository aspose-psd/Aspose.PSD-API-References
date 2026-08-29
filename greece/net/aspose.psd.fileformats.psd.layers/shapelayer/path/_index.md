---
title: "ShapeLayer.Path"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Ιδιότητα ShapeLayer. Λαμβάνει το σύνολο των διαδρομών που εμφανίζονται σε ένα στρώμα σχήματος"
type: docs
weight: 40
url: /el/net/aspose.psd.fileformats.psd.layers/shapelayer/path/
---
{{< psd/tize >}}
## ShapeLayer.Path property

Λαμβάνει το σύνολο των Διαδρομών που εμφανίζονται σε ένα στρώμα Shape.

```csharp
public IPath Path { get; }
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

* interface [IPath](../../../aspose.psd.fileformats.psd.layers.layerresources/ipath/)
* class [ShapeLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


