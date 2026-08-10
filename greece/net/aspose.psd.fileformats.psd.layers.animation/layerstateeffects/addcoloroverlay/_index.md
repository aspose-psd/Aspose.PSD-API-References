---
title: "LayerStateEffects.AddColorOverlay"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Μέθοδος LayerStateEffects. Προσθέτει το εφέ χρωματικής επικάλυψης"
type: docs
weight: 30
url: /el/net/aspose.psd.fileformats.psd.layers.animation/layerstateeffects/addcoloroverlay/
---
{{< psd/tize >}}
## LayerStateEffects.AddColorOverlay method

Προσθέτει το εφέ επικάλυψης χρώματος.

```csharp
public ColorOverlayEffect AddColorOverlay()
```

### Τιμή Επιστροφής

Η νέα παρουσία της κλάσης [`ColorOverlayEffect`](../../../aspose.psd.fileformats.psd.layers.layereffects/coloroverlayeffect/).

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει την υποστήριξη εφέ στα πλαίσια Timeline.

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

### Δείτε επίσης

* class [ColorOverlayEffect](../../../aspose.psd.fileformats.psd.layers.layereffects/coloroverlayeffect/)
* class [LayerStateEffects](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../../)


