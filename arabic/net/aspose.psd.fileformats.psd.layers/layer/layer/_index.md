---
title: "Layer.Layer"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "منشئ Layer. يهيئ نسخة جديدة من فئة Layer. منشئ للتهيئة الكسولة."
type: docs
weight: 10
url: /ar/net/aspose.psd.fileformats.psd.layers/layer/layer/
---
{{< psd/tize >}}
## Layer() {#constructor}

يهيئ نسخة جديدة من الفئة [`Layer`](../). منشئ للتهيئة الكسولة.

```csharp
public Layer()
```

## أمثلة

المثال التالي يوضح كيف يمكنك الرسم على طبقة تم إنشاؤها حديثًا إذا تم استخدام نسخة المنشئ البسيطة في Aspose.PSD.

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

    // ارسم مستطيلًا بأداة القلم
    graphic.DrawRectangle(new Pen(Color.Red), new Rectangle(30, 10, 40, 80));

    // ارسم مستطيلًا آخر بفرشاة صلبة باللون الأزرق
    graphic.DrawRectangle(new Pen(new SolidBrush(Color.Blue)), new Rectangle(10, 30, 80, 40));

    image.Save(outputFilePath);
}
```

### انظر أيضًا

* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)

---

## Layer(RasterImage, bool) {#constructor_1}

يهيئ نسخة جديدة من الفئة [`Layer`](../).

```csharp
public Layer(RasterImage image, bool disposeImage = false)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| صورة | RasterImage | الصورة. |
| disposeImage | Boolean | إذا تم تعيينه إلى `true` [dispose image]. |

## أمثلة

الكود التالي يوضح القدرة على تحميل ملفات الصور JPEG/PNG/إلخ إلى PsdImage دون تحميل مباشر.

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

### انظر أيضًا

* class [RasterImage](../../../aspose.psd/rasterimage/)
* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)

---

## Layer(Stream) {#constructor_3}

يهيئ نسخة جديدة من الفئة [`Layer`](../).

```csharp
public Layer(Stream stream)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | Stream | تيار الصورة |

## أمثلة

المثال التالي يوضح كيف يمكنك إضافة صور Bmp, Jpeg, Jpeg2000, Png, Psd, Tiff, Gif كطبقات إلى PsdImage

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

### انظر أيضًا

* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)

---

## Layer(Rectangle, byte[], byte[], byte[], string) {#constructor_2}

ينشئ مثيلاً جديداً من الفئة [`Layer`](../) باستخدام مصفوفات البايت.

```csharp
public Layer(Rectangle bounds, byte[] redBytes, byte[] greenBytes, byte[] blueBytes, string name)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| الحدود | Rectangle | حدود الطبقة. |
| redBytes | Byte[] | البايتات الحمراء. |
| greenBytes | Byte[] | البايتات الخضراء. |
| blueBytes | Byte[] | البايتات الزرقاء. |
| الاسم | String | اسم الطبقة. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| [PsdImageException](../../../aspose.psd.coreexceptions.imageformats/psdimageexception/) | لا يمكن أن تكون مصفوفات البايت فارغة أو يجب أن يكون طول مصفوفات البايت مساويًا لأبعاد الحدود (bounds.Width * bounds.Height). |

### انظر أيضًا

* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


