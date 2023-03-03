---
title: FXidResource.FXidResource
second_title: Aspose.PSD لمرجع .NET API
description: FXidResource البناء. يقوم بتهيئة مثيل جديد لملفFXidResource فئة .
type: docs
weight: 10
url: /ar/net/aspose.psd.fileformats.psd.layers.layerresources/fxidresource/fxidresource/
---
## FXidResource constructor

يقوم بتهيئة مثيل جديد لملف[`FXidResource`](../) فئة .

```csharp
public FXidResource(int key, int version, FilterEffectMaskData[] filterEffectMasks)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| key | Int32 | مفتاح المورد. |
| version | Int32 | النسخة. |
| filterEffectMasks | FilterEffectMaskData[] | أقنعة تأثير المرشح. |

### أمثلة

يوضح هذا المثال كيفية الحصول على خصائص مورد FXidResource وتعيينها.

```csharp
[C#]

string inputFilePath = "psdnet414_3.psd";
string output = "out_psdnet414_3.psd";

int resLength = 1144;
int maskLength = 369;

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

### أنظر أيضا

* class [FilterEffectMaskData](../../filtereffectmaskdata/)
* class [FXidResource](../)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../fxidresource/)
* المجسم [Aspose.PSD](../../../)


