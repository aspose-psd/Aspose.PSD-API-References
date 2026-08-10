---
title: "Enum TextRenderingHint"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Enum Aspose.PSD.TextRenderingHint. Menentukan kualitas rendering teks."
type: docs
weight: 6200
url: /id/net/aspose.psd/textrenderinghint/
---
{{< psd/tize >}}
## TextRenderingHint enumeration

Menentukan kualitas perenderan teks.

```csharp
public enum TextRenderingHint
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| SystemDefault | `0` | Setiap karakter digambar menggunakan bitmap glifnya, dengan petunjuk rendering default sistem. Teks akan digambar menggunakan pengaturan penyamaran font apa pun yang dipilih pengguna untuk sistem. |
| SingleBitPerPixelGridFit | `1` | Setiap karakter digambar menggunakan bitmap glifnya. Hinting digunakan untuk meningkatkan penampilan karakter pada batang dan kelengkungan. |
| SingleBitPerPixel | `2` | Setiap karakter digambar menggunakan bitmap glifnya. Hinting tidak digunakan. |
| AntiAliasGridFit | `3` | Setiap karakter digambar menggunakan bitmap glif anti-aliased dengan hinting. Kualitas jauh lebih baik karena anti-aliasing, tetapi dengan biaya kinerja yang lebih tinggi. |
| AntiAlias | `4` | Setiap karakter digambar menggunakan bitmap glif anti-aliased tanpa hinting. Kualitas lebih baik karena anti-aliasing. Perbedaan lebar batang mungkin terlihat karena hinting dimatikan. |
| ClearTypeGridFit | `5` | Setiap karakter digambar menggunakan bitmap glif ClearType dengan hinting. Pengaturan kualitas tertinggi. Digunakan untuk memanfaatkan fitur font ClearType. |

### Lihat Juga

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


