---
title: "PsdImage.Timeline"
second_title: "Aspose.PSD voor .NET API-referentie"
description: "PsdImage-eigenschap. Haalt de Timeline van deze PsdImage op."
type: docs
weight: 250
url: /nl/net/aspose.psd.fileformats.psd/psdimage/timeline/
---
{{< psd/tize >}}
## PsdImage.Timeline property

Haalt de `Timeline` van deze [`PsdImage`](../) op.

```csharp
public Timeline Timeline { get; }
```

## Voorbeelden

De volgende code toont een nieuwe benadering om met de Timeline te werken.

```csharp
[C#]

string sourceFile = "4_animated.psd";
string outputFile = "output_edited.psd";

using (var psdImage = (PsdImage)Image.Load(sourceFile))
{
    Timeline timeline = psdImage.Timeline;
    
    // Voeg nog een frame toe
    List<Frame> frames = new List<Frame>(timeline.Frames);
    frames.Add(new Frame());
    timeline.Frames = frames.ToArray();

    timeline.SwitchActiveFrame(4);

    psdImage.Save(outputFile);
}
```

### Zie ook

* class [Timeline](../../../aspose.psd.fileformats.psd.layers.animation/timeline/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


