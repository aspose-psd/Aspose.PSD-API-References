---
title: "الفئة BlendingOptions"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerEffects.BlendingOptions فئة. BlendingOptions. إنه غلاف لـ BaseFxResource الذي يوفر واجهة برمجة تطبيقات لتأثيرات الطبقة"
type: docs
weight: 2290
url: /ar/net/aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/
---
{{< psd/tize >}}
## BlendingOptions class

BlendingOptions. إنها غلاف لـ BaseFxResource الذي يوفر API لتأثيرات الطبقة.

```csharp
public class BlendingOptions
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AreEffectsEnabled](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/areeffectsenabled/) { get; set; } | يحصل أو يضبط رؤية جميع تأثيرات الطبقة. |
| [Effects](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/effects/) { get; set; } | يحصل على التأثيرات. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [AddColorOverlay](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addcoloroverlay/)() | يضيف تغطية اللون. |
| [AddDropShadow](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/adddropshadow/)() | يضيف تأثير الظل المنسدل. |
| [AddGradientOverlay](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addgradientoverlay/)() | يضيف تغطية التدرج. |
| [AddInnerShadow](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addinnershadow/)() | يضيف تأثير الظل الداخلي. |
| [AddOuterGlow](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addouterglow/)() | يضيف تأثير التوهج الخارجي. |
| [AddPatternOverlay](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addpatternoverlay/)() | يضيف تغطية النمط. |
| [AddStroke](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addstroke/)(FillType) | يضيف تأثير الحد. |

## أمثلة

الكود التالي يوضح كيفية تغيير إعدادات تأثير طبقة الظل الداخلي.

```csharp
[C#]

string sourceFile = "example.psd";
string outputFile = "sample_out.psd";

// حمّل صورة موجودة إلى مثال من فئة PsdImage
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

### انظر أيضًا

* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../)


