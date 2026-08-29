---
title: "FilterEffectMaskData.FilterEffectMaskData"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "منشئ FilterEffectMaskData. يهيئ مثيلاً جديداً من الفئة FilterEffectMaskData"
type: docs
weight: 10
url: /ar/net/aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/filtereffectmaskdata/
---
{{< psd/tize >}}
## FilterEffectMaskData constructor

يهيئ مثيلاً جديداً من الفئة [`FilterEffectMaskData`](../).

```csharp
public FilterEffectMaskData(string guid, Rectangle rectangle, int pixelsDepth, int maxChannels, 
    ChannelInformation[] channels, ChannelInformation userMask, Rectangle maskRectangle, 
    ChannelInformation sheetMask)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| guid | String | معرف المورد guid. |
| مستطيل | Rectangle | مستطيل القنوات. |
| pixelsDepth | Int32 | عمق البكسلات. |
| maxChannels | Int32 | قيمة الحد الأقصى للقنوات. |
| channels | ChannelInformation[] | القنوات. |
| userMask | ChannelInformation | قناع المستخدم. |
| maskRectangle | Rectangle | مستطيل قناع الورقة. |
| sheetMask | ChannelInformation | قناع الورقة. |

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

* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [ChannelInformation](../../../aspose.psd.fileformats.psd.layers/channelinformation/)
* class [FilterEffectMaskData](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


