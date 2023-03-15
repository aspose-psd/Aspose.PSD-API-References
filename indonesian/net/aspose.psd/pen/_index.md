---
title: Class Pen
second_title: Aspose.PSD untuk Referensi .NET API
description: Aspose.PSD.Pen kelas. Menentukan objek yang digunakan untuk menggambar garis kurva dan gambar.
type: docs
weight: 5200
url: /id/net/aspose.psd/pen/
---
## Pen class

Menentukan objek yang digunakan untuk menggambar garis, kurva, dan gambar.

```csharp
public class Pen : TransparencySupporter
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [Pen](pen/#constructor)(Brush) | Menginisialisasi instance baru dari`Pen` kelas dengan yang ditentukan[`Brush`](./brush/) . |
| [Pen](pen/#constructor_2)(Color) | Menginisialisasi instance baru dari`Pen` kelas dengan warna yang ditentukan. |
| [Pen](pen/#constructor_1)(Brush, float) | Menginisialisasi instance baru dari`Pen` kelas dengan yang ditentukan[`Brush`](./brush/) Dan[`Width`](./width/) . |
| [Pen](pen/#constructor_3)(Color, float) | Menginisialisasi instance baru dari`Pen` kelas dengan yang ditentukan[`Color`](./color/) Dan[`Width`](./width/) properti. |

## Properti

| Nama | Keterangan |
| --- | --- |
| [Alignment](../../aspose.psd/pen/alignment/) { get; set; } | Mendapat atau menyetel perataan untuk ini`Pen` . |
| [Brush](../../aspose.psd/pen/brush/) { get; set; } | Mendapat atau menyetel[`Brush`](./brush/) yang menentukan atribut ini`Pen` . |
| [Color](../../aspose.psd/pen/color/) { get; set; } | Mendapat atau menyetel warna ini`Pen` . |
| [CompoundArray](../../aspose.psd/pen/compoundarray/) { get; set; } | Mendapat atau menetapkan array nilai yang menentukan pena majemuk. Pena majemuk menggambar garis majemuk yang terdiri dari garis dan spasi paralel. |
| [CustomEndCap](../../aspose.psd/pen/customendcap/) { get; set; } | Mendapat atau menyetel batas khusus untuk digunakan di akhir garis yang digambar dengan ini`Pen` . |
| [CustomStartCap](../../aspose.psd/pen/customstartcap/) { get; set; } | Mendapat atau menyetel batas khusus untuk digunakan di awal garis yang digambar dengan ini`Pen` . |
| [DashCap](../../aspose.psd/pen/dashcap/) { get; set; } | Mendapat atau menyetel gaya topi yang digunakan di akhir tanda hubung yang membentuk garis putus-putus yang digambar dengan ini`Pen` . |
| [DashOffset](../../aspose.psd/pen/dashoffset/) { get; set; } | Mendapat atau mengatur jarak dari awal garis ke awal pola garis putus-putus. |
| [DashPattern](../../aspose.psd/pen/dashpattern/) { get; set; } | Mendapat atau menyetel larik tanda hubung dan spasi khusus. |
| [DashStyle](../../aspose.psd/pen/dashstyle/) { get; set; } | Mendapat atau menyetel gaya yang digunakan untuk garis putus-putus yang digambar dengan ini`Pen` . |
| [EndCap](../../aspose.psd/pen/endcap/) { get; set; } | Mendapat atau menyetel gaya topi yang digunakan pada akhir garis yang digambar dengan ini`Pen` . |
| [LineJoin](../../aspose.psd/pen/linejoin/) { get; set; } | Mendapat atau menyetel gaya gabungan untuk ujung dari dua garis berurutan yang digambar dengan ini`Pen` . |
| [MiterLimit](../../aspose.psd/pen/miterlimit/) { get; set; } | Mendapat atau menetapkan batas ketebalan gabungan pada sudut yang disematkan. |
| [Opacity](../../aspose.psd/transparencysupporter/opacity/) { get; set; } | Mendapat atau menyetel opasitas objek. Nilainya harus antara 0 dan 1. Nilai 0 berarti objek terlihat sepenuhnya, nilai 1 berarti objek sepenuhnya buram. |
| [PenType](../../aspose.psd/pen/pentype/) { get; } | Mendapat gaya garis yang digambar dengan ini`Pen` . |
| [StartCap](../../aspose.psd/pen/startcap/) { get; set; } | Mendapat atau menyetel gaya topi yang digunakan pada awal garis yang digambar dengan ini`Pen` . |
| [Transform](../../aspose.psd/pen/transform/) { get; set; } | Mendapatkan atau menyetel salinan transformasi geometrik untuk ini`Pen` . |
| [Width](../../aspose.psd/pen/width/) { get; set; } | Mendapat atau mengatur lebar ini`Pen` , dalam satuan objek Grafik yang digunakan untuk menggambar. |

## Metode

| Nama | Keterangan |
| --- | --- |
| [MultiplyTransform](../../aspose.psd/pen/multiplytransform/#multiplytransform)(Matrix) | Mengalikan matriks transformasi untuk ini`Pen` oleh yang ditentukan[`Matrix`](../matrix/) . |
| [MultiplyTransform](../../aspose.psd/pen/multiplytransform/#multiplytransform_1)(Matrix, MatrixOrder) | Mengalikan matriks transformasi untuk ini`Pen` oleh yang ditentukan[`Matrix`](../matrix/) dalam urutan yang ditentukan. |
| [ResetTransform](../../aspose.psd/pen/resettransform/)() | Mereset matriks transformasi geometrik untuk ini`Pen` ke identitas. |
| [RotateTransform](../../aspose.psd/pen/rotatetransform/#rotatetransform)(float) | Memutar transformasi geometris lokal dengan sudut yang ditentukan. Metode ini menambahkan rotasi ke transformasi. |
| [RotateTransform](../../aspose.psd/pen/rotatetransform/#rotatetransform_1)(float, MatrixOrder) | Memutar transformasi geometris lokal dengan sudut yang ditentukan dalam urutan yang ditentukan. |
| [ScaleTransform](../../aspose.psd/pen/scaletransform/#scaletransform)(float, float) | Menskalakan transformasi geometris lokal dengan faktor yang ditentukan. Metode ini menambahkan matriks penskalaan ke transformasi. |
| [ScaleTransform](../../aspose.psd/pen/scaletransform/#scaletransform_1)(float, float, MatrixOrder) | Menskalakan transformasi geometris lokal dengan faktor yang ditentukan dalam urutan yang ditentukan. |
| [SetLineCap](../../aspose.psd/pen/setlinecap/)(LineCap, LineCap, DashCap) | Menetapkan nilai yang menentukan gaya tutup yang digunakan untuk mengakhiri garis yang digambar oleh ini`Pen` . |
| [TranslateTransform](../../aspose.psd/pen/translatetransform/#translatetransform)(float, float) | Menerjemahkan transformasi geometris lokal dengan dimensi yang ditentukan. Metode ini menambahkan terjemahan ke transformasi. |
| [TranslateTransform](../../aspose.psd/pen/translatetransform/#translatetransform_1)(float, float, MatrixOrder) | Menerjemahkan transformasi geometris lokal dengan dimensi yang ditentukan dalam urutan yang ditentukan. |

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

* class [TransparencySupporter](../transparencysupporter/)
* ruang nama [Aspose.PSD](../../aspose.psd/)
* perakitan [Aspose.PSD](../../)


