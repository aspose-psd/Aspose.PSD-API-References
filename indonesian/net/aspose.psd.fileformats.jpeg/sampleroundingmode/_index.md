---
title: Enum SampleRoundingMode
second_title: Aspose.PSD untuk Referensi .NET API
description: Aspose.PSD.FileFormats.Jpeg.SampleRoundingMode enum. Menentukan cara di mana nilai nbit dikonversi menjadi nilai 8bit.
type: docs
weight: 1530
url: /id/net/aspose.psd.fileformats.jpeg/sampleroundingmode/
---
## SampleRoundingMode enumeration

Menentukan cara di mana nilai n-bit dikonversi menjadi nilai 8-bit.

```csharp
public enum SampleRoundingMode
```

### Nilai

| Nama | Nilai | Keterangan |
| --- | --- | --- |
| Extrapolate | `0` | Ekstrapolasi nilai 8-bit agar sesuai dengan n bit, di mana 1 &lt; n &lt; 8. Jumlah semua kemungkinan nilai 8-bit adalah 1 &lt;&lt; 8 = 256, dari 0 hingga 255. Jumlah semua kemungkinan nilai n-bit adalah 1 &lt;&lt; n, dari 0 hingga (1 &lt;&lt; n) - 1. Nilai n-bit yang paling masuk akal Vn sesuai dengan beberapa nilai 8-bit V8 sama dengan Vn = V8 &gt;&gt; (8 - N). |
| Truncate | `1` | Pangkas nilai 8-bit agar sesuai menjadi n bit, dengan 1 &lt; n &lt; 8. Jumlah semua kemungkinan nilai n-bit adalah 1 &lt;&lt; n, dari 0 hingga (1 &lt;&lt; n) - 1. Nilai n-bit paling masuk akal Vn sesuai dengan beberapa nilai 8-bit V8 sama dengan Vn = V8 &amp; ((1 &lt;&lt; n) - 1). |

### Lihat juga

* ruang nama [Aspose.PSD.FileFormats.Jpeg](../../aspose.psd.fileformats.jpeg/)
* perakitan [Aspose.PSD](../../)


