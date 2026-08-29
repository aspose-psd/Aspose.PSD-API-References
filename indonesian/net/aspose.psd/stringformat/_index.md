---
title: "Class StringFormat"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Kelas Aspose.PSD.StringFormat. Membungkus informasi tata letak teks seperti orientasi perataan dan manipulasi tampilan tab stop seperti penyisipan elipsis, substitusi digit nasional, dan fitur OpenType. Kelas ini tidak dapat diwarisi."
type: docs
weight: 6170
url: /id/net/aspose.psd/stringformat/
---
{{< psd/tize >}}
## StringFormat class

Mengkapsulkan informasi tata letak teks (seperti perataan, orientasi, dan tab stop) manipulasi tampilan (seperti penyisipan elipsis dan substitusi digit nasional) serta fitur OpenType. Kelas ini tidak dapat diwariskan.

```csharp
public sealed class StringFormat : DisposableObject
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [StringFormat](stringformat/#constructor)() | Menginisialisasi objek `StringFormat` baru. |
| [StringFormat](stringformat/#constructor_1)(StringFormat) | Menginisialisasi objek `StringFormat` baru dari objek `StringFormat` yang sudah ada yang ditentukan. |
| [StringFormat](stringformat/#constructor_2)(StringFormatFlags) | Menginisialisasi objek `StringFormat` baru dengan enumerasi [`StringFormatFlags`](../stringformatflags/) dan bahasa yang ditentukan. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| static [GenericDefault](../../aspose.psd/stringformat/genericdefault/) { get; } | Mendapatkan objek `StringFormat` default generik. |
| static [GenericTypographic](../../aspose.psd/stringformat/generictypographic/) { get; } | Mendapatkan objek `StringFormat` tipografi generik. |
| [Alignment](../../aspose.psd/stringformat/alignment/) { get; set; } | Mendapatkan atau mengatur informasi perataan teks pada bidang vertikal. |
| [CustomCharIdent](../../aspose.psd/stringformat/customcharident/) { get; set; } | Mendapatkan atau mengatur ident karakter khusus. |
| [DigitSubstitutionLanguage](../../aspose.psd/stringformat/digitsubstitutionlanguage/) { get; set; } | Mendapatkan atau mengatur bahasa yang digunakan ketika digit lokal digantikan dengan digit barat. |
| [DigitSubstitutionMethod](../../aspose.psd/stringformat/digitsubstitutionmethod/) { get; set; } | Mendapatkan atau mengatur metode yang akan digunakan untuk substitusi digit. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Mendapatkan nilai yang menunjukkan apakah instansi ini telah dibuang. |
| [FirstTabOffset](../../aspose.psd/stringformat/firsttaboffset/) { get; } | Mendapatkan jumlah spasi antara awal baris teks dan tab stop pertama. |
| [FormatFlags](../../aspose.psd/stringformat/formatflags/) { get; set; } | Mendapatkan atau mengatur enumerasi [`StringFormatFlags`](../stringformatflags/) yang berisi informasi pemformatan. |
| [HotkeyPrefix](../../aspose.psd/stringformat/hotkeyprefix/) { get; set; } | Mendapatkan atau mengatur objek [`HotkeyPrefix`](../hotkeyprefix/) untuk objek `StringFormat` ini. |
| [LineAlignment](../../aspose.psd/stringformat/linealignment/) { get; set; } | Mendapatkan atau mengatur perataan baris pada bidang horizontal. |
| [TabStops](../../aspose.psd/stringformat/tabstops/) { get; } | Mendapatkan array jarak antara tab stop dalam satuan yang ditentukan oleh properti [`PageUnit`](../graphics/pageunit/). |
| [Trimming](../../aspose.psd/stringformat/trimming/) { get; set; } | Mendapatkan atau mengatur enumerasi [`StringTrimming`](../stringtrimming/) untuk objek `StringFormat` ini. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [DeepClone](../../aspose.psd/stringformat/deepclone/)() | Membuat klon mendalam dari objek `StringFormat` ini. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Membuang instance saat ini. |
| override [Equals](../../aspose.psd/stringformat/equals/)(object) | Periksa apakah objek-objek sama. |
| override [GetHashCode](../../aspose.psd/stringformat/gethashcode/)() | Dapatkan kode hash dari objek saat ini. |
| [SetTabStops](../../aspose.psd/stringformat/settabstops/)(float, float[]) | Mengatur tab stop untuk objek `StringFormat` ini. |
| override [ToString](../../aspose.psd/stringformat/tostring/)() | Mengonversi objek `StringFormat` ini menjadi string yang dapat dibaca manusia. |

### Lihat Juga

* class [DisposableObject](../disposableobject/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


