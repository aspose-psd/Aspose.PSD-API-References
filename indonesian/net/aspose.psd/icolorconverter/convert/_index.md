---
title: IColorConverter.Convert
second_title: Aspose.PSD untuk Referensi .NET API
description: IColorConverter metode. Mengonversi data yang diteruskan ke format keluaran.
type: docs
weight: 10
url: /id/net/aspose.psd/icolorconverter/convert/
---
## IColorConverter.Convert method

Mengonversi data yang diteruskan ke format keluaran.

```csharp
public int Convert(PixelDataFormat sourceFormat, byte[] data, int offset, int bitStart, 
    int samplesCount, int linesCount, PixelDataFormat destFormat, byte[] outputData, 
    int outputOffset)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| sourceFormat | PixelDataFormat | Format sumber. |
| data | Byte[] | Data sumber. |
| offset | Int32 | Offset dalam byte tempat penyalinan data harus dimulai. |
| bitStart | Int32 | Sedikit mulai. Perhatikan bahwa nilai ini bukan nilai yang diselaraskan byte, melainkan ini adalah bit aktual tempat penyalinan harus dimulai. |
| samplesCount | Int32 | Jumlah sampel. |
| linesCount | Int32 | Garis dihitung. |
| destFormat | PixelDataFormat | Format tujuan. |
| outputData | Byte[] | Data keluaran. |
| outputOffset | Int32 | Offset keluaran tempat penyalinan data harus dimulai. |

### Nilai Pengembalian

Jumlah byte yang dikonversi.

### Lihat juga

* class [PixelDataFormat](../../pixeldataformat/)
* interface [IColorConverter](../)
* ruang nama [Aspose.PSD](../../icolorconverter/)
* perakitan [Aspose.PSD](../../../)


