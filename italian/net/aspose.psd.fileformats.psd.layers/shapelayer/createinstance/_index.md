---
title: "ShapeLayer.CreateInstance"
second_title: "Riferimento API Aspose.PSD per .NET"
description: "Metodo ShapeLayer. Crea una nuova istanza della classe ShapeLayer"
type: docs
weight: 20
url: /it/net/aspose.psd.fileformats.psd.layers/shapelayer/createinstance/
---
{{< psd/tize >}}
## ShapeLayer.CreateInstance method

Crea una nuova istanza della classe [`ShapeLayer`](../).

```csharp
public static ShapeLayer CreateInstance()
```

### Valore di ritorno

Restituisce la nuova istanza della classe [`ShapeLayer`](../).

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


