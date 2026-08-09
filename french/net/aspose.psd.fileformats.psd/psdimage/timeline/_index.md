---
title: "PsdImage.Timeline"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Propriété PsdImage. Obtient la chronologie de ce PsdImage"
type: docs
weight: 250
url: /fr/net/aspose.psd.fileformats.psd/psdimage/timeline/
---
{{< psd/tize >}}
## PsdImage.Timeline property

Obtient le `Timeline` de ce [`PsdImage`](../).

```csharp
public Timeline Timeline { get; }
```

## Exemples

Le code suivant montre une nouvelle approche pour travailler avec le Timeline.

```csharp
[C#]

string sourceFile = "4_animated.psd";
string outputFile = "output_edited.psd";

using (var psdImage = (PsdImage)Image.Load(sourceFile))
{
    Timeline timeline = psdImage.Timeline;
    
    // Ajouter une autre frame
    List<Frame> frames = new List<Frame>(timeline.Frames);
    frames.Add(new Frame());
    timeline.Frames = frames.ToArray();

    timeline.SwitchActiveFrame(4);

    psdImage.Save(outputFile);
}
```

### Voir aussi

* class [Timeline](../../../aspose.psd.fileformats.psd.layers.animation/timeline/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


