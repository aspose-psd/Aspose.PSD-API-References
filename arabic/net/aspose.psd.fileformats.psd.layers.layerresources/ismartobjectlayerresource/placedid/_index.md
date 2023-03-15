---
title: ISmartObjectLayerResource.PlacedId
second_title: Aspose.PSD لمرجع .NET API
description: ISmartObjectLayerResource ملكية. الحصول على أو تعيين المعرف الفريد لبيانات طبقة الكائن الذكي هذه في صورة PSD.
type: docs
weight: 10
url: /ar/net/aspose.psd.fileformats.psd.layers.layerresources/ismartobjectlayerresource/placedid/
---
## ISmartObjectLayerResource.PlacedId property

الحصول على أو تعيين المعرف الفريد لبيانات طبقة الكائن الذكي هذه في صورة PSD.

```csharp
public Guid PlacedId { get; set; }
```

### Property_Value

المعرف الفريد لمورد طبقة الكائن الذكي هذا.

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

* interface [ISmartObjectLayerResource](../)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../ismartobjectlayerresource/)
* المجسم [Aspose.PSD](../../../)


