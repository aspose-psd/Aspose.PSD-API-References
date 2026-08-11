---
title: "ShapeLayer.ShapeLayer"
second_title: "Riferimento API Aspose.PSD per .NET"
description: "Costruttore ShapeLayer. Inizializza una nuova istanza della classe ShapeLayer. Tutte le risorse sono create nello stato predefinito"
type: docs
weight: 10
url: /it/net/aspose.psd.fileformats.psd.layers/shapelayer/shapelayer/
---
{{< psd/tize >}}
## ShapeLayer constructor

Inizializza una nuova istanza della classe [`ShapeLayer`](../). Tutte le risorse sono create nello stato predefinito.

```csharp
public ShapeLayer()
```

## Esempi

Il codice seguente mostra il supporto per il layer ShapeLayer.

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

    // Il file di origine contiene 2 figure. Rimuovi la seconda.
    pathShapesDest.RemoveAt(1);

    layerPath.SetItems(pathShapesDest.ToArray());

    shapeLayer.Update();

    image.Save(outFile);
}
```

### Vedi anche

* class [ShapeLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


