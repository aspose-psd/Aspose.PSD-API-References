---
title: "Timeline.ActiveFrameIndex"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Propiedad Timeline. Obtiene el índice del fotograma activo"
type: docs
weight: 20
url: /es/net/aspose.psd.fileformats.psd.layers.animation/timeline/activeframeindex/
---
{{< psd/tize >}}
## Timeline.ActiveFrameIndex property

Obtiene el índice del fotograma activo.

```csharp
public int ActiveFrameIndex { get; }
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

* class [Timeline](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../../)


