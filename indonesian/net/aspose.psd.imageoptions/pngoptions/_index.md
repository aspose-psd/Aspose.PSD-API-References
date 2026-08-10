---
title: "Kelas PngOptions"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Kelas Aspose.PSD.ImageOptions.PngOptions. Opsi pembuatan format file png"
type: docs
weight: 5370
url: /id/net/aspose.psd.imageoptions/pngoptions/
---
{{< psd/tize >}}
## PngOptions class

Opsi pembuatan format file png.

```csharp
public class PngOptions : ImageOptionsBase
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [PngOptions](pngoptions/#constructor)() | Menginisialisasi instance baru dari kelas `PngOptions`. |
| [PngOptions](pngoptions/#constructor_1)(PngOptions) | Menginisialisasi instance baru dari kelas `PngOptions`. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [BitDepth](../../aspose.psd.imageoptions/pngoptions/bitdepth/) { get; set; } | Kedalaman bit. |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | Mendapatkan atau mengatur petunjuk ukuran buffer yang didefinisikan sebagai ukuran maksimum yang diizinkan untuk semua buffer internal. |
| [ColorType](../../aspose.psd.imageoptions/pngoptions/colortype/) { get; set; } | Mendapatkan atau mengatur tipe warna. |
| [CompressionLevel](../../aspose.psd.imageoptions/pngoptions/compressionlevel/) { get; set; } | Level kompresi gambar png dalam rentang 0-9, di mana 9 adalah kompresi maksimum dan 0 adalah mode penyimpanan. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | Mendapatkan atau mengatur font pengganti default (font yang akan digunakan untuk menggambar teks saat mengekspor ke raster, jika font lapisan yang ada dalam file PSD tidak tersedia di sistem). Untuk memperoleh nama font default yang tepat dapat digunakan cuplikan kode berikut: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Mendapatkan nilai yang menunjukkan apakah instansi ini telah dibuang. |
| [FilterType](../../aspose.psd.imageoptions/pngoptions/filtertype/) { get; set; } | Mendapatkan atau mengatur jenis filter yang digunakan selama proses penyimpanan file png. |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | Mendapatkan atau mengatur nilai yang menunjukkan apakah [full frame]. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | Opsi multipage |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | Mendapatkan atau mengatur palet warna. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | Mendapatkan atau mengatur penangan acara kemajuan. |
| [Progressive](../../aspose.psd.imageoptions/pngoptions/progressive/) { get; set; } | Mendapatkan atau mengatur nilai yang menunjukkan apakah `PngOptions` ini bersifat progresif. |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings/) { get; set; } | Mendapatkan atau mengatur pengaturan resolusi. |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | Mendapatkan atau mengatur sumber untuk membuat gambar di dalamnya. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | Mendapatkan atau mengatur opsi rasterisasi vektor. |
| override [XmpData](../../aspose.psd.imageoptions/pngoptions/xmpdata/) { get; set; } | Mendapatkan atau mengatur kontainer metadata XMP. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | Mengkloning instance ini. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Membuang instance saat ini. |

## Bidang

| Nama | Deskripsi |
| --- | --- |
| const [DefaultCompressionLevel](../../aspose.psd.imageoptions/pngoptions/defaultcompressionlevel/) | Level kompresi default. |

## Contoh

Contoh berikut menunjukkan cara Anda dapat mengekspor file AI ke format PSD dan PNG dalam Aspose.PSD

```csharp
[C#]

string sourceFileName = "form_8.ai";
string outputFileName = "form_8_export";
using (AiImage image = (AiImage)Image.Load(sourceFileName))
{
    image.Save(outputFileName + ".psd", new PsdOptions());
    image.Save(outputFileName + ".png", new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

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

Contoh berikut menunjukkan cara Anda dapat menggunakan mode campuran lapisan PassThrough dalam Aspose.PSD

```csharp
[C#]

string sourceFileName = "Apple.psd";
string outputFileName = "OutputApple";
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    if (image.Layers.Length < 23)
    {
        throw new Exception("There is not 23rd layer.");
    }

    var layer = image.Layers[23] as LayerGroup;

    if (layer == null)
    {
        throw new Exception("The 23rd layer is not a layer group.");
    }

    if (layer.Name != "AdjustmentGroup")
    {
        throw new Exception("The 23rd layer name is not 'AdjustmentGroup'.");
    }

    if (layer.BlendModeKey != BlendMode.PassThrough)
    {
        throw new Exception("AdjustmentGroup layer should have 'pass through' blend mode.");
    }

    image.Save(outputFileName + ".psd", new PsdOptions(image));
    image.Save(outputFileName + ".png", new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });

    layer.BlendModeKey = BlendMode.Normal;

    image.Save(outputFileName + "Normal.psd", new PsdOptions(image));
    image.Save(outputFileName + "Normal.png", new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

Contoh berikut menunjukkan bahwa kemajuan konversi dokumen berfungsi dengan benar dan tanpa pengecualian.

```csharp
[C#]

string sourceFilePath = "Apple.psd";
Stream outputStream = new MemoryStream();

Aspose.PSD.ProgressEventHandler localProgressEventHandler = delegate(ProgressEventHandlerInfo progressInfo)
{
    string message = string.Format(
        "{0} {1}: {2} out of {3}",
        progressInfo.Description,
        progressInfo.EventType,
        progressInfo.Value,
        progressInfo.MaxValue);
    Console.WriteLine(message);
};

Console.WriteLine("---------- Loading Apple.psd ----------");
var loadOptions = new PsdLoadOptions() { ProgressEventHandler = localProgressEventHandler };
using (PsdImage image = (PsdImage)Image.Load(sourceFilePath, loadOptions))
{
    Console.WriteLine("---------- Saving Apple.psd to PNG format ----------");
    image.Save(
        outputStream,
        new PngOptions()
            {
                ColorType = PngColorType.Truecolor,
                ProgressEventHandler = localProgressEventHandler
            });

    Console.WriteLine("---------- Saving Apple.psd to PSD format ----------");
    image.Save(
        outputStream,
        new PsdOptions()
            {
                ColorMode = ColorModes.Rgb,
                ChannelsCount = 4,
                ProgressEventHandler = localProgressEventHandler
            });
}
```

Contoh ini menggunakan kelas Graphics untuk membuat bentuk primitif pada permukaan Image. Untuk mendemonstrasikan operasi, contoh ini membuat Image baru dalam format PSD dan menggambar bentuk primitif pada permukaan Image menggunakan metode Draw yang disediakan oleh kelas Graphics, kemudian mengekspornya ke format file PSD.

```csharp
[C#]

//Buat sebuah instance dari Image
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Buat dan inisialisasi sebuah instance dari kelas Graphics
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Bersihkan permukaan Graphics
    graphics.Clear(Color.Wheat);

    //Gambar sebuah Arc dengan menentukan objek Pen yang berwarna Hitam, 
    //sebuah Rectangle yang mengelilingi Arc, Sudut Mulai, dan Sudut Penyapuan
    graphics.DrawArc(new Pen(Color.Black, 2), new Rectangle(200, 200, 100, 200), 0, 300);

    //Gambar sebuah Bezier dengan menentukan objek Pen yang berwarna Biru dan Titik koordinat.
    graphics.DrawBezier(new Pen(Color.Blue, 2), new Point(250, 100), new Point(300, 30), new Point(450, 100), new Point(235, 25));

    //Gambar sebuah Curve dengan menentukan objek Pen yang berwarna Hijau dan sebuah array Titik
    graphics.DrawCurve(new Pen(Color.Green, 2), new[] { new Point(100, 200), new Point(100, 350), new Point(200, 450) });

    //Gambar sebuah Ellipse menggunakan objek Pen dan Rectangle yang mengelilinginya
    graphics.DrawEllipse(new Pen(Color.Yellow, 2), new Rectangle(300, 300, 100, 100));

    //Gambar sebuah Garis 
    graphics.DrawLine(new Pen(Color.Violet, 2), new Point(100, 100), new Point(200, 200));

    //Gambar sebuah segmen Pie
    graphics.DrawPie(new Pen(Color.Silver, 2), new Rectangle(new Point(200, 20), new Size(200, 200)), 0, 45);

    //Gambar sebuah Polygon dengan menentukan objek Pen yang berwarna Merah dan sebuah array Titik
    graphics.DrawPolygon(new Pen(Color.Red, 2), new[] { new Point(20, 100), new Point(20, 200), new Point(220, 20) });

    //Gambar sebuah Rectangle
    graphics.DrawRectangle(new Pen(Color.Orange, 2), new Rectangle(new Point(250, 250), new Size(100, 100)));

    //Buat objek SolidBrush dan atur berbagai propertinya
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush();
    brush.Color = Color.Purple;
    brush.Opacity = 100;

    //Gambar sebuah String menggunakan objek SolidBrush dan Font, pada Point tertentu
    graphics.DrawString("This image is created by Aspose.PSD API", new Font("Times New Roman", 16), brush, new PointF(50, 400));

    //Buat sebuah instance dari PngOptions dan atur berbagai propertinya
    Aspose.PSD.ImageOptions.PngOptions pngOptions = new Aspose.PSD.ImageOptions.PngOptions();

    // simpan semua perubahan.
    image.Save("C:\\temp\\output.png", pngOptions);
}
```

### Lihat Juga

* class [ImageOptionsBase](../../aspose.psd/imageoptionsbase/)
* namespace [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../)


