---
title: LayerStateEffects.AddDropShadow
second_title: Aspose.PSD για Αναφορά API .NET
description: LayerStateEffects μέθοδος. Προσθέτει το εφέ drop shadow.
type: docs
weight: 40
url: /el/net/aspose.psd.fileformats.psd.layers.animation/layerstateeffects/adddropshadow/
---
## LayerStateEffects.AddDropShadow method

Προσθέτει το εφέ drop shadow.

```csharp
public DropShadowEffect AddDropShadow()
```

### Επιστρεφόμενη Αξία

Το νέο παράδειγμα του[`DropShadowEffect`](../../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/) τάξη.

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

* class [DropShadowEffect](../../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/)
* class [LayerStateEffects](../)
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../layerstateeffects/)
* συνέλευση [Aspose.PSD](../../../)


