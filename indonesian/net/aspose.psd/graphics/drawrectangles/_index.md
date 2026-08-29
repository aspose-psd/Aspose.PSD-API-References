---
title: "Graphics.DrawRectangles"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Metode Graphics. Menggambar serangkaian persegi panjang yang ditentukan oleh struktur RectangleF."
type: docs
weight: 320
url: /id/net/aspose.psd/graphics/drawrectangles/
---
{{< psd/tize >}}
## DrawRectangles(Pen, RectangleF[]) {#drawrectangles}

Menggambar serangkaian persegi panjang yang ditentukan oleh struktur [`RectangleF`](../../rectanglef/).

```csharp
public void DrawRectangles(Pen pen, RectangleF[] rects)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) yang menentukan warna, lebar, dan gaya garis luar persegi panjang. |
| rects | RectangleF[] | Array dari struktur [`RectangleF`](../../rectanglef/) yang mewakili persegi panjang yang akan digambar. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | *pen* bernilai null. -atau- *rects* bernilai null. |

### Lihat Juga

* class [Pen](../../pen/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawRectangles(Pen, Rectangle[]) {#drawrectangles_1}

Menggambar serangkaian persegi panjang yang ditentukan oleh struktur [`Rectangle`](../../rectangle/).

```csharp
public void DrawRectangles(Pen pen, Rectangle[] rects)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) yang menentukan warna, lebar, dan gaya garis luar persegi panjang. |
| rects | Rectangle[] | Array dari struktur [`Rectangle`](../../rectangle/) yang mewakili persegi panjang yang akan digambar. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | *pen* bernilai null. -atau- *rects* bernilai null. |

## Contoh

Contoh ini menunjukkan pembuatan dan penggunaan objek Pen. Contoh ini membuat Image baru dan menggambar Rectangles pada permukaan Image.

```csharp
[C#]

//Buat sebuah instance dari Image
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Buat sebuah instance dari Graphics dan inisialisasi dengan objek Image
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Bersihkan permukaan Graphics dengan Warna Putih
    graphics.Clear(Aspose.PSD.Color.White);

    //Buat sebuah instance dari Pen dengan warna Merah dan lebar 5
    Aspose.PSD.Pen pen = new Pen(Aspose.PSD.Color.Red, 5);

    //Buat sebuah instance dari HatchBrush dan atur propertinya
    Aspose.PSD.Brushes.HatchBrush brush = new Aspose.PSD.Brushes.HatchBrush();
    brush.BackgroundColor = Color.Wheat;
    brush.ForegroundColor = Color.Red;

    //Buat sebuah instance dari Pen
    //inisialisasi dengan objek HatchBrush dan lebar
    Aspose.PSD.Pen brusedpen = new Pen(brush, 5);

    //Gambar Rectangles dengan menentukan objek Pen
    graphics.DrawRectangles(pen, new[] { new Rectangle(new Point(210, 210), new Size(100, 100)), new Rectangle(new Point(110, 110), new Size(100, 100)), new Rectangle(new Point(310, 310), new Size(100, 100)) });

    //Gambar Rectangles dengan menentukan objek Pen
    graphics.DrawRectangles(brusedpen, new[] { new Rectangle(new Point(310, 110), new Size(100, 100)), new Rectangle(new Point(110, 310), new Size(100, 100)) });

    // Buat opsi ekspor dan inisialisasi mereka.
    Aspose.PSD.ImageOptions.Jpeg2000Options options = new Aspose.PSD.ImageOptions.Jpeg2000Options();

    // simpan semua perubahan.
    image.Save("c:\\temp\\output.jp2", options);
}
```

### Lihat Juga

* class [Pen](../../pen/)
* struct [Rectangle](../../rectangle/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


