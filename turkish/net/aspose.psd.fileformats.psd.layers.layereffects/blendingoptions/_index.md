---
title: Class BlendingOptions
second_title: Aspose.PSD for .NET API Referansı
description: Aspose.PSD.FileFormats.Psd.Layers.LayerEffects.BlendingOptions sınıf. Karıştırma Seçenekleri. Bu effects katmanı için api sağlayan Lfx2Resource için bir sarıcıdır.
type: docs
weight: 2100
url: /tr/net/aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/
---
## BlendingOptions class

Karıştırma Seçenekleri. Bu, effects katmanı için api sağlayan Lfx2Resource için bir sarıcıdır.

```csharp
public class BlendingOptions
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Effects](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/effects/) { get; } | Etkileri alır. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [AddColorOverlay](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addcoloroverlay/)() | Renk kaplamasını ekler. |
| [AddDropShadow](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/adddropshadow/)() | Gölge efekti ekler. |
| [AddGradientOverlay](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addgradientoverlay/)() | Degrade kaplamasını ekler. |
| [AddInnerShadow](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addinnershadow/)() | İç gölge efekti ekler. |
| [AddOuterGlow](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addouterglow/)() | Dış ışıma efektini ekler. |
| [AddPatternOverlay](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addpatternoverlay/)() | Model yerleşimini ekler. |
| [AddStroke](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addstroke/)(FillType) | Kontur efekti ekler. |

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

* ad alanı [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../aspose.psd.fileformats.psd.layers.layereffects/)
* toplantı [Aspose.PSD](../../)


