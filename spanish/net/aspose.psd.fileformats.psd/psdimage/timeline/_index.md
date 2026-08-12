---
title: "PsdImage.Timeline"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Propiedad de PsdImage. Obtiene la línea de tiempo de este PsdImage"
type: docs
weight: 250
url: /es/net/aspose.psd.fileformats.psd/psdimage/timeline/
---
{{< psd/tize >}}
## PsdImage.Timeline property

Obtiene la `Timeline` de este [`PsdImage`](../).

```csharp
public Timeline Timeline { get; }
```

## Ejemplos

El siguiente código demuestra un nuevo enfoque para trabajar con el Timeline.

```csharp
[C#]

string sourceFile = "4_animated.psd";
string outputFile = "output_edited.psd";

using (var psdImage = (PsdImage)Image.Load(sourceFile))
{
    Timeline timeline = psdImage.Timeline;
    
    // Agregar un fotograma más
    List<Frame> frames = new List<Frame>(timeline.Frames);
    frames.Add(new Frame());
    timeline.Frames = frames.ToArray();

    timeline.SwitchActiveFrame(4);

    psdImage.Save(outputFile);
}
```

### Ver también

* class [Timeline](../../../aspose.psd.fileformats.psd.layers.animation/timeline/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


