---
title: LayerStateEffects.AddInnerShadow
second_title: Aspose.PSD for .NET API Referansı
description: LayerStateEffects yöntem. İç gölge efekti ekler.
type: docs
weight: 60
url: /tr/net/aspose.psd.fileformats.psd.layers.animation/layerstateeffects/addinnershadow/
---
## LayerStateEffects.AddInnerShadow method

İç gölge efekti ekler.

```csharp
public InnerShadowEffect AddInnerShadow()
```

### Geri dönüş değeri

yeni örneğini[`InnerShadowEffect`](../../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/) sınıf.

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

* class [InnerShadowEffect](../../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/)
* class [LayerStateEffects](../)
* ad alanı [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../layerstateeffects/)
* toplantı [Aspose.PSD](../../../)


