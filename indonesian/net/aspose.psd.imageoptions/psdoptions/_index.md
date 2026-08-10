---
title: "Kelas PsdOptions"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Kelas Aspose.PSD.ImageOptions.PsdOptions. Opsi pembuatan format file psd."
type: docs
weight: 5390
url: /id/net/aspose.psd.imageoptions/psdoptions/
---
{{< psd/tize >}}
## PsdOptions class

Opsi pembuatan format file psd.

```csharp
public class PsdOptions : ImageOptionsBase
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [PsdOptions](psdoptions/#constructor)() | Menginisialisasi instance baru dari kelas `PsdOptions`. |
| [PsdOptions](psdoptions/#constructor_1)(PsdImage) | Menginisialisasi instance baru dari kelas `PsdOptions`. |
| [PsdOptions](psdoptions/#constructor_2)(PsdOptions) | Menginisialisasi instance baru dari kelas `PsdOptions`. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [BackgroundContents](../../aspose.psd.imageoptions/psdoptions/backgroundcontents/) { get; set; } | Mendapatkan atau mengatur warna latar belakang. Dapat dilihat di bawah objek transparan. |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | Mendapatkan atau mengatur petunjuk ukuran buffer yang didefinisikan sebagai ukuran maksimum yang diizinkan untuk semua buffer internal. |
| [ChannelBitsCount](../../aspose.psd.imageoptions/psdoptions/channelbitscount/) { get; set; } | Mendapatkan atau mengatur jumlah bit per saluran warna. |
| [ChannelsCount](../../aspose.psd.imageoptions/psdoptions/channelscount/) { get; set; } | Mendapatkan atau mengatur jumlah saluran warna. |
| [ColorMode](../../aspose.psd.imageoptions/psdoptions/colormode/) { get; set; } | Mendapatkan atau mengatur mode warna psd. |
| [CompressionMethod](../../aspose.psd.imageoptions/psdoptions/compressionmethod/) { get; set; } | Mendapatkan atau mengatur metode kompresi psd. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | Mendapatkan atau mengatur font pengganti default (font yang akan digunakan untuk menggambar teks saat mengekspor ke raster, jika font lapisan yang ada dalam file PSD tidak tersedia di sistem). Untuk memperoleh nama font default yang tepat dapat digunakan cuplikan kode berikut: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Mendapatkan nilai yang menunjukkan apakah instansi ini telah dibuang. |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | Mendapatkan atau mengatur nilai yang menunjukkan apakah [full frame]. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | Opsi multipage |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | Mendapatkan atau mengatur palet warna. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | Mendapatkan atau mengatur penangan acara kemajuan. |
| [PsdVersion](../../aspose.psd.imageoptions/psdoptions/psdversion/) { get; set; } | Mendapatkan atau mengatur versi format file. Bisa berupa PSD atau PSB. |
| [RefreshImagePreviewData](../../aspose.psd.imageoptions/psdoptions/refreshimagepreviewdata/) { get; set; } | Mendapatkan atau mengatur nilai yang menunjukkan apakah [refresh image preview data] - opsi yang digunakan untuk memaksimalkan kompatibilitas dengan penampil gambar PSD lainnya. Harap dicatat, menggambar lapisan teks ke tata letak akhir tidak didukung untuk platform Compact Framework. |
| [RemoveGlobalTextEngineResource](../../aspose.psd.imageoptions/psdoptions/removeglobaltextengineresource/) { get; set; } | Mendapatkan atau mengatur nilai yang menunjukkan apakah - Hapus sumber daya mesin teks global - Digunakan untuk beberapa file psd berlapis teks, hanya dalam kasus ketika mereka tidak dapat dibuka di Adobe Photoshop setelah diproses (biasanya terkait lapisan teks dengan font yang tidak ada). Setelah menggunakan opsi ini, pengguna perlu melakukan langkah berikut pada file yang dibuka di Photoshop: Menu "Text" -> "Process absent fonts". Setelah operasi itu semua teks akan muncul kembali. Harap dicatat, bahwa operasi ini dapat menyebabkan beberapa perubahan pada tata letak akhir. |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings/) { get; set; } | Mendapatkan atau mengatur pengaturan resolusi. |
| [Resources](../../aspose.psd.imageoptions/psdoptions/resources/) { get; set; } | Mendapatkan atau mengatur sumber daya psd. Jika nilai: NULL - maka simpan ImageResources asli (perilaku default) Tidak Kosong - maka simpan sumber daya yang diberikan ke properti ini + [required resources] Kosong - maka hanya [required resources] yang disimpan. Sumber daya yang diperlukan: ResolutionInfoResource, XmpResource |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | Mendapatkan atau mengatur sumber untuk membuat gambar di dalamnya. |
| [UpdateMetadata](../../aspose.psd.imageoptions/psdoptions/updatemetadata/) { get; set; } | Mendapatkan atau mengatur nilai yang menunjukkan apakah [update metadata]. Jika nilai true, metadata akan diperbarui saat menyimpan gambar. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | Mendapatkan atau mengatur opsi rasterisasi vektor. |
| [Version](../../aspose.psd.imageoptions/psdoptions/version/) { get; set; } | Mendapatkan atau mengatur versi file psd. |
| override [XmpData](../../aspose.psd.imageoptions/psdoptions/xmpdata/) { get; set; } | Dapatkan atau atur kontainer data XMP |

## Metode

| Nama | Deskripsi |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | Mengkloning instance ini. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Membuang instance saat ini. |

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

Contoh ini membuat file Image baru di lokasi disk tertentu sebagaimana ditentukan oleh properti Source dari instance PsdOptions. Beberapa properti untuk instance PsdOptions diatur sebelum membuat gambar sebenarnya. Khususnya properti Source, yang merujuk ke lokasi disk aktual dalam kasus ini.

```csharp
[C#]

//Buat sebuah instance dari PsdOptions dan atur berbagai propertinya
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//Buat sebuah instance dari FileCreateSource dan tetapkan sebagai Source untuk instance PsdOptions
//Parameter Boolean kedua menentukan apakah file yang akan dibuat bersifat IsTemporal atau tidak
psdOptions.Source = new Aspose.PSD.Sources.FileCreateSource(@"C:\temp\sample.psd", false);

//Buat sebuah instance dari Image dan inisialisasi dengan instance PsdOptions dengan memanggil metode Create
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //lakukan beberapa pemrosesan gambar

    // simpan semua perubahan
    image.Save();
}
```

Contoh berikut menunjukkan bahwa membaca dan menyimpan file PSD Grayscale 16 bit ke RGB 16 bit per saluran berfungsi dengan benar dan tanpa pengecualian.

```csharp
[C#]

string sourceFilePath = "grayscale5x5.psd";
string exportFilePath = "rgb16bit5x5.psd";
PsdOptions psdOptions = new PsdOptions()
{
    ColorMode = ColorModes.Rgb,
    ChannelBitsCount = 16,
    ChannelsCount = 4
};

using (PsdImage image = (PsdImage)Image.Load(sourceFilePath))
{
    RasterCachedImage raster = image.Layers[0];
    Aspose.PSD.Graphics graphics = new Graphics(raster);
    int width = raster.Width;
    int height = raster.Height;
    Rectangle rect = new Rectangle(width / 3, height / 3, width - (2 * (width / 3)) - 1, height - (2 * (height / 3)) - 1);
    graphics.DrawRectangle(new Aspose.PSD.Pen(Color.DarkGray, 1), rect);
    image.Save(exportFilePath, psdOptions);
}

string pngExportPath = Path.ChangeExtension(exportFilePath, "png");
using (PsdImage image = (PsdImage)Image.Load(exportFilePath))
{
    // Tidak seharusnya ada pengecualian di sini.
    image.Save(pngExportPath, new PngOptions() { ColorType = PngColorType.GrayscaleWithAlpha });
}
```

Contoh berikut menunjukkan bahwa membaca dan menyimpan file PSD Grayscale 16 bit ke Grayscale 8 bit per saluran berfungsi dengan benar dan tanpa pengecualian.

```csharp
[C#]

string sourceFilePath = "grayscale16bit.psd";
string exportFilePath = "grayscale16bit_Grayscale8_2_RLE.psd";
PsdOptions psdOptions = new PsdOptions()
{
    ColorMode = ColorModes.Grayscale,
    ChannelBitsCount = 8,
    ChannelsCount = 2
};

using (PsdImage image = (PsdImage)Image.Load(sourceFilePath))
{
    RasterCachedImage raster = image.Layers[0];
    Aspose.PSD.Graphics graphics = new Graphics(raster);
    int width = raster.Width;
    int height = raster.Height;
    Rectangle rect = new Rectangle(width / 3, height / 3, width - (2 * (width / 3)) - 1, height - (2 * (height / 3)) - 1);
    graphics.DrawRectangle(new Aspose.PSD.Pen(Color.DarkGray, 1), rect);
    image.Save(exportFilePath, psdOptions);
}

string pngExportPath = Path.ChangeExtension(exportFilePath, "png");
using (PsdImage image = (PsdImage)Image.Load(exportFilePath))
{
    // Tidak seharusnya ada pengecualian di sini.
    image.Save(pngExportPath, new PngOptions() { ColorType = PngColorType.GrayscaleWithAlpha });
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

Contoh ini menunjukkan cara memuat informasi Piksel dalam Array bertipe Color, memanipulasi array tersebut, dan mengembalikannya ke gambar. Untuk melakukan operasi ini, contoh ini membuat file Image baru (dalam format PSD) menggunakan objek MemoryStream.

```csharp
[C#]

//Buat sebuah instance dari MemoryStream
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    //Buat sebuah instance dari PsdOptions dan atur berbagai propertinya termasuk properti Source
    Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();
    psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream);

    //Buat sebuah instance dari Image
    using (Aspose.PSD.RasterImage image = (Aspose.PSD.RasterImage)Aspose.PSD.Image.Create(psdOptions, 500, 500))
    {
        //Dapatkan piksel gambar dengan menentukan area sebagai batas gambar
        Aspose.PSD.Color[] pixels = image.LoadPixels(image.Bounds);

        //Iterasi array dan atur warna piksel terindeks alternatif
        for (int index = 0; index < pixels.Length; index++)
        {
            if (index % 2 == 0)
            {
                //Atur warna piksel terindeks menjadi kuning
                pixels[index] = Aspose.PSD.Color.Yellow;
            }
            else
            {
                //Atur warna piksel terindeks menjadi biru
                pixels[index] = Aspose.PSD.Color.Blue;
            }
        }

        //Terapkan perubahan piksel ke gambar
        image.SavePixels(image.Bounds, pixels);

        // simpan semua perubahan.
        image.Save();
    }

    //Tulis MemoryStream ke File
    stream.WriteTo(new System.IO.FileStream(@"C:\temp\output.psd", System.IO.FileMode.CreateNew));
}
```

Contoh berikut menunjukkan bahwa membaca dan menyimpan file PSD 16 bit Grayscale bekerja dengan benar dan tanpa pengecualian.

```csharp
[C#]

Stack<string> outputFilePathStack = new Stack<string>();

void SaveToPsdThenLoadAndSaveToPng(
    string file,
    ColorModes colorMode,
    short channelBitsCount,
    short channelsCount,
    CompressionMethod compression,
    int layerNumber)
{
    string filePath = file + ".psd";
    string postfix = colorMode.ToString() + channelBitsCount + "_" + channelsCount + "_" + compression;
    string exportPath = file + postfix + ".psd";
    PsdOptions psdOptions = new PsdOptions()
    {
        ColorMode = colorMode,
        ChannelBitsCount = channelBitsCount,
        ChannelsCount = channelsCount,
        CompressionMethod = compression
    };

    using (PsdImage image = (PsdImage)Image.Load(filePath))
    {
        RasterCachedImage raster = layerNumber >= 0 ? (RasterCachedImage)image.Layers[layerNumber] : image;

        Aspose.PSD.Graphics graphics = new Graphics(raster);
        int width = raster.Width;
        int height = raster.Height;
        Rectangle rect = new Rectangle(
            width / 3,
            height / 3,
            width - (2 * (width / 3)) - 1,
            height - (2 * (height / 3)) - 1);
        graphics.DrawRectangle(new Aspose.PSD.Pen(Color.DarkGray, 1), rect);

        image.Save(exportPath, psdOptions);
    }

    string pngExportPath = Path.ChangeExtension(exportPath, "png");
    using (PsdImage image = (PsdImage)Image.Load(exportPath))
    {
        // Tidak seharusnya ada pengecualian di sini.
        image.Save(pngExportPath, new PngOptions() { ColorType = PngColorType.GrayscaleWithAlpha });
    }

    outputFilePathStack.Push(exportPath);
}

SaveToPsdThenLoadAndSaveToPng("grayscale5x5", ColorModes.Cmyk, 16, 5, CompressionMethod.RLE, 0);
SaveToPsdThenLoadAndSaveToPng("argb16bit_5x5", ColorModes.Grayscale, 16, 2, CompressionMethod.RLE, 0);
SaveToPsdThenLoadAndSaveToPng("argb16bit_5x5_no_layers", ColorModes.Grayscale, 16, 2, CompressionMethod.RLE, -1);
SaveToPsdThenLoadAndSaveToPng("argb8bit_5x5", ColorModes.Grayscale, 16, 2, CompressionMethod.RLE, 0);
SaveToPsdThenLoadAndSaveToPng("argb8bit_5x5_no_layers", ColorModes.Grayscale, 16, 2, CompressionMethod.RLE, -1);
SaveToPsdThenLoadAndSaveToPng("cmyk16bit_5x5_no_layers", ColorModes.Grayscale, 16, 2, CompressionMethod.RLE, -1);
SaveToPsdThenLoadAndSaveToPng("index8bit_5x5", ColorModes.Grayscale, 16, 2, CompressionMethod.RLE, -1);
```

### Lihat Juga

* class [ImageOptionsBase](../../aspose.psd/imageoptionsbase/)
* namespace [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../)


