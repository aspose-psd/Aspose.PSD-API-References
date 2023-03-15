---
title: Class Font
second_title: Aspose.PSD untuk Referensi .NET API
description: Aspose.PSD.Font kelas. Menentukan format tertentu untuk teks termasuk atribut font face size dan style. Kelas ini tidak dapat diwariskan.
type: docs
weight: 4280
url: /id/net/aspose.psd/font/
---
## Font class

Menentukan format tertentu untuk teks, termasuk atribut font face, size, dan style. Kelas ini tidak dapat diwariskan.

```csharp
public sealed class Font
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [Font](font/#constructor)(Font, FontStyle) | Menginisialisasi yang baru`Font` yang menggunakan ditentukan ada`Font` Dan[`FontStyle`](../fontstyle/) pencacahan. |
| [Font](font/#constructor_1)(string, float) | Menginisialisasi yang baru`Font` menggunakan ukuran tertentu. Set karakter diatur keDefault , unit grafik kePoint , gaya font keRegular . |
| [Font](font/#constructor_2)(string, float, FontStyle) | Menginisialisasi yang baru`Font` menggunakan ukuran dan gaya tertentu. Set karakter diatur keDefault , unit grafik kePoint . |
| [Font](font/#constructor_5)(string, float, GraphicsUnit) | Menginisialisasi yang baru`Font` menggunakan ukuran dan satuan tertentu. Set karakter diatur keDefault gaya diatur keRegular . |
| [Font](font/#constructor_3)(string, float, FontStyle, GraphicsUnit) | Menginisialisasi yang baru`Font` menggunakan ukuran, gaya, dan satuan tertentu. |
| [Font](font/#constructor_4)(string, float, FontStyle, GraphicsUnit, CharacterSet) | Menginisialisasi yang baru`Font` menggunakan ukuran, gaya, unit, dan kumpulan karakter yang ditentukan. |

## Properti

| Nama | Keterangan |
| --- | --- |
| [Bold](../../aspose.psd/font/bold/) { get; } | Mendapat nilai yang menunjukkan apakah ini`Font` tebal. |
| [CharacterSet](../../aspose.psd/font/characterset/) { get; } | Mendapat nilai byte yang menentukan set karakter ini`Font` kegunaan. |
| [Italic](../../aspose.psd/font/italic/) { get; } | Mendapat nilai yang menunjukkan apakah ini`Font`itu miring. |
| [Name](../../aspose.psd/font/name/) { get; } | Mendapat nama wajah ini`Font` . |
| [Size](../../aspose.psd/font/size/) { get; } | Mendapat ukuran em dari ini`Font` diukur dalam satuan yang ditentukan oleh[`Unit`](./unit/) properti. |
| [Strikeout](../../aspose.psd/font/strikeout/) { get; } | Mendapat nilai yang menunjukkan apakah ini`Font` menentukan garis horizontal melalui font. |
| [Style](../../aspose.psd/font/style/) { get; } | Mendapat informasi gaya untuk ini`Font` . |
| [Underline](../../aspose.psd/font/underline/) { get; } | Mendapat nilai yang menunjukkan apakah ini`Font` digarisbawahi. |
| [Unit](../../aspose.psd/font/unit/) { get; } | Mendapat satuan ukuran untuk ini`Font` . |

## Metode

| Nama | Keterangan |
| --- | --- |
| [DeepClone](../../aspose.psd/font/deepclone/)() | Membuat salinan mendalam yang tepat dari ini`Font` . |
| override [Equals](../../aspose.psd/font/equals/)(object) | Menunjukkan apakah objek yang ditentukan adalah a`Font` dan memiliki nilai properti yang sama seperti ini`Font` . |
| override [GetHashCode](../../aspose.psd/font/gethashcode/)() | Mendapat kode hash untuk ini`Font` . |
| override [ToString](../../aspose.psd/font/tostring/)() | Mengembalikan representasi string yang dapat dibaca manusia dari ini`Font` . |

### Contoh

Contoh ini mendemonstrasikan penggunaan kelas Font dan SolidBrush untuk menggambar string pada permukaan Gambar. Contoh membuat Gambar baru dan menggambar bentuk menggunakan Figures dan GraphicsPath

```csharp
[C#]

// Membuat instance dari Gambar
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Membuat dan menginisialisasi sebuah instance dari kelas Grafik
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    // Membersihkan permukaan Grafik
    graphics.Clear(Color.Wheat);

    //Membuat turunan dari Font
    Aspose.PSD.Font font = new Aspose.PSD.Font("Times New Roman", 16);

    //Buat instance SolidBrush yang memiliki Warna Merah
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush(Color.Red);

    //Gambar sebuah String
    graphics.DrawString("Created by Aspose.PSD for .Net", font, brush, new PointF(100, 100));

    // buat opsi ekspor.
    Aspose.PSD.ImageOptions.GifOptions options = new Aspose.PSD.ImageOptions.GifOptions();

    // simpan semua perubahan
    image.Save("C:\\temp\\output.gif", options);
}
```

### Lihat juga

* ruang nama [Aspose.PSD](../../aspose.psd/)
* perakitan [Aspose.PSD](../../)


