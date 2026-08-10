---
title: "Kelas Pen"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Kelas Aspose.PSD.Pen. Mendefinisikan objek yang digunakan untuk menggambar garis, kurva, dan gambar."
type: docs
weight: 5690
url: /id/net/aspose.psd/pen/
---
{{< psd/tize >}}
## Pen class

Mendefinisikan objek yang digunakan untuk menggambar garis, kurva, dan bentuk.

```csharp
public class Pen : TransparencySupporter
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [Pen](pen/#constructor)(Brush) | Menginisialisasi instance baru dari kelas `Pen` dengan [`Brush`](./brush/). |
| [Pen](pen/#constructor_2)(Color) | Menginisialisasi instance baru dari kelas `Pen` dengan warna yang ditentukan. |
| [Pen](pen/#constructor_1)(Brush, float) | Menginisialisasi instance baru dari kelas `Pen` dengan [`Brush`](./brush/) dan [`Width`](./width/) yang ditentukan. |
| [Pen](pen/#constructor_3)(Color, float) | Menginisialisasi instance baru dari kelas `Pen` dengan properti [`Color`](./color/) dan [`Width`](./width/) yang ditentukan. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Alignment](../../aspose.psd/pen/alignment/) { get; set; } | Mendapatkan atau mengatur penjajaran untuk `Pen` ini. |
| [Brush](../../aspose.psd/pen/brush/) { get; set; } | Mendapatkan atau mengatur [`Brush`](./brush/) yang menentukan atribut `Pen` ini. |
| [Color](../../aspose.psd/pen/color/) { get; set; } | Mendapatkan atau mengatur warna `Pen` ini. |
| [CompoundArray](../../aspose.psd/pen/compoundarray/) { get; set; } | Mendapatkan atau mengatur array nilai yang menentukan pena komposit. Pena komposit menggambar garis komposit yang terdiri dari garis paralel dan ruang. |
| [CustomEndCap](../../aspose.psd/pen/customendcap/) { get; set; } | Mendapatkan atau mengatur cap khusus yang digunakan di akhir garis yang digambar dengan `Pen` ini. |
| [CustomStartCap](../../aspose.psd/pen/customstartcap/) { get; set; } | Mendapatkan atau mengatur penutup khusus yang digunakan di awal garis yang digambar dengan `Pen` ini. |
| [DashCap](../../aspose.psd/pen/dashcap/) { get; set; } | Mendapatkan atau mengatur gaya penutup yang digunakan di akhir garis putus-putus yang membentuk garis bergaris yang digambar dengan `Pen` ini. |
| [DashOffset](../../aspose.psd/pen/dashoffset/) { get; set; } | Mendapatkan atau mengatur jarak dari awal sebuah garis ke permulaan pola garis putus-putus. |
| [DashPattern](../../aspose.psd/pen/dashpattern/) { get; set; } | Mendapatkan atau mengatur array garis putus-putus dan spasi khusus. |
| [DashStyle](../../aspose.psd/pen/dashstyle/) { get; set; } | Mendapatkan atau mengatur gaya yang digunakan untuk garis putus-putus yang digambar dengan `Pen` ini. |
| [EndCap](../../aspose.psd/pen/endcap/) { get; set; } | Mendapatkan atau mengatur gaya penutup yang digunakan di akhir garis yang digambar dengan `Pen` ini. |
| [LineJoin](../../aspose.psd/pen/linejoin/) { get; set; } | Mendapatkan atau mengatur gaya sambungan untuk ujung dua garis berurutan yang digambar dengan `Pen` ini. |
| [MiterLimit](../../aspose.psd/pen/miterlimit/) { get; set; } | Mendapatkan atau mengatur batas ketebalan sambungan pada sudut miring. |
| [Opacity](../../aspose.psd/transparencysupporter/opacity/) { get; set; } | Mengambil atau mengatur opasitas objek. Nilainya harus antara 0 dan 1. Nilai 0 berarti objek sepenuhnya terlihat, nilai 1 berarti objek sepenuhnya tidak tembus. |
| [PenType](../../aspose.psd/pen/pentype/) { get; } | Mendapatkan gaya garis yang digambar dengan `Pen` ini. |
| [StartCap](../../aspose.psd/pen/startcap/) { get; set; } | Mendapatkan atau mengatur gaya penutup yang digunakan di awal garis yang digambar dengan `Pen` ini. |
| [Transform](../../aspose.psd/pen/transform/) { get; set; } | Mendapatkan atau mengatur salinan transformasi geometrik untuk `Pen` ini. |
| [Width](../../aspose.psd/pen/width/) { get; set; } | Mendapatkan atau mengatur lebar `Pen` ini, dalam satuan objek Graphics yang digunakan untuk menggambar. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [MultiplyTransform](../../aspose.psd/pen/multiplytransform/#multiplytransform)(Matrix) | Mengalikan matriks transformasi untuk `Pen` ini dengan [`Matrix`](../matrix/) yang ditentukan. |
| [MultiplyTransform](../../aspose.psd/pen/multiplytransform/#multiplytransform_1)(Matrix, MatrixOrder) | Mengalikan matriks transformasi untuk `Pen` ini dengan [`Matrix`](../matrix/) yang ditentukan dalam urutan yang ditentukan. |
| [ResetTransform](../../aspose.psd/pen/resettransform/)() | Mengatur ulang matriks transformasi geometrik untuk `Pen` ini ke identitas. |
| [RotateTransform](../../aspose.psd/pen/rotatetransform/#rotatetransform)(float) | Memutar transformasi geometrik lokal sebesar sudut yang ditentukan. Metode ini menambahkan rotasi ke depan transformasi. |
| [RotateTransform](../../aspose.psd/pen/rotatetransform/#rotatetransform_1)(float, MatrixOrder) | Memutar transformasi geometrik lokal sebesar sudut yang ditentukan dalam urutan yang ditentukan. |
| [ScaleTransform](../../aspose.psd/pen/scaletransform/#scaletransform)(float, float) | Menskalakan transformasi geometrik lokal dengan faktor yang ditentukan. Metode ini menambahkan matriks skala ke depan transformasi. |
| [ScaleTransform](../../aspose.psd/pen/scaletransform/#scaletransform_1)(float, float, MatrixOrder) | Menskalakan transformasi geometrik lokal dengan faktor yang ditentukan dalam urutan yang ditentukan. |
| [SetLineCap](../../aspose.psd/pen/setlinecap/)(LineCap, LineCap, DashCap) | Menetapkan nilai yang menentukan gaya penutup yang digunakan untuk mengakhiri garis yang digambar oleh `Pen` ini. |
| [TranslateTransform](../../aspose.psd/pen/translatetransform/#translatetransform)(float, float) | Menerjemahkan transformasi geometrik lokal dengan dimensi yang ditentukan. Metode ini menambahkan translasi ke depan transformasi. |
| [TranslateTransform](../../aspose.psd/pen/translatetransform/#translatetransform_1)(float, float, MatrixOrder) | Menerjemahkan transformasi geometrik lokal dengan dimensi yang ditentukan dalam urutan yang ditentukan. |

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

* class [TransparencySupporter](../transparencysupporter/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


