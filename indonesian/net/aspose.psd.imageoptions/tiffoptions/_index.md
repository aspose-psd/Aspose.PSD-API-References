---
title: Class TiffOptions
second_title: Aspose.PSD untuk Referensi .NET API
description: Aspose.PSD.ImageOptions.TiffOptions kelas. Opsi format file tiff. Perhatikan bahwa tag lebar dan tinggi akan ditimpa pada pembuatan gambar dengan parameter lebar dan tinggi sehingga tidak perlu menentukannya secara langsung. Perhatikan bahwa banyak opsi mengembalikan nilai default tetapi itu tidak berarti demikian opsi ini ditetapkan secara eksplisit sebagai nilai tag. Untuk memverifikasi keberadaan tag gunakan properti Tags atau metode IsTagPresent yang sesuai.
type: docs
weight: 4940
url: /id/net/aspose.psd.imageoptions/tiffoptions/
---
## TiffOptions class

Opsi format file tiff. Perhatikan bahwa tag lebar dan tinggi akan ditimpa pada pembuatan gambar dengan parameter lebar dan tinggi sehingga tidak perlu menentukannya secara langsung. Perhatikan bahwa banyak opsi mengembalikan nilai default tetapi itu tidak berarti demikian opsi ini ditetapkan secara eksplisit sebagai nilai tag. Untuk memverifikasi keberadaan tag, gunakan properti Tags atau metode IsTagPresent yang sesuai.

```csharp
public class TiffOptions : ImageOptionsBase
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [TiffOptions](tiffoptions/#constructor_2)(TiffDataType[]) | Menginisialisasi instance baru dari`TiffOptions` kelas. |
| [TiffOptions](tiffoptions/#constructor)(TiffExpectedFormat) | Menginisialisasi instance baru dari`TiffOptions` kelas. Secara default konvensi little endian digunakan. |
| [TiffOptions](tiffoptions/#constructor_3)(TiffOptions) | Menginisialisasi instance baru dari`TiffOptions` kelas. |
| [TiffOptions](tiffoptions/#constructor_1)(TiffExpectedFormat, TiffByteOrder) | Menginisialisasi instance baru dari`TiffOptions` kelas. |

## Properti

| Nama | Keterangan |
| --- | --- |
| [AlphaStorage](../../aspose.psd.imageoptions/tiffoptions/alphastorage/) { get; set; } | Mendapat atau menyetel opsi penyimpanan alfa. Pilihan selainUnspecified digunakan jika ada lebih dari 3[`SamplesPerPixel`](./samplesperpixel/) didefinisikan. |
| [Artist](../../aspose.psd.imageoptions/tiffoptions/artist/) { get; set; } | Mendapat atau menyetel artis. |
| [BitsPerPixel](../../aspose.psd.imageoptions/tiffoptions/bitsperpixel/) { get; } | Mendapat bit per piksel. |
| [BitsPerSample](../../aspose.psd.imageoptions/tiffoptions/bitspersample/) { get; set; } | Mendapat atau mengatur bit per sampel. |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | Mendapat atau menyetel petunjuk ukuran buffer yang ditentukan ukuran maksimum yang diizinkan untuk semua buffer internal. |
| [ByteOrder](../../aspose.psd.imageoptions/tiffoptions/byteorder/) { get; set; } | Mendapat atau menetapkan nilai yang menunjukkan urutan tiff byte. |
| [ColorMap](../../aspose.psd.imageoptions/tiffoptions/colormap/) { get; set; } | Mendapat atau menyetel peta warna. |
| [CompressedQuality](../../aspose.psd.imageoptions/tiffoptions/compressedquality/) { get; set; } | Mendapatkan atau menyetel kualitas gambar terkompresi. Digunakan dengan kompresi Jpeg. |
| [Compression](../../aspose.psd.imageoptions/tiffoptions/compression/) { get; set; } | Mendapat atau menyetel kompresi. |
| [Copyright](../../aspose.psd.imageoptions/tiffoptions/copyright/) { get; set; } | Mendapatkan atau menyetel hak cipta. |
| [DateTime](../../aspose.psd.imageoptions/tiffoptions/datetime/) { get; set; } | Mendapat atau mengatur tanggal dan waktu. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | Mendapat atau menyetel font pengganti default (font yang akan digunakan untuk menggambar teks saat mengekspor ke raster, jika font layer yang ada di file PSD tidak disajikan di sistem). Untuk mengambil nama yang tepat dari font default dapat digunakan potongan kode selanjutnya : System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] keluarga = col.Families; string defaultFontName = keluarga[0].Nama; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Mendapat nilai yang menunjukkan apakah instance ini dibuang. |
| [DocumentName](../../aspose.psd.imageoptions/tiffoptions/documentname/) { get; set; } | Mendapat atau menetapkan nama dokumen. |
| [ExifIfd](../../aspose.psd.imageoptions/tiffoptions/exififd/) { get; } | Mendapat atau menyetel pointer ke EXIF IFD. |
| [FaxT4Options](../../aspose.psd.imageoptions/tiffoptions/faxt4options/) { get; set; } | Mendapat atau menyetel opsi t4 faks. |
| [FileStandard](../../aspose.psd.imageoptions/tiffoptions/filestandard/) { get; set; } | Mendapat atau menyetel standar file TIFF. |
| [FillOrder](../../aspose.psd.imageoptions/tiffoptions/fillorder/) { get; set; } | Mendapat atau menyetel urutan pengisian bit byte. |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | Mendapat atau menetapkan nilai yang menunjukkan apakah [full frame]. |
| [HalfToneHints](../../aspose.psd.imageoptions/tiffoptions/halftonehints/) { get; set; } | Mendapat atau menyetel petunjuk halftone. |
| [IccProfile](../../aspose.psd.imageoptions/tiffoptions/iccprofile/) { get; set; } | Mendapat atau menyetel aliran profil Icc. |
| [ImageDescription](../../aspose.psd.imageoptions/tiffoptions/imagedescription/) { get; set; } | Mendapat atau menyetel deskripsi gambar. |
| [ImageLength](../../aspose.psd.imageoptions/tiffoptions/imagelength/) { get; set; } | Mendapat atau menyetel panjang gambar. |
| [ImageWidth](../../aspose.psd.imageoptions/tiffoptions/imagewidth/) { get; set; } | Mendapat atau mengatur lebar gambar. |
| [InkNames](../../aspose.psd.imageoptions/tiffoptions/inknames/) { get; set; } | Mendapat atau menyetel nama tinta. |
| [IsExtraSamplesPresent](../../aspose.psd.imageoptions/tiffoptions/isextrasamplespresent/) { get; } | Mendapat nilai yang menunjukkan apakah ada sampel tambahan. |
| [IsTiled](../../aspose.psd.imageoptions/tiffoptions/istiled/) { get; } | Mendapat nilai yang menunjukkan apakah gambar berbentuk ubin. |
| [IsValid](../../aspose.psd.imageoptions/tiffoptions/isvalid/) { get; } | Mendapat nilai yang menunjukkan apakah`TiffOptions` telah dikonfigurasi dengan benar. Gunakan metode Validasi untuk menemukan alasan kegagalan. |
| [MaxSampleValue](../../aspose.psd.imageoptions/tiffoptions/maxsamplevalue/) { get; set; } | Mendapat atau menetapkan nilai sampel maks. |
| [MinSampleValue](../../aspose.psd.imageoptions/tiffoptions/minsamplevalue/) { get; set; } | Mendapat atau menyetel nilai sampel min. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | Opsi multi halaman |
| [Orientation](../../aspose.psd.imageoptions/tiffoptions/orientation/) { get; set; } | Mendapat atau menyetel orientasi. |
| [PageName](../../aspose.psd.imageoptions/tiffoptions/pagename/) { get; set; } | Mendapat atau mengatur nama halaman. |
| [PageNumber](../../aspose.psd.imageoptions/tiffoptions/pagenumber/) { get; set; } | Mendapat atau menyetel tag nomor halaman. |
| override [Palette](../../aspose.psd.imageoptions/tiffoptions/palette/) { get; set; } | Mendapat atau menyetel palet warna. |
| [Photometric](../../aspose.psd.imageoptions/tiffoptions/photometric/) { get; set; } | Mendapat atau menyetel fotometrik. |
| [PlanarConfiguration](../../aspose.psd.imageoptions/tiffoptions/planarconfiguration/) { get; set; } | Mendapat atau menyetel konfigurasi planar. |
| [Predictor](../../aspose.psd.imageoptions/tiffoptions/predictor/) { get; set; } | Mendapat atau menyetel prediktor untuk kompresi LZW. |
| [PremultiplyComponents](../../aspose.psd.imageoptions/tiffoptions/premultiplycomponents/) { get; set; } | Mendapat atau menetapkan nilai yang menunjukkan apakah komponen harus dikalikan sebelumnya. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | Mendapat atau menyetel pengendali event progres. |
| override [ResolutionSettings](../../aspose.psd.imageoptions/tiffoptions/resolutionsettings/) { get; set; } | Mendapat atau menyetel pengaturan resolusi. |
| [ResolutionUnit](../../aspose.psd.imageoptions/tiffoptions/resolutionunit/) { get; set; } | Mendapat atau menyetel unit resolusi. |
| [RowsPerStrip](../../aspose.psd.imageoptions/tiffoptions/rowsperstrip/) { get; set; } | Mendapat atau mengatur baris per strip. |
| [SampleFormat](../../aspose.psd.imageoptions/tiffoptions/sampleformat/) { get; set; } | Mendapat atau menyetel format sampel. |
| [SamplesPerPixel](../../aspose.psd.imageoptions/tiffoptions/samplesperpixel/) { get; } | Mendapat sampel per piksel. Untuk mengubah nilai properti ini gunakan[`BitsPerSample`](./bitspersample/) penyetel properti. |
| [ScannerManufacturer](../../aspose.psd.imageoptions/tiffoptions/scannermanufacturer/) { get; set; } | Mendapatkan atau menyetel pabrikan pemindai. |
| [ScannerModel](../../aspose.psd.imageoptions/tiffoptions/scannermodel/) { get; set; } | Mendapat atau menyetel model pemindai. |
| [SmaxSampleValue](../../aspose.psd.imageoptions/tiffoptions/smaxsamplevalue/) { get; set; } | Mendapat atau menetapkan nilai sampel maks. Nilai memiliki jenis bidang yang paling cocok dengan data sampel (tipe Byte, Pendek, atau Panjang). |
| [SminSampleValue](../../aspose.psd.imageoptions/tiffoptions/sminsamplevalue/) { get; set; } | Mendapat atau menetapkan nilai sampel min. Nilai memiliki jenis bidang yang paling cocok dengan data sampel (tipe Byte, Pendek, atau Panjang). |
| [SoftwareType](../../aspose.psd.imageoptions/tiffoptions/softwaretype/) { get; set; } | Mendapatkan atau menyetel jenis perangkat lunak. |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | Mendapatkan atau menyetel sumber untuk membuat gambar. |
| [StripByteCounts](../../aspose.psd.imageoptions/tiffoptions/stripbytecounts/) { get; set; } | Mendapat atau menyetel jumlah byte strip. |
| [StripOffsets](../../aspose.psd.imageoptions/tiffoptions/stripoffsets/) { get; set; } | Mendapat atau menyetel offset strip. |
| [SubFileType](../../aspose.psd.imageoptions/tiffoptions/subfiletype/) { get; set; } | Mendapat atau menetapkan indikasi umum dari jenis data yang terkandung dalam subfile ini. |
| [Tags](../../aspose.psd.imageoptions/tiffoptions/tags/) { get; set; } | Mendapat atau menyetel tag. |
| [TargetPrinter](../../aspose.psd.imageoptions/tiffoptions/targetprinter/) { get; set; } | Mendapat atau menyetel printer target. |
| [Threshholding](../../aspose.psd.imageoptions/tiffoptions/threshholding/) { get; set; } | Mendapat atau menyetel ambang batas. |
| [TileByteCounts](../../aspose.psd.imageoptions/tiffoptions/tilebytecounts/) { get; set; } | Mendapat atau menyetel jumlah byte petak. |
| [TileLength](../../aspose.psd.imageoptions/tiffoptions/tilelength/) { get; set; } | Mendapat banyak set panjang ubin. |
| [TileOffsets](../../aspose.psd.imageoptions/tiffoptions/tileoffsets/) { get; set; } | Mendapat atau menyetel offset petak. |
| [TileWidth](../../aspose.psd.imageoptions/tiffoptions/tilewidth/) { get; set; } | Mendapatkan banyak set lebar ubin. |
| [TotalPages](../../aspose.psd.imageoptions/tiffoptions/totalpages/) { get; } | Mendapat total halaman. |
| [ValidTagCount](../../aspose.psd.imageoptions/tiffoptions/validtagcount/) { get; } | Mendapat jumlah tag yang valid. Ini bukan jumlah total tag tetapi jumlah tag yang dapat dipertahankan. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | Mendapat atau menyetel opsi rasterisasi vektor. |
| override [XmpData](../../aspose.psd.imageoptions/tiffoptions/xmpdata/) { get; set; } | Mendapat atau menyetel penampung metadata XMP. |
| [XPAuthor](../../aspose.psd.imageoptions/tiffoptions/xpauthor/) { get; set; } | Mendapat atau menyetel penulis gambar, yang digunakan oleh Windows Explorer. |
| [XPComment](../../aspose.psd.imageoptions/tiffoptions/xpcomment/) { get; set; } | Mendapat atau mengatur komentar pada gambar, yang digunakan oleh Windows Explorer. |
| [XPKeywords](../../aspose.psd.imageoptions/tiffoptions/xpkeywords/) { get; set; } | Mendapat atau menyetel gambar subjek, yang digunakan oleh Windows Explorer. |
| [Xposition](../../aspose.psd.imageoptions/tiffoptions/xposition/) { get; set; } | Mendapat atau mengatur posisi x. |
| [XPSubject](../../aspose.psd.imageoptions/tiffoptions/xpsubject/) { get; set; } | Mendapat atau mengatur informasi tentang gambar, yang digunakan oleh Windows Explorer. |
| [XPTitle](../../aspose.psd.imageoptions/tiffoptions/xptitle/) { get; set; } | Mendapat atau mengatur informasi tentang gambar, yang digunakan oleh Windows Explorer. |
| [Xresolution](../../aspose.psd.imageoptions/tiffoptions/xresolution/) { get; set; } | Mendapat atau menyetel resolusi x. |
| [YCbCrCoefficients](../../aspose.psd.imageoptions/tiffoptions/ycbcrcoefficients/) { get; set; } | Mendapat atau menyetel Koefisien YCbCr. |
| [YCbCrSubsampling](../../aspose.psd.imageoptions/tiffoptions/ycbcrsubsampling/) { get; set; } | Mendapatkan atau menyetel faktor subsampling untuk fotometrik YCbCr. |
| [Yposition](../../aspose.psd.imageoptions/tiffoptions/yposition/) { get; set; } | Mendapat atau mengatur posisi y. |
| [Yresolution](../../aspose.psd.imageoptions/tiffoptions/yresolution/) { get; set; } | Mendapat atau mengatur resolusi y. |

## Metode

| Nama | Keterangan |
| --- | --- |
| [AddTag](../../aspose.psd.imageoptions/tiffoptions/addtag/)(TiffDataType) | Menambahkan tag baru. |
| [AddTags](../../aspose.psd.imageoptions/tiffoptions/addtags/)(TiffDataType[]) | Menambahkan tag. |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | Menggandakan instance ini. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Membuang instance saat ini. |
| [GetTagByType](../../aspose.psd.imageoptions/tiffoptions/gettagbytype/)(TiffTags) | Mendapat instance tag berdasarkan jenis. |
| [IsTagPresent](../../aspose.psd.imageoptions/tiffoptions/istagpresent/)(TiffTags) | Menentukan apakah tag ada di opsi atau tidak. |
| [RemoveTag](../../aspose.psd.imageoptions/tiffoptions/removetag/)(TiffTags) | Menghapus tag. |
| [Validate](../../aspose.psd.imageoptions/tiffoptions/validate/)() | Memvalidasi jika opsi memiliki kombinasi tag yang valid |
| static [GetValidTagsCount](../../aspose.psd.imageoptions/tiffoptions/getvalidtagscount/)(TiffDataType[]) | Mendapatkan jumlah tag yang valid. |

### Contoh

Contoh ini menunjukkan penggunaan kelas yang berbeda dari SaveOptions Namespace untuk tujuan ekspor. Gambar bertipe Psd dimuat ke dalam instance Gambar dan kemudian diekspor ke beberapa format.

```csharp
[C#]

// Muat gambar yang ada dalam instance kelas Gambar
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

Contoh ini menggunakan kelas GraphicsPath dan Graphics untuk membuat dan memanipulasi Angka pada permukaan Gambar. Contoh membuat Gambar baru dan menggambar jalur dengan bantuan kelas GraphicsPath. Pada akhirnya metode DrawPath yang diekspos oleh kelas Graphics dipanggil untuk merender jalur di permukaan. Akhirnya gambar diekspor ke format file Tiff.

```csharp
[C#]

//Buat instance dari Gambar 
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Membuat dan menginisialisasi sebuah instance dari kelas Graphics
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    // Bersihkan permukaan Grafik
    graphics.Clear(Color.Wheat);

    //Buat instance dari kelas GraphicsPath
    Aspose.PSD.GraphicsPath graphicspath = new Aspose.PSD.GraphicsPath();

    //Buat turunan dari kelas Gambar
    Aspose.PSD.Figure figure = new Aspose.PSD.Figure();

    //Tambahkan Bentuk ke objek Figur
    figure.AddShape(new Aspose.PSD.Shapes.RectangleShape(new RectangleF(10, 10, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.PieShape(new Rectangle(new Point(250, 250), new Size(200, 200)), 0, 45));

    // Tambahkan objek Gambar ke GraphicsPath
    graphicspath.AddFigure(figure);

    // Gambar jalur dengan objek Pena berwarna Hitam
    graphics.DrawPath(new Pen(Aspose.PSD.Color.Black, 2), graphicspath);

    //Buat instance TiffOptions dan atur berbagai propertinya
    Aspose.PSD.ImageOptions.TiffOptions tiffOptions = new Aspose.PSD.ImageOptions.TiffOptions(Aspose.PSD.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

    // simpan semua perubahan.
    image.Save("C:\\temp\\output.tiff", tiffOptions);
}
```

### Lihat juga

* class [ImageOptionsBase](../../aspose.psd/imageoptionsbase/)
* ruang nama [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions/)
* perakitan [Aspose.PSD](../../)


