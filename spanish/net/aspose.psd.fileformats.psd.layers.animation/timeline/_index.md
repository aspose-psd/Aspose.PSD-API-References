---
title: "Clase Timeline"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Clase Aspose.PSD.FileFormats.Psd.Layers.Animation.Timeline. El modelo de opciones de Timeline"
type: docs
weight: 1980
url: /es/net/aspose.psd.fileformats.psd.layers.animation/timeline/
---
{{< psd/tize >}}
## Timeline class

El modelo de opciones de la línea de tiempo.

```csharp
public sealed class Timeline
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Timeline](timeline/)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [ActiveFrameIndex](../../aspose.psd.fileformats.psd.layers.animation/timeline/activeframeindex/) { get; } | Obtiene el índice del fotograma activo. |
| [AFSt](../../aspose.psd.fileformats.psd.layers.animation/timeline/afst/) { get; set; } | Obtiene o establece el valor AFSt. |
| [Frames](../../aspose.psd.fileformats.psd.layers.animation/timeline/frames/) { get; set; } | Obtiene la lista de fotogramas. |
| [FsID](../../aspose.psd.fileformats.psd.layers.animation/timeline/fsid/) { get; set; } | Obtiene o establece el valor FsID. |
| [LoopesCount](../../aspose.psd.fileformats.psd.layers.animation/timeline/loopescount/) { get; set; } | Obtiene o establece el recuento de bucles. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd.layers.animation/timeline/save/#save)(Stream, ImageOptionsBase) | Guarda los datos de PsdImage y Timeline en el flujo especificado en el formato especificado según las opciones de guardado. |
| [Save](../../aspose.psd.fileformats.psd.layers.animation/timeline/save/#save_1)(string, ImageOptionsBase) | Guarda los datos de PsdImage y Timeline en la ubicación de archivo especificada en el formato especificado según las opciones de guardado. |
| [SwitchActiveFrame](../../aspose.psd.fileformats.psd.layers.animation/timeline/switchactiveframe/)(int) | Cambia el fotograma activo al objetivo. |

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

* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../)


