---
title: Class DropShadowEffect
second_title: Aspose.PSD for .NET API Referansı
description: Aspose.PSD.FileFormats.Psd.Layers.LayerEffects.DropShadowEffect sınıf. Alt Gölge Katmanı efekti
type: docs
weight: 2120
url: /tr/net/aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/
---
## DropShadowEffect class

Alt Gölge Katmanı efekti

```csharp
public class DropShadowEffect : IShadowEffect
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Angle](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/angle/) { get; set; } | Açıyı derece cinsinden alır veya ayarlar. |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/blendmode/) { get; set; } | Karışım modunu alır veya ayarlar. |
| [Color](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/color/) { get; set; } | Rengi alır veya ayarlar. |
| [Distance](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/distance/) { get; set; } | Mesafeyi piksel cinsinden alır veya ayarlar. |
| [EffectType](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/effecttype/) { get; } | Bir tür effect alır |
| [IsVisible](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/isvisible/) { get; set; } | Bu örneğin görünür olup olmadığını belirten bir değer alır veya ayarlar. |
| [KnocksOut](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/knocksout/) { get; set; } | [Görmez]. olup olmadığını gösteren bir değer alır veya ayarlar. |
| [Noise](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/noise/) { get; set; } | Gürültüyü alır veya ayarlar. |
| [Opacity](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/opacity/) { get; set; } | Opaklığı alır veya ayarlar. |
| [Size](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/size/) { get; set; } | Bulanıklık değerini piksel cinsinden alır veya ayarlar. |
| [Spread](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/spread/) { get; set; } | Yoğunluğu yüzde olarak alır veya ayarlar. |
| [UseGlobalLight](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/usegloballight/) { get; set; } | [Bu açıyı tüm katman efektlerinde kullanıp kullanmayacağını] belirten bir değer alır veya ayarlar. |

### Örnekler

Aşağıdaki kod, genel açı değerini değiştirmek için PsdImage.GlobalAngle özelliğine yönelik desteği gösterir.

```csharp
[C#]

// DropShadowEffect.UseGlobalLight özelliği 'true' olduğunda, DropShadowEffect nesnesi PsdImage.GlobalAngle özelliğinden açı değeri kullanır.

using (PsdImage image = (PsdImage)Image.Load("4.psd"))
{
    image.GlobalAngle = 30;
    image.Save("output.psd");
}
```

Aşağıdaki kod, DropShadowEffect'in Opacity özelliğinin kullanımını gösterir.

```csharp
[C#]

string inputFile = "input.psd";
string outputImage20 = "outputImage20.png";
string outputImage200 = "outputImage200.png";

using (PsdImage psdImage = (PsdImage)Image.Load(inputFile, new LoadOptions()))
{
    Layer workLayer = psdImage.Layers[1];

    DropShadowEffect dropShadowEffect = workLayer.BlendingOptions.AddDropShadow();
    dropShadowEffect.Distance = 0;
    dropShadowEffect.Size = 8;

    // Opaklık = 20 ile Örnek
    dropShadowEffect.Opacity = 20;
    psdImage.Save(outputImage20, new PngOptions());

    // Opaklık = 20 ile Örnek0
    dropShadowEffect.Opacity = 200;
    psdImage.Save(outputImage200, new PngOptions());
}
```

### Ayrıca bakınız

* interface [IShadowEffect](../ishadoweffect/)
* ad alanı [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../aspose.psd.fileformats.psd.layers.layereffects/)
* toplantı [Aspose.PSD](../../)


