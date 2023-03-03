---
title: Class HatchBrush
second_title: Aspose.PSD untuk Referensi .NET API
description: Aspose.PSD.Brushes.HatchBrush kelas. Menentukan sikat persegi panjang dengan gaya penetasan warna latar depan dan warna latar belakang. Kelas ini tidak dapat diwariskan.
type: docs
weight: 130
url: /id/net/aspose.psd.brushes/hatchbrush/
---
## HatchBrush class

Menentukan sikat persegi panjang dengan gaya penetasan, warna latar depan, dan warna latar belakang. Kelas ini tidak dapat diwariskan.

```csharp
public sealed class HatchBrush : Brush
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [HatchBrush](hatchbrush/)() | Konstruktor default. |

## Properti

| Nama | Keterangan |
| --- | --- |
| [BackgroundColor](../../aspose.psd.brushes/hatchbrush/backgroundcolor/) { get; set; } | Mendapat atau mengatur warna spasi antara garis penetasan. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Mendapat nilai yang menunjukkan apakah instance ini dibuang. |
| [ForegroundColor](../../aspose.psd.brushes/hatchbrush/foregroundcolor/) { get; set; } | Mendapat atau menyetel warna garis penetasan. |
| [HatchStyle](../../aspose.psd.brushes/hatchbrush/hatchstyle/) { get; set; } | Mendapat atau menyetel gaya penetasan kuas ini. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | Mendapat atau menyetel opasitas kuas. Nilai harus antara 0 dan 1. Nilai 0 berarti kuas terlihat sepenuhnya, nilai 1 berarti kuas sepenuhnya buram. |

## Metode

| Nama | Keterangan |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | Membuat klon dalam baru dari arus[`Brush`](../../aspose.psd/brush/) . |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Membuang instance saat ini. |

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

* class [Brush](../../aspose.psd/brush/)
* ruang nama [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* perakitan [Aspose.PSD](../../)


