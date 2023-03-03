---
title: Graphics.DrawRectangles
second_title: Aspose.PSD untuk Referensi .NET API
description: Graphics metode. Menggambar serangkaian persegi panjang yang ditentukan olehRectangleF struktur.
type: docs
weight: 310
url: /id/net/aspose.psd/graphics/drawrectangles/
---
## DrawRectangles(Pen, RectangleF[]) {#drawrectangles}

Menggambar serangkaian persegi panjang yang ditentukan oleh[`RectangleF`](../../rectanglef/) struktur.

```csharp
public void DrawRectangles(Pen pen, RectangleF[] rects)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) yang menentukan warna, lebar, dan gaya garis luar persegi panjang. |
| rects | RectangleF[] | Susunan dari[`RectangleF`](../../rectanglef/) struktur yang mewakili persegi panjang untuk menggambar. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | *pen* adalah null. -atau- *rects* adalah nol. |

### Lihat juga

* class [Pen](../../pen/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* ruang nama [Aspose.PSD](../../graphics/)
* perakitan [Aspose.PSD](../../../)

---

## DrawRectangles(Pen, Rectangle[]) {#drawrectangles_1}

Menggambar serangkaian persegi panjang yang ditentukan oleh[`Rectangle`](../../rectangle/) struktur.

```csharp
public void DrawRectangles(Pen pen, Rectangle[] rects)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) yang menentukan warna, lebar, dan gaya garis luar persegi panjang. |
| rects | Rectangle[] | Susunan dari[`Rectangle`](../../rectangle/) struktur yang mewakili persegi panjang untuk menggambar. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | *pen* adalah null. -atau- *rects* adalah nol. |

### Contoh

Contoh ini menunjukkan pembuatan dan penggunaan objek Pena. Contoh membuat Gambar baru dan menggambar Persegi Panjang pada permukaan Gambar.

```csharp
[C#]

//Buat instance dari Gambar
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    // Buat instance Grafik dan inisialisasi dengan objek Gambar
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    // Hapus sutface Grafik dengan Warna Putih
    graphics.Clear(Aspose.PSD.Color.White);

    //Buat instance Pena dengan warna Merah dan lebar 5
    Aspose.PSD.Pen pen = new Pen(Aspose.PSD.Color.Red, 5);

    //Buat instance HatchBrush dan atur propertinya
    Aspose.PSD.Brushes.HatchBrush brush = new Aspose.PSD.Brushes.HatchBrush();
    brush.BackgroundColor = Color.Wheat;
    brush.ForegroundColor = Color.Red;

    //Buat turunan Pena
    //inisialisasi dengan objek dan lebar HatchBrush
    Aspose.PSD.Pen brusedpen = new Pen(brush, 5);

    // Gambar Persegi Panjang dengan menentukan objek Pena
    graphics.DrawRectangles(pen, new[] { new Rectangle(new Point(210, 210), new Size(100, 100)), new Rectangle(new Point(110, 110), new Size(100, 100)), new Rectangle(new Point(310, 310), new Size(100, 100)) });

    // Gambar Persegi Panjang dengan menentukan objek Pena
    graphics.DrawRectangles(brusedpen, new[] { new Rectangle(new Point(310, 110), new Size(100, 100)), new Rectangle(new Point(110, 310), new Size(100, 100)) });

    // Buat opsi ekspor dan inisialisasi.
    Aspose.PSD.ImageOptions.Jpeg2000Options options = new Aspose.PSD.ImageOptions.Jpeg2000Options();

    // simpan semua perubahan.
    image.Save("c:\\temp\\output.jp2", options);
}
```

### Lihat juga

* class [Pen](../../pen/)
* struct [Rectangle](../../rectangle/)
* class [Graphics](../)
* ruang nama [Aspose.PSD](../../graphics/)
* perakitan [Aspose.PSD](../../../)


