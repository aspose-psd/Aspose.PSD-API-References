---
title: LayerStateEffects.AddGradientOverlay
second_title: Aspose.PSD per riferimento API .NET
description: LayerStateEffects metodo. Aggiunge leffetto di sovrapposizione sfumatura.
type: docs
weight: 50
url: /it/net/aspose.psd.fileformats.psd.layers.animation/layerstateeffects/addgradientoverlay/
---
## LayerStateEffects.AddGradientOverlay method

Aggiunge l'effetto di sovrapposizione sfumatura.

```csharp
public GradientOverlayEffect AddGradientOverlay()
```

### Valore di ritorno

La nuova istanza di[`GradientOverlayEffect`](../../../aspose.psd.fileformats.psd.layers.layereffects/gradientoverlayeffect/) classe.

### Esempi

Il codice seguente illustra il supporto degli effetti nei fotogrammi della sequenza temporale.

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

### Guarda anche

* class [GradientOverlayEffect](../../../aspose.psd.fileformats.psd.layers.layereffects/gradientoverlayeffect/)
* class [LayerStateEffects](../)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../layerstateeffects/)
* assemblea [Aspose.PSD](../../../)


