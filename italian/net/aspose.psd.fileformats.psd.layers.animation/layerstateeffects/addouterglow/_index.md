---
title: LayerStateEffects.AddOuterGlow
second_title: Aspose.PSD per riferimento API .NET
description: LayerStateEffects metodo. Aggiunge leffetto bagliore esterno.
type: docs
weight: 70
url: /it/net/aspose.psd.fileformats.psd.layers.animation/layerstateeffects/addouterglow/
---
## LayerStateEffects.AddOuterGlow method

Aggiunge l'effetto bagliore esterno.

```csharp
public OuterGlowEffect AddOuterGlow()
```

### Valore di ritorno

La nuova istanza di[`OuterGlowEffect`](../../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/) classe.

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

* class [OuterGlowEffect](../../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/)
* class [LayerStateEffects](../)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../layerstateeffects/)
* assemblea [Aspose.PSD](../../../)


