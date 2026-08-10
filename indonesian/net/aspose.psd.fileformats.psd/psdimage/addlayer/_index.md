---
title: "PsdImage.AddLayer"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Metode PsdImage. Menambahkan lapisan"
type: docs
weight: 390
url: /id/net/aspose.psd.fileformats.psd/psdimage/addlayer/
---
{{< psd/tize >}}
## PsdImage.AddLayer method

Menambahkan lapisan.

```csharp
public void AddLayer(Layer layer)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lapisan | Lapisan | Lapisan. |

## Contoh

Contoh berikut menunjukkan cara Anda dapat menggambar pada lapisan yang baru dibuat jika versi konstruktor sederhana digunakan dalam Aspose.PSD

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

    // gambar sebuah persegi panjang dengan alat Pen
    graphic.DrawRectangle(new Pen(Color.Red), new Rectangle(30, 10, 40, 80));

    // gambar persegi panjang lain dengan Kuas Solid berwarna Biru
    graphic.DrawRectangle(new Pen(new SolidBrush(Color.Blue)), new Rectangle(10, 30, 80, 40));

    image.Save(outputFilePath);
}
```

### Lihat Juga

* class [Layer](../../../aspose.psd.fileformats.psd.layers/layer/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


