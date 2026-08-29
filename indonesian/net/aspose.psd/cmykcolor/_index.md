---
title: "Struktur CmykColor"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Struktur Aspose.PSD.CmykColor. Warna CMYK dari piksel"
type: docs
weight: 270
url: /id/net/aspose.psd/cmykcolor/
---
{{< psd/tize >}}
## CmykColor structure

Warna CMYK piksel.

```csharp
public struct CmykColor
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| static [Empty](../../aspose.psd/cmykcolor/empty/) { get; } | Mendapatkan nilai kosong. |
| [C](../../aspose.psd/cmykcolor/c/) { get; } | Mendapatkan nilai komponen cyan dari struktur [`Color`](../color/) ini. |
| [IsEmpty](../../aspose.psd/cmykcolor/isempty/) { get; } | Mendapatkan nilai yang menunjukkan apakah struktur [`Color`](../color/) ini belum diinisialisasi. |
| [K](../../aspose.psd/cmykcolor/k/) { get; } | Mendapatkan nilai komponen hitam dari struktur [`Color`](../color/) ini. |
| [M](../../aspose.psd/cmykcolor/m/) { get; } | Mendapatkan nilai komponen magenta dari struktur [`Color`](../color/) ini. |
| [Y](../../aspose.psd/cmykcolor/y/) { get; } | Mendapatkan nilai komponen kuning dari struktur [`Color`](../color/) ini. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| static [FromParams](../../aspose.psd/cmykcolor/fromparams/)(int, int, int, int) | Membuat struktur `CmykColor` dari nilai cyan, magenta, kuning, dan hitam 32-bit. Metode ini sudah usang. Silakan gunakan [`FromComponents`](../cmykcolorhelper/fromcomponents/) yang lebih efektif. |
| static [ToCmyk](../../aspose.psd/cmykcolor/tocmyk/#tocmyk)(int) | Konversi dari ARGB 32-bit ke CMYKColor. Metode ini sudah usang. Silakan gunakan [`ToCmyk`](../cmykcolorhelper/tocmyk/) yang lebih efektif. |
| override [Equals](../../aspose.psd/cmykcolor/equals/)(object) | Menentukan apakah Object yang ditentukan, sama dengan instance ini. |
| override [GetHashCode](../../aspose.psd/cmykcolor/gethashcode/)() | Mendapatkan kode hash. |
| [ToValue](../../aspose.psd/cmykcolor/tovalue/)() | Nilai to. |
| static [ToArgb32](../../aspose.psd/cmykcolor/toargb32/)(CmykColor[]) | Konversi dari CMYKColor ke Warna ARGB 32-bit menggunakan konversi icc dengan profil default. Metode ini sudah usang. Silakan gunakan [`ToArgb32`](../cmykcolorhelper/toargb32/) yang lebih efektif. |
| static [ToCmyk](../../aspose.psd/cmykcolor/tocmyk/#tocmyk_1)(int[]) | Konversi dari warna ARGB 32-bit ke CMYKColor. Metode ini sudah usang. Silakan gunakan [`ToCmyk`](../cmykcolorhelper/tocmyk/) yang lebih efektif. |
| static [ToColor](../../aspose.psd/cmykcolor/tocolor/#tocolor)(CmykColor) | Konversi dari CMYKColor ke Color. Metode ini sudah usang. Silakan gunakan [`ToArgb`](../cmykcolorhelper/toargb/) yang lebih efektif. |
| static [ToColor](../../aspose.psd/cmykcolor/tocolor/#tocolor_1)(CmykColor[]) | Konversi dari CMYKColor ke Color menggunakan konversi icc dengan profil default. Metode ini sudah usang. Silakan gunakan [`ToArgb`](../cmykcolorhelper/toargb/) yang lebih efektif. |
| static [ToColorIcc](../../aspose.psd/cmykcolor/tocoloricc/#tocoloricc)(CmykColor) | Konversi dari CMYKColor ke Color menggunakan konversi icc dengan profil default. Metode ini sudah usang. Silakan gunakan [`ToArgbIcc`](../cmykcolorhelper/toargbicc/) yang lebih efektif. |
| static [ToColorIcc](../../aspose.psd/cmykcolor/tocoloricc/#tocoloricc_2)(CmykColor[]) | Konversi dari CMYKColor ke Color menggunakan konversi icc dengan profil default. Metode ini sudah usang. Silakan gunakan [`ToArgbIcc`](../cmykcolorhelper/toargbicc/) yang lebih efektif. |
| static [ToColorIcc](../../aspose.psd/cmykcolor/tocoloricc/#tocoloricc_1)(CmykColor, Stream, Stream) | Konversi dari CMYKColor ke Color menggunakan konversi icc. Metode ini sudah usang. Silakan gunakan [`ToArgbIcc`](../cmykcolorhelper/toargbicc/) yang lebih efektif. |
| static [ToColorIcc](../../aspose.psd/cmykcolor/tocoloricc/#tocoloricc_3)(CmykColor[], Stream, Stream) | Konversi dari CMYKColor ke Color menggunakan konversi icc. Metode ini sudah usang. Silakan gunakan [`ToArgbIcc`](../cmykcolorhelper/toargbicc/) yang lebih efektif. |

### Lihat Juga

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


