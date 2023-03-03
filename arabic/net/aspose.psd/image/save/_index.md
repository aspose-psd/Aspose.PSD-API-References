---
title: Image.Save
second_title: Aspose.PSD لمرجع .NET API
description: Image طريقة. يحفظ بيانات الصورة في التدفق الأساسي.
type: docs
weight: 230
url: /ar/net/aspose.psd/image/save/
---
## Save() {#save}

يحفظ بيانات الصورة في التدفق الأساسي.

```csharp
public void Save()
```

### أنظر أيضا

* class [Image](../)
* مساحة الاسم [Aspose.PSD](../../image/)
* المجسم [Aspose.PSD](../../../)

---

## Save(string, ImageOptionsBase) {#save_5}

يحفظ بيانات الكائن في موقع الملف المحدد بتنسيق الملف المحدد وفقًا لخيارات الحفظ.

```csharp
public virtual void Save(string filePath, ImageOptionsBase options)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| filePath | String | مسار الملف. |
| options | ImageOptionsBase | الخيارات . |

### أمثلة

يوضح المثال التالي كيف يمكنك تصدير ملفات Adobe Illustrator إلى تنسيق PDF بتنسيق Aspose.PSD

```csharp
[C#]

string sourceFilePath = "rect2_color.ai";
string outputFilePath = "rect2_color.ai_output.pdf";
using (AiImage image = (AiImage)Image.Load(sourceFilePath))
{
    image.Save(outputFilePath, new PdfOptions());
}
```

يوضح المثال التالي أن AsposePSD يدعم تصدير ملفات PSB إلى تنسيق PSD.

```csharp
[C#]

// دعم حفظ PSB كملف PDF
string sourceFileName = "sample.psb";
string outFileName = "sample.pdf";

using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    image.Save(outFileName, new PdfOptions());
}
```

الكود التالي يحفظ PsdImage كمستند PDF بنص قابل للتحديد.

```csharp
[C#]

// لا يوفر حفظ PSD في PDF نصًا قابلاً للتحديد
string sourceFileName = "text.psd";
string outFileName = "text.pdf";

using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    image.Save(outFileName, new PdfOptions());
}
```

يوضح المثال التالي كيف يمكنك تصدير ملف AI إلى تنسيق PSD و PNG في Aspose.PSD

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

يوضح هذا المثال الخطوات البسيطة لحفظ صورة. لإثبات هذه العملية ، نقوم بتحميل ملف موجود من بعض مواقع القرص ، ونقوم بإجراء عملية التدوير على الصورة وحفظ الصورة بتنسيق ملف Jpeg باستخدام مسار الملف

```csharp
[C#]

// إنشاء مثيل لفئة الصورة وتهيئته بملف موجود من خلال مسار الملف
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
{
    // قم بتدوير الصورة 180 درجة حول المحور X.
    image.RotateFlip(Aspose.PSD.RotateFlipType.Rotate180FlipX);

    // احفظ الصورة بتنسيق Jpeg إلى مسار الملف باستخدام إعدادات JpegOptions الافتراضية
    image.Save(@"C:\temp\output.jpeg", new Aspose.PSD.ImageOptions.JpegOptions());
}
```

يوضح المثال التالي كيف يمكنك تغيير رؤية LayerGroup في Aspose.PSD

```csharp
[C#]

string sourceFilePath = "input.psd";
string outputFilePath = "output.psd";

// إجراء تغييرات في أسماء الطبقات وحفظها
using (var image = (PsdImage)Image.Load(sourceFilePath))
{
    for (int i = 0; i < image.Layers.Length; i++)
    {
        var layer = image.Layers[i];

        // قم بإيقاف تشغيل كل شيء داخل المجموعة
        if (layer is LayerGroup)
        {
            layer.IsVisible = false;
        }
    }

    image.Save(outputFilePath);
}
```

يوضح المثال التالي كيف يمكنك الرسم على طبقة تم إنشاؤها حديثًا إذا تم استخدام إصدار المُنشئ البسيط في Aspose.PSD

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

    // رسم مستطيل باستخدام أداة القلم
    graphic.DrawRectangle(new Pen(Color.Red), new Rectangle(30, 10, 40, 80));

    // ارسم مستطيلاً آخر باستخدام فرشاة صلبة باللون الأزرق
    graphic.DrawRectangle(new Pen(new SolidBrush(Color.Blue)), new Rectangle(10, 30, 80, 40));

    image.Save(outputFilePath);
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

يوضح المثال التالي كيف يمكنك استخدام وضع مزج طبقة PassThrough في Aspose.PSD

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

* class [ImageOptionsBase](../../imageoptionsbase/)
* class [Image](../)
* مساحة الاسم [Aspose.PSD](../../image/)
* المجسم [Aspose.PSD](../../../)

---

## Save(string, ImageOptionsBase, Rectangle) {#save_6}

يحفظ بيانات الكائن في موقع الملف المحدد بتنسيق الملف المحدد وفقًا لخيارات الحفظ.

```csharp
public virtual void Save(string filePath, ImageOptionsBase options, Rectangle boundsRectangle)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| filePath | String | مسار الملف. |
| options | ImageOptionsBase | الخيارات. |
| boundsRectangle | Rectangle | مستطيل حدود الصورة الوجهة. اضبط المستطيل الفارغ لاستخدام حدود المسار. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | خيارات |
| [ImageSaveException](../../../aspose.psd.coreexceptions/imagesaveexception/) | فشل حفظ الصورة. |

### أنظر أيضا

* class [ImageOptionsBase](../../imageoptionsbase/)
* struct [Rectangle](../../rectangle/)
* class [Image](../)
* مساحة الاسم [Aspose.PSD](../../image/)
* المجسم [Aspose.PSD](../../../)

---

## Save(Stream, ImageOptionsBase) {#save_2}

يحفظ بيانات الصورة إلى التدفق المحدد بتنسيق الملف المحدد وفقًا لخيارات الحفظ.

```csharp
public void Save(Stream stream, ImageOptionsBase optionsBase)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| stream | Stream | التدفق الذي سيتم حفظ بيانات الصورة فيه. |
| optionsBase | ImageOptionsBase | خيارات الحفظ. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | الخيارات |
| ArgumentException | لا يمكن الحفظ بالتنسيق المحدد لأنه غير مدعوم في الوقت الحالي.؛ optionsBase |
| [ImageSaveException](../../../aspose.psd.coreexceptions/imagesaveexception/) | فشل تصدير الصورة. |

### أمثلة

يوضح هذا المثال عملية حفظ صورة في MemoryStream. لتوضيح هذه العملية ، يقوم المثال بتحميل ملف موجود من بعض مواقع القرص ، وتنفيذ عملية التدوير على الصورة وحفظ الصورة بتنسيق Gif

```csharp
[C#]

// إنشاء مثيل لـ MemoryStream
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    // إنشاء مثيل لفئة الصورة وتهيئته بملف موجود من خلال مسار الملف
    using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
    {
        // قم بتدوير الصورة 180 درجة حول المحور X.
        image.RotateFlip(Aspose.PSD.RotateFlipType.Rotate180FlipX);

        // احفظ الصورة بصيغة PSD في MemoryStream باستخدام إعدادات GifOptions الافتراضية
        image.Save(stream, new Aspose.PSD.ImageOptions.GifOptions());
    }
}
```

### أنظر أيضا

* class [ImageOptionsBase](../../imageoptionsbase/)
* class [Image](../)
* مساحة الاسم [Aspose.PSD](../../image/)
* المجسم [Aspose.PSD](../../../)

---

## Save(Stream, ImageOptionsBase, Rectangle) {#save_3}

يحفظ بيانات الصورة إلى التدفق المحدد بتنسيق الملف المحدد وفقًا لخيارات الحفظ.

```csharp
public virtual void Save(Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| stream | Stream | التدفق الذي سيتم حفظ بيانات الصورة فيه. |
| optionsBase | ImageOptionsBase | خيارات الحفظ. |
| boundsRectangle | Rectangle | مستطيل حدود الصورة الوجهة. اضبط المستطيل الفارغ لاستخدام حدود المصدر. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | الخيارات |
| ArgumentException | لا يمكن الحفظ بالتنسيق المحدد لأنه غير مدعوم في الوقت الحالي.؛ optionsBase |
| [ImageSaveException](../../../aspose.psd.coreexceptions/imagesaveexception/) | فشل تصدير الصورة. |

### أنظر أيضا

* class [ImageOptionsBase](../../imageoptionsbase/)
* struct [Rectangle](../../rectangle/)
* class [Image](../)
* مساحة الاسم [Aspose.PSD](../../image/)
* المجسم [Aspose.PSD](../../../)


