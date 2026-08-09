---
title: "الفئة InnerShadowEffect"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerEffects.InnerShadowEffect فئة. تأثير طبقة الظل الداخلي"
type: docs
weight: 2350
url: /ar/net/aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/
---
{{< psd/tize >}}
## InnerShadowEffect class

تأثير طبقة الظل الداخلي.

```csharp
public class InnerShadowEffect : IShadowEffect
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Angle](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/angle/) { get; set; } | يحصل أو يضبط الزاوية بالدرجات. |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/blendmode/) { get; set; } | يحصل أو يضبط وضع المزج. |
| [Color](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/color/) { get; set; } | يحصل أو يعيّن اللون. |
| [Distance](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/distance/) { get; set; } | يحصل أو يضبط المسافة بالبكسل. |
| [EffectType](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/effecttype/) { get; } | يحصل على نوع من التأثير |
| [IsVisible](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/isvisible/) { get; set; } | يحصل أو يضبط قيمة تشير إلى ما إذا كانت هذه الحالة مرئية. |
| [Noise](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/noise/) { get; set; } | يحصل أو يضبط الضوضاء. |
| [Opacity](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/opacity/) { get; set; } | يحصل أو يعيّن الشفافية. |
| [Size](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/size/) { get; set; } | يحصل أو يضبط قيمة الضبابية بالبكسل. |
| [Spread](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/spread/) { get; set; } | يحصل أو يضبط الانتشار (الاختناق) كنسبة مئوية. |
| [UseGlobalLight](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/usegloballight/) { get; set; } | يحصل أو يضبط قيمة تشير إلى ما إذا كان [use this angle in all of the layer effects]. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [GetEffectBounds](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/geteffectbounds/)(Rectangle, int) | احسب واحصل على حدود بكسلات التأثير بناءً على حدود بكسلات الطبقة المدخلة. |

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

* interface [IShadowEffect](../ishadoweffect/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../)


