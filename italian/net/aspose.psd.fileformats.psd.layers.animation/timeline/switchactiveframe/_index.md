---
title: "Timeline.SwitchActiveFrame"
second_title: "Riferimento API Aspose.PSD per .NET"
description: "Metodo Timeline. Cambia il fotogramma attivo a quello destinato"
type: docs
weight: 80
url: /it/net/aspose.psd.fileformats.psd.layers.animation/timeline/switchactiveframe/
---
{{< psd/tize >}}
## Timeline.SwitchActiveFrame method

Cambia il fotogramma attivo a quello destinato.

```csharp
public void SwitchActiveFrame(int targetActiveFrameIndex)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| targetActiveFrameIndex | Int32 | L'indice del fotogramma di destinazione. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| IndexOutOfRangeException | Il nuovo indice del fotogramma attivo deve rientrare nell'intervallo del conteggio dei fotogrammi. |

## Esempi

Il codice seguente dimostra un nuovo approccio per lavorare con la Timeline.

```csharp
[C#]

string sourceFile = "4_animated.psd";
string outputFile = "output_edited.psd";

using (var psdImage = (PsdImage)Image.Load(sourceFile))
{
    Timeline timeline = psdImage.Timeline;
    
    // Aggiungi un altro fotogramma
    List<Frame> frames = new List<Frame>(timeline.Frames);
    frames.Add(new Frame());
    timeline.Frames = frames.ToArray();

    timeline.SwitchActiveFrame(4);

    psdImage.Save(outputFile);
}
```

### Vedi anche

* class [Timeline](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../../)


