---
title: "LayerStateEffects.AddStroke"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Μέθοδος LayerStateEffects. Προσθέτει το εφέ γραμμής"
type: docs
weight: 90
url: /el/net/aspose.psd.fileformats.psd.layers.animation/layerstateeffects/addstroke/
---
{{< psd/tize >}}
## LayerStateEffects.AddStroke method

Προσθέτει το εφέ γραμμής.

```csharp
public StrokeEffect AddStroke(FillType fillType)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fillType | FillType | Ο τύπος γεμίσματος γραμμής. |

### Τιμή Επιστροφής

Η νέα παρουσία της κλάσης [`StrokeEffect`](../../../aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/).

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

* class [StrokeEffect](../../../aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/)
* enum [FillType](../../../aspose.psd.fileformats.psd.layers.fillsettings/filltype/)
* class [LayerStateEffects](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../../)


