---
title: "ShapeLayer.CreateInstance"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Metode ShapeLayer. Membuat instance baru dari kelas ShapeLayer."
type: docs
weight: 20
url: /id/net/aspose.psd.fileformats.psd.layers/shapelayer/createinstance/
---
{{< psd/tize >}}
## ShapeLayer.CreateInstance method

Membuat instance baru dari kelas [`ShapeLayer`](../).

```csharp
public static ShapeLayer CreateInstance()
```

### Nilai Kembalian

Mengembalikan instance baru dari kelas [`ShapeLayer`](../).

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


