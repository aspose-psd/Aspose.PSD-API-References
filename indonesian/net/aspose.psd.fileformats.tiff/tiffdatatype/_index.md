---
title: Class TiffDataType
second_title: Aspose.PSD untuk Referensi .NET API
description: Aspose.PSD.FileFormats.Tiff.TiffDataType kelas. Tipe data tiff.
type: docs
weight: 4210
url: /id/net/aspose.psd.fileformats.tiff/tiffdatatype/
---
## TiffDataType class

Tipe data tiff.

```csharp
public abstract class TiffDataType : IComparable
```

## Properti

| Nama | Keterangan |
| --- | --- |
| [AlignedDataSize](../../aspose.psd.fileformats.tiff/tiffdatatype/aligneddatasize/) { get; } | Mendapatkan ukuran data tambahan dalam satuan byte (jika 12 byte tidak cukup untuk memuat data tag). |
| abstract [Count](../../aspose.psd.fileformats.tiff/tiffdatatype/count/) { get; } | Mendapat jumlah elemen. |
| abstract [DataSize](../../aspose.psd.fileformats.tiff/tiffdatatype/datasize/) { get; } | Mendapatkan ukuran data tambahan dalam satuan byte (jika 12 byte tidak cukup untuk memuat data tag). |
| [Id](../../aspose.psd.fileformats.tiff/tiffdatatype/id/) { get; } | Mendapat representasi integer id tag. |
| [IsValid](../../aspose.psd.fileformats.tiff/tiffdatatype/isvalid/) { get; } | Mendapat nilai yang menunjukkan apakah data tag valid. Tag yang valid berisi data yang mungkin dipertahankan. Tag yang tidak valid tidak dapat disimpan. |
| [TagId](../../aspose.psd.fileformats.tiff/tiffdatatype/tagid/) { get; } | Mendapatkan id tag. |
| abstract [TagType](../../aspose.psd.fileformats.tiff/tiffdatatype/tagtype/) { get; } | Mendapat jenis tag. |
| abstract [Value](../../aspose.psd.fileformats.tiff/tiffdatatype/value/) { get; set; } | Mendapat atau menyetel nilai yang terkandung dalam tipe data ini. |

## Metode

| Nama | Keterangan |
| --- | --- |
| static [ReadTag](../../aspose.psd.fileformats.tiff/tiffdatatype/readtag/)(TiffStreamReader, long) | Membaca data tag. |
| [CompareTo](../../aspose.psd.fileformats.tiff/tiffdatatype/compareto/)(object) | Membandingkan instance saat ini dengan objek lain dari jenis yang sama dan mengembalikan bilangan bulat yang menunjukkan apakah instance saat ini mendahului, mengikuti, atau terjadi di posisi yang sama dalam urutan seperti objek lainnya. |
| virtual [DeepClone](../../aspose.psd.fileformats.tiff/tiffdatatype/deepclone/)() | Melakukan klon dalam dari instance ini. |
| override [ToString](../../aspose.psd.fileformats.tiff/tiffdatatype/tostring/)() | Mengembalikan aString yang mewakili instance ini. |
| abstract [WriteAdditionalData](../../aspose.psd.fileformats.tiff/tiffdatatype/writeadditionaldata/)(TiffStreamWriter) | Menulis data tag tambahan. |
| [WriteTag](../../aspose.psd.fileformats.tiff/tiffdatatype/writetag/)(TiffStreamWriter, long) | Menulis data tag. |

### Lihat juga

* ruang nama [Aspose.PSD.FileFormats.Tiff](../../aspose.psd.fileformats.tiff/)
* perakitan [Aspose.PSD](../../)


