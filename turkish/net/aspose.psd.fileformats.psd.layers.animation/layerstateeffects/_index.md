---
title: "Sınıf LayerStateEffects"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.FileFormats.Psd.Layers.Animation.LayerStateEffects sınıfı. Katman durum efektleri"
type: docs
weight: 1970
url: /tr/net/aspose.psd.fileformats.psd.layers.animation/layerstateeffects/
---
{{< psd/tize >}}
## LayerStateEffects class

Katman durumu etkileri.

```csharp
public class LayerStateEffects
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Effects](../../aspose.psd.fileformats.psd.layers.animation/layerstateeffects/effects/) { get; } | Katman efektlerini alır. |
| [IsVisible](../../aspose.psd.fileformats.psd.layers.animation/layerstateeffects/isvisible/) { get; set; } | Bu örneğin görünür olup olmadığını gösteren bir değeri alır veya ayarlar. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [AddColorOverlay](../../aspose.psd.fileformats.psd.layers.animation/layerstateeffects/addcoloroverlay/)() | Renk bindirme efektini ekler. |
| [AddDropShadow](../../aspose.psd.fileformats.psd.layers.animation/layerstateeffects/adddropshadow/)() | Gölge düşürme efektini ekler. |
| [AddGradientOverlay](../../aspose.psd.fileformats.psd.layers.animation/layerstateeffects/addgradientoverlay/)() | Gradyan bindirme efektini ekler. |
| [AddInnerShadow](../../aspose.psd.fileformats.psd.layers.animation/layerstateeffects/addinnershadow/)() | İç gölge efektini ekler. |
| [AddOuterGlow](../../aspose.psd.fileformats.psd.layers.animation/layerstateeffects/addouterglow/)() | Dış parıltı efektini ekler. |
| [AddPatternOverlay](../../aspose.psd.fileformats.psd.layers.animation/layerstateeffects/addpatternoverlay/)() | Desen bindirme efektini ekler. |
| [AddStroke](../../aspose.psd.fileformats.psd.layers.animation/layerstateeffects/addstroke/)(FillType) | Kontur efektini ekler. |
| [ClearLayerStyle](../../aspose.psd.fileformats.psd.layers.animation/layerstateeffects/clearlayerstyle/)() | Tüm katman stil efektlerini temizler. |
| [RemoveEffectAt](../../aspose.psd.fileformats.psd.layers.animation/layerstateeffects/removeeffectat/)(int) | Belirli indeksteki katman efektini kaldırır. |

## Örnekler

Aşağıdaki kod, Timeline çerçevelerindeki efekt desteğini gösterir.

```csharp
[C#]

string sourceFile = "4_animated.psd";
string outputFile = "output.psd";

using (var psdImage = (PsdImage)Image.Load(sourceFile))
{
    Timeline timeline = psdImage.Timeline;

    var layerStateEffects11 = timeline.Frames[1].LayerStates[1].StateEffects;

    layerStateEffects11.AddDropShadow();
    layerStateEffects11.AddGradientOverlay();

    var layerStateEffects21 = timeline.Frames[2].LayerStates[1].StateEffects;
    layerStateEffects21.AddStroke(FillType.Color);
    layerStateEffects21.IsVisible = false;

    psdImage.Save(outputFile);
}
```

### Ayrıca Bakınız

* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../)


