---
title: "Timeline.SwitchActiveFrame"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Método Timeline. Cambia el fotograma activo al objetivo"
type: docs
weight: 80
url: /es/net/aspose.psd.fileformats.psd.layers.animation/timeline/switchactiveframe/
---
{{< psd/tize >}}
## Timeline.SwitchActiveFrame method

Cambia el fotograma activo al objetivo.

```csharp
public void SwitchActiveFrame(int targetActiveFrameIndex)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| targetActiveFrameIndex | Int32 | El índice del fotograma objetivo. |

### Excepciones

| excepción | condición |
| --- | --- |
| IndexOutOfRangeException | El nuevo índice del fotograma activo debe estar dentro del rango del recuento de fotogramas. |

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


