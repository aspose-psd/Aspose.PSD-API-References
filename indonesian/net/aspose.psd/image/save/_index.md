---
title: Image.Save
second_title: Aspose.PSD untuk Referensi .NET API
description: Image metode. Menyimpan data gambar ke aliran yang mendasarinya.
type: docs
weight: 230
url: /id/net/aspose.psd/image/save/
---
## Save() {#save}

Menyimpan data gambar ke aliran yang mendasarinya.

```csharp
public void Save()
```

### Lihat juga

* class [Image](../)
* ruang nama [Aspose.PSD](../../image/)
* perakitan [Aspose.PSD](../../../)

---

## Save(string, ImageOptionsBase) {#save_5}

Menyimpan data objek ke lokasi file yang ditentukan dalam format file yang ditentukan sesuai dengan opsi penyimpanan.

```csharp
public virtual void Save(string filePath, ImageOptionsBase options)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| filePath | String | Jalur file. |
| options | ImageOptionsBase | Opsi. |

### Contoh

Contoh berikut menunjukkan bagaimana Anda dapat mengekspor file Adobe Illustrator ke format PDF di Aspose.PSD

```csharp
[C#]

string sourceFilePath = "rect2_color.ai";
string outputFilePath = "rect2_color.ai_output.pdf";
using (AiImage image = (AiImage)Image.Load(sourceFilePath))
{
    image.Save(outputFilePath, new PdfOptions());
}
```

Contoh berikut menunjukkan bahwa AsposePSD mendukung file PSB yang diekspor ke format PSD.

```csharp
[C#]

// Mendukung penyimpanan PSB sebagai PDF
string sourceFileName = "sample.psb";
string outFileName = "sample.pdf";

using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    image.Save(outFileName, new PdfOptions());
}
```

Kode berikut menyimpan PsdImage sebagai dokumen PDF dengan teks yang dapat dipilih.

```csharp
[C#]

// Menyimpan PSD ke dalam PDF tidak menyediakan teks yang dapat dipilih
string sourceFileName = "text.psd";
string outFileName = "text.pdf";

using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    image.Save(outFileName, new PdfOptions());
}
```

Contoh berikut menunjukkan bagaimana Anda dapat mengekspor file AI ke format PSD dan PNG di Aspose.PSD

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

Contoh ini menunjukkan langkah-langkah sederhana untuk Menyimpan Gambar. Untuk mendemonstrasikan operasi ini, kami memuat file yang ada dari beberapa lokasi disk, melakukan operasi Putar pada gambar dan Menyimpan gambar dalam format file Jpeg menggunakan File Path

```csharp
[C#]

//Buat instance kelas gambar dan inisialisasi dengan file yang ada melalui jalur File
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
{
    // Putar gambar 180 derajat terhadap sumbu X
    image.RotateFlip(Aspose.PSD.RotateFlipType.Rotate180FlipX);

    //Simpan Gambar sebagai Jpeg ke File Path dengan pengaturan default JpegOptions
    image.Save(@"C:\temp\output.jpeg", new Aspose.PSD.ImageOptions.JpegOptions());
}
```

Contoh berikut menunjukkan bagaimana Anda dapat mengubah visibilitas LayerGroup di Aspose.PSD

```csharp
[C#]

string sourceFilePath = "input.psd";
string outputFilePath = "output.psd";

// buat perubahan pada nama layer dan simpan
using (var image = (PsdImage)Image.Load(sourceFilePath))
{
    for (int i = 0; i < image.Layers.Length; i++)
    {
        var layer = image.Layers[i];

        // Matikan semua yang ada di dalam grup
        if (layer is LayerGroup)
        {
            layer.IsVisible = false;
        }
    }

    image.Save(outputFilePath);
}
```

Contoh berikut menunjukkan bagaimana Anda bisa menggambar pada lapisan yang baru dibuat jika versi konstruktor sederhana digunakan di Aspose.PSD

```csharp
[C#]

string outputFilePath = "output.psd";

int width = 100;
int height = 100;
using (var image = new PsdImage(width, height))
{
    var layer = new Layer();
    layer.Bottom = height;
    layer.Right = width;
    image.AddLayer(layer);

    Graphics graphic = new Graphics(layer);
    graphic.Clear(Color.Yellow);

    // menggambar persegi panjang dengan Pen tool
    graphic.DrawRectangle(new Pen(Color.Red), new Rectangle(30, 10, 40, 80));

    // menggambar persegi panjang lain dengan Kuas Padat dalam warna Biru
    graphic.DrawRectangle(new Pen(new SolidBrush(Color.Blue)), new Rectangle(10, 30, 80, 40));

    image.Save(outputFilePath);
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

Contoh berikut menunjukkan bagaimana Anda bisa menggunakan mode campuran lapisan PassThrough di Aspose.PSD

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

* class [ImageOptionsBase](../../imageoptionsbase/)
* class [Image](../)
* ruang nama [Aspose.PSD](../../image/)
* perakitan [Aspose.PSD](../../../)

---

## Save(string, ImageOptionsBase, Rectangle) {#save_6}

Menyimpan data objek ke lokasi file yang ditentukan dalam format file yang ditentukan sesuai dengan opsi penyimpanan.

```csharp
public virtual void Save(string filePath, ImageOptionsBase options, Rectangle boundsRectangle)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| filePath | String | Jalur file. |
| options | ImageOptionsBase | Opsi. |
| boundsRectangle | Rectangle | Gambar tujuan membatasi persegi panjang. Atur persegi panjang kosong untuk menggunakan batas sumber. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | pilihan |
| [ImageSaveException](../../../aspose.psd.coreexceptions/imagesaveexception/) | Penyimpanan gambar gagal. |

### Lihat juga

* class [ImageOptionsBase](../../imageoptionsbase/)
* struct [Rectangle](../../rectangle/)
* class [Image](../)
* ruang nama [Aspose.PSD](../../image/)
* perakitan [Aspose.PSD](../../../)

---

## Save(Stream, ImageOptionsBase) {#save_2}

Menyimpan data gambar ke aliran yang ditentukan dalam format file yang ditentukan sesuai dengan opsi penyimpanan.

```csharp
public void Save(Stream stream, ImageOptionsBase optionsBase)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| stream | Stream | Stream untuk menyimpan data gambar. |
| optionsBase | ImageOptionsBase | Opsi simpan. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | optionsBase |
| ArgumentException | Tidak dapat menyimpan ke format yang ditentukan karena saat ini tidak didukung.;optionsBase |
| [ImageSaveException](../../../aspose.psd.coreexceptions/imagesaveexception/) | Ekspor gambar gagal. |

### Contoh

Contoh ini menunjukkan proses Menyimpan Gambar ke MemoryStream. Untuk mendemonstrasikan operasi ini, misalnya memuat file yang ada dari beberapa lokasi disk, melakukan operasi Putar pada gambar dan Menyimpan gambar dalam format Gif

```csharp
[C#]

//Buat instance dari MemoryStream
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    //Buat instance kelas gambar dan inisialisasi dengan file yang ada melalui jalur File
    using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
    {
        // Putar gambar 180 derajat terhadap sumbu X
        image.RotateFlip(Aspose.PSD.RotateFlipType.Rotate180FlipX);

        //Simpan Gambar sebagai PSD ke MemoryStream dengan pengaturan default GifOptions
        image.Save(stream, new Aspose.PSD.ImageOptions.GifOptions());
    }
}
```

### Lihat juga

* class [ImageOptionsBase](../../imageoptionsbase/)
* class [Image](../)
* ruang nama [Aspose.PSD](../../image/)
* perakitan [Aspose.PSD](../../../)

---

## Save(Stream, ImageOptionsBase, Rectangle) {#save_3}

Menyimpan data gambar ke aliran yang ditentukan dalam format file yang ditentukan sesuai dengan opsi penyimpanan.

```csharp
public virtual void Save(Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| stream | Stream | Stream untuk menyimpan data gambar. |
| optionsBase | ImageOptionsBase | Opsi simpan. |
| boundsRectangle | Rectangle | Gambar tujuan membatasi persegi panjang. Atur persegi panjang kosong untuk menggunakan batas sumber. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | optionsBase |
| ArgumentException | Tidak dapat menyimpan ke format yang ditentukan karena saat ini tidak didukung.;optionsBase |
| [ImageSaveException](../../../aspose.psd.coreexceptions/imagesaveexception/) | Ekspor gambar gagal. |

### Lihat juga

* class [ImageOptionsBase](../../imageoptionsbase/)
* struct [Rectangle](../../rectangle/)
* class [Image](../)
* ruang nama [Aspose.PSD](../../image/)
* perakitan [Aspose.PSD](../../../)


