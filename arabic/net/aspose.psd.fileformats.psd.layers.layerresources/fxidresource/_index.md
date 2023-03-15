---
title: Class FXidResource
second_title: Aspose.PSD لمرجع .NET API
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.FXidResource فصل. يحتوي مورد تأثيرات التصفية على قنوات وقناع مستخدم وقناع ورقة لعامل التصفية الذكي.
type: docs
weight: 2460
url: /ar/net/aspose.psd.fileformats.psd.layers.layerresources/fxidresource/
---
## FXidResource class

يحتوي مورد تأثيرات التصفية على قنوات وقناع مستخدم وقناع ورقة لعامل التصفية الذكي.

```csharp
public sealed class FXidResource : LayerResource
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [FXidResource](fxidresource/)(int, int, FilterEffectMaskData[]) | يقوم بتهيئة مثيل جديد لملف`FXidResource` فئة . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [FilterEffectMasks](../../aspose.psd.fileformats.psd.layers.layerresources/fxidresource/filtereffectmasks/) { get; } | يحصل على أقنعة تأثير المرشح . |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/fxidresource/key/) { get; } | يحصل على مفتاح مورد الطبقة. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/fxidresource/length/) { get; } | الحصول على طول مورد الطبقة بالبايت. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/fxidresource/psdversion/) { get; } | يحصل على الحد الأدنى من إصدار psd المطلوب لمورد الطبقة. 0 يشير إلى عدم وجود قيود. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/fxidresource/signature/) { get; } | يحصل على توقيع مورد الطبقة. |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/fxidresource/version/) { get; } | يحصل على الإصدار . |

## طُرق

| اسم | وصف |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/fxidresource/save/)(StreamContainer, int) | يحفظ المورد في حاوية التدفق المحددة. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | إرجاع أString الذي يمثل هذا المثال. |

## مجالات

| اسم | وصف |
| --- | --- |
| const [FEidTypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/fxidresource/feidtypetoolkey/) | مفتاح معلومات أداة النوع FEid. |
| const [FXidTypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/fxidresource/fxidtypetoolkey/) | مفتاح معلومات أداة النوع FXid. |

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

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* المجسم [Aspose.PSD](../../)


