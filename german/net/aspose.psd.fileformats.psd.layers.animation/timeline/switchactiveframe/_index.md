---
title: "Timeline.SwitchActiveFrame"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Timeline-Methode. Schaltet das aktive Bild auf das Ziel um."
type: docs
weight: 80
url: /de/net/aspose.psd.fileformats.psd.layers.animation/timeline/switchactiveframe/
---
{{< psd/tize >}}
## Timeline.SwitchActiveFrame method

Wechselt den aktiven Frame zum Ziel-Frame.

```csharp
public void SwitchActiveFrame(int targetActiveFrameIndex)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| targetActiveFrameIndex | Int32 | Der Index des Zielbildes. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| IndexOutOfRangeException | Der neue Index des aktiven Bildes muss im Bereich der Bildanzahl liegen. |

## Beispiele

Der folgende Code demonstriert einen neuen Ansatz zur Arbeit mit der Timeline.

```csharp
[C#]

string sourceFile = "4_animated.psd";
string outputFile = "output_edited.psd";

using (var psdImage = (PsdImage)Image.Load(sourceFile))
{
    Timeline timeline = psdImage.Timeline;
    
    // Ein weiteres Bild hinzufügen
    List<Frame> frames = new List<Frame>(timeline.Frames);
    frames.Add(new Frame());
    timeline.Frames = frames.ToArray();

    timeline.SwitchActiveFrame(4);

    psdImage.Save(outputFile);
}
```

### Siehe auch

* class [Timeline](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../../)


