---
title: Image.Load
second_title: Aspose.PSD untuk Referensi .NET API
description: Image metode. Memuat gambar baru dari file yang ditentukan.
type: docs
weight: 20
url: /id/net/aspose.psd/image/load/
---
## Load(string, LoadOptions) {#load_3}

Memuat gambar baru dari file yang ditentukan.

```csharp
public static Image Load(string filePath, LoadOptions loadOptions)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| filePath | String | Jalur file untuk memuat gambar. |
| loadOptions | LoadOptions | Opsi beban. |

### Nilai Pengembalian

Gambar yang dimuat.

### Lihat juga

* class [LoadOptions](../../loadoptions/)
* class [Image](../)
* ruang nama [Aspose.PSD](../../image/)
* perakitan [Aspose.PSD](../../../)

---

## Load(string) {#load_2}

Memuat gambar baru dari file yang ditentukan.

```csharp
public static Image Load(string filePath)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| filePath | String | Jalur file untuk memuat gambar. |

### Nilai Pengembalian

Gambar yang dimuat.

### Contoh

Contoh ini mendemonstrasikan pemuatan file Gambar yang ada ke dalam instance Aspose.PSD.Image menggunakan jalur file yang ditentukan

```csharp
[C#]

//Buat instance Gambar dan inisialisasi dengan file gambar yang ada dari lokasi disk
string path = "C:\\temp\\image.psd";
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(path))
{
    //melakukan beberapa pemrosesan gambar
}
```

Contoh berikut menunjukkan bahwa Perataan Teks melalui ITextPortion untuk bahasa kanan ke kiri berfungsi dengan benar.

```csharp
[C#]

string sourceFilePath = "bidi.psd";
string exportFilePath = "bidiOutput.psd";

using (PsdImage image = (PsdImage)Image.Load(sourceFilePath))
{
    TextLayer layer = (TextLayer)image.Layers[2];
    ITextPortion[] portions = layer.TextData.Items;

    portions[0].Paragraph.Justification = JustificationMode.Center;
    layer.TextData.UpdateLayerData();

    image.Save(exportFilePath);
}
```

Contoh berikut menunjukkan bahwa membaca dan menyimpan file PSD Grayscale 16 bit ke 16bit per saluran RGB berfungsi dengan benar dan tanpa pengecualian.

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
    // Tidak terkecuali.
    image.Save(pngExportPath, new PngOptions() { ColorType = PngColorType.GrayscaleWithAlpha });
}
```

Contoh berikut menunjukkan bahwa membaca dan menyimpan file PSD Grayscale 16 bit ke 8 bit per saluran Grayscale bekerja dengan benar dan tanpa pengecualian.

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
    // Tidak terkecuali.
    image.Save(pngExportPath, new PngOptions() { ColorType = PngColorType.GrayscaleWithAlpha });
}
```

Contoh berikut menunjukkan bahwa progres konversi dokumen bekerja dengan benar dan tanpa pengecualian.

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

Contoh berikut menunjukkan bahwa membaca dan menyimpan file PSD Grayscale 16 bit bekerja dengan benar dan tanpa pengecualian.

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
        // Tidak terkecuali.
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

### Lihat juga

* class [Image](../)
* ruang nama [Aspose.PSD](../../image/)
* perakitan [Aspose.PSD](../../../)

---

## Load(Stream, LoadOptions) {#load_1}

Memuat gambar baru dari aliran yang ditentukan.

```csharp
public static Image Load(Stream stream, LoadOptions loadOptions)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| stream | Stream | Aliran untuk memuat gambar dari. |
| loadOptions | LoadOptions | Opsi beban. |

### Nilai Pengembalian

Gambar yang dimuat.

### Lihat juga

* class [LoadOptions](../../loadoptions/)
* class [Image](../)
* ruang nama [Aspose.PSD](../../image/)
* perakitan [Aspose.PSD](../../../)

---

## Load(Stream) {#load}

Memuat gambar baru dari aliran yang ditentukan.

```csharp
public static Image Load(Stream stream)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| stream | Stream | Aliran untuk memuat gambar dari. |

### Nilai Pengembalian

Gambar yang dimuat.

### Contoh

Contoh ini menunjukkan penggunaan objek System.IO.Stream untuk memuat file Gambar yang ada

```csharp
[C#]

//Buat instance FileStream
using(System.IO.FileStream stream = new System.IO.FileStream(@"C:\temp\sample.psd",System.IO.FileMode.Open))
{
    //Buat instance kelas Image dan muat file yang ada melalui objek FileStream dengan memanggil metode Load
    using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(stream))
    {
        //melakukan beberapa pemrosesan gambar.
    }
}
```

### Lihat juga

* class [Image](../)
* ruang nama [Aspose.PSD](../../image/)
* perakitan [Aspose.PSD](../../../)


