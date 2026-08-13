---
title: "Sınıf OuterGlowEffect"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerEffects.OuterGlowEffect sınıfı. Outer Glow Katman efekti"
type: docs
weight: 2370
url: /tr/net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/
---
{{< psd/tize >}}
## OuterGlowEffect class

Dış Parıltı Katman efekti

```csharp
public class OuterGlowEffect : ILayerEffect
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/blendmode/) { get; set; } | Karışım modunu alır veya ayarlar. |
| [EffectType](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/effecttype/) { get; } | Bir efekt türünü alır. |
| [FillColor](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/fillcolor/) { get; set; } | Rengi alır veya ayarlar. |
| [Intensity](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/intensity/) { get; set; } | Açıyı derece cinsinden alır veya ayarlar. |
| [IsAntiAliasing](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/isantialiasing/) { get; set; } | Etkin AntiAliasing efektini alır veya ayarlar |
| [IsSoftBlend](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/issoftblend/) { get; set; } | Kapatma [knocks out] olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [IsVisible](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/isvisible/) { get; set; } | Bu örneğin görünür olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [Jitter](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/jitter/) { get; set; } | Gürültüyü alır veya ayarlar. |
| [Noise](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/noise/) { get; set; } | Gürültüyü alır veya ayarlar. |
| [Opacity](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/opacity/) { get; set; } | Opaklığı alır veya ayarlar. |
| [Range](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/range/) { get; set; } | Gürültüyü alır veya ayarlar. |
| [Size](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/size/) { get; set; } | Bulanıklık değerini piksel olarak alır. |
| [Spread](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/spread/) { get; set; } | Yoğunluğu yüzde olarak alır veya ayarlar. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [GetEffectBounds](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/geteffectbounds/)(Rectangle, int) | Girdi katman piksel sınırlarına dayanarak efekt piksel sınırlarını hesaplar ve alır. |

## Örnekler

Aşağıdaki kod, OuterGlowEffect desteğini gösterir.

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

### Ayrıca Bakınız

* interface [ILayerEffect](../ilayereffect/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../)


