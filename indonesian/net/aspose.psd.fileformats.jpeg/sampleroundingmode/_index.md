---
title: "Enum SampleRoundingMode"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Enum Aspose.PSD.FileFormats.Jpeg.SampleRoundingMode. Mendefinisikan cara nilai nbit dikonversi menjadi nilai 8bit."
type: docs
weight: 1540
url: /id/net/aspose.psd.fileformats.jpeg/sampleroundingmode/
---
{{< psd/tize >}}
## SampleRoundingMode enumeration

Mendefinisikan cara di mana nilai n-bit dikonversi menjadi nilai 8-bit.

```csharp
public enum SampleRoundingMode
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| Extrapolate | `0` | Ekstrapolasi nilai 8-bit agar sesuai dengan n bit, dimana 1 &lt; n &lt; 8. Jumlah semua nilai 8-bit yang mungkin adalah 1 &lt;&lt; 8 = 256, dari 0 hingga 255. Jumlah semua nilai n-bit yang mungkin adalah 1 &lt;&lt; n, dari 0 hingga (1 &lt;&lt; n) - 1. Nilai n-bit yang paling masuk akal Vn yang sesuai dengan nilai 8-bit V8 adalah Vn = V8 &gt;&gt; (8 - n). |
| Truncate | `1` | Potong nilai 8-bit agar sesuai dengan n bit, dimana 1 &lt; n &lt; 8. Jumlah semua nilai n-bit yang mungkin adalah 1 &lt;&lt; n, dari 0 hingga (1 &lt;&lt; n) - 1. Nilai n-bit yang paling masuk akal Vn yang sesuai dengan nilai 8-bit V8 adalah Vn = V8 &amp; ((1 &lt;&lt; n) - 1). |

### Lihat Juga

* namespace [Aspose.PSD.FileFormats.Jpeg](../../aspose.psd.fileformats.jpeg/)
* assembly [Aspose.PSD](../../)


