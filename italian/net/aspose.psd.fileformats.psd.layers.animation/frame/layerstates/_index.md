---
title: Frame.LayerStates
second_title: Aspose.PSD per riferimento API .NET
description: Frame proprietà. Ottiene o imposta gli stati del livello del fotogramma.
type: docs
weight: 50
url: /it/net/aspose.psd.fileformats.psd.layers.animation/frame/layerstates/
---
## Frame.LayerStates property

Ottiene o imposta gli stati del livello del fotogramma.

```csharp
public Dictionary<int, LayerState> LayerStates { get; }
```

### Esempi

La classe TimeLine offre una capacità di alto livello per manipolare la sequenza temporale di PsdImage, come modificare il ritardo del fotogramma o modificare lo stato del livello su un fotogramma specifico.

```csharp
[C#]

string sourceFile = "image1219.psd";
string outputPsd = "output_image800.psd";

using (PsdImage psdImage = (PsdImage)Image.Load(sourceFile))
{
    TimeLine timeLine = TimeLine.InitializeFrom(psdImage);

    // Cambia il metodo dispose del frame 1
    timeLine.Frames[0].DisposalMethod = FrameDisposalMethod.DoNotDispose;

    // Modifica il ritardo del frame 2
    timeLine.Frames[1].Delay = 15;

    // Modifica l'opacità di "Livello 1" sul fotogramma 2
    LayerState layerState11 = timeLine.Frames[1].LayerStates[timeLine.LayerIds[1]];
    layerState11.Opacity = 50;

    // sposta 'Livello 1' nell'angolo inferiore sinistro del fotogramma 3
    LayerState layerState21 = timeLine.Frames[2].LayerStates[timeLine.LayerIds[1]];
    layerState21.PositionOffset = new Point(-50, 230);

    // Aggiunge un nuovo frame
    List<Frame> frames = new List<Frame>(timeLine.Frames);
    frames.Add(new Frame(timeLine));
    timeLine.Frames = frames.ToArray();

    // Cambia blendMode di 'Layer 1' sul fotogramma 4
    LayerState layerState31 = timeLine.Frames[3].LayerStates[timeLine.LayerIds[1]];
    layerState31.BlendMode = BlendMode.Dissolve;

    // Applica le modifiche all'istanza PsdImage
    timeLine.ApplyTo(psdImage);
    psdImage.Save(outputPsd);
}
```

### Guarda anche

* class [LayerState](../../layerstate/)
* class [Frame](../)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../frame/)
* assemblea [Aspose.PSD](../../../)


