---
title: "RawColorHelper.CreateCmyk8BitColor"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Metode RawColorHelper. Membuat warna CMYK 8bit per saluran"
type: docs
weight: 50
url: /id/net/aspose.psd.fileformats.psd.core.rawcolor/rawcolorhelper/createcmyk8bitcolor/
---
{{< psd/tize >}}
## RawColorHelper.CreateCmyk8BitColor method

Membuat warna CMYK 8-bit per saluran.

```csharp
public static RawColor CreateCmyk8BitColor(byte c, byte m, byte y, byte k)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| c | Byte | Nilai komponen sian (0-255). |
| m | Byte | Nilai komponen magenta (0-255). |
| y | Byte | Nilai komponen kuning (0-255). |
| k | Byte | Nilai komponen kunci (hitam) (0-255). |

### Nilai Kembalian

Instansi baru [`RawColor`](../../rawcolor/) yang mewakili warna CMYK.

## Catatan

Komponen warna dikemas ke dalam integer 32-bit dengan urutan: sian (bit 24-31), magenta (bit 16-23), kuning (bit 8-15), dan kunci/hitam (bit 0-7).

### Lihat Juga

* class [RawColor](../../rawcolor/)
* class [RawColorHelper](../)
* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../../)


