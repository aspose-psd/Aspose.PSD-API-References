---
title: Class InnerShadowEffect
second_title: Aspose.PSD for .NET API Referansı
description: Aspose.PSD.FileFormats.Psd.Layers.LayerEffects.InnerShadowEffect sınıf. İç Gölge Katmanı etkisi
type: docs
weight: 2160
url: /tr/net/aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/
---
## InnerShadowEffect class

İç Gölge Katmanı etkisi

```csharp
public class InnerShadowEffect : IShadowEffect
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Angle](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/angle/) { get; set; } | Açıyı derece cinsinden alır veya ayarlar. |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/blendmode/) { get; set; } | Karışım modunu alır veya ayarlar. |
| [Color](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/color/) { get; set; } | Rengi alır veya ayarlar. |
| [Distance](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/distance/) { get; set; } | Mesafeyi piksel cinsinden alır veya ayarlar. |
| [EffectType](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/effecttype/) { get; } | Bir tür effect alır |
| [IsVisible](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/isvisible/) { get; set; } | Bu örneğin görünür olup olmadığını belirten bir değer alır veya ayarlar. |
| [Noise](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/noise/) { get; set; } | Gürültüyü alır veya ayarlar. |
| [Opacity](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/opacity/) { get; set; } | Opaklığı alır veya ayarlar. |
| [Size](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/size/) { get; set; } | Bulanıklık değerini piksel cinsinden alır veya ayarlar. |
| [Spread](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/spread/) { get; set; } | Yayılmayı (boğma) yüzde olarak alır veya ayarlar. |
| [UseGlobalLight](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/usegloballight/) { get; set; } | [Bu açıyı tüm katman efektlerinde kullanıp kullanmayacağını] belirten bir değer alır veya ayarlar. |

### Örnekler

Aşağıdaki kod, İç Gölge Katmanı Efekti ayarlarının nasıl değiştirileceğini gösterir.

```csharp
[C#]

string sourceFile = "example.psd";
string outputFile = "sample_out.psd";

// Varolan bir görüntüyü PsdImage sınıfının bir örneğine yükleyin
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

### Ayrıca bakınız

* interface [IShadowEffect](../ishadoweffect/)
* ad alanı [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../aspose.psd.fileformats.psd.layers.layereffects/)
* toplantı [Aspose.PSD](../../)


