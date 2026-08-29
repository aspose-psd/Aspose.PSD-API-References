---
title: "الفئة FilterEffectMaskData"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.FilterEffectMaskData class. فئة بيانات قناع الفلتر"
type: docs
weight: 2740
url: /ar/net/aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/
---
{{< psd/tize >}}
## FilterEffectMaskData class

فئة بيانات قناع الفلتر.

```csharp
public sealed class FilterEffectMaskData
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [FilterEffectMaskData](filtereffectmaskdata/)(string, Rectangle, int, int, ChannelInformation[], ChannelInformation, Rectangle, ChannelInformation) | ينشئ مثيلًا جديدًا من الفئة `FilterEffectMaskData`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Channels](../../aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/channels/) { get; } | يحصل على القنوات. |
| [GUID](../../aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/guid/) { get; } | يحصل على GUID. |
| [Length](../../aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/length/) { get; } | يحصل على طول بيانات قناع الفلتر بالبايت. |
| [MaskRectangle](../../aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/maskrectangle/) { get; } | يحصل على مستطيل قناع الورقة. |
| [MaxChannels](../../aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/maxchannels/) { get; } | يحصل على الحد الأقصى لعدد القنوات. |
| [PixelsDepth](../../aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/pixelsdepth/) { get; } | يحصل على عمق البكسلات. |
| [Rectangle](../../aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/rectangle/) { get; } | يحصل على مستطيل القنوات. |
| [SheetMask](../../aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/sheetmask/) { get; } | يحصل على قناع الورقة. |
| [UserMask](../../aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/usermask/) { get; } | يحصل على قناع المستخدم. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [SaveData](../../aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/savedata/)(StreamContainer) | يحفظ المورد في حاوية الدفق المحددة. |

## أمثلة

يوضح هذا المثال كيفية الحصول على خصائص مورد FXidResource وتعيينها.

```csharp
[C#]

string inputFilePath = "psdnet414_3.psd";
string output = "out_psdnet414_3.psd";

int resLength = 1144;
long maskLength = 369;

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new FormatException(message ?? "Objects are not equal.");
    }
}

using (var psdImage = (PsdImage)Image.Load(inputFilePath))
{
    FXidResource fXidResource = (FXidResource)psdImage.GlobalLayerResources[3];

    AssertAreEqual(resLength, fXidResource.Length);
    foreach (var maskData in fXidResource.FilterEffectMasks)
    {
        AssertAreEqual(maskLength, maskData.Length);
    }

    psdImage.Save(output);
}

// تحقق بعد الحفظ
using (var psdImage = (PsdImage)Image.Load(output))
{
    FXidResource fXidResource = (FXidResource)psdImage.GlobalLayerResources[3];

    AssertAreEqual(resLength, fXidResource.Length);
    foreach (var maskData in fXidResource.FilterEffectMasks)
    {
        AssertAreEqual(maskLength, maskData.Length);
    }
}
```

### انظر أيضًا

* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


