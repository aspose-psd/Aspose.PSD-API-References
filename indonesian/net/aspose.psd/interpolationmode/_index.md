---
title: "Enum InterpolationMode"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Aspose.PSD.InterpolationMode enum. Enumerasi InterpolationMode menentukan algoritma yang digunakan ketika gambar diperbesar atau diputar."
type: docs
weight: 5520
url: /id/net/aspose.psd/interpolationmode/
---
{{< psd/tize >}}
## InterpolationMode enumeration

Enumerasi `InterpolationMode` menentukan algoritma yang digunakan ketika gambar diperbesar atau diputar.

```csharp
public enum InterpolationMode
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| Invalid | `-1` | Mode interpolasi tidak valid. |
| Default | `0` | Menentukan mode default. |
| Low | `1` | Menentukan interpolasi kualitas rendah. |
| High | `2` | Menentukan interpolasi kualitas tinggi. |
| Bilinear | `3` | Menentukan interpolasi bilinear. Tidak ada pra‑penyaringan yang dilakukan. Mode ini tidak cocok untuk memperkecil gambar di bawah 50 persen dari ukuran aslinya. |
| Bicubic | `4` | Menentukan interpolasi bikubik. Tidak ada pra‑penyaringan yang dilakukan. Mode ini tidak cocok untuk memperkecil gambar di bawah 25 persen dari ukuran aslinya. |
| NearestNeighbor | `5` | Menentukan interpolasi tetangga terdekat. |
| HighQualityBilinear | `6` | Menentukan interpolasi bilinear berkualitas tinggi. Pra‑penyaringan dilakukan untuk memastikan pengecilan berkualitas tinggi. |
| HighQualityBicubic | `7` | Menentukan interpolasi bikubik berkualitas tinggi. Pra‑penyaringan dilakukan untuk memastikan pengecilan berkualitas tinggi. Mode ini menghasilkan gambar yang diubah dengan kualitas tertinggi. |

### Lihat Juga

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


