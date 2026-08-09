---
title: "تعداد ColorSpace"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "Aspose.PSD.FileFormats.Psd.Resources.Enums.ColorSpace enum. أنواع فضاءات الألوان"
type: docs
weight: 4160
url: /ar/net/aspose.psd.fileformats.psd.resources.enums/colorspace/
---
{{< psd/tize >}}
## ColorSpace enumeration

أنواع مساحة اللون.

```csharp
public enum ColorSpace : ushort
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| RGB | `0` | فضاء اللون RGB. |
| HSB | `1` | فضاء اللون HSB. |
| CMYK | `2` | فضاء اللون CMYK. |
| Lab | `7` | فضاء اللون Lab. |
| GrayScale | `8` | فضاء اللون GrayScale. |

## أمثلة

الكود التالي يوضح كيفية تغيير Layer Mask Display Options على صور 16‑بت من خلال تعديل خصائص LmskResource.

```csharp
[C#]

string sourceFile = "sourceFile.psd";
string outputPsd = "sourceFile_output.psd";

void AssertAreEqual(object expected, object actual)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception("Objects are not equal.");
    }
}

// تحميل صورة 16-بت.
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    // العثور على LmskResource.
    LmskResource lmskResource = new LmskResource();
    foreach (var res in image.GlobalLayerResources)
    {
        if (res is LmskResource)
        {
            lmskResource = (LmskResource)res;
            break;
        }
    }

    // تحقق من خصائص LmskResource.
    AssertAreEqual(lmskResource.ColorSpace, ColorSpace.RGB);
    AssertAreEqual(lmskResource.ColorComponent1, (ushort)65535);
    AssertAreEqual(lmskResource.ColorComponent2, (ushort)0);
    AssertAreEqual(lmskResource.ColorComponent3, (ushort)0);
    AssertAreEqual(lmskResource.ColorComponent4, (ushort)0);
    AssertAreEqual(lmskResource.Opacity, (short)45);
    AssertAreEqual(lmskResource.Flag, (byte)128);

    // تغيير خصائص LmskResource.
    lmskResource.ColorSpace = ColorSpace.HSB;
    lmskResource.ColorComponent1 = 7854;
    lmskResource.ColorComponent2 = 10;
    lmskResource.ColorComponent3 = 15484;
    lmskResource.Opacity = 85;

    // حفظ الصورة.
    image.Save(outputPsd);
}
```

### انظر أيضًا

* namespace [Aspose.PSD.FileFormats.Psd.Resources.Enums](../../aspose.psd.fileformats.psd.resources.enums/)
* assembly [Aspose.PSD](../../)


