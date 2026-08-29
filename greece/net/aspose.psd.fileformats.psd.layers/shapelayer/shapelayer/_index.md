---
title: "ShapeLayer.ShapeLayer"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Κατασκευαστής ShapeLayer. Αρχικοποιεί ένα νέο αντικείμενο της κλάσης ShapeLayer. Όλοι οι πόροι δημιουργούνται στην προεπιλεγμένη κατάσταση"
type: docs
weight: 10
url: /el/net/aspose.psd.fileformats.psd.layers/shapelayer/shapelayer/
---
{{< psd/tize >}}
## ShapeLayer constructor

Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [`ShapeLayer`](../). Όλοι οι πόροι δημιουργούνται στην προεπιλεγμένη κατάσταση.

```csharp
public ShapeLayer()
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


