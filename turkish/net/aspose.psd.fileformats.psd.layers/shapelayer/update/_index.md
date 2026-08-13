---
title: "ShapeLayer.Update"
second_title: "Aspose.PSD for .NET API Referansı"
description: "ShapeLayer yöntemi. Shape katmanı özelliklerinden kaynakları günceller."
type: docs
weight: 60
url: /tr/net/aspose.psd.fileformats.psd.layers/shapelayer/update/
---
{{< psd/tize >}}
## ShapeLayer.Update method

Shape katmanı özelliklerinden kaynakları günceller.

```csharp
public void Update()
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

* class [ShapeLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


