---
title: "Sınıf BlendingOptions"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerEffects.BlendingOptions sınıfı. BlendingOptions. Katman efektleri için API sağlayan BaseFxResource için bir sarmalayıcıdır."
type: docs
weight: 2290
url: /tr/net/aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/
---
{{< psd/tize >}}
## BlendingOptions class

BlendingOptions. Katman efektleri için API sağlayan BaseFxResource için bir sarmalayıcıdır.

```csharp
public class BlendingOptions
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [AreEffectsEnabled](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/areeffectsenabled/) { get; set; } | Tüm katman efektlerinin görünürlüğünü alır veya ayarlar. |
| [Effects](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/effects/) { get; set; } | Efektleri alır. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [AddColorOverlay](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addcoloroverlay/)() | Renk kaplamasını ekler. |
| [AddDropShadow](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/adddropshadow/)() | Gölge düşürme efektini ekler. |
| [AddGradientOverlay](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addgradientoverlay/)() | Degrade kaplamasını ekler. |
| [AddInnerShadow](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addinnershadow/)() | İç gölge efektini ekler. |
| [AddOuterGlow](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addouterglow/)() | Dış parıltı efektini ekler. |
| [AddPatternOverlay](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addpatternoverlay/)() | Desen kaplamasını ekler. |
| [AddStroke](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addstroke/)(FillType) | Kontur efektini ekler. |

## Örnekler

Aşağıdaki kod, İç Gölge Katman Efekti ayarlarının nasıl değiştirileceğini gösterir.

```csharp
[C#]

string sourceFile = "example.psd";
string outputFile = "sample_out.psd";

// Mevcut bir görüntüyü PsdImage sınıfının bir örneğine yükle
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

### Ayrıca Bakınız

* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../)


