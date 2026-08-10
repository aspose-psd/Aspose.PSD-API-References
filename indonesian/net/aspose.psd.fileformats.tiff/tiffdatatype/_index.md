---
title: "Kelas TiffDataType"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Kelas Aspose.PSD.FileFormats.Tiff.TiffDataType. Tipe data tiff"
type: docs
weight: 4680
url: /id/net/aspose.psd.fileformats.tiff/tiffdatatype/
---
{{< psd/tize >}}
## TiffDataType class

Tipe data tiff.

```csharp
public abstract class TiffDataType : IComparable
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [AlignedDataSize](../../aspose.psd.fileformats.tiff/tiffdatatype/aligneddatasize/) { get; } | Mendapatkan ukuran data tambahan dalam byte (jika 12 byte tidak cukup untuk menampung data tag). |
| abstract [Count](../../aspose.psd.fileformats.tiff/tiffdatatype/count/) { get; } | Mendapatkan jumlah elemen. |
| abstract [DataSize](../../aspose.psd.fileformats.tiff/tiffdatatype/datasize/) { get; } | Mendapatkan ukuran data tambahan dalam byte (jika 12 byte tidak cukup untuk menampung data tag). |
| [Id](../../aspose.psd.fileformats.tiff/tiffdatatype/id/) { get; } | Mendapatkan representasi integer dari id tag. |
| [IsValid](../../aspose.psd.fileformats.tiff/tiffdatatype/isvalid/) { get; } | Mendapatkan nilai yang menunjukkan apakah data tag valid. Tag yang valid berisi data yang dapat dipertahankan. Tag yang tidak valid tidak dapat disimpan. |
| [TagId](../../aspose.psd.fileformats.tiff/tiffdatatype/tagid/) { get; } | Mendapatkan id tag. |
| abstract [TagType](../../aspose.psd.fileformats.tiff/tiffdatatype/tagtype/) { get; } | Mendapatkan tipe tag. |
| abstract [Value](../../aspose.psd.fileformats.tiff/tiffdatatype/value/) { get; set; } | Mendapatkan atau mengatur nilai yang dimiliki tipe data ini. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| static [ReadTag](../../aspose.psd.fileformats.tiff/tiffdatatype/readtag/)(TiffStreamReader, long) | Membaca data tag. |
| [CompareTo](../../aspose.psd.fileformats.tiff/tiffdatatype/compareto/)(object) | Membandingkan instance saat ini dengan objek lain dengan tipe yang sama dan mengembalikan integer yang menunjukkan apakah instance saat ini mendahului, mengikuti, atau berada pada posisi yang sama dalam urutan penyortiran dibandingkan objek lainnya. |
| virtual [DeepClone](../../aspose.psd.fileformats.tiff/tiffdatatype/deepclone/)() | Melakukan kloning mendalam dari instance ini. |
| override [ToString](../../aspose.psd.fileformats.tiff/tiffdatatype/tostring/)() | Mengembalikan String yang mewakili instance ini. |
| abstract [WriteAdditionalData](../../aspose.psd.fileformats.tiff/tiffdatatype/writeadditionaldata/)(TiffStreamWriter) | Menulis data tag tambahan. |
| [WriteTag](../../aspose.psd.fileformats.tiff/tiffdatatype/writetag/)(TiffStreamWriter, long) | Menulis data tag. |

### Lihat Juga

* namespace [Aspose.PSD.FileFormats.Tiff](../../aspose.psd.fileformats.tiff/)
* assembly [Aspose.PSD](../../)


