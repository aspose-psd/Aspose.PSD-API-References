---
title: "FXidResource.FXidResource"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "منشئ FXidResource. يهيئ مثيلاً جديداً من فئة FXidResource"
type: docs
weight: 10
url: /ar/net/aspose.psd.fileformats.psd.layers.layerresources/fxidresource/fxidresource/
---
{{< psd/tize >}}
## FXidResource constructor

يهيئ مثيلاً جديداً من الفئة [`FXidResource`](../).

```csharp
public FXidResource(int key, int version, FilterEffectMaskData[] filterEffectMasks)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المفتاح | Int32 | مفتاح المورد. |
| version | Int32 | الإصدار. |
| filterEffectMasks | FilterEffectMaskData[] | أقنعة تأثير الفلتر. |

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

* class [FilterEffectMaskData](../../filtereffectmaskdata/)
* class [FXidResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


