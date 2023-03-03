---
title: Class InnerShadowEffect
second_title: Aspose.PSD لمرجع .NET API
description: Aspose.PSD.FileFormats.Psd.Layers.LayerEffects.InnerShadowEffect فصل. تأثير طبقة الظل الداخلية
type: docs
weight: 2160
url: /ar/net/aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/
---
## InnerShadowEffect class

تأثير طبقة الظل الداخلية

```csharp
public class InnerShadowEffect : IShadowEffect
```

## الخصائص

| اسم | وصف |
| --- | --- |
| [Angle](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/angle/) { get; set; } | الحصول على الزاوية أو تحديدها بالدرجات . |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/blendmode/) { get; set; } | الحصول على أو تحديد وضع المزج . |
| [Color](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/color/) { get; set; } | الحصول على اللون أو تحديده . |
| [Distance](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/distance/) { get; set; } | الحصول على أو تحديد المسافة بالبكسل . |
| [EffectType](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/effecttype/) { get; } | يحصل على نوع من التأثير |
| [IsVisible](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/isvisible/) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كان هذا المثيل مرئيًا. |
| [Noise](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/noise/) { get; set; } | الحصول على الضوضاء أو ضبطها . |
| [Opacity](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/opacity/) { get; set; } | الحصول على التعتيم أو تعيينه . |
| [Size](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/size/) { get; set; } | الحصول على أو تعيين قيمة التمويه بالبكسل. |
| [Spread](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/spread/) { get; set; } | الحصول على أو تحديد الانتشار (الاختناق) كنسبة مئوية. |
| [UseGlobalLight](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/usegloballight/) { get; set; } | الحصول على أو تعيين قيمة تشير إلى [استخدام هذه الزاوية في جميع تأثيرات الطبقة] . |

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

* interface [IShadowEffect](../ishadoweffect/)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../aspose.psd.fileformats.psd.layers.layereffects/)
* المجسم [Aspose.PSD](../../)


