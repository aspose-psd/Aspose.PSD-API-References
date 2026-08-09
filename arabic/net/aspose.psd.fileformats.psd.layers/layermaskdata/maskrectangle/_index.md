---
title: "LayerMaskData.MaskRectangle"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "خاصية LayerMaskData. يحصل على أو يضبط مستطيل القناع لقناع الطبقة في ملف PSD. يأخذ خصائص اليسار واليمين والأعلى والأسفل وينشئ Rectangle"
type: docs
weight: 70
url: /ar/net/aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/
---
{{< psd/tize >}}
## LayerMaskData.MaskRectangle property

يحصل على أو يضبط القناع [`Rectangle`](../../../aspose.psd/rectangle/) لقناع الطبقة في ملف PSD. يأخذ خصائص اليسار واليمين والأعلى والأسفل وينشئ [`Rectangle`](../../../aspose.psd/rectangle/)

```csharp
public Rectangle MaskRectangle { get; set; }
```

### Property Value

مستطيل القناع.

## أمثلة

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

// يحصل على قيمة int محوّلة إلى ترتيب البايتات big-endian.
byte[] GetBigEndianBytesInt32(int value)
{
    byte[] bytes = new byte[4];
    bytes[0] = (byte)((value >> 24) & 0x000000FF);
    bytes[1] = (byte)((value >> 16) & 0x000000FF);
    bytes[2] = (byte)((value >> 8) & 0x000000FF);
    bytes[3] = (byte)value;
    return bytes;
}

// يحصل على القيمة محوّلة من big-endian إلى Int32.
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

// يحصل على قناع نقطي من طبقة صورة PSD ويحفظه إلى ملف
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

// يضيف قناعًا نقطيًا من الملف إلى الطبقة ويحفظه كصورة بتنسيق PSD
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

    // مجرد إضافة LayerMaskData لا يكفي للحفظ الصحيح لأن القنوات لم يتم تحديثها؛
    // layer.LayerMaskData = mask; // هذا لا يضيف قناة القناع

    // إضافة (أو تحديث) القناع
    layer.AddLayerMask(maskData); // But this adds / updates both the mask and channels!
}

// يوضح هذا المثال كيفية الحصول على أقنعة الطبقة النقطية وتحديثها وإزالتها وإضافتها في ملف Adobe® Photoshop® برمجيًا.
var pngOptions = new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha };
var sourceFilePath = "FourWithMasks.psd";
using (PsdImage image = (PsdImage)Image.Load(sourceFilePath))
{
    Layer layer = image.Layers[2];

    // احصل على قناع نقطي من الطبقة واحفظه إلى ملف
    SaveRasterMask("FourWithMasks2.msk", layer);

    // غيّر قناع الطبقة (عكس) واحفظ الصورة
    var mask = layer.LayerMaskData;
    byte[] maskData = mask.ImageData;
    for (int i = 0; i < maskData.Length; i++)
    {
        maskData[i] = (byte)~maskData[i];
    }

    // مجرد تغيير LayerMaskData يكفي لتأثير العرض
    image.Save("FourWithMasksUpdated2.png", pngOptions);

    // لكن مجرد تغيير LayerMaskData لا يكفي للحفظ الصحيح لأن القنوات لم يتم تحديثها؛
    layer.LayerMaskData = mask; // This does not work either
    layer.AddLayerMask(mask); // But this updates both the mask and channels!
    image.Save("FourWithMasksUpdated2.psd");

    // إزالة قناع نقطي من الطبقة وحفظ الصورة
    layer.LayerMaskData = null; // Just removing LayerMaskData is enough to effect rendering but not for saving to PSD format
    image.Save("FourWithMasksRemoved2.png", pngOptions);

    layer.AddLayerMask(null); // But this removes both the mask and the mask channel!
    image.Save("FourWithMasksRemoved2.psd");

    // إضافة قناع نقطي من الملف إلى الطبقة وحفظ الصورة
    AddRasterMask(layer, "raster.msk");
    image.Save("FourWithMasksAdded2.png", pngOptions);
    image.Save("FourWithMasksAdded2.psd");
}
```

### انظر أيضًا

* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [LayerMaskData](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


