---
title: "Kelas RawColor"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Aspose.PSD.FileFormats.Psd.Core.RawColor.RawColor kelas. Kelas Raw Color membantu menyimpan warna dengan jumlah saluran apa saja, mode warna apa saja, dan kedalaman bit apa saja. Harap perhatikan bahwa beberapa kelas internal dapat mengalami masalah saat mengonversi RawColor ke format aslinya, jadi jika API menyediakan warna CMYK untuk Anda, lebih dapat diandalkan menggunakan format yang disediakan. Juga ada beberapa kasus ketika Raw Color dapat dikonversi."
type: docs
weight: 1650
url: /id/net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/
---
{{< psd/tize >}}
## RawColor class

Raw Color Class membantu menyimpan warna dengan jumlah saluran apa pun, mode warna apa pun, dan kedalaman bit apa pun. Harap dicatat, beberapa kelas internal dapat mengalami masalah saat mengonversi RawColor ke format aslinya, jadi jika API menyediakan warna CMYK untuk Anda, lebih dapat diandalkan untuk menggunakan format yang disediakan. Juga, ada beberapa kasus ketika Raw Color dapat dikonversi.

```csharp
public sealed class RawColor
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [RawColor](rawcolor/#constructor)(ColorComponent[]) | Menginisialisasi instance baru dari kelas `RawColor`. |
| [RawColor](rawcolor/#constructor_1)(PixelDataFormat, short) | Menginisialisasi instance baru dari kelas `RawColor` dari format data piksel menggunakan mode warna yang telah ditentukan |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [ColorMode](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/colormode/) { get; set; } | Mode untuk warna yang akan diikuti. |
| [Components](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/components/) { get; } | Mendapatkan komponen warna. Setiap komponen adalah saluran terpisah, dan jika Anda menggunakan skema warna yang tidak populer, lebih baik bekerja dengan setiap saluran secara terpisah. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| override [Equals](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/equals/)(object) | Menentukan apakah Object yang ditentukan, sama dengan instance ini. |
| [GetAsInt](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/getasint/)() | Mendapatkan warna sebagai int jika memungkinkan untuk mendapatkannya. |
| [GetAsLong](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/getaslong/)() | Mendapatkan warna sebagai long jika memungkinkan untuk mendapatkannya. |
| [GetBitDepth](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/getbitdepth/)() | Mendapatkan kedalaman bit dari Raw Color. Misalnya untuk warna ARGB dengan 8 bit per saluran/komponen adalah 32. Kedalaman bit dari warna ARGB penuh dengan 16 bit per saluran/komponen adalah 64. Kedalaman bit dihitung dari jumlah kedalaman bit masing-masing saluran. Hal ini memungkinkan jika saluran yang berbeda memiliki kedalaman bit yang berbeda. |
| [GetColorModeName](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/getcolormodename/)() | Mendapatkan nama mode warna. Nama mode warna dikumpulkan dari nama saluran/komponen. |
| override [GetHashCode](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/gethashcode/)() | Dapatkan kode hash dari objek saat ini. |
| [SetAsInt](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/setasint/)(int) | Mengatur data ke semua saluran dari argumen int jika memungkinkan |
| [SetAsLong](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/setaslong/)(long) | Mengatur data ke semua saluran dari argumen int jika memungkinkan |
| [operator ==](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/op_equality/) | Mengimplementasikan operator ==. |
| [operator !=](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/op_inequality/) | Mengimplementasikan operator !=. |

## Contoh

Kode berikut menunjukkan dukungan kelas RawColor sebagai pengganti struct Color yang usang.

```csharp
[C#]

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception(message ?? "Objects are not equal.");
    }
}

var color = new RawColor(PixelDataFormat.Rgba32Bpp);
var oldColor = Color.FromArgb(5, 1, 2, 3);

var argbValue = oldColor.ToArgb();
color.SetAsInt(argbValue);

AssertAreEqual("ARGB", color.GetColorModeName());
AssertAreEqual(32, color.GetBitDepth());
AssertAreEqual("A Alpha", color.Components[0].FullName);
AssertAreEqual(5, (int)color.Components[0].Value);
AssertAreEqual("R Red", color.Components[1].FullName);
AssertAreEqual(1, (int)color.Components[1].Value);
AssertAreEqual("G Green", color.Components[2].FullName);
AssertAreEqual(2, (int)color.Components[2].Value);
AssertAreEqual("B Blue", color.Components[3].FullName);
AssertAreEqual(3, (int)color.Components[3].Value);

AssertAreEqual(argbValue, color.GetAsInt());
```

### Lihat Juga

* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../)


