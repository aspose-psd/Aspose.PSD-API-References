---
title: LinkResource.Item
second_title: Aspose.PSD لمرجع .NET API
description: LinkResource ملكية. يحصل على ملفLinkDataSource في الفهرس المحدد وهو المعرف الفريد لمصدر بيانات الارتباط ..
type: docs
weight: 30
url: /ar/net/aspose.psd.fileformats.psd.layers.layerresources/linkresource/item/
---
## LinkResource indexer

يحصل على ملف[`LinkDataSource`](../../linkdatasource/) في الفهرس المحدد وهو المعرف الفريد لمصدر بيانات الارتباط ..

```csharp
public LinkDataSource this[Guid index] { get; }
```

| معامل | وصف |
| --- | --- |
| index | الفهرس كمعرف فريد لمصدر بيانات الارتباط. |

### قيمة الإرجاع

ملف[`LinkDataSource`](../../linkdatasource/) المثال.

### Property_Value

ملف[`LinkDataSource`](../../linkdatasource/) .

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

* class [LinkDataSource](../../linkdatasource/)
* class [LinkResource](../)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../linkresource/)
* المجسم [Aspose.PSD](../../../)


