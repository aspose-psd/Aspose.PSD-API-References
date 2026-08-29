---
title: "Timeline.ActiveFrameIndex"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Propriété Timeline. Obtient l'index de la frame active"
type: docs
weight: 20
url: /fr/net/aspose.psd.fileformats.psd.layers.animation/timeline/activeframeindex/
---
{{< psd/tize >}}
## Timeline.ActiveFrameIndex property

Obtient l'index du cadre actif.

```csharp
public int ActiveFrameIndex { get; }
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

* class [Timeline](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../../)


