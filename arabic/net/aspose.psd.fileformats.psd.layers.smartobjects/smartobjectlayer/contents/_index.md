---
title: SmartObjectLayer.Contents
second_title: Aspose.PSD لمرجع .NET API
description: SmartObjectLayer ملكية. الحصول على أو تعيين محتويات طبقة الكائن الذكي. محتويات الكائن الذكي المضمنة هي ملف الصورة الخام المضمنData وخصائصه . محتويات الكائن الذكي المرتبط هي المحتوى الأولي لملف الصورة المرتبط إذا كان متاحًا وخصائصهLiFeDataSource . لا ندعم التحميل من Adobe Photoshop  مكتبة الرسومات عندماIsLibraryLink هو true . بالنسبة لملفات الارتباط العادية  نستخدم في البدايةRelativePath للبحث عن الملف نسبيًا في مسار الصورة المصدرSourceImagePath  إذا لم يكن متوفرًا ننظر إليهFullPath  إذا لم يكن كذلك  فنحن نبحث عن ملف الارتباط في نفس الدليل حيث توجد صورتناSourceImagePath .
type: docs
weight: 10
url: /ar/net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/contents/
---
## SmartObjectLayer.Contents property

الحصول على أو تعيين محتويات طبقة الكائن الذكي. محتويات الكائن الذكي المضمنة هي ملف الصورة الخام المضمن:[`Data`](../../../aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/data/) وخصائصه . محتويات الكائن الذكي المرتبط هي المحتوى الأولي لملف الصورة المرتبط إذا كان متاحًا وخصائصه:[`LiFeDataSource`](../../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/) . لا ندعم التحميل من Adobe� Photoshop� �� مكتبة الرسومات عندما[`IsLibraryLink`](../../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/islibrarylink/) هو true . بالنسبة لملفات الارتباط العادية ، نستخدم في البداية[`RelativePath`](../../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/relativepath/) للبحث عن الملف نسبيًا في مسار الصورة المصدرSourceImagePath ، إذا لم يكن متوفرًا ننظر إليه[`FullPath`](../../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/fullpath/) ، إذا لم يكن كذلك ، فنحن نبحث عن ملف الارتباط في نفس الدليل حيث توجد صورتنا:SourceImagePath .

```csharp
public byte[] Contents { get; set; }
```

### Property_Value

ملفbyte[] محتويات طبقة الكائن الذكي.

### استثناءات

| استثناء | حالة |
| --- | --- |
| NotSupportedException | لا يمكن الحصول على محتويات من مكتبة Adobe� Photoshop� ��. |

### أمثلة

يوضح الكود التالي دعم الكائنات الذكية المضمنة.

```csharp
[C#]

void AssertAreEqual(object actual, object expected)
{
    if (!object.Equals(actual, expected))
    {
        throw new FormatException(string.Format("Actual value {0} are not equal to expected {1}.", actual, expected));
    }
}

// يوضح هذا المثال كيفية تغيير طبقة الكائن الذكي في ملف PSD وتصدير / تحديث المحتويات المضمنة الأصلية للكائن الذكي.
const int left = 0;
const int top = 0;
const int right = 0xb;
const int bottom = 0x10;
FileFormat[] formats = new[]
{
    FileFormat.Png, FileFormat.Psd, FileFormat.Bmp, FileFormat.Jpeg, FileFormat.Gif, FileFormat.Tiff, FileFormat.Jpeg2000
};
foreach (FileFormat format in formats)
{
    string formatString = format.ToString().ToLowerInvariant();
    string formatExt = format == FileFormat.Jpeg2000 ? "jpf" : formatString;
    string fileName = "r-embedded-" + formatString;
    string sourceFilePath = fileName + ".psd";
    string pngOutputPath = fileName + "_output.png";
    string psdOutputPath = fileName + "_output.psd";
    string png2OutputPath = fileName + "_updated.png";
    string psd2OutputPath = fileName + "_updated.psd";
    string exportPath = fileName + "_export." + formatExt;
    using (PsdImage image = (PsdImage)Image.Load(sourceFilePath))
    {
        var smartObjectLayer = (SmartObjectLayer)image.Layers[0];

        AssertAreEqual(left, smartObjectLayer.ContentsBounds.Left);
        AssertAreEqual(top, smartObjectLayer.ContentsBounds.Top);
        AssertAreEqual(right, smartObjectLayer.ContentsBounds.Right);
        AssertAreEqual(bottom, smartObjectLayer.ContentsBounds.Bottom);

        // لنقوم بتصدير صورة الكائن الذكي المضمنة من طبقة الكائن الذكي PSD
        smartObjectLayer.ExportContents(exportPath);

        // دعنا نتحقق مما إذا تم حفظ الصورة الأصلية بشكل صحيح
        image.Save(psdOutputPath, new PsdOptions(image));
        image.Save(pngOutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });

        using (var innerImage = (RasterImage)smartObjectLayer.LoadContents(null))
        {
            AssertAreEqual(format, innerImage.FileFormat);

            // لنقلب صورة الكائن الذكية الأصلية
            var pixels = innerImage.LoadArgb32Pixels(innerImage.Bounds);
            for (int i = 0; i < pixels.Length; i++)
            {
                var pixel = pixels[i];
                var alpha = (int)(pixel & 0xff000000);
                pixels[i] = (~(pixel & 0x00ffffff)) | alpha;
            }

            innerImage.SaveArgb32Pixels(innerImage.Bounds, pixels);

            // لنستبدل صورة الكائن الذكي المضمنة في طبقة PSD
            smartObjectLayer.ReplaceContents(innerImage);
        }

        // دعنا نتحقق مما إذا تم حفظ الصورة المحدثة بشكل صحيح
        image.Save(psd2OutputPath, new PsdOptions(image));
        image.Save(png2OutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
    }
}
```

### أنظر أيضا

* class [SmartObjectLayer](../)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd.Layers.SmartObjects](../../smartobjectlayer/)
* المجسم [Aspose.PSD](../../../)


