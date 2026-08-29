---
title: "RawColorHelper.CreateArgb8BitColor"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Metode RawColorHelper. Membuat warna ARGB 8bit per kanal"
type: docs
weight: 30
url: /id/net/aspose.psd.fileformats.psd.core.rawcolor/rawcolorhelper/createargb8bitcolor/
---
{{< psd/tize >}}
## CreateArgb8BitColor(byte, byte, byte, byte) {#createargb8bitcolor_1}

Membuat warna ARGB dengan 8-bit per saluran.

```csharp
public static RawColor CreateArgb8BitColor(byte a, byte r, byte g, byte b)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| a | Byte | Nilai komponen alfa (0-255). |
| r | Byte | Nilai komponen merah (0-255). |
| g | Byte | Nilai komponen hijau (0-255). |
| b | Byte | Nilai komponen biru (0-255). |

### Nilai Kembalian

Instansi baru [`RawColor`](../../rawcolor/) yang mewakili warna ARGB.

## Catatan

Komponen warna dikemas ke dalam integer 32-bit dengan urutan: alfa (bit 24-31), merah (bit 16-23), hijau (bit 8-15), dan biru (bit 0-7).

### Lihat Juga

* class [RawColor](../../rawcolor/)
* class [RawColorHelper](../)
* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../../)

---

## CreateArgb8BitColor(Color) {#createargb8bitcolor}

Membuat warna ARGB dengan 8-bit per saluran dari Drawing.Color

```csharp
public static RawColor CreateArgb8BitColor(Color drawingColor)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| drawingColor | Warna | Warna System.Drawing |

### Nilai Kembalian

Instansi baru [`RawColor`](../../rawcolor/) yang mewakili warna ARGB.

## Catatan

Komponen warna dikemas ke dalam integer 32-bit dengan urutan: alfa (bit 24-31), merah (bit 16-23), hijau (bit 8-15), dan biru (bit 0-7).

### Lihat Juga

* class [RawColor](../../rawcolor/)
* struct [Color](../../../aspose.psd/color/)
* class [RawColorHelper](../)
* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../../)


