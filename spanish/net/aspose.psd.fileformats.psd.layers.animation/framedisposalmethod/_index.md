---
title: "Enumeración FrameDisposalMethod"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Aspose.PSD.FileFormats.Psd.Layers.Animation.FrameDisposalMethod enumeración. El método de eliminación del fotograma especifica si se debe descartar el fotograma actual antes de mostrar el siguiente fotograma. Selecciona un método de eliminación para animaciones que incluyen transparencia de fondo para especificar si el fotograma actual será visible a través de las áreas transparentes del siguiente fotograma."
type: docs
weight: 1950
url: /es/net/aspose.psd.fileformats.psd.layers.animation/framedisposalmethod/
---
{{< psd/tize >}}
## FrameDisposalMethod enumeration

El método de eliminación de fotogramas especifica si se debe descartar el fotograma actual antes de mostrar el siguiente fotograma. Selecciona un método de eliminación para animaciones que incluyen transparencia de fondo para especificar si el fotograma actual será visible a través de las áreas transparentes del siguiente fotograma.

```csharp
public enum FrameDisposalMethod
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Automatic | `0` | Determina automáticamente un método de eliminación para el fotograma actual, descartando el fotograma actual si el siguiente fotograma contiene transparencia de capa. Para la mayoría de las animaciones, la opción Automático (predeterminada) produce los resultados deseados. |
| DoNotDispose | `1` | Preserva el fotograma actual mientras se agrega el siguiente fotograma a la pantalla. El fotograma actual (y los fotogramas anteriores) pueden mostrarse a través de áreas transparentes del siguiente fotograma. |
| Dispose | `2` | Descarta el fotograma actual de la pantalla antes de que se muestre el siguiente fotograma. Solo se muestra un fotograma a la vez (y el fotograma actual no aparece a través de las áreas transparentes del siguiente fotograma). |

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


