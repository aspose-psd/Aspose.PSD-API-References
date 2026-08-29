---
title: "Kelas TiffOptions"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Kelas Aspose.PSD.ImageOptions.TiffOptions. Opsi format file tiff. Perhatikan bahwa tag lebar dan tinggi akan ditimpa saat pembuatan gambar oleh parameter lebar dan tinggi sehingga tidak perlu menyebutkannya secara langsung. Perhatikan bahwa banyak opsi mengembalikan nilai default tetapi itu tidak berarti bahwa opsi ini diatur secara eksplisit sebagai nilai tag. Untuk memverifikasi keberadaan tag, gunakan properti Tags atau metode IsTagPresent yang sesuai."
type: docs
weight: 5430
url: /id/net/aspose.psd.imageoptions/tiffoptions/
---
{{< psd/tize >}}
## TiffOptions class

Opsi format file tiff. Perhatikan bahwa tag lebar dan tinggi akan ditimpa saat pembuatan gambar oleh parameter lebar dan tinggi sehingga tidak perlu menyebutkannya secara langsung. Perhatikan bahwa banyak opsi mengembalikan nilai default tetapi itu tidak berarti bahwa opsi ini diatur secara eksplisit sebagai nilai tag. Untuk memverifikasi keberadaan tag, gunakan properti Tags atau metode IsTagPresent yang sesuai.

```csharp
public class TiffOptions : ImageOptionsBase
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [TiffOptions](tiffoptions/#constructor_2)(TiffDataType[]) | Menginisialisasi instance baru dari kelas `TiffOptions`. |
| [TiffOptions](tiffoptions/#constructor)(TiffExpectedFormat) | Menginisialisasi instance baru dari kelas `TiffOptions`. Secara default konvensi little endian digunakan. |
| [TiffOptions](tiffoptions/#constructor_3)(TiffOptions) | Menginisialisasi instance baru dari kelas `TiffOptions`. |
| [TiffOptions](tiffoptions/#constructor_1)(TiffExpectedFormat, TiffByteOrder) | Menginisialisasi instance baru dari kelas `TiffOptions`. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [AlphaStorage](../../aspose.psd.imageoptions/tiffoptions/alphastorage/) { get; set; } | Mendapatkan atau mengatur opsi penyimpanan alfa. Opsi selain Unspecified digunakan ketika ada lebih dari 3 [`SamplesPerPixel`](./samplesperpixel/) yang didefinisikan. |
| [Artist](../../aspose.psd.imageoptions/tiffoptions/artist/) { get; set; } | Mendapatkan atau mengatur artis. |
| [BitsPerPixel](../../aspose.psd.imageoptions/tiffoptions/bitsperpixel/) { get; } | Mendapatkan bit per piksel. |
| [BitsPerSample](../../aspose.psd.imageoptions/tiffoptions/bitspersample/) { get; set; } | Mendapatkan atau mengatur bit per sampel. |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | Mendapatkan atau mengatur petunjuk ukuran buffer yang didefinisikan sebagai ukuran maksimum yang diizinkan untuk semua buffer internal. |
| [ByteOrder](../../aspose.psd.imageoptions/tiffoptions/byteorder/) { get; set; } | Mendapatkan atau mengatur nilai yang menunjukkan urutan byte tiff. |
| [ColorMap](../../aspose.psd.imageoptions/tiffoptions/colormap/) { get; set; } | Mendapatkan atau mengatur peta warna. |
| [CompressedQuality](../../aspose.psd.imageoptions/tiffoptions/compressedquality/) { get; set; } | Mendapatkan atau mengatur kualitas gambar terkompresi. Digunakan dengan kompresi Jpeg. |
| [Compression](../../aspose.psd.imageoptions/tiffoptions/compression/) { get; set; } | Mendapatkan atau mengatur kompresi. |
| [Copyright](../../aspose.psd.imageoptions/tiffoptions/copyright/) { get; set; } | Mendapatkan atau mengatur hak cipta. |
| [DateTime](../../aspose.psd.imageoptions/tiffoptions/datetime/) { get; set; } | Mendapatkan atau mengatur tanggal dan waktu. |
| [DefaultMemoryAllocationLimit](../../aspose.psd.imageoptions/tiffoptions/defaultmemoryallocationlimit/) { get; set; } | Mendapatkan atau mengatur batas alokasi memori default. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | Mendapatkan atau mengatur font pengganti default (font yang akan digunakan untuk menggambar teks saat mengekspor ke raster, jika font lapisan yang ada dalam file PSD tidak tersedia di sistem). Untuk memperoleh nama font default yang tepat dapat digunakan cuplikan kode berikut: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Mendapatkan nilai yang menunjukkan apakah instansi ini telah dibuang. |
| [DocumentName](../../aspose.psd.imageoptions/tiffoptions/documentname/) { get; set; } | Mendapatkan atau mengatur nama dokumen. |
| [ExifIfd](../../aspose.psd.imageoptions/tiffoptions/exififd/) { get; } | Mendapatkan atau mengatur penunjuk ke EXIF IFD. |
| [FaxT4Options](../../aspose.psd.imageoptions/tiffoptions/faxt4options/) { get; set; } | Mendapatkan atau mengatur opsi fax t4. |
| [FileStandard](../../aspose.psd.imageoptions/tiffoptions/filestandard/) { get; set; } | Mendapatkan atau mengatur standar file TIFF. |
| [FillOrder](../../aspose.psd.imageoptions/tiffoptions/fillorder/) { get; set; } | Mendapatkan atau mengatur urutan pengisian bit byte. |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | Mendapatkan atau mengatur nilai yang menunjukkan apakah [full frame]. |
| [HalfToneHints](../../aspose.psd.imageoptions/tiffoptions/halftonehints/) { get; set; } | Mendapatkan atau mengatur petunjuk setengah nada. |
| [IccProfile](../../aspose.psd.imageoptions/tiffoptions/iccprofile/) { get; set; } | Mendapatkan atau mengatur aliran profil Icc. |
| [ImageDescription](../../aspose.psd.imageoptions/tiffoptions/imagedescription/) { get; set; } | Mendapatkan atau mengatur deskripsi gambar. |
| [ImageLength](../../aspose.psd.imageoptions/tiffoptions/imagelength/) { get; set; } | Mendapatkan atau mengatur panjang gambar. |
| [ImageWidth](../../aspose.psd.imageoptions/tiffoptions/imagewidth/) { get; set; } | Mendapatkan atau mengatur lebar gambar. |
| [InkNames](../../aspose.psd.imageoptions/tiffoptions/inknames/) { get; set; } | Mendapatkan atau mengatur nama tinta. |
| [IsExtraSamplesPresent](../../aspose.psd.imageoptions/tiffoptions/isextrasamplespresent/) { get; } | Mendapatkan nilai yang menunjukkan apakah sampel ekstra ada. |
| [IsTiled](../../aspose.psd.imageoptions/tiffoptions/istiled/) { get; } | Mendapatkan nilai yang menunjukkan apakah gambar berubin. |
| [IsValid](../../aspose.psd.imageoptions/tiffoptions/isvalid/) { get; } | Mendapatkan nilai yang menunjukkan apakah `TiffOptions` telah dikonfigurasi dengan benar. Gunakan metode Validate untuk menemukan alasan kegagalan. |
| [MaxSampleValue](../../aspose.psd.imageoptions/tiffoptions/maxsamplevalue/) { get; set; } | Mendapatkan atau mengatur nilai sampel maksimum. |
| [MinSampleValue](../../aspose.psd.imageoptions/tiffoptions/minsamplevalue/) { get; set; } | Mendapatkan atau mengatur nilai sampel minimum. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | Opsi multipage |
| [Orientation](../../aspose.psd.imageoptions/tiffoptions/orientation/) { get; set; } | Mendapatkan atau mengatur orientasi. |
| [PageName](../../aspose.psd.imageoptions/tiffoptions/pagename/) { get; set; } | Mendapatkan atau mengatur nama halaman. |
| [PageNumber](../../aspose.psd.imageoptions/tiffoptions/pagenumber/) { get; set; } | Mendapatkan atau mengatur tag nomor halaman. |
| override [Palette](../../aspose.psd.imageoptions/tiffoptions/palette/) { get; set; } | Mendapatkan atau mengatur palet warna. |
| [Photometric](../../aspose.psd.imageoptions/tiffoptions/photometric/) { get; set; } | Mendapatkan atau mengatur fotometrik. |
| [PlanarConfiguration](../../aspose.psd.imageoptions/tiffoptions/planarconfiguration/) { get; set; } | Mendapatkan atau mengatur konfigurasi planar. |
| [Predictor](../../aspose.psd.imageoptions/tiffoptions/predictor/) { get; set; } | Mendapatkan atau mengatur prediktor untuk kompresi LZW. |
| [PremultiplyComponents](../../aspose.psd.imageoptions/tiffoptions/premultiplycomponents/) { get; set; } | Mendapatkan atau mengatur nilai yang menunjukkan apakah komponen harus dipremultiplikasikan. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | Mendapatkan atau mengatur penangan acara kemajuan. |
| override [ResolutionSettings](../../aspose.psd.imageoptions/tiffoptions/resolutionsettings/) { get; set; } | Mendapatkan atau mengatur pengaturan resolusi. |
| [ResolutionUnit](../../aspose.psd.imageoptions/tiffoptions/resolutionunit/) { get; set; } | Mendapatkan atau mengatur satuan resolusi. |
| [RowsPerStrip](../../aspose.psd.imageoptions/tiffoptions/rowsperstrip/) { get; set; } | Mendapatkan atau mengatur baris per strip. |
| [SampleFormat](../../aspose.psd.imageoptions/tiffoptions/sampleformat/) { get; set; } | Mendapatkan atau mengatur format sampel. |
| [SamplesPerPixel](../../aspose.psd.imageoptions/tiffoptions/samplesperpixel/) { get; } | Mendapatkan sampel per piksel. Untuk mengubah nilai properti ini gunakan penyetel properti [`BitsPerSample`](./bitspersample/). |
| [ScannerManufacturer](../../aspose.psd.imageoptions/tiffoptions/scannermanufacturer/) { get; set; } | Mendapatkan atau mengatur produsen pemindai. |
| [ScannerModel](../../aspose.psd.imageoptions/tiffoptions/scannermodel/) { get; set; } | Mendapatkan atau mengatur model pemindai. |
| [SmaxSampleValue](../../aspose.psd.imageoptions/tiffoptions/smaxsamplevalue/) { get; set; } | Mendapatkan atau mengatur nilai sampel maksimum. Nilai memiliki tipe bidang yang paling cocok dengan data sampel (tipe Byte, Short, atau Long). |
| [SminSampleValue](../../aspose.psd.imageoptions/tiffoptions/sminsamplevalue/) { get; set; } | Mendapatkan atau mengatur nilai sampel minimum. Nilai memiliki tipe bidang yang paling cocok dengan data sampel (tipe Byte, Short, atau Long). |
| [SoftwareType](../../aspose.psd.imageoptions/tiffoptions/softwaretype/) { get; set; } | Mendapatkan atau mengatur tipe perangkat lunak. |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | Mendapatkan atau mengatur sumber untuk membuat gambar di dalamnya. |
| [StripByteCounts](../../aspose.psd.imageoptions/tiffoptions/stripbytecounts/) { get; set; } | Mendapatkan atau mengatur jumlah byte strip. |
| [StripOffsets](../../aspose.psd.imageoptions/tiffoptions/stripoffsets/) { get; set; } | Mendapatkan atau mengatur offset strip. |
| [SubFileType](../../aspose.psd.imageoptions/tiffoptions/subfiletype/) { get; set; } | Mendapatkan atau mengatur indikasi umum tentang jenis data yang terdapat dalam subfile ini. |
| [Tags](../../aspose.psd.imageoptions/tiffoptions/tags/) { get; set; } | Mendapatkan atau mengatur tag. |
| [TargetPrinter](../../aspose.psd.imageoptions/tiffoptions/targetprinter/) { get; set; } | Mendapatkan atau mengatur printer target. |
| [Threshholding](../../aspose.psd.imageoptions/tiffoptions/threshholding/) { get; set; } | Mendapatkan atau mengatur ambang. |
| [TileByteCounts](../../aspose.psd.imageoptions/tiffoptions/tilebytecounts/) { get; set; } | Mendapatkan atau mengatur jumlah byte ubin. |
| [TileLength](../../aspose.psd.imageoptions/tiffoptions/tilelength/) { get; set; } | Mendapatkan ot mengatur panjang ubin. |
| [TileOffsets](../../aspose.psd.imageoptions/tiffoptions/tileoffsets/) { get; set; } | Mendapatkan atau mengatur offset ubin. |
| [TileWidth](../../aspose.psd.imageoptions/tiffoptions/tilewidth/) { get; set; } | Mendapatkan ot mengatur lebar ubin. |
| [TotalPages](../../aspose.psd.imageoptions/tiffoptions/totalpages/) { get; } | Mendapatkan total halaman. |
| [ValidTagCount](../../aspose.psd.imageoptions/tiffoptions/validtagcount/) { get; } | Mendapatkan jumlah tag yang valid. Ini bukan total jumlah tag tetapi jumlah tag yang dapat dipertahankan. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | Mendapatkan atau mengatur opsi rasterisasi vektor. |
| override [XmpData](../../aspose.psd.imageoptions/tiffoptions/xmpdata/) { get; set; } | Mendapatkan atau mengatur kontainer metadata XMP. |
| [XPAuthor](../../aspose.psd.imageoptions/tiffoptions/xpauthor/) { get; set; } | Mendapatkan atau mengatur penulis gambar, yang digunakan oleh Windows Explorer. |
| [XPComment](../../aspose.psd.imageoptions/tiffoptions/xpcomment/) { get; set; } | Mendapatkan atau mengatur komentar pada gambar, yang digunakan oleh Windows Explorer. |
| [XPKeywords](../../aspose.psd.imageoptions/tiffoptions/xpkeywords/) { get; set; } | Mendapatkan atau mengatur subjek gambar, yang digunakan oleh Windows Explorer. |
| [Xposition](../../aspose.psd.imageoptions/tiffoptions/xposition/) { get; set; } | Mendapatkan atau mengatur posisi x. |
| [XPSubject](../../aspose.psd.imageoptions/tiffoptions/xpsubject/) { get; set; } | Mendapatkan atau mengatur informasi tentang gambar, yang digunakan oleh Windows Explorer. |
| [XPTitle](../../aspose.psd.imageoptions/tiffoptions/xptitle/) { get; set; } | Mendapatkan atau mengatur informasi tentang gambar, yang digunakan oleh Windows Explorer. |
| [Xresolution](../../aspose.psd.imageoptions/tiffoptions/xresolution/) { get; set; } | Mendapatkan atau mengatur resolusi x. |
| [YCbCrCoefficients](../../aspose.psd.imageoptions/tiffoptions/ycbcrcoefficients/) { get; set; } | Mendapatkan atau mengatur YCbCrCoefficients. |
| [YCbCrSubsampling](../../aspose.psd.imageoptions/tiffoptions/ycbcrsubsampling/) { get; set; } | Mendapatkan atau mengatur faktor subsampling untuk fotometrik YCbCr. |
| [Yposition](../../aspose.psd.imageoptions/tiffoptions/yposition/) { get; set; } | Mendapatkan atau mengatur posisi y. |
| [Yresolution](../../aspose.psd.imageoptions/tiffoptions/yresolution/) { get; set; } | Mendapatkan atau mengatur resolusi y. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [AddTag](../../aspose.psd.imageoptions/tiffoptions/addtag/)(TiffDataType) | Menambahkan tag baru. |
| [AddTags](../../aspose.psd.imageoptions/tiffoptions/addtags/)(TiffDataType[]) | Menambahkan tag-tag. |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | Mengkloning instance ini. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Membuang instance saat ini. |
| [GetTagByType](../../aspose.psd.imageoptions/tiffoptions/gettagbytype/)(TiffTags) | Mendapatkan instance tag berdasarkan tipe. |
| [IsTagPresent](../../aspose.psd.imageoptions/tiffoptions/istagpresent/)(TiffTags) | Menentukan apakah tag ada dalam opsi atau tidak. |
| [RemoveTag](../../aspose.psd.imageoptions/tiffoptions/removetag/)(TiffTags) | Menghapus tag. |
| [Validate](../../aspose.psd.imageoptions/tiffoptions/validate/)() | Memvalidasi apakah opsi memiliki kombinasi tag yang valid |
| static [GetValidTagsCount](../../aspose.psd.imageoptions/tiffoptions/getvalidtagscount/)(TiffDataType[]) | Mendapatkan jumlah tag yang valid. |

## Contoh

Contoh ini menunjukkan penggunaan berbagai kelas dari Namespace SaveOptions untuk tujuan ekspor. Gambar berjenis Psd dimuat ke dalam instance Image dan kemudian diekspor ke beberapa format.

```csharp
[C#]

//Muat gambar yang ada dalam instance kelas Image
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
{
    //Ekspor ke format file BMP menggunakan opsi default
    image.Save(@"C:\temp\output.bmp", new Aspose.PSD.ImageOptions.BmpOptions());

    //Ekspor ke format file JPEG menggunakan opsi default
    image.Save(@"C:\temp\output.jpeg", new Aspose.PSD.ImageOptions.JpegOptions());

    //Ekspor ke format file JPEG 2000 menggunakan opsi default
    image.Save(@"C:\temp\output.jp2", new Aspose.PSD.ImageOptions.Jpeg2000Options());

    //Ekspor ke format file PNG menggunakan opsi default
    image.Save(@"C:\temp\output.png", new Aspose.PSD.ImageOptions.PngOptions());

    //Ekspor ke format file TIFF menggunakan opsi default
    image.Save(@"c:\temp\output.tiff", new Aspose.PSD.ImageOptions.TiffOptions(Aspose.PSD.FileFormats.Tiff.Enums.TiffExpectedFormat.Default));
}
```

Contoh ini menggunakan kelas GraphicsPath dan Graphics untuk membuat dan memanipulasi Figure pada permukaan Image. Contoh membuat Image baru dan menggambar jalur dengan bantuan kelas GraphicsPath. Pada akhirnya metode DrawPath yang disediakan oleh kelas Graphics dipanggil untuk merender jalur pada permukaan. Akhirnya image diekspor ke format file Tiff.

```csharp
[C#]

//Buat sebuah instance dari Image
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Buat dan inisialisasi sebuah instance dari kelas Graphics
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Bersihkan permukaan Graphics
    graphics.Clear(Color.Wheat);

    //Buat sebuah instance dari kelas GraphicsPath
    Aspose.PSD.GraphicsPath graphicspath = new Aspose.PSD.GraphicsPath();

    //Buat sebuah instance dari kelas Figure
    Aspose.PSD.Figure figure = new Aspose.PSD.Figure();

    //Tambahkan Shape ke objek Figure
    figure.AddShape(new Aspose.PSD.Shapes.RectangleShape(new RectangleF(10, 10, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.PieShape(new Rectangle(new Point(250, 250), new Size(200, 200)), 0, 45));

    //Tambahkan objek Figure ke GraphicsPath
    graphicspath.AddFigure(figure);

    //Gambar jalur dengan objek Pen berwarna Hitam
    graphics.DrawPath(new Pen(Aspose.PSD.Color.Black, 2), graphicspath);

    //Buat sebuah instance dari TiffOptions dan atur berbagai propertinya
    Aspose.PSD.ImageOptions.TiffOptions tiffOptions = new Aspose.PSD.ImageOptions.TiffOptions(Aspose.PSD.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

    // simpan semua perubahan.
    image.Save("C:\\temp\\output.tiff", tiffOptions);
}
```

### Lihat Juga

* class [ImageOptionsBase](../../aspose.psd/imageoptionsbase/)
* namespace [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../)


