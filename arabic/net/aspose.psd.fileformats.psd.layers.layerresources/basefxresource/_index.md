---
title: "الفئة BaseFxResource"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.BaseFxResource الفئة. مورد التأثيرات الأساسية"
type: docs
weight: 2550
url: /ar/net/aspose.psd.fileformats.psd.layers.layerresources/basefxresource/
---
{{< psd/tize >}}
## BaseFxResource class

مورد التأثيرات الأساسي

```csharp
public abstract class BaseFxResource : LayerResource
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [DescriptorVersion](../../aspose.psd.fileformats.psd.layers.layerresources/basefxresource/descriptorversion/) { get; } | يحصل على إصدار الوصف. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | يحصل على مفتاح مورد الطبقة. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/basefxresource/length/) { get; } | يحصل على طول مورد الطبقة بالبايت. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | يحصل على الحد الأدنى لإصدار PSD المطلوب لمورد الطبقة. 0 يعني عدم وجود قيود. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | يحصل على التوقيع. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/basefxresource/save/)(StreamContainer, int) | يحفظ المورد في حاوية الدفق المحددة. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | إرجاع String تمثل هذا المثيل. |

## أمثلة

الكود التالي يوضح دعم مورد متعدد التأثيرات.

```csharp
[C#]

// صورة PSD تحتوي على تأثيرين Drop Shadow
string sourceFile = "MultiExample.psd";
string outputFile1 = "export1.png";
string outputFile2 = "export2.png";
string outputFile3 = "export3.png";

using (PsdImage image = (PsdImage)Aspose.PSD.Image.Load(sourceFile, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    // يعرض صورة PSD مع تأثيرين Drop Shadow
    image.Save(outputFile1, new PngOptions { ColorType = PngColorType.TruecolorWithAlpha });

    var blendingOptions = image.Layers[0].BlendingOptions;

    // يضيف تأثير Drop Shadow ثالث.
    DropShadowEffect dropShadowEffect3 = blendingOptions.AddDropShadow();
    dropShadowEffect3.Color = Color.Red;
    dropShadowEffect3.Distance = 50;
    dropShadowEffect3.Angle = 0;

    // يقوم بعرض صورة PSD مع 3 تأثيرات Drop Shadow
    image.Save(outputFile2, new PngOptions { ColorType = PngColorType.TruecolorWithAlpha });

    // يتم استخدام مورد imfx إذا كانت الطبقة تحتوي على تأثيرات متعددة من نفس النوع.
    var imfx = (ImfxResource)image.Layers[0].Resources[0];

    // يقوم بمسح جميع التأثيرات
    blendingOptions.Effects = new ILayerEffect[0];

    DropShadowEffect dropShadowEffect1 = blendingOptions.AddDropShadow();
    dropShadowEffect1.Color = Color.Blue;
    dropShadowEffect1.Distance = 10;

    // يقوم بعرض صورة PSD مع تأثير واحد Drop Shadow (تم حذف البقية)
    image.Save(outputFile3, new PngOptions { ColorType = PngColorType.TruecolorWithAlpha });

    // يتم استخدام مورد lfx2 إذا لم تحتوي الطبقة على تأثيرات متعددة من نفس النوع.
    var lfx2 = (Lfx2Resource)image.Layers[0].Resources[14];
}
```

### انظر أيضًا

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


