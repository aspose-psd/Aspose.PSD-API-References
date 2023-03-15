---
title: PsdImage.AddLayer
second_title: Aspose.PSD untuk Referensi .NET API
description: PsdImage metode. Menambahkan lapisan.
type: docs
weight: 370
url: /id/net/aspose.psd.fileformats.psd/psdimage/addlayer/
---
## PsdImage.AddLayer method

Menambahkan lapisan.

```csharp
public void AddLayer(Layer layer)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| layer | Layer | Lapisan. |

### Contoh

Contoh berikut menunjukkan bagaimana Anda bisa menggambar pada lapisan yang baru dibuat jika versi konstruktor sederhana digunakan di Aspose.PSD

```csharp
[C#]

string outputFilePath = "output.psd";

int width = 100;
int height = 100;
using (var image = new PsdImage(width, height))
{
    var layer = new Layer();
    layer.Bottom = height;
    layer.Right = width;
    image.AddLayer(layer);

    Graphics graphic = new Graphics(layer);
    graphic.Clear(Color.Yellow);

    // menggambar persegi panjang dengan Pen tool
    graphic.DrawRectangle(new Pen(Color.Red), new Rectangle(30, 10, 40, 80));

    // menggambar persegi panjang lain dengan Kuas Padat dalam warna Biru
    graphic.DrawRectangle(new Pen(new SolidBrush(Color.Blue)), new Rectangle(10, 30, 80, 40));

    image.Save(outputFilePath);
}
```

### Lihat juga

* class [Layer](../../../aspose.psd.fileformats.psd.layers/layer/)
* class [PsdImage](../)
* ruang nama [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* perakitan [Aspose.PSD](../../../)


