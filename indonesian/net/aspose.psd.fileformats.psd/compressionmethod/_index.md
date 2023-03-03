---
title: Enum CompressionMethod
second_title: Aspose.PSD untuk Referensi .NET API
description: Aspose.PSD.FileFormats.Psd.CompressionMethod enum. Menentukan metode kompresi yang digunakan untuk data gambar.
type: docs
weight: 1620
url: /id/net/aspose.psd.fileformats.psd/compressionmethod/
---
## CompressionMethod enumeration

Menentukan metode kompresi yang digunakan untuk data gambar.

```csharp
public enum CompressionMethod : short
```

### Nilai

| Nama | Nilai | Keterangan |
| --- | --- | --- |
| Raw | `0` | Tanpa kompresi. Data gambar disimpan sebagai byte mentah dalam urutan planar RGBA. Artinya, pertama semua data R ditulis, lalu semua G ditulis, lalu semua B dan terakhir semua data A ditulis. |
| RLE | `1` | RLE mengompresi data gambar dimulai dengan jumlah byte untuk semua garis pemindaian (baris * saluran), dengan setiap hitungan disimpan sebagai nilai dua byte. Data terkompresi RLE mengikuti, dengan setiap baris pemindaian dikompresi secara terpisah. Kompresi RLE adalah algoritme kompresi yang sama yang digunakan oleh PackBits rutin ROM Macintosh dan standar TIFF. |
| ZipWithoutPrediction | `2` | ZIP tanpa prediksi. |
| ZipWithPrediction | `3` | ZIP dengan prediksi. |

### Lihat juga

* ruang nama [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* perakitan [Aspose.PSD](../../)


