---
title: "ShapeLayer.ShapeLayer"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Konstruktor ShapeLayer. Menginisialisasi instance baru dari kelas ShapeLayer. Semua sumber daya dibuat dalam keadaan default."
type: docs
weight: 10
url: /id/net/aspose.psd.fileformats.psd.layers/shapelayer/shapelayer/
---
{{< psd/tize >}}
## ShapeLayer constructor

Menginisialisasi instance baru dari kelas [`ShapeLayer`](../). Semua sumber daya dibuat dalam keadaan default.

```csharp
public ShapeLayer()
```

## Contoh

Kode berikut menunjukkan dukungan untuk lapisan ShapeLayer.

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

    // File sumber berisi 2 gambar. Hapus yang kedua.
    pathShapesDest.RemoveAt(1);

    layerPath.SetItems(pathShapesDest.ToArray());

    shapeLayer.Update();

    image.Save(outFile);
}
```

### Lihat Juga

* class [ShapeLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


