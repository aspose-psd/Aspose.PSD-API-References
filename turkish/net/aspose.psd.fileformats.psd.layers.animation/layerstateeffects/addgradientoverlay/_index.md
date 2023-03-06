---
title: LayerStateEffects.AddGradientOverlay
second_title: Aspose.PSD for .NET API Referansı
description: LayerStateEffects yöntem. Degrade kaplama efektini ekler.
type: docs
weight: 50
url: /tr/net/aspose.psd.fileformats.psd.layers.animation/layerstateeffects/addgradientoverlay/
---
## LayerStateEffects.AddGradientOverlay method

Degrade kaplama efektini ekler.

```csharp
public GradientOverlayEffect AddGradientOverlay()
```

### Geri dönüş değeri

yeni örneğini[`GradientOverlayEffect`](../../../aspose.psd.fileformats.psd.layers.layereffects/gradientoverlayeffect/) sınıf.

### Örnekler

Aşağıdaki kod, Zaman Çizelgesi çerçevelerindeki efektlerin desteğini gösterir.

```csharp
[C#]

string sourceFile = "4_animated.psd";
string outputFile = "output.psd";

using (var psdImage = (PsdImage)Image.Load(sourceFile))
{
    TimeLine timeLine = TimeLine.InitializeFrom(psdImage);
    int[] layerIds = timeLine.LayerIds;

    var layerStateEffects11 = timeLine.Frames[1].LayerStates[layerIds[1]].StateEffects;

    layerStateEffects11.AddDropShadow();
    layerStateEffects11.AddGradientOverlay();

    var layerStateEffects21 = timeLine.Frames[2].LayerStates[layerIds[1]].StateEffects;
    layerStateEffects21.AddStroke(FillType.Color);
    layerStateEffects21.IsVisible = false;

    timeLine.ApplyTo(psdImage);

    psdImage.Save(outputFile);
}
```

### Ayrıca bakınız

* class [GradientOverlayEffect](../../../aspose.psd.fileformats.psd.layers.layereffects/gradientoverlayeffect/)
* class [LayerStateEffects](../)
* ad alanı [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../layerstateeffects/)
* toplantı [Aspose.PSD](../../../)


