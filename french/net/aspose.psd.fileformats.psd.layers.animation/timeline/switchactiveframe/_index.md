---
title: "Timeline.SwitchActiveFrame"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Méthode Timeline. Bascule le cadre actif vers le cadre ciblé"
type: docs
weight: 80
url: /fr/net/aspose.psd.fileformats.psd.layers.animation/timeline/switchactiveframe/
---
{{< psd/tize >}}
## Timeline.SwitchActiveFrame method

Bascule le cadre actif vers la cible.

```csharp
public void SwitchActiveFrame(int targetActiveFrameIndex)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| targetActiveFrameIndex | Int32 | L'index du cadre cible. |

### Exceptions

| exception | condition |
| --- | --- |
| IndexOutOfRangeException | Le nouvel index du cadre actif doit être dans la plage du nombre de cadres. |

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


