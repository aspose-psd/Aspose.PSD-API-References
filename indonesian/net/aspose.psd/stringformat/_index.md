---
title: Class StringFormat
second_title: Aspose.PSD untuk Referensi .NET API
description: Aspose.PSD.StringFormat kelas. Mengenkapsulasi informasi tata letak teks seperti perataan orientasi dan perhentian tab manipulasi tampilan seperti penyisipan elipsis dan substitusi digit nasional dan fitur OpenType. Kelas ini tidak dapat diwariskan.
type: docs
weight: 5670
url: /id/net/aspose.psd/stringformat/
---
## StringFormat class

Mengenkapsulasi informasi tata letak teks (seperti perataan, orientasi, dan perhentian tab), manipulasi tampilan (seperti penyisipan elipsis dan substitusi digit nasional) dan fitur OpenType. Kelas ini tidak dapat diwariskan.

```csharp
public sealed class StringFormat : DisposableObject
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [StringFormat](stringformat/#constructor)() | Menginisialisasi yang baru`StringFormat` objek. |
| [StringFormat](stringformat/#constructor_1)(StringFormat) | Menginisialisasi yang baru`StringFormat` objek dari yang ditentukan ada`StringFormat` objek. |
| [StringFormat](stringformat/#constructor_2)(StringFormatFlags) | Menginisialisasi yang baru`StringFormat` objek dengan yang ditentukan[`StringFormatFlags`](../stringformatflags/) pencacahan dan bahasa. |

## Properti

| Nama | Keterangan |
| --- | --- |
| static [GenericDefault](../../aspose.psd/stringformat/genericdefault/) { get; } | Mendapat default umum`StringFormat` objek. |
| static [GenericTypographic](../../aspose.psd/stringformat/generictypographic/) { get; } | Mendapat tipografi umum`StringFormat` objek. |
| [Alignment](../../aspose.psd/stringformat/alignment/) { get; set; } | Mendapat atau menyetel informasi perataan teks pada bidang vertikal. |
| [DigitSubstitutionLanguage](../../aspose.psd/stringformat/digitsubstitutionlanguage/) { get; set; } | Mendapat atau mengatur bahasa yang digunakan saat digit lokal diganti dengan digit barat. |
| [DigitSubstitutionMethod](../../aspose.psd/stringformat/digitsubstitutionmethod/) { get; set; } | Mendapat atau menetapkan metode yang akan digunakan untuk penggantian digit. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Mendapat nilai yang menunjukkan apakah instance ini dibuang. |
| [FirstTabOffset](../../aspose.psd/stringformat/firsttaboffset/) { get; } | Mendapat jumlah spasi antara awal baris teks dan perhentian tab pertama. |
| [FormatFlags](../../aspose.psd/stringformat/formatflags/) { get; set; } | Mendapat atau menyetel a[`StringFormatFlags`](../stringformatflags/) pencacahan yang berisi informasi pemformatan. |
| [HotkeyPrefix](../../aspose.psd/stringformat/hotkeyprefix/) { get; set; } | Mendapat atau menyetel[`HotkeyPrefix`](../hotkeyprefix/) keberatan untuk ini`StringFormat` objek. |
| [LineAlignment](../../aspose.psd/stringformat/linealignment/) { get; set; } | Mendapat atau mengatur perataan garis pada bidang horizontal. |
| [TabStops](../../aspose.psd/stringformat/tabstops/) { get; } | Mendapat larik jarak antara perhentian tab dalam satuan yang ditentukan oleh[`PageUnit`](../graphics/pageunit/) properti. |
| [Trimming](../../aspose.psd/stringformat/trimming/) { get; set; } | Mendapat atau menyetel[`StringTrimming`](../stringtrimming/) pencacahan untuk ini`StringFormat` objek. |

## Metode

| Nama | Keterangan |
| --- | --- |
| [DeepClone](../../aspose.psd/stringformat/deepclone/)() | Membuat klon yang dalam dari ini`StringFormat` objek. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Membuang instance saat ini. |
| [SetTabStops](../../aspose.psd/stringformat/settabstops/)(float, float[]) | Menyetel perhentian tab untuk ini`StringFormat` objek. |
| override [ToString](../../aspose.psd/stringformat/tostring/)() | Mengubah ini`StringFormat` menolak string yang dapat dibaca manusia. |

### Lihat juga

* class [DisposableObject](../disposableobject/)
* ruang nama [Aspose.PSD](../../aspose.psd/)
* perakitan [Aspose.PSD](../../)


