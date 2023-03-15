---
title: Layer.Layer
second_title: Aspose.PSD لمرجع .NET API
description: Layer البناء. يقوم بتهيئة مثيل جديد لملفLayer فصل. مُنشئ للتهيئة البطيئة .
type: docs
weight: 10
url: /ar/net/aspose.psd.fileformats.psd.layers/layer/layer/
---
## Layer() {#constructor}

يقوم بتهيئة مثيل جديد لملف[`Layer`](../) فصل. مُنشئ للتهيئة البطيئة .

```csharp
public Layer()
```

### أمثلة

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

### أنظر أيضا

* class [Layer](../)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* المجسم [Aspose.PSD](../../../)

---

## Layer(RasterImage, bool) {#constructor_1}

يقوم بتهيئة مثيل جديد لملف[`Layer`](../) فئة .

```csharp
public Layer(RasterImage image, bool disposeImage = false)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| image | RasterImage | الصورة. |
| disposeImage | Boolean | إذا تم التعيين على`حقيقي` [التخلص من الصورة]. |

### أمثلة

يوضح الكود التالي القدرة على تحميل ملفات الصور JPEG / PNG / etc إلى PsdImage دون تحميل مباشر.

```csharp
[C#]

string filePath = "PsdExample.psd";
string outputFilePath = "PsdResult.psd";
using (var image = new PsdImage(200, 200))
{
    using (var im = Image.Load(filePath))
    {
        Layer layer = null;
        try
        {
            layer = new Layer((RasterImage)im);
            image.AddLayer(layer);
        }
        catch (Exception)
        {
            if (layer != null)
            {
                layer.Dispose();
            }

            throw;
        }
    }

    image.Save(outputFilePath);
}
```

### أنظر أيضا

* class [RasterImage](../../../aspose.psd/rasterimage/)
* class [Layer](../)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* المجسم [Aspose.PSD](../../../)

---

## Layer(Stream) {#constructor_3}

يقوم بتهيئة مثيل جديد لملف[`Layer`](../) فئة .

```csharp
public Layer(Stream stream)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| stream | Stream | تيار الصورة |

### أمثلة

يوضح المثال التالي كيف يمكنك إضافة صور Bmp و Jpeg و Jpeg2000 و Png و Psd و Tiff و Gif كطبقات إلى PsdImage

```csharp
[C#]

string outputFilePath = "PsdResult.psd";

var filesList = new string[]
{
    "PsdExample.psd",
    "BmpExample.bmp",
    "GifExample.gif",
    "Jpeg2000Example.jpf",
    "JpegExample.jpg",
    "PngExample.png",
    "TiffExample.tif",
};

using (var image = new PsdImage(200, 200))
{
    foreach (var fileName in filesList)
    {
        string filePath = fileName;
        using (var stream = new FileStream(filePath, FileMode.Open))
        {
            Layer layer = null;
            try
            {
                layer = new Layer(stream);
                image.AddLayer(layer);
            }
            catch (Exception e)
            {
                if (layer != null)
                {
                    layer.Dispose();
                }

                throw e;
            }
        }
    }

    image.Save(outputFilePath);
}
```

### أنظر أيضا

* class [Layer](../)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* المجسم [Aspose.PSD](../../../)

---

## Layer(Rectangle, byte[], byte[], byte[], string) {#constructor_2}

يقوم بتهيئة مثيل جديد لملف[`Layer`](../) فئة من مصفوفات البايت.

```csharp
public Layer(Rectangle bounds, byte[] redBytes, byte[] greenBytes, byte[] blueBytes, string name)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| bounds | Rectangle | حدود الطبقة. |
| redBytes | Byte[] | البايت الأحمر. |
| greenBytes | Byte[] | البايتات الخضراء. |
| blueBytes | Byte[] | البايت الأزرق. |
| name | String | اسم الطبقة. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| [PsdImageException](../../../aspose.psd.coreexceptions.imageformats/psdimageexception/) | لا يمكن أن تكون مصفوفات البايت فارغة أو يجب أن يكون طول مصفوفات البايت مساويًا لأبعاد الحدود (الحدود والعرض * الحدود والارتفاع) |

### أنظر أيضا

* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [Layer](../)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* المجسم [Aspose.PSD](../../../)


