---
title: "Enum CompressionMethod"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Enum Aspose.PSD.FileFormats.Psd.CompressionMethod. Mendefinisikan metode kompresi yang digunakan untuk data gambar"
type: docs
weight: 1630
url: /id/net/aspose.psd.fileformats.psd/compressionmethod/
---
{{< psd/tize >}}
## CompressionMethod enumeration

Mendefinisikan metode kompresi yang digunakan untuk data gambar.

```csharp
public enum CompressionMethod : short
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| Raw | `0` | Tanpa kompresi. Data gambar disimpan sebagai byte mentah dalam urutan planar RGBA. Artinya pertama semua data R ditulis, kemudian semua data G, kemudian semua data B, dan akhirnya semua data A ditulis. |
| RLE | `1` | Data gambar terkompresi RLE dimulai dengan hitungan byte untuk semua baris pemindaian (baris * kanal), dengan setiap hitungan disimpan sebagai nilai dua byte. Data terkompresi RLE mengikuti, dengan setiap baris pemindaian dikompresi secara terpisah. Kompresi RLE adalah algoritma kompresi yang sama yang digunakan oleh rutin ROM Macintosh PackBits dan standar TIFF. |
| ZipWithoutPrediction | `2` | ZIP tanpa prediksi. |
| ZipWithPrediction | `3` | ZIP dengan prediksi. |

### Lihat Juga

* namespace [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../)


