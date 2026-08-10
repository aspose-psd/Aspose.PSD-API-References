---
title: "RawColorHelper.CreateCmyk16BitBitColor"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Metode RawColorHelper. Membuat warna CMYK 16bit per saluran"
type: docs
weight: 40
url: /id/net/aspose.psd.fileformats.psd.core.rawcolor/rawcolorhelper/createcmyk16bitbitcolor/
---
{{< psd/tize >}}
## RawColorHelper.CreateCmyk16BitBitColor method

Membuat warna CMYK 16-bit per saluran.

```csharp
public static RawColor CreateCmyk16BitBitColor(ushort c, ushort m, ushort y, ushort k)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| c | UInt16 | Nilai komponen sian (0-65535). |
| m | UInt16 | Nilai komponen magenta (0-65535). |
| y | UInt16 | Nilai komponen kuning (0-65535). |
| k | UInt16 | Nilai komponen kunci (hitam) (0-65535). |

### Nilai Kembalian

Instansi baru [`RawColor`](../../rawcolor/) yang mewakili warna CMYK.

## Catatan

Komponen warna dikemas ke dalam integer 64-bit dengan urutan: sian (bit 48-63), magenta (bit 32-47), kuning (bit 16-31), dan kunci/hitam (bit 0-15).

### Lihat Juga

* class [RawColor](../../rawcolor/)
* class [RawColorHelper](../)
* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../../)


