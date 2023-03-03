---
title: Enum FrameDisposalMethod
second_title: Aspose.PSD per riferimento API .NET
description: Aspose.PSD.FileFormats.Psd.Layers.Animation.FrameDisposalMethod enum. Il metodo di eliminazione del fotogramma specifica se eliminare il fotogramma corrente prima di visualizzare il fotogramma successivo. Seleziona un metodo di eliminazione per le animazioni che includono la trasparenza dello sfondo per specificare se il fotogramma corrente sarà visibile attraverso le aree trasparenti del fotogramma successivo.
type: docs
weight: 1850
url: /it/net/aspose.psd.fileformats.psd.layers.animation/framedisposalmethod/
---
## FrameDisposalMethod enumeration

Il metodo di eliminazione del fotogramma specifica se eliminare il fotogramma corrente prima di visualizzare il fotogramma successivo. Seleziona un metodo di eliminazione per le animazioni che includono la trasparenza dello sfondo per specificare se il fotogramma corrente sarà visibile attraverso le aree trasparenti del fotogramma successivo.

```csharp
public enum FrameDisposalMethod
```

### I valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| Automatic | `0` | Determina automaticamente un metodo di eliminazione per il fotogramma corrente, scartando il fotogramma corrente se il fotogramma successivo contiene trasparenza del livello. Per la maggior parte delle animazioni, l'opzione Automatico (impostazione predefinita) produce i risultati desiderati. |
| DoNotDispose | `1` | Conserva il fotogramma corrente quando il fotogramma successivo viene aggiunto al display. Il fotogramma corrente (e i fotogrammi precedenti) possono essere visualizzati attraverso aree trasparenti del fotogramma successivo. |
| Dispose | `2` | Scarta il fotogramma corrente dal display prima che venga visualizzato il fotogramma successivo. Viene visualizzato un solo fotogramma alla volta (e il fotogramma corrente non appare attraverso le aree trasparenti del fotogramma successivo). |

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


