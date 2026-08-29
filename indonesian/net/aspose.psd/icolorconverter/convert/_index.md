---
title: "IColorConverter.Convert"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Metode IColorConverter. Mengonversi data yang diberikan ke format output"
type: docs
weight: 10
url: /id/net/aspose.psd/icolorconverter/convert/
---
{{< psd/tize >}}
## IColorConverter.Convert method

Mengonversi data yang diberikan ke format output.

```csharp
public int Convert(PixelDataFormat sourceFormat, byte[] data, int offset, int bitStart, 
    int samplesCount, int linesCount, PixelDataFormat destFormat, byte[] outputData, 
    int outputOffset)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceFormat | PixelDataFormat | Format sumber. |
| data | Byte[] | Data sumber. |
| offset | Int32 | Offset dalam byte dimana penyalinan data harus dimulai. |
| bitStart | Int32 | Awal bit. Catatan nilai ini tidak selaras byte, melainkan bit aktual dimana penyalinan harus dimulai. |
| samplesCount | Int32 | Jumlah sampel. |
| linesCount | Int32 | Jumlah baris. |
| destFormat | PixelDataFormat | Format tujuan. |
| outputData | Byte[] | Data output. |
| outputOffset | Int32 | Offset output dimana penyalinan data harus dimulai. |

### Nilai Kembalian

Jumlah byte yang dikonversi.

### Lihat Juga

* class [PixelDataFormat](../../pixeldataformat/)
* interface [IColorConverter](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


