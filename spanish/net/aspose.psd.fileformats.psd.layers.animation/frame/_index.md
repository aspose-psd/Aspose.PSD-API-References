---
title: Class Frame
second_title: Referencia de API de Aspose.PSD para .NET
description: Aspose.PSD.FileFormats.Psd.Layers.Animation.Frame clase. Las opciones del elemento de marco de línea de tiempo.
type: docs
weight: 1840
url: /es/net/aspose.psd.fileformats.psd.layers.animation/frame/
---
## Frame class

Las opciones del elemento de marco de línea de tiempo.

```csharp
public sealed class Frame
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Frame](frame/)(TimeLine) | Inicializa una nueva instancia del`Frame` clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Delay](../../aspose.psd.fileformats.psd.layers.animation/frame/delay/) { get; set; } | Obtiene o establece el valor de retardo de cuadro en centa-segundos. Por ejemplo, en 1 segundo contiene 100 centa-segundos. |
| [DisposalMethod](../../aspose.psd.fileformats.psd.layers.animation/frame/disposalmethod/) { get; set; } | Obtiene o establece el método de eliminación de frame. |
| [Id](../../aspose.psd.fileformats.psd.layers.animation/frame/id/) { get; set; } | Obtiene o establece el marco id. |
| [LayerStates](../../aspose.psd.fileformats.psd.layers.animation/frame/layerstates/) { get; } | Obtiene o establece los estados de capa del marco. |

### Ejemplos

La clase TimeLine brinda una capacidad de alto nivel para manipular la línea de tiempo de PsdImage, como cambiar el retraso del cuadro o editar el estado de la capa en un cuadro específico.

```csharp
[C#]

string sourceFile = "image1219.psd";
string outputPsd = "output_image800.psd";

using (PsdImage psdImage = (PsdImage)Image.Load(sourceFile))
{
    TimeLine timeLine = TimeLine.InitializeFrom(psdImage);

    // Cambiar el método de eliminación del cuadro 1
    timeLine.Frames[0].DisposalMethod = FrameDisposalMethod.DoNotDispose;

    // Cambiar el retraso del cuadro 2
    timeLine.Frames[1].Delay = 15;

    // Cambiar la opacidad de 'Layer 1' en el cuadro 2
    LayerState layerState11 = timeLine.Frames[1].LayerStates[timeLine.LayerIds[1]];
    layerState11.Opacity = 50;

    // mover 'Capa 1' a la esquina inferior izquierda en el cuadro 3
    LayerState layerState21 = timeLine.Frames[2].LayerStates[timeLine.LayerIds[1]];
    layerState21.PositionOffset = new Point(-50, 230);

    // Agrega un nuevo marco
    List<Frame> frames = new List<Frame>(timeLine.Frames);
    frames.Add(new Frame(timeLine));
    timeLine.Frames = frames.ToArray();

    // Cambiar blendMode de 'Layer 1' en el cuadro 4
    LayerState layerState31 = timeLine.Frames[3].LayerStates[timeLine.LayerIds[1]];
    layerState31.BlendMode = BlendMode.Dissolve;

    // Aplicar los cambios de nuevo a la instancia de PsdImage
    timeLine.ApplyTo(psdImage);
    psdImage.Save(outputPsd);
}
```

### Ver también

* espacio de nombres [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../aspose.psd.fileformats.psd.layers.animation/)
* asamblea [Aspose.PSD](../../)


