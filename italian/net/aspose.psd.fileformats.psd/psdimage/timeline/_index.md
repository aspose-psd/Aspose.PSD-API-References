---
title: "PsdImage.Timeline"
second_title: "Riferimento API Aspose.PSD per .NET"
description: "Proprietà PsdImage. Ottiene la Timeline di questo PsdImage"
type: docs
weight: 250
url: /it/net/aspose.psd.fileformats.psd/psdimage/timeline/
---
{{< psd/tize >}}
## PsdImage.Timeline property

Ottiene la `Timeline` di questo [`PsdImage`](../).

```csharp
public Timeline Timeline { get; }
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

* class [Timeline](../../../aspose.psd.fileformats.psd.layers.animation/timeline/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


