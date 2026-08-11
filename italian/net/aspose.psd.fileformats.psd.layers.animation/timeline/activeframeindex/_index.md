---
title: "Timeline.ActiveFrameIndex"
second_title: "Riferimento API Aspose.PSD per .NET"
description: "Proprietà Timeline. Ottiene l'indice del fotogramma attivo"
type: docs
weight: 20
url: /it/net/aspose.psd.fileformats.psd.layers.animation/timeline/activeframeindex/
---
{{< psd/tize >}}
## Timeline.ActiveFrameIndex property

Ottiene l'indice del fotogramma attivo.

```csharp
public int ActiveFrameIndex { get; }
```

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


