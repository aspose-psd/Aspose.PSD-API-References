---
title: "ShapeLayer.CreateInstance"
second_title: "Aspose.PSD for .NET API Referansı"
description: "ShapeLayer yöntemi. ShapeLayer sınıfının yeni bir örneğini oluşturur."
type: docs
weight: 20
url: /tr/net/aspose.psd.fileformats.psd.layers/shapelayer/createinstance/
---
{{< psd/tize >}}
## ShapeLayer.CreateInstance method

Yeni bir [`ShapeLayer`](../) sınıfı örneği oluşturur.

```csharp
public static ShapeLayer CreateInstance()
```

### Dönüş Değeri

Yeni bir [`ShapeLayer`](../) sınıfı örneğini döndürür.

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


