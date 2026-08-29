---
title: "الفئة OuterGlowEffect"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "الفئة Aspose.PSD.FileFormats.Psd.Layers.LayerEffects.OuterGlowEffect. تأثير طبقة التوهج الخارجي."
type: docs
weight: 2370
url: /ar/net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/
---
{{< psd/tize >}}
## OuterGlowEffect class

تأثير طبقة التوهج الخارجي.

```csharp
public class OuterGlowEffect : ILayerEffect
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/blendmode/) { get; set; } | يحصل أو يضبط وضع المزج. |
| [EffectType](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/effecttype/) { get; } | يحصل على نوع من نوع التأثير |
| [FillColor](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/fillcolor/) { get; set; } | يحصل أو يعيّن اللون. |
| [Intensity](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/intensity/) { get; set; } | يحصل أو يضبط الزاوية بالدرجات. |
| [IsAntiAliasing](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/isantialiasing/) { get; set; } | يحصل أو يعيّن تأثير AntiAliasing الممكّن |
| [IsSoftBlend](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/issoftblend/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان [knocks out]. |
| [IsVisible](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/isvisible/) { get; set; } | يحصل أو يضبط قيمة تشير إلى ما إذا كانت هذه الحالة مرئية. |
| [Jitter](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/jitter/) { get; set; } | يحصل أو يضبط الضوضاء. |
| [Noise](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/noise/) { get; set; } | يحصل أو يضبط الضوضاء. |
| [Opacity](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/opacity/) { get; set; } | يحصل أو يعيّن الشفافية. |
| [Range](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/range/) { get; set; } | يحصل أو يضبط الضوضاء. |
| [Size](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/size/) { get; set; } | يحصل على قيمة الضبابية بالبكسل. |
| [Spread](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/spread/) { get; set; } | يحصل أو يضبط الشدة كنسبة مئوية. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [GetEffectBounds](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/geteffectbounds/)(Rectangle, int) | احسب واحصل على حدود بكسلات التأثير بناءً على حدود بكسلات الطبقة المدخلة. |

## أمثلة

يوضح الشيفرة التالية دعم OuterGlowEffect.

```csharp
[C#]

string src = "GreenLayer.psd";
string outputPng = "output261.png";

using (var image = (PsdImage)Image.Load(src))
{
    OuterGlowEffect effect = image.Layers[1].BlendingOptions.AddOuterGlow();
    effect.Range = 10;
    effect.Spread = 10;
    ((IColorFillSettings)effect.FillColor).Color = Color.Red;
    effect.Opacity = 128;
    effect.BlendMode = BlendMode.Normal;

    image.Save(outputPng, new PngOptions());
}
```

### انظر أيضًا

* interface [ILayerEffect](../ilayereffect/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../)


