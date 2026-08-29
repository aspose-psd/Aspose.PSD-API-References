---
title: "Enum TiffTags"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Aspose.PSD.FileFormats.Tiff.Enums.TiffTags enum. Enum tag tiff"
type: docs
weight: 4640
url: /id/net/aspose.psd.fileformats.tiff.enums/tifftags/
---
{{< psd/tize >}}
## TiffTags enumeration

Enum tag tiff.

```csharp
public enum TiffTags
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| SubFileType | `254` | Deskriptor data subfile. |
| OsubfileType | `255` | [obsoleted by TIFF rev. 5.0] Jenis data dalam subfile. |
| ImageWidth | `256` | Lebar gambar dalam piksel. |
| ImageLength | `257` | Tinggi gambar dalam piksel. |
| BitsPerSample | `258` | Bit per saluran (sampel). |
| Compression | `259` | Teknik kompresi data. |
| Photometric | `262` | Interpretasi fotometrik. |
| Thresholding | `263` | [obsoleted by TIFF rev. 5.0] Ambang yang digunakan pada data. |
| CellWidth | `264` | [obsoleted by TIFF rev. 5.0] Lebar matriks dithering. |
| CellLength | `265` | [obsoleted by TIFF rev. 5.0] Tinggi matriks dithering |
| FillOrder | `266` | Urutan data dalam satu byte. |
| DocumentName | `269` | Nama dokumen yang menyimpan gambar. |
| ImageDescription | `270` | Informasi tentang gambar. |
| Make | `271` | Nama produsen pemindai. |
| Model | `272` | Nama/nomor model pemindai. |
| StripOffsets | `273` | Offset ke strip data. |
| Orientation | `274` | [usang sejak TIFF rev. 5.0] Orientasi gambar. |
| SamplesPerPixel | `277` | Sampel per piksel. |
| RowsPerStrip | `278` | Baris per strip data. |
| StripByteCounts | `279` | Jumlah byte untuk strip. |
| MinSampleValue | `280` | [usang sejak TIFF rev. 5.0] Nilai sampel minimum. |
| MaxSampleValue | `281` | [usang sejak TIFF rev. 5.0] Nilai sampel maksimum. |
| Xresolution | `282` | Piksel/resolusi pada x. |
| Yresolution | `283` | Piksel/resolusi pada y. |
| PlanarConfig | `284` | Organisasi penyimpanan. |
| PageName | `285` | Nama halaman tempat gambar berasal. |
| Xposition | `286` | Offset halaman X gambar sisi kiri. |
| Yposition | `287` | Offset halaman Y gambar sisi kiri. |
| FreeOffsets | `288` | [usang sejak TIFF rev. 5.0] Offset byte ke blok bebas. |
| FreeByteCounts | `289` | [usang sejak TIFF rev. 5.0] Ukuran blok bebas. |
| GrayResponseUnit | `290` | [usang sejak TIFF rev. 6.0] Akurasi kurva skala abu-abu. |
| GrayResponseCurve | `291` | [usang sejak TIFF rev. 6.0] Kurva respons skala abu-abu. |
| T4Options | `292` | Nama alias yang tepat TIFF 6.0 untuk GROUP3OPTIONS. Opsi untuk pengkodean faks CCITT Group 3. 32 bit flag. |
| T6Options | `293` | Opsi untuk pengkodean faks CCITT Group 4. 32 bit flag. Nama alias yang tepat TIFF 6.0 untuk GROUP4OPTIONS. |
| ResolutionUnit | `296` | Satuan resolusi. |
| PageNumber | `297` | Nomor halaman dari multi-halaman. |
| ColorResponseUnit | `300` | [usang oleh TIFF rev. 6.0] Akurasi kurva warna. |
| TransferFunction | `301` | Info kolorimetri. |
| Software | `305` | Nama &amp; rilis. |
| DateTime | `306` | Tanggal dan waktu pembuatan. |
| Artist | `315` | Pembuat gambar. |
| HostComputer | `316` | Mesin tempat dibuat. |
| Predictor | `317` | Skema prediksi w/ LZW. |
| WhitePoint | `318` | Titik putih gambar. |
| PrimaryChromaticities | `319` | Kromatisitas utama. |
| ColorMap | `320` | Peta RGB untuk gambar pallette. |
| HalftoneHints | `321` | Info sorotan + bayangan. |
| TileWidth | `322` | Lebar ubin dalam piksel. |
| TileLength | `323` | Tinggi ubin dalam piksel. |
| TileOffsets | `324` | Offset ke ubin data. |
| TileByteCounts | `325` | Hitungan byte untuk ubin. |
| BadFaxLines | `326` | Baris dengan jumlah piksel salah. |
| CleanFaxData | `327` | Info baris yang diregenerasi. |
| ConsecutiveBadFaxLines | `328` | Baris buruk berurutan maksimum. |
| SubIfd | `330` | Deskriptor subgambar. |
| InkSet | `332` | Tinta dalam gambar terpisah. |
| InkNames | `333` | Nama ASCII tinta. |
| NumberOfInks | `334` | Jumlah tinta. |
| DotRange | `336` | Kode titik 0% dan 100%. |
| TargetPrinter | `337` | Target pemisahan. |
| ExtraSamples | `338` | Informasi tentang sampel tambahan. |
| SampleFormat | `339` | Format sampel data. |
| SminSampleValue | `340` | Variabel MinSampleValue. |
| SmaxSampleValue | `341` | Variabel MaxSampleValue. |
| TransferRange | `342` | Variabel TransferRange |
| ClipPath | `343` | ClipPath. Diperkenalkan setelah TIFF rev 6.0 oleh Adobe TIFF technote 2. |
| Xclippathunits | `344` | XClipPathUnits. Diperkenalkan setelah TIFF rev 6.0 oleh Adobe TIFF technote 2. |
| Yclippathunits | `345` | YClipPathUnits. Diperkenalkan setelah TIFF rev 6.0 oleh Adobe TIFF technote 2. |
| Indexed | `346` | Indexed. Diperkenalkan setelah TIFF rev 6.0 oleh Adobe TIFF Technote 3. |
| JpegTables | `347` | Aliran tabel JPEG. Diperkenalkan setelah TIFF rev 6.0. |
| OpiProxy | `351` | OPI Proxy. Diperkenalkan setelah TIFF rev 6.0 oleh Adobe TIFF technote. |
| JpegProc | `512` | [diusulkan oleh Technical Note #2 yang menentukan skema JPEG-in-TIFF yang direvisi] algoritma pemrosesan JPEG. |
| JpegInerchangeFormat | `513` | [diusulkan oleh Technical Note #2 yang menentukan skema JPEG-in-TIFF yang direvisi] Penunjuk ke penanda SOI. |
| JpegInterchangeFormatLength | `514` | [diusulkan oleh Technical Note #2 yang menentukan skema JPEG-in-TIFF yang direvisi] panjang aliran JFIF |
| JpegRestartInterval | `515` | [diusulkan oleh Technical Note #2 yang menentukan skema JPEG-in-TIFF yang direvisi] panjang interval restart. |
| JpegLosslessPredictors | `517` | [diusulkan oleh Technical Note #2 yang menentukan skema JPEG-in-TIFF yang direvisi] prediktor proses lossless. |
| JpegPointTransform | `518` | [diusulkan oleh Technical Note #2 yang menentukan skema JPEG-in-TIFF yang direvisi] transformasi titik lossless. |
| JpegQTables | `519` | [diusulkan oleh Technical Note #2 yang menentukan skema JPEG-in-TIFF yang direvisi] offset matriks Q. |
| JpegDCtables | `520` | [diusulkan oleh Technical Note #2 yang menentukan skema JPEG-in-TIFF yang direvisi] offset tabel DCT. |
| JpegACtables | `521` | [diusulkan oleh Technical Note #2 yang menentukan skema JPEG-in-TIFF yang direvisi] offset koefisien AC. |
| YcbcrCoefficients | `529` | Transformasi RGB -> YCbCr. |
| YcbcrSubSampling | `530` | Faktor subsampling YCbCr. |
| YcbcrPositioning | `531` | Posisi sub-sampel. |
| ReferenceBlackWhite | `532` | Info kolorimetri. |
| XmlPacket | `700` | Paket XML. Diperkenalkan setelah TIFF rev 6.0 oleh Adobe XMP Specification, Januari 2004. |
| OpiImageid | `32781` | OPI ImageID. Diperkenalkan setelah TIFF rev 6.0 oleh Adobe TIFF technote. |
| Refpts | `32953` | Titik referensi gambar. Tag pribadi terdaftar ke Island Graphics. |
| Copyright | `33432` | String hak cipta. Tag ini terdaftar dalam TIFF rev. 6.0 dengan kepemilikan yang tidak diketahui. |
| PhotoshopResources | `34377` | Sumber daya gambar Photoshop. |
| IccProfile | `34675` | Profil perangkat ICC yang disematkan |
| ExifIfdPointer | `34665` | Penunjuk ke Exif IFD. |
| XPTitle | `40091` | Informasi tentang gambar, digunakan oleh Windows Explorer. XPTitle diabaikan oleh Windows Explorer jika tag ImageDescription ada. |
| XPComment | `40092` | Komentar pada gambar, digunakan oleh Windows Explorer. |
| XPAuthor | `40093` | Penulis gambar, digunakan oleh Windows Explorer. XPAuthor diabaikan oleh Windows Explorer jika tag Artist ada. |
| XPKeywords | `40094` | Kata kunci gambar, digunakan oleh Windows Explorer. |
| XPSubject | `40095` | Subjek gambar, digunakan oleh Windows Explorer. |

### Lihat Juga

* namespace [Aspose.PSD.FileFormats.Tiff.Enums](../../aspose.psd.fileformats.tiff.enums/)
* assembly [Aspose.PSD](../../)


