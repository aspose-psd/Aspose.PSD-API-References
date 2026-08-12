---
title: "TimeLine.ApplyTo"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Método TimeLine. Aplica los valores actuales de la línea de tiempo a la PsdImage de entrada"
type: docs
weight: 90
url: /es/net/aspose.psd.fileformats.psd.layers.animation/timeline/applyto/
---
{{< psd/tize >}}
## TimeLine.ApplyTo method

Aplica los valores actuales de la línea de tiempo a la [`PsdImage`](../../../aspose.psd.fileformats.psd/psdimage/).

```csharp
public void ApplyTo(PsdImage psdImage)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| psdImage | PsdImage | La imagen psd. |

## Ejemplos

La clase TimeLine brinda una capacidad de alto nivel para manipular la línea de tiempo de PsdImage, como cambiar el retardo de fotogramas o editar el estado de la capa en un fotograma específico.

```csharp
[C#]

string sourceFile = "image1219.psd";
string outputPsd = "output_image800.psd";

using (PsdImage psdImage = (PsdImage)Image.Load(sourceFile))
{
    TimeLine timeLine = TimeLine.InitializeFrom(psdImage);

    // Cambiar el método de eliminación del fotograma 1
    timeLine.Frames[0].DisposalMethod = FrameDisposalMethod.DoNotDispose;

    // Cambiar el retardo del fotograma 2
    timeLine.Frames[1].Delay = 15;

    // Cambiar la opacidad de 'Layer 1' en el fotograma 2
    LayerState layerState11 = timeLine.Frames[1].LayerStates[timeLine.LayerIds[1]];
    layerState11.Opacity = 50;

    // Mover 'Layer 1' a la esquina inferior izquierda en el fotograma 3
    LayerState layerState21 = timeLine.Frames[2].LayerStates[timeLine.LayerIds[1]];
    layerState21.PositionOffset = new Point(-50, 230);

    // Agrega un nuevo fotograma
    List<Frame> frames = new List<Frame>(timeLine.Frames);
    frames.Add(new Frame(timeLine));
    timeLine.Frames = frames.ToArray();

    // Cambiar blendMode de 'Layer 1' en el fotograma 4
    LayerState layerState31 = timeLine.Frames[3].LayerStates[timeLine.LayerIds[1]];
    layerState31.BlendMode = BlendMode.Dissolve;

    // Aplicar los cambios a la instancia de PsdImage
    timeLine.ApplyTo(psdImage);
    psdImage.Save(outputPsd);
}
```

### Ver también

* class [PsdImage](../../../aspose.psd.fileformats.psd/psdimage/)
* class [TimeLine](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../timeline/)
* assembly [Aspose.PSD](../../../)


