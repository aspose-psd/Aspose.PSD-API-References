---
title: LayerMaskData.MaskRectangle
second_title: Aspose.PSD لمرجع .NET API
description: LayerMaskData ملكية. الحصول على القناع أو تحديدهRectangleقناع الطبقة في ملف PSD. يأخذ خصائص وينشئ اليسار واليمين والعلوي والسفليRectangle
type: docs
weight: 70
url: /ar/net/aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/
---
## LayerMaskData.MaskRectangle property

الحصول على القناع أو تحديده[`Rectangle`](../../../aspose.psd/rectangle/)قناع الطبقة في ملف PSD. يأخذ خصائص وينشئ اليسار واليمين والعلوي والسفلي[`Rectangle`](../../../aspose.psd/rectangle/)

```csharp
public Rectangle MaskRectangle { get; set; }
```

### Property_Value

مستطيل القناع .

### أمثلة

يوضح هذا المثال كيفية الحصول على أقنعة الطبقة النقطية وتحديثها وإزالتها وإضافتها في ملف Adobe® Photoshop® برمجيًا.

```csharp
[C#]

void AssertAreEqual(object actual, object expected)
{
    if (!object.Equals(actual, expected))
    {
        throw new FormatException(
            string.Format("Actual value {0} are not equal to expected {1}.", actual, expected));
    }
}

// يحصل على تحويل القيمة int إلى ترتيب بايت كبير الحجم.
byte[] GetBigEndianBytesInt32(int value)
{
    byte[] bytes = new byte[4];
    bytes[0] = (byte)((value >> 24) & 0x000000FF);
    bytes[1] = (byte)((value >> 16) & 0x000000FF);
    bytes[2] = (byte)((value >> 8) & 0x000000FF);
    bytes[3] = (byte)value;
    return bytes;
}

// يحصل على القيمة المحولة من endian الكبير إلى Int32.
int FromBigEndianToInt32(byte[] bytes, int index)
{
    if (bytes == null)
    {
        throw new ArgumentNullException("bytes");
    }

    if (index < 0 || index + 4 > bytes.Length)
    {
        throw new ArgumentOutOfRangeException("index", "The index falls outside the bytes array.");
    }

    return (bytes[index] << 24) | (bytes[index + 1] << 16) | (bytes[index + 2] << 8) | bytes[index + 3];
}

// يحصل على قناع نقطي من طبقة صورة PSD ويحفظه في ملف
void SaveRasterMask(string maskFilePath, Layer layer)
{
    LayerMaskDataShort maskData = (LayerMaskDataShort)layer.LayerMaskData;

    using (var container = FileStreamContainer.CreateFileStream(maskFilePath, false))
    {
        container.Write(GetBigEndianBytesInt32(maskData.Top));
        container.Write(GetBigEndianBytesInt32(maskData.Left));
        container.Write(GetBigEndianBytesInt32(maskData.Bottom));
        container.Write(GetBigEndianBytesInt32(maskData.Right));
        container.WriteByte(maskData.DefaultColor);
        container.WriteByte((byte)maskData.Flags);
        container.Write(GetBigEndianBytesInt32(maskData.ImageData.Length));
        container.Write(maskData.ImageData, 0, maskData.ImageData.Length);
    }
}

// يضيف قناع نقطي من الملف إلى الطبقة ويحفظه في صورة تنسيق PSD
void AddRasterMask(Layer layer, string maskSourcePath)
{
    var maskData = new LayerMaskDataShort();
    using (FileStreamContainer container = FileStreamContainer.OpenFileStream(maskSourcePath))
    {
        byte[] bytes = new byte[22];
        AssertAreEqual(container.Read(bytes), 22);
        maskData.Top = FromBigEndianToInt32(bytes, 0);
        maskData.Left = FromBigEndianToInt32(bytes, 4);
        maskData.Bottom = FromBigEndianToInt32(bytes, 8);
        maskData.Right = FromBigEndianToInt32(bytes, 12);
        maskData.DefaultColor = bytes[16];
        maskData.Flags = (LayerMaskFlags)bytes[17];
        int imageDataLength = FromBigEndianToInt32(bytes, 18);
        byte[] data = new byte[imageDataLength];
        AssertAreEqual(maskData.MaskRectangle.Width * maskData.MaskRectangle.Height, imageDataLength);
        AssertAreEqual(container.Read(data), imageDataLength);
        maskData.ImageData = data;
    }

    // لا يكفي مجرد إضافة LayerMaskData للحفظ الصحيح لأن القنوات لا يتم تحديثها ;
    // layer.LayerMaskData = قناع ; // هذا لا يضيف قناة القناع

    // أضف (أو حدّث) القناع
    layer.AddLayerMask(maskData); // لكن هذا يضيف / يحدّث كلاً من القناع والقنوات!
}

// يوضح هذا المثال كيفية الحصول على أقنعة الطبقة النقطية وتحديثها وإزالتها وإضافتها في ملف Adobe® Photoshop® برمجيًا.
var pngOptions = new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha };
var sourceFilePath = "FourWithMasks.psd";
using (PsdImage image = (PsdImage)Image.Load(sourceFilePath))
{
    Layer layer = image.Layers[2];

    // احصل على قناع نقطي من الطبقة واحفظه في ملف
    SaveRasterMask("FourWithMasks2.msk", layer);

    // تغيير قناع الطبقة (عكس) وحفظ الصورة
    var mask = layer.LayerMaskData;
    byte[] maskData = mask.ImageData;
    for (int i = 0; i < maskData.Length; i++)
    {
        maskData[i] = (byte)~maskData[i];
    }

    // فقط تغيير LayerMaskData يكفي لإحداث تأثير
    image.Save("FourWithMasksUpdated2.png", pngOptions);

    // لكن مجرد تغيير LayerMaskData لا يكفي للحفظ الصحيح لأن القنوات لا يتم تحديثها ;
    layer.LayerMaskData = mask; // هذا لا يعمل أيضا
    layer.AddLayerMask(mask); // لكن هذا يقوم بتحديث كل من القناع والقنوات!
    image.Save("FourWithMasksUpdated2.psd");

    // إزالة قناع نقطي من الطبقة وحفظ الصورة
    layer.LayerMaskData = null; // فقط إزالة LayerMaskData كافية لإحداث تأثير ولكن ليس للحفظ بتنسيق PSD
    image.Save("FourWithMasksRemoved2.png", pngOptions);

    layer.AddLayerMask(null); // لكن هذا يزيل القناع وقناة القناع!
    image.Save("FourWithMasksRemoved2.psd");

    // أضف قناع نقطي من الملف إلى الطبقة واحفظ الصورة
    AddRasterMask(layer, "raster.msk");
    image.Save("FourWithMasksAdded2.png", pngOptions);
    image.Save("FourWithMasksAdded2.psd");
}
```

### أنظر أيضا

* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [LayerMaskData](../)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd.Layers](../../layermaskdata/)
* المجسم [Aspose.PSD](../../../)


