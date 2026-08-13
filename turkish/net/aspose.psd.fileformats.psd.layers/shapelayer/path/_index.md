---
title: "ShapeLayer.Path"
second_title: "Aspose.PSD for .NET API Referansı"
description: "ShapeLayer özelliği. Bir Shape katmanında bulunan Path kümesini alır."
type: docs
weight: 40
url: /tr/net/aspose.psd.fileformats.psd.layers/shapelayer/path/
---
{{< psd/tize >}}
## ShapeLayer.Path property

Bir Shape katmanında bulunan Path'lerin kümesini alır.

```csharp
public IPath Path { get; }
```

## Örnekler

Aşağıdaki kod, ShapeLayer katmanı desteğini gösterir.

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

    // Kaynak dosya 2 şekil içeriyor. İkinci olanı kaldır.
    pathShapesDest.RemoveAt(1);

    layerPath.SetItems(pathShapesDest.ToArray());

    shapeLayer.Update();

    image.Save(outFile);
}
```

### Ayrıca Bakınız

* interface [IPath](../../../aspose.psd.fileformats.psd.layers.layerresources/ipath/)
* class [ShapeLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


