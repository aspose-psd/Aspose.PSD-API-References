---
title: "LinkResource.Item"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "خاصية LinkResource. يحصل على LinkDataSource عند الفهرس المحدد والذي هو المعرف الفريد لمصدر بيانات الارتباط"
type: docs
weight: 30
url: /ar/net/aspose.psd.fileformats.psd.layers.layerresources/linkresource/item/
---
{{< psd/tize >}}
## LinkResource indexer

يحصل على [`LinkDataSource`](../../linkdatasource/) عند الفهرس المحدد والذي هو المعرف الفريد لمصدر بيانات الارتباط..

```csharp
public LinkDataSource this[Guid index] { get; }
```

| معامل | الوصف |
| --- | --- |
| فهرس | الفهرس كمعرف فريد لمصدر بيانات الارتباط. |

### قيمة الإرجاع

مثيل [`LinkDataSource`](../../linkdatasource/).

### Property Value

الـ [`LinkDataSource`](../../linkdatasource/).

## أمثلة

الكود التالي يوضح دعم الكائنات الذكية المدمجة.

```csharp
[C#]

void AssertAreEqual(object actual, object expected)
{
    if (!object.Equals(actual, expected))
    {
        throw new FormatException(string.Format("Actual value {0} are not equal to expected {1}.", actual, expected));
    }
}

// هذا المثال يوضح كيفية تغيير طبقة الكائن الذكي في ملف PSD وتصدير / تحديث المحتويات الأصلية المدمجة للكائن الذكي.
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

        // لنقوم بتصدير صورة الكائن الذكي المدمج من طبقة الكائن الذكي في PSD
        smartObjectLayer.ExportContents(exportPath);

        // لنتحقق مما إذا كانت الصورة الأصلية محفوظة بشكل صحيح
        image.Save(psdOutputPath, new PsdOptions(image));
        image.Save(pngOutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });

        using (var innerImage = (RasterImage)smartObjectLayer.LoadContents(null))
        {
            AssertAreEqual(format, innerImage.FileFormat);

            // لنقلب صورة الكائن الذكي الأصلية
            var pixels = innerImage.LoadArgb32Pixels(innerImage.Bounds);
            for (int i = 0; i < pixels.Length; i++)
            {
                var pixel = pixels[i];
                var alpha = (int)(pixel & 0xff000000);
                pixels[i] = (~(pixel & 0x00ffffff)) | alpha;
            }

            innerImage.SaveArgb32Pixels(innerImage.Bounds, pixels);

            // لنستبدل صورة الكائن الذكي المدمج في طبقة PSD
            smartObjectLayer.ReplaceContents(innerImage);
        }

        // لنتحقق مما إذا كانت الصورة المحدثة محفوظة بشكل صحيح
        image.Save(psd2OutputPath, new PsdOptions(image));
        image.Save(png2OutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
    }
}
```

### انظر أيضًا

* class [LinkDataSource](../../linkdatasource/)
* class [LinkResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


