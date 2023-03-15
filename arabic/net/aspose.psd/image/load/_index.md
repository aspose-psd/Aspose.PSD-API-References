---
title: Image.Load
second_title: Aspose.PSD لمرجع .NET API
description: Image طريقة. يقوم بتحميل صورة جديدة من الملف المحدد.
type: docs
weight: 20
url: /ar/net/aspose.psd/image/load/
---
## Load(string, LoadOptions) {#load_3}

يقوم بتحميل صورة جديدة من الملف المحدد.

```csharp
public static Image Load(string filePath, LoadOptions loadOptions)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| filePath | String | مسار الملف لتحميل الصورة منه. |
| loadOptions | LoadOptions | خيارات التحميل. |

### قيمة الإرجاع

الصورة المحملة .

### أنظر أيضا

* class [LoadOptions](../../loadoptions/)
* class [Image](../)
* مساحة الاسم [Aspose.PSD](../../image/)
* المجسم [Aspose.PSD](../../../)

---

## Load(string) {#load_2}

يقوم بتحميل صورة جديدة من الملف المحدد.

```csharp
public static Image Load(string filePath)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| filePath | String | مسار الملف المراد تحميل الصورة منه . |

### قيمة الإرجاع

الصورة المحملة .

### أمثلة

يوضح هذا المثال تحميل ملف صورة موجود في مثيل Aspose.PSD.Image باستخدام مسار الملف المحدد

```csharp
[C#]

// إنشاء مثيل صورة وتهيئته بملف صورة موجود من موقع القرص
string path = "C:\\temp\\image.psd";
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(path))
{
    // القيام ببعض معالجة الصور
}
```

يوضح المثال التالي أن محاذاة النص من خلال ITextPortion للغات التي تُكتب من اليمين إلى اليسار تعمل بشكل صحيح.

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

يوضح المثال التالي أن قراءة ملفات PSD ذات 16 بت بتدرج الرمادي وحفظها إلى 16 بت لكل قناة RGB تعمل بشكل صحيح وبدون استثناء.

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
    // هنا يجب ألا يكون هناك استثناء.
    image.Save(pngExportPath, new PngOptions() { ColorType = PngColorType.GrayscaleWithAlpha });
}
```

يوضح المثال التالي أن قراءة ملفات PSD ذات 16 بت بتدرج الرمادي وحفظها إلى 8 بت لكل قناة تعمل بتدرج الرمادي بشكل صحيح وبدون استثناء.

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
    // هنا يجب ألا يكون هناك استثناء.
    image.Save(pngExportPath, new PngOptions() { ColorType = PngColorType.GrayscaleWithAlpha });
}
```

يوضح المثال التالي أن تقدم تحويل المستند يعمل بشكل صحيح وبدون استثناء.

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

يوضح المثال التالي أن قراءة ملفات PSD ذات 16 بت بتدرج الرمادي وحفظها تعمل بشكل صحيح وبدون استثناء.

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
        // هنا يجب ألا يكون هناك استثناء.
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

### أنظر أيضا

* class [Image](../)
* مساحة الاسم [Aspose.PSD](../../image/)
* المجسم [Aspose.PSD](../../../)

---

## Load(Stream, LoadOptions) {#load_1}

يتم تحميل صورة جديدة من التدفق المحدد.

```csharp
public static Image Load(Stream stream, LoadOptions loadOptions)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| stream | Stream | الدفق لتحميل الصورة منه. |
| loadOptions | LoadOptions | خيارات التحميل. |

### قيمة الإرجاع

الصورة المحملة .

### أنظر أيضا

* class [LoadOptions](../../loadoptions/)
* class [Image](../)
* مساحة الاسم [Aspose.PSD](../../image/)
* المجسم [Aspose.PSD](../../../)

---

## Load(Stream) {#load}

يتم تحميل صورة جديدة من التدفق المحدد.

```csharp
public static Image Load(Stream stream)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| stream | Stream | الدفق لتحميل الصورة منه . |

### قيمة الإرجاع

الصورة المحملة .

### أمثلة

يوضح هذا المثال استخدام كائنات System.IO.Stream لتحميل ملف صورة موجود

```csharp
[C#]

// إنشاء مثيل لـ FileStream
using(System.IO.FileStream stream = new System.IO.FileStream(@"C:\temp\sample.psd",System.IO.FileMode.Open))
{
    // إنشاء مثيل لفئة الصورة وتحميل ملف موجود من خلال كائن FileStream عن طريق استدعاء طريقة التحميل
    using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(stream))
    {
        // القيام ببعض معالجة الصور.
    }
}
```

### أنظر أيضا

* class [Image](../)
* مساحة الاسم [Aspose.PSD](../../image/)
* المجسم [Aspose.PSD](../../../)


