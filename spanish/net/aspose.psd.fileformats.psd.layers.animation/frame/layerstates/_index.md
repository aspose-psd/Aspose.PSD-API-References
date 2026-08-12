---
title: "Frame.LayerStates"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Propiedad Frame. Obtiene o establece los estados de capa del fotograma"
type: docs
weight: 50
url: /es/net/aspose.psd.fileformats.psd.layers.animation/frame/layerstates/
---
{{< psd/tize >}}
## Frame.LayerStates property

Obtiene o establece los estados de capa del fotograma.

```csharp
public LayerState[] LayerStates { get; set; }
```

## Ejemplos

La clase Timeline brinda una capacidad de alto nivel para manipular la línea de tiempo de PsdImage, como cambiar el retardo del fotograma o editar el estado de capa en un fotograma específico.

```csharp
[C#]

string sourceFile = "image1219.psd";
string outputPsd = "output_image800.psd";

using (PsdImage psdImage = (PsdImage)Image.Load(sourceFile))
{
    Timeline timeline = psdImage.Timeline;

    // Cambiar el método de eliminación del fotograma 1
    timeline.Frames[0].DisposalMethod = FrameDisposalMethod.DoNotDispose;

    // Cambiar el retardo del fotograma 2
    timeline.Frames[1].Delay = 15;

    // Cambiar la opacidad de 'Layer 1' en el fotograma 2
    LayerState layerState11 = timeline.Frames[1].LayerStates[1];
    layerState11.Opacity = 50;

    // Mover 'Layer 1' a la esquina inferior izquierda en el fotograma 3
    LayerState layerState21 = timeline.Frames[2].LayerStates[1];
    layerState21.PositionOffset = new Point(-50, 230);

    // Agrega un nuevo fotograma
    List<Frame> frames = new List<Frame>(timeline.Frames);
    frames.Add(new Frame());
    timeline.Frames = frames.ToArray();

    // Cambiar blendMode de 'Layer 1' en el fotograma 4
    LayerState layerState31 = timeline.Frames[3].LayerStates[1];
    layerState31.BlendMode = BlendMode.Dissolve;

    // Aplicar los cambios a la instancia de PsdImage
    psdImage.Save(outputPsd);
}
```

### Ver también

* class [LayerState](../../layerstate/)
* class [Frame](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../../)


