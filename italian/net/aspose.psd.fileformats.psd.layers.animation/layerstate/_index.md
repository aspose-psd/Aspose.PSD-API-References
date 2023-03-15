---
title: Class LayerState
second_title: Aspose.PSD per riferimento API .NET
description: Aspose.PSD.FileFormats.Psd.Layers.Animation.LayerState classe. Le opzioni dello stato del livello della linea del tempo.
type: docs
weight: 1860
url: /it/net/aspose.psd.fileformats.psd.layers.animation/layerstate/
---
## LayerState class

Le opzioni dello stato del livello della linea del tempo.

```csharp
public sealed class LayerState
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [LayerState](layerstate/)(int) | Inizializza una nuova istanza di`LayerState` classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.animation/layerstate/blendmode/) { get; set; } | Ottiene o imposta la modalità blen. |
| [Enabled](../../aspose.psd.fileformats.psd.layers.animation/layerstate/enabled/) { get; set; } | Ottiene o imposta lo stato abilitato. |
| [FillOpacity](../../aspose.psd.fileformats.psd.layers.animation/layerstate/fillopacity/) { get; set; } | Ottiene o imposta il valore di opacità del riempimento. |
| [HorizontalFXRf](../../aspose.psd.fileformats.psd.layers.animation/layerstate/horizontalfxrf/) { get; set; } | Ottiene o imposta il valore HorizontalFXRf. |
| [Id](../../aspose.psd.fileformats.psd.layers.animation/layerstate/id/) { get; set; } | Ottiene o imposta l'id. |
| [Opacity](../../aspose.psd.fileformats.psd.layers.animation/layerstate/opacity/) { get; set; } | Ottiene o imposta il valore di opacità. |
| [PositionOffset](../../aspose.psd.fileformats.psd.layers.animation/layerstate/positionoffset/) { get; set; } | Ottiene o imposta l'offset della posizione del layer relativo alla posizione effettiva del layer. |
| [StateEffects](../../aspose.psd.fileformats.psd.layers.animation/layerstate/stateeffects/) { get; } | Ottiene gli effetti dello stato del livello. |
| [VerticalFXRf](../../aspose.psd.fileformats.psd.layers.animation/layerstate/verticalfxrf/) { get; set; } | Ottiene o imposta il valore VerticalFXRf. |

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

* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../aspose.psd.fileformats.psd.layers.animation/)
* assemblea [Aspose.PSD](../../)


