---
title: LayerStateEffects.AddStroke
second_title: Aspose.PSD για Αναφορά API .NET
description: LayerStateEffects μέθοδος. Προσθέτει το εφέ stroke.
type: docs
weight: 90
url: /el/net/aspose.psd.fileformats.psd.layers.animation/layerstateeffects/addstroke/
---
## LayerStateEffects.AddStroke method

Προσθέτει το εφέ stroke.

```csharp
public StrokeEffect AddStroke(FillType fillType)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fillType | FillType | Το γέμισμα τύπου stroke. |

### Επιστρεφόμενη Αξία

Το νέο παράδειγμα του[`StrokeEffect`](../../../aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/) τάξη.

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

* class [StrokeEffect](../../../aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/)
* enum [FillType](../../../aspose.psd.fileformats.psd.layers.fillsettings/filltype/)
* class [LayerStateEffects](../)
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../layerstateeffects/)
* συνέλευση [Aspose.PSD](../../../)


