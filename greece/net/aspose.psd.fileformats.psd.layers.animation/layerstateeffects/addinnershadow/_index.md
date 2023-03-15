---
title: LayerStateEffects.AddInnerShadow
second_title: Aspose.PSD για Αναφορά API .NET
description: LayerStateEffects μέθοδος. Προσθέτει το εφέ εσωτερικής σκιάς.
type: docs
weight: 60
url: /el/net/aspose.psd.fileformats.psd.layers.animation/layerstateeffects/addinnershadow/
---
## LayerStateEffects.AddInnerShadow method

Προσθέτει το εφέ εσωτερικής σκιάς.

```csharp
public InnerShadowEffect AddInnerShadow()
```

### Επιστρεφόμενη Αξία

Το νέο παράδειγμα του[`InnerShadowEffect`](../../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/) τάξη.

### Παραδείγματα

Ο ακόλουθος κώδικας δείχνει την υποστήριξη των εφέ σε πλαίσια Timeline.

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

### Δείτε επίσης

* class [InnerShadowEffect](../../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/)
* class [LayerStateEffects](../)
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../layerstateeffects/)
* συνέλευση [Aspose.PSD](../../../)


