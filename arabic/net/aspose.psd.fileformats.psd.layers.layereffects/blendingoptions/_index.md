---
title: Class BlendingOptions
second_title: Aspose.PSD لمرجع .NET API
description: Aspose.PSD.FileFormats.Psd.Layers.LayerEffects.BlendingOptions فصل. BlendingOptions. إنه غلاف لـ Lfx2Resource الذي يوفر واجهة برمجة تطبيقات لتأثيرات الطبقة
type: docs
weight: 2100
url: /ar/net/aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/
---
## BlendingOptions class

BlendingOptions. إنه غلاف لـ Lfx2Resource الذي يوفر واجهة برمجة تطبيقات لتأثيرات الطبقة

```csharp
public class BlendingOptions
```

## الخصائص

| اسم | وصف |
| --- | --- |
| [Effects](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/effects/) { get; } | يحصل على التأثيرات . |

## طُرق

| اسم | وصف |
| --- | --- |
| [AddColorOverlay](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addcoloroverlay/)() | يضيف تراكب اللون . |
| [AddDropShadow](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/adddropshadow/)() | يضيف تأثير الظل المسقط . |
| [AddGradientOverlay](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addgradientoverlay/)() | يضيف تراكب التدرج . |
| [AddInnerShadow](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addinnershadow/)() | يضيف تأثير الظل الداخلي . |
| [AddOuterGlow](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addouterglow/)() | يضيف تأثير التوهج الخارجي. |
| [AddPatternOverlay](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addpatternoverlay/)() | يضيف تراكب النقش . |
| [AddStroke](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addstroke/)(FillType) | يضيف تأثير ضربة الفرشاة . |

### أمثلة

يوضح الكود التالي كيفية تغيير إعدادات Inner Shadow Layer Effect.

```csharp
[C#]

string sourceFile = "example.psd";
string outputFile = "sample_out.psd";

// تحميل صورة موجودة في مثيل لفئة PsdImage
var loadOptions = new PsdLoadOptions();
loadOptions.LoadEffectsResource = true;
using (var image = (PsdImage)Image.Load(sourceFile, loadOptions))
{
    var layer = image.Layers[image.Layers.Length - 1];
    var shadowEffect = (IShadowEffect)layer.BlendingOptions.Effects[0];

    shadowEffect.Color = Color.Green;
    shadowEffect.Opacity = 128;
    shadowEffect.Distance = 1;
    shadowEffect.UseGlobalLight = false;
    shadowEffect.Size = 2;
    shadowEffect.Angle = 45;
    shadowEffect.Spread = 50;
    shadowEffect.Noise = 5;

    image.Save(outputFile, new PsdOptions(image));
}
```

### أنظر أيضا

* مساحة الاسم [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../aspose.psd.fileformats.psd.layers.layereffects/)
* المجسم [Aspose.PSD](../../)


