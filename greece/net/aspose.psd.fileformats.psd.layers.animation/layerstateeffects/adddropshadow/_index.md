---
title: "LayerStateEffects.AddDropShadow"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Μέθοδος LayerStateEffects. Προσθέτει το εφέ σκιάς"
type: docs
weight: 40
url: /el/net/aspose.psd.fileformats.psd.layers.animation/layerstateeffects/adddropshadow/
---
{{< psd/tize >}}
## LayerStateEffects.AddDropShadow method

Προσθέτει το εφέ σκιάς απόρριψης.

```csharp
public DropShadowEffect AddDropShadow()
```

### Τιμή Επιστροφής

Η νέα παρουσία της κλάσης [`DropShadowEffect`](../../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/).

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

* class [DropShadowEffect](../../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/)
* class [LayerStateEffects](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../../)


