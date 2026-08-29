---
title: "Kelas Font"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Kelas Aspose.PSD.Font. Mendefinisikan format khusus untuk teks termasuk ukuran dan atribut gaya font. Kelas ini tidak dapat diwariskan"
type: docs
weight: 4750
url: /id/net/aspose.psd/font/
---
{{< psd/tize >}}
## Font class

Mendefinisikan format khusus untuk teks, termasuk jenis huruf, ukuran, dan atribut gaya. Kelas ini tidak dapat diwariskan.

```csharp
public sealed class Font
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [Font](font/#constructor)(Font, FontStyle) | Menginisialisasi `Font` baru yang menggunakan `Font` yang ada yang ditentukan dan enumerasi [`FontStyle`](../fontstyle/). |
| [Font](font/#constructor_1)(string, float) | Menginisialisasi `Font` baru dengan ukuran yang ditentukan. Set karakter diatur ke Default, unit grafis ke Point, gaya font ke Regular. |
| [Font](font/#constructor_2)(string, float, FontStyle) | Menginisialisasi `Font` baru dengan ukuran dan gaya yang ditentukan. Set karakter diatur ke Default, unit grafis ke Point. |
| [Font](font/#constructor_5)(string, float, GraphicsUnit) | Menginisialisasi `Font` baru dengan ukuran dan unit yang ditentukan. Set karakter diatur ke Default, gaya diatur ke Regular. |
| [Font](font/#constructor_3)(string, float, FontStyle, GraphicsUnit) | Menginisialisasi `Font` baru dengan ukuran, gaya, dan unit yang ditentukan. Set karakter diatur ke Default, gaya diatur ke Regular. |
| [Font](font/#constructor_4)(string, float, FontStyle, GraphicsUnit, CharacterSet) | Menginisialisasi `Font` baru menggunakan ukuran, gaya, satuan, dan set karakter yang ditentukan. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Bold](../../aspose.psd/font/bold/) { get; } | Mendapatkan nilai yang menunjukkan apakah `Font` ini tebal. |
| [CharacterSet](../../aspose.psd/font/characterset/) { get; } | Mendapatkan nilai byte yang menentukan set karakter yang digunakan oleh `Font` ini. |
| [Italic](../../aspose.psd/font/italic/) { get; } | Mendapatkan nilai yang menunjukkan apakah `Font` ini miring. |
| [Name](../../aspose.psd/font/name/) { get; } | Mendapatkan nama wajah dari `Font` ini. |
| [Size](../../aspose.psd/font/size/) { get; } | Mendapatkan ukuran em dari `Font` ini yang diukur dalam satuan yang ditentukan oleh properti [`Unit`](./unit/). |
| [Strikeout](../../aspose.psd/font/strikeout/) { get; } | Mendapatkan nilai yang menunjukkan apakah `Font` ini memiliki garis horizontal yang melintang pada huruf. |
| [Style](../../aspose.psd/font/style/) { get; } | Mendapatkan informasi gaya untuk `Font` ini. |
| [Underline](../../aspose.psd/font/underline/) { get; } | Mendapatkan nilai yang menunjukkan apakah `Font` ini bergaris bawah. |
| [Unit](../../aspose.psd/font/unit/) { get; } | Mendapatkan satuan ukuran untuk `Font` ini. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [DeepClone](../../aspose.psd/font/deepclone/)() | Membuat salinan mendalam yang persis dari `Font` ini. |
| override [Equals](../../aspose.psd/font/equals/)(object) | Menunjukkan apakah objek yang ditentukan adalah `Font` dan memiliki nilai properti yang sama dengan `Font` ini. |
| override [GetHashCode](../../aspose.psd/font/gethashcode/)() | Mendapatkan kode hash untuk `Font` ini. |
| override [ToString](../../aspose.psd/font/tostring/)() | Mengembalikan representasi string yang dapat dibaca manusia dari `Font` ini. |

## Contoh

Contoh ini menunjukkan penggunaan kelas Font dan SolidBrush untuk menggambar string pada permukaan Image. Contoh ini membuat Image baru dan menggambar bentuk menggunakan Figures dan GraphicsPath

```csharp
[C#]

//Membuat instance dari Image
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Membuat dan menginisialisasi instance dari kelas Graphics
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Membersihkan permukaan Graphics
    graphics.Clear(Color.Wheat);

    //Membuat instance dari Font
    Aspose.PSD.Font font = new Aspose.PSD.Font("Times New Roman", 16);

    //Membuat instance SolidBrush dengan Warna Merah
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush(Color.Red);

    //Menggambar String
    graphics.DrawString("Created by Aspose.PSD for .Net", font, brush, new PointF(100, 100));

    // membuat opsi ekspor.
    Aspose.PSD.ImageOptions.GifOptions options = new Aspose.PSD.ImageOptions.GifOptions();

    // simpan semua perubahan
    image.Save("C:\\temp\\output.gif", options);
}
```

### Lihat Juga

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


