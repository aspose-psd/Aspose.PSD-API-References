---
title: "IColorConverter"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Pengonversi warna."
type: docs
weight: 116
url: /id/java/com.aspose.psd/icolorconverter/
---
```
public interface IColorConverter
```

Pengonversi warna.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [convert(PixelDataFormat sourceFormat, byte[] data, int offset, int bitStart, int samplesCount, int linesCount, PixelDataFormat destFormat, byte[] outputData, int outputOffset)](#convert-com.aspose.psd.PixelDataFormat-byte---int-int-int-int-com.aspose.psd.PixelDataFormat-byte---int-) | Mengonversi data yang diberikan ke format keluaran. |
### convert(PixelDataFormat sourceFormat, byte[] data, int offset, int bitStart, int samplesCount, int linesCount, PixelDataFormat destFormat, byte[] outputData, int outputOffset) {#convert-com.aspose.psd.PixelDataFormat-byte---int-int-int-int-com.aspose.psd.PixelDataFormat-byte---int-}
```
public abstract int convert(PixelDataFormat sourceFormat, byte[] data, int offset, int bitStart, int samplesCount, int linesCount, PixelDataFormat destFormat, byte[] outputData, int outputOffset)
```


Mengonversi data yang diberikan ke format keluaran.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceFormat | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | Format sumber. |
| data | byte[] | Data sumber. |
| offset | int | Offset dalam byte dimana penyalinan data harus dimulai. |
| bitStart | int | Awal bit. Catatan nilai ini bukan nilai yang selaras byte, melainkan bit aktual dimana penyalinan harus dimulai. |
| samplesCount | int | Jumlah sampel. |
| linesCount | int | Jumlah baris. |
| destFormat | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | Format tujuan. |
| outputData | byte[] | Data keluaran. |
| outputOffset | int | Offset keluaran dimana penyalinan data harus dimulai. |

**Returns:**
int - Jumlah byte yang dikonversi.
