---
title: Class LayerState
second_title: Referencia de API de Aspose.PSD para .NET
description: Aspose.PSD.FileFormats.Psd.Layers.Animation.LayerState clase. Las opciones de estado de la capa de línea de tiempo.
type: docs
weight: 1860
url: /es/net/aspose.psd.fileformats.psd.layers.animation/layerstate/
---
## LayerState class

Las opciones de estado de la capa de línea de tiempo.

```csharp
public sealed class LayerState
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [LayerState](layerstate/)(int) | Inicializa una nueva instancia del`LayerState` clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.animation/layerstate/blendmode/) { get; set; } | Obtiene o establece el modo combinado. |
| [Enabled](../../aspose.psd.fileformats.psd.layers.animation/layerstate/enabled/) { get; set; } | Obtiene o establece el estado habilitado. |
| [FillOpacity](../../aspose.psd.fileformats.psd.layers.animation/layerstate/fillopacity/) { get; set; } | Obtiene o establece el valor de opacidad de relleno. |
| [HorizontalFXRf](../../aspose.psd.fileformats.psd.layers.animation/layerstate/horizontalfxrf/) { get; set; } | Obtiene o establece el valor HorizontalFXRf. |
| [Id](../../aspose.psd.fileformats.psd.layers.animation/layerstate/id/) { get; set; } | Obtiene o establece el id. |
| [Opacity](../../aspose.psd.fileformats.psd.layers.animation/layerstate/opacity/) { get; set; } | Obtiene o establece el valor de opacidad. |
| [PositionOffset](../../aspose.psd.fileformats.psd.layers.animation/layerstate/positionoffset/) { get; set; } | Obtiene o establece el desplazamiento de la posición de la capa en relación con la posición real de la capa. |
| [StateEffects](../../aspose.psd.fileformats.psd.layers.animation/layerstate/stateeffects/) { get; } | Obtiene los efectos del estado de la capa. |
| [VerticalFXRf](../../aspose.psd.fileformats.psd.layers.animation/layerstate/verticalfxrf/) { get; set; } | Obtiene o establece el valor de VerticalFXRf. |

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


